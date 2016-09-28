#### Test 870929456b1b86b_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-28 06:46:49.290   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 06:46:49.290   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 06:46:49.802  5625  5625 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-28 06:46:49.807  5625  5625 D AndroidRuntime: CheckJNI is OFF
09-28 06:46:49.835  5625  5625 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-28 06:46:49.868   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
09-28 06:46:49.877  5625  5625 I Radio-JNI: register_android_hardware_Radio DONE
09-28 06:46:49.894  5625  5625 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-28 06:46:49.899   927  3413 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-28 06:46:49.940   927  3413 I ActivityManager: Start proc 5634:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-28 06:46:49.956  5625  5625 D AndroidRuntime: Shutting down VM
,09-28 06:46:50.279   927  3153 I WindowManager: Screenshot max retries 4 of Token{4a23589 ActivityRecord{59c8890 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{590d9a8 u0 Starting com.test.thalitest} drawState=2
,09-28 06:46:50.349  5634  5634 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-28 06:46:50.382  5634  5634 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-28 06:46:50.409  5634  5634 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 241-261)
,09-28 06:46:50.409  5634  5634 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-28 06:46:50.428  5634  5634 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {91bce28}
,09-28 06:46:50.429  5634  5634 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-28 06:46:50.429  5634  5634 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-28 06:46:50.435  5634  5634 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-28 06:46:50.436  5634  5634 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-28 06:46:50.471  5634  5634 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-28 06:46:50.484  5634  5634 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-28 06:46:50.484  5634  5634 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-28 06:46:50.484  5634  5634 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-28 06:46:50.484  5634  5634 I Adreno  : Build Date                       : 12/06/15
09-28 06:46:50.484  5634  5634 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-28 06:46:50.484  5634  5634 I Adreno  : Local Branch                     : mybranch17112971
09-28 06:46:50.484  5634  5634 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-28 06:46:50.484  5634  5634 I Adreno  : Remote Branch                    : NONE
09-28 06:46:50.484  5634  5634 I Adreno  : Reconstruct Branch               : NOTHING
,09-28 06:46:50.536   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d0a289f:true
,09-28 06:46:50.571   405   405 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25467]" dev="sockfs" ino=25467 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 06:46:50.571   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[25467]" dev="sockfs" ino=25467 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 06:46:50.584  5634  5634 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-28 06:46:50.594  5634  5634 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-28 06:46:50.624   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33657]" dev="sockfs" ino=33657 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 06:46:50.624   405   405 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33657]" dev="sockfs" ino=33657 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-28 06:46:50.624  5634  5671 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-28 06:46:50.627  3153  3153 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[25471]" dev="sockfs" ino=25471 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 06:46:50.627  3153  3153 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[25471]" dev="sockfs" ino=25471 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 06:46:50.632  5634  5658 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-28 06:46:50.656  5634  5671 I OpenGLRenderer: Initialized EGL, version 1.4
,09-28 06:46:50.733   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +450ms (total +820ms)
,09-28 06:46:50.760  5634  5634 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5634
,09-28 06:46:50.886  5634  5634 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-28 06:46:50.968  5634  5674 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -578811600
,09-28 06:46:50.972  5634  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-28 06:46:50.972  5634  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-28 06:46:50.972  5634  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-28 06:46:50.972  5634  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-28 06:46:50.972  5634  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-28 06:46:50.972  5634  5674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85c157e added. We now have 1 listener(s)
,09-28 06:46:50.975  5634  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-28 06:46:50.975  5634  5674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 06:46:50.975  5634  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 06:46:50.976  5634  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-28 06:46:50.978  5634  5674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6de1f5 added. We now have 1 listener(s)
09-28 06:46:50.978  5634  5674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:46:50.983   927  3010 D WifiService: New client listening to asynchronous messages
,09-28 06:46:50.983  5634  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 06:46:50.983  5634  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-28 06:46:50.983  5634  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-28 06:46:50.983  5634  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-28 06:46:50.983  5634  5674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-28 06:46:50.985  5634  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:46:50.985  5634  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-28 06:46:50.989  5634  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:46:50.989  5634  5674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:46:50.989  5634  5674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-28 06:46:50.989  5634  5674 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:46:50.990  5634  5674 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-28 06:46:50.991  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:46:50.994  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:46:51.061  5634  5634 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-28 06:46:51.275  5634  5680 W jxcore-log: Initializing JXcore engine
09-28 06:46:51.275  5634  5680 W jxcore-log: JXcore engine is ready
,09-28 06:46:51.304  5680  5680 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10914 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-28 06:46:51.304  5680  5680 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13664]" dev="sockfs" ino=13664 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-28 06:46:51.304  5680  5680 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-28 06:46:51.304  5680  5680 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32584]" dev="sockfs" ino=32584 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-28 06:46:51.311  5634  5680 W jxcore-log: Starting JXcore engine
,09-28 06:46:51.376  5634  5680 W jxcore-log: Platform android
09-28 06:46:51.376  5634  5680 W jxcore-log: 
,09-28 06:46:51.376  5634  5680 W jxcore-log: Process ARCH arm
09-28 06:46:51.376  5634  5680 W jxcore-log: 
,09-28 06:46:51.475  5634  5680 I jxcore-log: JXcore Cordova bridge is ready!
09-28 06:46:51.475  5634  5680 I jxcore-log: 
,09-28 06:46:51.475  5634  5680 W jxcore-log: JXcore engine is started
,09-28 06:46:51.491  5634  5674 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-28 06:46:51.497  5634  5634 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-28 06:46:59.291   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:00.292   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:01.294   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:01.352  5634  5680 I jxcore-log: 2016-09-28 10:47:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 06:47:01.352  5634  5680 I jxcore-log: 
,09-28 06:47:01.354  5634  5680 I jxcore-log: 2016-09-28 10:47:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 06:47:01.354  5634  5680 I jxcore-log: 
,09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:01.359  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:47:01.361  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:47:01.363  5634  5680 I jxcore-log: 2016-09-28 10:47:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 06:47:01.363  5634  5680 I jxcore-log: 
,09-28 06:47:01.365  5634  5680 I jxcore-log: 2016-09-28 10:47:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 06:47:01.365  5634  5680 I jxcore-log: 
,09-28 06:47:01.620  5634  5680 I jxcore-log: 2016-09-28 10:47:01 - DEBUG UnitTest_app: 'Running unit tests'
09-28 06:47:01.620  5634  5680 I jxcore-log: 
,09-28 06:47:01.621  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 06:47:01.621  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fa04be added. We now have 2 listener(s)
,09-28 06:47:01.622  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 06:47:01.622  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 06:47:01.622  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 06:47:01.622  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:47:01.622  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ada191f added. We now have 2 listener(s)
,09-28 06:47:01.622  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 06:47:01.623  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 06:47:01.625  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:01.628  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:47:01.629  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:47:01.629  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:47:01.629  5634  5680 D executeNativeTests: Running unit tests
,09-28 06:47:01.634  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:01.639  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:01.667  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 06:47:01.667  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 added. We now have 3 listener(s)
,09-28 06:47:01.668  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 06:47:01.668  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 06:47:01.668  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 06:47:01.668  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:47:01.668  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a added. We now have 3 listener(s)
,09-28 06:47:01.668  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 06:47:01.668  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 06:47:01.670  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:01.672  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:47:01.673  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:01.673  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:47:01.674  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 06:47:01.675  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 06:47:01.675  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 06:47:01.675  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 06:47:01.675  5634  5680 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-28 06:47:01.675  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 06:47:01.675  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 06:47:01.676  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 06:47:01.676  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 06:47:01.676  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 06:47:01.676  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:01.676  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:01.676  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:01.676  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:01.676  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.676  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:01.676  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 06:47:01.676  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 removed from the list
09-28 06:47:01.676  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:47:01.676  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a removed from the list
09-28 06:47:01.682  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:01.687  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:01.688  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:01.688  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.688  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.688  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.689  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 06:47:01.689  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:01.689  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:01.689  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:01.690  5634  5680 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-28 06:47:01.690  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:01.690  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:01.690  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:01.690  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:01.690  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.690  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.690  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:01.690  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:01.690  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:01.690  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 06:47:01.690  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.690  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.690  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.690  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.691  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:01.691  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:01.691  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:01.691  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:01.693  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 06:47:01.693  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 06:47:01.694  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 06:47:01.694  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:01.694  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:01.694  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:01.695  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:01.695  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.695  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.695  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:01.695  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:01.695  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:01.695  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:01.695  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.695  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.695  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:01.695  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:01.695  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:01.695  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:01.695  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:01.695  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:01.696  5634  5680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 06:47:01.697  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:01.699  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:47:01.700  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:01.700  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:47:01.700  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:47:01.700  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 06:47:01.700  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 06:47:01.700  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:47:01.700  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:47:01.705  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:47:01.705  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 06:47:01.705  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:01.707  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 06:47:01.708  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:47:01.708  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:47:01.710  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:01.711  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-28 06:47:01.712  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-28 06:47:01.712  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 06:47:01.713  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 06:47:01.713  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 06:47:01.713  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:47:01.716  4611  4630 D BtGatt.GattService: registerClient() - UUID=d549e757-de9a-4d92-9fd4-7f9745677e69
,09-28 06:47:01.717  4611  4691 D BtGatt.GattService: onClientRegistered() - UUID=d549e757-de9a-4d92-9fd4-7f9745677e69, clientIf=5
,09-28 06:47:01.718  5634  5644 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 06:47:01.719  4611  4854 D BtGatt.GattService: start scan with filters
,09-28 06:47:01.724  4611  4697 D BtGatt.ScanManager: handling starting scan
09-28 06:47:01.724  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 06:47:01.724  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-28 06:47:01.725  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 06:47:01.725  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 06:47:01.728  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 06:47:01.728  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 06:47:01.728  4611  4697 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
09-28 06:47:01.728  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 06:47:01.729  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 06:47:01.730  5634  5680 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 06:47:01.736  4611  4691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 06:47:01.736  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:01.736  4611  4697 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 06:47:01.744  4611  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 06:47:01.744  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:01.744  4611  4697 D BtGatt.ScanManager: Starting BLE batch scan
09-28 06:47:01.744  4611  4697 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 06:47:01.757  4611  4691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 06:47:01.757  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:01.765  4611  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 06:47:01.765  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:02.230  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 06:47:02.230  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:47:02.230  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 06:47:02.295   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:03.296   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:03.698   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 06:47:03.706   927  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-28 06:47:04.296   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 06:47:06.724   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 06:47:06.731   927  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-28 06:47:06.735  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:47:06.735  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:06.735  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 06:47:06.735  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:06.735  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 06:47:06.735  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-28 06:47:06.735  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 06:47:06.735  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 06:47:06.735  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 06:47:06.736  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 06:47:06.736  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 06:47:06.737  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:06.738  4611  4630 D BtGatt.GattService: stopScan() - queue size =1
,09-28 06:47:06.740  4611  4854 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 06:47:06.743  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 06:47:06.743  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 06:47:06.743  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 06:47:06.744  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 06:47:06.744  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 06:47:06.746  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 06:47:06.746  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:06.746  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 06:47:06.747  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 06:47:06.748  4611  4611 D BtGatt.ScanManager: awakened up at time 236600
09-28 06:47:06.751  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:06.754  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:06.754  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:06.754  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:47:06.754  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:06.755  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:06.755  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:06.755  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:06.755  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:06.755  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:06.755  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:06.755  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:47:06.757  4611  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 06:47:06.757  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:06.757  4611  4697 D BtGatt.ScanManager: stopping BLe Batch
,09-28 06:47:06.762  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 06:47:06.762  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 06:47:06.766  4611  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 06:47:06.767  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:06.767  4611  4697 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 06:47:06.769  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 06:47:06.770  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:47:06.770  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:47:06.770  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 06:47:06.771  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:06.776  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:47:06.776  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:47:06.776  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 06:47:06.780  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 06:47:06.780  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:47:06.781  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:06.783  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 06:47:06.789  4611  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 06:47:06.789  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:06.789  4611  4691 D BtGatt.GattService: current time is 236641802277
09-28 06:47:06.789  4611  4691 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -76, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -75, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -77, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -70, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -74, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 06:47:06.792  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 06:47:06.792  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 06:47:06.793  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 06:47:06.793  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 06:47:06.793  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 06:47:06.793  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 06:47:07.285  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 06:47:09.298   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:10.299   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:11.301   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:11.757  5634  5680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 06:47:11.764  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:11.775  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:47:11.780  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:47:11.781  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 06:47:11.781  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 06:47:11.782  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 06:47:11.782  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 06:47:11.782  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:11.782  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 06:47:11.789  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 06:47:11.791  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:11.798  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:11.799  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 06:47:11.799  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 06:47:11.799  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 06:47:11.800  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:11.804  4611  4876 D BtGatt.GattService: registerClient() - UUID=a681881e-35a8-429c-bec8-da3f6418d9f9
09-28 06:47:11.805  4611  4691 D BtGatt.GattService: onClientRegistered() - UUID=a681881e-35a8-429c-bec8-da3f6418d9f9, clientIf=5
,09-28 06:47:11.806  5634  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 06:47:11.806  4611  4854 D BtGatt.GattService: start scan with filters
09-28 06:47:11.811  4611  4697 D BtGatt.ScanManager: handling starting scan
09-28 06:47:11.812  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 06:47:11.812  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 06:47:11.812  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 06:47:11.813  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 06:47:11.819  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 06:47:11.819  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 06:47:11.819  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 06:47:11.821  4611  4691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 06:47:11.822  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:11.822  4611  4697 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 06:47:11.822  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 06:47:11.827  5634  5680 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 06:47:11.831  4611  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 06:47:11.831  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:11.831  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:11.831  5634  5680 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 06:47:11.831  4611  4697 D BtGatt.ScanManager: Starting BLE batch scan
09-28 06:47:11.831  4611  4697 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 06:47:11.831  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:11.831  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-28 06:47:11.832  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:11.832  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 06:47:11.832  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 06:47:11.832  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 06:47:11.832  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 06:47:11.832  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 06:47:11.832  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 06:47:11.832  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 06:47:11.833  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:47:11.835  4611  4854 D BtGatt.GattService: stopScan() - queue size =1
09-28 06:47:11.836  4611  4630 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 06:47:11.837  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:11.837  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 06:47:11.837  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 06:47:11.837  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 06:47:11.837  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 06:47:11.841  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 06:47:11.841  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:11.841  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 06:47:11.841  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 06:47:11.843  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:47:11.845  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:47:11.845  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:11.845  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:11.845  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:47:11.845  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:11.845  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 06:47:11.845  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
,09-28 06:47:11.845  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:11.845  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:11.845  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:11.845  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:47:11.849  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:47:11.849  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 06:47:11.849  4611  4691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 06:47:11.849  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:11.855  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 06:47:11.856  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:47:11.856  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:47:11.856  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:47:11.856  4611  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 06:47:11.856  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:11.857  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:11.859  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:11.859  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:11.861  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 06:47:11.861  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 06:47:11.861  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:11.862  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:11.862  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:11.862  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:11.862  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:11.862  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:11.862  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:47:11.862  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:11.862  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 06:47:11.863  5634  5680 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 06:47:11.865  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:11.866  4611  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 06:47:11.866  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:11.867  4611  4697 D BtGatt.ScanManager: stopping BLe Batch
,09-28 06:47:11.868  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:47:11.868  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:47:11.869  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:11.874  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:47:11.875  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 06:47:11.875  4611  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 06:47:11.875  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:11.875  4611  4697 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 06:47:11.877  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:11.877  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 06:47:11.878  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:47:11.878  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 06:47:11.878  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 06:47:11.878  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:11.878  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:47:11.880  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:47:11.881  4611  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 06:47:11.881  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:11.882  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:11.884  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 06:47:11.884  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-28 06:47:11.884  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 06:47:11.885  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:11.886  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:47:11.887  4611  4628 D BtGatt.GattService: registerClient() - UUID=ee838d7b-824e-4455-aa37-d7f5c2b9caa6
09-28 06:47:11.888  4611  4691 D BtGatt.GattService: onClientRegistered() - UUID=ee838d7b-824e-4455-aa37-d7f5c2b9caa6, clientIf=5
,09-28 06:47:11.888  5634  5644 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 06:47:11.888  4611  4630 D BtGatt.GattService: start scan with filters
,09-28 06:47:11.891  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 06:47:11.891  4611  4697 D BtGatt.ScanManager: handling starting scan
09-28 06:47:11.891  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 06:47:11.891  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 06:47:11.891  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 06:47:11.893  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 06:47:11.893  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 06:47:11.893  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 06:47:11.895  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 06:47:11.897  4611  4691 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 06:47:11.897  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:11.897  4611  4697 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 06:47:11.898  5634  5680 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 06:47:11.902  4611  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 06:47:11.902  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:11.903  4611  4697 D BtGatt.ScanManager: Starting BLE batch scan
09-28 06:47:11.903  4611  4697 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 06:47:11.912  4611  4691 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 06:47:11.912  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:11.917  4611  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 06:47:11.917  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:12.302   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:12.395  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 06:47:12.395  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:47:12.395  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 06:47:13.303   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:14.304   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 06:47:16.899  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:47:16.899  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 06:47:16.899  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-28 06:47:16.899  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:16.900  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-28 06:47:16.900  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 06:47:16.900  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 06:47:16.900  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-28 06:47:16.900  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 06:47:16.900  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 06:47:16.900  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 06:47:16.903  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:16.904  4611  4876 D BtGatt.GattService: stopScan() - queue size =1
,09-28 06:47:16.906  4611  4854 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 06:47:16.907  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:16.907  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 06:47:16.908  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 06:47:16.908  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 06:47:16.908  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 06:47:16.910  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 06:47:16.911  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 06:47:16.911  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 06:47:16.911  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:47:16.912  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:16.915  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:47:16.916  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:16.916  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:47:16.916  4611  4611 D BtGatt.ScanManager: awakened up at time 246768
09-28 06:47:16.922  4611  4691 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 06:47:16.922  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:16.922  4611  4697 D BtGatt.ScanManager: stopping BLe Batch
09-28 06:47:16.925  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:47:16.926  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 06:47:16.930  4611  4691 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 06:47:16.931  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:47:16.931  4611  4697 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 06:47:16.932  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 06:47:16.933  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:47:16.934  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:47:16.934  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:47:16.935  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:47:16.939  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:47:16.940  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:16.940  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 06:47:16.944  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 06:47:16.944  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:47:16.944  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:16.947  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 06:47:16.954  4611  4691 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 06:47:16.954  4611  4691 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:47:16.954  4611  4691 D BtGatt.GattService: current time is 246806562912
09-28 06:47:16.954  4611  4691 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -76, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -70, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -73, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 06:47:16.955  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 06:47:16.955  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 06:47:16.955  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 06:47:16.955  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 06:47:16.956  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-28 06:47:16.956  4611  4691 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 06:47:17.448  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 06:47:17.449  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:17.449  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 06:47:21.916  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:47:21.917  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 06:47:21.917  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.917  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.918  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.918  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:47:21.918  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.918  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.918  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.918  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.919  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:21.922  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.922  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:21.925  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 06:47:21.925  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.925  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.927  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.927  5634  5680 D BluetoothLeScanner: could not find callback wrapper
,09-28 06:47:21.927  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.927  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.927  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.929  5634  5680 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-28 06:47:21.931  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.931  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 06:47:21.931  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.931  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.932  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.932  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:21.932  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.932  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.932  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.933  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.933  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.933  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.933  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:21.933  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.936  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.936  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.936  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.937  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.937  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.937  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.938  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:47:21.938  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
,09-28 06:47:21.940  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 06:47:21.940  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.940  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 06:47:21.940  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.940  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.940  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.941  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.941  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.941  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.941  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.941  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.941  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:21.941  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.941  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.941  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.943  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.943  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.943  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.944  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.945  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.945  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.945  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:47:21.945  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
,09-28 06:47:21.946  5634  5680 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-28 06:47:21.947  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.947  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:21.947  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.947  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 06:47:21.947  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.947  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.947  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.948  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.948  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.948  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.948  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.948  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:21.948  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.948  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.950  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.950  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 06:47:21.950  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.951  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.951  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.951  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.952  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.952  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
,09-28 06:47:21.953  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-28 06:47:21.953  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:47:21.954  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:21.954  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.954  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.954  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.954  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.954  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
,09-28 06:47:21.954  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.954  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.954  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.954  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:21.955  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.955  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.955  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.957  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.957  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.957  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 06:47:21.958  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.958  5634  5680 D BluetoothLeScanner: could not find callback wrapper
,09-28 06:47:21.958  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.958  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.958  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.959  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 06:47:21.960  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 06:47:21.960  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 06:47:21.960  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 06:47:21.960  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 06:47:21.960  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 06:47:21.960  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 06:47:21.960  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 06:47:21.960  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 06:47:21.960  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.960  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:21.960  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.960  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.960  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.961  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.961  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.961  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.961  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
,09-28 06:47:21.961  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.961  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.961  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.961  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.961  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.962  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.962  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.962  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.963  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.963  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.963  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.963  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.963  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.964  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 06:47:21.965  5634  5680 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 06:47:21.965  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 06:47:21.968  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 06:47:21.968  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 06:47:21.968  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 06:47:21.969  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 06:47:21.970  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 06:47:21.970  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-28 06:47:21.970  5634  5680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 06:47:21.970  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-28 06:47:21.970  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 06:47:21.970  5634  5680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 06:47:21.971  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-28 06:47:21.971  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 06:47:21.971  5634  5680 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 06:47:21.971  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-28 06:47:21.975  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-28 06:47:21.975  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-28 06:47:21.976  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-28 06:47:21.976  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-28 06:47:21.977  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-28 06:47:21.977  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-28 06:47:21.977  5634  5680 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 06:47:21.977  5634  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-28 06:47:21.977  5634  5680 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-28 06:47:21.978  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.978  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:21.978  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.978  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.979  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.979  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.979  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-28 06:47:21.979  5634  5681 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:47:21.980  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.980  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.980  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.980  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.980  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.980  5634  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-28 06:47:21.980  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.980  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.980  5634  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-28 06:47:21.980  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.980  5634  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-28 06:47:21.981  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.981  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.981  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.981  4630  4630 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31631]" dev="sockfs" ino=31631 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 06:47:21.983  5634  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-28 06:47:21.983  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.983  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.984  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.984  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.984  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.981  4630  4630 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31631]" dev="sockfs" ino=31631 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 06:47:21.984  5634  5680 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-28 06:47:21.985  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.985  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:21.985  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.985  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.985  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.985  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.985  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.985  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.985  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.985  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.985  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.985  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.986  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.986  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.987  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.987  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.987  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.987  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.988  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.988  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.988  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.988  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.988  5634  5680 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-28 06:47:21.988  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.989  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:21.989  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.989  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.989  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.989  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.989  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.989  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.989  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.989  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.989  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.989  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.989  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.989  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.990  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.990  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.990  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.990  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.990  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.990  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.990  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.990  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.992  5634  5680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-28 06:47:21.992  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-28 06:47:21.992  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 06:47:21.992  5634  5680 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-28 06:47:21.992  5634  5680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 06:47:21.992  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-28 06:47:21.992  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 06:47:21.993  5634  5680 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-28 06:47:21.993  5634  5680 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 06:47:21.993  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 06:47:21.993  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 06:47:21.993  5634  5680 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-28 06:47:21.993  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:21.993  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:21.993  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:21.993  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.993  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.994  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.994  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.994  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.994  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.994  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.994  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.994  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.994  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.994  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.995  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:21.996  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:21.996  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:21.996  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:21.996  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:21.997  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:21.997  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.997  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.997  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:21.998  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.998  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:21.998  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:21.998  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:21.998  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:21.998  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:21.998  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:21.998  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:24.305   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:24.896   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 06:47:25.306   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:26.307   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:26.999  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:47:26.999  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
,09-28 06:47:26.999  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:26.999  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:27.000  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.000  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:27.000  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:47:27.000  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:27.000  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:27.000  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:27.001  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:27.001  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.001  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:27.001  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:47:27.001  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.002  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:27.002  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:27.002  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:27.002  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.002  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.005  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:27.005  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:27.005  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:27.007  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:27.007  5634  5680 D BluetoothLeScanner: could not find callback wrapper
,09-28 06:47:27.008  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:27.008  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.008  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.012  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-28 06:47:27.012  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:27.014  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-28 06:47:27.016  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 06:47:27.016  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 06:47:27.017  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 06:47:27.017  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 06:47:27.017  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 06:47:27.018  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 06:47:27.018  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 06:47:27.018  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 06:47:27.018  5634  5684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:47:27.018  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-28 06:47:27.018  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:27.019  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-28 06:47:27.019  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:27.019  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.019  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 06:47:27.019  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 06:47:27.019  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 06:47:27.019  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 06:47:27.019  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 06:47:27.021  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:27.021  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:27.021  4628  4628 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32644]" dev="sockfs" ino=32644 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 06:47:27.021  4628  4628 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32644]" dev="sockfs" ino=32644 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 06:47:27.021  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:27.021  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:27.021  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 06:47:27.022  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.022  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.023  5634  5684 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 06:47:27.023  5634  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 06:47:27.023  5634  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 06:47:27.024  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 06:47:27.024  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.024  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:27.024  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:27.024  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:27.024  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 06:47:27.024  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:27.024  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:27.025  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:47:27.025  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:27.025  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:27.025  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:27.025  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.025  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.026  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 06:47:27.026  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.026  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:47:27.031  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 06:47:27.031  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 06:47:27.039  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 06:47:27.040  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:47:27.041  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 06:47:27.041  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 06:47:27.042  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:27.045  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:27.045  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.047  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:27.047  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:27.047  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:27.048  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:27.048  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:27.048  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:27.048  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.048  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:47:27.048  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.048  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:47:27.049  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 06:47:27.050  5634  5680 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-28 06:47:27.050  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 06:47:27.050  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 06:47:27.051  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 06:47:27.051  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 06:47:27.051  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:27.051  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 06:47:27.051  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:27.051  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:27.051  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.051  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:27.051  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:27.052  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.052  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.052  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 06:47:27.052  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.052  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:47:27.052  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:47:27.053  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:47:27.054  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:27.058  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 06:47:27.058  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.058  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-28 06:47:27.058  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:27.060  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:27.060  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:27.060  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:47:27.061  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:47:27.061  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:27.061  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:27.061  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.061  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.065  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:27.065  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:47:27.065  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 06:47:27.065  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:27.065  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.065  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.065  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:27.065  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.066  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.066  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 06:47:27.066  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.066  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.066  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.066  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.067  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:27.067  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:27.067  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 06:47:27.068  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:47:27.068  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:27.068  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:27.068  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.068  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
,09-28 06:47:27.069  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:47:27.069  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 06:47:27.070  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:47:27.070  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:47:27.070  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.070  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:27.070  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c13eaa5 not in the list
09-28 06:47:27.070  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.070  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.070  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:27.070  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:27.070  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.070  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:47:27.070  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:47:27.072  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:47:27.072  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:47:27.072  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 06:47:27.073  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:47:27.073  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:47:27.073  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:47:27.073  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:27.073  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6975e7a not in the list
09-28 06:47:27.074  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-28 06:47:27.074  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-28 06:47:27.074  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-28 06:47:27.074  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 06:47:27.074  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-28 06:47:27.074  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 06:47:27.076  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 06:47:27.076  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-28 06:47:27.077  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-28 06:47:27.077  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 06:47:27.077  5634  5680 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-28 06:47:27.077  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 06:47:27.077  5634  5680 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-28 06:47:27.078  5634  5680 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-28 06:47:27.078  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-28 06:47:27.078  5634  5680 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-28 06:47:27.079  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-28 06:47:27.079  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-28 06:47:27.079  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-28 06:47:27.079  5634  5680 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-28 06:47:27.081  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:47:27.081  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9a223d0 added. We now have 3 listener(s)
09-28 06:47:27.081  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 06:47:27.083  5634  5680 D BluetoothAdapter: enable(): BT is already enabled..!
09-28 06:47:27.083   927  3414 D WifiService: setWifiEnabled: true pid=5634, uid=10077
,09-28 06:47:27.084   927  3414 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 06:47:27.106  4611  4824 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-28 06:47:27.107  4611  4849 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-28 06:47:27.308   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:27.558  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 06:47:27.921   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 06:47:28.309   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:29.310   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 06:47:29.872   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:47:32.089  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 06:47:32.089  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d2cfc9 added. We now have 4 listener(s)
09-28 06:47:32.090  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:47:32.102  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:47:32.102  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d2cfc9 removed from the list
,09-28 06:47:32.102  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:32.102  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:32.103  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:32.104  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:47:32.104  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a87e6ce added. We now have 4 listener(s)
09-28 06:47:32.105  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:47:32.108  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:32.108  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a87e6ce removed from the list
09-28 06:47:32.108  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:32.108  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:32.108  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:32.110  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 06:47:32.110  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@58439ef added. We now have 4 listener(s)
,09-28 06:47:32.110  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:47:32.116   927   937 D WifiService: setWifiEnabled: false pid=5634, uid=10077
,09-28 06:47:32.116   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 06:47:32.125   927  3000 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 06:47:32.126   927  3000 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 06:47:32.126   927  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 06:47:32.126   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 06:47:32.133  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:47:32.135  4611  4687 D BluetoothAdapterState: Current state: ON, message: 23
09-28 06:47:32.135  4611  4687 D BluetoothAdapterProperties: Setting state to 13
09-28 06:47:32.135  4611  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 06:47:32.136  4611  4687 D BluetoothAdapterProperties: onBluetoothDisable()
09-28 06:47:32.136  4611  4687 I BluetoothAdapterState: Entering PendingCommandState
09-28 06:47:32.138  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:32.138  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:47:32.139  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.139  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:32.140  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 06:47:32.142  4611  4611 D BluetoothMapService: onReceive
,09-28 06:47:32.142  4611  4611 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 06:47:32.142  4611  4611 D BluetoothMapService: STATE_TURNING_OFF
09-28 06:47:32.143  4611  4611 D BluetoothMapService: MAP Service closeService in
09-28 06:47:32.143  4611  4611 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 06:47:32.143  4611  4611 D ObexServerSockets0: shutdown(block = true)
09-28 06:47:32.143  4611  4691 D BluetoothAdapterProperties: Scan Mode:20
09-28 06:47:32.143  4611  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-28 06:47:32.144  4611  4611 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 06:47:32.144  4611  4611 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 06:47:32.144  4611  4849 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 06:47:32.144  4611  4878 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-28 06:47:32.144  4611  4879 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-28 06:47:32.147  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.147   927  5377 D DhcpClient: Clearing IP address
09-28 06:47:32.148   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-28 06:47:32.152  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.154  4611  4611 I BtOppRfcommListener: stopping Accept Thread
09-28 06:47:32.155  4611  5349 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 06:47:32.155  4611  5349 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 06:47:32.155  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:32.156  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:47:32.156  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.156  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:47:32.158   508   921 D CommandListener: Setting iface cfg
,09-28 06:47:32.160  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:32.160  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:47:32.161  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.161  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:32.164  3575  5439 V NativeCrypto: Read error: ssl=0x7fad757580: I/O error during system call, Connection timed out
09-28 06:47:32.165   927  5378 D DhcpClient: Receive thread stopped
09-28 06:47:32.165  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.166  3575  5439 V NativeCrypto: SSL shutdown failed: ssl=0x7fad757580: I/O error during system call, Broken pipe
09-28 06:47:32.168   927  3153 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-28 06:47:32.168   927   940 I ActivityManager: Start proc 5688:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-28 06:47:32.168   927  5375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-28 06:47:32.170  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.171   927  5375 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-28 06:47:32.172   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-28 06:47:32.172   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-28 06:47:32.173  4611  4611 D HeadsetService: Received stop request...Stopping profile...
,09-28 06:47:32.173   927  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 06:47:32.174   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:32.174   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:32.175  3811  3836 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:32.176   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 06:47:32.176   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:32.176   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-28 06:47:32.176  3125  3966 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:32.177  3125  3125 D HeadsetProfile: Bluetooth service disconnected
09-28 06:47:32.180  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:32.182   927   927 D RttService: SCAN_AVAILABLE : 1
,09-28 06:47:32.182   927  3011 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-28 06:47:32.183   534   534 E Parcel  : Reading a NULL string not supported here.
09-28 06:47:32.183   927  3076 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 06:47:32.183  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.183  4611  4611 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:32.183  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:47:32.183  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.183  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:32.183  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:32.184  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:32.184  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:47:32.184  3767  3891 W QCNEJ   : |CORE| network lost: 100
,09-28 06:47:32.185  3767  3891 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-28 06:47:32.191  4611  4611 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-28 06:47:32.192  4611  4611 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 06:47:32.192  4611  4691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 06:47:32.192  4611  4824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:32.192  4611  4824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:32.192  4611  4824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:32.192  4611  4611 D A2dpService: Received stop request...Stopping profile...
09-28 06:47:32.192  4611  4859 D A2dpStateMachine: Exit Disconnected: -1
09-28 06:47:32.193   927   927 D BluetoothA2dp: Proxy object disconnected
09-28 06:47:32.193  4611  4691 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 06:47:32.194   927  3000 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-28 06:47:32.198  4611  4611 D HidService: Received stop request...Stopping profile...
09-28 06:47:32.198  4611  4611 D HidService: Stopping Bluetooth HidService
,09-28 06:47:32.201  3125  3125 D BluetoothA2dp: Proxy object disconnected
09-28 06:47:32.201  3125  3125 D BluetoothInputDevice: Proxy object disconnected
,09-28 06:47:32.202  3125  3125 D HidProfile: Bluetooth service disconnected
09-28 06:47:32.202  4611  4611 D HealthService: Received stop request...Stopping profile...
,09-28 06:47:32.203   927  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 06:47:32.206  4611  4611 D PanService: Received stop request...Stopping profile...
09-28 06:47:32.207  4611  4611 D BluetoothMapService: Received stop request...Stopping profile...
09-28 06:47:32.208  4611  4611 D BluetoothMapService: stop()
09-28 06:47:32.208  4611  4611 D BluetoothMapAppObserver: deinitObservers()
09-28 06:47:32.208  4611  4611 D BluetoothMapAppObserver: removeReceiver()
,09-28 06:47:32.209  4611  4611 D SapService: Received stop request...Stopping profile...
,09-28 06:47:32.210  4611  4611 V SapService: stop()
09-28 06:47:32.210  4611  4611 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:32.211  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.211  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 06:47:32.211  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:32.212  4611  4691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 06:47:32.212  4611  4824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:32.212  4611  4611 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:32.212  4611  4824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:32.213  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.213  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:32.213  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:32.213  4611  4824 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 06:47:32.213  4611  4824 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 06:47:32.213  4611  4824 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 06:47:32.213  4611  4824 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 06:47:32.213  4611  4611 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-28 06:47:32.213  4611  4611 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 06:47:32.213  4611  4691 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 06:47:32.213  4611  4611 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:32.213  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.213  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:32.213  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:32.214  4611  4611 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 06:47:32.214  4611  4691 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 06:47:32.214  4611  4611 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 06:47:32.214  4611  4611 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:32.214  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.214  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:32.214  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:32.214  4611  4611 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 06:47:32.215  4611  4611 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 06:47:32.215   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 06:47:32.215  4611  4611 D BluetoothMapService: MAP Service closeService in
09-28 06:47:32.215  4611  4611 V BluetoothAdapterState: isTurningOff()=true
,09-28 06:47:32.215  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.215  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:32.215  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:32.216  4611  4611 D BluetoothMapService: cleanup()
09-28 06:47:32.216  4611  4611 D BluetoothMapService: MAP Service closeService in
,09-28 06:47:32.216  4611  4611 V BluetoothAdapterState: isTurningOff()=true
,09-28 06:47:32.216  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.216  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:32.216  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:32.216  4611  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 06:47:32.216  4611  4687 D BluetoothAdapterProperties: Setting state to 15
09-28 06:47:32.216  4611  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 06:47:32.217  4611  4687 I BluetoothAdapterState: Entering BleOnState
,09-28 06:47:32.217   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 06:47:32.217  3811  3985 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:32.218  3125  3139 D BluetoothPan: onBluetoothStateChange on: false
09-28 06:47:32.218  3125  3963 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:32.219  3125  3966 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-28 06:47:32.219  3125  3137 D BluetoothPbap: onBluetoothStateChange: up=false
,09-28 06:47:32.220  3125  3139 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-28 06:47:32.221  3125  3963 D BluetoothMap: onBluetoothStateChange: up=false
,09-28 06:47:32.221   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:32.221   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 06:47:32.221   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 06:47:32.222  4611  4687 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-28 06:47:32.222  4611  4687 D BluetoothAdapterProperties: Setting state to 16
,09-28 06:47:32.222  4611  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 06:47:32.223  4611  4687 D BluetoothAdapterProperties: onBleDisable
09-28 06:47:32.223  4611  4687 I BluetoothAdapterState: Entering PendingCommandState
09-28 06:47:32.223  4611  4688 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 06:47:32.224  4611  4824 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 06:47:32.225  4611  4824 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:32.226  4611  4691 D BluetoothAdapterProperties: Scan Mode:20
09-28 06:47:32.227  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:32.227  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:32.228  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.228  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:47:32.230  5688  5688 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-28 06:47:32.234  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:32.234  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:32.235  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.235  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:32.237  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:32.237  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:32.238  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.239  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.240  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:32.247   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 06:47:32.247   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-28 06:47:32.247   508   921 D TetherController: Setting IP forward enable = 0
,09-28 06:47:32.248   927  3011 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-28 06:47:32.248   927  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 06:47:32.250   927   944 D Tethering: MasterInitialState.processMessage what=3
09-28 06:47:32.253  5269  5269 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1444594 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-28 06:47:32.255   927  3000 D DhcpClient: doQuit
09-28 06:47:32.255   927  3000 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 06:47:32.256   927  5377 D DhcpClient: onQuitting
09-28 06:47:32.256  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.257  3437  3437 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-28 06:47:32.258  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:32.260  5054  5078 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 06:47:32.260  5054  5078 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 06:47:32.260  5054  5078 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 06:47:32.260  5054  5078 E SarControlService: no key has been found,reset the power
09-28 06:47:32.261  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:32.261  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:32.261  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 06:47:32.261  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 06:47:32.261  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 06:47:32.261  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 06:47:32.262  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:32.262  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:32.262  5079  5079 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 06:47:32.264  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 06:47:32.264  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 06:47:32.264  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 06:47:32.264  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 06:47:32.264  5079  5079 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 06:47:32.266  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:32.266  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:32.267  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.267  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:32.267  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000ea03000000000000ffffffff]
09-28 06:47:32.267  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:47:32.267  5079  5093 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-28 06:47:32.267  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 06:47:32.267  5054  5064 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 06:47:32.269  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:32.269  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:32.270  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do, the check when the Bluetooth is disabled - will return stored value
09-28 06:47:32.270  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:32.272  5688  5688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 06:47:32.272  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.275  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000eb03000000000000ffffffff]
09-28 06:47:32.275  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:47:32.275  5079  5093 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-28 06:47:32.279  3437  3437 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-28 06:47:32.284  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 06:47:32.287  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 06:47:32.288  5054  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 06:47:32.291   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e93cb4f:true
,09-28 06:47:32.292  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 06:47:32.305   927   937 I ActivityManager: Start proc 5717:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-28 06:47:32.318  5688  5688 D LocalBluetoothProfileManager: Adding local MAP profile
,09-28 06:47:32.319  3437  3437 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 06:47:32.322  5688  5688 D BluetoothMap: Create BluetoothMap proxy object
,09-28 06:47:32.328  3437  3437 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 06:47:32.339  5688  5688 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-28 06:47:32.346  5717  5717 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-28 06:47:32.357  5688  5688 D DockEventReceiver: finishStartingService: stopping service
,09-28 06:47:32.360   927  3413 I ActivityManager: Killing 4994:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-28 06:47:32.430  5029  5029 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 06:47:32.431   927  3000 D wifi    : In wifi stop Hal
,09-28 06:47:32.431   927  3000 D wifi    : halHandle = 0x7f91068340, mVM = 0x7fad6cd140, mCls = 0x100a02
09-28 06:47:32.431   927  3436 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 06:47:32.431   927  3436 D WifiHAL : Got a signal to exit!!!
,09-28 06:47:32.432   927  3436 I WifiHAL : Exit wifi_event_loop
,09-28 06:47:32.432   927  3000 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 06:47:32.432   927  3000 E WifiHAL : Event processing terminated
09-28 06:47:32.432   927  3000 D wifi    : In wifi cleaned up handler
09-28 06:47:32.432   927  3000 I WifiHAL : Internal cleanup completed
09-28 06:47:32.436  4070  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 06:47:32.436  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.438  4611  4691 I bt_hci  : shut_down
,09-28 06:47:32.438  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.440  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:32.440  4611  4698 I bt_vendor: low_power_mode_cb
,09-28 06:47:32.443  4611  4698 D bt_hwcfg: hw_epilog_process
,09-28 06:47:32.446  4611  4698 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 06:47:32.446  4611  4698 I bt_vendor: epilog_cb
09-28 06:47:32.446  4611  4698 I bt_hci  : epilog_finished_callback
,09-28 06:47:32.449  4611  4691 I bt_hci_h4: hal_close
,09-28 06:47:32.449  4611  4691 I bt_userial_vendor: device fd = 54 close
,09-28 06:47:32.456   927  3436 D wifi    : set interface wlan0 flags (DOWN)
,09-28 06:47:32.456   927  3000 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 06:47:32.528  5717  5717 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.528  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 06:47:32.529  5717  5717 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 06:47:32.529  5717  5717 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 06:47:32.529  5717  5717 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.529  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 06:47:32.551  5717  5717 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.r.k.d(PG:583)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 06:47:32.551  5717  5717 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 06:47:32.551  5717  5717 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 06:47:32.551  5717  5717 D StrictMode: StrictMode policy violation; ~duration=49 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 06:47:32.551  5717  5717 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 06:47:32.556  4611  4688 D bt_stack_manager: event_shut_down_stack finished.
09-28 06:47:32.556  4611  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-28 06:47:32.561  4611  4687 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 06:47:32.561  4611  4611 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 06:47:32.562  4611  4611 D BtGatt.GattService: Received stop request...Stopping profile...
,09-28 06:47:32.562  4611  4611 D BtGatt.GattService: stop()
09-28 06:47:32.562  5688  5688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 06:47:32.562  4611  4611 D BtGatt.AdvertiseManager: advertise clients cleared
09-28 06:47:32.564  4611  4611 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:32.564  4611  4611 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:32.565  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:32.565  4611  4611 V BluetoothAdapterState: isBleTurningOff()=true
09-28 06:47:32.565  4611  4687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 06:47:32.565  4611  4687 D BluetoothAdapterProperties: Setting state to 10
09-28 06:47:32.566  4611  4687 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 06:47:32.566  4611  4687 I BluetoothAdapterState: Entering OffState
09-28 06:47:32.567   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-28 06:47:32.568  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 06:47:32.575  4611  4611 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-28 06:47:32.575  4611  4611 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 06:47:32.575  4611  4611 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 06:47:32.577  4611  4688 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-28 06:47:32.580  3724  3724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 06:47:32.585  3724  3724 D SystemUpdateService: onCreate
09-28 06:47:32.590  4611  4688 D bt_stack_manager: event_clean_up_stack finished.
09-28 06:47:32.590  3724  3724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 06:47:32.598  3724  3724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 06:47:32.602  3724  5409 I iu.UploadsManager: num queued entries: 0
09-28 06:47:32.602  3724  5409 I iu.UploadsManager: num updated entries: 0
09-28 06:47:32.603  3724  5409 I iu.SyncManager: NEXT; no task
,09-28 06:47:32.605  4611  4611 I art     : System.exit called, status: 0
09-28 06:47:32.605  4611  4611 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 06:47:32.612  5688  5688 D DockEventReceiver: finishStartingService: stopping service
,09-28 06:47:32.628  3724  3724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 06:47:32.630  3724  3724 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 06:47:32.632  5412  5412 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 06:47:32.636  5412  5412 D SprintDMHelper: simOperator: 
09-28 06:47:32.636  5412  5412 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 06:47:32.649  3724  5749 I SystemUpdateService: active receiver: enabled
,09-28 06:47:32.657  5029  5751 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 06:47:32.659   927   944 D Tethering: InitialState.processMessage what=4
09-28 06:47:32.661   927   938 I ActivityManager: Start proc 5752:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-28 06:47:32.662   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 06:47:32.665   927  3809 I ActivityManager: Process com.android.bluetooth (pid 4611) has died
,09-28 06:47:32.667  3724  5749 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 06:47:32.678  3724  5749 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 06:47:32.679  3724  5749 I SystemUpdateService: now status is 0 (complete)
09-28 06:47:32.679  3724  5749 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 06:47:32.679  3724  5749 I SystemUpdateService: file has been verified
09-28 06:47:32.679  3724  5749 I SystemUpdateService: OTA package size = 21989297
,09-28 06:47:32.699  5752  5752 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-28 06:47:32.710   927  3678 I ActivityManager: Killing 5269:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-28 06:47:32.735  3724  5749 I SystemUpdateService: showing system update notification
,09-28 06:47:32.777  3724  3724 D SystemUpdateService: onDestroy
,09-28 06:47:32.778   927  3109 I ActivityManager: Killing 4702:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-28 06:47:32.890  5717  5736 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-28 06:47:32.898   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@578c210:true
,09-28 06:47:33.334   508   921 E Netd    : netlink response contains error (No such file or directory)
,09-28 06:47:33.336   927  3011 E NetdConnector: NDC Command {113 network destroy 100} took too long (1087ms)
,09-28 06:47:33.337   927  3011 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 06:47:33.338   927  2970 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1082ms)
,09-28 06:47:33.339   927  2969 E NetdConnector: NDC Command {115 bandwidth gettetherstats} took too long (675ms)
09-28 06:47:33.339   508   921 D TetherController: Setting IP forward enable = 0
,09-28 06:47:37.142   927  3863 D WifiService: setWifiEnabled: true pid=5634, uid=10077
,09-28 06:47:37.143   927  3863 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 06:47:37.152   508   921 D SoftapController: Softap fwReload - Ok
,09-28 06:47:37.157   508   921 D CommandListener: Setting iface cfg
09-28 06:47:37.157   508   921 D CommandListener: Trying to bring down wlan0
,09-28 06:47:37.159   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-28 06:47:37.166   927  3000 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 06:47:37.737   927  3000 D wifi    : set interface wlan0 flags (UP)
,09-28 06:47:37.740   927  3000 I WifiHAL : Initializing wifi
,09-28 06:47:37.740   927  3000 I WifiHAL : Creating socket
09-28 06:47:37.742   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 06:47:37.745   927  3000 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 06:47:37.745   927  3000 D wifi    : Did set static halHandle = 0x7f91068340
09-28 06:47:37.746   927  3000 D wifi    : halHandle = 0x7f91068340, mVM = 0x7fad6cd140, mCls = 0x10194a
09-28 06:47:37.746   927  3000 D wifi    : array field set
09-28 06:47:37.746   927  3000 I WifiNative-HAL: interface[0] = wlan0
,09-28 06:47:37.747   927  5775 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547893969728
09-28 06:47:37.747   927  5775 D wifi    : waitForHalEvents called, vm = 0x7fad6cd140, obj = 0x10194a, env = 0x7f933a46c0
,09-28 06:47:37.809  5776  5776 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 06:47:37.828  5776  5776 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 06:47:37.848   927  3000 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 06:47:37.857  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:37.859  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:37.860  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:37.882  5776  5776 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 06:47:37.882  5776  5776 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 06:47:37.898   927  3000 D WifiConfigStore: Loading config and enabling all networks 
,09-28 06:47:37.899  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:37.900  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:47:37.900  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:37.900  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:37.902  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:37.902  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:37.902  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:37.902  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:37.903  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:37.903  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:37.903  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:37.903  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:47:37.912   927  3000 D WifiConfigStore: loaded 0 passpoint configs
,09-28 06:47:37.912   927  3000 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 06:47:37.913   927  3000 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 06:47:37.914   927  3000 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 06:47:37.916   927  3000 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 06:47:37.916   927  3000 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 06:47:37.916   927  3000 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 06:47:37.916   927  3000 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 06:47:37.920   927  3000 D WifiNative-HAL: Setting external_sim to 1
,09-28 06:47:37.920  5029  5029 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 06:47:37.920   927  3000 D wifi    : setting dfs flag to true, 0x7f915fa9c0
,09-28 06:47:37.921   927  3000 D WifiStateMachine: Setting OUI to DA-A1-19
,09-28 06:47:37.921   927  3000 D wifi    : setting scan oui 0x7f915fa9c0
09-28 06:47:37.921   927  3000 D WifiHAL : Sending mac address OUI
,09-28 06:47:37.926   927  3000 E native  : do suspend false
,09-28 06:47:37.934   927   927 D RttService: SCAN_AVAILABLE : 3
09-28 06:47:37.934   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 06:47:37.934   927  3000 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 06:47:37.935   927  3076 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-28 06:47:37.936   508   921 D CommandListener: Setting iface cfg
,09-28 06:47:37.940   927  2971 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-28 06:47:37.940   927  2971 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 06:47:37.950   927  2971 D WifiNative-HAL: p2pGetDeviceAddress
,09-28 06:47:37.950   927  2971 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 06:47:37.971   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267823 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=30 mControllerEnergyUsed=114 }
,09-28 06:47:41.117  5776  5776 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:47:41.122  5776  5776 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:47:41.128  5776  5776 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:47:41.132  5776  5776 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:47:41.196   927  3000 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 06:47:41.198   927  3000 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 06:47:41.198   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 06:47:41.210   927  3000 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 06:47:41.244   927  3000 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 06:47:41.247  5776  5776 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 06:47:41.706  5776  5776 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 06:47:41.757  5776  5776 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 06:47:41.759  5776  5776 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 06:47:41.767   927  3000 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 06:47:41.767   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 06:47:41.767   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 06:47:41.788   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 06:47:41.800   508   921 D CommandListener: Setting iface cfg
,09-28 06:47:41.808   927  3000 D WifiStateMachine: Start Dhcp Watchdog 2
,09-28 06:47:41.814   927  5782 D DhcpClient: Receive thread started
,09-28 06:47:41.818   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 06:47:41.818   927  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-28 06:47:41.818   927  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-28 06:47:41.898   927  3000 E native  : do suspend false
,09-28 06:47:41.910   927  5781 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 06:47:41.923   927  5782 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,09-28 06:47:41.924   927  5781 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,09-28 06:47:41.926   927  5781 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 06:47:41.940   927  5782 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 06:47:41.940   927  5781 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 06:47:41.944   508   921 D CommandListener: Setting iface cfg
,09-28 06:47:41.949   927  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 06:47:41.953   927  5781 D DhcpClient: Scheduling renewal in 86399s
,09-28 06:47:41.962   927  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-28 06:47:41.963   927  3000 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 06:47:41.964   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 06:47:41.966   927  3011 D ConnectivityService: Adding iface wlan0 to network 101
,09-28 06:47:41.978   927  3000 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 06:47:42.029   927  3011 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 06:47:42.029   927  3011 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-28 06:47:42.035   927  3011 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-28 06:47:42.039   927  3011 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-28 06:47:42.040   927  3011 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-28 06:47:42.046   927  3011 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 06:47:42.050   927  3011 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-28 06:47:42.051   927  3011 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-28 06:47:42.051   927  3011 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-28 06:47:42.051   927  3011 D ConnectivityService:    accepting network in place of null
09-28 06:47:42.051   927  3000 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 06:47:42.051   927  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 06:47:42.052   927  3011 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 06:47:42.065   927  5780 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:47:42.074   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 06:47:42.096   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 06:47:42.099   927  3011 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-28 06:47:42.099  3767  3891 W QCNEJ   : |CORE| network available: 101
09-28 06:47:42.099   927  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 06:47:42.100   927  3011 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-28 06:47:42.101  3767  3891 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 06:47:42.102  3767  3891 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 06:47:42.102  3767  3891 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-28 06:47:42.103   927   944 D Tethering: MasterInitialState.processMessage what=3
09-28 06:47:42.108  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:42.108  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:47:42.108  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.108  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:47:42.110  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:42.110  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:47:42.111  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.111  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:47:42.113  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:47:42.113  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:47:42.113  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.113  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:47:42.114  5054  5078 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 06:47:42.114  5054  5078 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 06:47:42.114  5054  5078 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 06:47:42.115  5054  5078 E SarControlService: no key has been found,reset the power
09-28 06:47:42.115  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 06:47:42.115  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 06:47:42.115  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 06:47:42.115  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 06:47:42.116  5079  5079 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-28 06:47:42.117  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 06:47:42.117  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 06:47:42.117  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-28 06:47:42.118  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 06:47:42.118  5079  5079 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 06:47:42.120  3724  3724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 06:47:42.123  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000ec03000000000000ffffffff]
09-28 06:47:42.123  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:47:42.123  5079  5093 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-28 06:47:42.123  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000ed03000000000000ffffffff]
09-28 06:47:42.123  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:47:42.123  5079  5093 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-28 06:47:42.124  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 06:47:42.124  5054  5064 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 06:47:42.125  3724  3724 D SystemUpdateService: onCreate
,09-28 06:47:42.125  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-28 06:47:42.126  5054  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 06:47:42.128  3724  3724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 06:47:42.137  3724  3724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 06:47:42.141  3724  5409 I iu.UploadsManager: num queued entries: 0
09-28 06:47:42.142  3724  5409 I iu.UploadsManager: num updated entries: 0
09-28 06:47:42.142  3724  5409 I iu.SyncManager: NEXT; no task
09-28 06:47:42.143   927  5779 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-28 06:47:42.145  3724  5792 I SystemUpdateService: active receiver: enabled
,09-28 06:47:42.146  3724  3724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 06:47:42.148  3724  3724 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-28 06:47:42.149   927  3830 D WifiService: setWifiEnabled: false pid=5634, uid=10077
,09-28 06:47:42.149   927  3830 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 06:47:42.150  5412  5412 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 06:47:42.150   927  3000 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-28 06:47:42.150   927  3000 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 06:47:42.150   927  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 06:47:42.151   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 06:47:42.156  5412  5412 D SprintDMHelper: simOperator: 
09-28 06:47:42.156  5412  5412 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-28 06:47:42.158   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-28 06:47:42.159   927  5781 D DhcpClient: Clearing IP address
09-28 06:47:42.160   508   921 D CommandListener: Setting iface cfg
,09-28 06:47:42.167   927  5779 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-28 06:47:42.168   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-28 06:47:42.173   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-28 06:47:42.173   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-28 06:47:42.175   534   534 E Parcel  : Reading a NULL string not supported here.
,09-28 06:47:42.182   927  3011 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-28 06:47:42.183   927   927 D RttService: SCAN_AVAILABLE : 1
09-28 06:47:42.183   927  3076 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 06:47:42.184  3767  3891 W QCNEJ   : |CORE| network lost: 101
,09-28 06:47:42.186  3767  3891 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-28 06:47:42.186   927  3000 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-28 06:47:42.187   927  5782 D DhcpClient: Receive thread stopped
,09-28 06:47:42.188  3724  5792 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-28 06:47:42.189   927  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 06:47:42.195  3724  5792 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-28 06:47:42.195  3724  5792 I SystemUpdateService: now status is 0 (complete)
09-28 06:47:42.195  3724  5792 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 06:47:42.195  3724  5792 I SystemUpdateService: file has been verified
09-28 06:47:42.195  3724  5792 I SystemUpdateService: OTA package size = 21989297
,09-28 06:47:42.201  3724  5792 I SystemUpdateService: showing system update notification
,09-28 06:47:42.210   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 06:47:42.212  3724  3724 D SystemUpdateService: onDestroy
,09-28 06:47:42.231   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 06:47:42.231   927  3011 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 06:47:42.231   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-28 06:47:42.231   927  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 06:47:42.234   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-28 06:47:42.238   927  3000 D DhcpClient: doQuit
,09-28 06:47:42.238   927  3000 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 06:47:42.238   927  5781 D DhcpClient: onQuitting
09-28 06:47:42.239  5776  5776 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 06:47:42.239  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:42.239  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:47:42.239  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.239  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:42.241  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:42.241  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:42.241  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.241  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:42.242  5054  5078 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 06:47:42.243  5054  5078 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,09-28 06:47:42.243  5054  5078 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 06:47:42.243  5054  5078 E SarControlService: no key has been found,reset the power
09-28 06:47:42.243  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 06:47:42.243  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 06:47:42.243  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 06:47:42.243  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:42.243  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:42.243  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.243  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:47:42.244  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 06:47:42.244  5079  5079 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 06:47:42.244  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:42.245  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:42.245  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:42.245  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:42.246  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:42.247  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 06:47:42.247  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 06:47:42.247  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-28 06:47:42.248  3724  3724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 06:47:42.252  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000ee03000000000000ffffffff]
09-28 06:47:42.252  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:47:42.252  5079  5093 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-28 06:47:42.253  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 06:47:42.253  5054  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 06:47:42.254  3724  3724 D SystemUpdateService: onCreate
09-28 06:47:42.255  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 06:47:42.255  5079  5079 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 06:47:42.256  5776  5776 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 06:47:42.257  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000ef03000000000000ffffffff]
09-28 06:47:42.258  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:47:42.258  5079  5093 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,09-28 06:47:42.258  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 06:47:42.258  5054  5064 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 06:47:42.260  5776  5776 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-28 06:47:42.260  3724  3724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 06:47:42.264  3724  5807 I SystemUpdateService: active receiver: enabled
,09-28 06:47:42.269  3724  3724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 06:47:42.274  3724  5409 I iu.UploadsManager: num queued entries: 0
,09-28 06:47:42.274  3724  5409 I iu.UploadsManager: num updated entries: 0
,09-28 06:47:42.275  3724  5409 I iu.SyncManager: NEXT; no task
,09-28 06:47:42.277  3724  3724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 06:47:42.279  3724  3724 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 06:47:42.280  5412  5412 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 06:47:42.283  5412  5412 D SprintDMHelper: simOperator: 
09-28 06:47:42.283  5412  5412 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 06:47:42.288  5776  5776 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 06:47:42.289   508   921 E Netd    : netlink response contains error (No such file or directory)
09-28 06:47:42.290  5776  5776 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-28 06:47:42.290   927  3011 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 06:47:42.290   927  3011 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 06:47:42.291  3724  5807 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 06:47:42.299  3724  5807 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 06:47:42.299  3724  5807 I SystemUpdateService: now status is 0 (complete)
,09-28 06:47:42.300  3724  5807 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 06:47:42.300  3724  5807 I SystemUpdateService: file has been verified
09-28 06:47:42.300  3724  5807 I SystemUpdateService: OTA package size = 21989297
,09-28 06:47:42.315  3724  5807 I SystemUpdateService: showing system update notification
,09-28 06:47:42.321  3724  3724 D SystemUpdateService: onDestroy
,09-28 06:47:42.392   927  3000 D wifi    : In wifi stop Hal
,09-28 06:47:42.392   927  3000 D wifi    : halHandle = 0x7f91068340, mVM = 0x7fad6cd140, mCls = 0x10194a
09-28 06:47:42.393   927  5775 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 06:47:42.393   927  5775 D WifiHAL : Got a signal to exit!!!
09-28 06:47:42.393   927  5775 I WifiHAL : Exit wifi_event_loop
09-28 06:47:42.394   927  3000 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 06:47:42.394   927  3000 E WifiHAL : Event processing terminated
09-28 06:47:42.394   927  3000 D wifi    : In wifi cleaned up handler
09-28 06:47:42.394   927  3000 I WifiHAL : Internal cleanup completed
09-28 06:47:42.394  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:42.393  5029  5029 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 06:47:42.395  4070  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 06:47:42.395  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:42.396  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:42.416   927  5775 D wifi    : set interface wlan0 flags (DOWN)
,09-28 06:47:42.416   927  3000 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 06:47:42.622   927   944 D Tethering: InitialState.processMessage what=4
,09-28 06:47:42.628   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 06:47:43.100   927  3011 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-28 06:47:44.311   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:45.312   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:46.313   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:47.188   927   944 I ActivityManager: Start proc 5814:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 06:47:47.283  5814  5814 D AdapterServiceConfig: Adding HeadsetService
,09-28 06:47:47.284  5814  5814 D AdapterServiceConfig: Adding A2dpService
09-28 06:47:47.284  5814  5814 D AdapterServiceConfig: Adding HidService
09-28 06:47:47.284  5814  5814 D AdapterServiceConfig: Adding HealthService
09-28 06:47:47.284  5814  5814 D AdapterServiceConfig: Adding PanService
,09-28 06:47:47.284  5814  5814 D AdapterServiceConfig: Adding GattService
,09-28 06:47:47.284  5814  5814 D AdapterServiceConfig: Adding BluetoothMapService
09-28 06:47:47.285  5814  5814 D AdapterServiceConfig: Adding SapService
,09-28 06:47:47.298   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d2934a6:true
,09-28 06:47:47.298  5814  5814 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 06:47:47.300  5814  5814 I bt_bluedroid: init
09-28 06:47:47.300  5814  5826 I BluetoothAdapterState: Entering OffState
,09-28 06:47:47.302  5814  5827 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-28 06:47:47.302  5814  5827 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 06:47:47.302  5814  5827 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 06:47:47.303  5814  5827 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-28 06:47:47.303  5814  5814 I bt_bluedroid: get_profile_interface socket
,09-28 06:47:47.304  5814  5830 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 06:47:47.304  5814  5814 I bt_bluedroid: get_profile_interface sdp
,09-28 06:47:47.306  5814  5830 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 06:47:47.309  5814  5825 I bt_bluedroid: config_hci_snoop_log
09-28 06:47:47.310   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 06:47:47.314   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:47.315  5814  5826 D BluetoothAdapterState: Current state: OFF, message: 0
09-28 06:47:47.315  5814  5826 D BluetoothAdapterProperties: Setting state to 14
09-28 06:47:47.315  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 06:47:47.317  5814  5826 D BluetoothBondStateMachine: make
,09-28 06:47:47.318  5814  5831 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 06:47:47.321  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
,09-28 06:47:47.322  5814  5814 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 06:47:47.324  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:47:47.324  5814  5814 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 06:47:47.325  5814  5814 D BtGatt.GattService: Received start request. Starting profile...
,09-28 06:47:47.325  5814  5814 D BtGatt.GattService: start()
09-28 06:47:47.325  5814  5814 I bt_bluedroid: get_profile_interface gatt
09-28 06:47:47.326  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
09-28 06:47:47.326  5814  5814 D BtGatt.AdvertiseManager: advertise manager created
,09-28 06:47:47.330  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,09-28 06:47:47.330  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:47.330  5814  5814 V BluetoothAdapterState: isBleTurningOn()=true
09-28 06:47:47.330  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:47.330  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-28 06:47:47.331  5814  5826 I bt_bluedroid: bt_bluedroid
09-28 06:47:47.331  5814  5827 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 06:47:47.332  5814  5827 I bt_hci  : start_up
,09-28 06:47:47.337  5814  5827 I bt_vendor: alloc value 0xf4151871
,09-28 06:47:47.337  5814  5827 I bt_vendor: init
09-28 06:47:47.337  5814  5827 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 06:47:47.337  5814  5827 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 06:47:47.448  5814  5827 D bt_hci  : start_up starting async portion
,09-28 06:47:47.448  5814  5834 I bt_hci  : event_finish_startup
,09-28 06:47:47.448  5814  5834 I bt_hci_h4: hal_open
09-28 06:47:47.448  5814  5834 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-28 06:47:47.447  5835  5835 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 06:47:47.451  5814  5834 I bt_userial_vendor: device fd = 54 open
,09-28 06:47:47.465  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 06:47:47.468  5814  5834 D bt_hwcfg: Chipset BCM4358A3
,09-28 06:47:47.468  5814  5834 D bt_hwcfg: Target name = [BCM4358A3]
09-28 06:47:47.468  5814  5834 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 06:47:47.872  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 06:47:47.872  5814  5834 D bt_hwcfg: Settlement delay -- 100 ms
,09-28 06:47:47.872  5814  5834 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 06:47:48.006  5814  5834 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 06:47:48.007  5814  5834 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 06:47:48.008  5814  5834 I bt_hwcfg: vendor lib fwcfg completed
,09-28 06:47:48.008  5814  5834 I bt_vendor: firmware callback
09-28 06:47:48.008  5814  5834 I bt_hci  : firmware_config_callback
,09-28 06:47:48.016  5814  5837 I bt_btu  : btu_task pending for preload complete event
,09-28 06:47:48.017  5814  5837 I bt_btu_task: Bluetooth chip preload is complete
09-28 06:47:48.017  5814  5837 I bt_btu  : btu_task received preload complete event
,09-28 06:47:48.023  5814  5837 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 06:47:48.023  5814  5837 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 06:47:48.023  5814  5837 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 06:47:48.023  5814  5837 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 06:47:48.023  5814  5837 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 06:47:48.024  5814  5837 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 06:47:48.024  5814  5837 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 06:47:48.024  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 06:47:48.024  5814  5837 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 06:47:48.024  5814  5837 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 06:47:48.024  5814  5837 I         : BTE_InitTraceLevels -- TRC_SDP
,09-28 06:47:48.024  5814  5837 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 06:47:48.025  5814  5837 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 06:47:48.025  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 06:47:48.025  5814  5837 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 06:47:48.108  5814  5837 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40cf549
09-28 06:47:48.108  5814  5837 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40cf549 
,09-28 06:47:48.132  5814  5830 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 06:47:48.133  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 06:47:48.134  5814  5830 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 06:47:48.136  5814  5830 D BluetoothAdapterProperties: Name is: Nexus 6P
09-28 06:47:48.139  5814  5830 D BluetoothAdapterProperties: Scan Mode:20
09-28 06:47:48.139  5814  5830 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 06:47:48.139  5814  5830 D bt_hci  : do_postload posting postload work item
09-28 06:47:48.139  5814  5834 I bt_hci  : event_postload
09-28 06:47:48.139  5814  5834 I bt_vendor: sco_config_cb
,09-28 06:47:48.140  5814  5834 I bt_hci  : sco_config_callback postload finished.
09-28 06:47:48.142  5814  5830 D bt_bte_conf: Device ID record 1 : primary
09-28 06:47:48.142  5814  5830 D bt_bte_conf:   vendorId            = 000f
09-28 06:47:48.142  5814  5830 D bt_bte_conf:   vendorIdSource      = 0001
09-28 06:47:48.143  5814  5830 D bt_bte_conf:   product             = 1200
09-28 06:47:48.143  5814  5830 D bt_bte_conf:   version             = 1436
09-28 06:47:48.143  5814  5830 D bt_bte_conf:   clientExecutableURL = 
09-28 06:47:48.143  5814  5830 D bt_bte_conf:   serviceDescription  = 
09-28 06:47:48.143  5814  5830 D bt_bte_conf:   documentationURL    = 
09-28 06:47:48.143  5814  5830 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 06:47:48.143  5814  5827 D bt_stack_manager: event_start_up_stack finished
09-28 06:47:48.144  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 06:47:48.145  5814  5826 D BluetoothAdapterProperties: Setting state to 15
09-28 06:47:48.145  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:48.145  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 06:47:48.146  5814  5826 I BluetoothAdapterState: Entering BleOnState
,09-28 06:47:48.148  5814  5834 I bt_vendor: low_power_mode_cb
09-28 06:47:48.150  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:48.151  5814  5826 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 06:47:48.151  5814  5826 D BluetoothAdapterProperties: Setting state to 11
09-28 06:47:48.151  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-28 06:47:48.155  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:48.159  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:47:48.159  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:48.160  5814  5814 D HeadsetService: Received start request. Starting profile...
09-28 06:47:48.161  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:48.162  5814  5814 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 06:47:48.162  5814  5814 D HeadsetStateMachine: make
09-28 06:47:48.162  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:48.168  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
,09-28 06:47:48.171  5814  5814 D HeadsetStateMachine: max_hf_connections = 1
,09-28 06:47:48.171  5814  5814 I bt_bluedroid: get_profile_interface handsfree
09-28 06:47:48.172  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 06:47:48.172  5814  5830 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-28 06:47:48.176  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:47:48.177  5814  5814 D A2dpService: Received start request. Starting profile...
09-28 06:47:48.177  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 06:47:48.177  5814  5814 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 06:47:48.178  5814  5814 I bt_bluedroid: get_profile_interface avrcp
,09-28 06:47:48.184  5814  5814 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 06:47:48.184  5814  5814 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 06:47:48.184  5814  5814 D A2dpStateMachine: make
,09-28 06:47:48.185  5814  5814 I bt_bluedroid: get_profile_interface a2dp
09-28 06:47:48.186  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 06:47:48.187  5814  5845 D A2dpStateMachine: Enter Disconnected: -2
,09-28 06:47:48.188  5814  5814 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 06:47:48.188  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:47:48.191  5814  5814 D HidService: Received start request. Starting profile...
,09-28 06:47:48.191  5814  5814 I bt_bluedroid: get_profile_interface hidhost
09-28 06:47:48.192  5814  5830 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40b056d
09-28 06:47:48.192  5814  5814 D HidService: setHidService(): set to: null
09-28 06:47:48.192  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 06:47:48.192  5814  5814 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 06:47:48.193  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
09-28 06:47:48.193  5814  5814 D HealthService: Received start request. Starting profile...
09-28 06:47:48.194  5688  5688 D BluetoothInputDevice: Proxy object connected
09-28 06:47:48.194  5688  5688 D HidProfile: Bluetooth service connected
09-28 06:47:48.194  5814  5814 I bt_bluedroid: get_profile_interface health
09-28 06:47:48.195  5814  5814 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-28 06:47:48.195  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:47:48.196  5688  5688 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 06:47:48.196  5814  5814 D PanService: Received start request. Starting profile...
09-28 06:47:48.197  5814  5814 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 06:47:48.197  5814  5814 I bt_bluedroid: get_profile_interface pan
09-28 06:47:48.197  5688  5688 D PanProfile: Bluetooth service connected
,09-28 06:47:48.197  5814  5830 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-28 06:47:48.199  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:47:48.200  5814  5814 D BluetoothMapService: Received start request. Starting profile...
09-28 06:47:48.200  5688  5688 D BluetoothMap: Proxy object connected
,09-28 06:47:48.200  5814  5814 D BluetoothMapService: start()
09-28 06:47:48.200  5688  5688 D MapProfile: Bluetooth service connected
09-28 06:47:48.200  5688  5688 D BluetoothMap: getConnectedDevices()
09-28 06:47:48.201  5688  5688 D BluetoothMap: Bluetooth is Not enabled
,09-28 06:47:48.202  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 06:47:48.203  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-28 06:47:48.203  5814  5814 D BluetoothMapAppObserver: createReceiver()
09-28 06:47:48.204  5814  5814 D BluetoothMapAppObserver: initObservers()
09-28 06:47:48.204  5814  5814 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 06:47:48.210  5814  5814 V SapService: SapBinder()
,09-28 06:47:48.210  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
09-28 06:47:48.211  5814  5814 D SapService: Received start request. Starting profile...
09-28 06:47:48.211  5814  5814 V SapService: start()
,09-28 06:47:48.214  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,09-28 06:47:48.214  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-28 06:47:48.214  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:48.214  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:48.215  5814  5843 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 06:47:48.215  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:48.215  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-28 06:47:48.215  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:48.215  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:48.215  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isTurningOn()=true
,09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-28 06:47:48.216  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:48.217  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:48.217  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:48.217  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-28 06:47:48.217  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:48.217  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 06:47:48.218  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:48.218  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-28 06:47:48.218  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:48.218  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 06:47:48.218  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 06:47:48.218  5814  5826 D BluetoothAdapterProperties: ScanMode =  20
09-28 06:47:48.218  5814  5826 D BluetoothAdapterProperties: State =  11
09-28 06:47:48.220  5814  5830 D BluetoothAdapterProperties: Scan Mode:21
09-28 06:47:48.220  5814  5830 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 06:47:48.220  5814  5826 D BluetoothAdapterProperties: Setting state to 12
09-28 06:47:48.220  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-28 06:47:48.220  5814  5826 I BluetoothAdapterState: Entering OnState
,09-28 06:47:48.221  5688  5702 D BluetoothMap: onBluetoothStateChange: up=true
09-28 06:47:48.221   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 06:47:48.222  5688  5700 D BluetoothPan: onBluetoothStateChange on: true
09-28 06:47:48.222  3811  3985 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 06:47:48.222   927   927 D BluetoothA2dp: Proxy object connected
09-28 06:47:48.223  3125  3963 D BluetoothPan: onBluetoothStateChange on: true
09-28 06:47:48.225  3125  3137 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 06:47:48.225  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 06:47:48.225  3125  3125 D PanProfile: Bluetooth service connected
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:48.225  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:48.226  3125  3139 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 06:47:48.227  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:47:48.227  5688  5702 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 06:47:48.227  3125  3125 D BluetoothInputDevice: Proxy object connected
09-28 06:47:48.227  3125  3125 D HidProfile: Bluetooth service connected
09-28 06:47:48.227  3125  3137 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 06:47:48.229  3125  3139 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 06:47:48.229  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 06:47:48.230  5814  5814 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 06:47:48.230  3125  3963 D BluetoothMap: onBluetoothStateChange: up=true
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:48.230  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:47:48.231  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:47:48.231  3125  3125 D BluetoothA2dp: Proxy object connected
09-28 06:47:48.232   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 06:47:48.232   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 06:47:48.232  5688  5700 D BluetoothPbap: onBluetoothStateChange: up=true
,09-28 06:47:48.233  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:48.233  3125  3125 D BluetoothMap: Proxy object connected
09-28 06:47:48.233  3125  3125 D MapProfile: Bluetooth service connected
09-28 06:47:48.233  3125  3125 D BluetoothMap: getConnectedDevices()
09-28 06:47:48.234  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:47:48.235   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:48.236  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:48.236  5814  5814 D ObexServerSockets: Succeed to create listening sockets 
09-28 06:47:48.236  5814  5814 D ObexServerSockets0: startAccept()
09-28 06:47:48.236  5814  5814 D ObexServerSockets0: prepareForNewConnect()
09-28 06:47:48.237   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 06:47:48.238  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:47:48.239  5814  5814 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 06:47:48.239  5814  5814 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 06:47:48.240  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:48.240  5814  5814 D BluetoothMapService: onReceive
09-28 06:47:48.240  5814  5814 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 06:47:48.240  5814  5814 D BluetoothMapService: STATE_ON
09-28 06:47:48.241  5814  5853 D ObexServerSockets0: Accepting socket connection...
09-28 06:47:48.241  5814  5854 D ObexServerSockets0: Accepting socket connection...
,09-28 06:47:48.242  5688  5688 D LocalBluetoothProfileManager: Adding local A2DP profile
09-28 06:47:48.242  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:48.243  5814  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:47:48.244  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:48.245  5814  5856 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 06:47:48.245  5814  5856 D BluetoothSdpJni: SDP Create record success - handle: 1
09-28 06:47:48.245  5688  5688 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-28 06:47:48.251  5688  5688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 06:47:48.253  5688  5688 D BluetoothA2dp: Proxy object connected
,09-28 06:47:48.258  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 06:47:48.259  5688  5688 D DockEventReceiver: finishStartingService: stopping service
,09-28 06:47:48.265  3125  3125 D BluetoothPbap: Proxy object connected
,09-28 06:47:48.265  3125  3125 D PbapServerProfile: Bluetooth service connected
09-28 06:47:48.265  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 06:47:48.266  5814  5814 D ObexServerSockets0: prepareForNewConnect()
09-28 06:47:48.268  5688  5688 D BluetoothPbap: Proxy object connected
09-28 06:47:48.269  5688  5688 D PbapServerProfile: Bluetooth service connected
,09-28 06:47:48.275  5814  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 06:47:48.286  5814  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 06:47:48.288  5814  5864 I BtOppRfcommListener: Accept thread started.
,09-28 06:47:48.314   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:47:48.325   927   927 D BluetoothHeadset: Proxy object connected
,09-28 06:47:48.325   927   927 D BluetoothHeadset: Proxy object connected
,09-28 06:47:48.326  3811  3838 D BluetoothHeadset: Proxy object connected
09-28 06:47:48.326   927   927 D BluetoothHeadset: Proxy object connected
09-28 06:47:48.326  3125  3966 D BluetoothHeadset: Proxy object connected
09-28 06:47:48.327  3125  3139 D BluetoothHeadset: Proxy object connected
09-28 06:47:48.327  3125  3125 D HeadsetProfile: Bluetooth service connected
,09-28 06:47:48.329  3125  3125 D HeadsetProfile: Bluetooth service connected
,09-28 06:47:48.332   927   944 D BluetoothHeadset: Proxy object connected
,09-28 06:47:48.332   927   944 D BluetoothHeadset: Proxy object connected
,09-28 06:47:48.336   927   944 D BluetoothHeadset: Proxy object connected
,09-28 06:47:48.348  5688  5700 D BluetoothHeadset: Proxy object connected
,09-28 06:47:48.349  5688  5688 D HeadsetProfile: Bluetooth service connected
,09-28 06:47:49.314   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 06:47:50.058   927  3011 D ConnectivityService: handlePromptUnvalidated 101
,09-28 06:47:52.167  5814  5826 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 06:47:52.167  5814  5826 D BluetoothAdapterProperties: Setting state to 13
09-28 06:47:52.167  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 06:47:52.168  5814  5826 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 06:47:52.171  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
,09-28 06:47:52.178  5814  5814 D BluetoothMapService: onReceive
,09-28 06:47:52.178  5814  5814 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 06:47:52.179  5814  5814 D BluetoothMapService: STATE_TURNING_OFF
09-28 06:47:52.179  5814  5814 D BluetoothMapService: MAP Service closeService in
09-28 06:47:52.179  5814  5814 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 06:47:52.180  5814  5814 D ObexServerSockets0: shutdown(block = true)
09-28 06:47:52.180  5814  5853 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-28 06:47:52.184  5814  5830 D BluetoothAdapterProperties: Scan Mode:20
09-28 06:47:52.185  5814  5814 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 06:47:52.185  5814  5814 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 06:47:52.185  5688  5688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 06:47:52.185  5814  5839 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 06:47:52.185  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 06:47:52.185  5814  5854 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 06:47:52.186  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:52.186  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:52.186  5814  5814 I BtOppRfcommListener: stopping Accept Thread
09-28 06:47:52.187  5814  5864 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 06:47:52.187  5814  5864 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-28 06:47:52.188  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 06:47:52.188  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:52.191  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:52.192  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:52.193  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:52.193  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:52.194  5814  5814 D HeadsetService: Received stop request...Stopping profile...
09-28 06:47:52.195  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:52.195   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:47:52.195  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:47:52.195   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:52.196  3811  3836 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:52.196  5814  5814 D A2dpService: Received stop request...Stopping profile...
09-28 06:47:52.196  5634  5634 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 06:47:52.196  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:47:52.196  5814  5845 D A2dpStateMachine: Exit Disconnected: -1
,09-28 06:47:52.197  5688  5702 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:52.198  3125  3125 D BluetoothA2dp: Proxy object disconnected
09-28 06:47:52.198  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:52.198   927   927 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:52.198  5814  5814 D HidService: Received stop request...Stopping profile...
09-28 06:47:52.199  5814  5814 D HidService: Stopping Bluetooth HidService
09-28 06:47:52.199  3125  3139 D BluetoothHeadset: Proxy object disconnected
09-28 06:47:52.199  3125  3125 D HeadsetProfile: Bluetooth service disconnected
09-28 06:47:52.199   927   927 D BluetoothA2dp: Proxy object disconnected
09-28 06:47:52.201  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:52.201  5814  5814 D HealthService: Received stop request...Stopping profile...
09-28 06:47:52.202  3125  3125 D BluetoothInputDevice: Proxy object disconnected
09-28 06:47:52.202  3125  3125 D HidProfile: Bluetooth service disconnected
09-28 06:47:52.203  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:52.203  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 06:47:52.205  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:52.205  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:52.205  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:52.205  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:52.208  5688  5688 D DockEventReceiver: finishStartingService: stopping service
09-28 06:47:52.208  5814  5814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 06:47:52.208  5814  5814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 06:47:52.208  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 06:47:52.208  5814  5837 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 06:47:52.208  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:52.208  5814  5837 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:52.208  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:52.208  5814  5837 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:52.208  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:52.208  5814  5830 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 06:47:52.209  5688  5688 D HeadsetProfile: Bluetooth service disconnected
09-28 06:47:52.208  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:52.209  5688  5688 D BluetoothA2dp: Proxy object disconnected
09-28 06:47:52.209  5688  5688 D BluetoothInputDevice: Proxy object disconnected
09-28 06:47:52.209  5688  5688 D HidProfile: Bluetooth service disconnected
,09-28 06:47:52.211  5814  5837 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:52.212  5814  5837 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 06:47:52.212  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:52.212  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:52.212  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:52.212  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 06:47:52.212  5814  5837 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 06:47:52.212  5814  5837 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 06:47:52.212  5814  5837 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 06:47:52.212  5814  5837 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 06:47:52.212  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:52.213  5814  5814 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 06:47:52.213  5814  5814 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 06:47:52.213  5814  5830 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 06:47:52.215  3125  3125 D BluetoothPbap: Proxy object disconnected
,09-28 06:47:52.215  3125  3125 D PbapServerProfile: Bluetooth service disconnected
09-28 06:47:52.215  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:52.215  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:52.215  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:52.215  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:52.215  5814  5814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 06:47:52.216  5814  5830 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 06:47:52.216  5814  5814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 06:47:52.216  5814  5814 D PanService: Received stop request...Stopping profile...
09-28 06:47:52.217  3125  3125 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 06:47:52.217  3125  3125 D PanProfile: Bluetooth service disconnected
09-28 06:47:52.217  5688  5688 D BluetoothPbap: Proxy object disconnected
09-28 06:47:52.217  5688  5688 D PbapServerProfile: Bluetooth service disconnected
09-28 06:47:52.218  5814  5814 D BluetoothMapService: Received stop request...Stopping profile...
09-28 06:47:52.218  5814  5814 D BluetoothMapService: stop()
09-28 06:47:52.218  5688  5688 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 06:47:52.218  5688  5688 D PanProfile: Bluetooth service disconnected
09-28 06:47:52.219  5814  5814 D BluetoothMapAppObserver: deinitObservers()
09-28 06:47:52.219  5814  5814 D BluetoothMapAppObserver: removeReceiver()
,09-28 06:47:52.222  3125  3125 D BluetoothMap: Proxy object disconnected
09-28 06:47:52.222  3125  3125 D MapProfile: Bluetooth service disconnected
09-28 06:47:52.222  5688  5688 D BluetoothMap: Proxy object disconnected
09-28 06:47:52.222  5688  5688 D MapProfile: Bluetooth service disconnected
,09-28 06:47:52.223  5814  5814 D SapService: Received stop request...Stopping profile...
09-28 06:47:52.223  5814  5814 V SapService: stop()
,09-28 06:47:52.224  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:52.224  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:52.224  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 06:47:52.224  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:52.225  5814  5814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 06:47:52.225  5814  5814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 06:47:52.226  5814  5814 D BluetoothMapService: MAP Service closeService in
09-28 06:47:52.226  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:52.226  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:52.226  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:52.233  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:52.233  5814  5814 D BluetoothMapService: cleanup()
09-28 06:47:52.233  5814  5814 D BluetoothMapService: MAP Service closeService in
09-28 06:47:52.233  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-28 06:47:52.234  5814  5814 V BluetoothAdapterState: isTurningOn()=false
,09-28 06:47:52.234  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:52.234  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:47:52.234  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 06:47:52.234  5814  5826 D BluetoothAdapterProperties: Setting state to 15
09-28 06:47:52.234  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 06:47:52.234  5814  5826 I BluetoothAdapterState: Entering BleOnState
09-28 06:47:52.234  5688  5700 D BluetoothMap: onBluetoothStateChange: up=false
09-28 06:47:52.235   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 06:47:52.235  5688  5868 D BluetoothPan: onBluetoothStateChange on: false
09-28 06:47:52.236  5688  5702 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 06:47:52.236  3811  3985 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:52.237  3125  3963 D BluetoothPan: onBluetoothStateChange on: false
09-28 06:47:52.237  3125  3137 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:52.237  3125  3139 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-28 06:47:52.238  5688  5700 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 06:47:52.239  3125  3966 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 06:47:52.239  5688  5868 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:52.240  3125  3963 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 06:47:52.240  3125  3137 D BluetoothMap: onBluetoothStateChange: up=false
09-28 06:47:52.240   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:52.241   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:52.241  5688  5702 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 06:47:52.241   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 06:47:52.242  5814  5826 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-28 06:47:52.242  5814  5826 D BluetoothAdapterProperties: Setting state to 16
09-28 06:47:52.242  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 06:47:52.242  5814  5826 D BluetoothAdapterProperties: onBleDisable
09-28 06:47:52.242  5814  5826 I BluetoothAdapterState: Entering PendingCommandState
09-28 06:47:52.243  5814  5827 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-28 06:47:52.244  5814  5830 D BluetoothAdapterProperties: Scan Mode:20
09-28 06:47:52.245  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:52.246  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:52.247  5814  5837 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 06:47:52.247  5814  5837 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 06:47:52.247  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:52.248  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:52.250  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:47:52.250  5688  5688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 06:47:52.252  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:47:52.255  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 06:47:52.256  5688  5688 D DockEventReceiver: finishStartingService: stopping service
,09-28 06:47:52.454  5814  5830 I bt_hci  : shut_down
,09-28 06:47:52.459  5814  5834 D bt_hwcfg: hw_epilog_process
,09-28 06:47:52.460  5814  5834 I bt_vendor: low_power_mode_cb
,09-28 06:47:52.462  5814  5834 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 06:47:52.462  5814  5834 I bt_vendor: epilog_cb
09-28 06:47:52.462  5814  5834 I bt_hci  : epilog_finished_callback
,09-28 06:47:52.464  5814  5830 I bt_hci_h4: hal_close
,09-28 06:47:52.464  5814  5830 I bt_userial_vendor: device fd = 54 close
,09-28 06:47:52.577  5814  5827 D bt_stack_manager: event_shut_down_stack finished.
,09-28 06:47:52.577  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 06:47:52.580  5814  5814 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 06:47:52.580  5814  5826 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 06:47:52.580  5814  5814 D BtGatt.GattService: Received stop request...Stopping profile...
09-28 06:47:52.580  5814  5814 D BtGatt.GattService: stop()
09-28 06:47:52.580  5814  5814 D BtGatt.AdvertiseManager: advertise clients cleared
,09-28 06:47:52.582  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-28 06:47:52.583  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-28 06:47:52.583  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:47:52.583  5814  5814 V BluetoothAdapterState: isBleTurningOff()=true
09-28 06:47:52.583  5814  5826 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-28 06:47:52.583  5814  5826 D BluetoothAdapterProperties: Setting state to 10
09-28 06:47:52.583  5814  5826 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 06:47:52.584  5814  5826 I BluetoothAdapterState: Entering OffState
,09-28 06:47:52.585   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-28 06:47:52.592  5814  5814 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 06:47:52.592  5814  5814 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 06:47:52.593  5814  5814 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 06:47:52.594  5814  5827 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 06:47:52.599  5814  5814 I art     : System.exit called, status: 0
,09-28 06:47:52.600  5814  5814 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 06:47:52.630   927  3153 I ActivityManager: Process com.android.bluetooth (pid 5814) has died
,09-28 06:47:57.164  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:57.164  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:57.169  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:47:57.169  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@58439ef removed from the list
09-28 06:47:57.169  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:47:57.170  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:57.170  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:57.172  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:47:57.172  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92f9f85 added. We now have 4 listener(s)
09-28 06:47:57.173  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:47:57.174  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:47:57.175  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@92f9f85 removed from the list
09-28 06:47:57.175  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 06:47:57.175  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:47:57.175  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:47:57.179  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 06:47:57.179  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bfa1da added. We now have 4 listener(s)
,09-28 06:47:57.180  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:48:02.192  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:02.225   927   944 I ActivityManager: Start proc 5873:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 06:48:02.314  5873  5873 D AdapterServiceConfig: Adding HeadsetService
09-28 06:48:02.314  5873  5873 D AdapterServiceConfig: Adding A2dpService
09-28 06:48:02.314  5873  5873 D AdapterServiceConfig: Adding HidService
09-28 06:48:02.315  5873  5873 D AdapterServiceConfig: Adding HealthService
09-28 06:48:02.315  5873  5873 D AdapterServiceConfig: Adding PanService
09-28 06:48:02.315  5873  5873 D AdapterServiceConfig: Adding GattService
09-28 06:48:02.315  5873  5873 D AdapterServiceConfig: Adding BluetoothMapService
09-28 06:48:02.316  5873  5873 D AdapterServiceConfig: Adding SapService
,09-28 06:48:02.329   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76c9aa7:true
,09-28 06:48:02.329  5873  5873 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 06:48:02.332  5873  5873 I bt_bluedroid: init
09-28 06:48:02.333  5873  5885 I BluetoothAdapterState: Entering OffState
,09-28 06:48:02.335  5873  5886 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 06:48:02.335  5873  5886 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 06:48:02.336  5873  5886 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 06:48:02.336  5873  5886 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 06:48:02.337  5873  5873 I bt_bluedroid: get_profile_interface socket
,09-28 06:48:02.338  5873  5889 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 06:48:02.339  5873  5873 I bt_bluedroid: get_profile_interface sdp
09-28 06:48:02.340  5873  5889 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 06:48:02.345  5873  5883 I bt_bluedroid: config_hci_snoop_log
,09-28 06:48:02.346   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 06:48:02.351  5873  5885 D BluetoothAdapterState: Current state: OFF, message: 0
09-28 06:48:02.352  5873  5885 D BluetoothAdapterProperties: Setting state to 14
09-28 06:48:02.352  5873  5885 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-28 06:48:02.353  5873  5885 D BluetoothBondStateMachine: make
,09-28 06:48:02.355  5873  5891 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 06:48:02.359  5873  5885 I BluetoothAdapterState: Entering PendingCommandState
,09-28 06:48:02.360  5873  5873 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 06:48:02.363  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:48:02.363  5873  5873 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 06:48:02.364  5873  5873 D BtGatt.GattService: Received start request. Starting profile...
,09-28 06:48:02.364  5873  5873 D BtGatt.GattService: start()
,09-28 06:48:02.364  5873  5873 I bt_bluedroid: get_profile_interface gatt
09-28 06:48:02.365  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
09-28 06:48:02.365  5873  5873 D BtGatt.AdvertiseManager: advertise manager created
,09-28 06:48:02.372  5873  5873 V BluetoothAdapterState: isTurningOff()=false
,09-28 06:48:02.372  5873  5873 V BluetoothAdapterState: isTurningOn()=false
09-28 06:48:02.372  5873  5873 V BluetoothAdapterState: isBleTurningOn()=true
09-28 06:48:02.372  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:02.372  5873  5885 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 06:48:02.374  5873  5885 I bt_bluedroid: bt_bluedroid
09-28 06:48:02.374  5873  5886 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-28 06:48:02.374  5873  5886 I bt_hci  : start_up
,09-28 06:48:02.380  5873  5886 I bt_vendor: alloc value 0xf4111871
09-28 06:48:02.381  5873  5886 I bt_vendor: init
09-28 06:48:02.381  5873  5886 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 06:48:02.381  5873  5886 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 06:48:02.493  5873  5886 D bt_hci  : start_up starting async portion
,09-28 06:48:02.493  5873  5894 I bt_hci  : event_finish_startup
09-28 06:48:02.493  5873  5894 I bt_hci_h4: hal_open
09-28 06:48:02.493  5873  5894 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 06:48:02.494  5895  5895 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 06:48:02.497  5873  5894 I bt_userial_vendor: device fd = 54 open
,09-28 06:48:02.514  5873  5894 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 06:48:02.518  5873  5894 D bt_hwcfg: Chipset BCM4358A3
,09-28 06:48:02.518  5873  5894 D bt_hwcfg: Target name = [BCM4358A3]
09-28 06:48:02.518  5873  5894 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 06:48:03.029  5873  5894 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-28 06:48:03.030  5873  5894 D bt_hwcfg: Settlement delay -- 100 ms
,09-28 06:48:03.030  5873  5894 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 06:48:03.164  5873  5894 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 06:48:03.164  5873  5894 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-28 06:48:03.166  5873  5894 I bt_hwcfg: vendor lib fwcfg completed
,09-28 06:48:03.166  5873  5894 I bt_vendor: firmware callback
,09-28 06:48:03.166  5873  5894 I bt_hci  : firmware_config_callback
,09-28 06:48:03.175  5873  5897 I bt_btu  : btu_task pending for preload complete event
09-28 06:48:03.176  5873  5897 I bt_btu_task: Bluetooth chip preload is complete
,09-28 06:48:03.176  5873  5897 I bt_btu  : btu_task received preload complete event
,09-28 06:48:03.184  5873  5897 I         : BTE_InitTraceLevels -- TRC_HCI
09-28 06:48:03.184  5873  5897 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-28 06:48:03.184  5873  5897 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 06:48:03.185  5873  5897 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 06:48:03.186  5873  5897 I         : BTE_InitTraceLevels -- TRC_GATT
,09-28 06:48:03.186  5873  5897 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 06:48:03.186  5873  5897 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 06:48:03.186  5873  5897 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 06:48:03.282  5873  5897 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf408f549
,09-28 06:48:03.282  5873  5897 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf408f549 
,09-28 06:48:03.297  5873  5889 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,09-28 06:48:03.300  5873  5889 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 06:48:03.301  5873  5889 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-28 06:48:03.304  5873  5889 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 06:48:03.308  5873  5889 D BluetoothAdapterProperties: Scan Mode:20
09-28 06:48:03.308  5873  5889 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 06:48:03.309  5873  5889 D bt_hci  : do_postload posting postload work item
,09-28 06:48:03.309  5873  5894 I bt_hci  : event_postload
,09-28 06:48:03.309  5873  5894 I bt_vendor: sco_config_cb
,09-28 06:48:03.309  5873  5894 I bt_hci  : sco_config_callback postload finished.
09-28 06:48:03.315  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:03.317  5873  5889 D bt_bte_conf: Device ID record 1 : primary
09-28 06:48:03.317  5873  5889 D bt_bte_conf:   vendorId            = 000f
09-28 06:48:03.317  5873  5889 D bt_bte_conf:   vendorIdSource      = 0001
,09-28 06:48:03.317  5873  5889 D bt_bte_conf:   product             = 1200
09-28 06:48:03.317  5873  5889 D bt_bte_conf:   version             = 1436
09-28 06:48:03.317  5873  5889 D bt_bte_conf:   clientExecutableURL = 
09-28 06:48:03.318  5873  5889 D bt_bte_conf:   serviceDescription  = 
09-28 06:48:03.318  5873  5889 D bt_bte_conf:   documentationURL    = 
09-28 06:48:03.318  5873  5889 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 06:48:03.318  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:03.319  5873  5886 D bt_stack_manager: event_start_up_stack finished
,09-28 06:48:03.321  5873  5885 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 06:48:03.322  5873  5885 D BluetoothAdapterProperties: Setting state to 15
09-28 06:48:03.322  5873  5885 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-28 06:48:03.322  5873  5894 I bt_vendor: low_power_mode_cb
,09-28 06:48:03.323  5873  5885 I BluetoothAdapterState: Entering BleOnState
09-28 06:48:03.327  5873  5885 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 06:48:03.327  5873  5885 D BluetoothAdapterProperties: Setting state to 11
09-28 06:48:03.327  5873  5885 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 06:48:03.335  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:48:03.336  5873  5873 D HeadsetService: Received start request. Starting profile...
,09-28 06:48:03.340  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:03.342  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:03.342  5873  5873 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 06:48:03.342  5873  5873 D HeadsetStateMachine: make
,09-28 06:48:03.353  5873  5885 I BluetoothAdapterState: Entering PendingCommandState
,09-28 06:48:03.354  5873  5873 D HeadsetStateMachine: max_hf_connections = 1
,09-28 06:48:03.354  5873  5873 I bt_bluedroid: get_profile_interface handsfree
09-28 06:48:03.354  5873  5889 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-28 06:48:03.358  5873  5889 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-28 06:48:03.358  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:48:03.359  5873  5873 D A2dpService: Received start request. Starting profile...
,09-28 06:48:03.359  5873  5873 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 06:48:03.360  5873  5873 I bt_bluedroid: get_profile_interface avrcp
,09-28 06:48:03.369  5873  5873 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-28 06:48:03.369  5873  5873 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 06:48:03.369  5873  5873 D A2dpStateMachine: make
,09-28 06:48:03.371  5873  5873 I bt_bluedroid: get_profile_interface a2dp
,09-28 06:48:03.373  5873  5904 D A2dpStateMachine: Enter Disconnected: -2
,09-28 06:48:03.373  5873  5873 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 06:48:03.374  5873  5889 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 06:48:03.375  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
09-28 06:48:03.375  5873  5873 D HidService: Received start request. Starting profile...
09-28 06:48:03.375  5873  5873 I bt_bluedroid: get_profile_interface hidhost
09-28 06:48:03.376  5873  5889 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf407056d
09-28 06:48:03.376  5873  5873 D HidService: setHidService(): set to: null
09-28 06:48:03.376  5873  5889 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-28 06:48:03.376  5873  5873 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-28 06:48:03.377  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:48:03.378  5873  5873 D HealthService: Received start request. Starting profile...
,09-28 06:48:03.380  5873  5873 I bt_bluedroid: get_profile_interface health
,09-28 06:48:03.382  5873  5873 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-28 06:48:03.383  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:48:03.383  5873  5873 D PanService: Received start request. Starting profile...
09-28 06:48:03.383  5873  5873 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 06:48:03.384  5873  5873 I bt_bluedroid: get_profile_interface pan
,09-28 06:48:03.384  5873  5889 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-28 06:48:03.384  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 06:48:03.387  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:48:03.388  5873  5873 D BluetoothMapService: Received start request. Starting profile...
,09-28 06:48:03.388  5873  5873 D BluetoothMapService: start()
09-28 06:48:03.391  5873  5873 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-28 06:48:03.392  5873  5873 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 06:48:03.392  5873  5873 D BluetoothMapAppObserver: createReceiver()
,09-28 06:48:03.394  5873  5873 D BluetoothMapAppObserver: initObservers()
09-28 06:48:03.394  5873  5873 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 06:48:03.400  5873  5873 V SapService: SapBinder()
,09-28 06:48:03.400  5873  5873 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
,09-28 06:48:03.401  5873  5873 D SapService: Received start request. Starting profile...
09-28 06:48:03.401  5873  5873 V SapService: start()
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOff()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOn()=true
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:48:03.403  5873  5902 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOff()=false
,09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOn()=true
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOff()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOn()=true
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOff()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isTurningOn()=true
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:48:03.403  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isTurningOff()=false
09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isTurningOn()=true
09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isTurningOff()=false
09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isTurningOn()=true
09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 06:48:03.404  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:03.405  5873  5873 V BluetoothAdapterState: isTurningOff()=false
09-28 06:48:03.405  5873  5873 V BluetoothAdapterState: isTurningOn()=true
09-28 06:48:03.405  5873  5873 V BluetoothAdapterState: isBleTurningOn()=false
09-28 06:48:03.405  5873  5873 V BluetoothAdapterState: isBleTurningOff()=false
09-28 06:48:03.406  5873  5885 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 06:48:03.406  5873  5885 D BluetoothAdapterProperties: ScanMode =  20
09-28 06:48:03.406  5873  5885 D BluetoothAdapterProperties: State =  11
,09-28 06:48:03.410  5873  5889 D BluetoothAdapterProperties: Scan Mode:21
,09-28 06:48:03.410  5873  5885 D BluetoothAdapterProperties: Setting state to 12
09-28 06:48:03.410  5873  5885 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 06:48:03.410  5873  5889 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 06:48:03.411  5873  5885 I BluetoothAdapterState: Entering OnState
,09-28 06:48:03.411  5688  5868 D BluetoothMap: onBluetoothStateChange: up=true
09-28 06:48:03.414   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 06:48:03.415  5688  5688 D BluetoothMap: Proxy object connected
09-28 06:48:03.415  5688  5688 D MapProfile: Bluetooth service connected
09-28 06:48:03.415  5688  5688 D BluetoothMap: getConnectedDevices()
09-28 06:48:03.415  5688  5700 D BluetoothPan: onBluetoothStateChange on: true
,09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:48:03.417  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:48:03.418  5688  5868 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-28 06:48:03.418   927   927 D BluetoothA2dp: Proxy object connected
09-28 06:48:03.420  3811  3838 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 06:48:03.420  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:48:03.420  3125  3137 D BluetoothPan: onBluetoothStateChange on: true
,09-28 06:48:03.421  5873  5873 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 06:48:03.421  5873  5873 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 06:48:03.422  3125  3125 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 06:48:03.422  3125  3125 D PanProfile: Bluetooth service connected
09-28 06:48:03.422  3125  3139 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 06:48:03.423  5873  5873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:48:03.423  3125  3966 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:48:03.423  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 06:48:03.424  5873  5873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:48:03.425  5688  5868 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 06:48:03.425  5873  5873 D ObexServerSockets: Succeed to create listening sockets 
09-28 06:48:03.425  5873  5873 D ObexServerSockets0: startAccept()
09-28 06:48:03.425  5873  5873 D ObexServerSockets0: prepareForNewConnect()
09-28 06:48:03.425  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:48:03.426  3125  3963 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 06:48:03.428  5873  5873 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 06:48:03.428  5873  5873 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-28 06:48:03.429  5688  5700 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 06:48:03.430  3125  3137 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 06:48:03.431  5873  5910 D ObexServerSockets0: Accepting socket connection...
,09-28 06:48:03.431  5873  5911 D ObexServerSockets0: Accepting socket connection...
09-28 06:48:03.431  3125  3125 D BluetoothInputDevice: Proxy object connected
09-28 06:48:03.431  3125  3125 D HidProfile: Bluetooth service connected
09-28 06:48:03.432  5688  5688 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 06:48:03.432  5688  5688 D PanProfile: Bluetooth service connected
09-28 06:48:03.433  3125  3125 D BluetoothA2dp: Proxy object connected
,09-28 06:48:03.433  3125  3139 D BluetoothMap: onBluetoothStateChange: up=true
09-28 06:48:03.434  3125  3125 D BluetoothMap: Proxy object connected
09-28 06:48:03.434  3125  3125 D MapProfile: Bluetooth service connected
09-28 06:48:03.434  3125  3125 D BluetoothMap: getConnectedDevices()
,09-28 06:48:03.434   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 06:48:03.434   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 06:48:03.434  5688  5700 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 06:48:03.436   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 06:48:03.432  5688  5688 D BluetoothA2dp: Proxy object connected
09-28 06:48:03.436   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 06:48:03.437  5873  5873 D BluetoothMapService: onReceive
,09-28 06:48:03.437  5873  5873 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 06:48:03.437  5873  5873 D BluetoothMapService: STATE_ON
09-28 06:48:03.438  5688  5688 D BluetoothInputDevice: Proxy object connected
09-28 06:48:03.438  5688  5688 D HidProfile: Bluetooth service connected
09-28 06:48:03.439  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:03.439  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:03.440  5873  5913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:48:03.442  5873  5913 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 06:48:03.442  5873  5913 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 06:48:03.444  5688  5688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 06:48:03.449  3575  3575 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 06:48:03.450  5688  5688 D DockEventReceiver: finishStartingService: stopping service
,09-28 06:48:03.457  5688  5688 D BluetoothPbap: Proxy object connected
,09-28 06:48:03.458  5688  5688 D PbapServerProfile: Bluetooth service connected
,09-28 06:48:03.462  5873  5917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 06:48:03.463  5873  5873 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 06:48:03.463  5873  5873 D ObexServerSockets0: prepareForNewConnect()
09-28 06:48:03.466  3125  3125 D BluetoothPbap: Proxy object connected
09-28 06:48:03.466  3125  3125 D PbapServerProfile: Bluetooth service connected
,09-28 06:48:03.481  5873  5921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 06:48:03.483  5873  5921 I BtOppRfcommListener: Accept thread started.
,09-28 06:48:03.523   927   927 D BluetoothHeadset: Proxy object connected
,09-28 06:48:03.523   927   927 D BluetoothHeadset: Proxy object connected
09-28 06:48:03.523  3811  3836 D BluetoothHeadset: Proxy object connected
09-28 06:48:03.523  3125  3963 D BluetoothHeadset: Proxy object connected
,09-28 06:48:03.523  3125  3125 D HeadsetProfile: Bluetooth service connected
,09-28 06:48:03.524  5688  5702 D BluetoothHeadset: Proxy object connected
09-28 06:48:03.524   927   927 D BluetoothHeadset: Proxy object connected
09-28 06:48:03.525  3125  3137 D BluetoothHeadset: Proxy object connected
09-28 06:48:03.527  3125  3125 D HeadsetProfile: Bluetooth service connected
09-28 06:48:03.529  5688  5688 D HeadsetProfile: Bluetooth service connected
09-28 06:48:03.530  5688  5868 D BluetoothHeadset: Proxy object connected
,09-28 06:48:03.531  5688  5688 D HeadsetProfile: Bluetooth service connected
09-28 06:48:03.534   927   944 D BluetoothHeadset: Proxy object connected
09-28 06:48:03.535   927   944 D BluetoothHeadset: Proxy object connected
,09-28 06:48:03.536   927   944 D BluetoothHeadset: Proxy object connected
,09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:48:07.208  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:48:07.213  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:48:07.213  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:48:07.214  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bfa1da removed from the list
,09-28 06:48:07.214  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 06:48:07.214  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:07.214  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:07.216  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:48:07.216  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a84860b added. We now have 4 listener(s)
,09-28 06:48:07.216  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 06:48:07.220   927   937 D WifiService: setWifiEnabled: false pid=5634, uid=10077
,09-28 06:48:07.221   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 06:48:09.315   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:10.317   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:11.318   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:12.231  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:12.232   927  3414 D WifiService: setWifiEnabled: true pid=5634, uid=10077
09-28 06:48:12.232   927  3414 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 06:48:12.240   508   921 D SoftapController: Softap fwReload - Ok
,09-28 06:48:12.245   508   921 D CommandListener: Setting iface cfg
,09-28 06:48:12.246   508   921 D CommandListener: Trying to bring down wlan0
,09-28 06:48:12.248   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-28 06:48:12.254   927  3000 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 06:48:12.319   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:12.920   927  3000 D wifi    : set interface wlan0 flags (UP)
,09-28 06:48:12.921   927  3000 I WifiHAL : Initializing wifi
09-28 06:48:12.922   927  3000 I WifiHAL : Creating socket
,09-28 06:48:12.929   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 06:48:12.932   927  3000 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 06:48:12.932   927  3000 D wifi    : Did set static halHandle = 0x7f91068340
09-28 06:48:12.932   927  3000 D wifi    : halHandle = 0x7f91068340, mVM = 0x7fad6cd140, mCls = 0x10161a
09-28 06:48:12.932   927  3000 D wifi    : array field set
09-28 06:48:12.932   927  3000 I WifiNative-HAL: interface[0] = wlan0
,09-28 06:48:12.936   927  5926 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547893969728
,09-28 06:48:12.936   927  5926 D wifi    : waitForHalEvents called, vm = 0x7fad6cd140, obj = 0x10161a, env = 0x7f933a5740
,09-28 06:48:12.996  5927  5927 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 06:48:13.018  5927  5927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 06:48:13.036   927  3000 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-28 06:48:13.037   927  3000 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-28 06:48:13.045  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:13.051  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:13.054  5927  5927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-28 06:48:13.054  5927  5927 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 06:48:13.321   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:14.056   927  3000 D WifiConfigStore: Loading config and enabling all networks 
,09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:48:14.063  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:48:14.067  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:48:14.077  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:48:14.082  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 06:48:14.084   927  3000 D WifiConfigStore: loaded 0 passpoint configs
,09-28 06:48:14.084   927  3000 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 06:48:14.085   927  3000 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 06:48:14.086   927  3000 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 06:48:14.088   927  3000 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 06:48:14.089   927  3000 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 06:48:14.089   927  3000 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 06:48:14.089   927  3000 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 06:48:14.093   927  3000 D WifiNative-HAL: Setting external_sim to 1
,09-28 06:48:14.094  5029  5029 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 06:48:14.094   927  3000 D wifi    : setting dfs flag to true, 0x7f915fa6a0
,09-28 06:48:14.095   927  3000 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 06:48:14.095   927  3000 D wifi    : setting scan oui 0x7f915fa6a0
09-28 06:48:14.095   927  3000 D WifiHAL : Sending mac address OUI
,09-28 06:48:14.101   927  3000 E native  : do suspend false
,09-28 06:48:14.114   927  3000 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 06:48:14.114   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-28 06:48:14.115   927   927 D RttService: SCAN_AVAILABLE : 3
09-28 06:48:14.115   927  3076 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 06:48:14.116   508   921 D CommandListener: Setting iface cfg
,09-28 06:48:14.121   927  2971 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-28 06:48:14.121   927  2971 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 06:48:14.127   927  2971 D WifiNative-HAL: p2pGetDeviceAddress
09-28 06:48:14.128   927  2971 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 06:48:14.163   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304016 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=42 mControllerEnergyUsed=159 }
,09-28 06:48:14.322   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 06:48:17.252  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 06:48:17.258  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 06:48:17.258  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:17.259  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a84860b removed from the list
09-28 06:48:17.259  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 06:48:17.259  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:17.259  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:17.267  5634  5929 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-28 06:48:17.267  5634  5929 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 06:48:17.287  5927  5927 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:48:17.289  5927  5927 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:48:17.291  5927  5927 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:48:17.293  5927  5927 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 06:48:17.345   927  3000 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 06:48:17.346   927  3000 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 06:48:17.346   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 06:48:17.356   927  3000 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 06:48:17.393   927  3000 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 06:48:17.395  5927  5927 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 06:48:17.950  5927  5927 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 06:48:18.016  5927  5927 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 06:48:18.017  5927  5927 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 06:48:18.033   927  3000 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 06:48:18.033   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 06:48:18.033   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 06:48:18.049   927  3000 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 06:48:18.062   508   921 D CommandListener: Setting iface cfg
,09-28 06:48:18.068   927  3000 D WifiStateMachine: Start Dhcp Watchdog 3
,09-28 06:48:18.074   927  5933 D DhcpClient: Receive thread started
,09-28 06:48:18.078   927  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-28 06:48:18.078   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 06:48:18.078   927  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 06:48:18.159   927  3000 E native  : do suspend false
,09-28 06:48:18.175   927  5932 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 06:48:18.201   927  5933 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,09-28 06:48:18.202   927  5932 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,09-28 06:48:18.205   927  5932 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 06:48:18.219   927  5933 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 06:48:18.220   927  5932 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-28 06:48:18.223   508   921 D CommandListener: Setting iface cfg
,09-28 06:48:18.228   927  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 06:48:18.232   927  5932 D DhcpClient: Scheduling renewal in 86399s
,09-28 06:48:18.241   927  3000 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-28 06:48:18.242   927  3000 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 06:48:18.243   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 06:48:18.245   927  3000 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-28 06:48:18.245   927  3011 D ConnectivityService: Adding iface wlan0 to network 102
,09-28 06:48:18.300   927  3011 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-28 06:48:18.300   927  3011 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-28 06:48:18.302   927  3011 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-28 06:48:18.304   927  3011 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-28 06:48:18.307   927  3011 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-28 06:48:18.318   927  3011 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 06:48:18.323   927  3011 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-28 06:48:18.323   927  3011 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-28 06:48:18.323   927  3011 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-28 06:48:18.323   927  3011 D ConnectivityService:    accepting network in place of null
09-28 06:48:18.323   927  3000 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 06:48:18.323   927  3000 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 06:48:18.324   927  3011 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 06:48:18.339   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308191, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:48:18.347   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 06:48:18.370   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,09-28 06:48:18.373   927  3011 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-28 06:48:18.373  3767  3891 W QCNEJ   : |CORE| network available: 102
09-28 06:48:18.373   927  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 06:48:18.374   927  3011 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-28 06:48:18.375  3767  3891 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 06:48:18.377  3767  3891 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 06:48:18.378  3767  3891 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-28 06:48:18.378   927   944 D Tethering: MasterInitialState.processMessage what=3
,09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:48:18.384  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:48:18.388  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:18.390  5054  5078 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 06:48:18.390  5054  5078 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 06:48:18.390  5054  5078 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 06:48:18.390  5054  5078 E SarControlService: no key has been found,reset the power
09-28 06:48:18.390  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 06:48:18.390  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 06:48:18.391  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 06:48:18.391  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 06:48:18.391  5079  5079 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:48:18.393  5634  5634 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 06:48:18.394  5054  5091 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 06:48:18.394  5054  5091 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-28 06:48:18.394  5054  5091 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 06:48:18.396  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 06:48:18.396  5634  5634 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:18.396  5079  5079 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 06:48:18.396  3724  3724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 06:48:18.399  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000f003000000000000ffffffff]
09-28 06:48:18.399  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:48:18.399  5079  5093 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-28 06:48:18.400  3724  3724 D SystemUpdateService: onCreate
,09-28 06:48:18.401  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 06:48:18.401  5054  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 06:48:18.404  5079  5093 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ca0a11a HexData = [00000000f103000000000000ffffffff]
09-28 06:48:18.404  5079  5093 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 06:48:18.404  5079  5093 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-28 06:48:18.405  5079  5079 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-28 06:48:18.405  5054  5064 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 06:48:18.406  3724  3724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 06:48:18.416  3724  3724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 06:48:18.424  3724  5943 I SystemUpdateService: active receiver: enabled
,09-28 06:48:18.425  3724  3724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 06:48:18.427  3724  3724 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 06:48:18.428  5412  5412 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-28 06:48:18.432  5412  5412 D SprintDMHelper: simOperator: 
09-28 06:48:18.432  5412  5412 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 06:48:18.433  3724  5409 I iu.UploadsManager: num queued entries: 0
,09-28 06:48:18.443  3724  5409 I iu.UploadsManager: num updated entries: 0
,09-28 06:48:18.443  3724  5409 I iu.SyncManager: NEXT; no task
,09-28 06:48:18.459  3724  5943 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 06:48:18.469  3724  5943 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 06:48:18.469  3724  5943 I SystemUpdateService: now status is 0 (complete)
09-28 06:48:18.469  3724  5943 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 06:48:18.469  3724  5943 I SystemUpdateService: file has been verified
09-28 06:48:18.469  3724  5943 I SystemUpdateService: OTA package size = 21989297
,09-28 06:48:18.474  3724  5943 I SystemUpdateService: showing system update notification
,09-28 06:48:18.482  3724  3724 D SystemUpdateService: onDestroy
,09-28 06:48:20.275  5634  5952 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-28 06:48:20.275  5634  5929 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-28 06:48:20.276  5634  5952 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 06:48:20.276  5634  5929 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 06:48:20.276  5634  5952 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 06:48:20.277  5634  5929 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 06:48:20.277  5634  5952 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 06:48:20.280  5634  5952 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-28 06:48:20.280  5634  5929 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 06:48:20.280  5634  5954 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: IncomingSocketThread/Sender)
,09-28 06:48:20.282  5634  5929 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 06:48:20.287  5634  5955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender)
,09-28 06:48:20.287  5634  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Receiver)
,09-28 06:48:20.288  5634  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Receiver)
09-28 06:48:20.288  5634  5956 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: IncomingSocketThread/Receiver)
09-28 06:48:20.289  5634  5956 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 06:48:20.289  5634  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 06:48:20.289  5634  5957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Receiver)
09-28 06:48:20.289  5634  5957 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 06:48:20.289  5634  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 06:48:21.102   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 06:48:23.275  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-28 06:48:23.276  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-28 06:48:23.281  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ace7abe Bundle[{}]
,09-28 06:48:23.282  5634  5680 I io.jxcore.node.LifeCycleMonitor: start: OK
09-28 06:48:23.283  5634  5680 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-28 06:48:23.284  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-28 06:48:23.286  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-28 06:48:23.287  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-28 06:48:23.288  5634  5680 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-28 06:48:23.292  5634  5680 I System.out: Running OutgoingSocketThread
,09-28 06:48:23.294  5634  5958 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-28 06:48:23.294  5634  5958 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 06:48:23.410   927  5930 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-28 06:48:23.470   927  5930 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 10:48:23 GMT], X-Android-Received-Millis=[1475059703468], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475059703436]}
,09-28 06:48:23.472   927  3011 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 06:48:23.473   927  3011 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-28 06:48:23.474   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 06:48:23.477   927  3011 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 06:48:23.544  5029  5948 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 06:48:26.305  5634  5962 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-28 06:48:26.305  5634  5958 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-28 06:48:26.306  5634  5958 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-28 06:48:26.306  5634  5962 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 06:48:26.306  5634  5962 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 06:48:26.306  5634  5958 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 06:48:26.308  5634  5962 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 06:48:26.309  5634  5958 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 06:48:26.313  5634  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: IncomingSocketThread/Sender)
,09-28 06:48:26.313  5634  5962 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-28 06:48:26.317  5634  5958 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 06:48:26.318  5634  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Sender)
,09-28 06:48:26.320  5634  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver)
,09-28 06:48:26.321  5634  5967 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver)
,09-28 06:48:26.321  5634  5967 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 06:48:26.321  5634  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 06:48:26.321  5634  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Receiver)
,09-28 06:48:26.323  5634  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: IncomingSocketThread/Receiver)
09-28 06:48:26.323  5634  5966 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-28 06:48:26.323  5634  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 06:48:26.324   927  3011 D ConnectivityService: handlePromptUnvalidated 102
,09-28 06:48:29.166   927  3000 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-28 06:48:29.304  5634  5680 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 180)
,09-28 06:48:29.306  5634  5680 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-28 06:48:29.306  5634  5680 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
09-28 06:48:29.312  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 06:48:29.312  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c69ce8 added. We now have 3 listener(s)
,09-28 06:48:29.315  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 06:48:29.315  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 06:48:29.315  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 06:48:29.316  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:48:29.316  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfaf01 added. We now have 4 listener(s)
09-28 06:48:29.316  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:48:29.317  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 06:48:29.323  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:48:29.330  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:48:29.334  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:48:29.334  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:48:29.335  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:48:29.336  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:48:29.336  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:48:29.336  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:29.336  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:48:29.336  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:29.336  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 06:48:29.336  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c69ce8 removed from the list
09-28 06:48:29.336  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:29.336  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfaf01 removed from the list
09-28 06:48:29.339  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:29.342  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:29.342  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:48:29.342  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:29.343  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:29.343  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:29.344  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:29.344  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:48:29.344  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:29.344  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfaf01 not in the list
,09-28 06:48:29.344  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:29.344  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:29.345  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 06:48:29.346  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:29.346  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:29.346  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfaf01 not in the list
09-28 06:48:29.346  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:29.346  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:29.346  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:29.346  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c69ce8 not in the list
09-28 06:48:29.347  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 06:48:29.347  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f377e7 added. We now have 3 listener(s)
09-28 06:48:29.348  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 06:48:29.348  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 06:48:29.348  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 06:48:29.349  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:48:29.349  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adc9f94 added. We now have 4 listener(s)
09-28 06:48:29.349  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 06:48:29.349  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 06:48:29.352  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:48:29.356  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:48:29.358  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:29.359  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:48:29.359  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:48:29.359  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 06:48:29.359  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-28 06:48:29.359  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:29.359  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:48:29.362  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:29.363  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:48:29.363  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 06:48:29.365  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:29.367  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 06:48:29.368  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:48:29.368  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 06:48:29.371  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 06:48:29.371  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 06:48:29.371  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 06:48:29.372  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:48:29.375  5873  5909 D BtGatt.GattService: registerClient() - UUID=2826ce0d-816f-4947-9d0b-7c7a06e6a0fe
,09-28 06:48:29.376  5873  5889 D BtGatt.GattService: onClientRegistered() - UUID=2826ce0d-816f-4947-9d0b-7c7a06e6a0fe, clientIf=5
,09-28 06:48:29.377  5634  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 06:48:29.378  5873  5912 D BtGatt.GattService: start scan with filters
,09-28 06:48:29.381  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 06:48:29.381  5873  5893 D BtGatt.ScanManager: handling starting scan
09-28 06:48:29.381  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 06:48:29.381  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 06:48:29.381  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 06:48:29.382  5873  5893 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@65761c3
09-28 06:48:29.383  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 06:48:29.384  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 06:48:29.384  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 06:48:29.385  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 06:48:29.387  5634  5680 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-28 06:48:29.388  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 06:48:29.388  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 06:48:29.388  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:29.388  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 06:48:29.388  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 06:48:29.388  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 06:48:29.388  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 06:48:29.388  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 06:48:29.388  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 06:48:29.388  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 06:48:29.389  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:48:29.390  5873  5889 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 06:48:29.390  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:29.390  5873  5909 D BtGatt.GattService: stopScan() - queue size =1
09-28 06:48:29.390  5873  5893 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 06:48:29.391  5873  5912 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 06:48:29.391  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 06:48:29.391  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 06:48:29.391  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 06:48:29.392  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 06:48:29.392  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 06:48:29.393  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 06:48:29.393  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:29.393  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 06:48:29.393  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:48:29.393  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:29.395  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:48:29.395  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:29.395  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:48:29.397  5873  5889 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 06:48:29.397  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:29.397  5873  5893 D BtGatt.ScanManager: Starting BLE batch scan
09-28 06:48:29.398  5873  5893 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 06:48:29.398  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:48:29.398  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 06:48:29.402  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 06:48:29.403  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:48:29.403  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:48:29.403  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:48:29.404  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:29.406  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:48:29.406  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:29.406  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:48:29.408  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:48:29.409  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:48:29.409  5873  5889 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 06:48:29.410  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:29.410  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:48:29.413  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 06:48:29.416  5873  5889 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 06:48:29.416  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:48:29.423  5873  5889 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 06:48:29.423  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:29.424  5873  5893 D BtGatt.ScanManager: stopping BLe Batch
,09-28 06:48:29.429  5873  5889 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 06:48:29.429  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:29.430  5873  5893 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 06:48:29.435  5873  5889 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 06:48:29.435  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:48:29.914  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 06:48:29.915  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:48:29.915  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 06:48:32.395  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:48:32.396  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:48:32.396  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:48:32.396  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:32.396  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:48:32.397  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:32.397  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 06:48:32.397  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f377e7 removed from the list
,09-28 06:48:32.397  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:32.398  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adc9f94 removed from the list
09-28 06:48:32.399  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:48:32.399  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:32.400  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:48:32.400  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:32.404  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 06:48:32.404  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:32.404  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:48:32.406  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:48:32.406  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:48:32.406  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 06:48:32.406  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:32.406  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adc9f94 not in the list
09-28 06:48:32.407  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:32.407  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:32.409  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 06:48:32.412  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:48:32.412  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:48:32.412  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:48:32.413  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:32.413  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:32.413  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:32.413  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adc9f94 not in the list
09-28 06:48:32.413  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 06:48:32.414  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:32.414  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:32.414  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f377e7 not in the list
,09-28 06:48:32.415  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 06:48:32.416  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7073f5 added. We now have 3 listener(s)
09-28 06:48:32.419  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 06:48:32.419  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 06:48:32.420  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 06:48:32.420  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:48:32.420  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4358a added. We now have 4 listener(s)
09-28 06:48:32.420  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 06:48:32.421  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 06:48:32.427  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:48:32.434  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:48:32.437  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:48:32.438  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:48:32.438  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-28 06:48:32.439  5634  5680 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-28 06:48:32.439  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-28 06:48:32.439  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 06:48:32.439  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-28 06:48:32.439  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-28 06:48:32.439  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:32.441  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-28 06:48:32.441  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 06:48:32.442  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:32.442  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 06:48:32.443  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 06:48:32.443  5634  5968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 06:48:32.443  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-28 06:48:32.444  5909  5909 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30608]" dev="sockfs" ino=30608 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 06:48:32.443  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:32.444  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:48:32.444  5909  5909 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30608]" dev="sockfs" ino=30608 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 06:48:32.447  5634  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-28 06:48:32.449  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:32.449  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-28 06:48:32.451  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 06:48:32.451  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 06:48:32.456  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 06:48:32.456  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:48:32.457  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:48:32.459  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-28 06:48:32.459  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 06:48:32.460  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-28 06:48:32.460  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-28 06:48:32.461  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-28 06:48:32.461  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-28 06:48:32.462  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:48:32.467  5873  5883 D BtGatt.GattService: registerClient() - UUID=b1c7b50e-af9e-4ae2-a266-63886735e3cf
,09-28 06:48:32.467  5873  5889 D BtGatt.GattService: onClientRegistered() - UUID=b1c7b50e-af9e-4ae2-a266-63886735e3cf, clientIf=5
09-28 06:48:32.468  5634  5644 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-28 06:48:32.470  5873  5892 D BtGatt.AdvertiseManager: message : 0
,09-28 06:48:32.472  5873  5892 D BtGatt.AdvertiseManager: starting multi advertising
,09-28 06:48:32.485  5873  5889 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-28 06:48:32.493  5873  5889 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-28 06:48:32.494  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-28 06:48:32.494  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 06:48:32.496  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 06:48:32.497  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-28 06:48:32.498  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-28 06:48:32.498  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-28 06:48:32.498  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-28 06:48:32.498  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-28 06:48:32.498  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-28 06:48:32.499  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-28 06:48:32.501  5634  5634 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 06:48:32.502  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-28 06:48:33.003  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-28 06:48:33.003  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 06:48:33.003  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 06:48:35.501  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:48:35.501  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-28 06:48:35.501  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 06:48:35.502  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 06:48:35.502  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-28 06:48:35.502  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-28 06:48:35.502  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-28 06:48:35.502  5634  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 06:48:35.503  5634  5680 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-28 06:48:35.503  5634  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 06:48:35.503  5634  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 06:48:35.503  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 06:48:35.503  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 06:48:35.503  5634  5634 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 06:48:35.503  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 06:48:35.503  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 06:48:35.503  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 06:48:35.506  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:48:35.506  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:48:35.506  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:48:35.507  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-28 06:48:35.509  5873  5892 D BtGatt.AdvertiseManager: message : 1
09-28 06:48:35.511  5873  5892 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-28 06:48:35.526  5873  5889 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-28 06:48:35.526  5873  5889 D BtGatt.GattService: Client app is not null!
09-28 06:48:35.527  5873  5909 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 06:48:35.528  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 06:48:35.528  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-28 06:48:35.528  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-28 06:48:35.528  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-28 06:48:35.529  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-28 06:48:35.531  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 06:48:35.531  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 06:48:35.532  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 06:48:35.533  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:48:35.536  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:35.536  5634  5634 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 06:48:35.536  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:35.536  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:35.536  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 06:48:35.536  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:48:35.536  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7073f5 removed from the list
09-28 06:48:35.536  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:35.536  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:35.536  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:48:35.536  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4358a removed from the list
09-28 06:48:35.536  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:48:35.537  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 06:48:35.542  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:48:35.542  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 06:48:35.548  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 06:48:35.549  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:48:35.549  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:48:35.549  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:48:35.550  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:35.553  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:35.553  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:35.555  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 06:48:35.555  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:35.555  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:48:35.556  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:48:35.556  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:48:35.556  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:48:35.556  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:35.556  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 06:48:35.556  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4358a not in the list
09-28 06:48:35.556  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:35.556  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 06:48:35.560  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:48:35.560  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 06:48:35.561  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:35.564  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:35.564  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 06:48:35.564  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:35.565  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:48:35.566  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:48:35.566  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:48:35.566  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:48:35.566  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:35.566  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:35.566  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:35.566  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b4358a not in the list
09-28 06:48:35.566  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:35.566  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:35.566  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:35.566  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7073f5 not in the list
09-28 06:48:35.567  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 06:48:35.567  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d687b73 added. We now have 3 listener(s)
,09-28 06:48:35.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 06:48:35.569  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 06:48:35.570  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 06:48:35.570  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:48:35.570  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90bca30 added. We now have 4 listener(s)
09-28 06:48:35.570  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 06:48:35.571  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 06:48:35.575  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:48:35.580  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:48:35.582  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:48:35.583  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 06:48:35.583  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:48:35.583  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 06:48:35.583  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 06:48:35.583  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 06:48:35.583  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 06:48:35.587  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:35.588  5634  5680 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 06:48:35.588  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 06:48:35.590  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:35.592  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 06:48:35.593  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:48:35.593  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 06:48:35.597  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 06:48:35.597  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 06:48:35.597  5634  5680 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 06:48:35.598  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:48:35.601  5873  5883 D BtGatt.GattService: registerClient() - UUID=050b5bce-ad3b-429b-881b-a14a0d1bedc7
,09-28 06:48:35.601  5873  5889 D BtGatt.GattService: onClientRegistered() - UUID=050b5bce-ad3b-429b-881b-a14a0d1bedc7, clientIf=5
09-28 06:48:35.602  5634  5644 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 06:48:35.602  5873  5884 D BtGatt.GattService: start scan with filters
,09-28 06:48:35.605  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 06:48:35.605  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 06:48:35.605  5873  5893 D BtGatt.ScanManager: handling starting scan
09-28 06:48:35.605  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 06:48:35.605  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 06:48:35.608  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 06:48:35.608  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 06:48:35.609  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 06:48:35.610  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 06:48:35.614  5873  5889 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 06:48:35.614  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:35.614  5873  5893 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 06:48:35.620  5873  5889 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 06:48:35.620  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:35.620  5873  5893 D BtGatt.ScanManager: Starting BLE batch scan
09-28 06:48:35.620  5873  5893 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 06:48:35.631  5873  5889 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 06:48:35.631  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:48:35.637  5873  5889 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 06:48:35.637  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:48:36.064  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 06:48:36.109  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 06:48:36.110  5634  5634 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:48:36.110  5634  5634 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-28 06:48:36.205   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 06:48:36.212   927  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 56
,09-28 06:48:38.620  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 06:48:38.620  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 06:48:38.620  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 06:48:38.620  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.621  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 06:48:38.621  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-28 06:48:38.621  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 06:48:38.621  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 06:48:38.621  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 06:48:38.622  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 06:48:38.622  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 06:48:38.624  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:48:38.625  5873  5909 D BtGatt.GattService: stopScan() - queue size =1
09-28 06:48:38.627  5873  5912 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 06:48:38.628  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:48:38.628  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 06:48:38.628  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 06:48:38.629  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 06:48:38.629  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 06:48:38.632  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 06:48:38.632  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:38.633  5634  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 06:48:38.633  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:48:38.634  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:38.634  5873  5873 D BtGatt.ScanManager: awakened up at time 328487
09-28 06:48:38.637  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:48:38.637  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:38.637  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:48:38.638  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:48:38.638  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.638  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 06:48:38.638  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-28 06:48:38.638  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d687b73 removed from the list
09-28 06:48:38.638  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:48:38.639  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90bca30 removed from the list
09-28 06:48:38.639  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:48:38.639  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:38.644  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:48:38.644  5873  5889 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 06:48:38.644  5634  5634 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 06:48:38.644  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 06:48:38.644  5873  5893 D BtGatt.ScanManager: stopping BLe Batch
09-28 06:48:38.651  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 06:48:38.652  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 06:48:38.652  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 06:48:38.652  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:48:38.653  5873  5889 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 06:48:38.653  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:38.653  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:38.653  5873  5893 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 06:48:38.656  5634  5634 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 06:48:38.656  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:48:38.656  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 06:48:38.661  5634  5634 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 06:48:38.661  5634  5634 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 06:48:38.662  5634  5634 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:38.666  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.666  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:38.666  5634  5634 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 06:48:38.668  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:38.668  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:38.668  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:48:38.669  5634  5680 D BluetoothAdapter: STATE_ON
09-28 06:48:38.669  5634  5680 D BluetoothLeScanner: could not find callback wrapper
09-28 06:48:38.669  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:48:38.669  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:38.669  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90bca30 not in the list
09-28 06:48:38.670  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.670  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:38.671  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:48:38.672  5634  5680 D BluetoothAdapter: STATE_ON
,09-28 06:48:38.672  5634  5680 D BluetoothLeScanner: could not find callback wrapper
,09-28 06:48:38.672  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 06:48:38.672  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:38.672  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 06:48:38.672  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:38.672  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90bca30 not in the list
09-28 06:48:38.672  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:38.672  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.672  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:38.672  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d687b73 not in the list
,09-28 06:48:38.673  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 06:48:38.673  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8acc1e1 added. We now have 3 listener(s)
09-28 06:48:38.673  5873  5889 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-28 06:48:38.673  5873  5889 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 06:48:38.674  5873  5889 D BtGatt.GattService: current time is 328526251053
09-28 06:48:38.674  5873  5889 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -73, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -76, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -77, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -81, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -73, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 06:48:38.675  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 06:48:38.675  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 06:48:38.675  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 06:48:38.675  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 06:48:38.675  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a74b06 added. We now have 4 listener(s)
09-28 06:48:38.676  5634  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 06:48:38.676  5873  5889 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 06:48:38.676  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 06:48:38.679  5873  5889 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 06:48:38.679  5873  5889 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 06:48:38.679  5873  5889 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 06:48:38.679  5873  5889 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-28 06:48:38.679  5873  5889 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 06:48:38.680  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 06:48:38.684  5634  5680 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 06:48:38.686  5634  5680 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 06:48:38.686  5634  5680 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 06:48:38.687  5634  5680 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 06:48:38.687  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 06:48:38.687  5634  5680 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 06:48:38.687  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:38.687  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.687  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 06:48:38.687  5634  5680 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 06:48:38.687  5634  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8acc1e1 removed from the list
09-28 06:48:38.687  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 06:48:38.687  5634  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a74b06 removed from the list
09-28 06:48:38.689  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 06:48:38.689  5634  5680 D io.jxcore.node.ConnectivityMonitor: stop
09-28 06:48:38.689  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:38.690  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.690  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 06:48:38.692  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:38.692  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 06:48:38.692  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:38.692  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a74b06 not in the list
,09-28 06:48:38.692  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 06:48:38.692  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:38.692  5634  5634 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 06:48:38.693  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 06:48:38.693  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 06:48:38.693  5634  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 06:48:38.694  5634  5680 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a74b06 not in the list
09-28 06:48:38.694  5634  5680 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 06:48:38.694  5634  5680 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 06:48:38.694  5634  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 06:48:38.694  5634  5680 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8acc1e1 not in the list
09-28 06:48:38.695  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-28 06:48:38.695  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 06:48:38.695  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-28 06:48:38.695  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 06:48:38.695  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-28 06:48:38.695  5634  5680 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 06:48:39.167  5634  5634 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 06:48:39.226   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 06:48:39.232   927  3011 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 06:48:39.322   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 06:48:39.323   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 06:48:40.358   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:48:40.705  5634  5969 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: My test thread name)
,09-28 06:48:42.257   927  3011 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 06:48:42.705  5634  5680 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 190
,09-28 06:48:42.705  5634  5680 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 190, name: My test thread name)
09-28 06:48:42.709  5634  5970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-28 06:48:42.710  5634  5970 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: My test thread name)
09-28 06:48:42.710  5634  5970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-28 06:48:42.715  5634  5680 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 06:48:42.719  5634  5969 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-28 06:48:42.721  5634  5971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name)
,09-28 06:48:42.722  5634  5971 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 195, thread name: My test thread name): Test exception.
09-28 06:48:42.722  5634  5971 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-28 06:48:42.729  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-28 06:48:42.729  5634  5680 I jxcore-log: 
,09-28 06:48:42.730  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-28 06:48:42.730  5634  5680 I jxcore-log: 
09-28 06:48:42.730  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-28 06:48:42.730  5634  5680 I jxcore-log: 
09-28 06:48:42.731  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-28 06:48:42.731  5634  5680 I jxcore-log: 
,09-28 06:48:42.733  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'Total duration:  101057'
09-28 06:48:42.733  5634  5680 I jxcore-log: 
,09-28 06:48:42.738  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-28 06:48:42.738  5634  5680 I jxcore-log: 
,09-28 06:48:42.748  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.748  5634  5680 I jxcore-log: 
,09-28 06:48:42.750  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.750  5634  5680 I jxcore-log: 
,09-28 06:48:42.752  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.752  5634  5680 I jxcore-log: 
,09-28 06:48:42.753  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.753  5634  5680 I jxcore-log: 
,09-28 06:48:42.754  5634  5634 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-28 06:48:42.755  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 06:48:42.755  5634  5680 I jxcore-log: 
,09-28 06:48:42.756  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 06:48:42.756  5634  5680 I jxcore-log: 
,09-28 06:48:42.758  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.758  5634  5680 I jxcore-log: 
,09-28 06:48:42.759  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.759  5634  5680 I jxcore-log: 
09-28 06:48:42.759  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 06:48:42.759  5634  5680 I jxcore-log: 
09-28 06:48:42.760  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 06:48:42.760  5634  5680 I jxcore-log: 
09-28 06:48:42.761  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 06:48:42.761  5634  5680 I jxcore-log: 
,09-28 06:48:42.762  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.762  5634  5680 I jxcore-log: 
,09-28 06:48:42.763  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.763  5634  5680 I jxcore-log: 
09-28 06:48:42.764  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.764  5634  5680 I jxcore-log: 
,09-28 06:48:42.765  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.765  5634  5680 I jxcore-log: 
,09-28 06:48:42.766  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.766  5634  5680 I jxcore-log: 
,09-28 06:48:42.768  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.768  5634  5680 I jxcore-log: 
,09-28 06:48:42.769  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.769  5634  5680 I jxcore-log: 
09-28 06:48:42.769  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.769  5634  5680 I jxcore-log: 
09-28 06:48:42.770  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.770  5634  5680 I jxcore-log: 
,09-28 06:48:42.771  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.771  5634  5680 I jxcore-log: 
,09-28 06:48:42.772  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.772  5634  5680 I jxcore-log: 
09-28 06:48:42.773  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.773  5634  5680 I jxcore-log: 
,09-28 06:48:42.776  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.776  5634  5680 I jxcore-log: 
,09-28 06:48:42.777  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.777  5634  5680 I jxcore-log: 
09-28 06:48:42.778  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.778  5634  5680 I jxcore-log: 
,09-28 06:48:42.779  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.779  5634  5680 I jxcore-log: 
,09-28 06:48:42.780  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.780  5634  5680 I jxcore-log: 
09-28 06:48:42.780  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.780  5634  5680 I jxcore-log: 
,09-28 06:48:42.781  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.781  5634  5680 I jxcore-log: 
,09-28 06:48:42.782  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.782  5634  5680 I jxcore-log: 
09-28 06:48:42.783  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.783  5634  5680 I jxcore-log: 
,09-28 06:48:42.783  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.783  5634  5680 I jxcore-log: 
09-28 06:48:42.784  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.784  5634  5680 I jxcore-log: 
,09-28 06:48:42.784  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.784  5634  5680 I jxcore-log: 
,09-28 06:48:42.785  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.785  5634  5680 I jxcore-log: 
09-28 06:48:42.786  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.786  5634  5680 I jxcore-log: 
09-28 06:48:42.786  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.786  5634  5680 I jxcore-log: 
,09-28 06:48:42.787  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 06:48:42.787  5634  5680 I jxcore-log: 
09-28 06:48:42.788  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.788  5634  5680 I jxcore-log: 
,09-28 06:48:42.788  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.788  5634  5680 I jxcore-log: 
09-28 06:48:42.789  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 06:48:42.789  5634  5680 I jxcore-log: 
,09-28 06:48:42.790  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.790  5634  5680 I jxcore-log: 
09-28 06:48:42.790  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.790  5634  5680 I jxcore-log: 
,09-28 06:48:42.791  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.791  5634  5680 I jxcore-log: 
09-28 06:48:42.792  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.792  5634  5680 I jxcore-log: 
,09-28 06:48:42.792  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 06:48:42.792  5634  5680 I jxcore-log: 
09-28 06:48:42.793  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.793  5634  5680 I jxcore-log: 
09-28 06:48:42.794  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-28 06:48:42.794  5634  5680 I jxcore-log: 
09-28 06:48:42.794  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.794  5634  5680 I jxcore-log: 
09-28 06:48:42.795  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 06:48:42.795  5634  5680 I jxcore-log: 
09-28 06:48:42.796  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 06:48:42.796  5634  5680 I jxcore-log: 
09-28 06:48:42.796  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 06:48:42.796  5634  5680 I jxcore-log: 
09-28 06:48:42.797  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 06:48:42.797  5634  5680 I jxcore-log: 
09-28 06:48:42.805  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-28 06:48:42.805  5634  5680 I jxcore-log: 
09-28 06:48:42.806  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - WARN testUtils: 'myNameCallback not set!'
09-28 06:48:42.806  5634  5680 I jxcore-log: 
09-28 06:48:42.807  5634  5680 I jxcore-log: 2016-09-28 10:48:42 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-28 06:48:42.807  5634  5680 I jxcore-log: 
,09-28 06:48:44.836  5634  5680 I jxcore-log: 2016-09-28 10:48:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-28 06:48:44.836  5634  5680 I jxcore-log: 
,09-28 06:48:45.162  5634  5680 I jxcore-log: 2016-09-28 10:48:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-28 06:48:45.162  5634  5680 I jxcore-log: 
,09-28 06:48:45.177  5634  5680 I jxcore-log: 2016-09-28 10:48:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-28 06:48:45.177  5634  5680 I jxcore-log: 
,09-28 06:48:46.278  5634  5680 I jxcore-log: 2016-09-28 10:48:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-28 06:48:46.278  5634  5680 I jxcore-log: 
,09-28 06:48:46.430  5634  5680 I jxcore-log: 2016-09-28 10:48:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-28 06:48:46.430  5634  5680 I jxcore-log: 
,09-28 06:48:46.435  5634  5680 I jxcore-log: 2016-09-28 10:48:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-28 06:48:46.435  5634  5680 I jxcore-log: 
,09-28 06:48:46.440  5634  5680 I jxcore-log: 2016-09-28 10:48:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-28 06:48:46.440  5634  5680 I jxcore-log: 
,09-28 06:48:46.985  5634  5680 I jxcore-log: 2016-09-28 10:48:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-28 06:48:46.985  5634  5680 I jxcore-log: 
,09-28 06:48:47.037  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-28 06:48:47.037  5634  5680 I jxcore-log: 
,09-28 06:48:47.050  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-28 06:48:47.050  5634  5680 I jxcore-log: 
,09-28 06:48:47.061  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-28 06:48:47.061  5634  5680 I jxcore-log: 
,09-28 06:48:47.339  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-28 06:48:47.339  5634  5680 I jxcore-log: 
,09-28 06:48:47.465  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-28 06:48:47.465  5634  5680 I jxcore-log: 
,09-28 06:48:47.858  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-28 06:48:47.858  5634  5680 I jxcore-log: 
,09-28 06:48:47.866  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-28 06:48:47.866  5634  5680 I jxcore-log: 
,09-28 06:48:47.871  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-28 06:48:47.871  5634  5680 I jxcore-log: 
,09-28 06:48:47.876  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-28 06:48:47.876  5634  5680 I jxcore-log: 
,09-28 06:48:47.903  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-28 06:48:47.903  5634  5680 I jxcore-log: 
,09-28 06:48:47.938  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-28 06:48:47.938  5634  5680 I jxcore-log: 
,09-28 06:48:47.945  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-28 06:48:47.945  5634  5680 I jxcore-log: 
,09-28 06:48:47.952  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-28 06:48:47.952  5634  5680 I jxcore-log: 
,09-28 06:48:47.967  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-28 06:48:47.967  5634  5680 I jxcore-log: 
,09-28 06:48:47.972  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-28 06:48:47.972  5634  5680 I jxcore-log: 
,09-28 06:48:47.979  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-28 06:48:47.979  5634  5680 I jxcore-log: 
,09-28 06:48:47.984  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-28 06:48:47.984  5634  5680 I jxcore-log: 
,09-28 06:48:47.997  5634  5680 I jxcore-log: 2016-09-28 10:48:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-28 06:48:47.997  5634  5680 I jxcore-log: 
,09-28 06:48:48.018  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-28 06:48:48.018  5634  5680 I jxcore-log: 
,09-28 06:48:48.028  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-28 06:48:48.028  5634  5680 I jxcore-log: 
,09-28 06:48:48.038  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-28 06:48:48.038  5634  5680 I jxcore-log: 
,09-28 06:48:48.048  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-28 06:48:48.048  5634  5680 I jxcore-log: 
,09-28 06:48:48.059  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-28 06:48:48.059  5634  5680 I jxcore-log: 
,09-28 06:48:48.069  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-28 06:48:48.069  5634  5680 I jxcore-log: 
,09-28 06:48:48.074  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-28 06:48:48.074  5634  5680 I jxcore-log: 
,09-28 06:48:48.096  5634  5680 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-28 06:48:48.097  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - INFO testUtils: 'BLE multiple advertisement supported'
09-28 06:48:48.097  5634  5680 I jxcore-log: 
,09-28 06:48:48.198  5634  5680 I jxcore-log: 2016-09-28 10:48:48 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 06:48:48.198  5634  5680 I jxcore-log: 
,09-28 06:48:48.636  5634  5680 I jxcore-log: TAP version 13
09-28 06:48:48.636  5634  5680 I jxcore-log: 
,09-28 06:48:48.678  5634  5680 I jxcore-log: # setup
09-28 06:48:48.678  5634  5680 I jxcore-log: 
,09-28 06:48:49.399  5634  5680 I jxcore-log: # calling createNativeListener directly rejects
09-28 06:48:49.399  5634  5680 I jxcore-log: 
,09-28 06:48:49.764  5634  5680 I jxcore-log: 2016-09-28 10:48:49 - DEBUG createNativeListener: 'creating native server'
09-28 06:48:49.764  5634  5680 I jxcore-log: 
,09-28 06:48:49.770  5634  5680 I jxcore-log: 2016-09-28 10:48:49 - DEBUG createNativeListener: 'listening 41859'
09-28 06:48:49.770  5634  5680 I jxcore-log: 
,09-28 06:48:49.778  5634  5680 I jxcore-log: ok 1 Should throw
09-28 06:48:49.778  5634  5680 I jxcore-log: 
,09-28 06:48:49.786  5634  5680 I jxcore-log: # teardown
09-28 06:48:49.786  5634  5680 I jxcore-log: 
,09-28 06:48:50.187  5634  5680 I jxcore-log: # setup
09-28 06:48:50.187  5634  5680 I jxcore-log: 
,09-28 06:48:51.001  5634  5680 I jxcore-log: # emits incomingConnectionState
09-28 06:48:51.001  5634  5680 I jxcore-log: 
,09-28 06:48:51.414  5634  5680 I jxcore-log: 2016-09-28 10:48:51 - DEBUG createNativeListener: 'creating native server'
09-28 06:48:51.414  5634  5680 I jxcore-log: 
,09-28 06:48:51.419  5634  5680 I jxcore-log: 2016-09-28 10:48:51 - DEBUG createNativeListener: 'listening 41944'
09-28 06:48:51.419  5634  5680 I jxcore-log: 
,09-28 06:48:51.429  5634  5680 I jxcore-log: 2016-09-28 10:48:51 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:48:51.429  5634  5680 I jxcore-log: 
,09-28 06:48:51.433  5634  5680 I jxcore-log: 2016-09-28 10:48:51 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:48:51.433  5634  5680 I jxcore-log: 
,09-28 06:48:51.443  5634  5680 I jxcore-log: 2016-09-28 10:48:51 - DEBUG createNativeListener: 'new mux'
09-28 06:48:51.443  5634  5680 I jxcore-log: 
,09-28 06:48:51.450  5634  5680 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-28 06:48:51.450  5634  5680 I jxcore-log: 
,09-28 06:48:51.470  5634  5680 I jxcore-log: 2016-09-28 10:48:51 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:48:51.470  5634  5680 I jxcore-log: 
,09-28 06:48:51.471  5634  5680 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-28 06:48:51.471  5634  5680 I jxcore-log: 
,09-28 06:48:51.478  5634  5680 I jxcore-log: # teardown
09-28 06:48:51.478  5634  5680 I jxcore-log: 
,09-28 06:48:52.232  5634  5680 I jxcore-log: # setup
09-28 06:48:52.232  5634  5680 I jxcore-log: 
,09-28 06:48:52.954  5634  5680 I jxcore-log: # emits routerPortConnectionFailed
09-28 06:48:52.954  5634  5680 I jxcore-log: 
,09-28 06:48:53.158   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:48:54.323   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:54.491  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'creating native server'
09-28 06:48:54.491  5634  5680 I jxcore-log: 
,09-28 06:48:54.495  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'listening 40815'
09-28 06:48:54.495  5634  5680 I jxcore-log: 
,09-28 06:48:54.502  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:48:54.502  5634  5680 I jxcore-log: 
,09-28 06:48:54.503  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:48:54.503  5634  5680 I jxcore-log: 
,09-28 06:48:54.505  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'new mux'
09-28 06:48:54.505  5634  5680 I jxcore-log: 
,09-28 06:48:54.532  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'new stream: '
09-28 06:48:54.532  5634  5680 I jxcore-log: 
,09-28 06:48:54.535  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:48:54.535  5634  5680 I jxcore-log: 
,09-28 06:48:54.539  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: ''
09-28 06:48:54.539  5634  5680 I jxcore-log: 
,09-28 06:48:54.540  5634  5680 I jxcore-log: ok 4 tried to connect to right port
09-28 06:48:54.540  5634  5680 I jxcore-log: 
,09-28 06:48:54.541  5634  5680 I jxcore-log: ok 5 failed due to refused connection
09-28 06:48:54.541  5634  5680 I jxcore-log: 
,09-28 06:48:54.542  5634  5680 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-28 06:48:54.542  5634  5680 I jxcore-log: 
,09-28 06:48:54.545  5634  5680 I jxcore-log: # teardown
09-28 06:48:54.545  5634  5680 I jxcore-log: 
,09-28 06:48:54.547  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'stream close:'
09-28 06:48:54.547  5634  5680 I jxcore-log: 
,09-28 06:48:54.770  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'mux close'
09-28 06:48:54.770  5634  5680 I jxcore-log: 
,09-28 06:48:54.780  5634  5680 I jxcore-log: 2016-09-28 10:48:54 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:48:54.780  5634  5680 I jxcore-log: 
,09-28 06:48:54.793  5634  5680 I jxcore-log: # setup
09-28 06:48:54.793  5634  5680 I jxcore-log: 
,09-28 06:48:55.325   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:55.914  5634  5680 I jxcore-log: # native server connections all up
09-28 06:48:55.914  5634  5680 I jxcore-log: 
,09-28 06:48:56.326   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:57.245  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'creating native server'
09-28 06:48:57.245  5634  5680 I jxcore-log: 
,09-28 06:48:57.252  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'listening 45741'
09-28 06:48:57.252  5634  5680 I jxcore-log: 
,09-28 06:48:57.261  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:48:57.261  5634  5680 I jxcore-log: 
,09-28 06:48:57.263  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:48:57.263  5634  5680 I jxcore-log: 
,09-28 06:48:57.265  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'new mux'
09-28 06:48:57.265  5634  5680 I jxcore-log: 
,09-28 06:48:57.296  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'new stream: '
09-28 06:48:57.296  5634  5680 I jxcore-log: 
,09-28 06:48:57.299  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:48:57.299  5634  5680 I jxcore-log: 
,09-28 06:48:57.302  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'new stream: '
09-28 06:48:57.302  5634  5680 I jxcore-log: 
,09-28 06:48:57.305  5634  5680 I jxcore-log: 2016-09-28 10:48:57 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:48:57.305  5634  5680 I jxcore-log: 
,09-28 06:48:57.327   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:57.329  5634  5680 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-28 06:48:57.329  5634  5680 I jxcore-log: 
09-28 06:48:57.329  5634  5680 I jxcore-log: ok 8 Send/recvd #1 should be same
09-28 06:48:57.329  5634  5680 I jxcore-log: 
,09-28 06:48:57.332  5634  5680 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-28 06:48:57.332  5634  5680 I jxcore-log: 
09-28 06:48:57.333  5634  5680 I jxcore-log: ok 10 Send/recvd #2 should be same
09-28 06:48:57.333  5634  5680 I jxcore-log: 
,09-28 06:48:57.336  5634  5680 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-28 06:48:57.336  5634  5680 I jxcore-log: 
,09-28 06:48:57.343  5634  5680 I jxcore-log: # teardown
09-28 06:48:57.343  5634  5680 I jxcore-log: 
,09-28 06:48:58.165  5634  5680 I jxcore-log: 2016-09-28 10:48:58 - DEBUG createNativeListener: 'stream close:'
09-28 06:48:58.165  5634  5680 I jxcore-log: 
,09-28 06:48:58.170  5634  5680 I jxcore-log: 2016-09-28 10:48:58 - DEBUG createNativeListener: 'stream close:'
09-28 06:48:58.170  5634  5680 I jxcore-log: 
,09-28 06:48:58.175  5634  5680 I jxcore-log: 2016-09-28 10:48:58 - DEBUG createNativeListener: 'mux close'
09-28 06:48:58.175  5634  5680 I jxcore-log: 
,09-28 06:48:58.184  5634  5680 I jxcore-log: 2016-09-28 10:48:58 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:48:58.184  5634  5680 I jxcore-log: 
,09-28 06:48:58.202  5634  5680 I jxcore-log: # setup
09-28 06:48:58.202  5634  5680 I jxcore-log: 
,09-28 06:48:58.298   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:48:58.327   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:48:58.543  5634  5680 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-28 06:48:58.543  5634  5680 I jxcore-log: 
,09-28 06:48:59.328   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 06:48:59.487  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'creating native server'
09-28 06:48:59.487  5634  5680 I jxcore-log: 
,09-28 06:48:59.494  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'listening 38513'
09-28 06:48:59.494  5634  5680 I jxcore-log: 
,09-28 06:48:59.501  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:48:59.501  5634  5680 I jxcore-log: 
,09-28 06:48:59.503  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:48:59.503  5634  5680 I jxcore-log: 
,09-28 06:48:59.507  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new mux'
09-28 06:48:59.507  5634  5680 I jxcore-log: 
,09-28 06:48:59.523  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new stream: '
09-28 06:48:59.523  5634  5680 I jxcore-log: 
,09-28 06:48:59.526  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:48:59.526  5634  5680 I jxcore-log: 
,09-28 06:48:59.538  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'stream close:'
09-28 06:48:59.538  5634  5680 I jxcore-log: 
,09-28 06:48:59.549  5634  5680 I jxcore-log: ok 12 socket shouldn't close until after stream
09-28 06:48:59.549  5634  5680 I jxcore-log: 
,09-28 06:48:59.549  5634  5680 I jxcore-log: ok 13 incoming remains open
09-28 06:48:59.549  5634  5680 I jxcore-log: 
,09-28 06:48:59.556  5634  5680 I jxcore-log: # teardown
09-28 06:48:59.556  5634  5680 I jxcore-log: 
,09-28 06:48:59.635  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'mux close'
09-28 06:48:59.635  5634  5680 I jxcore-log: 
,09-28 06:48:59.641  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:48:59.641  5634  5680 I jxcore-log: 
,09-28 06:48:59.647  5634  5680 I jxcore-log: # setup
09-28 06:48:59.647  5634  5680 I jxcore-log: 
,09-28 06:48:59.780  5634  5680 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-28 06:48:59.780  5634  5680 I jxcore-log: 
,09-28 06:48:59.869  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'creating native server'
09-28 06:48:59.869  5634  5680 I jxcore-log: 
,09-28 06:48:59.875  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'listening 46185'
09-28 06:48:59.875  5634  5680 I jxcore-log: 
,09-28 06:48:59.885  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:48:59.885  5634  5680 I jxcore-log: 
,09-28 06:48:59.886  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:48:59.886  5634  5680 I jxcore-log: 
,09-28 06:48:59.888  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new mux'
09-28 06:48:59.888  5634  5680 I jxcore-log: 
,09-28 06:48:59.898  5634  5680 I jxcore-log: ok 14 we should not have gotten an error
09-28 06:48:59.898  5634  5680 I jxcore-log: 
,09-28 06:48:59.906  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new stream: '
09-28 06:48:59.906  5634  5680 I jxcore-log: 
,09-28 06:48:59.911  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:48:59.911  5634  5680 I jxcore-log: 
,09-28 06:48:59.921  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'stream close:'
09-28 06:48:59.921  5634  5680 I jxcore-log: 
,09-28 06:48:59.923  5634  5680 I jxcore-log: 2016-09-28 10:48:59 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:48:59.923  5634  5680 I jxcore-log: 
,09-28 06:48:59.931  5634  5680 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-28 06:48:59.931  5634  5680 I jxcore-log: 
,09-28 06:48:59.932  5634  5680 I jxcore-log: ok 16 incoming is cleaned up
09-28 06:48:59.932  5634  5680 I jxcore-log: 
,09-28 06:48:59.935  5634  5680 I jxcore-log: # teardown
09-28 06:48:59.935  5634  5680 I jxcore-log: 
,09-28 06:49:00.026  5634  5680 I jxcore-log: # setup
09-28 06:49:00.026  5634  5680 I jxcore-log: 
,09-28 06:49:00.132  5634  5680 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-28 06:49:00.132  5634  5680 I jxcore-log: 
,09-28 06:49:00.195  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating native server'
09-28 06:49:00.195  5634  5680 I jxcore-log: 
,09-28 06:49:00.199  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'listening 38537'
09-28 06:49:00.199  5634  5680 I jxcore-log: 
,09-28 06:49:00.205  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.205  5634  5680 I jxcore-log: 
,09-28 06:49:00.207  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.207  5634  5680 I jxcore-log: 
,09-28 06:49:00.210  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.210  5634  5680 I jxcore-log: 
,09-28 06:49:00.226  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:00.226  5634  5680 I jxcore-log: 
,09-28 06:49:00.228  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:00.228  5634  5680 I jxcore-log: 
,09-28 06:49:00.243  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:00.243  5634  5680 I jxcore-log: 
,09-28 06:49:00.261  5634  5680 I jxcore-log: ok 17 stream was closed
09-28 06:49:00.261  5634  5680 I jxcore-log: 
,09-28 06:49:00.262  5634  5680 I jxcore-log: ok 18 incoming should survive
09-28 06:49:00.262  5634  5680 I jxcore-log: 
09-28 06:49:00.262  5634  5680 I jxcore-log: ok 19 mux should have no streams
09-28 06:49:00.262  5634  5680 I jxcore-log: 
,09-28 06:49:00.268  5634  5680 I jxcore-log: # teardown
09-28 06:49:00.268  5634  5680 I jxcore-log: 
,09-28 06:49:00.343  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'mux close'
09-28 06:49:00.343  5634  5680 I jxcore-log: 
,09-28 06:49:00.352  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:00.352  5634  5680 I jxcore-log: 
,09-28 06:49:00.360  5634  5680 I jxcore-log: # setup
09-28 06:49:00.360  5634  5680 I jxcore-log: 
,09-28 06:49:00.509  5634  5680 I jxcore-log: # native server - closing the whole server cleans everything up
09-28 06:49:00.509  5634  5680 I jxcore-log: 
,09-28 06:49:00.612  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating native server'
09-28 06:49:00.612  5634  5680 I jxcore-log: 
,09-28 06:49:00.620  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'listening 41214'
09-28 06:49:00.620  5634  5680 I jxcore-log: 
,09-28 06:49:00.635  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.635  5634  5680 I jxcore-log: 
,09-28 06:49:00.638  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.638  5634  5680 I jxcore-log: 
09-28 06:49:00.640  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.640  5634  5680 I jxcore-log: 
,09-28 06:49:00.655  5634  5680 I jxcore-log: ok 20 we should not have gotten an error
09-28 06:49:00.655  5634  5680 I jxcore-log: 
,09-28 06:49:00.671  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:00.671  5634  5680 I jxcore-log: 
,09-28 06:49:00.676  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:00.676  5634  5680 I jxcore-log: 
,09-28 06:49:00.688  5634  5680 I jxcore-log: ok 21 Buffers are identical
09-28 06:49:00.688  5634  5680 I jxcore-log: 
,09-28 06:49:00.690  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:00.690  5634  5680 I jxcore-log: 
,09-28 06:49:00.694  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'mux close'
09-28 06:49:00.694  5634  5680 I jxcore-log: 
,09-28 06:49:00.697  5634  5680 I jxcore-log: ok 22 native server is nulled out
09-28 06:49:00.697  5634  5680 I jxcore-log: 
,09-28 06:49:00.698  5634  5680 I jxcore-log: ok 23 native server should be closed
09-28 06:49:00.698  5634  5680 I jxcore-log: 
09-28 06:49:00.698  5634  5680 I jxcore-log: ok 24 incoming has been removed
09-28 06:49:00.698  5634  5680 I jxcore-log: 
09-28 06:49:00.699  5634  5680 I jxcore-log: ok 25 Incoming should be done
09-28 06:49:00.699  5634  5680 I jxcore-log: 
,09-28 06:49:00.699  5634  5680 I jxcore-log: ok 26 The mux object should be closed
09-28 06:49:00.699  5634  5680 I jxcore-log: 
,09-28 06:49:00.700  5634  5680 I jxcore-log: ok 27 The mux stream should be closed
09-28 06:49:00.700  5634  5680 I jxcore-log: 
,09-28 06:49:00.701  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:00.701  5634  5680 I jxcore-log: 
,09-28 06:49:00.716  5634  5680 I jxcore-log: # teardown
09-28 06:49:00.716  5634  5680 I jxcore-log: 
,09-28 06:49:00.766  5634  5680 I jxcore-log: # setup
09-28 06:49:00.766  5634  5680 I jxcore-log: 
,09-28 06:49:00.855  5634  5680 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-28 06:49:00.855  5634  5680 I jxcore-log: 
,09-28 06:49:00.908  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating native server'
09-28 06:49:00.908  5634  5680 I jxcore-log: 
,09-28 06:49:00.911  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'listening 46337'
09-28 06:49:00.911  5634  5680 I jxcore-log: 
,09-28 06:49:00.935  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.935  5634  5680 I jxcore-log: 
,09-28 06:49:00.936  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.936  5634  5680 I jxcore-log: 
,09-28 06:49:00.938  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.938  5634  5680 I jxcore-log: 
,09-28 06:49:00.942  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.942  5634  5680 I jxcore-log: 
09-28 06:49:00.943  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.943  5634  5680 I jxcore-log: 
09-28 06:49:00.944  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.944  5634  5680 I jxcore-log: 
,09-28 06:49:00.948  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.948  5634  5680 I jxcore-log: 
,09-28 06:49:00.949  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.949  5634  5680 I jxcore-log: 
,09-28 06:49:00.950  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.950  5634  5680 I jxcore-log: 
,09-28 06:49:00.954  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.954  5634  5680 I jxcore-log: 
,09-28 06:49:00.955  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.955  5634  5680 I jxcore-log: 
,09-28 06:49:00.956  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.956  5634  5680 I jxcore-log: 
,09-28 06:49:00.959  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.959  5634  5680 I jxcore-log: 
,09-28 06:49:00.960  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.960  5634  5680 I jxcore-log: 
,09-28 06:49:00.961  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.961  5634  5680 I jxcore-log: 
,09-28 06:49:00.963  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.963  5634  5680 I jxcore-log: 
,09-28 06:49:00.964  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.964  5634  5680 I jxcore-log: 
,09-28 06:49:00.965  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.965  5634  5680 I jxcore-log: 
,09-28 06:49:00.967  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.967  5634  5680 I jxcore-log: 
,09-28 06:49:00.968  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.968  5634  5680 I jxcore-log: 
09-28 06:49:00.969  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.969  5634  5680 I jxcore-log: 
,09-28 06:49:00.976  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.976  5634  5680 I jxcore-log: 
,09-28 06:49:00.977  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.977  5634  5680 I jxcore-log: 
,09-28 06:49:00.978  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.978  5634  5680 I jxcore-log: 
,09-28 06:49:00.981  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.981  5634  5680 I jxcore-log: 
,09-28 06:49:00.982  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.982  5634  5680 I jxcore-log: 
,09-28 06:49:00.982  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.982  5634  5680 I jxcore-log: 
,09-28 06:49:00.983  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:00.983  5634  5680 I jxcore-log: 
09-28 06:49:00.984  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:00.984  5634  5680 I jxcore-log: 
,09-28 06:49:00.984  5634  5680 I jxcore-log: 2016-09-28 10:49:00 - DEBUG createNativeListener: 'new mux'
09-28 06:49:00.984  5634  5680 I jxcore-log: 
,09-28 06:49:01.036  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.036  5634  5680 I jxcore-log: 
,09-28 06:49:01.038  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.038  5634  5680 I jxcore-log: 
,09-28 06:49:01.040  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.040  5634  5680 I jxcore-log: 
,09-28 06:49:01.041  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.041  5634  5680 I jxcore-log: 
,09-28 06:49:01.042  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.042  5634  5680 I jxcore-log: 
,09-28 06:49:01.043  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.043  5634  5680 I jxcore-log: 
,09-28 06:49:01.044  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.044  5634  5680 I jxcore-log: 
,09-28 06:49:01.045  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.045  5634  5680 I jxcore-log: 
,09-28 06:49:01.047  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.047  5634  5680 I jxcore-log: 
,09-28 06:49:01.048  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.048  5634  5680 I jxcore-log: 
,09-28 06:49:01.048  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.048  5634  5680 I jxcore-log: 
,09-28 06:49:01.049  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.049  5634  5680 I jxcore-log: 
09-28 06:49:01.050  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.050  5634  5680 I jxcore-log: 
,09-28 06:49:01.051  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.051  5634  5680 I jxcore-log: 
,09-28 06:49:01.052  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.052  5634  5680 I jxcore-log: 
09-28 06:49:01.053  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.053  5634  5680 I jxcore-log: 
,09-28 06:49:01.054  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.054  5634  5680 I jxcore-log: 
,09-28 06:49:01.055  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.055  5634  5680 I jxcore-log: 
09-28 06:49:01.056  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.056  5634  5680 I jxcore-log: 
,09-28 06:49:01.056  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.056  5634  5680 I jxcore-log: 
,09-28 06:49:01.057  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.057  5634  5680 I jxcore-log: 
09-28 06:49:01.058  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.058  5634  5680 I jxcore-log: 
,09-28 06:49:01.059  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.059  5634  5680 I jxcore-log: 
,09-28 06:49:01.060  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.060  5634  5680 I jxcore-log: 
,09-28 06:49:01.061  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.061  5634  5680 I jxcore-log: 
,09-28 06:49:01.062  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.062  5634  5680 I jxcore-log: 
09-28 06:49:01.062  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.062  5634  5680 I jxcore-log: 
,09-28 06:49:01.068  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.068  5634  5680 I jxcore-log: 
,09-28 06:49:01.070  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.070  5634  5680 I jxcore-log: 
,09-28 06:49:01.071  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.071  5634  5680 I jxcore-log: 
,09-28 06:49:01.072  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.072  5634  5680 I jxcore-log: 
,09-28 06:49:01.073  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.073  5634  5680 I jxcore-log: 
,09-28 06:49:01.074  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.074  5634  5680 I jxcore-log: 
,09-28 06:49:01.075  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.075  5634  5680 I jxcore-log: 
,09-28 06:49:01.076  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.076  5634  5680 I jxcore-log: 
,09-28 06:49:01.077  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.077  5634  5680 I jxcore-log: 
09-28 06:49:01.077  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.077  5634  5680 I jxcore-log: 
,09-28 06:49:01.078  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.078  5634  5680 I jxcore-log: 
,09-28 06:49:01.079  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.079  5634  5680 I jxcore-log: 
,09-28 06:49:01.080  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.080  5634  5680 I jxcore-log: 
09-28 06:49:01.081  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.081  5634  5680 I jxcore-log: 
,09-28 06:49:01.081  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.081  5634  5680 I jxcore-log: 
09-28 06:49:01.082  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.082  5634  5680 I jxcore-log: 
,09-28 06:49:01.083  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.083  5634  5680 I jxcore-log: 
,09-28 06:49:01.083  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.083  5634  5680 I jxcore-log: 
09-28 06:49:01.084  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.084  5634  5680 I jxcore-log: 
,09-28 06:49:01.084  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.084  5634  5680 I jxcore-log: 
09-28 06:49:01.085  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.085  5634  5680 I jxcore-log: 
,09-28 06:49:01.086  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.086  5634  5680 I jxcore-log: 
,09-28 06:49:01.087  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.087  5634  5680 I jxcore-log: 
09-28 06:49:01.087  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.087  5634  5680 I jxcore-log: 
09-28 06:49:01.088  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.088  5634  5680 I jxcore-log: 
,09-28 06:49:01.089  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.089  5634  5680 I jxcore-log: 
,09-28 06:49:01.089  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.089  5634  5680 I jxcore-log: 
09-28 06:49:01.090  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.090  5634  5680 I jxcore-log: 
,09-28 06:49:01.091  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.091  5634  5680 I jxcore-log: 
,09-28 06:49:01.092  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.092  5634  5680 I jxcore-log: 
,09-28 06:49:01.093  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.093  5634  5680 I jxcore-log: 
,09-28 06:49:01.094  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.094  5634  5680 I jxcore-log: 
,09-28 06:49:01.095  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.095  5634  5680 I jxcore-log: 
09-28 06:49:01.095  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.095  5634  5680 I jxcore-log: 
09-28 06:49:01.096  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.096  5634  5680 I jxcore-log: 
09-28 06:49:01.096  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.096  5634  5680 I jxcore-log: 
,09-28 06:49:01.097  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.097  5634  5680 I jxcore-log: 
09-28 06:49:01.098  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.098  5634  5680 I jxcore-log: 
,09-28 06:49:01.099  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.099  5634  5680 I jxcore-log: 
,09-28 06:49:01.099  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.099  5634  5680 I jxcore-log: 
09-28 06:49:01.100  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.100  5634  5680 I jxcore-log: 
,09-28 06:49:01.101  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.101  5634  5680 I jxcore-log: 
,09-28 06:49:01.101  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.101  5634  5680 I jxcore-log: 
09-28 06:49:01.102  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.102  5634  5680 I jxcore-log: 
,09-28 06:49:01.103  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.103  5634  5680 I jxcore-log: 
09-28 06:49:01.103  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.103  5634  5680 I jxcore-log: 
,09-28 06:49:01.104  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.104  5634  5680 I jxcore-log: 
,09-28 06:49:01.105  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.105  5634  5680 I jxcore-log: 
09-28 06:49:01.106  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.106  5634  5680 I jxcore-log: 
,09-28 06:49:01.106  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.106  5634  5680 I jxcore-log: 
,09-28 06:49:01.107  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.107  5634  5680 I jxcore-log: 
09-28 06:49:01.107  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:01.107  5634  5680 I jxcore-log: 
,09-28 06:49:01.108  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:01.108  5634  5680 I jxcore-log: 
,09-28 06:49:01.158  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.158  5634  5680 I jxcore-log: 
,09-28 06:49:01.159  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.159  5634  5680 I jxcore-log: 
,09-28 06:49:01.160  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.160  5634  5680 I jxcore-log: 
09-28 06:49:01.161  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.161  5634  5680 I jxcore-log: 
,09-28 06:49:01.161  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.161  5634  5680 I jxcore-log: 
09-28 06:49:01.162  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.162  5634  5680 I jxcore-log: 
,09-28 06:49:01.163  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.163  5634  5680 I jxcore-log: 
09-28 06:49:01.163  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.163  5634  5680 I jxcore-log: 
09-28 06:49:01.164  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.164  5634  5680 I jxcore-log: 
,09-28 06:49:01.164  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.164  5634  5680 I jxcore-log: 
09-28 06:49:01.165  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.165  5634  5680 I jxcore-log: 
,09-28 06:49:01.166  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.166  5634  5680 I jxcore-log: 
,09-28 06:49:01.167  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.167  5634  5680 I jxcore-log: 
09-28 06:49:01.168  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.168  5634  5680 I jxcore-log: 
,09-28 06:49:01.169  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.169  5634  5680 I jxcore-log: 
,09-28 06:49:01.172  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.172  5634  5680 I jxcore-log: 
,09-28 06:49:01.174  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.174  5634  5680 I jxcore-log: 
,09-28 06:49:01.175  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.175  5634  5680 I jxcore-log: 
09-28 06:49:01.176  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.176  5634  5680 I jxcore-log: 
,09-28 06:49:01.176  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.176  5634  5680 I jxcore-log: 
09-28 06:49:01.177  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.177  5634  5680 I jxcore-log: 
09-28 06:49:01.177  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.177  5634  5680 I jxcore-log: 
,09-28 06:49:01.177  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.177  5634  5680 I jxcore-log: 
09-28 06:49:01.178  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.178  5634  5680 I jxcore-log: 
09-28 06:49:01.178  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.178  5634  5680 I jxcore-log: 
,09-28 06:49:01.179  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.179  5634  5680 I jxcore-log: 
09-28 06:49:01.179  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.179  5634  5680 I jxcore-log: 
,09-28 06:49:01.180  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.180  5634  5680 I jxcore-log: 
09-28 06:49:01.180  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.180  5634  5680 I jxcore-log: 
09-28 06:49:01.181  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.181  5634  5680 I jxcore-log: 
,09-28 06:49:01.181  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.181  5634  5680 I jxcore-log: 
,09-28 06:49:01.182  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.182  5634  5680 I jxcore-log: 
,09-28 06:49:01.182  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.182  5634  5680 I jxcore-log: 
,09-28 06:49:01.182  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.182  5634  5680 I jxcore-log: 
,09-28 06:49:01.183  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.183  5634  5680 I jxcore-log: 
09-28 06:49:01.183  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.183  5634  5680 I jxcore-log: 
,09-28 06:49:01.184  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.184  5634  5680 I jxcore-log: 
,09-28 06:49:01.184  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.184  5634  5680 I jxcore-log: 
09-28 06:49:01.185  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.185  5634  5680 I jxcore-log: 
09-28 06:49:01.185  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.185  5634  5680 I jxcore-log: 
,09-28 06:49:01.185  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.185  5634  5680 I jxcore-log: 
09-28 06:49:01.186  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.186  5634  5680 I jxcore-log: 
09-28 06:49:01.186  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.186  5634  5680 I jxcore-log: 
09-28 06:49:01.187  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.187  5634  5680 I jxcore-log: 
,09-28 06:49:01.187  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.187  5634  5680 I jxcore-log: 
09-28 06:49:01.188  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.188  5634  5680 I jxcore-log: 
09-28 06:49:01.188  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.188  5634  5680 I jxcore-log: 
09-28 06:49:01.191  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.191  5634  5680 I jxcore-log: 
,09-28 06:49:01.192  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:01.192  5634  5680 I jxcore-log: 
,09-28 06:49:01.192  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'mux close'
09-28 06:49:01.192  5634  5680 I jxcore-log: 
,09-28 06:49:01.194  5634  5680 I jxcore-log: ok 28 native server is nulled out
09-28 06:49:01.194  5634  5680 I jxcore-log: 
,09-28 06:49:01.195  5634  5680 I jxcore-log: ok 29 native server should be closed
09-28 06:49:01.195  5634  5680 I jxcore-log: 
09-28 06:49:01.195  5634  5680 I jxcore-log: ok 30 incoming has been removed
09-28 06:49:01.195  5634  5680 I jxcore-log: 
,09-28 06:49:01.196  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.196  5634  5680 I jxcore-log: 
09-28 06:49:01.196  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.196  5634  5680 I jxcore-log: 
,09-28 06:49:01.196  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.196  5634  5680 I jxcore-log: 
09-28 06:49:01.196  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.196  5634  5680 I jxcore-log: 
09-28 06:49:01.197  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.197  5634  5680 I jxcore-log: 
,09-28 06:49:01.197  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.197  5634  5680 I jxcore-log: 
09-28 06:49:01.197  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.197  5634  5680 I jxcore-log: 
09-28 06:49:01.197  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.197  5634  5680 I jxcore-log: 
09-28 06:49:01.197  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.197  5634  5680 I jxcore-log: 
,09-28 06:49:01.198  5634  5680 I jxcore-log: 2016-09-28 10:49:01 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:01.198  5634  5680 I jxcore-log: 
,09-28 06:49:01.275  5634  5680 I jxcore-log: # teardown
09-28 06:49:01.275  5634  5680 I jxcore-log: 
,09-28 06:49:01.421  5634  5680 I jxcore-log: # setup
09-28 06:49:01.421  5634  5680 I jxcore-log: 
,09-28 06:49:03.385  5634  5680 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-28 06:49:03.385  5634  5680 I jxcore-log: 
,09-28 06:49:04.219  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'creating native server'
09-28 06:49:04.219  5634  5680 I jxcore-log: 
,09-28 06:49:04.225  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'listening 45584'
09-28 06:49:04.225  5634  5680 I jxcore-log: 
,09-28 06:49:04.235  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:04.235  5634  5680 I jxcore-log: 
,09-28 06:49:04.237  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:04.237  5634  5680 I jxcore-log: 
,09-28 06:49:04.239  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'new mux'
09-28 06:49:04.239  5634  5680 I jxcore-log: 
,09-28 06:49:04.249  5634  5680 I jxcore-log: ok 31 we should not have gotten an error
09-28 06:49:04.249  5634  5680 I jxcore-log: 
,09-28 06:49:04.258  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:04.258  5634  5680 I jxcore-log: 
,09-28 06:49:04.262  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:04.262  5634  5680 I jxcore-log: 
,09-28 06:49:04.270  5634  5680 I jxcore-log: ok 32 Buffers are identical
09-28 06:49:04.270  5634  5680 I jxcore-log: 
,09-28 06:49:04.271  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:04.271  5634  5680 I jxcore-log: 
09-28 06:49:04.273  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'mux close'
09-28 06:49:04.273  5634  5680 I jxcore-log: 
,09-28 06:49:04.286  5634  5680 I jxcore-log: 2016-09-28 10:49:04 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:04.286  5634  5680 I jxcore-log: 
,09-28 06:49:04.287  5634  5680 I jxcore-log: ok 33 server should be fine
09-28 06:49:04.287  5634  5680 I jxcore-log: 
09-28 06:49:04.287  5634  5680 I jxcore-log: ok 34 server should be open
09-28 06:49:04.287  5634  5680 I jxcore-log: 
,09-28 06:49:04.288  5634  5680 I jxcore-log: ok 35 incoming has been removed
09-28 06:49:04.288  5634  5680 I jxcore-log: 
,09-28 06:49:04.288  5634  5680 I jxcore-log: ok 36 The mux object should be closed
09-28 06:49:04.288  5634  5680 I jxcore-log: 
09-28 06:49:04.289  5634  5680 I jxcore-log: ok 37 The mux stream should be closed
09-28 06:49:04.289  5634  5680 I jxcore-log: 
,09-28 06:49:04.294  5634  5680 I jxcore-log: # teardown
09-28 06:49:04.294  5634  5680 I jxcore-log: 
,09-28 06:49:04.329   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:04.724  5634  5680 I jxcore-log: # setup
09-28 06:49:04.724  5634  5680 I jxcore-log: 
,09-28 06:49:05.330   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:06.332   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:06.459  5634  5680 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-28 06:49:06.459  5634  5680 I jxcore-log: 
,09-28 06:49:07.333   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:07.477  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'creating native server'
09-28 06:49:07.477  5634  5680 I jxcore-log: 
,09-28 06:49:07.483  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'listening 47227'
09-28 06:49:07.483  5634  5680 I jxcore-log: 
,09-28 06:49:07.493  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'new incoming socket'
09-28 06:49:07.493  5634  5680 I jxcore-log: 
,09-28 06:49:07.496  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'creating incoming mux'
09-28 06:49:07.496  5634  5680 I jxcore-log: 
,09-28 06:49:07.498  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'new mux'
09-28 06:49:07.498  5634  5680 I jxcore-log: 
,09-28 06:49:07.507  5634  5680 I jxcore-log: ok 38 we should not have gotten an error
09-28 06:49:07.507  5634  5680 I jxcore-log: 
,09-28 06:49:07.519  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'new stream: '
09-28 06:49:07.519  5634  5680 I jxcore-log: 
,09-28 06:49:07.523  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'new outgoing socket'
09-28 06:49:07.523  5634  5680 I jxcore-log: 
,09-28 06:49:07.533  5634  5680 I jxcore-log: ok 39 Buffers are identical
09-28 06:49:07.533  5634  5680 I jxcore-log: 
,09-28 06:49:07.540  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'incoming socket timeout'
09-28 06:49:07.540  5634  5680 I jxcore-log: 
,09-28 06:49:07.542  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'stream close:'
09-28 06:49:07.542  5634  5680 I jxcore-log: 
,09-28 06:49:07.544  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'mux close'
09-28 06:49:07.544  5634  5680 I jxcore-log: 
,09-28 06:49:07.551  5634  5680 I jxcore-log: 2016-09-28 10:49:07 - DEBUG createNativeListener: 'incoming socket close'
09-28 06:49:07.551  5634  5680 I jxcore-log: 
,09-28 06:49:07.552  5634  5680 I jxcore-log: ok 40 server should be fine
09-28 06:49:07.552  5634  5680 I jxcore-log: 
09-28 06:49:07.552  5634  5680 I jxcore-log: ok 41 server should be open
09-28 06:49:07.552  5634  5680 I jxcore-log: 
09-28 06:49:07.553  5634  5680 I jxcore-log: ok 42 incoming has been removed
09-28 06:49:07.553  5634  5680 I jxcore-log: 
,09-28 06:49:07.553  5634  5680 I jxcore-log: ok 43 The mux object should be closed
09-28 06:49:07.553  5634  5680 I jxcore-log: 
09-28 06:49:07.554  5634  5680 I jxcore-log: ok 44 The mux stream should be closed
09-28 06:49:07.554  5634  5680 I jxcore-log: 
,09-28 06:49:07.562  5634  5680 I jxcore-log: # teardown
09-28 06:49:07.562  5634  5680 I jxcore-log: 
,09-28 06:49:08.334   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:08.813  5634  5680 I jxcore-log: # setup
09-28 06:49:08.813  5634  5680 I jxcore-log: 
,09-28 06:49:09.334   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 06:49:09.643  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-28 06:49:09.643  5634  5680 I jxcore-log: 
,09-28 06:49:10.273  5634  5680 I jxcore-log: 2016-09-28 10:49:10 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-28 06:49:10.273  5634  5680 I jxcore-log: 
,09-28 06:49:10.274  5634  5680 I jxcore-log: ok 45 Got right error
09-28 06:49:10.274  5634  5680 I jxcore-log: 
,09-28 06:49:10.278  5634  5680 I jxcore-log: # teardown
09-28 06:49:10.278  5634  5680 I jxcore-log: 
,09-28 06:49:10.965  5634  5680 I jxcore-log: # setup
09-28 06:49:10.965  5634  5680 I jxcore-log: 
,09-28 06:49:12.004  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-28 06:49:12.004  5634  5680 I jxcore-log: 
,09-28 06:49:12.199  5634  5680 I jxcore-log: 2016-09-28 10:49:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-28 06:49:12.199  5634  5680 I jxcore-log: 
,09-28 06:49:12.201  5634  5680 I jxcore-log: ok 46 Got socket hang up
09-28 06:49:12.201  5634  5680 I jxcore-log: 
,09-28 06:49:12.206  5634  5680 I jxcore-log: # teardown
09-28 06:49:12.206  5634  5680 I jxcore-log: 
,09-28 06:49:12.330  5634  5680 I jxcore-log: # setup
09-28 06:49:12.330  5634  5680 I jxcore-log: 
,09-28 06:49:12.448  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-28 06:49:12.448  5634  5680 I jxcore-log: 
,09-28 06:49:12.621  5634  5680 I jxcore-log: 2016-09-28 10:49:12 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-28 06:49:12.621  5634  5680 I jxcore-log: 
,09-28 06:49:12.622  5634  5680 I jxcore-log: ok 47 Got 500 as expected
09-28 06:49:12.622  5634  5680 I jxcore-log: 
,09-28 06:49:12.625  5634  5680 I jxcore-log: # teardown
09-28 06:49:12.625  5634  5680 I jxcore-log: 
,09-28 06:49:12.699  5634  5680 I jxcore-log: # setup
09-28 06:49:12.699  5634  5680 I jxcore-log: 
,09-28 06:49:13.277  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-28 06:49:13.277  5634  5680 I jxcore-log: 
,09-28 06:49:15.549  5634  5680 I jxcore-log: ok 48 should be equal
09-28 06:49:15.549  5634  5680 I jxcore-log: 
,09-28 06:49:15.550  5634  5680 I jxcore-log: ok 49 revs are equal
09-28 06:49:15.550  5634  5680 I jxcore-log: 
,09-28 06:49:15.556  5634  5680 I jxcore-log: # teardown
09-28 06:49:15.556  5634  5680 I jxcore-log: 
,09-28 06:49:15.641  5634  5680 I jxcore-log: # setup
09-28 06:49:15.641  5634  5680 I jxcore-log: 
,09-28 06:49:16.196  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-28 06:49:16.196  5634  5680 I jxcore-log: 
,09-28 06:49:17.069  5634  5680 I jxcore-log: ok 50 should be equal
09-28 06:49:17.069  5634  5680 I jxcore-log: 
,09-28 06:49:17.069  5634  5680 I jxcore-log: ok 51 revs are equal
09-28 06:49:17.069  5634  5680 I jxcore-log: 
,09-28 06:49:17.075  5634  5680 I jxcore-log: # teardown
09-28 06:49:17.075  5634  5680 I jxcore-log: 
,09-28 06:49:17.166  5634  5680 I jxcore-log: # setup
09-28 06:49:17.166  5634  5680 I jxcore-log: 
,09-28 06:49:17.234  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-28 06:49:17.234  5634  5680 I jxcore-log: 
,09-28 06:49:17.831  5634  5680 I jxcore-log: ok 52 should be equal
09-28 06:49:17.831  5634  5680 I jxcore-log: 
,09-28 06:49:17.832  5634  5680 I jxcore-log: ok 53 revs are equal
09-28 06:49:17.832  5634  5680 I jxcore-log: 
,09-28 06:49:17.988  5634  5680 I jxcore-log: ok 54 should be equal
09-28 06:49:17.988  5634  5680 I jxcore-log: 
09-28 06:49:17.989  5634  5680 I jxcore-log: ok 55 revs are equal
09-28 06:49:17.989  5634  5680 I jxcore-log: 
,09-28 06:49:18.130  5634  5680 I jxcore-log: ok 56 should be equal
09-28 06:49:18.130  5634  5680 I jxcore-log: 
,09-28 06:49:18.131  5634  5680 I jxcore-log: ok 57 revs are equal
09-28 06:49:18.131  5634  5680 I jxcore-log: 
,09-28 06:49:18.138  5634  5680 I jxcore-log: # teardown
09-28 06:49:18.138  5634  5680 I jxcore-log: 
,09-28 06:49:18.302   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:49:18.482  5634  5680 I jxcore-log: # setup
09-28 06:49:18.482  5634  5680 I jxcore-log: 
,09-28 06:49:18.652  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-28 06:49:18.652  5634  5680 I jxcore-log: 
,09-28 06:49:19.266  5634  5680 I jxcore-log: 2016-09-28 10:49:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-28 06:49:19.266  5634  5680 I jxcore-log: 
,09-28 06:49:19.267  5634  5680 I jxcore-log: ok 58 Our rev is old so we should fail
09-28 06:49:19.267  5634  5680 I jxcore-log: 
,09-28 06:49:19.269  5634  5680 I jxcore-log: # teardown
09-28 06:49:19.269  5634  5680 I jxcore-log: 
,09-28 06:49:19.336   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:19.381  5634  5680 I jxcore-log: # setup
09-28 06:49:19.381  5634  5680 I jxcore-log: 
,09-28 06:49:19.477  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-28 06:49:19.477  5634  5680 I jxcore-log: 
,09-28 06:49:19.627  5634  5680 I jxcore-log: ok 59 confirm stop caused failure
09-28 06:49:19.627  5634  5680 I jxcore-log: 
,09-28 06:49:19.641  5634  5680 I jxcore-log: # teardown
09-28 06:49:19.641  5634  5680 I jxcore-log: 
,09-28 06:49:19.719  5634  5680 I jxcore-log: # setup
09-28 06:49:19.719  5634  5680 I jxcore-log: 
,09-28 06:49:20.012  5634  5680 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-28 06:49:20.012  5634  5680 I jxcore-log: 
,09-28 06:49:20.337   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:21.338   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:21.396  5634  5680 I jxcore-log: 2016-09-28 10:49:21 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-28 06:49:21.396  5634  5680 I jxcore-log: 
,09-28 06:49:21.397  5634  5680 I jxcore-log: ok 60 stop caused us to fail
09-28 06:49:21.397  5634  5680 I jxcore-log: 
09-28 06:49:21.398  5634  5680 I jxcore-log: ok 61 We specifically failed on a stop before put
09-28 06:49:21.398  5634  5680 I jxcore-log: 
,09-28 06:49:21.402  5634  5680 I jxcore-log: # teardown
09-28 06:49:21.402  5634  5680 I jxcore-log: 
,09-28 06:49:21.535  5634  5680 I jxcore-log: # setup
09-28 06:49:21.535  5634  5680 I jxcore-log: 
,09-28 06:49:21.674  5634  5680 I jxcore-log: # #update - fail if stop is called
09-28 06:49:21.674  5634  5680 I jxcore-log: 
,09-28 06:49:21.937  5634  5680 I jxcore-log: ok 62 failed due to stop
09-28 06:49:21.937  5634  5680 I jxcore-log: 
,09-28 06:49:21.940  5634  5680 I jxcore-log: ok 63 failed due to stop
09-28 06:49:21.940  5634  5680 I jxcore-log: 
,09-28 06:49:21.956  5634  5680 I jxcore-log: # teardown
09-28 06:49:21.956  5634  5680 I jxcore-log: 
,09-28 06:49:22.005  5634  5680 I jxcore-log: # setup
09-28 06:49:22.005  5634  5680 I jxcore-log: 
,09-28 06:49:22.063  5634  5680 I jxcore-log: # #update - set seq for first time
09-28 06:49:22.063  5634  5680 I jxcore-log: 
,09-28 06:49:22.339   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:22.566  5634  5680 I jxcore-log: ok 64 should be equal
09-28 06:49:22.566  5634  5680 I jxcore-log: 
,09-28 06:49:22.572  5634  5680 I jxcore-log: # teardown
09-28 06:49:22.572  5634  5680 I jxcore-log: 
,09-28 06:49:22.999  5634  5680 I jxcore-log: # setup
09-28 06:49:22.999  5634  5680 I jxcore-log: 
,09-28 06:49:23.340   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:24.340   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 06:49:24.486  5634  5680 I jxcore-log: # #update - Fail on bad seq value
09-28 06:49:24.486  5634  5680 I jxcore-log: 
,09-28 06:49:25.846  5634  5680 I jxcore-log: 2016-09-28 10:49:25 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-28 06:49:25.846  5634  5680 I jxcore-log: 
,09-28 06:49:25.848  5634  5680 I jxcore-log: ok 65 Expected bad seq error
09-28 06:49:25.848  5634  5680 I jxcore-log: 
,09-28 06:49:25.851  5634  5680 I jxcore-log: # teardown
09-28 06:49:25.851  5634  5680 I jxcore-log: 
,09-28 06:49:26.123  5634  5680 I jxcore-log: # setup
09-28 06:49:26.123  5634  5680 I jxcore-log: 
,09-28 06:49:27.037  5634  5680 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-28 06:49:27.037  5634  5680 I jxcore-log: 
,09-28 06:49:29.371  5634  5680 I jxcore-log: ok 66 Different promises
09-28 06:49:29.371  5634  5680 I jxcore-log: 
,09-28 06:49:29.373  5634  5680 I jxcore-log: ok 67 Timer was cancelled
09-28 06:49:29.373  5634  5680 I jxcore-log: 
,09-28 06:49:29.521  5634  5680 I jxcore-log: ok 68 should be equal
09-28 06:49:29.521  5634  5680 I jxcore-log: 
,09-28 06:49:29.527  5634  5680 I jxcore-log: # teardown
09-28 06:49:29.527  5634  5680 I jxcore-log: 
,09-28 06:49:29.610  5634  5680 I jxcore-log: # setup
09-28 06:49:29.610  5634  5680 I jxcore-log: 
,09-28 06:49:30.211  5634  5680 I jxcore-log: # #update - do we wait for blocked update
09-28 06:49:30.211  5634  5680 I jxcore-log: 
,09-28 06:49:31.000  5634  5680 I jxcore-log: ok 69 One go and one blocked
09-28 06:49:31.000  5634  5680 I jxcore-log: 
,09-28 06:49:31.001  5634  5680 I jxcore-log: ok 70 All blocked
09-28 06:49:31.001  5634  5680 I jxcore-log: 
09-28 06:49:31.002  5634  5680 I jxcore-log: ok 71 Still blocked
09-28 06:49:31.002  5634  5680 I jxcore-log: 
,09-28 06:49:31.742  5634  5680 I jxcore-log: ok 72 should be equal
09-28 06:49:31.742  5634  5680 I jxcore-log: 
,09-28 06:49:31.748  5634  5680 I jxcore-log: # teardown
09-28 06:49:31.748  5634  5680 I jxcore-log: 
,09-28 06:49:32.036  5634  5680 I jxcore-log: # setup
09-28 06:49:32.036  5634  5680 I jxcore-log: 
,09-28 06:49:33.185  5634  5680 I jxcore-log: # #update - test that we wait long enough
09-28 06:49:33.185  5634  5680 I jxcore-log: 
,09-28 06:49:34.745  5634  5680 I jxcore-log: ok 73 We waited long enough
09-28 06:49:34.745  5634  5680 I jxcore-log: 
,09-28 06:49:34.869  5634  5680 I jxcore-log: ok 74 should be equal
09-28 06:49:34.869  5634  5680 I jxcore-log: 
,09-28 06:49:34.874  5634  5680 I jxcore-log: # teardown
09-28 06:49:34.874  5634  5680 I jxcore-log: 
,09-28 06:49:35.785  5634  5680 I jxcore-log: # setup
09-28 06:49:35.785  5634  5680 I jxcore-log: 
,09-28 06:49:36.762  5634  5680 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-28 06:49:36.762  5634  5680 I jxcore-log: 
,09-28 06:49:37.814  5634  5680 I jxcore-log: ok 75 Should have gotten same timer promise
09-28 06:49:37.814  5634  5680 I jxcore-log: 
,09-28 06:49:37.815  5634  5680 I jxcore-log: ok 76 Still same timer promise
09-28 06:49:37.815  5634  5680 I jxcore-log: 
,09-28 06:49:38.305   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:49:38.623  5634  5680 I jxcore-log: ok 77 We waited long enough
09-28 06:49:38.623  5634  5680 I jxcore-log: 
,09-28 06:49:38.687  5634  5680 I jxcore-log: ok 78 should be equal
09-28 06:49:38.687  5634  5680 I jxcore-log: 
,09-28 06:49:38.692  5634  5680 I jxcore-log: # teardown
09-28 06:49:38.692  5634  5680 I jxcore-log: 
,09-28 06:49:39.259  5634  5680 I jxcore-log: # setup
09-28 06:49:39.259  5634  5680 I jxcore-log: 
,09-28 06:49:39.342   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:40.343   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:40.406  5634  5680 I jxcore-log: # Coordinated seq test
09-28 06:49:40.406  5634  5680 I jxcore-log: 
,09-28 06:49:41.231  5634  5680 I jxcore-log: 2016-09-28 10:49:41 - DEBUG thaliWifiInfrastructure: 'listening 42183'
09-28 06:49:41.231  5634  5680 I jxcore-log: 
,09-28 06:49:41.344   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:42.345   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:43.346   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:49:43.776  5634  5680 I jxcore-log: ok 79 should be equal
09-28 06:49:43.776  5634  5680 I jxcore-log: 
,09-28 06:49:44.347   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 06:49:44.660  5634  5680 I jxcore-log: ok 80 should be equal
09-28 06:49:44.660  5634  5680 I jxcore-log: 
,09-28 06:49:44.673  5634  5680 I jxcore-log: # teardown
09-28 06:49:44.673  5634  5680 I jxcore-log: 
,09-28 06:49:58.306   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:50:01.346   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411198, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:50:04.348   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:05.349   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:06.351   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:07.352   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:08.332   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:50:08.353   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:09.354   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 06:50:20.038   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=429890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:50:33.398   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:50:34.355   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 06:50:34.355   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 06:50:38.311   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:50:44.690  5634  5680 I jxcore-log: 2016-09-28 10:50:44 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-28 06:50:44.690  5634  5680 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-28 06:50:44.690  5634  5680 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-28 06:50:44.690  5634  5680 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-28 06:50:44.690  5634  5680 I jxcore-log:     at $9@timers.js:120:1
09-28 06:50:44.690  5634  5680 I jxcore-log: ''
09-28 06:50:44.690  5634  5680 I jxcore-log: 
,09-28 06:50:45.079   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=454930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:50:54.356   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:55.358   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:56.359   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:57.360   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:58.312   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:50:58.362   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:50:58.439   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:50:59.362   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 06:51:04.364   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:05.366   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:06.367   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:07.369   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:08.370   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:09.371   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 06:51:10.305   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=480157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:51:18.315   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:51:19.372   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:20.374   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:21.375   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:22.377   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:23.378   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:23.665   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=493517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:51:24.379   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 06:51:35.345   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=505197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:51:39.380   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:40.382   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:41.383   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:42.384   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:43.386   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:51:44.386   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 06:51:48.692   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=518544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:51:58.320   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:52:00.386   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=530237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:52:04.388   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:52:05.389   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:52:06.390   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:52:07.392   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:52:08.393   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 06:52:09.394   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 06:52:13.719   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=543570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 06:52:18.322   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:52:25.399   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=555250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 06:52:34.395   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 06:52:34.395   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 06:52:38.323   927  3000 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 06:52:38.759   927  5931 D NetlinkSocketObserver: NeighborEvent{elapsedMs=568610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-28 06:52:41.158  5634  5680 I jxcore-log: 2016-09-28 10:52:41 - DEBUG CoordinatedClient: 'all tests completed'
09-28 06:52:41.158  5634  5680 I jxcore-log: 
,09-28 06:52:41.270  5634  5680 I jxcore-log: 2016-09-28 10:52:41 - DEBUG CoordinatedClient: 'test client disconnected'
09-28 06:52:41.270  5634  5680 I jxcore-log: 
,09-28 06:52:41.272  5634  5680 I jxcore-log: 2016-09-28 10:52:41 - DEBUG CoordinatedClient: 'test client succeed'
09-28 06:52:41.272  5634  5680 I jxcore-log: 
,09-28 06:52:41.279  5634  5680 I jxcore-log: 2016-09-28 10:52:41 - DEBUG CoordinatedThaliTape: 'all tests succeed'
09-28 06:52:41.279  5634  5680 I jxcore-log: 
09-28 06:52:41.280  5634  5680 I jxcore-log: 2016-09-28 10:52:41 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
09-28 06:52:41.280  5634  5680 I jxcore-log: 
09-28 06:52:41.288  5634  5680 I jxcore-log: not ok 81 test exited without ending
09-28 06:52:41.288  5634  5680 I jxcore-log: 
09-28 06:52:41.289  5634  5680 I jxcore-log:   ---
09-28 06:52:41.289  5634  5680 I jxcore-log: 
09-28 06:52:41.289  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.289  5634  5680 I jxcore-log: 
09-28 06:52:41.289  5634  5680 I jxcore-log:   ...
09-28 06:52:41.289  5634  5680 I jxcore-log: 
09-28 06:52:41.294  5634  5680 I jxcore-log: not ok 82 test exited without ending
09-28 06:52:41.294  5634  5680 I jxcore-log: 
09-28 06:52:41.294  5634  5680 I jxcore-log:   ---
09-28 06:52:41.294  5634  5680 I jxcore-log: 
09-28 06:52:41.294  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.294  5634  5680 I jxcore-log: 
09-28 06:52:41.294  5634  5680 I jxcore-log:   ...
09-28 06:52:41.294  5634  5680 I jxcore-log: 
09-28 06:52:41.298  5634  5680 I jxcore-log: not ok 83 test exited without ending
09-28 06:52:41.298  5634  5680 I jxcore-log: 
09-28 06:52:41.298  5634  5680 I jxcore-log:   ---
09-28 06:52:41.298  5634  5680 I jxcore-log: 
09-28 06:52:41.299  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.299  5634  5680 I jxcore-log: 
09-28 06:52:41.299  5634  5680 I jxcore-log:   ...
09-28 06:52:41.299  5634  5680 I jxcore-log: 
09-28 06:52:41.301  5634  5680 I jxcore-log: not ok 84 test exited without ending
09-28 06:52:41.301  5634  5680 I jxcore-log: 
09-28 06:52:41.301  5634  5680 I jxcore-log:   ---
09-28 06:52:41.301  5634  5680 I jxcore-log: 
09-28 06:52:41.302  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.302  5634  5680 I jxcore-log: 
09-28 06:52:41.302  5634  5680 I jxcore-log:   ...
09-28 06:52:41.302  5634  5680 I jxcore-log: 
09-28 06:52:41.304  5634  5680 I jxcore-log: not ok 85 test exited without ending
09-28 06:52:41.304  5634  5680 I jxcore-log: 
09-28 06:52:41.304  5634  5680 I jxcore-log:   ---
09-28 06:52:41.304  5634  5680 I jxcore-log: 
09-28 06:52:41.304  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.304  5634  5680 I jxcore-log: 
09-28 06:52:41.305  5634  5680 I jxcore-log:   ...
09-28 06:52:41.305  5634  5680 I jxcore-log: 
09-28 06:52:41.307  5634  5680 I jxcore-log: not ok 86 test exited without ending
09-28 06:52:41.307  5634  5680 I jxcore-log: 
09-28 06:52:41.307  5634  5680 I jxcore-log:   ---
09-28 06:52:41.307  5634  5680 I jxcore-log: 
09-28 06:52:41.307  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.307  5634  5680 I jxcore-log: 
09-28 06:52:41.308  5634  5680 I jxcore-log:   ...
09-28 06:52:41.308  5634  5680 I jxcore-log: 
09-28 06:52:41.310  5634  5680 I jxcore-log: not ok 87 test exited without ending
09-28 06:52:41.310  5634  5680 I jxcore-log: 
09-28 06:52:41.310  5634  5680 I jxcore-log:   ---
09-28 06:52:41.310  5634  5680 I jxcore-log: 
09-28 06:52:41.310  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.310  5634  5680 I jxcore-log: 
09-28 06:52:41.310  5634  5680 I jxcore-log:   ...
09-28 06:52:41.310  5634  5680 I jxcore-log: 
09-28 06:52:41.313  5634  5680 I jxcore-log: not ok 88 test exited without ending
09-28 06:52:41.313  5634  5680 I jxcore-log: 
09-28 06:52:41.313  5634  5680 I jxcore-log:   ---
09-28 06:52:41.313  5634  5680 I jxcore-log: 
09-28 06:52:41.313  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.313  5634  5680 I jxcore-log: 
09-28 06:52:41.313  5634  5680 I jxcore-log:   ...
09-28 06:52:41.313  5634  5680 I jxcore-log: 
09-28 06:52:41.315  5634  5680 I jxcore-log: not ok 89 test exited without ending
09-28 06:52:41.315  5634  5680 I jxcore-log: 
09-28 06:52:41.315  5634  5680 I jxcore-log:   ---
09-28 06:52:41.315  5634  5680 I jxcore-log: 
09-28 06:52:41.315  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.315  5634  5680 I jxcore-log: 
09-28 06:52:41.315  5634  5680 I jxcore-log:   ...
09-28 06:52:41.315  5634  5680 I jxcore-log: 
09-28 06:52:41.317  5634  5680 I jxcore-log: not ok 90 test exited without ending
09-28 06:52:41.317  5634  5680 I jxcore-log: 
09-28 06:52:41.317  5634  5680 I jxcore-log:   ---
09-28 06:52:41.317  5634  5680 I jxcore-log: 
09-28 06:52:41.317  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.317  5634  5680 I jxcore-log: 
09-28 06:52:41.317  5634  5680 I jxcore-log:   ...
09-28 06:52:41.317  5634  5680 I jxcore-log: 
09-28 06:52:41.318  5634  5680 I jxcore-log: not ok 91 test exited without ending
09-28 06:52:41.318  5634  5680 I jxcore-log: 
09-28 06:52:41.318  5634  5680 I jxcore-log:   ---
09-28 06:52:41.318  5634  5680 I jxcore-log: 
09-28 06:52:41.319  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.319  5634  5680 I jxcore-log: 
09-28 06:52:41.319  5634  5680 I jxcore-log:   ...
09-28 06:52:41.319  5634  5680 I jxcore-log: 
09-28 06:52:41.320  5634  5680 I jxcore-log: not ok 92 test exited without ending
09-28 06:52:41.320  5634  5680 I jxcore-log: 
09-28 06:52:41.320  5634  5680 I jxcore-log:   ---
09-28 06:52:41.320  5634  5680 I jxcore-log: 
09-28 06:52:41.320  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.320  5634  5680 I jxcore-log: 
09-28 06:52:41.320  5634  5680 I jxcore-log:   ...
09-28 06:52:41.320  5634  5680 I jxcore-log: 
09-28 06:52:41.321  5634  5680 I jxcore-log: not ok 93 test exited without ending
09-28 06:52:41.321  5634  5680 I jxcore-log: 
09-28 06:52:41.321  5634  5680 I jxcore-log:   ---
09-28 06:52:41.321  5634  5680 I jxcore-log: 
09-28 06:52:41.321  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.321  5634  5680 I jxcore-log: 
09-28 06:52:41.322  5634  5680 I jxcore-log:   ...
09-28 06:52:41.322  5634  5680 I jxcore-log: 
09-28 06:52:41.323  5634  5680 I jxcore-log: not ok 94 test exited without ending
09-28 06:52:41.323  5634  5680 I jxcore-log: 
09-28 06:52:41.323  5634  5680 I jxcore-log:   ---
09-28 06:52:41.323  5634  5680 I jxcore-log: 
09-28 06:52:41.323  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.323  5634  5680 I jxcore-log: 
09-28 06:52:41.323  5634  5680 I jxcore-log:   ...
09-28 06:52:41.323  5634  5680 I jxcore-log: 
09-28 06:52:41.325  5634  5680 I jxcore-log: not ok 95 test exited without ending
09-28 06:52:41.325  5634  5680 I jxcore-log: 
09-28 06:52:41.325  5634  5680 I jxcore-log:   ---
09-28 06:52:41.325  5634  5680 I jxcore-log: 
09-28 06:52:41.325  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.325  5634  5680 I jxcore-log: 
09-28 06:52:41.325  5634  5680 I jxcore-log:   ...
09-28 06:52:41.325  5634  5680 I jxcore-log: 
09-28 06:52:41.327  5634  5680 I jxcore-log: not ok 96 test exited without ending
09-28 06:52:41.327  5634  5680 I jxcore-log: 
09-28 06:52:41.327  5634  5680 I jxcore-log:   ---
09-28 06:52:41.327  5634  5680 I jxcore-log: 
09-28 06:52:41.327  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.327  5634  5680 I jxcore-log: 
09-28 06:52:41.327  5634  5680 I jxcore-log:   ...
09-28 06:52:41.327  5634  5680 I jxcore-log: 
09-28 06:52:41.328  5634  5680 I jxcore-log: not ok 97 test exited without ending
09-28 06:52:41.328  5634  5680 I jxcore-log: 
09-28 06:52:41.328  5634  5680 I jxcore-log:   ---
09-28 06:52:41.328  5634  5680 I jxcore-log: 
09-28 06:52:41.328  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.328  5634  5680 I jxcore-log: 
09-28 06:52:41.328  5634  5680 I jxcore-log:   ...
09-28 06:52:41.328  5634  5680 I jxcore-log: 
09-28 06:52:41.330  5634  5680 I jxcore-log: not ok 98 test exited without ending
09-28 06:52:41.330  5634  5680 I jxcore-log: 
09-28 06:52:41.330  5634  5680 I jxcore-log:   ---
09-28 06:52:41.330  5634  5680 I jxcore-log: 
09-28 06:52:41.330  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.330  5634  5680 I jxcore-log: 
09-28 06:52:41.330  5634  5680 I jxcore-log:   ...
09-28 06:52:41.330  5634  5680 I jxcore-log: 
09-28 06:52:41.331  5634  5680 I jxcore-log: not ok 99 test exited without ending
09-28 06:52:41.331  5634  5680 I jxcore-log: 
09-28 06:52:41.331  5634  5680 I jxcore-log:   ---
09-28 06:52:41.331  5634  5680 I jxcore-log: 
09-28 06:52:41.331  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.331  5634  5680 I jxcore-log: 
09-28 06:52:41.331  5634  5680 I jxcore-log:   ...
09-28 06:52:41.331  5634  5680 I jxcore-log: 
,09-28 06:52:41.333  5634  5680 I jxcore-log: not ok 100 test exited without ending
09-28 06:52:41.333  5634  5680 I jxcore-log: 
09-28 06:52:41.333  5634  5680 I jxcore-log:   ---
09-28 06:52:41.333  5634  5680 I jxcore-log: 
09-28 06:52:41.333  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.333  5634  5680 I jxcore-log: 
09-28 06:52:41.333  5634  5680 I jxcore-log:   ...
09-28 06:52:41.333  5634  5680 I jxcore-log: 
09-28 06:52:41.334  5634  5680 I jxcore-log: not ok 101 test exited without ending
09-28 06:52:41.334  5634  5680 I jxcore-log: 
09-28 06:52:41.334  5634  5680 I jxcore-log:   ---
09-28 06:52:41.334  5634  5680 I jxcore-log: 
09-28 06:52:41.334  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.334  5634  5680 I jxcore-log: 
09-28 06:52:41.335  5634  5680 I jxcore-log:   ...
09-28 06:52:41.335  5634  5680 I jxcore-log: 
09-28 06:52:41.336  5634  5680 I jxcore-log: not ok 102 test exited without ending
09-28 06:52:41.336  5634  5680 I jxcore-log: 
09-28 06:52:41.336  5634  5680 I jxcore-log:   ---
09-28 06:52:41.336  5634  5680 I jxcore-log: 
09-28 06:52:41.336  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.336  5634  5680 I jxcore-log: 
09-28 06:52:41.336  5634  5680 I jxcore-log:   ...
09-28 06:52:41.336  5634  5680 I jxcore-log: 
09-28 06:52:41.337  5634  5680 I jxcore-log: not ok 103 test exited without ending
09-28 06:52:41.337  5634  5680 I jxcore-log: 
09-28 06:52:41.337  5634  5680 I jxcore-log:   ---
09-28 06:52:41.337  5634  5680 I jxcore-log: 
09-28 06:52:41.337  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.337  5634  5680 I jxcore-log: 
09-28 06:52:41.337  5634  5680 I jxcore-log:   ...
09-28 06:52:41.337  5634  5680 I jxcore-log: 
09-28 06:52:41.338  5634  5680 I jxcore-log: not ok 104 test exited without ending
09-28 06:52:41.338  5634  5680 I jxcore-log: 
09-28 06:52:41.338  5634  5680 I jxcore-log:   ---
09-28 06:52:41.338  5634  5680 I jxcore-log: 
09-28 06:52:41.338  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.338  5634  5680 I jxcore-log: 
09-28 06:52:41.338  5634  5680 I jxcore-log:   ...
09-28 06:52:41.338  5634  5680 I jxcore-log: 
09-28 06:52:41.339  5634  5680 I jxcore-log: not ok 105 test exited without ending
09-28 06:52:41.339  5634  5680 I jxcore-log: 
09-28 06:52:41.339  5634  5680 I jxcore-log:   ---
09-28 06:52:41.339  5634  5680 I jxcore-log: 
09-28 06:52:41.339  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.339  5634  5680 I jxcore-log: 
09-28 06:52:41.340  5634  5680 I jxcore-log:   ...
09-28 06:52:41.340  5634  5680 I jxcore-log: 
09-28 06:52:41.340  5634  5680 I jxcore-log: not ok 106 test exited without ending
09-28 06:52:41.340  5634  5680 I jxcore-log: 
09-28 06:52:41.340  5634  5680 I jxcore-log:   ---
09-28 06:52:41.340  5634  5680 I jxcore-log: 
09-28 06:52:41.340  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.340  5634  5680 I jxcore-log: 
09-28 06:52:41.341  5634  5680 I jxcore-log:   ...
09-28 06:52:41.341  5634  5680 I jxcore-log: 
09-28 06:52:41.341  5634  5680 I jxcore-log: not ok 107 test exited without ending
09-28 06:52:41.341  5634  5680 I jxcore-log: 
09-28 06:52:41.342  5634  5680 I jxcore-log:   ---
09-28 06:52:41.342  5634  5680 I jxcore-log: 
09-28 06:52:41.342  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.342  5634  5680 I jxcore-log: 
09-28 06:52:41.342  5634  5680 I jxcore-log:   ...
09-28 06:52:41.342  5634  5680 I jxcore-log: 
09-28 06:52:41.343  5634  5680 I jxcore-log: not ok 108 test exited without ending
09-28 06:52:41.343  5634  5680 I jxcore-log: 
09-28 06:52:41.343  5634  5680 I jxcore-log:   ---
09-28 06:52:41.343  5634  5680 I jxcore-log: 
09-28 06:52:41.343  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.343  5634  5680 I jxcore-log: 
09-28 06:52:41.343  5634  5680 I jxcore-log:   ...
09-28 06:52:41.343  5634  5680 I jxcore-log: 
09-28 06:52:41.344  5634  5680 I jxcore-log: not ok 109 test exited without ending
09-28 06:52:41.344  5634  5680 I jxcore-log: 
09-28 06:52:41.344  5634  5680 I jxcore-log:   ---
09-28 06:52:41.344  5634  5680 I jxcore-log: 
09-28 06:52:41.344  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.344  5634  5680 I jxcore-log: 
09-28 06:52:41.344  5634  5680 I jxcore-log:   ...
09-28 06:52:41.344  5634  5680 I jxcore-log: 
09-28 06:52:41.345  5634  5680 I jxcore-log: not ok 110 test exited without ending
09-28 06:52:41.345  5634  5680 I jxcore-log: 
09-28 06:52:41.345  5634  5680 I jxcore-log:   ---
09-28 06:52:41.345  5634  5680 I jxcore-log: 
09-28 06:52:41.345  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.345  5634  5680 I jxcore-log: 
09-28 06:52:41.345  5634  5680 I jxcore-log:   ...
09-28 06:52:41.345  5634  5680 I jxcore-log: 
09-28 06:52:41.346  5634  5680 I jxcore-log: not ok 111 test exited without ending
09-28 06:52:41.346  5634  5680 I jxcore-log: 
09-28 06:52:41.346  5634  5680 I jxcore-log:   ---
09-28 06:52:41.346  5634  5680 I jxcore-log: 
09-28 06:52:41.346  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.346  5634  5680 I jxcore-log: 
09-28 06:52:41.346  5634  5680 I jxcore-log:   ...
09-28 06:52:41.346  5634  5680 I jxcore-log: 
09-28 06:52:41.347  5634  5680 I jxcore-log: not ok 112 test exited without ending
09-28 06:52:41.347  5634  5680 I jxcore-log: 
09-28 06:52:41.347  5634  5680 I jxcore-log:   ---
09-28 06:52:41.347  5634  5680 I jxcore-log: 
09-28 06:52:41.347  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.347  5634  5680 I jxcore-log: 
09-28 06:52:41.347  5634  5680 I jxcore-log:   ...
09-28 06:52:41.347  5634  5680 I jxcore-log: 
09-28 06:52:41.348  5634  5680 I jxcore-log: not ok 113 test exited without ending
09-28 06:52:41.348  5634  5680 I jxcore-log: 
09-28 06:52:41.348  5634  5680 I jxcore-log:   ---
09-28 06:52:41.348  5634  5680 I jxcore-log: 
09-28 06:52:41.348  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.348  5634  5680 I jxcore-log: 
09-28 06:52:41.348  5634  5680 I jxcore-log:   ...
09-28 06:52:41.348  5634  5680 I jxcore-log: 
09-28 06:52:41.349  5634  5680 I jxcore-log: not ok 114 test exited without ending
09-28 06:52:41.349  5634  5680 I jxcore-log: 
09-28 06:52:41.349  5634  5680 I jxcore-log:   ---
09-28 06:52:41.349  5634  5680 I jxcore-log: 
09-28 06:52:41.349  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.349  5634  5680 I jxcore-log: 
09-28 06:52:41.350  5634  5680 I jxcore-log:   ...
09-28 06:52:41.350  5634  5680 I jxcore-log: 
09-28 06:52:41.351  5634  5680 I jxcore-log: not ok 115 test exited without ending
09-28 06:52:41.351  5634  5680 I jxcore-log: 
09-28 06:52:41.351  5634  5680 I jxcore-log:   ---
09-28 06:52:41.351  5634  5680 I jxcore-log: 
09-28 06:52:41.351  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.351  5634  5680 I jxcore-log: 
09-28 06:52:41.351  5634  5680 I jxcore-log:   ...
09-28 06:52:41.351  5634  5680 I jxcore-log: 
09-28 06:52:41.352  5634  5680 I jxcore-log: not ok 116 test exited without ending
09-28 06:52:41.352  5634  5680 I jxcore-log: 
09-28 06:52:41.352  5634  5680 I jxcore-log:   ---
09-28 06:52:41.352  5634  5680 I jxcore-log: 
09-28 06:52:41.352  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.352  5634  5680 I jxcore-log: 
09-28 06:52:41.352  5634  5680 I jxcore-log:   ...
09-28 06:52:41.352  5634  5680 I jxcore-log: 
09-28 06:52:41.353  5634  5680 I jxcore-log: not ok 117 test exited without ending
09-28 06:52:41.353  5634  5680 I jxcore-log: 
09-28 06:52:41.353  5634  5680 I jxcore-log:   ---
09-28 06:52:41.353  5634  5680 I jxcore-log: 
09-28 06:52:41.353  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.353  5634  5680 I jxcore-log: 
09-28 06:52:41.353  5634  5680 I jxcore-log:   ...
09-28 06:52:41.353  5634  5680 I jxcore-log: 
09-28 06:52:41.355  5634  5680 I jxcore-log: not ok 118 test exited without ending
09-28 06:52:41.355  5634  5680 I jxcore-log: 
09-28 06:52:41.355  5634  5680 I jxcore-log:   ---
09-28 06:52:41.355  5634  5680 I jxcore-log: 
09-28 06:52:41.355  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.355  5634  5680 I jxcore-log: 
09-28 06:52:41.355  5634  5680 I jxcore-log:   ...
09-28 06:52:41.355  5634  5680 I jxcore-log: 
09-28 06:52:41.356  5634  5680 I jxcore-log: not ok 119 test exited without ending
09-28 06:52:41.356  5634  5680 I jxcore-log: 
09-28 06:52:41.356  5634  5680 I jxcore-log:   ---
09-28 06:52:41.356  5634  5680 I jxcore-log: 
09-28 06:52:41.356  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.356  5634  5680 I jxcore-log: 
09-28 06:52:41.356  5634  5680 I jxcore-log:   ...
09-28 06:52:41.356  5634  5680 I jxcore-log: 
09-28 06:52:41.357  5634  5680 I jxcore-log: not ok 120 test exited without ending
09-28 06:52:41.357  5634  5680 I jxcore-log: 
09-28 06:52:41.357  5634  5680 I jxcore-log:   ---
09-28 06:52:41.357  5634  5680 I jxcore-log: 
09-28 06:52:41.357  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.357  5634  5680 I jxcore-log: 
09-28 06:52:41.357  5634  5680 I jxcore-log:   ...
09-28 06:52:41.357  5634  5680 I jxcore-log: 
09-28 06:52:41.358  5634  5680 I jxcore-log: not ok 121 test exited without ending
09-28 06:52:41.358  5634  5680 I jxcore-log: 
09-28 06:52:41.358  5634  5680 I jxcore-log:   ---
09-28 06:52:41.358  5634  5680 I jxcore-log: 
09-28 06:52:41.358  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.358  5634  5680 I jxcore-log: 
09-28 06:52:41.358  5634  5680 I jxcore-log:   ...
09-28 06:52:41.358  5634  5680 I jxcore-log: 
09-28 06:52:41.359  5634  5680 I jxcore-log: not ok 122 test exited without ending
09-28 06:52:41.359  5634  5680 I jxcore-log: 
09-28 06:52:41.359  5634  5680 I jxcore-log:   ---
09-28 06:52:41.359  5634  5680 I jxcore-log: 
09-28 06:52:41.359  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.359  5634  5680 I jxcore-log: 
09-28 06:52:41.359  5634  5680 I jxcore-log:   ...
09-28 06:52:41.359  5634  5680 I jxcore-log: 
09-28 06:52:41.360  5634  5680 I jxcore-log: not ok 123 test exited without ending
09-28 06:52:41.360  5634  5680 I jxcore-log: 
09-28 06:52:41.360  5634  5680 I jxcore-log:   ---
09-28 06:52:41.360  5634  5680 I jxcore-log: 
09-28 06:52:41.360  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.360  5634  5680 I jxcore-log: 
09-28 06:52:41.360  5634  5680 I jxcore-log:   ...
09-28 06:52:41.360  5634  5680 I jxcore-log: 
09-28 06:52:41.361  5634  5680 I jxcore-log: not ok 124 test exited without ending
09-28 06:52:41.361  5634  5680 I jxcore-log: 
09-28 06:52:41.361  5634  5680 I jxcore-log:   ---
09-28 06:52:41.361  5634  5680 I jxcore-log: 
09-28 06:52:41.361  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.361  5634  5680 I jxcore-log: 
09-28 06:52:41.362  5634  5680 I jxcore-log:   ...
09-28 06:52:41.362  5634  5680 I jxcore-log: 
09-28 06:52:41.362  5634  5680 I jxcore-log: not ok 125 test exited without ending
09-28 06:52:41.362  5634  5680 I jxcore-log: 
09-28 06:52:41.362  5634  5680 I jxcore-log:   ---
09-28 06:52:41.362  5634  5680 I jxcore-log: 
09-28 06:52:41.363  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.363  5634  5680 I jxcore-log: 
09-28 06:52:41.363  5634  5680 I jxcore-log:   ...
09-28 06:52:41.363  5634  5680 I jxcore-log: 
,09-28 06:52:41.372  5634  5680 I jxcore-log: not ok 126 test exited without ending
09-28 06:52:41.372  5634  5680 I jxcore-log: 
09-28 06:52:41.372  5634  5680 I jxcore-log:   ---
09-28 06:52:41.372  5634  5680 I jxcore-log: 
09-28 06:52:41.372  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.372  5634  5680 I jxcore-log: 
09-28 06:52:41.372  5634  5680 I jxcore-log:   ...
09-28 06:52:41.372  5634  5680 I jxcore-log: 
09-28 06:52:41.373  5634  5680 I jxcore-log: not ok 127 test exited without ending
09-28 06:52:41.373  5634  5680 I jxcore-log: 
09-28 06:52:41.373  5634  5680 I jxcore-log:   ---
09-28 06:52:41.373  5634  5680 I jxcore-log: 
09-28 06:52:41.373  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.373  5634  5680 I jxcore-log: 
09-28 06:52:41.373  5634  5680 I jxcore-log:   ...
09-28 06:52:41.373  5634  5680 I jxcore-log: 
09-28 06:52:41.374  5634  5680 I jxcore-log: not ok 128 test exited without ending
09-28 06:52:41.374  5634  5680 I jxcore-log: 
09-28 06:52:41.374  5634  5680 I jxcore-log:   ---
09-28 06:52:41.374  5634  5680 I jxcore-log: 
09-28 06:52:41.374  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.374  5634  5680 I jxcore-log: 
09-28 06:52:41.374  5634  5680 I jxcore-log:   ...
09-28 06:52:41.374  5634  5680 I jxcore-log: 
09-28 06:52:41.375  5634  5680 I jxcore-log: not ok 129 test exited without ending
09-28 06:52:41.375  5634  5680 I jxcore-log: 
09-28 06:52:41.375  5634  5680 I jxcore-log:   ---
09-28 06:52:41.375  5634  5680 I jxcore-log: 
09-28 06:52:41.375  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.375  5634  5680 I jxcore-log: 
09-28 06:52:41.375  5634  5680 I jxcore-log:   ...
09-28 06:52:41.375  5634  5680 I jxcore-log: 
09-28 06:52:41.376  5634  5680 I jxcore-log: not ok 130 test exited without ending
09-28 06:52:41.376  5634  5680 I jxcore-log: 
09-28 06:52:41.376  5634  5680 I jxcore-log:   ---
09-28 06:52:41.376  5634  5680 I jxcore-log: 
09-28 06:52:41.376  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.376  5634  5680 I jxcore-log: 
09-28 06:52:41.376  5634  5680 I jxcore-log:   ...
09-28 06:52:41.376  5634  5680 I jxcore-log: 
09-28 06:52:41.376  5634  5680 I jxcore-log: not ok 131 test exited without ending
09-28 06:52:41.376  5634  5680 I jxcore-log: 
09-28 06:52:41.377  5634  5680 I jxcore-log:   ---
09-28 06:52:41.377  5634  5680 I jxcore-log: 
09-28 06:52:41.377  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.377  5634  5680 I jxcore-log: 
09-28 06:52:41.377  5634  5680 I jxcore-log:   ...
09-28 06:52:41.377  5634  5680 I jxcore-log: 
09-28 06:52:41.378  5634  5680 I jxcore-log: not ok 132 test exited without ending
09-28 06:52:41.378  5634  5680 I jxcore-log: 
09-28 06:52:41.378  5634  5680 I jxcore-log:   ---
09-28 06:52:41.378  5634  5680 I jxcore-log: 
09-28 06:52:41.378  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.378  5634  5680 I jxcore-log: 
09-28 06:52:41.378  5634  5680 I jxcore-log:   ...
09-28 06:52:41.378  5634  5680 I jxcore-log: 
09-28 06:52:41.379  5634  5680 I jxcore-log: not ok 133 test exited without ending
09-28 06:52:41.379  5634  5680 I jxcore-log: 
09-28 06:52:41.379  5634  5680 I jxcore-log:   ---
09-28 06:52:41.379  5634  5680 I jxcore-log: 
09-28 06:52:41.379  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.379  5634  5680 I jxcore-log: 
,09-28 06:52:41.379  5634  5680 I jxcore-log:   ...
09-28 06:52:41.379  5634  5680 I jxcore-log: 
09-28 06:52:41.380  5634  5680 I jxcore-log: not ok 134 test exited without ending
09-28 06:52:41.380  5634  5680 I jxcore-log: 
09-28 06:52:41.380  5634  5680 I jxcore-log:   ---
09-28 06:52:41.380  5634  5680 I jxcore-log: 
09-28 06:52:41.380  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.380  5634  5680 I jxcore-log: 
09-28 06:52:41.380  5634  5680 I jxcore-log:   ...
09-28 06:52:41.380  5634  5680 I jxcore-log: 
09-28 06:52:41.381  5634  5680 I jxcore-log: not ok 135 test exited without ending
09-28 06:52:41.381  5634  5680 I jxcore-log: 
09-28 06:52:41.381  5634  5680 I jxcore-log:   ---
09-28 06:52:41.381  5634  5680 I jxcore-log: 
09-28 06:52:41.381  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.381  5634  5680 I jxcore-log: 
09-28 06:52:41.381  5634  5680 I jxcore-log:   ...
09-28 06:52:41.381  5634  5680 I jxcore-log: 
,09-28 06:52:41.382  5634  5680 I jxcore-log: not ok 136 test exited without ending
09-28 06:52:41.382  5634  5680 I jxcore-log: 
09-28 06:52:41.382  5634  5680 I jxcore-log:   ---
09-28 06:52:41.382  5634  5680 I jxcore-log: 
09-28 06:52:41.382  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.382  5634  5680 I jxcore-log: 
09-28 06:52:41.382  5634  5680 I jxcore-log:   ...
09-28 06:52:41.382  5634  5680 I jxcore-log: 
09-28 06:52:41.382  5634  5680 I jxcore-log: not ok 137 test exited without ending
09-28 06:52:41.382  5634  5680 I jxcore-log: 
09-28 06:52:41.382  5634  5680 I jxcore-log:   ---
09-28 06:52:41.382  5634  5680 I jxcore-log: 
09-28 06:52:41.382  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.382  5634  5680 I jxcore-log: 
09-28 06:52:41.382  5634  5680 I jxcore-log:   ...
09-28 06:52:41.382  5634  5680 I jxcore-log: 
,09-28 06:52:41.383  5634  5680 I jxcore-log: not ok 138 test exited without ending
09-28 06:52:41.383  5634  5680 I jxcore-log: 
09-28 06:52:41.383  5634  5680 I jxcore-log:   ---
09-28 06:52:41.383  5634  5680 I jxcore-log: 
09-28 06:52:41.383  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.383  5634  5680 I jxcore-log: 
09-28 06:52:41.383  5634  5680 I jxcore-log:   ...
09-28 06:52:41.383  5634  5680 I jxcore-log: 
09-28 06:52:41.384  5634  5680 I jxcore-log: not ok 139 test exited without ending
09-28 06:52:41.384  5634  5680 I jxcore-log: 
09-28 06:52:41.384  5634  5680 I jxcore-log:   ---
09-28 06:52:41.384  5634  5680 I jxcore-log: 
09-28 06:52:41.384  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.384  5634  5680 I jxcore-log: 
09-28 06:52:41.384  5634  5680 I jxcore-log:   ...
09-28 06:52:41.384  5634  5680 I jxcore-log: 
09-28 06:52:41.385  5634  5680 I jxcore-log: not ok 140 test exited without ending
09-28 06:52:41.385  5634  5680 I jxcore-log: 
09-28 06:52:41.385  5634  5680 I jxcore-log:   ---
09-28 06:52:41.385  5634  5680 I jxcore-log: 
09-28 06:52:41.385  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.385  5634  5680 I jxcore-log: 
09-28 06:52:41.385  5634  5680 I jxcore-log:   ...
09-28 06:52:41.385  5634  5680 I jxcore-log: 
,09-28 06:52:41.385  5634  5680 I jxcore-log: not ok 141 test exited without ending
09-28 06:52:41.385  5634  5680 I jxcore-log: 
09-28 06:52:41.386  5634  5680 I jxcore-log:   ---
09-28 06:52:41.386  5634  5680 I jxcore-log: 
09-28 06:52:41.386  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.386  5634  5680 I jxcore-log: 
09-28 06:52:41.386  5634  5680 I jxcore-log:   ...
09-28 06:52:41.386  5634  5680 I jxcore-log: 
09-28 06:52:41.386  5634  5680 I jxcore-log: not ok 142 test exited without ending
09-28 06:52:41.386  5634  5680 I jxcore-log: 
09-28 06:52:41.386  5634  5680 I jxcore-log:   ---
09-28 06:52:41.386  5634  5680 I jxcore-log: 
09-28 06:52:41.386  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.386  5634  5680 I jxcore-log: 
09-28 06:52:41.386  5634  5680 I jxcore-log:   ...
09-28 06:52:41.386  5634  5680 I jxcore-log: 
09-28 06:52:41.387  5634  5680 I jxcore-log: not ok 143 test exited without ending
09-28 06:52:41.387  5634  5680 I jxcore-log: 
09-28 06:52:41.387  5634  5680 I jxcore-log:   ---
09-28 06:52:41.387  5634  5680 I jxcore-log: 
09-28 06:52:41.387  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.387  5634  5680 I jxcore-log: 
09-28 06:52:41.387  5634  5680 I jxcore-log:   ...
09-28 06:52:41.387  5634  5680 I jxcore-log: 
,09-28 06:52:41.388  5634  5680 I jxcore-log: not ok 144 test exited without ending
09-28 06:52:41.388  5634  5680 I jxcore-log: 
09-28 06:52:41.388  5634  5680 I jxcore-log:   ---
09-28 06:52:41.388  5634  5680 I jxcore-log: 
09-28 06:52:41.388  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.388  5634  5680 I jxcore-log: 
09-28 06:52:41.388  5634  5680 I jxcore-log:   ...
09-28 06:52:41.388  5634  5680 I jxcore-log: 
09-28 06:52:41.389  5634  5680 I jxcore-log: not ok 145 test exited without ending
09-28 06:52:41.389  5634  5680 I jxcore-log: 
09-28 06:52:41.389  5634  5680 I jxcore-log:   ---
09-28 06:52:41.389  5634  5680 I jxcore-log: 
09-28 06:52:41.389  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.389  5634  5680 I jxcore-log: 
09-28 06:52:41.389  5634  5680 I jxcore-log:   ...
09-28 06:52:41.389  5634  5680 I jxcore-log: 
09-28 06:52:41.389  5634  5680 I jxcore-log: not ok 146 test exited without ending
09-28 06:52:41.389  5634  5680 I jxcore-log: 
09-28 06:52:41.390  5634  5680 I jxcore-log:   ---
09-28 06:52:41.390  5634  5680 I jxcore-log: 
09-28 06:52:41.390  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.390  5634  5680 I jxcore-log: 
09-28 06:52:41.390  5634  5680 I jxcore-log:   ...
09-28 06:52:41.390  5634  5680 I jxcore-log: 
09-28 06:52:41.390  5634  5680 I jxcore-log: not ok 147 test exited without ending
09-28 06:52:41.390  5634  5680 I jxcore-log: 
09-28 06:52:41.390  5634  5680 I jxcore-log:   ---
09-28 06:52:41.390  5634  5680 I jxcore-log: 
09-28 06:52:41.390  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.390  5634  5680 I jxcore-log: 
09-28 06:52:41.390  5634  5680 I jxcore-log:   ...
09-28 06:52:41.390  5634  5680 I jxcore-log: 
09-28 06:52:41.391  5634  5680 I jxcore-log: not ok 148 test exited without ending
09-28 06:52:41.391  5634  5680 I jxcore-log: 
09-28 06:52:41.391  5634  5680 I jxcore-log:   ---
09-28 06:52:41.391  5634  5680 I jxcore-log: 
09-28 06:52:41.391  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.391  5634  5680 I jxcore-log: 
09-28 06:52:41.391  5634  5680 I jxcore-log:   ...
09-28 06:52:41.391  5634  5680 I jxcore-log: 
09-28 06:52:41.392  5634  5680 I jxcore-log: not ok 149 test exited without ending
09-28 06:52:41.392  5634  5680 I jxcore-log: 
09-28 06:52:41.392  5634  5680 I jxcore-log:   ---
09-28 06:52:41.392  5634  5680 I jxcore-log: 
09-28 06:52:41.392  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.392  5634  5680 I jxcore-log: 
09-28 06:52:41.392  5634  5680 I jxcore-log:   ...
09-28 06:52:41.392  5634  5680 I jxcore-log: 
09-28 06:52:41.393  5634  5680 I jxcore-log: not ok 150 test exited without ending
09-28 06:52:41.393  5634  5680 I jxcore-log: 
09-28 06:52:41.393  5634  5680 I jxcore-log:   ---
09-28 06:52:41.393  5634  5680 I jxcore-log: 
09-28 06:52:41.393  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.393  5634  5680 I jxcore-log: 
09-28 06:52:41.393  5634  5680 I jxcore-log:   ...
09-28 06:52:41.393  5634  5680 I jxcore-log: 
09-28 06:52:41.393  5634  5680 I jxcore-log: not ok 151 test exited without ending
09-28 06:52:41.393  5634  5680 I jxcore-log: 
09-28 06:52:41.394  5634  5680 I jxcore-log:   ---
09-28 06:52:41.394  5634  5680 I jxcore-log: 
09-28 06:52:41.394  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.394  5634  5680 I jxcore-log: 
09-28 06:52:41.394  5634  5680 I jxcore-log:   ...
09-28 06:52:41.394  5634  5680 I jxcore-log: 
09-28 06:52:41.394  5634  5680 I jxcore-log: not ok 152 test exited without ending
09-28 06:52:41.394  5634  5680 I jxcore-log: 
09-28 06:52:41.394  5634  5680 I jxcore-log:   ---
09-28 06:52:41.394  5634  5680 I jxcore-log: 
09-28 06:52:41.394  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.394  5634  5680 I jxcore-log: 
09-28 06:52:41.394  5634  5680 I jxcore-log:   ...
09-28 06:52:41.394  5634  5680 I jxcore-log: 
09-28 06:52:41.395  5634  5680 I jxcore-log: not ok 153 test exited without ending
09-28 06:52:41.395  5634  5680 I jxcore-log: 
09-28 06:52:41.396  5634  5680 I jxcore-log:   ---
09-28 06:52:41.396  5634  5680 I jxcore-log: 
09-28 06:52:41.396  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.396  5634  5680 I jxcore-log: 
09-28 06:52:41.396  5634  5680 I jxcore-log:   ...
09-28 06:52:41.396  5634  5680 I jxcore-log: 
09-28 06:52:41.396  5634  5680 I jxcore-log: not ok 154 test exited without ending
09-28 06:52:41.396  5634  5680 I jxcore-log: 
09-28 06:52:41.396  5634  5680 I jxcore-log:   ---
09-28 06:52:41.396  5634  5680 I jxcore-log: 
09-28 06:52:41.396  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.396  5634  5680 I jxcore-log: 
09-28 06:52:41.396  5634  5680 I jxcore-log:   ...
09-28 06:52:41.396  5634  5680 I jxcore-log: 
09-28 06:52:41.397  5634  5680 I jxcore-log: not ok 155 test exited without ending
09-28 06:52:41.397  5634  5680 I jxcore-log: 
09-28 06:52:41.397  5634  5680 I jxcore-log:   ---
09-28 06:52:41.397  5634  5680 I jxcore-log: 
09-28 06:52:41.397  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.397  5634  5680 I jxcore-log: 
09-28 06:52:41.397  5634  5680 I jxcore-log:   ...
09-28 06:52:41.397  5634  5680 I jxcore-log: 
09-28 06:52:41.398  5634  5680 I jxcore-log: not ok 156 test exited without ending
09-28 06:52:41.398  5634  5680 I jxcore-log: 
09-28 06:52:41.398  5634  5680 I jxcore-log:   ---
09-28 06:52:41.398  5634  5680 I jxcore-log: 
09-28 06:52:41.398  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.398  5634  5680 I jxcore-log: 
09-28 06:52:41.398  5634  5680 I jxcore-log:   ...
09-28 06:52:41.398  5634  5680 I jxcore-log: 
09-28 06:52:41.399  5634  5680 I jxcore-log: not ok 157 test exited without ending
09-28 06:52:41.399  5634  5680 I jxcore-log: 
09-28 06:52:41.399  5634  5680 I jxcore-log:   ---
09-28 06:52:41.399  5634  5680 I jxcore-log: 
09-28 06:52:41.399  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.399  5634  5680 I jxcore-log: 
09-28 06:52:41.399  5634  5680 I jxcore-log:   ...
09-28 06:52:41.399  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log: not ok 158 test exited without ending
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log:   ---
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log:   ...
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log: not ok 159 test exited without ending
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log:   ---
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.400  5634  5680 I jxcore-log:   ...
09-28 06:52:41.400  5634  5680 I jxcore-log: 
09-28 06:52:41.401  5634  5680 I jxcore-log: not ok 160 test exited without ending
09-28 06:52:41.401  5634  5680 I jxcore-log: 
09-28 06:52:41.401  5634  5680 I jxcore-log:   ---
09-28 06:52:41.401  5634  5680 I jxcore-log: 
09-28 06:52:41.401  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.401  5634  5680 I jxcore-log: 
09-28 06:52:41.401  5634  5680 I jxcore-log:   ...
09-28 06:52:41.401  5634  5680 I jxcore-log: 
09-28 06:52:41.402  5634  5680 I jxcore-log: not ok 161 test exited without ending
09-28 06:52:41.402  5634  5680 I jxcore-log: 
09-28 06:52:41.402  5634  5680 I jxcore-log:   ---
09-28 06:52:41.402  5634  5680 I jxcore-log: 
09-28 06:52:41.402  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.402  5634  5680 I jxcore-log: 
09-28 06:52:41.402  5634  5680 I jxcore-log:   ...
09-28 06:52:41.402  5634  5680 I jxcore-log: 
09-28 06:52:41.403  5634  5680 I jxcore-log: not ok 162 test exited without ending
09-28 06:52:41.403  5634  5680 I jxcore-log: 
09-28 06:52:41.403  5634  5680 I jxcore-log:   ---
09-28 06:52:41.403  5634  5680 I jxcore-log: 
09-28 06:52:41.403  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.403  5634  5680 I jxcore-log: 
09-28 06:52:41.403  5634  5680 I jxcore-log:   ...
09-28 06:52:41.403  5634  5680 I jxcore-log: 
09-28 06:52:41.403  5634  5680 I jxcore-log: not ok 163 test exited without ending
09-28 06:52:41.403  5634  5680 I jxcore-log: 
09-28 06:52:41.404  5634  5680 I jxcore-log:   ---
09-28 06:52:41.404  5634  5680 I jxcore-log: 
09-28 06:52:41.404  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.404  5634  5680 I jxcore-log: 
09-28 06:52:41.404  5634  5680 I jxcore-log:   ...
09-28 06:52:41.404  5634  5680 I jxcore-log: 
09-28 06:52:41.404  5634  5680 I jxcore-log: not ok 164 test exited without ending
09-28 06:52:41.404  5634  5680 I jxcore-log: 
09-28 06:52:41.404  5634  5680 I jxcore-log:   ---
09-28 06:52:41.404  5634  5680 I jxcore-log: 
09-28 06:52:41.404  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.404  5634  5680 I jxcore-log: 
09-28 06:52:41.404  5634  5680 I jxcore-log:   ...
09-28 06:52:41.404  5634  5680 I jxcore-log: 
09-28 06:52:41.405  5634  5680 I jxcore-log: not ok 165 test exited without ending
09-28 06:52:41.405  5634  5680 I jxcore-log: 
09-28 06:52:41.405  5634  5680 I jxcore-log:   ---
09-28 06:52:41.405  5634  5680 I jxcore-log: 
09-28 06:52:41.405  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.405  5634  5680 I jxcore-log: 
09-28 06:52:41.405  5634  5680 I jxcore-log:   ...
09-28 06:52:41.405  5634  5680 I jxcore-log: 
09-28 06:52:41.406  5634  5680 I jxcore-log: not ok 166 test exited without ending
09-28 06:52:41.406  5634  5680 I jxcore-log: 
09-28 06:52:41.406  5634  5680 I jxcore-log:   ---
09-28 06:52:41.406  5634  5680 I jxcore-log: 
09-28 06:52:41.406  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.406  5634  5680 I jxcore-log: 
09-28 06:52:41.406  5634  5680 I jxcore-log:   ...
09-28 06:52:41.406  5634  5680 I jxcore-log: 
09-28 06:52:41.407  5634  5680 I jxcore-log: not ok 167 test exited without ending
09-28 06:52:41.407  5634  5680 I jxcore-log: 
09-28 06:52:41.407  5634  5680 I jxcore-log:   ---
09-28 06:52:41.407  5634  5680 I jxcore-log: 
09-28 06:52:41.407  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.407  5634  5680 I jxcore-log: 
09-28 06:52:41.407  5634  5680 I jxcore-log:   ...
09-28 06:52:41.407  5634  5680 I jxcore-log: 
09-28 06:52:41.407  5634  5680 I jxcore-log: not ok 168 test exited without ending
09-28 06:52:41.407  5634  5680 I jxcore-log: 
09-28 06:52:41.407  5634  5680 I jxcore-log:   ---
09-28 06:52:41.407  5634  5680 I jxcore-log: 
09-28 06:52:41.408  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.408  5634  5680 I jxcore-log: 
09-28 06:52:41.408  5634  5680 I jxcore-log:   ...
09-28 06:52:41.408  5634  5680 I jxcore-log: 
09-28 06:52:41.408  5634  5680 I jxcore-log: not ok 169 test exited without ending
09-28 06:52:41.408  5634  5680 I jxcore-log: 
09-28 06:52:41.408  5634  5680 I jxcore-log:   ---
09-28 06:52:41.408  5634  5680 I jxcore-log: 
09-28 06:52:41.408  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.408  5634  5680 I jxcore-log: 
09-28 06:52:41.408  5634  5680 I jxcore-log:   ...
09-28 06:52:41.408  5634  5680 I jxcore-log: 
09-28 06:52:41.409  5634  5680 I jxcore-log: not ok 170 test exited without ending
09-28 06:52:41.409  5634  5680 I jxcore-log: 
09-28 06:52:41.409  5634  5680 I jxcore-log:   ---
09-28 06:52:41.409  5634  5680 I jxcore-log: 
09-28 06:52:41.409  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.409  5634  5680 I jxcore-log: 
09-28 06:52:41.409  5634  5680 I jxcore-log:   ...
09-28 06:52:41.409  5634  5680 I jxcore-log: 
09-28 06:52:41.410  5634  5680 I jxcore-log: not ok 171 test exited without ending
09-28 06:52:41.410  5634  5680 I jxcore-log: 
09-28 06:52:41.410  5634  5680 I jxcore-log:   ---
09-28 06:52:41.410  5634  5680 I jxcore-log: 
09-28 06:52:41.410  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.410  5634  5680 I jxcore-log: 
09-28 06:52:41.410  5634  5680 I jxcore-log:   ...
09-28 06:52:41.410  5634  5680 I jxcore-log: 
09-28 06:52:41.411  5634  5680 I jxcore-log: not ok 172 test exited without ending
09-28 06:52:41.411  5634  5680 I jxcore-log: 
09-28 06:52:41.411  5634  5680 I jxcore-log:   ---
09-28 06:52:41.411  5634  5680 I jxcore-log: 
09-28 06:52:41.411  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.411  5634  5680 I jxcore-log: 
09-28 06:52:41.411  5634  5680 I jxcore-log:   ...
09-28 06:52:41.411  5634  5680 I jxcore-log: 
09-28 06:52:41.411  5634  5680 I jxcore-log: not ok 173 test exited without ending
09-28 06:52:41.411  5634  5680 I jxcore-log: 
09-28 06:52:41.411  5634  5680 I jxcore-log:   ---
09-28 06:52:41.411  5634  5680 I jxcore-log: 
09-28 06:52:41.412  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.412  5634  5680 I jxcore-log: 
09-28 06:52:41.412  5634  5680 I jxcore-log:   ...
09-28 06:52:41.412  5634  5680 I jxcore-log: 
09-28 06:52:41.412  5634  5680 I jxcore-log: not ok 174 test exited without ending
09-28 06:52:41.412  5634  5680 I jxcore-log: 
09-28 06:52:41.412  5634  5680 I jxcore-log:   ---
09-28 06:52:41.412  5634  5680 I jxcore-log: 
09-28 06:52:41.412  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.412  5634  5680 I jxcore-log: 
09-28 06:52:41.412  5634  5680 I jxcore-log:   ...
09-28 06:52:41.412  5634  5680 I jxcore-log: 
09-28 06:52:41.413  5634  5680 I jxcore-log: not ok 175 test exited without ending
09-28 06:52:41.413  5634  5680 I jxcore-log: 
09-28 06:52:41.413  5634  5680 I jxcore-log:   ---
09-28 06:52:41.413  5634  5680 I jxcore-log: 
09-28 06:52:41.413  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.413  5634  5680 I jxcore-log: 
09-28 06:52:41.413  5634  5680 I jxcore-log:   ...
09-28 06:52:41.413  5634  5680 I jxcore-log: 
09-28 06:52:41.414  5634  5680 I jxcore-log: not ok 176 test exited without ending
09-28 06:52:41.414  5634  5680 I jxcore-log: 
09-28 06:52:41.414  5634  5680 I jxcore-log:   ---
09-28 06:52:41.414  5634  5680 I jxcore-log: 
09-28 06:52:41.414  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.414  5634  5680 I jxcore-log: 
09-28 06:52:41.414  5634  5680 I jxcore-log:   ...
09-28 06:52:41.414  5634  5680 I jxcore-log: 
09-28 06:52:41.415  5634  5680 I jxcore-log: not ok 177 test exited without ending
09-28 06:52:41.415  5634  5680 I jxcore-log: 
09-28 06:52:41.415  5634  5680 I jxcore-log:   ---
09-28 06:52:41.415  5634  5680 I jxcore-log: 
09-28 06:52:41.415  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.415  5634  5680 I jxcore-log: 
09-28 06:52:41.415  5634  5680 I jxcore-log:   ...
09-28 06:52:41.415  5634  5680 I jxcore-log: 
,09-28 06:52:41.415  5634  5680 I jxcore-log: not ok 178 test exited without ending
09-28 06:52:41.415  5634  5680 I jxcore-log: 
09-28 06:52:41.415  5634  5680 I jxcore-log:   ---
09-28 06:52:41.415  5634  5680 I jxcore-log: 
09-28 06:52:41.415  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.415  5634  5680 I jxcore-log: 
09-28 06:52:41.416  5634  5680 I jxcore-log:   ...
09-28 06:52:41.416  5634  5680 I jxcore-log: 
,09-28 06:52:41.416  5634  5680 I jxcore-log: not ok 179 test exited without ending
09-28 06:52:41.416  5634  5680 I jxcore-log: 
09-28 06:52:41.416  5634  5680 I jxcore-log:   ---
09-28 06:52:41.416  5634  5680 I jxcore-log: 
09-28 06:52:41.416  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.416  5634  5680 I jxcore-log: 
09-28 06:52:41.416  5634  5680 I jxcore-log:   ...
09-28 06:52:41.416  5634  5680 I jxcore-log: 
09-28 06:52:41.417  5634  5680 I jxcore-log: not ok 180 test exited without ending
09-28 06:52:41.417  5634  5680 I jxcore-log: 
09-28 06:52:41.417  5634  5680 I jxcore-log:   ---
09-28 06:52:41.417  5634  5680 I jxcore-log: 
09-28 06:52:41.417  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.417  5634  5680 I jxcore-log: 
09-28 06:52:41.417  5634  5680 I jxcore-log:   ...
09-28 06:52:41.417  5634  5680 I jxcore-log: 
,09-28 06:52:41.418  5634  5680 I jxcore-log: not ok 181 test exited without ending
09-28 06:52:41.418  5634  5680 I jxcore-log: 
09-28 06:52:41.418  5634  5680 I jxcore-log:   ---
09-28 06:52:41.418  5634  5680 I jxcore-log: 
09-28 06:52:41.418  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.418  5634  5680 I jxcore-log: 
09-28 06:52:41.418  5634  5680 I jxcore-log:   ...
09-28 06:52:41.418  5634  5680 I jxcore-log: 
,09-28 06:52:41.419  5634  5680 I jxcore-log: not ok 182 test exited without ending
09-28 06:52:41.419  5634  5680 I jxcore-log: 
09-28 06:52:41.419  5634  5680 I jxcore-log:   ---
09-28 06:52:41.419  5634  5680 I jxcore-log: 
09-28 06:52:41.419  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.419  5634  5680 I jxcore-log: 
09-28 06:52:41.419  5634  5680 I jxcore-log:   ...
09-28 06:52:41.419  5634  5680 I jxcore-log: 
09-28 06:52:41.419  5634  5680 I jxcore-log: not ok 183 test exited without ending
09-28 06:52:41.419  5634  5680 I jxcore-log: 
09-28 06:52:41.419  5634  5680 I jxcore-log:   ---
09-28 06:52:41.419  5634  5680 I jxcore-log: 
09-28 06:52:41.419  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.419  5634  5680 I jxcore-log: 
09-28 06:52:41.419  5634  5680 I jxcore-log:   ...
09-28 06:52:41.419  5634  5680 I jxcore-log: 
,09-28 06:52:41.420  5634  5680 I jxcore-log: not ok 184 test exited without ending
09-28 06:52:41.420  5634  5680 I jxcore-log: 
09-28 06:52:41.420  5634  5680 I jxcore-log:   ---
09-28 06:52:41.420  5634  5680 I jxcore-log: 
09-28 06:52:41.420  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.420  5634  5680 I jxcore-log: 
09-28 06:52:41.420  5634  5680 I jxcore-log:   ...
09-28 06:52:41.420  5634  5680 I jxcore-log: 
09-28 06:52:41.421  5634  5680 I jxcore-log: not ok 185 test exited without ending
09-28 06:52:41.421  5634  5680 I jxcore-log: 
09-28 06:52:41.421  5634  5680 I jxcore-log:   ---
09-28 06:52:41.421  5634  5680 I jxcore-log: 
09-28 06:52:41.421  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.421  5634  5680 I jxcore-log: 
09-28 06:52:41.421  5634  5680 I jxcore-log:   ...
09-28 06:52:41.421  5634  5680 I jxcore-log: 
09-28 06:52:41.422  5634  5680 I jxcore-log: not ok 186 test exited without ending
09-28 06:52:41.422  5634  5680 I jxcore-log: 
09-28 06:52:41.422  5634  5680 I jxcore-log:   ---
09-28 06:52:41.422  5634  5680 I jxcore-log: 
09-28 06:52:41.422  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.422  5634  5680 I jxcore-log: 
09-28 06:52:41.422  5634  5680 I jxcore-log:   ...
09-28 06:52:41.422  5634  5680 I jxcore-log: 
,09-28 06:52:41.422  5634  5680 I jxcore-log: not ok 187 test exited without ending
09-28 06:52:41.422  5634  5680 I jxcore-log: 
09-28 06:52:41.423  5634  5680 I jxcore-log:   ---
09-28 06:52:41.423  5634  5680 I jxcore-log: 
09-28 06:52:41.423  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.423  5634  5680 I jxcore-log: 
09-28 06:52:41.423  5634  5680 I jxcore-log:   ...
09-28 06:52:41.423  5634  5680 I jxcore-log: 
09-28 06:52:41.423  5634  5680 I jxcore-log: not ok 188 test exited without ending
09-28 06:52:41.423  5634  5680 I jxcore-log: 
09-28 06:52:41.423  5634  5680 I jxcore-log:   ---
09-28 06:52:41.423  5634  5680 I jxcore-log: 
,09-28 06:52:41.423  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.423  5634  5680 I jxcore-log: 
09-28 06:52:41.423  5634  5680 I jxcore-log:   ...
09-28 06:52:41.423  5634  5680 I jxcore-log: 
09-28 06:52:41.424  5634  5680 I jxcore-log: not ok 189 test exited without ending
09-28 06:52:41.424  5634  5680 I jxcore-log: 
09-28 06:52:41.424  5634  5680 I jxcore-log:   ---
09-28 06:52:41.424  5634  5680 I jxcore-log: 
09-28 06:52:41.424  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.424  5634  5680 I jxcore-log: 
09-28 06:52:41.424  5634  5680 I jxcore-log:   ...
09-28 06:52:41.424  5634  5680 I jxcore-log: 
09-28 06:52:41.425  5634  5680 I jxcore-log: not ok 190 test exited without ending
09-28 06:52:41.425  5634  5680 I jxcore-log: 
09-28 06:52:41.425  5634  5680 I jxcore-log:   ---
09-28 06:52:41.425  5634  5680 I jxcore-log: 
09-28 06:52:41.425  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.425  5634  5680 I jxcore-log: 
09-28 06:52:41.425  5634  5680 I jxcore-log:   ...
09-28 06:52:41.425  5634  5680 I jxcore-log: 
09-28 06:52:41.426  5634  5680 I jxcore-log: not ok 191 test exited without ending
09-28 06:52:41.426  5634  5680 I jxcore-log: 
,09-28 06:52:41.426  5634  5680 I jxcore-log:   ---
09-28 06:52:41.426  5634  5680 I jxcore-log: 
,09-28 06:52:41.427  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.427  5634  5680 I jxcore-log: 
09-28 06:52:41.428  5634  5680 I jxcore-log:   ...
09-28 06:52:41.428  5634  5680 I jxcore-log: 
,09-28 06:52:41.428  5634  5680 I jxcore-log: not ok 192 test exited without ending
09-28 06:52:41.428  5634  5680 I jxcore-log: 
09-28 06:52:41.428  5634  5680 I jxcore-log:   ---
09-28 06:52:41.428  5634  5680 I jxcore-log: 
09-28 06:52:41.429  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.429  5634  5680 I jxcore-log: 
09-28 06:52:41.429  5634  5680 I jxcore-log:   ...
09-28 06:52:41.429  5634  5680 I jxcore-log: 
09-28 06:52:41.429  5634  5680 I jxcore-log: not ok 193 test exited without ending
09-28 06:52:41.429  5634  5680 I jxcore-log: 
09-28 06:52:41.429  5634  5680 I jxcore-log:   ---
09-28 06:52:41.429  5634  5680 I jxcore-log: 
09-28 06:52:41.429  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.429  5634  5680 I jxcore-log: 
09-28 06:52:41.429  5634  5680 I jxcore-log:   ...
09-28 06:52:41.429  5634  5680 I jxcore-log: 
,09-28 06:52:41.431  5634  5680 I jxcore-log: not ok 194 test exited without ending
09-28 06:52:41.431  5634  5680 I jxcore-log: 
09-28 06:52:41.431  5634  5680 I jxcore-log:   ---
09-28 06:52:41.431  5634  5680 I jxcore-log: 
09-28 06:52:41.431  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.431  5634  5680 I jxcore-log: 
09-28 06:52:41.431  5634  5680 I jxcore-log:   ...
09-28 06:52:41.431  5634  5680 I jxcore-log: 
,09-28 06:52:41.432  5634  5680 I jxcore-log: not ok 195 test exited without ending
09-28 06:52:41.432  5634  5680 I jxcore-log: 
09-28 06:52:41.432  5634  5680 I jxcore-log:   ---
09-28 06:52:41.432  5634  5680 I jxcore-log: 
09-28 06:52:41.432  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.432  5634  5680 I jxcore-log: 
09-28 06:52:41.432  5634  5680 I jxcore-log:   ...
09-28 06:52:41.432  5634  5680 I jxcore-log: 
,09-28 06:52:41.437  5634  5680 I jxcore-log: not ok 196 test exited without ending
09-28 06:52:41.437  5634  5680 I jxcore-log: 
09-28 06:52:41.437  5634  5680 I jxcore-log:   ---
09-28 06:52:41.437  5634  5680 I jxcore-log: 
09-28 06:52:41.437  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.437  5634  5680 I jxcore-log: 
09-28 06:52:41.437  5634  5680 I jxcore-log:   ...
09-28 06:52:41.437  5634  5680 I jxcore-log: 
,09-28 06:52:41.438  5634  5680 I jxcore-log: not ok 197 test exited without ending
09-28 06:52:41.438  5634  5680 I jxcore-log: 
09-28 06:52:41.438  5634  5680 I jxcore-log:   ---
09-28 06:52:41.438  5634  5680 I jxcore-log: 
09-28 06:52:41.438  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.438  5634  5680 I jxcore-log: 
09-28 06:52:41.438  5634  5680 I jxcore-log:   ...
09-28 06:52:41.438  5634  5680 I jxcore-log: 
,09-28 06:52:41.439  5634  5680 I jxcore-log: not ok 198 test exited without ending
09-28 06:52:41.439  5634  5680 I jxcore-log: 
09-28 06:52:41.439  5634  5680 I jxcore-log:   ---
09-28 06:52:41.439  5634  5680 I jxcore-log: 
09-28 06:52:41.439  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.439  5634  5680 I jxcore-log: 
09-28 06:52:41.439  5634  5680 I jxcore-log:   ...
09-28 06:52:41.439  5634  5680 I jxcore-log: 
,09-28 06:52:41.440  5634  5680 I jxcore-log: not ok 199 test exited without ending
09-28 06:52:41.440  5634  5680 I jxcore-log: 
09-28 06:52:41.440  5634  5680 I jxcore-log:   ---
09-28 06:52:41.440  5634  5680 I jxcore-log: 
09-28 06:52:41.440  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.440  5634  5680 I jxcore-log: 
09-28 06:52:41.440  5634  5680 I jxcore-log:   ...
09-28 06:52:41.440  5634  5680 I jxcore-log: 
09-28 06:52:41.441  5634  5680 I jxcore-log: not ok 200 test exited without ending
09-28 06:52:41.441  5634  5680 I jxcore-log: 
09-28 06:52:41.441  5634  5680 I jxcore-log:   ---
09-28 06:52:41.441  5634  5680 I jxcore-log: 
09-28 06:52:41.441  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.441  5634  5680 I jxcore-log: 
09-28 06:52:41.441  5634  5680 I jxcore-log:   ...
09-28 06:52:41.441  5634  5680 I jxcore-log: 
,09-28 06:52:41.442  5634  5680 I jxcore-log: not ok 201 test exited without ending
09-28 06:52:41.442  5634  5680 I jxcore-log: 
09-28 06:52:41.442  5634  5680 I jxcore-log:   ---
09-28 06:52:41.442  5634  5680 I jxcore-log: 
09-28 06:52:41.442  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.442  5634  5680 I jxcore-log: 
09-28 06:52:41.442  5634  5680 I jxcore-log:   ...
09-28 06:52:41.442  5634  5680 I jxcore-log: 
09-28 06:52:41.442  5634  5680 I jxcore-log: not ok 202 test exited without ending
09-28 06:52:41.442  5634  5680 I jxcore-log: 
09-28 06:52:41.442  5634  5680 I jxcore-log:   ---
09-28 06:52:41.442  5634  5680 I jxcore-log: 
09-28 06:52:41.443  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.443  5634  5680 I jxcore-log: 
09-28 06:52:41.443  5634  5680 I jxcore-log:   ...
09-28 06:52:41.443  5634  5680 I jxcore-log: 
,09-28 06:52:41.443  5634  5680 I jxcore-log: not ok 203 test exited without ending
09-28 06:52:41.443  5634  5680 I jxcore-log: 
09-28 06:52:41.443  5634  5680 I jxcore-log:   ---
09-28 06:52:41.443  5634  5680 I jxcore-log: 
09-28 06:52:41.443  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.443  5634  5680 I jxcore-log: 
09-28 06:52:41.443  5634  5680 I jxcore-log:   ...
09-28 06:52:41.443  5634  5680 I jxcore-log: 
09-28 06:52:41.444  5634  5680 I jxcore-log: not ok 204 test exited without ending
09-28 06:52:41.444  5634  5680 I jxcore-log: 
09-28 06:52:41.444  5634  5680 I jxcore-log:   ---
09-28 06:52:41.444  5634  5680 I jxcore-log: 
09-28 06:52:41.444  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.444  5634  5680 I jxcore-log: 
09-28 06:52:41.444  5634  5680 I jxcore-log:   ...
09-28 06:52:41.444  5634  5680 I jxcore-log: 
09-28 06:52:41.445  5634  5680 I jxcore-log: not ok 205 test exited without ending
09-28 06:52:41.445  5634  5680 I jxcore-log: 
09-28 06:52:41.445  5634  5680 I jxcore-log:   ---
09-28 06:52:41.445  5634  5680 I jxcore-log: 
09-28 06:52:41.445  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.445  5634  5680 I jxcore-log: 
09-28 06:52:41.445  5634  5680 I jxcore-log:   ...
09-28 06:52:41.445  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log: not ok 206 test exited without ending
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log:   ---
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log:   ...
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log: not ok 207 test exited without ending
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log:   ---
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.446  5634  5680 I jxcore-log:   ...
09-28 06:52:41.446  5634  5680 I jxcore-log: 
09-28 06:52:41.447  5634  5680 I jxcore-log: not ok 208 test exited without ending
09-28 06:52:41.447  5634  5680 I jxcore-log: 
09-28 06:52:41.447  5634  5680 I jxcore-log:   ---
09-28 06:52:41.447  5634  5680 I jxcore-log: 
09-28 06:52:41.447  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.447  5634  5680 I jxcore-log: 
09-28 06:52:41.447  5634  5680 I jxcore-log:   ...
09-28 06:52:41.447  5634  5680 I jxcore-log: 
09-28 06:52:41.448  5634  5680 I jxcore-log: not ok 209 test exited without ending
09-28 06:52:41.448  5634  5680 I jxcore-log: 
09-28 06:52:41.448  5634  5680 I jxcore-log:   ---
09-28 06:52:41.448  5634  5680 I jxcore-log: 
09-28 06:52:41.448  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.448  5634  5680 I jxcore-log: 
09-28 06:52:41.448  5634  5680 I jxcore-log:   ...
09-28 06:52:41.448  5634  5680 I jxcore-log: 
09-28 06:52:41.449  5634  5680 I jxcore-log: not ok 210 test exited without ending
09-28 06:52:41.449  5634  5680 I jxcore-log: 
09-28 06:52:41.449  5634  5680 I jxcore-log:   ---
09-28 06:52:41.449  5634  5680 I jxcore-log: 
09-28 06:52:41.449  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.449  5634  5680 I jxcore-log: 
09-28 06:52:41.449  5634  5680 I jxcore-log:   ...
09-28 06:52:41.449  5634  5680 I jxcore-log: 
09-28 06:52:41.449  5634  5680 I jxcore-log: not ok 211 test exited without ending
09-28 06:52:41.449  5634  5680 I jxcore-log: 
09-28 06:52:41.449  5634  5680 I jxcore-log:   ---
09-28 06:52:41.449  5634  5680 I jxcore-log: 
09-28 06:52:41.450  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.450  5634  5680 I jxcore-log: 
09-28 06:52:41.450  5634  5680 I jxcore-log:   ...
09-28 06:52:41.450  5634  5680 I jxcore-log: 
09-28 06:52:41.450  5634  5680 I jxcore-log: not ok 212 test exited without ending
09-28 06:52:41.450  5634  5680 I jxcore-log: 
09-28 06:52:41.450  5634  5680 I jxcore-log:   ---
09-28 06:52:41.450  5634  5680 I jxcore-log: 
09-28 06:52:41.450  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.450  5634  5680 I jxcore-log: 
09-28 06:52:41.450  5634  5680 I jxcore-log:   ...
09-28 06:52:41.450  5634  5680 I jxcore-log: 
09-28 06:52:41.451  5634  5680 I jxcore-log: not ok 213 test exited without ending
09-28 06:52:41.451  5634  5680 I jxcore-log: 
09-28 06:52:41.451  5634  5680 I jxcore-log:   ---
09-28 06:52:41.451  5634  5680 I jxcore-log: 
09-28 06:52:41.451  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.451  5634  5680 I jxcore-log: 
09-28 06:52:41.451  5634  5680 I jxcore-log:   ...
09-28 06:52:41.451  5634  5680 I jxcore-log: 
09-28 06:52:41.452  5634  5680 I jxcore-log: not ok 214 test exited without ending
09-28 06:52:41.452  5634  5680 I jxcore-log: 
09-28 06:52:41.452  5634  5680 I jxcore-log:   ---
09-28 06:52:41.452  5634  5680 I jxcore-log: 
09-28 06:52:41.452  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.452  5634  5680 I jxcore-log: 
09-28 06:52:41.452  5634  5680 I jxcore-log:   ...
09-28 06:52:41.452  5634  5680 I jxcore-log: 
09-28 06:52:41.453  5634  5680 I jxcore-log: not ok 215 test exited without ending
09-28 06:52:41.453  5634  5680 I jxcore-log: 
09-28 06:52:41.453  5634  5680 I jxcore-log:   ---
09-28 06:52:41.453  5634  5680 I jxcore-log: 
09-28 06:52:41.454  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.454  5634  5680 I jxcore-log: 
09-28 06:52:41.454  5634  5680 I jxcore-log:   ...
09-28 06:52:41.454  5634  5680 I jxcore-log: 
09-28 06:52:41.454  5634  5680 I jxcore-log: not ok 216 test exited without ending
09-28 06:52:41.454  5634  5680 I jxcore-log: 
09-28 06:52:41.454  5634  5680 I jxcore-log:   ---
09-28 06:52:41.454  5634  5680 I jxcore-log: 
09-28 06:52:41.454  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.454  5634  5680 I jxcore-log: 
09-28 06:52:41.454  5634  5680 I jxcore-log:   ...
09-28 06:52:41.454  5634  5680 I jxcore-log: 
09-28 06:52:41.455  5634  5680 I jxcore-log: not ok 217 test exited without ending
09-28 06:52:41.455  5634  5680 I jxcore-log: 
09-28 06:52:41.455  5634  5680 I jxcore-log:   ---
09-28 06:52:41.455  5634  5680 I jxcore-log: 
09-28 06:52:41.455  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.455  5634  5680 I jxcore-log: 
09-28 06:52:41.455  5634  5680 I jxcore-log:   ...
09-28 06:52:41.455  5634  5680 I jxcore-log: 
09-28 06:52:41.456  5634  5680 I jxcore-log: not ok 218 test exited without ending
09-28 06:52:41.456  5634  5680 I jxcore-log: 
09-28 06:52:41.456  5634  5680 I jxcore-log:   ---
09-28 06:52:41.456  5634  5680 I jxcore-log: 
09-28 06:52:41.456  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.456  5634  5680 I jxcore-log: 
09-28 06:52:41.456  5634  5680 I jxcore-log:   ...
09-28 06:52:41.456  5634  5680 I jxcore-log: 
09-28 06:52:41.457  5634  5680 I jxcore-log: not ok 219 test exited without ending
09-28 06:52:41.457  5634  5680 I jxcore-log: 
09-28 06:52:41.457  5634  5680 I jxcore-log:   ---
09-28 06:52:41.457  5634  5680 I jxcore-log: 
09-28 06:52:41.457  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.457  5634  5680 I jxcore-log: 
09-28 06:52:41.457  5634  5680 I jxcore-log:   ...
09-28 06:52:41.457  5634  5680 I jxcore-log: 
09-28 06:52:41.457  5634  5680 I jxcore-log: not ok 220 test exited without ending
09-28 06:52:41.457  5634  5680 I jxcore-log: 
09-28 06:52:41.458  5634  5680 I jxcore-log:   ---
09-28 06:52:41.458  5634  5680 I jxcore-log: 
09-28 06:52:41.458  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.458  5634  5680 I jxcore-log: 
09-28 06:52:41.458  5634  5680 I jxcore-log:   ...
09-28 06:52:41.458  5634  5680 I jxcore-log: 
09-28 06:52:41.458  5634  5680 I jxcore-log: not ok 221 test exited without ending
09-28 06:52:41.458  5634  5680 I jxcore-log: 
09-28 06:52:41.458  5634  5680 I jxcore-log:   ---
09-28 06:52:41.458  5634  5680 I jxcore-log: 
09-28 06:52:41.458  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.458  5634  5680 I jxcore-log: 
09-28 06:52:41.458  5634  5680 I jxcore-log:   ...
09-28 06:52:41.458  5634  5680 I jxcore-log: 
09-28 06:52:41.459  5634  5680 I jxcore-log: not ok 222 test exited without ending
09-28 06:52:41.459  5634  5680 I jxcore-log: 
09-28 06:52:41.459  5634  5680 I jxcore-log:   ---
09-28 06:52:41.459  5634  5680 I jxcore-log: 
09-28 06:52:41.459  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.459  5634  5680 I jxcore-log: 
09-28 06:52:41.459  5634  5680 I jxcore-log:   ...
09-28 06:52:41.459  5634  5680 I jxcore-log: 
09-28 06:52:41.460  5634  5680 I jxcore-log: not ok 223 test exited without ending
09-28 06:52:41.460  5634  5680 I jxcore-log: 
09-28 06:52:41.460  5634  5680 I jxcore-log:   ---
09-28 06:52:41.460  5634  5680 I jxcore-log: 
09-28 06:52:41.460  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.460  5634  5680 I jxcore-log: 
09-28 06:52:41.460  5634  5680 I jxcore-log:   ...
09-28 06:52:41.460  5634  5680 I jxcore-log: 
09-28 06:52:41.461  5634  5680 I jxcore-log: not ok 224 test exited without ending
09-28 06:52:41.461  5634  5680 I jxcore-log: 
09-28 06:52:41.461  5634  5680 I jxcore-log:   ---
09-28 06:52:41.461  5634  5680 I jxcore-log: 
09-28 06:52:41.461  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.461  5634  5680 I jxcore-log: 
09-28 06:52:41.461  5634  5680 I jxcore-log:   ...
09-28 06:52:41.461  5634  5680 I jxcore-log: 
09-28 06:52:41.462  5634  5680 I jxcore-log: not ok 225 test exited without ending
09-28 06:52:41.462  5634  5680 I jxcore-log: 
09-28 06:52:41.462  5634  5680 I jxcore-log:   ---
09-28 06:52:41.462  5634  5680 I jxcore-log: 
09-28 06:52:41.462  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.462  5634  5680 I jxcore-log: 
09-28 06:52:41.462  5634  5680 I jxcore-log:   ...
09-28 06:52:41.462  5634  5680 I jxcore-log: 
09-28 06:52:41.462  5634  5680 I jxcore-log: not ok 226 test exited without ending
09-28 06:52:41.462  5634  5680 I jxcore-log: 
09-28 06:52:41.463  5634  5680 I jxcore-log:   ---
09-28 06:52:41.463  5634  5680 I jxcore-log: 
09-28 06:52:41.463  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.463  5634  5680 I jxcore-log: 
09-28 06:52:41.463  5634  5680 I jxcore-log:   ...
09-28 06:52:41.463  5634  5680 I jxcore-log: 
09-28 06:52:41.463  5634  5680 I jxcore-log: not ok 227 test exited without ending
09-28 06:52:41.463  5634  5680 I jxcore-log: 
09-28 06:52:41.463  5634  5680 I jxcore-log:   ---
09-28 06:52:41.463  5634  5680 I jxcore-log: 
09-28 06:52:41.463  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.463  5634  5680 I jxcore-log: 
09-28 06:52:41.463  5634  5680 I jxcore-log:   ...
09-28 06:52:41.463  5634  5680 I jxcore-log: 
09-28 06:52:41.464  5634  5680 I jxcore-log: not ok 228 test exited without ending
09-28 06:52:41.464  5634  5680 I jxcore-log: 
09-28 06:52:41.464  5634  5680 I jxcore-log:   ---
09-28 06:52:41.464  5634  5680 I jxcore-log: 
09-28 06:52:41.464  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.464  5634  5680 I jxcore-log: 
09-28 06:52:41.464  5634  5680 I jxcore-log:   ...
09-28 06:52:41.464  5634  5680 I jxcore-log: 
09-28 06:52:41.465  5634  5680 I jxcore-log: not ok 229 test exited without ending
09-28 06:52:41.465  5634  5680 I jxcore-log: 
09-28 06:52:41.465  5634  5680 I jxcore-log:   ---
09-28 06:52:41.465  5634  5680 I jxcore-log: 
09-28 06:52:41.465  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.465  5634  5680 I jxcore-log: 
09-28 06:52:41.465  5634  5680 I jxcore-log:   ...
09-28 06:52:41.465  5634  5680 I jxcore-log: 
09-28 06:52:41.466  5634  5680 I jxcore-log: not ok 230 test exited without ending
09-28 06:52:41.466  5634  5680 I jxcore-log: 
09-28 06:52:41.466  5634  5680 I jxcore-log:   ---
09-28 06:52:41.466  5634  5680 I jxcore-log: 
09-28 06:52:41.466  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.466  5634  5680 I jxcore-log: 
09-28 06:52:41.466  5634  5680 I jxcore-log:   ...
09-28 06:52:41.466  5634  5680 I jxcore-log: 
09-28 06:52:41.466  5634  5680 I jxcore-log: not ok 231 test exited without ending
09-28 06:52:41.466  5634  5680 I jxcore-log: 
09-28 06:52:41.466  5634  5680 I jxcore-log:   ---
09-28 06:52:41.466  5634  5680 I jxcore-log: 
09-28 06:52:41.466  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.466  5634  5680 I jxcore-log: 
09-28 06:52:41.467  5634  5680 I jxcore-log:   ...
09-28 06:52:41.467  5634  5680 I jxcore-log: 
09-28 06:52:41.467  5634  5680 I jxcore-log: not ok 232 test exited without ending
09-28 06:52:41.467  5634  5680 I jxcore-log: 
09-28 06:52:41.467  5634  5680 I jxcore-log:   ---
09-28 06:52:41.467  5634  5680 I jxcore-log: 
09-28 06:52:41.467  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.467  5634  5680 I jxcore-log: 
09-28 06:52:41.467  5634  5680 I jxcore-log:   ...
09-28 06:52:41.467  5634  5680 I jxcore-log: 
09-28 06:52:41.468  5634  5680 I jxcore-log: not ok 233 test exited without ending
09-28 06:52:41.468  5634  5680 I jxcore-log: 
09-28 06:52:41.468  5634  5680 I jxcore-log:   ---
09-28 06:52:41.468  5634  5680 I jxcore-log: 
09-28 06:52:41.468  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.468  5634  5680 I jxcore-log: 
09-28 06:52:41.468  5634  5680 I jxcore-log:   ...
09-28 06:52:41.468  5634  5680 I jxcore-log: 
09-28 06:52:41.469  5634  5680 I jxcore-log: not ok 234 test exited without ending
09-28 06:52:41.469  5634  5680 I jxcore-log: 
09-28 06:52:41.469  5634  5680 I jxcore-log:   ---
09-28 06:52:41.469  5634  5680 I jxcore-log: 
09-28 06:52:41.469  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.469  5634  5680 I jxcore-log: 
09-28 06:52:41.469  5634  5680 I jxcore-log:   ...
09-28 06:52:41.469  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log: not ok 235 test exited without ending
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log:   ---
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log:   ...
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log: not ok 236 test exited without ending
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log:   ---
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.470  5634  5680 I jxcore-log:   ...
09-28 06:52:41.470  5634  5680 I jxcore-log: 
09-28 06:52:41.471  5634  5680 I jxcore-log: not ok 237 test exited without ending
09-28 06:52:41.471  5634  5680 I jxcore-log: 
09-28 06:52:41.471  5634  5680 I jxcore-log:   ---
09-28 06:52:41.471  5634  5680 I jxcore-log: 
09-28 06:52:41.471  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.471  5634  5680 I jxcore-log: 
09-28 06:52:41.471  5634  5680 I jxcore-log:   ...
09-28 06:52:41.471  5634  5680 I jxcore-log: 
,09-28 06:52:41.472  5634  5680 I jxcore-log: not ok 238 test exited without ending
09-28 06:52:41.472  5634  5680 I jxcore-log: 
09-28 06:52:41.472  5634  5680 I jxcore-log:   ---
09-28 06:52:41.472  5634  5680 I jxcore-log: 
09-28 06:52:41.472  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.472  5634  5680 I jxcore-log: 
09-28 06:52:41.472  5634  5680 I jxcore-log:   ...
09-28 06:52:41.472  5634  5680 I jxcore-log: 
09-28 06:52:41.473  5634  5680 I jxcore-log: not ok 239 test exited without ending
09-28 06:52:41.473  5634  5680 I jxcore-log: 
09-28 06:52:41.473  5634  5680 I jxcore-log:   ---
09-28 06:52:41.473  5634  5680 I jxcore-log: 
09-28 06:52:41.473  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.473  5634  5680 I jxcore-log: 
09-28 06:52:41.473  5634  5680 I jxcore-log:   ...
09-28 06:52:41.473  5634  5680 I jxcore-log: 
09-28 06:52:41.474  5634  5680 I jxcore-log: not ok 240 test exited without ending
09-28 06:52:41.474  5634  5680 I jxcore-log: 
09-28 06:52:41.474  5634  5680 I jxcore-log:   ---
09-28 06:52:41.474  5634  5680 I jxcore-log: 
09-28 06:52:41.474  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.474  5634  5680 I jxcore-log: 
09-28 06:52:41.474  5634  5680 I jxcore-log:   ...
09-28 06:52:41.474  5634  5680 I jxcore-log: 
09-28 06:52:41.474  5634  5680 I jxcore-log: not ok 241 test exited without ending
09-28 06:52:41.474  5634  5680 I jxcore-log: 
09-28 06:52:41.475  5634  5680 I jxcore-log:   ---
09-28 06:52:41.475  5634  5680 I jxcore-log: 
09-28 06:52:41.475  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.475  5634  5680 I jxcore-log: 
09-28 06:52:41.475  5634  5680 I jxcore-log:   ...
09-28 06:52:41.475  5634  5680 I jxcore-log: 
09-28 06:52:41.475  5634  5680 I jxcore-log: not ok 242 test exited without ending
09-28 06:52:41.475  5634  5680 I jxcore-log: 
09-28 06:52:41.475  5634  5680 I jxcore-log:   ---
09-28 06:52:41.475  5634  5680 I jxcore-log: 
09-28 06:52:41.475  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.475  5634  5680 I jxcore-log: 
09-28 06:52:41.475  5634  5680 I jxcore-log:   ...
09-28 06:52:41.475  5634  5680 I jxcore-log: 
09-28 06:52:41.476  5634  5680 I jxcore-log: not ok 243 test exited without ending
09-28 06:52:41.476  5634  5680 I jxcore-log: 
09-28 06:52:41.476  5634  5680 I jxcore-log:   ---
09-28 06:52:41.476  5634  5680 I jxcore-log: 
09-28 06:52:41.476  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.476  5634  5680 I jxcore-log: 
09-28 06:52:41.476  5634  5680 I jxcore-log:   ...
09-28 06:52:41.476  5634  5680 I jxcore-log: 
09-28 06:52:41.477  5634  5680 I jxcore-log: not ok 244 test exited without ending
09-28 06:52:41.477  5634  5680 I jxcore-log: 
09-28 06:52:41.477  5634  5680 I jxcore-log:   ---
09-28 06:52:41.477  5634  5680 I jxcore-log: 
09-28 06:52:41.477  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.477  5634  5680 I jxcore-log: 
09-28 06:52:41.478  5634  5680 I jxcore-log:   ...
09-28 06:52:41.478  5634  5680 I jxcore-log: 
09-28 06:52:41.478  5634  5680 I jxcore-log: not ok 245 test exited without ending
09-28 06:52:41.478  5634  5680 I jxcore-log: 
09-28 06:52:41.478  5634  5680 I jxcore-log:   ---
09-28 06:52:41.478  5634  5680 I jxcore-log: 
09-28 06:52:41.478  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.478  5634  5680 I jxcore-log: 
09-28 06:52:41.478  5634  5680 I jxcore-log:   ...
09-28 06:52:41.478  5634  5680 I jxcore-log: 
09-28 06:52:41.479  5634  5680 I jxcore-log: not ok 246 test exited without ending
09-28 06:52:41.479  5634  5680 I jxcore-log: 
09-28 06:52:41.479  5634  5680 I jxcore-log:   ---
09-28 06:52:41.479  5634  5680 I jxcore-log: 
09-28 06:52:41.479  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.479  5634  5680 I jxcore-log: 
09-28 06:52:41.479  5634  5680 I jxcore-log:   ...
09-28 06:52:41.479  5634  5680 I jxcore-log: 
09-28 06:52:41.483  5634  5680 I jxcore-log: not ok 247 test exited without ending
09-28 06:52:41.483  5634  5680 I jxcore-log: 
09-28 06:52:41.483  5634  5680 I jxcore-log:   ---
09-28 06:52:41.483  5634  5680 I jxcore-log: 
09-28 06:52:41.483  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.483  5634  5680 I jxcore-log: 
09-28 06:52:41.484  5634  5680 I jxcore-log:   ...
09-28 06:52:41.484  5634  5680 I jxcore-log: 
09-28 06:52:41.484  5634  5680 I jxcore-log: not ok 248 test exited without ending
09-28 06:52:41.484  5634  5680 I jxcore-log: 
09-28 06:52:41.484  5634  5680 I jxcore-log:   ---
09-28 06:52:41.484  5634  5680 I jxcore-log: 
09-28 06:52:41.485  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.485  5634  5680 I jxcore-log: 
09-28 06:52:41.485  5634  5680 I jxcore-log:   ...
09-28 06:52:41.485  5634  5680 I jxcore-log: 
09-28 06:52:41.485  5634  5680 I jxcore-log: not ok 249 test exited without ending
09-28 06:52:41.485  5634  5680 I jxcore-log: 
09-28 06:52:41.485  5634  5680 I jxcore-log:   ---
09-28 06:52:41.485  5634  5680 I jxcore-log: 
09-28 06:52:41.485  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.485  5634  5680 I jxcore-log: 
09-28 06:52:41.485  5634  5680 I jxcore-log:   ...
09-28 06:52:41.485  5634  5680 I jxcore-log: 
09-28 06:52:41.486  5634  5680 I jxcore-log: not ok 250 test exited without ending
09-28 06:52:41.486  5634  5680 I jxcore-log: 
09-28 06:52:41.486  5634  5680 I jxcore-log:   ---
09-28 06:52:41.486  5634  5680 I jxcore-log: 
09-28 06:52:41.486  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.486  5634  5680 I jxcore-log: 
09-28 06:52:41.486  5634  5680 I jxcore-log:   ...
09-28 06:52:41.486  5634  5680 I jxcore-log: 
09-28 06:52:41.487  5634  5680 I jxcore-log: not ok 251 test exited without ending
09-28 06:52:41.487  5634  5680 I jxcore-log: 
09-28 06:52:41.487  5634  5680 I jxcore-log:   ---
09-28 06:52:41.487  5634  5680 I jxcore-log: 
09-28 06:52:41.487  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.487  5634  5680 I jxcore-log: 
09-28 06:52:41.487  5634  5680 I jxcore-log:   ...
09-28 06:52:41.487  5634  5680 I jxcore-log: 
09-28 06:52:41.488  5634  5680 I jxcore-log: not ok 252 test exited without ending
09-28 06:52:41.488  5634  5680 I jxcore-log: 
09-28 06:52:41.488  5634  5680 I jxcore-log:   ---
09-28 06:52:41.488  5634  5680 I jxcore-log: 
09-28 06:52:41.488  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.488  5634  5680 I jxcore-log: 
09-28 06:52:41.488  5634  5680 I jxcore-log:   ...
09-28 06:52:41.488  5634  5680 I jxcore-log: 
09-28 06:52:41.488  5634  5680 I jxcore-log: not ok 253 test exited without ending
09-28 06:52:41.488  5634  5680 I jxcore-log: 
09-28 06:52:41.488  5634  5680 I jxcore-log:   ---
09-28 06:52:41.488  5634  5680 I jxcore-log: 
09-28 06:52:41.488  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.488  5634  5680 I jxcore-log: 
09-28 06:52:41.489  5634  5680 I jxcore-log:   ...
09-28 06:52:41.489  5634  5680 I jxcore-log: 
09-28 06:52:41.489  5634  5680 I jxcore-log: not ok 254 test exited without ending
09-28 06:52:41.489  5634  5680 I jxcore-log: 
09-28 06:52:41.489  5634  5680 I jxcore-log:   ---
09-28 06:52:41.489  5634  5680 I jxcore-log: 
09-28 06:52:41.489  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.489  5634  5680 I jxcore-log: 
09-28 06:52:41.489  5634  5680 I jxcore-log:   ...
09-28 06:52:41.489  5634  5680 I jxcore-log: 
09-28 06:52:41.490  5634  5680 I jxcore-log: not ok 255 test exited without ending
09-28 06:52:41.490  5634  5680 I jxcore-log: 
09-28 06:52:41.490  5634  5680 I jxcore-log:   ---
09-28 06:52:41.490  5634  5680 I jxcore-log: 
09-28 06:52:41.490  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.490  5634  5680 I jxcore-log: 
09-28 06:52:41.490  5634  5680 I jxcore-log:   ...
09-28 06:52:41.490  5634  5680 I jxcore-log: 
09-28 06:52:41.491  5634  5680 I jxcore-log: not ok 256 test exited without ending
09-28 06:52:41.491  5634  5680 I jxcore-log: 
09-28 06:52:41.491  5634  5680 I jxcore-log:   ---
09-28 06:52:41.491  5634  5680 I jxcore-log: 
09-28 06:52:41.491  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.491  5634  5680 I jxcore-log: 
09-28 06:52:41.491  5634  5680 I jxcore-log:   ...
09-28 06:52:41.491  5634  5680 I jxcore-log: 
09-28 06:52:41.492  5634  5680 I jxcore-log: not ok 257 test exited without ending
09-28 06:52:41.492  5634  5680 I jxcore-log: 
09-28 06:52:41.492  5634  5680 I jxcore-log:   ---
09-28 06:52:41.492  5634  5680 I jxcore-log: 
09-28 06:52:41.492  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.492  5634  5680 I jxcore-log: 
09-28 06:52:41.492  5634  5680 I jxcore-log:   ...
09-28 06:52:41.492  5634  5680 I jxcore-log: 
09-28 06:52:41.492  5634  5680 I jxcore-log: not ok 258 test exited without ending
09-28 06:52:41.492  5634  5680 I jxcore-log: 
09-28 06:52:41.492  5634  5680 I jxcore-log:   ---
09-28 06:52:41.492  5634  5680 I jxcore-log: 
09-28 06:52:41.492  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.492  5634  5680 I jxcore-log: 
09-28 06:52:41.493  5634  5680 I jxcore-log:   ...
09-28 06:52:41.493  5634  5680 I jxcore-log: 
09-28 06:52:41.493  5634  5680 I jxcore-log: not ok 259 test exited without ending
09-28 06:52:41.493  5634  5680 I jxcore-log: 
09-28 06:52:41.493  5634  5680 I jxcore-log:   ---
09-28 06:52:41.493  5634  5680 I jxcore-log: 
09-28 06:52:41.493  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.493  5634  5680 I jxcore-log: 
09-28 06:52:41.493  5634  5680 I jxcore-log:   ...
09-28 06:52:41.493  5634  5680 I jxcore-log: 
09-28 06:52:41.494  5634  5680 I jxcore-log: not ok 260 test exited without ending
09-28 06:52:41.494  5634  5680 I jxcore-log: 
09-28 06:52:41.494  5634  5680 I jxcore-log:   ---
09-28 06:52:41.494  5634  5680 I jxcore-log: 
09-28 06:52:41.494  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.494  5634  5680 I jxcore-log: 
09-28 06:52:41.494  5634  5680 I jxcore-log:   ...
09-28 06:52:41.494  5634  5680 I jxcore-log: 
09-28 06:52:41.495  5634  5680 I jxcore-log: not ok 261 test exited without ending
09-28 06:52:41.495  5634  5680 I jxcore-log: 
09-28 06:52:41.495  5634  5680 I jxcore-log:   ---
09-28 06:52:41.495  5634  5680 I jxcore-log: 
09-28 06:52:41.495  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.495  5634  5680 I jxcore-log: 
09-28 06:52:41.495  5634  5680 I jxcore-log:   ...
09-28 06:52:41.495  5634  5680 I jxcore-log: 
09-28 06:52:41.496  5634  5680 I jxcore-log: not ok 262 test exited without ending
09-28 06:52:41.496  5634  5680 I jxcore-log: 
09-28 06:52:41.496  5634  5680 I jxcore-log:   ---
09-28 06:52:41.496  5634  5680 I jxcore-log: 
09-28 06:52:41.496  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.496  5634  5680 I jxcore-log: 
09-28 06:52:41.496  5634  5680 I jxcore-log:   ...
09-28 06:52:41.496  5634  5680 I jxcore-log: 
09-28 06:52:41.496  5634  5680 I jxcore-log: not ok 263 test exited without ending
09-28 06:52:41.496  5634  5680 I jxcore-log: 
09-28 06:52:41.496  5634  5680 I jxcore-log:   ---
09-28 06:52:41.496  5634  5680 I jxcore-log: 
09-28 06:52:41.496  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.496  5634  5680 I jxcore-log: 
09-28 06:52:41.497  5634  5680 I jxcore-log:   ...
09-28 06:52:41.497  5634  5680 I jxcore-log: 
09-28 06:52:41.497  5634  5680 I jxcore-log: not ok 264 test exited without ending
09-28 06:52:41.497  5634  5680 I jxcore-log: 
09-28 06:52:41.497  5634  5680 I jxcore-log:   ---
09-28 06:52:41.497  5634  5680 I jxcore-log: 
09-28 06:52:41.497  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.497  5634  5680 I jxcore-log: 
09-28 06:52:41.497  5634  5680 I jxcore-log:   ...
09-28 06:52:41.497  5634  5680 I jxcore-log: 
09-28 06:52:41.498  5634  5680 I jxcore-log: not ok 265 test exited without ending
09-28 06:52:41.498  5634  5680 I jxcore-log: 
09-28 06:52:41.498  5634  5680 I jxcore-log:   ---
09-28 06:52:41.498  5634  5680 I jxcore-log: 
09-28 06:52:41.498  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.498  5634  5680 I jxcore-log: 
09-28 06:52:41.498  5634  5680 I jxcore-log:   ...
09-28 06:52:41.498  5634  5680 I jxcore-log: 
09-28 06:52:41.499  5634  5680 I jxcore-log: not ok 266 test exited without ending
09-28 06:52:41.499  5634  5680 I jxcore-log: 
09-28 06:52:41.499  5634  5680 I jxcore-log:   ---
09-28 06:52:41.499  5634  5680 I jxcore-log: 
09-28 06:52:41.499  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.499  5634  5680 I jxcore-log: 
09-28 06:52:41.499  5634  5680 I jxcore-log:   ...
09-28 06:52:41.499  5634  5680 I jxcore-log: 
09-28 06:52:41.499  5634  5680 I jxcore-log: not ok 267 test exited without ending
09-28 06:52:41.499  5634  5680 I jxcore-log: 
09-28 06:52:41.500  5634  5680 I jxcore-log:   ---
09-28 06:52:41.500  5634  5680 I jxcore-log: 
09-28 06:52:41.500  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.500  5634  5680 I jxcore-log: 
09-28 06:52:41.500  5634  5680 I jxcore-log:   ...
09-28 06:52:41.500  5634  5680 I jxcore-log: 
09-28 06:52:41.500  5634  5680 I jxcore-log: not ok 268 test exited without ending
09-28 06:52:41.500  5634  5680 I jxcore-log: 
09-28 06:52:41.500  5634  5680 I jxcore-log:   ---
09-28 06:52:41.500  5634  5680 I jxcore-log: 
09-28 06:52:41.500  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.500  5634  5680 I jxcore-log: 
09-28 06:52:41.500  5634  5680 I jxcore-log:   ...
09-28 06:52:41.500  5634  5680 I jxcore-log: 
09-28 06:52:41.501  5634  5680 I jxcore-log: not ok 269 test exited without ending
09-28 06:52:41.501  5634  5680 I jxcore-log: 
09-28 06:52:41.501  5634  5680 I jxcore-log:   ---
09-28 06:52:41.501  5634  5680 I jxcore-log: 
09-28 06:52:41.501  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.501  5634  5680 I jxcore-log: 
09-28 06:52:41.501  5634  5680 I jxcore-log:   ...
09-28 06:52:41.501  5634  5680 I jxcore-log: 
09-28 06:52:41.502  5634  5680 I jxcore-log: not ok 270 test exited without ending
09-28 06:52:41.502  5634  5680 I jxcore-log: 
09-28 06:52:41.502  5634  5680 I jxcore-log:   ---
09-28 06:52:41.502  5634  5680 I jxcore-log: 
09-28 06:52:41.502  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.502  5634  5680 I jxcore-log: 
09-28 06:52:41.502  5634  5680 I jxcore-log:   ...
09-28 06:52:41.502  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log: not ok 271 test exited without ending
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log:   ---
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log:   ...
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log: not ok 272 test exited without ending
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log:   ---
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.503  5634  5680 I jxcore-log:   ...
09-28 06:52:41.503  5634  5680 I jxcore-log: 
09-28 06:52:41.504  5634  5680 I jxcore-log: not ok 273 test exited without ending
09-28 06:52:41.504  5634  5680 I jxcore-log: 
09-28 06:52:41.504  5634  5680 I jxcore-log:   ---
09-28 06:52:41.504  5634  5680 I jxcore-log: 
09-28 06:52:41.504  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.504  5634  5680 I jxcore-log: 
09-28 06:52:41.504  5634  5680 I jxcore-log:   ...
09-28 06:52:41.504  5634  5680 I jxcore-log: 
09-28 06:52:41.505  5634  5680 I jxcore-log: not ok 274 test exited without ending
09-28 06:52:41.505  5634  5680 I jxcore-log: 
09-28 06:52:41.505  5634  5680 I jxcore-log:   ---
09-28 06:52:41.505  5634  5680 I jxcore-log: 
09-28 06:52:41.505  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.505  5634  5680 I jxcore-log: 
09-28 06:52:41.505  5634  5680 I jxcore-log:   ...
09-28 06:52:41.505  5634  5680 I jxcore-log: 
09-28 06:52:41.506  5634  5680 I jxcore-log: not ok 275 test exited without ending
09-28 06:52:41.506  5634  5680 I jxcore-log: 
09-28 06:52:41.506  5634  5680 I jxcore-log:   ---
09-28 06:52:41.506  5634  5680 I jxcore-log: 
09-28 06:52:41.506  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.506  5634  5680 I jxcore-log: 
09-28 06:52:41.506  5634  5680 I jxcore-log:   ...
09-28 06:52:41.506  5634  5680 I jxcore-log: 
09-28 06:52:41.507  5634  5680 I jxcore-log: not ok 276 test exited without ending
09-28 06:52:41.507  5634  5680 I jxcore-log: 
09-28 06:52:41.507  5634  5680 I jxcore-log:   ---
09-28 06:52:41.507  5634  5680 I jxcore-log: 
09-28 06:52:41.507  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.507  5634  5680 I jxcore-log: 
09-28 06:52:41.507  5634  5680 I jxcore-log:   ...
09-28 06:52:41.507  5634  5680 I jxcore-log: 
09-28 06:52:41.507  5634  5680 I jxcore-log: not ok 277 test exited without ending
09-28 06:52:41.507  5634  5680 I jxcore-log: 
09-28 06:52:41.507  5634  5680 I jxcore-log:   ---
09-28 06:52:41.507  5634  5680 I jxcore-log: 
09-28 06:52:41.507  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.507  5634  5680 I jxcore-log: 
09-28 06:52:41.508  5634  5680 I jxcore-log:   ...
09-28 06:52:41.508  5634  5680 I jxcore-log: 
09-28 06:52:41.508  5634  5680 I jxcore-log: not ok 278 test exited without ending
09-28 06:52:41.508  5634  5680 I jxcore-log: 
09-28 06:52:41.508  5634  5680 I jxcore-log:   ---
09-28 06:52:41.508  5634  5680 I jxcore-log: 
09-28 06:52:41.508  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.508  5634  5680 I jxcore-log: 
09-28 06:52:41.508  5634  5680 I jxcore-log:   ...
09-28 06:52:41.508  5634  5680 I jxcore-log: 
09-28 06:52:41.509  5634  5680 I jxcore-log: not ok 279 test exited without ending
09-28 06:52:41.509  5634  5680 I jxcore-log: 
09-28 06:52:41.509  5634  5680 I jxcore-log:   ---
09-28 06:52:41.509  5634  5680 I jxcore-log: 
09-28 06:52:41.509  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.509  5634  5680 I jxcore-log: 
09-28 06:52:41.509  5634  5680 I jxcore-log:   ...
09-28 06:52:41.509  5634  5680 I jxcore-log: 
09-28 06:52:41.510  5634  5680 I jxcore-log: not ok 280 test exited without ending
09-28 06:52:41.510  5634  5680 I jxcore-log: 
09-28 06:52:41.510  5634  5680 I jxcore-log:   ---
09-28 06:52:41.510  5634  5680 I jxcore-log: 
09-28 06:52:41.510  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.510  5634  5680 I jxcore-log: 
09-28 06:52:41.510  5634  5680 I jxcore-log:   ...
09-28 06:52:41.510  5634  5680 I jxcore-log: 
09-28 06:52:41.510  5634  5680 I jxcore-log: not ok 281 test exited without ending
09-28 06:52:41.510  5634  5680 I jxcore-log: 
09-28 06:52:41.511  5634  5680 I jxcore-log:   ---
09-28 06:52:41.511  5634  5680 I jxcore-log: 
09-28 06:52:41.511  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.511  5634  5680 I jxcore-log: 
09-28 06:52:41.511  5634  5680 I jxcore-log:   ...
09-28 06:52:41.511  5634  5680 I jxcore-log: 
09-28 06:52:41.511  5634  5680 I jxcore-log: not ok 282 test exited without ending
09-28 06:52:41.511  5634  5680 I jxcore-log: 
09-28 06:52:41.511  5634  5680 I jxcore-log:   ---
09-28 06:52:41.511  5634  5680 I jxcore-log: 
09-28 06:52:41.511  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.511  5634  5680 I jxcore-log: 
09-28 06:52:41.511  5634  5680 I jxcore-log:   ...
09-28 06:52:41.511  5634  5680 I jxcore-log: 
09-28 06:52:41.512  5634  5680 I jxcore-log: not ok 283 test exited without ending
09-28 06:52:41.512  5634  5680 I jxcore-log: 
09-28 06:52:41.512  5634  5680 I jxcore-log:   ---
09-28 06:52:41.512  5634  5680 I jxcore-log: 
09-28 06:52:41.512  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.512  5634  5680 I jxcore-log: 
,09-28 06:52:41.512  5634  5680 I jxcore-log:   ...
09-28 06:52:41.512  5634  5680 I jxcore-log: 
09-28 06:52:41.513  5634  5680 I jxcore-log: not ok 284 test exited without ending
09-28 06:52:41.513  5634  5680 I jxcore-log: 
09-28 06:52:41.513  5634  5680 I jxcore-log:   ---
09-28 06:52:41.513  5634  5680 I jxcore-log: 
09-28 06:52:41.513  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.513  5634  5680 I jxcore-log: 
09-28 06:52:41.513  5634  5680 I jxcore-log:   ...
09-28 06:52:41.513  5634  5680 I jxcore-log: 
09-28 06:52:41.514  5634  5680 I jxcore-log: not ok 285 test exited without ending
09-28 06:52:41.514  5634  5680 I jxcore-log: 
09-28 06:52:41.514  5634  5680 I jxcore-log:   ---
09-28 06:52:41.514  5634  5680 I jxcore-log: 
09-28 06:52:41.514  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.514  5634  5680 I jxcore-log: 
09-28 06:52:41.514  5634  5680 I jxcore-log:   ...
09-28 06:52:41.514  5634  5680 I jxcore-log: 
09-28 06:52:41.514  5634  5680 I jxcore-log: not ok 286 test exited without ending
09-28 06:52:41.514  5634  5680 I jxcore-log: 
09-28 06:52:41.514  5634  5680 I jxcore-log:   ---
09-28 06:52:41.514  5634  5680 I jxcore-log: 
09-28 06:52:41.514  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.514  5634  5680 I jxcore-log: 
09-28 06:52:41.515  5634  5680 I jxcore-log:   ...
09-28 06:52:41.515  5634  5680 I jxcore-log: 
09-28 06:52:41.515  5634  5680 I jxcore-log: not ok 287 test exited without ending
09-28 06:52:41.515  5634  5680 I jxcore-log: 
09-28 06:52:41.515  5634  5680 I jxcore-log:   ---
09-28 06:52:41.515  5634  5680 I jxcore-log: 
09-28 06:52:41.515  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.515  5634  5680 I jxcore-log: 
09-28 06:52:41.515  5634  5680 I jxcore-log:   ...
09-28 06:52:41.515  5634  5680 I jxcore-log: 
09-28 06:52:41.516  5634  5680 I jxcore-log: not ok 288 test exited without ending
09-28 06:52:41.516  5634  5680 I jxcore-log: 
09-28 06:52:41.516  5634  5680 I jxcore-log:   ---
09-28 06:52:41.516  5634  5680 I jxcore-log: 
09-28 06:52:41.516  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.516  5634  5680 I jxcore-log: 
09-28 06:52:41.516  5634  5680 I jxcore-log:   ...
09-28 06:52:41.516  5634  5680 I jxcore-log: 
09-28 06:52:41.517  5634  5680 I jxcore-log: not ok 289 test exited without ending
09-28 06:52:41.517  5634  5680 I jxcore-log: 
09-28 06:52:41.518  5634  5680 I jxcore-log:   ---
09-28 06:52:41.518  5634  5680 I jxcore-log: 
09-28 06:52:41.518  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.518  5634  5680 I jxcore-log: 
09-28 06:52:41.518  5634  5680 I jxcore-log:   ...
09-28 06:52:41.518  5634  5680 I jxcore-log: 
09-28 06:52:41.519  5634  5680 I jxcore-log: not ok 290 test exited without ending
09-28 06:52:41.519  5634  5680 I jxcore-log: 
09-28 06:52:41.519  5634  5680 I jxcore-log:   ---
09-28 06:52:41.519  5634  5680 I jxcore-log: 
09-28 06:52:41.519  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.519  5634  5680 I jxcore-log: 
09-28 06:52:41.519  5634  5680 I jxcore-log:   ...
09-28 06:52:41.519  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log: not ok 291 test exited without ending
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log:   ---
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log:   ...
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log: not ok 292 test exited without ending
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log:   ---
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.520  5634  5680 I jxcore-log:   ...
09-28 06:52:41.520  5634  5680 I jxcore-log: 
09-28 06:52:41.521  5634  5680 I jxcore-log: not ok 293 test exited without ending
09-28 06:52:41.521  5634  5680 I jxcore-log: 
09-28 06:52:41.521  5634  5680 I jxcore-log:   ---
09-28 06:52:41.521  5634  5680 I jxcore-log: 
09-28 06:52:41.521  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.521  5634  5680 I jxcore-log: 
09-28 06:52:41.521  5634  5680 I jxcore-log:   ...
09-28 06:52:41.521  5634  5680 I jxcore-log: 
09-28 06:52:41.522  5634  5680 I jxcore-log: not ok 294 test exited without ending
09-28 06:52:41.522  5634  5680 I jxcore-log: 
09-28 06:52:41.522  5634  5680 I jxcore-log:   ---
09-28 06:52:41.522  5634  5680 I jxcore-log: 
09-28 06:52:41.522  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.522  5634  5680 I jxcore-log: 
09-28 06:52:41.522  5634  5680 I jxcore-log:   ...
09-28 06:52:41.522  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log: not ok 295 test exited without ending
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log:   ---
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log:   ...
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log: not ok 296 test exited without ending
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log:   ---
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.523  5634  5680 I jxcore-log:   ...
09-28 06:52:41.523  5634  5680 I jxcore-log: 
09-28 06:52:41.524  5634  5680 I jxcore-log: not ok 297 test exited without ending
09-28 06:52:41.524  5634  5680 I jxcore-log: 
09-28 06:52:41.524  5634  5680 I jxcore-log:   ---
09-28 06:52:41.524  5634  5680 I jxcore-log: 
09-28 06:52:41.524  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.524  5634  5680 I jxcore-log: 
09-28 06:52:41.524  5634  5680 I jxcore-log:   ...
09-28 06:52:41.524  5634  5680 I jxcore-log: 
09-28 06:52:41.525  5634  5680 I jxcore-log: not ok 298 test exited without ending
09-28 06:52:41.525  5634  5680 I jxcore-log: 
09-28 06:52:41.525  5634  5680 I jxcore-log:   ---
09-28 06:52:41.525  5634  5680 I jxcore-log: 
09-28 06:52:41.525  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.525  5634  5680 I jxcore-log: 
09-28 06:52:41.525  5634  5680 I jxcore-log:   ...
09-28 06:52:41.525  5634  5680 I jxcore-log: 
09-28 06:52:41.526  5634  5680 I jxcore-log: not ok 299 test exited without ending
09-28 06:52:41.526  5634  5680 I jxcore-log: 
09-28 06:52:41.526  5634  5680 I jxcore-log:   ---
09-28 06:52:41.526  5634  5680 I jxcore-log: 
09-28 06:52:41.526  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.526  5634  5680 I jxcore-log: 
09-28 06:52:41.526  5634  5680 I jxcore-log:   ...
09-28 06:52:41.526  5634  5680 I jxcore-log: 
09-28 06:52:41.526  5634  5680 I jxcore-log: not ok 300 test exited without ending
09-28 06:52:41.526  5634  5680 I jxcore-log: 
09-28 06:52:41.526  5634  5680 I jxcore-log:   ---
09-28 06:52:41.526  5634  5680 I jxcore-log: 
09-28 06:52:41.527  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.527  5634  5680 I jxcore-log: 
09-28 06:52:41.527  5634  5680 I jxcore-log:   ...
09-28 06:52:41.527  5634  5680 I jxcore-log: 
09-28 06:52:41.527  5634  5680 I jxcore-log: not ok 301 test exited without ending
09-28 06:52:41.527  5634  5680 I jxcore-log: 
09-28 06:52:41.527  5634  5680 I jxcore-log:   ---
09-28 06:52:41.527  5634  5680 I jxcore-log: 
09-28 06:52:41.527  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.527  5634  5680 I jxcore-log: 
09-28 06:52:41.527  5634  5680 I jxcore-log:   ...
09-28 06:52:41.527  5634  5680 I jxcore-log: 
09-28 06:52:41.528  5634  5680 I jxcore-log: not ok 302 test exited without ending
09-28 06:52:41.528  5634  5680 I jxcore-log: 
09-28 06:52:41.528  5634  5680 I jxcore-log:   ---
09-28 06:52:41.528  5634  5680 I jxcore-log: 
09-28 06:52:41.528  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.528  5634  5680 I jxcore-log: 
09-28 06:52:41.528  5634  5680 I jxcore-log:   ...
09-28 06:52:41.528  5634  5680 I jxcore-log: 
09-28 06:52:41.529  5634  5680 I jxcore-log: not ok 303 test exited without ending
09-28 06:52:41.529  5634  5680 I jxcore-log: 
09-28 06:52:41.529  5634  5680 I jxcore-log:   ---
09-28 06:52:41.529  5634  5680 I jxcore-log: 
09-28 06:52:41.529  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.529  5634  5680 I jxcore-log: 
09-28 06:52:41.529  5634  5680 I jxcore-log:   ...
09-28 06:52:41.529  5634  5680 I jxcore-log: 
09-28 06:52:41.529  5634  5680 I jxcore-log: not ok 304 test exited without ending
09-28 06:52:41.529  5634  5680 I jxcore-log: 
09-28 06:52:41.530  5634  5680 I jxcore-log:   ---
09-28 06:52:41.530  5634  5680 I jxcore-log: 
09-28 06:52:41.530  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.530  5634  5680 I jxcore-log: 
09-28 06:52:41.530  5634  5680 I jxcore-log:   ...
09-28 06:52:41.530  5634  5680 I jxcore-log: 
09-28 06:52:41.530  5634  5680 I jxcore-log: not ok 305 test exited without ending
09-28 06:52:41.530  5634  5680 I jxcore-log: 
09-28 06:52:41.531  5634  5680 I jxcore-log:   ---
09-28 06:52:41.531  5634  5680 I jxcore-log: 
09-28 06:52:41.531  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.531  5634  5680 I jxcore-log: 
09-28 06:52:41.531  5634  5680 I jxcore-log:   ...
09-28 06:52:41.531  5634  5680 I jxcore-log: 
09-28 06:52:41.531  5634  5680 I jxcore-log: not ok 306 test exited without ending
09-28 06:52:41.531  5634  5680 I jxcore-log: 
09-28 06:52:41.532  5634  5680 I jxcore-log:   ---
09-28 06:52:41.532  5634  5680 I jxcore-log: 
09-28 06:52:41.532  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.532  5634  5680 I jxcore-log: 
09-28 06:52:41.532  5634  5680 I jxcore-log:   ...
09-28 06:52:41.532  5634  5680 I jxcore-log: 
09-28 06:52:41.532  5634  5680 I jxcore-log: not ok 307 test exited without ending
09-28 06:52:41.532  5634  5680 I jxcore-log: 
09-28 06:52:41.532  5634  5680 I jxcore-log:   ---
09-28 06:52:41.532  5634  5680 I jxcore-log: 
09-28 06:52:41.532  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.532  5634  5680 I jxcore-log: 
09-28 06:52:41.532  5634  5680 I jxcore-log:   ...
09-28 06:52:41.532  5634  5680 I jxcore-log: 
09-28 06:52:41.533  5634  5680 I jxcore-log: not ok 308 test exited without ending
09-28 06:52:41.533  5634  5680 I jxcore-log: 
09-28 06:52:41.533  5634  5680 I jxcore-log:   ---
09-28 06:52:41.533  5634  5680 I jxcore-log: 
09-28 06:52:41.533  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.533  5634  5680 I jxcore-log: 
09-28 06:52:41.533  5634  5680 I jxcore-log:   ...
09-28 06:52:41.533  5634  5680 I jxcore-log: 
09-28 06:52:41.534  5634  5680 I jxcore-log: not ok 309 test exited without ending
09-28 06:52:41.534  5634  5680 I jxcore-log: 
09-28 06:52:41.534  5634  5680 I jxcore-log:   ---
09-28 06:52:41.534  5634  5680 I jxcore-log: 
09-28 06:52:41.534  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.534  5634  5680 I jxcore-log: 
09-28 06:52:41.534  5634  5680 I jxcore-log:   ...
09-28 06:52:41.534  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log: not ok 310 test exited without ending
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log:   ---
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log:   ...
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log: not ok 311 test exited without ending
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log:   ---
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.535  5634  5680 I jxcore-log:   ...
09-28 06:52:41.535  5634  5680 I jxcore-log: 
09-28 06:52:41.536  5634  5680 I jxcore-log: not ok 312 test exited without ending
09-28 06:52:41.536  5634  5680 I jxcore-log: 
09-28 06:52:41.536  5634  5680 I jxcore-log:   ---
09-28 06:52:41.536  5634  5680 I jxcore-log: 
09-28 06:52:41.536  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.536  5634  5680 I jxcore-log: 
09-28 06:52:41.536  5634  5680 I jxcore-log:   ...
09-28 06:52:41.536  5634  5680 I jxcore-log: 
09-28 06:52:41.537  5634  5680 I jxcore-log: not ok 313 test exited without ending
09-28 06:52:41.537  5634  5680 I jxcore-log: 
09-28 06:52:41.537  5634  5680 I jxcore-log:   ---
09-28 06:52:41.537  5634  5680 I jxcore-log: 
09-28 06:52:41.537  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.537  5634  5680 I jxcore-log: 
09-28 06:52:41.537  5634  5680 I jxcore-log:   ...
09-28 06:52:41.537  5634  5680 I jxcore-log: 
09-28 06:52:41.537  5634  5680 I jxcore-log: not ok 314 test exited without ending
09-28 06:52:41.537  5634  5680 I jxcore-log: 
09-28 06:52:41.538  5634  5680 I jxcore-log:   ---
09-28 06:52:41.538  5634  5680 I jxcore-log: 
09-28 06:52:41.538  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.538  5634  5680 I jxcore-log: 
09-28 06:52:41.538  5634  5680 I jxcore-log:   ...
09-28 06:52:41.538  5634  5680 I jxcore-log: 
09-28 06:52:41.538  5634  5680 I jxcore-log: not ok 315 test exited without ending
09-28 06:52:41.538  5634  5680 I jxcore-log: 
09-28 06:52:41.538  5634  5680 I jxcore-log:   ---
09-28 06:52:41.538  5634  5680 I jxcore-log: 
09-28 06:52:41.538  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.538  5634  5680 I jxcore-log: 
09-28 06:52:41.538  5634  5680 I jxcore-log:   ...
09-28 06:52:41.538  5634  5680 I jxcore-log: 
09-28 06:52:41.539  5634  5680 I jxcore-log: not ok 316 test exited without ending
09-28 06:52:41.539  5634  5680 I jxcore-log: 
09-28 06:52:41.539  5634  5680 I jxcore-log:   ---
09-28 06:52:41.539  5634  5680 I jxcore-log: 
09-28 06:52:41.539  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.539  5634  5680 I jxcore-log: 
09-28 06:52:41.539  5634  5680 I jxcore-log:   ...
09-28 06:52:41.539  5634  5680 I jxcore-log: 
09-28 06:52:41.540  5634  5680 I jxcore-log: not ok 317 test exited without ending
09-28 06:52:41.540  5634  5680 I jxcore-log: 
09-28 06:52:41.540  5634  5680 I jxcore-log:   ---
09-28 06:52:41.540  5634  5680 I jxcore-log: 
09-28 06:52:41.540  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.540  5634  5680 I jxcore-log: 
09-28 06:52:41.540  5634  5680 I jxcore-log:   ...
09-28 06:52:41.540  5634  5680 I jxcore-log: 
09-28 06:52:41.540  5634  5680 I jxcore-log: not ok 318 test exited without ending
09-28 06:52:41.540  5634  5680 I jxcore-log: 
09-28 06:52:41.540  5634  5680 I jxcore-log:   ---
09-28 06:52:41.540  5634  5680 I jxcore-log: 
09-28 06:52:41.541  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.541  5634  5680 I jxcore-log: 
09-28 06:52:41.541  5634  5680 I jxcore-log:   ...
09-28 06:52:41.541  5634  5680 I jxcore-log: 
09-28 06:52:41.541  5634  5680 I jxcore-log: not ok 319 test exited without ending
09-28 06:52:41.541  5634  5680 I jxcore-log: 
09-28 06:52:41.541  5634  5680 I jxcore-log:   ---
09-28 06:52:41.541  5634  5680 I jxcore-log: 
09-28 06:52:41.541  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.541  5634  5680 I jxcore-log: 
09-28 06:52:41.541  5634  5680 I jxcore-log:   ...
09-28 06:52:41.541  5634  5680 I jxcore-log: 
09-28 06:52:41.542  5634  5680 I jxcore-log: not ok 320 test exited without ending
09-28 06:52:41.542  5634  5680 I jxcore-log: 
09-28 06:52:41.542  5634  5680 I jxcore-log:   ---
09-28 06:52:41.542  5634  5680 I jxcore-log: 
09-28 06:52:41.542  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.542  5634  5680 I jxcore-log: 
09-28 06:52:41.542  5634  5680 I jxcore-log:   ...
09-28 06:52:41.542  5634  5680 I jxcore-log: 
09-28 06:52:41.543  5634  5680 I jxcore-log: not ok 321 test exited without ending
09-28 06:52:41.543  5634  5680 I jxcore-log: 
09-28 06:52:41.543  5634  5680 I jxcore-log:   ---
09-28 06:52:41.543  5634  5680 I jxcore-log: 
09-28 06:52:41.543  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.543  5634  5680 I jxcore-log: 
09-28 06:52:41.543  5634  5680 I jxcore-log:   ...
09-28 06:52:41.543  5634  5680 I jxcore-log: 
09-28 06:52:41.548  5634  5680 I jxcore-log: not ok 322 test exited without ending
09-28 06:52:41.548  5634  5680 I jxcore-log: 
09-28 06:52:41.548  5634  5680 I jxcore-log:   ---
09-28 06:52:41.548  5634  5680 I jxcore-log: 
09-28 06:52:41.549  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.549  5634  5680 I jxcore-log: 
09-28 06:52:41.549  5634  5680 I jxcore-log:   ...
09-28 06:52:41.549  5634  5680 I jxcore-log: 
09-28 06:52:41.549  5634  5680 I jxcore-log: not ok 323 test exited without ending
09-28 06:52:41.549  5634  5680 I jxcore-log: 
09-28 06:52:41.549  5634  5680 I jxcore-log:   ---
09-28 06:52:41.549  5634  5680 I jxcore-log: 
09-28 06:52:41.550  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.550  5634  5680 I jxcore-log: 
09-28 06:52:41.550  5634  5680 I jxcore-log:   ...
09-28 06:52:41.550  5634  5680 I jxcore-log: 
09-28 06:52:41.550  5634  5680 I jxcore-log: not ok 324 test exited without ending
09-28 06:52:41.550  5634  5680 I jxcore-log: 
09-28 06:52:41.550  5634  5680 I jxcore-log:   ---
09-28 06:52:41.550  5634  5680 I jxcore-log: 
09-28 06:52:41.550  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.550  5634  5680 I jxcore-log: 
09-28 06:52:41.550  5634  5680 I jxcore-log:   ...
09-28 06:52:41.550  5634  5680 I jxcore-log: 
09-28 06:52:41.551  5634  5680 I jxcore-log: not ok 325 test exited without ending
09-28 06:52:41.551  5634  5680 I jxcore-log: 
09-28 06:52:41.551  5634  5680 I jxcore-log:   ---
09-28 06:52:41.551  5634  5680 I jxcore-log: 
09-28 06:52:41.551  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.551  5634  5680 I jxcore-log: 
09-28 06:52:41.551  5634  5680 I jxcore-log:   ...
09-28 06:52:41.551  5634  5680 I jxcore-log: 
09-28 06:52:41.552  5634  5680 I jxcore-log: not ok 326 test exited without ending
09-28 06:52:41.552  5634  5680 I jxcore-log: 
09-28 06:52:41.552  5634  5680 I jxcore-log:   ---
09-28 06:52:41.552  5634  5680 I jxcore-log: 
09-28 06:52:41.552  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.552  5634  5680 I jxcore-log: 
09-28 06:52:41.552  5634  5680 I jxcore-log:   ...
09-28 06:52:41.552  5634  5680 I jxcore-log: 
09-28 06:52:41.552  5634  5680 I jxcore-log: not ok 327 test exited without ending
09-28 06:52:41.552  5634  5680 I jxcore-log: 
09-28 06:52:41.553  5634  5680 I jxcore-log:   ---
09-28 06:52:41.553  5634  5680 I jxcore-log: 
09-28 06:52:41.553  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.553  5634  5680 I jxcore-log: 
09-28 06:52:41.553  5634  5680 I jxcore-log:   ...
09-28 06:52:41.553  5634  5680 I jxcore-log: 
09-28 06:52:41.553  5634  5680 I jxcore-log: not ok 328 test exited without ending
09-28 06:52:41.553  5634  5680 I jxcore-log: 
09-28 06:52:41.553  5634  5680 I jxcore-log:   ---
09-28 06:52:41.553  5634  5680 I jxcore-log: 
09-28 06:52:41.553  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.553  5634  5680 I jxcore-log: 
09-28 06:52:41.553  5634  5680 I jxcore-log:   ...
09-28 06:52:41.553  5634  5680 I jxcore-log: 
09-28 06:52:41.554  5634  5680 I jxcore-log: not ok 329 test exited without ending
09-28 06:52:41.554  5634  5680 I jxcore-log: 
09-28 06:52:41.554  5634  5680 I jxcore-log:   ---
09-28 06:52:41.554  5634  5680 I jxcore-log: 
09-28 06:52:41.554  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.554  5634  5680 I jxcore-log: 
09-28 06:52:41.554  5634  5680 I jxcore-log:   ...
09-28 06:52:41.554  5634  5680 I jxcore-log: 
,09-28 06:52:41.555  5634  5680 I jxcore-log: not ok 330 test exited without ending
09-28 06:52:41.555  5634  5680 I jxcore-log: 
09-28 06:52:41.555  5634  5680 I jxcore-log:   ---
09-28 06:52:41.555  5634  5680 I jxcore-log: 
09-28 06:52:41.555  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.555  5634  5680 I jxcore-log: 
09-28 06:52:41.555  5634  5680 I jxcore-log:   ...
09-28 06:52:41.555  5634  5680 I jxcore-log: 
09-28 06:52:41.555  5634  5680 I jxcore-log: not ok 331 test exited without ending
09-28 06:52:41.555  5634  5680 I jxcore-log: 
09-28 06:52:41.555  5634  5680 I jxcore-log:   ---
09-28 06:52:41.555  5634  5680 I jxcore-log: 
09-28 06:52:41.556  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.556  5634  5680 I jxcore-log: 
09-28 06:52:41.556  5634  5680 I jxcore-log:   ...
09-28 06:52:41.556  5634  5680 I jxcore-log: 
09-28 06:52:41.556  5634  5680 I jxcore-log: not ok 332 test exited without ending
09-28 06:52:41.556  5634  5680 I jxcore-log: 
09-28 06:52:41.556  5634  5680 I jxcore-log:   ---
09-28 06:52:41.556  5634  5680 I jxcore-log: 
09-28 06:52:41.556  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.556  5634  5680 I jxcore-log: 
09-28 06:52:41.556  5634  5680 I jxcore-log:   ...
09-28 06:52:41.556  5634  5680 I jxcore-log: 
,09-28 06:52:41.557  5634  5680 I jxcore-log: not ok 333 test exited without ending
09-28 06:52:41.557  5634  5680 I jxcore-log: 
09-28 06:52:41.557  5634  5680 I jxcore-log:   ---
09-28 06:52:41.557  5634  5680 I jxcore-log: 
09-28 06:52:41.557  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.557  5634  5680 I jxcore-log: 
09-28 06:52:41.557  5634  5680 I jxcore-log:   ...
09-28 06:52:41.557  5634  5680 I jxcore-log: 
,09-28 06:52:41.558  5634  5680 I jxcore-log: not ok 334 test exited without ending
09-28 06:52:41.558  5634  5680 I jxcore-log: 
09-28 06:52:41.558  5634  5680 I jxcore-log:   ---
09-28 06:52:41.558  5634  5680 I jxcore-log: 
09-28 06:52:41.558  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.558  5634  5680 I jxcore-log: 
09-28 06:52:41.558  5634  5680 I jxcore-log:   ...
09-28 06:52:41.558  5634  5680 I jxcore-log: 
09-28 06:52:41.558  5634  5680 I jxcore-log: not ok 335 test exited without ending
09-28 06:52:41.558  5634  5680 I jxcore-log: 
09-28 06:52:41.558  5634  5680 I jxcore-log:   ---
09-28 06:52:41.558  5634  5680 I jxcore-log: 
09-28 06:52:41.559  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.559  5634  5680 I jxcore-log: 
09-28 06:52:41.559  5634  5680 I jxcore-log:   ...
09-28 06:52:41.559  5634  5680 I jxcore-log: 
,09-28 06:52:41.559  5634  5680 I jxcore-log: not ok 336 test exited without ending
09-28 06:52:41.559  5634  5680 I jxcore-log: 
09-28 06:52:41.559  5634  5680 I jxcore-log:   ---
09-28 06:52:41.559  5634  5680 I jxcore-log: 
09-28 06:52:41.559  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.559  5634  5680 I jxcore-log: 
09-28 06:52:41.559  5634  5680 I jxcore-log:   ...
09-28 06:52:41.559  5634  5680 I jxcore-log: 
09-28 06:52:41.560  5634  5680 I jxcore-log: not ok 337 test exited without ending
09-28 06:52:41.560  5634  5680 I jxcore-log: 
09-28 06:52:41.560  5634  5680 I jxcore-log:   ---
09-28 06:52:41.560  5634  5680 I jxcore-log: 
09-28 06:52:41.560  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.560  5634  5680 I jxcore-log: 
09-28 06:52:41.560  5634  5680 I jxcore-log:   ...
09-28 06:52:41.560  5634  5680 I jxcore-log: 
09-28 06:52:41.561  5634  5680 I jxcore-log: not ok 338 test exited without ending
09-28 06:52:41.561  5634  5680 I jxcore-log: 
09-28 06:52:41.561  5634  5680 I jxcore-log:   ---
09-28 06:52:41.561  5634  5680 I jxcore-log: 
09-28 06:52:41.561  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.561  5634  5680 I jxcore-log: 
09-28 06:52:41.561  5634  5680 I jxcore-log:   ...
09-28 06:52:41.561  5634  5680 I jxcore-log: 
,09-28 06:52:41.561  5634  5680 I jxcore-log: not ok 339 test exited without ending
09-28 06:52:41.561  5634  5680 I jxcore-log: 
09-28 06:52:41.561  5634  5680 I jxcore-log:   ---
09-28 06:52:41.561  5634  5680 I jxcore-log: 
09-28 06:52:41.561  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.561  5634  5680 I jxcore-log: 
09-28 06:52:41.561  5634  5680 I jxcore-log:   ...
09-28 06:52:41.561  5634  5680 I jxcore-log: 
09-28 06:52:41.562  5634  5680 I jxcore-log: not ok 340 test exited without ending
09-28 06:52:41.562  5634  5680 I jxcore-log: 
,09-28 06:52:41.562  5634  5680 I jxcore-log:   ---
09-28 06:52:41.562  5634  5680 I jxcore-log: 
09-28 06:52:41.562  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.562  5634  5680 I jxcore-log: 
09-28 06:52:41.562  5634  5680 I jxcore-log:   ...
09-28 06:52:41.562  5634  5680 I jxcore-log: 
09-28 06:52:41.563  5634  5680 I jxcore-log: not ok 341 test exited without ending
09-28 06:52:41.563  5634  5680 I jxcore-log: 
09-28 06:52:41.563  5634  5680 I jxcore-log:   ---
09-28 06:52:41.563  5634  5680 I jxcore-log: 
09-28 06:52:41.563  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.563  5634  5680 I jxcore-log: 
09-28 06:52:41.563  5634  5680 I jxcore-log:   ...
09-28 06:52:41.563  5634  5680 I jxcore-log: 
,09-28 06:52:41.563  5634  5680 I jxcore-log: not ok 342 test exited without ending
09-28 06:52:41.563  5634  5680 I jxcore-log: 
09-28 06:52:41.564  5634  5680 I jxcore-log:   ---
09-28 06:52:41.564  5634  5680 I jxcore-log: 
09-28 06:52:41.564  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.564  5634  5680 I jxcore-log: 
09-28 06:52:41.564  5634  5680 I jxcore-log:   ...
09-28 06:52:41.564  5634  5680 I jxcore-log: 
09-28 06:52:41.564  5634  5680 I jxcore-log: not ok 343 test exited without ending
09-28 06:52:41.564  5634  5680 I jxcore-log: 
09-28 06:52:41.564  5634  5680 I jxcore-log:   ---
09-28 06:52:41.564  5634  5680 I jxcore-log: 
09-28 06:52:41.564  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.564  5634  5680 I jxcore-log: 
09-28 06:52:41.564  5634  5680 I jxcore-log:   ...
09-28 06:52:41.564  5634  5680 I jxcore-log: 
,09-28 06:52:41.565  5634  5680 I jxcore-log: not ok 344 test exited without ending
09-28 06:52:41.565  5634  5680 I jxcore-log: 
09-28 06:52:41.565  5634  5680 I jxcore-log:   ---
09-28 06:52:41.565  5634  5680 I jxcore-log: 
09-28 06:52:41.565  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.565  5634  5680 I jxcore-log: 
09-28 06:52:41.565  5634  5680 I jxcore-log:   ...
09-28 06:52:41.565  5634  5680 I jxcore-log: 
,09-28 06:52:41.566  5634  5680 I jxcore-log: not ok 345 test exited without ending
09-28 06:52:41.566  5634  5680 I jxcore-log: 
09-28 06:52:41.566  5634  5680 I jxcore-log:   ---
09-28 06:52:41.566  5634  5680 I jxcore-log: 
09-28 06:52:41.566  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.566  5634  5680 I jxcore-log: 
09-28 06:52:41.566  5634  5680 I jxcore-log:   ...
09-28 06:52:41.566  5634  5680 I jxcore-log: 
,09-28 06:52:41.567  5634  5680 I jxcore-log: not ok 346 test exited without ending
09-28 06:52:41.567  5634  5680 I jxcore-log: 
09-28 06:52:41.567  5634  5680 I jxcore-log:   ---
09-28 06:52:41.567  5634  5680 I jxcore-log: 
09-28 06:52:41.567  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.567  5634  5680 I jxcore-log: 
09-28 06:52:41.567  5634  5680 I jxcore-log:   ...
09-28 06:52:41.567  5634  5680 I jxcore-log: 
09-28 06:52:41.567  5634  5680 I jxcore-log: not ok 347 test exited without ending
09-28 06:52:41.567  5634  5680 I jxcore-log: 
09-28 06:52:41.567  5634  5680 I jxcore-log:   ---
09-28 06:52:41.567  5634  5680 I jxcore-log: 
09-28 06:52:41.567  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.567  5634  5680 I jxcore-log: 
,09-28 06:52:41.567  5634  5680 I jxcore-log:   ...
09-28 06:52:41.567  5634  5680 I jxcore-log: 
09-28 06:52:41.568  5634  5680 I jxcore-log: not ok 348 test exited without ending
09-28 06:52:41.568  5634  5680 I jxcore-log: 
09-28 06:52:41.568  5634  5680 I jxcore-log:   ---
09-28 06:52:41.568  5634  5680 I jxcore-log: 
09-28 06:52:41.568  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.568  5634  5680 I jxcore-log: 
09-28 06:52:41.568  5634  5680 I jxcore-log:   ...
09-28 06:52:41.568  5634  5680 I jxcore-log: 
,09-28 06:52:41.569  5634  5680 I jxcore-log: not ok 349 test exited without ending
09-28 06:52:41.569  5634  5680 I jxcore-log: 
09-28 06:52:41.569  5634  5680 I jxcore-log:   ---
09-28 06:52:41.569  5634  5680 I jxcore-log: 
09-28 06:52:41.569  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.569  5634  5680 I jxcore-log: 
,09-28 06:52:41.569  5634  5680 I jxcore-log:   ...
09-28 06:52:41.569  5634  5680 I jxcore-log: 
09-28 06:52:41.570  5634  5680 I jxcore-log: not ok 350 test exited without ending
09-28 06:52:41.570  5634  5680 I jxcore-log: 
09-28 06:52:41.570  5634  5680 I jxcore-log:   ---
09-28 06:52:41.570  5634  5680 I jxcore-log: 
,09-28 06:52:41.570  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.570  5634  5680 I jxcore-log: 
09-28 06:52:41.570  5634  5680 I jxcore-log:   ...
09-28 06:52:41.570  5634  5680 I jxcore-log: 
,09-28 06:52:41.571  5634  5680 I jxcore-log: not ok 351 test exited without ending
09-28 06:52:41.571  5634  5680 I jxcore-log: 
09-28 06:52:41.571  5634  5680 I jxcore-log:   ---
09-28 06:52:41.571  5634  5680 I jxcore-log: 
09-28 06:52:41.571  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.571  5634  5680 I jxcore-log: 
09-28 06:52:41.571  5634  5680 I jxcore-log:   ...
09-28 06:52:41.571  5634  5680 I jxcore-log: 
,09-28 06:52:41.572  5634  5680 I jxcore-log: not ok 352 test exited without ending
09-28 06:52:41.572  5634  5680 I jxcore-log: 
09-28 06:52:41.572  5634  5680 I jxcore-log:   ---
09-28 06:52:41.572  5634  5680 I jxcore-log: 
09-28 06:52:41.572  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.572  5634  5680 I jxcore-log: 
09-28 06:52:41.572  5634  5680 I jxcore-log:   ...
09-28 06:52:41.572  5634  5680 I jxcore-log: 
,09-28 06:52:41.573  5634  5680 I jxcore-log: not ok 353 test exited without ending
09-28 06:52:41.573  5634  5680 I jxcore-log: 
09-28 06:52:41.573  5634  5680 I jxcore-log:   ---
09-28 06:52:41.573  5634  5680 I jxcore-log: 
09-28 06:52:41.573  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.573  5634  5680 I jxcore-log: 
09-28 06:52:41.573  5634  5680 I jxcore-log:   ...
09-28 06:52:41.573  5634  5680 I jxcore-log: 
,09-28 06:52:41.574  5634  5680 I jxcore-log: not ok 354 test exited without ending
09-28 06:52:41.574  5634  5680 I jxcore-log: 
09-28 06:52:41.574  5634  5680 I jxcore-log:   ---
09-28 06:52:41.574  5634  5680 I jxcore-log: 
09-28 06:52:41.574  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.574  5634  5680 I jxcore-log: 
09-28 06:52:41.574  5634  5680 I jxcore-log:   ...
09-28 06:52:41.574  5634  5680 I jxcore-log: 
,09-28 06:52:41.575  5634  5680 I jxcore-log: not ok 355 test exited without ending
09-28 06:52:41.575  5634  5680 I jxcore-log: 
09-28 06:52:41.575  5634  5680 I jxcore-log:   ---
09-28 06:52:41.575  5634  5680 I jxcore-log: 
09-28 06:52:41.575  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.575  5634  5680 I jxcore-log: 
09-28 06:52:41.575  5634  5680 I jxcore-log:   ...
09-28 06:52:41.575  5634  5680 I jxcore-log: 
,09-28 06:52:41.576  5634  5680 I jxcore-log: not ok 356 test exited without ending
09-28 06:52:41.576  5634  5680 I jxcore-log: 
09-28 06:52:41.576  5634  5680 I jxcore-log:   ---
09-28 06:52:41.576  5634  5680 I jxcore-log: 
09-28 06:52:41.576  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.576  5634  5680 I jxcore-log: 
09-28 06:52:41.576  5634  5680 I jxcore-log:   ...
09-28 06:52:41.576  5634  5680 I jxcore-log: 
,09-28 06:52:41.577  5634  5680 I jxcore-log: not ok 357 test exited without ending
09-28 06:52:41.577  5634  5680 I jxcore-log: 
09-28 06:52:41.577  5634  5680 I jxcore-log:   ---
09-28 06:52:41.577  5634  5680 I jxcore-log: 
09-28 06:52:41.577  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.577  5634  5680 I jxcore-log: 
,09-28 06:52:41.577  5634  5680 I jxcore-log:   ...
09-28 06:52:41.577  5634  5680 I jxcore-log: 
,09-28 06:52:41.578  5634  5680 I jxcore-log: not ok 358 test exited without ending
09-28 06:52:41.578  5634  5680 I jxcore-log: 
09-28 06:52:41.578  5634  5680 I jxcore-log:   ---
09-28 06:52:41.578  5634  5680 I jxcore-log: 
09-28 06:52:41.578  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.578  5634  5680 I jxcore-log: 
09-28 06:52:41.578  5634  5680 I jxcore-log:   ...
09-28 06:52:41.578  5634  5680 I jxcore-log: 
,09-28 06:52:41.579  5634  5680 I jxcore-log: not ok 359 test exited without ending
09-28 06:52:41.579  5634  5680 I jxcore-log: 
09-28 06:52:41.579  5634  5680 I jxcore-log:   ---
09-28 06:52:41.579  5634  5680 I jxcore-log: 
09-28 06:52:41.579  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.579  5634  5680 I jxcore-log: 
09-28 06:52:41.579  5634  5680 I jxcore-log:   ...
09-28 06:52:41.579  5634  5680 I jxcore-log: 
,09-28 06:52:41.580  5634  5680 I jxcore-log: not ok 360 test exited without ending
09-28 06:52:41.580  5634  5680 I jxcore-log: 
09-28 06:52:41.580  5634  5680 I jxcore-log:   ---
09-28 06:52:41.580  5634  5680 I jxcore-log: 
09-28 06:52:41.580  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.580  5634  5680 I jxcore-log: 
09-28 06:52:41.580  5634  5680 I jxcore-log:   ...
09-28 06:52:41.580  5634  5680 I jxcore-log: 
,09-28 06:52:41.581  5634  5680 I jxcore-log: not ok 361 test exited without ending
09-28 06:52:41.581  5634  5680 I jxcore-log: 
,09-28 06:52:41.581  5634  5680 I jxcore-log:   ---
09-28 06:52:41.581  5634  5680 I jxcore-log: 
09-28 06:52:41.581  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.581  5634  5680 I jxcore-log: 
09-28 06:52:41.581  5634  5680 I jxcore-log:   ...
09-28 06:52:41.581  5634  5680 I jxcore-log: 
,09-28 06:52:41.582  5634  5680 I jxcore-log: not ok 362 test exited without ending
09-28 06:52:41.582  5634  5680 I jxcore-log: 
09-28 06:52:41.582  5634  5680 I jxcore-log:   ---
09-28 06:52:41.582  5634  5680 I jxcore-log: 
09-28 06:52:41.582  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.582  5634  5680 I jxcore-log: 
09-28 06:52:41.582  5634  5680 I jxcore-log:   ...
09-28 06:52:41.582  5634  5680 I jxcore-log: 
,09-28 06:52:41.582  5634  5680 I jxcore-log: not ok 363 test exited without ending
09-28 06:52:41.582  5634  5680 I jxcore-log: 
09-28 06:52:41.582  5634  5680 I jxcore-log:   ---
09-28 06:52:41.582  5634  5680 I jxcore-log: 
09-28 06:52:41.583  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.583  5634  5680 I jxcore-log: 
09-28 06:52:41.583  5634  5680 I jxcore-log:   ...
09-28 06:52:41.583  5634  5680 I jxcore-log: 
,09-28 06:52:41.583  5634  5680 I jxcore-log: not ok 364 test exited without ending
09-28 06:52:41.583  5634  5680 I jxcore-log: 
09-28 06:52:41.583  5634  5680 I jxcore-log:   ---
09-28 06:52:41.583  5634  5680 I jxcore-log: 
09-28 06:52:41.583  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.583  5634  5680 I jxcore-log: 
09-28 06:52:41.583  5634  5680 I jxcore-log:   ...
09-28 06:52:41.583  5634  5680 I jxcore-log: 
09-28 06:52:41.584  5634  5680 I jxcore-log: not ok 365 test exited without ending
09-28 06:52:41.584  5634  5680 I jxcore-log: 
09-28 06:52:41.584  5634  5680 I jxcore-log:   ---
09-28 06:52:41.584  5634  5680 I jxcore-log: 
09-28 06:52:41.584  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.584  5634  5680 I jxcore-log: 
09-28 06:52:41.584  5634  5680 I jxcore-log:   ...
09-28 06:52:41.584  5634  5680 I jxcore-log: 
,09-28 06:52:41.585  5634  5680 I jxcore-log: not ok 366 test exited without ending
09-28 06:52:41.585  5634  5680 I jxcore-log: 
09-28 06:52:41.585  5634  5680 I jxcore-log:   ---
09-28 06:52:41.585  5634  5680 I jxcore-log: 
09-28 06:52:41.585  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.585  5634  5680 I jxcore-log: 
09-28 06:52:41.585  5634  5680 I jxcore-log:   ...
09-28 06:52:41.585  5634  5680 I jxcore-log: 
,09-28 06:52:41.586  5634  5680 I jxcore-log: not ok 367 test exited without ending
09-28 06:52:41.586  5634  5680 I jxcore-log: 
09-28 06:52:41.586  5634  5680 I jxcore-log:   ---
09-28 06:52:41.586  5634  5680 I jxcore-log: 
09-28 06:52:41.586  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.586  5634  5680 I jxcore-log: 
09-28 06:52:41.586  5634  5680 I jxcore-log:   ...
09-28 06:52:41.586  5634  5680 I jxcore-log: 
,09-28 06:52:41.587  5634  5680 I jxcore-log: not ok 368 test exited without ending
09-28 06:52:41.587  5634  5680 I jxcore-log: 
09-28 06:52:41.587  5634  5680 I jxcore-log:   ---
09-28 06:52:41.587  5634  5680 I jxcore-log: 
09-28 06:52:41.587  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.587  5634  5680 I jxcore-log: 
09-28 06:52:41.587  5634  5680 I jxcore-log:   ...
09-28 06:52:41.587  5634  5680 I jxcore-log: 
,09-28 06:52:41.588  5634  5680 I jxcore-log: not ok 369 test exited without ending
09-28 06:52:41.588  5634  5680 I jxcore-log: 
09-28 06:52:41.588  5634  5680 I jxcore-log:   ---
09-28 06:52:41.588  5634  5680 I jxcore-log: 
,09-28 06:52:41.588  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.588  5634  5680 I jxcore-log: 
09-28 06:52:41.588  5634  5680 I jxcore-log:   ...
09-28 06:52:41.588  5634  5680 I jxcore-log: 
,09-28 06:52:41.589  5634  5680 I jxcore-log: not ok 370 test exited without ending
09-28 06:52:41.589  5634  5680 I jxcore-log: 
09-28 06:52:41.589  5634  5680 I jxcore-log:   ---
09-28 06:52:41.589  5634  5680 I jxcore-log: 
09-28 06:52:41.589  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.589  5634  5680 I jxcore-log: 
09-28 06:52:41.589  5634  5680 I jxcore-log:   ...
09-28 06:52:41.589  5634  5680 I jxcore-log: 
,09-28 06:52:41.590  5634  5680 I jxcore-log: not ok 371 test exited without ending
09-28 06:52:41.590  5634  5680 I jxcore-log: 
09-28 06:52:41.590  5634  5680 I jxcore-log:   ---
09-28 06:52:41.590  5634  5680 I jxcore-log: 
09-28 06:52:41.590  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.590  5634  5680 I jxcore-log: 
09-28 06:52:41.590  5634  5680 I jxcore-log:   ...
09-28 06:52:41.590  5634  5680 I jxcore-log: 
,09-28 06:52:41.591  5634  5680 I jxcore-log: not ok 372 test exited without ending
09-28 06:52:41.591  5634  5680 I jxcore-log: 
09-28 06:52:41.591  5634  5680 I jxcore-log:   ---
09-28 06:52:41.591  5634  5680 I jxcore-log: 
09-28 06:52:41.591  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.591  5634  5680 I jxcore-log: 
09-28 06:52:41.591  5634  5680 I jxcore-log:   ...
09-28 06:52:41.591  5634  5680 I jxcore-log: 
,09-28 06:52:41.592  5634  5680 I jxcore-log: not ok 373 test exited without ending
09-28 06:52:41.592  5634  5680 I jxcore-log: 
09-28 06:52:41.592  5634  5680 I jxcore-log:   ---
09-28 06:52:41.592  5634  5680 I jxcore-log: 
09-28 06:52:41.592  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.592  5634  5680 I jxcore-log: 
09-28 06:52:41.592  5634  5680 I jxcore-log:   ...
09-28 06:52:41.592  5634  5680 I jxcore-log: 
,09-28 06:52:41.592  5634  5680 I jxcore-log: not ok 374 test exited without ending
09-28 06:52:41.592  5634  5680 I jxcore-log: 
09-28 06:52:41.593  5634  5680 I jxcore-log:   ---
09-28 06:52:41.593  5634  5680 I jxcore-log: 
09-28 06:52:41.593  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.593  5634  5680 I jxcore-log: 
09-28 06:52:41.593  5634  5680 I jxcore-log:   ...
09-28 06:52:41.593  5634  5680 I jxcore-log: 
,09-28 06:52:41.593  5634  5680 I jxcore-log: not ok 375 test exited without ending
09-28 06:52:41.593  5634  5680 I jxcore-log: 
09-28 06:52:41.593  5634  5680 I jxcore-log:   ---
09-28 06:52:41.593  5634  5680 I jxcore-log: 
09-28 06:52:41.594  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.594  5634  5680 I jxcore-log: 
09-28 06:52:41.594  5634  5680 I jxcore-log:   ...
09-28 06:52:41.594  5634  5680 I jxcore-log: 
,09-28 06:52:41.594  5634  5680 I jxcore-log: not ok 376 test exited without ending
09-28 06:52:41.594  5634  5680 I jxcore-log: 
09-28 06:52:41.594  5634  5680 I jxcore-log:   ---
09-28 06:52:41.594  5634  5680 I jxcore-log: 
09-28 06:52:41.595  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.595  5634  5680 I jxcore-log: 
09-28 06:52:41.595  5634  5680 I jxcore-log:   ...
09-28 06:52:41.595  5634  5680 I jxcore-log: 
,09-28 06:52:41.595  5634  5680 I jxcore-log: not ok 377 test exited without ending
09-28 06:52:41.595  5634  5680 I jxcore-log: 
09-28 06:52:41.596  5634  5680 I jxcore-log:   ---
09-28 06:52:41.596  5634  5680 I jxcore-log: 
09-28 06:52:41.596  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.596  5634  5680 I jxcore-log: 
09-28 06:52:41.596  5634  5680 I jxcore-log:   ...
09-28 06:52:41.596  5634  5680 I jxcore-log: 
,09-28 06:52:41.596  5634  5680 I jxcore-log: not ok 378 test exited without ending
09-28 06:52:41.596  5634  5680 I jxcore-log: 
09-28 06:52:41.596  5634  5680 I jxcore-log:   ---
09-28 06:52:41.596  5634  5680 I jxcore-log: 
09-28 06:52:41.596  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.596  5634  5680 I jxcore-log: 
,09-28 06:52:41.597  5634  5680 I jxcore-log:   ...
09-28 06:52:41.597  5634  5680 I jxcore-log: 
09-28 06:52:41.597  5634  5680 I jxcore-log: not ok 379 test exited without ending
09-28 06:52:41.597  5634  5680 I jxcore-log: 
09-28 06:52:41.597  5634  5680 I jxcore-log:   ---
09-28 06:52:41.597  5634  5680 I jxcore-log: 
09-28 06:52:41.597  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.597  5634  5680 I jxcore-log: 
09-28 06:52:41.597  5634  5680 I jxcore-log:   ...
09-28 06:52:41.597  5634  5680 I jxcore-log: 
,09-28 06:52:41.598  5634  5680 I jxcore-log: not ok 380 test exited without ending
09-28 06:52:41.598  5634  5680 I jxcore-log: 
09-28 06:52:41.598  5634  5680 I jxcore-log:   ---
09-28 06:52:41.598  5634  5680 I jxcore-log: 
09-28 06:52:41.598  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.598  5634  5680 I jxcore-log: 
,09-28 06:52:41.598  5634  5680 I jxcore-log:   ...
09-28 06:52:41.598  5634  5680 I jxcore-log: 
09-28 06:52:41.599  5634  5680 I jxcore-log: not ok 381 test exited without ending
09-28 06:52:41.599  5634  5680 I jxcore-log: 
09-28 06:52:41.599  5634  5680 I jxcore-log:   ---
09-28 06:52:41.599  5634  5680 I jxcore-log: 
09-28 06:52:41.599  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.599  5634  5680 I jxcore-log: 
,09-28 06:52:41.599  5634  5680 I jxcore-log:   ...
09-28 06:52:41.599  5634  5680 I jxcore-log: 
09-28 06:52:41.600  5634  5680 I jxcore-log: not ok 382 test exited without ending
09-28 06:52:41.600  5634  5680 I jxcore-log: 
,09-28 06:52:41.600  5634  5680 I jxcore-log:   ---
09-28 06:52:41.600  5634  5680 I jxcore-log: 
09-28 06:52:41.600  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.600  5634  5680 I jxcore-log: 
09-28 06:52:41.600  5634  5680 I jxcore-log:   ...
09-28 06:52:41.600  5634  5680 I jxcore-log: 
,09-28 06:52:41.601  5634  5680 I jxcore-log: not ok 383 test exited without ending
09-28 06:52:41.601  5634  5680 I jxcore-log: 
09-28 06:52:41.601  5634  5680 I jxcore-log:   ---
09-28 06:52:41.601  5634  5680 I jxcore-log: 
09-28 06:52:41.601  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.601  5634  5680 I jxcore-log: 
09-28 06:52:41.601  5634  5680 I jxcore-log:   ...
09-28 06:52:41.601  5634  5680 I jxcore-log: 
09-28 06:52:41.602  5634  5680 I jxcore-log: not ok 384 test exited without ending
09-28 06:52:41.602  5634  5680 I jxcore-log: 
09-28 06:52:41.602  5634  5680 I jxcore-log:   ---
09-28 06:52:41.602  5634  5680 I jxcore-log: 
,09-28 06:52:41.602  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.602  5634  5680 I jxcore-log: 
09-28 06:52:41.602  5634  5680 I jxcore-log:   ...
09-28 06:52:41.602  5634  5680 I jxcore-log: 
09-28 06:52:41.603  5634  5680 I jxcore-log: not ok 385 test exited without ending
09-28 06:52:41.603  5634  5680 I jxcore-log: 
09-28 06:52:41.603  5634  5680 I jxcore-log:   ---
09-28 06:52:41.603  5634  5680 I jxcore-log: 
09-28 06:52:41.603  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.603  5634  5680 I jxcore-log: 
09-28 06:52:41.603  5634  5680 I jxcore-log:   ...
09-28 06:52:41.603  5634  5680 I jxcore-log: 
,09-28 06:52:41.603  5634  5680 I jxcore-log: not ok 386 test exited without ending
09-28 06:52:41.603  5634  5680 I jxcore-log: 
09-28 06:52:41.604  5634  5680 I jxcore-log:   ---
09-28 06:52:41.604  5634  5680 I jxcore-log: 
09-28 06:52:41.604  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.604  5634  5680 I jxcore-log: 
09-28 06:52:41.604  5634  5680 I jxcore-log:   ...
09-28 06:52:41.604  5634  5680 I jxcore-log: 
,09-28 06:52:41.604  5634  5680 I jxcore-log: not ok 387 test exited without ending
09-28 06:52:41.604  5634  5680 I jxcore-log: 
09-28 06:52:41.605  5634  5680 I jxcore-log:   ---
09-28 06:52:41.605  5634  5680 I jxcore-log: 
09-28 06:52:41.605  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.605  5634  5680 I jxcore-log: 
09-28 06:52:41.605  5634  5680 I jxcore-log:   ...
09-28 06:52:41.605  5634  5680 I jxcore-log: 
,09-28 06:52:41.605  5634  5680 I jxcore-log: not ok 388 test exited without ending
09-28 06:52:41.605  5634  5680 I jxcore-log: 
09-28 06:52:41.605  5634  5680 I jxcore-log:   ---
09-28 06:52:41.605  5634  5680 I jxcore-log: 
09-28 06:52:41.605  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.605  5634  5680 I jxcore-log: 
09-28 06:52:41.606  5634  5680 I jxcore-log:   ...
09-28 06:52:41.606  5634  5680 I jxcore-log: 
,09-28 06:52:41.606  5634  5680 I jxcore-log: not ok 389 test exited without ending
09-28 06:52:41.606  5634  5680 I jxcore-log: 
09-28 06:52:41.606  5634  5680 I jxcore-log:   ---
09-28 06:52:41.606  5634  5680 I jxcore-log: 
,09-28 06:52:41.606  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.606  5634  5680 I jxcore-log: 
09-28 06:52:41.607  5634  5680 I jxcore-log:   ...
09-28 06:52:41.607  5634  5680 I jxcore-log: 
,09-28 06:52:41.607  5634  5680 I jxcore-log: not ok 390 test exited without ending
09-28 06:52:41.607  5634  5680 I jxcore-log: 
09-28 06:52:41.607  5634  5680 I jxcore-log:   ---
09-28 06:52:41.607  5634  5680 I jxcore-log: 
09-28 06:52:41.607  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.607  5634  5680 I jxcore-log: 
09-28 06:52:41.608  5634  5680 I jxcore-log:   ...
09-28 06:52:41.608  5634  5680 I jxcore-log: 
,09-28 06:52:41.608  5634  5680 I jxcore-log: not ok 391 test exited without ending
09-28 06:52:41.608  5634  5680 I jxcore-log: 
09-28 06:52:41.608  5634  5680 I jxcore-log:   ---
09-28 06:52:41.608  5634  5680 I jxcore-log: 
09-28 06:52:41.608  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.608  5634  5680 I jxcore-log: 
09-28 06:52:41.608  5634  5680 I jxcore-log:   ...
09-28 06:52:41.608  5634  5680 I jxcore-log: 
,09-28 06:52:41.609  5634  5680 I jxcore-log: not ok 392 test exited without ending
09-28 06:52:41.609  5634  5680 I jxcore-log: 
09-28 06:52:41.609  5634  5680 I jxcore-log:   ---
09-28 06:52:41.609  5634  5680 I jxcore-log: 
09-28 06:52:41.609  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.609  5634  5680 I jxcore-log: 
09-28 06:52:41.609  5634  5680 I jxcore-log:   ...
09-28 06:52:41.609  5634  5680 I jxcore-log: 
,09-28 06:52:41.610  5634  5680 I jxcore-log: not ok 393 test exited without ending
09-28 06:52:41.610  5634  5680 I jxcore-log: 
09-28 06:52:41.610  5634  5680 I jxcore-log:   ---
09-28 06:52:41.610  5634  5680 I jxcore-log: 
09-28 06:52:41.610  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.610  5634  5680 I jxcore-log: 
09-28 06:52:41.610  5634  5680 I jxcore-log:   ...
09-28 06:52:41.610  5634  5680 I jxcore-log: 
,09-28 06:52:41.611  5634  5680 I jxcore-log: not ok 394 test exited without ending
09-28 06:52:41.611  5634  5680 I jxcore-log: 
09-28 06:52:41.611  5634  5680 I jxcore-log:   ---
09-28 06:52:41.611  5634  5680 I jxcore-log: 
09-28 06:52:41.611  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.611  5634  5680 I jxcore-log: 
09-28 06:52:41.611  5634  5680 I jxcore-log:   ...
09-28 06:52:41.611  5634  5680 I jxcore-log: 
,09-28 06:52:41.612  5634  5680 I jxcore-log: not ok 395 test exited without ending
09-28 06:52:41.612  5634  5680 I jxcore-log: 
09-28 06:52:41.612  5634  5680 I jxcore-log:   ---
09-28 06:52:41.612  5634  5680 I jxcore-log: 
09-28 06:52:41.612  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.612  5634  5680 I jxcore-log: 
,09-28 06:52:41.612  5634  5680 I jxcore-log:   ...
09-28 06:52:41.612  5634  5680 I jxcore-log: 
09-28 06:52:41.613  5634  5680 I jxcore-log: not ok 396 test exited without ending
09-28 06:52:41.613  5634  5680 I jxcore-log: 
09-28 06:52:41.613  5634  5680 I jxcore-log:   ---
09-28 06:52:41.613  5634  5680 I jxcore-log: 
,09-28 06:52:41.613  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.613  5634  5680 I jxcore-log: 
09-28 06:52:41.613  5634  5680 I jxcore-log:   ...
09-28 06:52:41.613  5634  5680 I jxcore-log: 
09-28 06:52:41.614  5634  5680 I jxcore-log: not ok 397 test exited without ending
09-28 06:52:41.614  5634  5680 I jxcore-log: 
09-28 06:52:41.614  5634  5680 I jxcore-log:   ---
09-28 06:52:41.614  5634  5680 I jxcore-log: 
,09-28 06:52:41.614  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.614  5634  5680 I jxcore-log: 
09-28 06:52:41.614  5634  5680 I jxcore-log:   ...
09-28 06:52:41.614  5634  5680 I jxcore-log: 
,09-28 06:52:41.615  5634  5680 I jxcore-log: not ok 398 test exited without ending
09-28 06:52:41.615  5634  5680 I jxcore-log: 
09-28 06:52:41.615  5634  5680 I jxcore-log:   ---
09-28 06:52:41.615  5634  5680 I jxcore-log: 
09-28 06:52:41.615  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.615  5634  5680 I jxcore-log: 
09-28 06:52:41.615  5634  5680 I jxcore-log:   ...
09-28 06:52:41.615  5634  5680 I jxcore-log: 
,09-28 06:52:41.616  5634  5680 I jxcore-log: not ok 399 test exited without ending
09-28 06:52:41.616  5634  5680 I jxcore-log: 
09-28 06:52:41.616  5634  5680 I jxcore-log:   ---
09-28 06:52:41.616  5634  5680 I jxcore-log: 
09-28 06:52:41.616  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.616  5634  5680 I jxcore-log: 
09-28 06:52:41.616  5634  5680 I jxcore-log:   ...
09-28 06:52:41.616  5634  5680 I jxcore-log: 
,09-28 06:52:41.617  5634  5680 I jxcore-log: not ok 400 test exited without ending
09-28 06:52:41.617  5634  5680 I jxcore-log: 
09-28 06:52:41.617  5634  5680 I jxcore-log:   ---
09-28 06:52:41.617  5634  5680 I jxcore-log: 
09-28 06:52:41.617  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.617  5634  5680 I jxcore-log: 
09-28 06:52:41.617  5634  5680 I jxcore-log:   ...
09-28 06:52:41.617  5634  5680 I jxcore-log: 
,09-28 06:52:41.618  5634  5680 I jxcore-log: not ok 401 test exited without ending
09-28 06:52:41.618  5634  5680 I jxcore-log: 
09-28 06:52:41.618  5634  5680 I jxcore-log:   ---
09-28 06:52:41.618  5634  5680 I jxcore-log: 
09-28 06:52:41.618  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.618  5634  5680 I jxcore-log: 
,09-28 06:52:41.618  5634  5680 I jxcore-log:   ...
09-28 06:52:41.618  5634  5680 I jxcore-log: 
,09-28 06:52:41.619  5634  5680 I jxcore-log: not ok 402 test exited without ending
09-28 06:52:41.619  5634  5680 I jxcore-log: 
09-28 06:52:41.619  5634  5680 I jxcore-log:   ---
09-28 06:52:41.619  5634  5680 I jxcore-log: 
09-28 06:52:41.619  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.619  5634  5680 I jxcore-log: 
09-28 06:52:41.619  5634  5680 I jxcore-log:   ...
09-28 06:52:41.619  5634  5680 I jxcore-log: 
,09-28 06:52:41.620  5634  5680 I jxcore-log: not ok 403 test exited without ending
09-28 06:52:41.620  5634  5680 I jxcore-log: 
09-28 06:52:41.620  5634  5680 I jxcore-log:   ---
09-28 06:52:41.620  5634  5680 I jxcore-log: 
09-28 06:52:41.620  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.620  5634  5680 I jxcore-log: 
,09-28 06:52:41.620  5634  5680 I jxcore-log:   ...
09-28 06:52:41.620  5634  5680 I jxcore-log: 
,09-28 06:52:41.629  5634  5680 I jxcore-log: not ok 404 test exited without ending
09-28 06:52:41.629  5634  5680 I jxcore-log: 
,09-28 06:52:41.630  5634  5680 I jxcore-log:   ---
09-28 06:52:41.630  5634  5680 I jxcore-log: 
09-28 06:52:41.630  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.630  5634  5680 I jxcore-log: 
09-28 06:52:41.630  5634  5680 I jxcore-log:   ...
09-28 06:52:41.630  5634  5680 I jxcore-log: 
,09-28 06:52:41.630  5634  5680 I jxcore-log: not ok 405 test exited without ending
09-28 06:52:41.630  5634  5680 I jxcore-log: 
09-28 06:52:41.631  5634  5680 I jxcore-log:   ---
09-28 06:52:41.631  5634  5680 I jxcore-log: 
09-28 06:52:41.631  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.631  5634  5680 I jxcore-log: 
09-28 06:52:41.631  5634  5680 I jxcore-log:   ...
09-28 06:52:41.631  5634  5680 I jxcore-log: 
,09-28 06:52:41.632  5634  5680 I jxcore-log: not ok 406 test exited without ending
09-28 06:52:41.632  5634  5680 I jxcore-log: 
09-28 06:52:41.632  5634  5680 I jxcore-log:   ---
09-28 06:52:41.632  5634  5680 I jxcore-log: 
09-28 06:52:41.632  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.632  5634  5680 I jxcore-log: 
09-28 06:52:41.632  5634  5680 I jxcore-log:   ...
09-28 06:52:41.632  5634  5680 I jxcore-log: 
,09-28 06:52:41.632  5634  5680 I jxcore-log: not ok 407 test exited without ending
09-28 06:52:41.632  5634  5680 I jxcore-log: 
09-28 06:52:41.633  5634  5680 I jxcore-log:   ---
09-28 06:52:41.633  5634  5680 I jxcore-log: 
09-28 06:52:41.633  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.633  5634  5680 I jxcore-log: 
09-28 06:52:41.633  5634  5680 I jxcore-log:   ...
09-28 06:52:41.633  5634  5680 I jxcore-log: 
,09-28 06:52:41.633  5634  5680 I jxcore-log: not ok 408 test exited without ending
09-28 06:52:41.633  5634  5680 I jxcore-log: 
,09-28 06:52:41.633  5634  5680 I jxcore-log:   ---
09-28 06:52:41.633  5634  5680 I jxcore-log: 
09-28 06:52:41.634  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.634  5634  5680 I jxcore-log: 
09-28 06:52:41.634  5634  5680 I jxcore-log:   ...
09-28 06:52:41.634  5634  5680 I jxcore-log: 
09-28 06:52:41.634  5634  5680 I jxcore-log: not ok 409 test exited without ending
09-28 06:52:41.634  5634  5680 I jxcore-log: 
09-28 06:52:41.635  5634  5680 I jxcore-log:   ---
09-28 06:52:41.635  5634  5680 I jxcore-log: 
,09-28 06:52:41.635  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.635  5634  5680 I jxcore-log: 
09-28 06:52:41.635  5634  5680 I jxcore-log:   ...
09-28 06:52:41.635  5634  5680 I jxcore-log: 
09-28 06:52:41.635  5634  5680 I jxcore-log: not ok 410 test exited without ending
09-28 06:52:41.635  5634  5680 I jxcore-log: 
09-28 06:52:41.635  5634  5680 I jxcore-log:   ---
09-28 06:52:41.635  5634  5680 I jxcore-log: 
,09-28 06:52:41.635  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.635  5634  5680 I jxcore-log: 
09-28 06:52:41.635  5634  5680 I jxcore-log:   ...
09-28 06:52:41.635  5634  5680 I jxcore-log: 
09-28 06:52:41.636  5634  5680 I jxcore-log: not ok 411 test exited without ending
09-28 06:52:41.636  5634  5680 I jxcore-log: 
09-28 06:52:41.636  5634  5680 I jxcore-log:   ---
09-28 06:52:41.636  5634  5680 I jxcore-log: 
09-28 06:52:41.636  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.636  5634  5680 I jxcore-log: 
,09-28 06:52:41.636  5634  5680 I jxcore-log:   ...
09-28 06:52:41.636  5634  5680 I jxcore-log: 
,09-28 06:52:41.637  5634  5680 I jxcore-log: not ok 412 test exited without ending
09-28 06:52:41.637  5634  5680 I jxcore-log: 
,09-28 06:52:41.639  5634  5680 I jxcore-log:   ---
09-28 06:52:41.639  5634  5680 I jxcore-log: 
09-28 06:52:41.639  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.639  5634  5680 I jxcore-log: 
09-28 06:52:41.639  5634  5680 I jxcore-log:   ...
09-28 06:52:41.639  5634  5680 I jxcore-log: 
,09-28 06:52:41.640  5634  5680 I jxcore-log: not ok 413 test exited without ending
09-28 06:52:41.640  5634  5680 I jxcore-log: 
09-28 06:52:41.640  5634  5680 I jxcore-log:   ---
09-28 06:52:41.640  5634  5680 I jxcore-log: 
09-28 06:52:41.640  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.640  5634  5680 I jxcore-log: 
09-28 06:52:41.640  5634  5680 I jxcore-log:   ...
09-28 06:52:41.640  5634  5680 I jxcore-log: 
,09-28 06:52:41.645  5634  5680 I jxcore-log: not ok 414 test exited without ending
09-28 06:52:41.645  5634  5680 I jxcore-log: 
,09-28 06:52:41.646  5634  5680 I jxcore-log:   ---
09-28 06:52:41.646  5634  5680 I jxcore-log: 
09-28 06:52:41.646  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.646  5634  5680 I jxcore-log: 
09-28 06:52:41.646  5634  5680 I jxcore-log:   ...
09-28 06:52:41.646  5634  5680 I jxcore-log: 
,09-28 06:52:41.648  5634  5680 I jxcore-log: not ok 415 test exited without ending
09-28 06:52:41.648  5634  5680 I jxcore-log: 
,09-28 06:52:41.648  5634  5680 I jxcore-log:   ---
09-28 06:52:41.648  5634  5680 I jxcore-log: 
09-28 06:52:41.648  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.648  5634  5680 I jxcore-log: 
09-28 06:52:41.648  5634  5680 I jxcore-log:   ...
09-28 06:52:41.648  5634  5680 I jxcore-log: 
09-28 06:52:41.649  5634  5680 I jxcore-log: not ok 416 test exited without ending
09-28 06:52:41.649  5634  5680 I jxcore-log: 
09-28 06:52:41.650  5634  5680 I jxcore-log:   ---
09-28 06:52:41.650  5634  5680 I jxcore-log: 
,09-28 06:52:41.650  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.650  5634  5680 I jxcore-log: 
09-28 06:52:41.650  5634  5680 I jxcore-log:   ...
09-28 06:52:41.650  5634  5680 I jxcore-log: 
09-28 06:52:41.650  5634  5680 I jxcore-log: not ok 417 test exited without ending
09-28 06:52:41.650  5634  5680 I jxcore-log: 
,09-28 06:52:41.650  5634  5680 I jxcore-log:   ---
09-28 06:52:41.650  5634  5680 I jxcore-log: 
09-28 06:52:41.655  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.655  5634  5680 I jxcore-log: 
09-28 06:52:41.655  5634  5680 I jxcore-log:   ...
09-28 06:52:41.655  5634  5680 I jxcore-log: 
,09-28 06:52:41.656  5634  5680 I jxcore-log: not ok 418 test exited without ending
09-28 06:52:41.656  5634  5680 I jxcore-log: 
09-28 06:52:41.656  5634  5680 I jxcore-log:   ---
09-28 06:52:41.656  5634  5680 I jxcore-log: 
09-28 06:52:41.656  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.656  5634  5680 I jxcore-log: 
09-28 06:52:41.656  5634  5680 I jxcore-log:   ...
09-28 06:52:41.656  5634  5680 I jxcore-log: 
09-28 06:52:41.657  5634  5680 I jxcore-log: not ok 419 test exited without ending
09-28 06:52:41.657  5634  5680 I jxcore-log: 
09-28 06:52:41.657  5634  5680 I jxcore-log:   ---
09-28 06:52:41.657  5634  5680 I jxcore-log: 
,09-28 06:52:41.657  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.657  5634  5680 I jxcore-log: 
09-28 06:52:41.657  5634  5680 I jxcore-log:   ...
09-28 06:52:41.657  5634  5680 I jxcore-log: 
09-28 06:52:41.658  5634  5680 I jxcore-log: not ok 420 test exited without ending
09-28 06:52:41.658  5634  5680 I jxcore-log: 
09-28 06:52:41.658  5634  5680 I jxcore-log:   ---
09-28 06:52:41.658  5634  5680 I jxcore-log: 
09-28 06:52:41.658  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.658  5634  5680 I jxcore-log: 
,09-28 06:52:41.658  5634  5680 I jxcore-log:   ...
09-28 06:52:41.658  5634  5680 I jxcore-log: 
09-28 06:52:41.658  5634  5680 I jxcore-log: not ok 421 test exited without ending
09-28 06:52:41.658  5634  5680 I jxcore-log: 
09-28 06:52:41.658  5634  5680 I jxcore-log:   ---
09-28 06:52:41.658  5634  5680 I jxcore-log: 
09-28 06:52:41.658  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.658  5634  5680 I jxcore-log: 
09-28 06:52:41.659  5634  5680 I jxcore-log:   ...
09-28 06:52:41.659  5634  5680 I jxcore-log: 
,09-28 06:52:41.659  5634  5680 I jxcore-log: not ok 422 test exited without ending
09-28 06:52:41.659  5634  5680 I jxcore-log: 
09-28 06:52:41.659  5634  5680 I jxcore-log:   ---
09-28 06:52:41.659  5634  5680 I jxcore-log: 
09-28 06:52:41.659  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.659  5634  5680 I jxcore-log: 
09-28 06:52:41.659  5634  5680 I jxcore-log:   ...
09-28 06:52:41.659  5634  5680 I jxcore-log: 
09-28 06:52:41.660  5634  5680 I jxcore-log: not ok 423 test exited without ending
09-28 06:52:41.660  5634  5680 I jxcore-log: 
09-28 06:52:41.660  5634  5680 I jxcore-log:   ---
09-28 06:52:41.660  5634  5680 I jxcore-log: 
,09-28 06:52:41.660  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.660  5634  5680 I jxcore-log: 
09-28 06:52:41.660  5634  5680 I jxcore-log:   ...
09-28 06:52:41.660  5634  5680 I jxcore-log: 
09-28 06:52:41.661  5634  5680 I jxcore-log: not ok 424 test exited without ending
09-28 06:52:41.661  5634  5680 I jxcore-log: 
09-28 06:52:41.661  5634  5680 I jxcore-log:   ---
09-28 06:52:41.661  5634  5680 I jxcore-log: 
09-28 06:52:41.661  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.661  5634  5680 I jxcore-log: 
09-28 06:52:41.661  5634  5680 I jxcore-log:   ...
09-28 06:52:41.661  5634  5680 I jxcore-log: 
,09-28 06:52:41.662  5634  5680 I jxcore-log: not ok 425 test exited without ending
09-28 06:52:41.662  5634  5680 I jxcore-log: 
09-28 06:52:41.662  5634  5680 I jxcore-log:   ---
09-28 06:52:41.662  5634  5680 I jxcore-log: 
09-28 06:52:41.662  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.662  5634  5680 I jxcore-log: 
09-28 06:52:41.662  5634  5680 I jxcore-log:   ...
09-28 06:52:41.662  5634  5680 I jxcore-log: 
09-28 06:52:41.663  5634  5680 I jxcore-log: not ok 426 test exited without ending
09-28 06:52:41.663  5634  5680 I jxcore-log: 
09-28 06:52:41.663  5634  5680 I jxcore-log:   ---
09-28 06:52:41.663  5634  5680 I jxcore-log: 
,09-28 06:52:41.663  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.663  5634  5680 I jxcore-log: 
09-28 06:52:41.663  5634  5680 I jxcore-log:   ...
09-28 06:52:41.663  5634  5680 I jxcore-log: 
09-28 06:52:41.663  5634  5680 I jxcore-log: not ok 427 test exited without ending
09-28 06:52:41.663  5634  5680 I jxcore-log: 
09-28 06:52:41.664  5634  5680 I jxcore-log:   ---
09-28 06:52:41.664  5634  5680 I jxcore-log: 
09-28 06:52:41.664  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.664  5634  5680 I jxcore-log: 
,09-28 06:52:41.664  5634  5680 I jxcore-log:   ...
09-28 06:52:41.664  5634  5680 I jxcore-log: 
09-28 06:52:41.664  5634  5680 I jxcore-log: not ok 428 test exited without ending
09-28 06:52:41.664  5634  5680 I jxcore-log: 
09-28 06:52:41.664  5634  5680 I jxcore-log:   ---
09-28 06:52:41.664  5634  5680 I jxcore-log: 
09-28 06:52:41.664  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.664  5634  5680 I jxcore-log: 
09-28 06:52:41.665  5634  5680 I jxcore-log:   ...
09-28 06:52:41.665  5634  5680 I jxcore-log: 
09-28 06:52:41.665  5634  5680 I jxcore-log: not ok 429 test exited without ending
09-28 06:52:41.665  5634  5680 I jxcore-log: 
,09-28 06:52:41.665  5634  5680 I jxcore-log:   ---
09-28 06:52:41.665  5634  5680 I jxcore-log: 
09-28 06:52:41.665  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.665  5634  5680 I jxcore-log: 
09-28 06:52:41.665  5634  5680 I jxcore-log:   ...
09-28 06:52:41.665  5634  5680 I jxcore-log: 
09-28 06:52:41.666  5634  5680 I jxcore-log: not ok 430 test exited without ending
09-28 06:52:41.666  5634  5680 I jxcore-log: 
09-28 06:52:41.666  5634  5680 I jxcore-log:   ---
09-28 06:52:41.666  5634  5680 I jxcore-log: 
,09-28 06:52:41.666  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.666  5634  5680 I jxcore-log: 
09-28 06:52:41.666  5634  5680 I jxcore-log:   ...
09-28 06:52:41.666  5634  5680 I jxcore-log: 
09-28 06:52:41.667  5634  5680 I jxcore-log: not ok 431 test exited without ending
09-28 06:52:41.667  5634  5680 I jxcore-log: 
09-28 06:52:41.667  5634  5680 I jxcore-log:   ---
09-28 06:52:41.667  5634  5680 I jxcore-log: 
09-28 06:52:41.667  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.667  5634  5680 I jxcore-log: 
09-28 06:52:41.667  5634  5680 I jxcore-log:   ...
09-28 06:52:41.667  5634  5680 I jxcore-log: 
09-28 06:52:41.668  5634  5680 I jxcore-log: not ok 432 test exited without ending
09-28 06:52:41.668  5634  5680 I jxcore-log: 
,09-28 06:52:41.668  5634  5680 I jxcore-log:   ---
09-28 06:52:41.668  5634  5680 I jxcore-log: 
09-28 06:52:41.668  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.668  5634  5680 I jxcore-log: 
09-28 06:52:41.668  5634  5680 I jxcore-log:   ...
09-28 06:52:41.668  5634  5680 I jxcore-log: 
09-28 06:52:41.669  5634  5680 I jxcore-log: not ok 433 test exited without ending
09-28 06:52:41.669  5634  5680 I jxcore-log: 
09-28 06:52:41.669  5634  5680 I jxcore-log:   ---
09-28 06:52:41.669  5634  5680 I jxcore-log: 
09-28 06:52:41.669  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.669  5634  5680 I jxcore-log: 
09-28 06:52:41.669  5634  5680 I jxcore-log:   ...
09-28 06:52:41.669  5634  5680 I jxcore-log: 
09-28 06:52:41.670  5634  5680 I jxcore-log: not ok 434 test exited without ending
09-28 06:52:41.670  5634  5680 I jxcore-log: 
09-28 06:52:41.670  5634  5680 I jxcore-log:   ---
09-28 06:52:41.670  5634  5680 I jxcore-log: 
09-28 06:52:41.670  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.670  5634  5680 I jxcore-log: 
09-28 06:52:41.670  5634  5680 I jxcore-log:   ...
09-28 06:52:41.670  5634  5680 I jxcore-log: 
,09-28 06:52:41.671  5634  5680 I jxcore-log: not ok 435 test exited without ending
09-28 06:52:41.671  5634  5680 I jxcore-log: 
09-28 06:52:41.671  5634  5680 I jxcore-log:   ---
09-28 06:52:41.671  5634  5680 I jxcore-log: 
09-28 06:52:41.671  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.671  5634  5680 I jxcore-log: 
09-28 06:52:41.671  5634  5680 I jxcore-log:   ...
09-28 06:52:41.671  5634  5680 I jxcore-log: 
09-28 06:52:41.671  5634  5680 I jxcore-log: not ok 436 test exited without ending
09-28 06:52:41.671  5634  5680 I jxcore-log: 
09-28 06:52:41.672  5634  5680 I jxcore-log:   ---
09-28 06:52:41.672  5634  5680 I jxcore-log: 
09-28 06:52:41.672  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.672  5634  5680 I jxcore-log: 
,09-28 06:52:41.672  5634  5680 I jxcore-log:   ...
09-28 06:52:41.672  5634  5680 I jxcore-log: 
09-28 06:52:41.672  5634  5680 I jxcore-log: not ok 437 test exited without ending
09-28 06:52:41.672  5634  5680 I jxcore-log: 
09-28 06:52:41.672  5634  5680 I jxcore-log:   ---
09-28 06:52:41.672  5634  5680 I jxcore-log: 
09-28 06:52:41.673  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.673  5634  5680 I jxcore-log: 
09-28 06:52:41.673  5634  5680 I jxcore-log:   ...
09-28 06:52:41.673  5634  5680 I jxcore-log: 
09-28 06:52:41.673  5634  5680 I jxcore-log: not ok 438 test exited without ending
09-28 06:52:41.673  5634  5680 I jxcore-log: 
09-28 06:52:41.673  5634  5680 I jxcore-log:   ---
09-28 06:52:41.673  5634  5680 I jxcore-log: 
09-28 06:52:41.673  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.673  5634  5680 I jxcore-log: 
09-28 06:52:41.674  5634  5680 I jxcore-log:   ...
09-28 06:52:41.674  5634  5680 I jxcore-log: 
09-28 06:52:41.674  5634  5680 I jxcore-log: not ok 439 test exited without ending
09-28 06:52:41.674  5634  5680 I jxcore-log: 
09-28 06:52:41.674  5634  5680 I jxcore-log:   ---
09-28 06:52:41.674  5634  5680 I jxcore-log: 
,09-28 06:52:41.674  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.674  5634  5680 I jxcore-log: 
09-28 06:52:41.675  5634  5680 I jxcore-log:   ...
09-28 06:52:41.675  5634  5680 I jxcore-log: 
09-28 06:52:41.675  5634  5680 I jxcore-log: not ok 440 test exited without ending
09-28 06:52:41.675  5634  5680 I jxcore-log: 
09-28 06:52:41.675  5634  5680 I jxcore-log:   ---
09-28 06:52:41.675  5634  5680 I jxcore-log: 
09-28 06:52:41.675  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.675  5634  5680 I jxcore-log: 
,09-28 06:52:41.675  5634  5680 I jxcore-log:   ...
09-28 06:52:41.675  5634  5680 I jxcore-log: 
09-28 06:52:41.676  5634  5680 I jxcore-log: not ok 441 test exited without ending
09-28 06:52:41.676  5634  5680 I jxcore-log: 
09-28 06:52:41.676  5634  5680 I jxcore-log:   ---
09-28 06:52:41.676  5634  5680 I jxcore-log: 
09-28 06:52:41.676  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.676  5634  5680 I jxcore-log: 
09-28 06:52:41.676  5634  5680 I jxcore-log:   ...
09-28 06:52:41.676  5634  5680 I jxcore-log: 
,09-28 06:52:41.677  5634  5680 I jxcore-log: not ok 442 test exited without ending
09-28 06:52:41.677  5634  5680 I jxcore-log: 
09-28 06:52:41.677  5634  5680 I jxcore-log:   ---
09-28 06:52:41.677  5634  5680 I jxcore-log: 
09-28 06:52:41.677  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.677  5634  5680 I jxcore-log: 
09-28 06:52:41.677  5634  5680 I jxcore-log:   ...
09-28 06:52:41.677  5634  5680 I jxcore-log: 
,09-28 06:52:41.678  5634  5680 I jxcore-log: not ok 443 test exited without ending
09-28 06:52:41.678  5634  5680 I jxcore-log: 
09-28 06:52:41.678  5634  5680 I jxcore-log:   ---
09-28 06:52:41.678  5634  5680 I jxcore-log: 
09-28 06:52:41.678  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.678  5634  5680 I jxcore-log: 
09-28 06:52:41.678  5634  5680 I jxcore-log:   ...
09-28 06:52:41.678  5634  5680 I jxcore-log: 
,09-28 06:52:41.679  5634  5680 I jxcore-log: not ok 444 test exited without ending
09-28 06:52:41.679  5634  5680 I jxcore-log: 
09-28 06:52:41.679  5634  5680 I jxcore-log:   ---
09-28 06:52:41.679  5634  5680 I jxcore-log: 
09-28 06:52:41.679  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.679  5634  5680 I jxcore-log: 
09-28 06:52:41.679  5634  5680 I jxcore-log:   ...
09-28 06:52:41.679  5634  5680 I jxcore-log: 
,09-28 06:52:41.680  5634  5680 I jxcore-log: not ok 445 test exited without ending
09-28 06:52:41.680  5634  5680 I jxcore-log: 
09-28 06:52:41.680  5634  5680 I jxcore-log:   ---
09-28 06:52:41.680  5634  5680 I jxcore-log: 
09-28 06:52:41.680  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.680  5634  5680 I jxcore-log: 
09-28 06:52:41.680  5634  5680 I jxcore-log:   ...
09-28 06:52:41.680  5634  5680 I jxcore-log: 
,09-28 06:52:41.681  5634  5680 I jxcore-log: not ok 446 test exited without ending
09-28 06:52:41.681  5634  5680 I jxcore-log: 
09-28 06:52:41.681  5634  5680 I jxcore-log:   ---
09-28 06:52:41.681  5634  5680 I jxcore-log: 
09-28 06:52:41.681  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.681  5634  5680 I jxcore-log: 
09-28 06:52:41.681  5634  5680 I jxcore-log:   ...
09-28 06:52:41.681  5634  5680 I jxcore-log: 
,09-28 06:52:41.682  5634  5680 I jxcore-log: not ok 447 test exited without ending
09-28 06:52:41.682  5634  5680 I jxcore-log: 
09-28 06:52:41.682  5634  5680 I jxcore-log:   ---
09-28 06:52:41.682  5634  5680 I jxcore-log: 
09-28 06:52:41.682  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.682  5634  5680 I jxcore-log: 
09-28 06:52:41.682  5634  5680 I jxcore-log:   ...
09-28 06:52:41.682  5634  5680 I jxcore-log: 
09-28 06:52:41.683  5634  5680 I jxcore-log: not ok 448 test exited without ending
09-28 06:52:41.683  5634  5680 I jxcore-log: 
09-28 06:52:41.683  5634  5680 I jxcore-log:   ---
09-28 06:52:41.683  5634  5680 I jxcore-log: 
09-28 06:52:41.683  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.683  5634  5680 I jxcore-log: 
09-28 06:52:41.683  5634  5680 I jxcore-log:   ...
09-28 06:52:41.683  5634  5680 I jxcore-log: 
09-28 06:52:41.684  5634  5680 I jxcore-log: not ok 449 test exited without ending
09-28 06:52:41.684  5634  5680 I jxcore-log: 
09-28 06:52:41.684  5634  5680 I jxcore-log:   ---
09-28 06:52:41.684  5634  5680 I jxcore-log: 
,09-28 06:52:41.684  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.684  5634  5680 I jxcore-log: 
09-28 06:52:41.684  5634  5680 I jxcore-log:   ...
09-28 06:52:41.684  5634  5680 I jxcore-log: 
09-28 06:52:41.685  5634  5680 I jxcore-log: not ok 450 test exited without ending
09-28 06:52:41.685  5634  5680 I jxcore-log: 
09-28 06:52:41.685  5634  5680 I jxcore-log:   ---
09-28 06:52:41.685  5634  5680 I jxcore-log: 
09-28 06:52:41.685  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.685  5634  5680 I jxcore-log: 
09-28 06:52:41.685  5634  5680 I jxcore-log:   ...
09-28 06:52:41.685  5634  5680 I jxcore-log: 
,09-28 06:52:41.686  5634  5680 I jxcore-log: not ok 451 test exited without ending
09-28 06:52:41.686  5634  5680 I jxcore-log: 
09-28 06:52:41.686  5634  5680 I jxcore-log:   ---
09-28 06:52:41.686  5634  5680 I jxcore-log: 
09-28 06:52:41.686  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.686  5634  5680 I jxcore-log: 
09-28 06:52:41.686  5634  5680 I jxcore-log:   ...
09-28 06:52:41.686  5634  5680 I jxcore-log: 
,09-28 06:52:41.686  5634  5680 I jxcore-log: not ok 452 test exited without ending
09-28 06:52:41.686  5634  5680 I jxcore-log: 
09-28 06:52:41.686  5634  5680 I jxcore-log:   ---
09-28 06:52:41.686  5634  5680 I jxcore-log: 
09-28 06:52:41.687  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.687  5634  5680 I jxcore-log: 
09-28 06:52:41.687  5634  5680 I jxcore-log:   ...
09-28 06:52:41.687  5634  5680 I jxcore-log: 
09-28 06:52:41.687  5634  5680 I jxcore-log: not ok 453 test exited without ending
09-28 06:52:41.687  5634  5680 I jxcore-log: 
,09-28 06:52:41.687  5634  5680 I jxcore-log:   ---
09-28 06:52:41.687  5634  5680 I jxcore-log: 
09-28 06:52:41.687  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.687  5634  5680 I jxcore-log: 
09-28 06:52:41.688  5634  5680 I jxcore-log:   ...
09-28 06:52:41.688  5634  5680 I jxcore-log: 
09-28 06:52:41.688  5634  5680 I jxcore-log: not ok 454 test exited without ending
09-28 06:52:41.688  5634  5680 I jxcore-log: 
09-28 06:52:41.688  5634  5680 I jxcore-log:   ---
09-28 06:52:41.688  5634  5680 I jxcore-log: 
,09-28 06:52:41.688  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.688  5634  5680 I jxcore-log: 
09-28 06:52:41.689  5634  5680 I jxcore-log:   ...
09-28 06:52:41.689  5634  5680 I jxcore-log: 
09-28 06:52:41.689  5634  5680 I jxcore-log: not ok 455 test exited without ending
09-28 06:52:41.689  5634  5680 I jxcore-log: 
09-28 06:52:41.689  5634  5680 I jxcore-log:   ---
09-28 06:52:41.689  5634  5680 I jxcore-log: 
,09-28 06:52:41.689  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.689  5634  5680 I jxcore-log: 
09-28 06:52:41.690  5634  5680 I jxcore-log:   ...
09-28 06:52:41.690  5634  5680 I jxcore-log: 
09-28 06:52:41.690  5634  5680 I jxcore-log: not ok 456 test exited without ending
09-28 06:52:41.690  5634  5680 I jxcore-log: 
09-28 06:52:41.690  5634  5680 I jxcore-log:   ---
09-28 06:52:41.690  5634  5680 I jxcore-log: 
,09-28 06:52:41.690  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.690  5634  5680 I jxcore-log: 
09-28 06:52:41.690  5634  5680 I jxcore-log:   ...
09-28 06:52:41.690  5634  5680 I jxcore-log: 
09-28 06:52:41.691  5634  5680 I jxcore-log: not ok 457 test exited without ending
09-28 06:52:41.691  5634  5680 I jxcore-log: 
09-28 06:52:41.691  5634  5680 I jxcore-log:   ---
09-28 06:52:41.691  5634  5680 I jxcore-log: 
,09-28 06:52:41.691  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.691  5634  5680 I jxcore-log: 
09-28 06:52:41.691  5634  5680 I jxcore-log:   ...
09-28 06:52:41.691  5634  5680 I jxcore-log: 
09-28 06:52:41.692  5634  5680 I jxcore-log: not ok 458 test exited without ending
09-28 06:52:41.692  5634  5680 I jxcore-log: 
09-28 06:52:41.692  5634  5680 I jxcore-log:   ---
09-28 06:52:41.692  5634  5680 I jxcore-log: 
,09-28 06:52:41.692  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.692  5634  5680 I jxcore-log: 
09-28 06:52:41.692  5634  5680 I jxcore-log:   ...
09-28 06:52:41.692  5634  5680 I jxcore-log: 
09-28 06:52:41.693  5634  5680 I jxcore-log: not ok 459 test exited without ending
09-28 06:52:41.693  5634  5680 I jxcore-log: 
09-28 06:52:41.693  5634  5680 I jxcore-log:   ---
09-28 06:52:41.693  5634  5680 I jxcore-log: 
09-28 06:52:41.693  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.693  5634  5680 I jxcore-log: 
,09-28 06:52:41.693  5634  5680 I jxcore-log:   ...
09-28 06:52:41.693  5634  5680 I jxcore-log: 
09-28 06:52:41.694  5634  5680 I jxcore-log: not ok 460 test exited without ending
09-28 06:52:41.694  5634  5680 I jxcore-log: 
09-28 06:52:41.694  5634  5680 I jxcore-log:   ---
09-28 06:52:41.694  5634  5680 I jxcore-log: 
09-28 06:52:41.694  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.694  5634  5680 I jxcore-log: 
09-28 06:52:41.694  5634  5680 I jxcore-log:   ...
09-28 06:52:41.694  5634  5680 I jxcore-log: 
,09-28 06:52:41.695  5634  5680 I jxcore-log: not ok 461 test exited without ending
09-28 06:52:41.695  5634  5680 I jxcore-log: 
09-28 06:52:41.695  5634  5680 I jxcore-log:   ---
09-28 06:52:41.695  5634  5680 I jxcore-log: 
09-28 06:52:41.695  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.695  5634  5680 I jxcore-log: 
09-28 06:52:41.695  5634  5680 I jxcore-log:   ...
09-28 06:52:41.695  5634  5680 I jxcore-log: 
,09-28 06:52:41.696  5634  5680 I jxcore-log: not ok 462 test exited without ending
09-28 06:52:41.696  5634  5680 I jxcore-log: 
09-28 06:52:41.696  5634  5680 I jxcore-log:   ---
09-28 06:52:41.696  5634  5680 I jxcore-log: 
09-28 06:52:41.696  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.696  5634  5680 I jxcore-log: 
09-28 06:52:41.696  5634  5680 I jxcore-log:   ...
09-28 06:52:41.696  5634  5680 I jxcore-log: 
,09-28 06:52:41.697  5634  5680 I jxcore-log: not ok 463 test exited without ending
09-28 06:52:41.697  5634  5680 I jxcore-log: 
09-28 06:52:41.697  5634  5680 I jxcore-log:   ---
09-28 06:52:41.697  5634  5680 I jxcore-log: 
09-28 06:52:41.697  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.697  5634  5680 I jxcore-log: 
09-28 06:52:41.697  5634  5680 I jxcore-log:   ...
09-28 06:52:41.697  5634  5680 I jxcore-log: 
,09-28 06:52:41.697  5634  5680 I jxcore-log: not ok 464 test exited without ending
09-28 06:52:41.697  5634  5680 I jxcore-log: 
09-28 06:52:41.698  5634  5680 I jxcore-log:   ---
09-28 06:52:41.698  5634  5680 I jxcore-log: 
09-28 06:52:41.698  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.698  5634  5680 I jxcore-log: 
09-28 06:52:41.698  5634  5680 I jxcore-log:   ...
09-28 06:52:41.698  5634  5680 I jxcore-log: 
,09-28 06:52:41.698  5634  5680 I jxcore-log: not ok 465 test exited without ending
09-28 06:52:41.698  5634  5680 I jxcore-log: 
09-28 06:52:41.698  5634  5680 I jxcore-log:   ---
09-28 06:52:41.698  5634  5680 I jxcore-log: 
09-28 06:52:41.698  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.698  5634  5680 I jxcore-log: 
09-28 06:52:41.699  5634  5680 I jxcore-log:   ...
09-28 06:52:41.699  5634  5680 I jxcore-log: 
,09-28 06:52:41.699  5634  5680 I jxcore-log: not ok 466 test exited without ending
09-28 06:52:41.699  5634  5680 I jxcore-log: 
09-28 06:52:41.699  5634  5680 I jxcore-log:   ---
09-28 06:52:41.699  5634  5680 I jxcore-log: 
09-28 06:52:41.699  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.699  5634  5680 I jxcore-log: 
09-28 06:52:41.699  5634  5680 I jxcore-log:   ...
09-28 06:52:41.699  5634  5680 I jxcore-log: 
,09-28 06:52:41.700  5634  5680 I jxcore-log: not ok 467 test exited without ending
09-28 06:52:41.700  5634  5680 I jxcore-log: 
09-28 06:52:41.700  5634  5680 I jxcore-log:   ---
09-28 06:52:41.700  5634  5680 I jxcore-log: 
09-28 06:52:41.700  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.700  5634  5680 I jxcore-log: 
09-28 06:52:41.700  5634  5680 I jxcore-log:   ...
09-28 06:52:41.700  5634  5680 I jxcore-log: 
09-28 06:52:41.701  5634  5680 I jxcore-log: not ok 468 test exited without ending
09-28 06:52:41.701  5634  5680 I jxcore-log: 
,09-28 06:52:41.701  5634  5680 I jxcore-log:   ---
09-28 06:52:41.701  5634  5680 I jxcore-log: 
09-28 06:52:41.701  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.701  5634  5680 I jxcore-log: 
09-28 06:52:41.701  5634  5680 I jxcore-log:   ...
09-28 06:52:41.701  5634  5680 I jxcore-log: 
09-28 06:52:41.702  5634  5680 I jxcore-log: not ok 469 test exited without ending
09-28 06:52:41.702  5634  5680 I jxcore-log: 
09-28 06:52:41.702  5634  5680 I jxcore-log:   ---
09-28 06:52:41.702  5634  5680 I jxcore-log: 
,09-28 06:52:41.702  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.702  5634  5680 I jxcore-log: 
09-28 06:52:41.702  5634  5680 I jxcore-log:   ...
09-28 06:52:41.702  5634  5680 I jxcore-log: 
09-28 06:52:41.703  5634  5680 I jxcore-log: not ok 470 test exited without ending
09-28 06:52:41.703  5634  5680 I jxcore-log: 
09-28 06:52:41.703  5634  5680 I jxcore-log:   ---
09-28 06:52:41.703  5634  5680 I jxcore-log: 
09-28 06:52:41.703  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.703  5634  5680 I jxcore-log: 
09-28 06:52:41.703  5634  5680 I jxcore-log:   ...
09-28 06:52:41.703  5634  5680 I jxcore-log: 
,09-28 06:52:41.704  5634  5680 I jxcore-log: not ok 471 test exited without ending
09-28 06:52:41.704  5634  5680 I jxcore-log: 
09-28 06:52:41.704  5634  5680 I jxcore-log:   ---
09-28 06:52:41.704  5634  5680 I jxcore-log: 
09-28 06:52:41.704  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.704  5634  5680 I jxcore-log: 
09-28 06:52:41.704  5634  5680 I jxcore-log:   ...
09-28 06:52:41.704  5634  5680 I jxcore-log: 
,09-28 06:52:41.705  5634  5680 I jxcore-log: not ok 472 test exited without ending
09-28 06:52:41.705  5634  5680 I jxcore-log: 
09-28 06:52:41.705  5634  5680 I jxcore-log:   ---
09-28 06:52:41.705  5634  5680 I jxcore-log: 
09-28 06:52:41.705  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.705  5634  5680 I jxcore-log: 
09-28 06:52:41.705  5634  5680 I jxcore-log:   ...
09-28 06:52:41.705  5634  5680 I jxcore-log: 
09-28 06:52:41.706  5634  5680 I jxcore-log: not ok 473 test exited without ending
09-28 06:52:41.706  5634  5680 I jxcore-log: 
,09-28 06:52:41.706  5634  5680 I jxcore-log:   ---
09-28 06:52:41.706  5634  5680 I jxcore-log: 
09-28 06:52:41.706  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.706  5634  5680 I jxcore-log: 
09-28 06:52:41.706  5634  5680 I jxcore-log:   ...
09-28 06:52:41.706  5634  5680 I jxcore-log: 
09-28 06:52:41.707  5634  5680 I jxcore-log: not ok 474 test exited without ending
09-28 06:52:41.707  5634  5680 I jxcore-log: 
09-28 06:52:41.707  5634  5680 I jxcore-log:   ---
09-28 06:52:41.707  5634  5680 I jxcore-log: 
,09-28 06:52:41.707  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.707  5634  5680 I jxcore-log: 
09-28 06:52:41.707  5634  5680 I jxcore-log:   ...
09-28 06:52:41.707  5634  5680 I jxcore-log: 
09-28 06:52:41.707  5634  5680 I jxcore-log: not ok 475 test exited without ending
09-28 06:52:41.707  5634  5680 I jxcore-log: 
09-28 06:52:41.708  5634  5680 I jxcore-log:   ---
09-28 06:52:41.708  5634  5680 I jxcore-log: 
09-28 06:52:41.708  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.708  5634  5680 I jxcore-log: 
09-28 06:52:41.708  5634  5680 I jxcore-log:   ...
09-28 06:52:41.708  5634  5680 I jxcore-log: 
09-28 06:52:41.708  5634  5680 I jxcore-log: not ok 476 test exited without ending
09-28 06:52:41.708  5634  5680 I jxcore-log: 
,09-28 06:52:41.708  5634  5680 I jxcore-log:   ---
09-28 06:52:41.708  5634  5680 I jxcore-log: 
09-28 06:52:41.709  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.709  5634  5680 I jxcore-log: 
09-28 06:52:41.709  5634  5680 I jxcore-log:   ...
09-28 06:52:41.709  5634  5680 I jxcore-log: 
09-28 06:52:41.709  5634  5680 I jxcore-log: not ok 477 test exited without ending
09-28 06:52:41.709  5634  5680 I jxcore-log: 
,09-28 06:52:41.709  5634  5680 I jxcore-log:   ---
09-28 06:52:41.709  5634  5680 I jxcore-log: 
09-28 06:52:41.709  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.709  5634  5680 I jxcore-log: 
09-28 06:52:41.709  5634  5680 I jxcore-log:   ...
09-28 06:52:41.709  5634  5680 I jxcore-log: 
09-28 06:52:41.710  5634  5680 I jxcore-log: not ok 478 test exited without ending
09-28 06:52:41.710  5634  5680 I jxcore-log: 
09-28 06:52:41.710  5634  5680 I jxcore-log:   ---
09-28 06:52:41.710  5634  5680 I jxcore-log: 
09-28 06:52:41.710  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.710  5634  5680 I jxcore-log: 
09-28 06:52:41.710  5634  5680 I jxcore-log:   ...
09-28 06:52:41.710  5634  5680 I jxcore-log: 
,09-28 06:52:41.711  5634  5680 I jxcore-log: not ok 479 test exited without ending
09-28 06:52:41.711  5634  5680 I jxcore-log: 
09-28 06:52:41.711  5634  5680 I jxcore-log:   ---
09-28 06:52:41.711  5634  5680 I jxcore-log: 
09-28 06:52:41.711  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.711  5634  5680 I jxcore-log: 
09-28 06:52:41.711  5634  5680 I jxcore-log:   ...
09-28 06:52:41.711  5634  5680 I jxcore-log: 
,09-28 06:52:41.712  5634  5680 I jxcore-log: not ok 480 test exited without ending
09-28 06:52:41.712  5634  5680 I jxcore-log: 
09-28 06:52:41.712  5634  5680 I jxcore-log:   ---
09-28 06:52:41.712  5634  5680 I jxcore-log: 
09-28 06:52:41.712  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.712  5634  5680 I jxcore-log: 
09-28 06:52:41.712  5634  5680 I jxcore-log:   ...
09-28 06:52:41.712  5634  5680 I jxcore-log: 
,09-28 06:52:41.713  5634  5680 I jxcore-log: not ok 481 test exited without ending
09-28 06:52:41.713  5634  5680 I jxcore-log: 
09-28 06:52:41.713  5634  5680 I jxcore-log:   ---
09-28 06:52:41.713  5634  5680 I jxcore-log: 
09-28 06:52:41.713  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.713  5634  5680 I jxcore-log: 
,09-28 06:52:41.713  5634  5680 I jxcore-log:   ...
09-28 06:52:41.713  5634  5680 I jxcore-log: 
09-28 06:52:41.714  5634  5680 I jxcore-log: not ok 482 test exited without ending
09-28 06:52:41.714  5634  5680 I jxcore-log: 
09-28 06:52:41.714  5634  5680 I jxcore-log:   ---
09-28 06:52:41.714  5634  5680 I jxcore-log: 
09-28 06:52:41.714  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.714  5634  5680 I jxcore-log: 
,09-28 06:52:41.714  5634  5680 I jxcore-log:   ...
09-28 06:52:41.714  5634  5680 I jxcore-log: 
09-28 06:52:41.715  5634  5680 I jxcore-log: not ok 483 test exited without ending
09-28 06:52:41.715  5634  5680 I jxcore-log: 
09-28 06:52:41.715  5634  5680 I jxcore-log:   ---
09-28 06:52:41.715  5634  5680 I jxcore-log: 
09-28 06:52:41.715  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.715  5634  5680 I jxcore-log: 
09-28 06:52:41.715  5634  5680 I jxcore-log:   ...
09-28 06:52:41.715  5634  5680 I jxcore-log: 
,09-28 06:52:41.716  5634  5680 I jxcore-log: not ok 484 test exited without ending
09-28 06:52:41.716  5634  5680 I jxcore-log: 
09-28 06:52:41.716  5634  5680 I jxcore-log:   ---
09-28 06:52:41.716  5634  5680 I jxcore-log: 
09-28 06:52:41.716  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.716  5634  5680 I jxcore-log: 
09-28 06:52:41.716  5634  5680 I jxcore-log:   ...
09-28 06:52:41.716  5634  5680 I jxcore-log: 
,09-28 06:52:41.717  5634  5680 I jxcore-log: not ok 485 test exited without ending
09-28 06:52:41.717  5634  5680 I jxcore-log: 
09-28 06:52:41.717  5634  5680 I jxcore-log:   ---
09-28 06:52:41.717  5634  5680 I jxcore-log: 
09-28 06:52:41.717  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.717  5634  5680 I jxcore-log: 
09-28 06:52:41.717  5634  5680 I jxcore-log:   ...
09-28 06:52:41.717  5634  5680 I jxcore-log: 
,09-28 06:52:41.718  5634  5680 I jxcore-log: not ok 486 test exited without ending
09-28 06:52:41.718  5634  5680 I jxcore-log: 
09-28 06:52:41.718  5634  5680 I jxcore-log:   ---
09-28 06:52:41.718  5634  5680 I jxcore-log: 
09-28 06:52:41.718  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.718  5634  5680 I jxcore-log: 
09-28 06:52:41.718  5634  5680 I jxcore-log:   ...
09-28 06:52:41.718  5634  5680 I jxcore-log: 
,09-28 06:52:41.719  5634  5680 I jxcore-log: not ok 487 test exited without ending
09-28 06:52:41.719  5634  5680 I jxcore-log: 
09-28 06:52:41.719  5634  5680 I jxcore-log:   ---
09-28 06:52:41.719  5634  5680 I jxcore-log: 
09-28 06:52:41.719  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.719  5634  5680 I jxcore-log: 
09-28 06:52:41.719  5634  5680 I jxcore-log:   ...
09-28 06:52:41.719  5634  5680 I jxcore-log: 
,09-28 06:52:41.719  5634  5680 I jxcore-log: not ok 488 test exited without ending
09-28 06:52:41.719  5634  5680 I jxcore-log: 
09-28 06:52:41.720  5634  5680 I jxcore-log:   ---
09-28 06:52:41.720  5634  5680 I jxcore-log: 
09-28 06:52:41.720  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.720  5634  5680 I jxcore-log: 
09-28 06:52:41.720  5634  5680 I jxcore-log:   ...
09-28 06:52:41.720  5634  5680 I jxcore-log: 
09-28 06:52:41.720  5634  5680 I jxcore-log: not ok 489 test exited without ending
09-28 06:52:41.720  5634  5680 I jxcore-log: 
09-28 06:52:41.720  5634  5680 I jxcore-log:   ---
09-28 06:52:41.720  5634  5680 I jxcore-log: 
,09-28 06:52:41.720  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.720  5634  5680 I jxcore-log: 
09-28 06:52:41.720  5634  5680 I jxcore-log:   ...
09-28 06:52:41.720  5634  5680 I jxcore-log: 
,09-28 06:52:41.721  5634  5680 I jxcore-log: not ok 490 test exited without ending
09-28 06:52:41.721  5634  5680 I jxcore-log: 
09-28 06:52:41.721  5634  5680 I jxcore-log:   ---
09-28 06:52:41.721  5634  5680 I jxcore-log: 
09-28 06:52:41.722  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.722  5634  5680 I jxcore-log: 
09-28 06:52:41.722  5634  5680 I jxcore-log:   ...
09-28 06:52:41.722  5634  5680 I jxcore-log: 
,09-28 06:52:41.722  5634  5680 I jxcore-log: not ok 491 test exited without ending
09-28 06:52:41.722  5634  5680 I jxcore-log: 
09-28 06:52:41.722  5634  5680 I jxcore-log:   ---
09-28 06:52:41.722  5634  5680 I jxcore-log: 
09-28 06:52:41.722  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.722  5634  5680 I jxcore-log: 
09-28 06:52:41.723  5634  5680 I jxcore-log:   ...
09-28 06:52:41.723  5634  5680 I jxcore-log: 
,09-28 06:52:41.723  5634  5680 I jxcore-log: not ok 492 test exited without ending
09-28 06:52:41.723  5634  5680 I jxcore-log: 
09-28 06:52:41.723  5634  5680 I jxcore-log:   ---
09-28 06:52:41.723  5634  5680 I jxcore-log: 
09-28 06:52:41.723  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.723  5634  5680 I jxcore-log: 
09-28 06:52:41.723  5634  5680 I jxcore-log:   ...
09-28 06:52:41.723  5634  5680 I jxcore-log: 
,09-28 06:52:41.724  5634  5680 I jxcore-log: not ok 493 test exited without ending
09-28 06:52:41.724  5634  5680 I jxcore-log: 
09-28 06:52:41.724  5634  5680 I jxcore-log:   ---
09-28 06:52:41.724  5634  5680 I jxcore-log: 
09-28 06:52:41.724  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.724  5634  5680 I jxcore-log: 
,09-28 06:52:41.724  5634  5680 I jxcore-log:   ...
09-28 06:52:41.724  5634  5680 I jxcore-log: 
09-28 06:52:41.725  5634  5680 I jxcore-log: not ok 494 test exited without ending
09-28 06:52:41.725  5634  5680 I jxcore-log: 
09-28 06:52:41.725  5634  5680 I jxcore-log:   ---
09-28 06:52:41.725  5634  5680 I jxcore-log: 
09-28 06:52:41.725  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.725  5634  5680 I jxcore-log: 
,09-28 06:52:41.725  5634  5680 I jxcore-log:   ...
09-28 06:52:41.725  5634  5680 I jxcore-log: 
09-28 06:52:41.726  5634  5680 I jxcore-log: not ok 495 test exited without ending
09-28 06:52:41.726  5634  5680 I jxcore-log: 
09-28 06:52:41.726  5634  5680 I jxcore-log:   ---
09-28 06:52:41.726  5634  5680 I jxcore-log: 
09-28 06:52:41.726  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.726  5634  5680 I jxcore-log: 
,09-28 06:52:41.726  5634  5680 I jxcore-log:   ...
09-28 06:52:41.726  5634  5680 I jxcore-log: 
09-28 06:52:41.727  5634  5680 I jxcore-log: not ok 496 test exited without ending
09-28 06:52:41.727  5634  5680 I jxcore-log: 
09-28 06:52:41.727  5634  5680 I jxcore-log:   ---
09-28 06:52:41.727  5634  5680 I jxcore-log: 
09-28 06:52:41.727  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.727  5634  5680 I jxcore-log: 
09-28 06:52:41.727  5634  5680 I jxcore-log:   ...
09-28 06:52:41.727  5634  5680 I jxcore-log: 
,09-28 06:52:41.728  5634  5680 I jxcore-log: not ok 497 test exited without ending
09-28 06:52:41.728  5634  5680 I jxcore-log: 
09-28 06:52:41.728  5634  5680 I jxcore-log:   ---
09-28 06:52:41.728  5634  5680 I jxcore-log: 
09-28 06:52:41.728  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.728  5634  5680 I jxcore-log: 
09-28 06:52:41.728  5634  5680 I jxcore-log:   ...
09-28 06:52:41.728  5634  5680 I jxcore-log: 
,09-28 06:52:41.729  5634  5680 I jxcore-log: not ok 498 test exited without ending
09-28 06:52:41.729  5634  5680 I jxcore-log: 
09-28 06:52:41.729  5634  5680 I jxcore-log:   ---
09-28 06:52:41.729  5634  5680 I jxcore-log: 
09-28 06:52:41.729  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.729  5634  5680 I jxcore-log: 
09-28 06:52:41.729  5634  5680 I jxcore-log:   ...
09-28 06:52:41.729  5634  5680 I jxcore-log: 
,09-28 06:52:41.730  5634  5680 I jxcore-log: not ok 499 test exited without ending
09-28 06:52:41.730  5634  5680 I jxcore-log: 
09-28 06:52:41.730  5634  5680 I jxcore-log:   ---
09-28 06:52:41.730  5634  5680 I jxcore-log: 
09-28 06:52:41.730  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.730  5634  5680 I jxcore-log: 
,09-28 06:52:41.730  5634  5680 I jxcore-log:   ...
09-28 06:52:41.730  5634  5680 I jxcore-log: 
09-28 06:52:41.731  5634  5680 I jxcore-log: not ok 500 test exited without ending
09-28 06:52:41.731  5634  5680 I jxcore-log: 
09-28 06:52:41.731  5634  5680 I jxcore-log:   ---
09-28 06:52:41.731  5634  5680 I jxcore-log: 
,09-28 06:52:41.731  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.731  5634  5680 I jxcore-log: 
09-28 06:52:41.731  5634  5680 I jxcore-log:   ...
09-28 06:52:41.731  5634  5680 I jxcore-log: 
09-28 06:52:41.732  5634  5680 I jxcore-log: not ok 501 test exited without ending
09-28 06:52:41.732  5634  5680 I jxcore-log: 
09-28 06:52:41.732  5634  5680 I jxcore-log:   ---
09-28 06:52:41.732  5634  5680 I jxcore-log: 
09-28 06:52:41.732  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.732  5634  5680 I jxcore-log: 
,09-28 06:52:41.732  5634  5680 I jxcore-log:   ...
09-28 06:52:41.732  5634  5680 I jxcore-log: 
09-28 06:52:41.732  5634  5680 I jxcore-log: not ok 502 test exited without ending
09-28 06:52:41.732  5634  5680 I jxcore-log: 
09-28 06:52:41.733  5634  5680 I jxcore-log:   ---
09-28 06:52:41.733  5634  5680 I jxcore-log: 
,09-28 06:52:41.733  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.733  5634  5680 I jxcore-log: 
09-28 06:52:41.733  5634  5680 I jxcore-log:   ...
09-28 06:52:41.733  5634  5680 I jxcore-log: 
09-28 06:52:41.733  5634  5680 I jxcore-log: not ok 503 test exited without ending
09-28 06:52:41.733  5634  5680 I jxcore-log: 
,09-28 06:52:41.733  5634  5680 I jxcore-log:   ---
09-28 06:52:41.733  5634  5680 I jxcore-log: 
09-28 06:52:41.734  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.734  5634  5680 I jxcore-log: 
09-28 06:52:41.734  5634  5680 I jxcore-log:   ...
09-28 06:52:41.734  5634  5680 I jxcore-log: 
,09-28 06:52:41.734  5634  5680 I jxcore-log: not ok 504 test exited without ending
09-28 06:52:41.734  5634  5680 I jxcore-log: 
09-28 06:52:41.734  5634  5680 I jxcore-log:   ---
09-28 06:52:41.734  5634  5680 I jxcore-log: 
09-28 06:52:41.734  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.734  5634  5680 I jxcore-log: 
,09-28 06:52:41.735  5634  5680 I jxcore-log:   ...
09-28 06:52:41.735  5634  5680 I jxcore-log: 
09-28 06:52:41.735  5634  5680 I jxcore-log: not ok 505 test exited without ending
09-28 06:52:41.735  5634  5680 I jxcore-log: 
09-28 06:52:41.735  5634  5680 I jxcore-log:   ---
09-28 06:52:41.735  5634  5680 I jxcore-log: 
09-28 06:52:41.735  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.735  5634  5680 I jxcore-log: 
,09-28 06:52:41.735  5634  5680 I jxcore-log:   ...
09-28 06:52:41.735  5634  5680 I jxcore-log: 
09-28 06:52:41.736  5634  5680 I jxcore-log: not ok 506 test exited without ending
09-28 06:52:41.736  5634  5680 I jxcore-log: 
09-28 06:52:41.736  5634  5680 I jxcore-log:   ---
09-28 06:52:41.736  5634  5680 I jxcore-log: 
09-28 06:52:41.736  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.736  5634  5680 I jxcore-log: 
09-28 06:52:41.736  5634  5680 I jxcore-log:   ...
09-28 06:52:41.736  5634  5680 I jxcore-log: 
,09-28 06:52:41.737  5634  5680 I jxcore-log: not ok 507 test exited without ending
09-28 06:52:41.737  5634  5680 I jxcore-log: 
09-28 06:52:41.737  5634  5680 I jxcore-log:   ---
09-28 06:52:41.737  5634  5680 I jxcore-log: 
09-28 06:52:41.737  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.737  5634  5680 I jxcore-log: 
09-28 06:52:41.737  5634  5680 I jxcore-log:   ...
09-28 06:52:41.737  5634  5680 I jxcore-log: 
,09-28 06:52:41.738  5634  5680 I jxcore-log: not ok 508 test exited without ending
09-28 06:52:41.738  5634  5680 I jxcore-log: 
09-28 06:52:41.738  5634  5680 I jxcore-log:   ---
09-28 06:52:41.738  5634  5680 I jxcore-log: 
09-28 06:52:41.738  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.738  5634  5680 I jxcore-log: 
09-28 06:52:41.738  5634  5680 I jxcore-log:   ...
09-28 06:52:41.738  5634  5680 I jxcore-log: 
09-28 06:52:41.739  5634  5680 I jxcore-log: not ok 509 test exited without ending
09-28 06:52:41.739  5634  5680 I jxcore-log: 
09-28 06:52:41.739  5634  5680 I jxcore-log:   ---
09-28 06:52:41.739  5634  5680 I jxcore-log: 
,09-28 06:52:41.739  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.739  5634  5680 I jxcore-log: 
09-28 06:52:41.739  5634  5680 I jxcore-log:   ...
09-28 06:52:41.739  5634  5680 I jxcore-log: 
09-28 06:52:41.740  5634  5680 I jxcore-log: not ok 510 test exited without ending
09-28 06:52:41.740  5634  5680 I jxcore-log: 
09-28 06:52:41.740  5634  5680 I jxcore-log:   ---
09-28 06:52:41.740  5634  5680 I jxcore-log: 
09-28 06:52:41.740  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.740  5634  5680 I jxcore-log: 
09-28 06:52:41.740  5634  5680 I jxcore-log:   ...
09-28 06:52:41.740  5634  5680 I jxcore-log: 
,09-28 06:52:41.741  5634  5680 I jxcore-log: not ok 511 test exited without ending
09-28 06:52:41.741  5634  5680 I jxcore-log: 
09-28 06:52:41.741  5634  5680 I jxcore-log:   ---
09-28 06:52:41.741  5634  5680 I jxcore-log: 
,09-28 06:52:41.741  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.741  5634  5680 I jxcore-log: 
09-28 06:52:41.741  5634  5680 I jxcore-log:   ...
09-28 06:52:41.741  5634  5680 I jxcore-log: 
,09-28 06:52:41.742  5634  5680 I jxcore-log: not ok 512 test exited without ending
09-28 06:52:41.742  5634  5680 I jxcore-log: 
09-28 06:52:41.742  5634  5680 I jxcore-log:   ---
09-28 06:52:41.742  5634  5680 I jxcore-log: 
09-28 06:52:41.742  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.742  5634  5680 I jxcore-log: 
09-28 06:52:41.742  5634  5680 I jxcore-log:   ...
09-28 06:52:41.742  5634  5680 I jxcore-log: 
09-28 06:52:41.742  5634  5680 I jxcore-log: not ok 513 test exited without ending
09-28 06:52:41.742  5634  5680 I jxcore-log: 
,09-28 06:52:41.743  5634  5680 I jxcore-log:   ---
09-28 06:52:41.743  5634  5680 I jxcore-log: 
09-28 06:52:41.743  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.743  5634  5680 I jxcore-log: 
09-28 06:52:41.743  5634  5680 I jxcore-log:   ...
09-28 06:52:41.743  5634  5680 I jxcore-log: 
09-28 06:52:41.743  5634  5680 I jxcore-log: not ok 514 test exited without ending
09-28 06:52:41.743  5634  5680 I jxcore-log: 
09-28 06:52:41.744  5634  5680 I jxcore-log:   ---
09-28 06:52:41.744  5634  5680 I jxcore-log: 
09-28 06:52:41.744  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.744  5634  5680 I jxcore-log: 
09-28 06:52:41.744  5634  5680 I jxcore-log:   ...
09-28 06:52:41.744  5634  5680 I jxcore-log: 
,09-28 06:52:41.744  5634  5680 I jxcore-log: not ok 515 test exited without ending
09-28 06:52:41.744  5634  5680 I jxcore-log: 
09-28 06:52:41.745  5634  5680 I jxcore-log:   ---
09-28 06:52:41.745  5634  5680 I jxcore-log: 
09-28 06:52:41.745  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.745  5634  5680 I jxcore-log: 
09-28 06:52:41.745  5634  5680 I jxcore-log:   ...
09-28 06:52:41.745  5634  5680 I jxcore-log: 
,09-28 06:52:41.745  5634  5680 I jxcore-log: not ok 516 test exited without ending
09-28 06:52:41.745  5634  5680 I jxcore-log: 
09-28 06:52:41.745  5634  5680 I jxcore-log:   ---
09-28 06:52:41.745  5634  5680 I jxcore-log: 
09-28 06:52:41.745  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.745  5634  5680 I jxcore-log: 
09-28 06:52:41.746  5634  5680 I jxcore-log:   ...
09-28 06:52:41.746  5634  5680 I jxcore-log: 
,09-28 06:52:41.746  5634  5680 I jxcore-log: not ok 517 test exited without ending
09-28 06:52:41.746  5634  5680 I jxcore-log: 
09-28 06:52:41.746  5634  5680 I jxcore-log:   ---
09-28 06:52:41.746  5634  5680 I jxcore-log: 
09-28 06:52:41.746  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.746  5634  5680 I jxcore-log: 
09-28 06:52:41.746  5634  5680 I jxcore-log:   ...
09-28 06:52:41.746  5634  5680 I jxcore-log: 
,09-28 06:52:41.747  5634  5680 I jxcore-log: not ok 518 test exited without ending
09-28 06:52:41.747  5634  5680 I jxcore-log: 
09-28 06:52:41.747  5634  5680 I jxcore-log:   ---
09-28 06:52:41.747  5634  5680 I jxcore-log: 
09-28 06:52:41.747  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.747  5634  5680 I jxcore-log: 
,09-28 06:52:41.747  5634  5680 I jxcore-log:   ...
09-28 06:52:41.747  5634  5680 I jxcore-log: 
09-28 06:52:41.748  5634  5680 I jxcore-log: not ok 519 test exited without ending
09-28 06:52:41.748  5634  5680 I jxcore-log: 
09-28 06:52:41.748  5634  5680 I jxcore-log:   ---
09-28 06:52:41.748  5634  5680 I jxcore-log: 
09-28 06:52:41.748  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.748  5634  5680 I jxcore-log: 
,09-28 06:52:41.748  5634  5680 I jxcore-log:   ...
09-28 06:52:41.748  5634  5680 I jxcore-log: 
09-28 06:52:41.749  5634  5680 I jxcore-log: not ok 520 test exited without ending
09-28 06:52:41.749  5634  5680 I jxcore-log: 
09-28 06:52:41.749  5634  5680 I jxcore-log:   ---
09-28 06:52:41.749  5634  5680 I jxcore-log: 
09-28 06:52:41.749  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.749  5634  5680 I jxcore-log: 
,09-28 06:52:41.749  5634  5680 I jxcore-log:   ...
09-28 06:52:41.749  5634  5680 I jxcore-log: 
09-28 06:52:41.750  5634  5680 I jxcore-log: not ok 521 test exited without ending
09-28 06:52:41.750  5634  5680 I jxcore-log: 
09-28 06:52:41.750  5634  5680 I jxcore-log:   ---
09-28 06:52:41.750  5634  5680 I jxcore-log: 
,09-28 06:52:41.750  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.750  5634  5680 I jxcore-log: 
09-28 06:52:41.750  5634  5680 I jxcore-log:   ...
09-28 06:52:41.750  5634  5680 I jxcore-log: 
,09-28 06:52:41.751  5634  5680 I jxcore-log: not ok 522 test exited without ending
09-28 06:52:41.751  5634  5680 I jxcore-log: 
09-28 06:52:41.751  5634  5680 I jxcore-log:   ---
09-28 06:52:41.751  5634  5680 I jxcore-log: 
09-28 06:52:41.751  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.751  5634  5680 I jxcore-log: 
09-28 06:52:41.751  5634  5680 I jxcore-log:   ...
09-28 06:52:41.751  5634  5680 I jxcore-log: 
,09-28 06:52:41.752  5634  5680 I jxcore-log: not ok 523 test exited without ending
09-28 06:52:41.752  5634  5680 I jxcore-log: 
09-28 06:52:41.752  5634  5680 I jxcore-log:   ---
09-28 06:52:41.752  5634  5680 I jxcore-log: 
09-28 06:52:41.752  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.752  5634  5680 I jxcore-log: 
09-28 06:52:41.752  5634  5680 I jxcore-log:   ...
09-28 06:52:41.752  5634  5680 I jxcore-log: 
,09-28 06:52:41.753  5634  5680 I jxcore-log: not ok 524 test exited without ending
09-28 06:52:41.753  5634  5680 I jxcore-log: 
09-28 06:52:41.753  5634  5680 I jxcore-log:   ---
09-28 06:52:41.753  5634  5680 I jxcore-log: 
,09-28 06:52:41.753  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.753  5634  5680 I jxcore-log: 
09-28 06:52:41.753  5634  5680 I jxcore-log:   ...
09-28 06:52:41.753  5634  5680 I jxcore-log: 
,09-28 06:52:41.754  5634  5680 I jxcore-log: not ok 525 test exited without ending
09-28 06:52:41.754  5634  5680 I jxcore-log: 
09-28 06:52:41.754  5634  5680 I jxcore-log:   ---
09-28 06:52:41.754  5634  5680 I jxcore-log: 
09-28 06:52:41.754  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.754  5634  5680 I jxcore-log: 
09-28 06:52:41.754  5634  5680 I jxcore-log:   ...
09-28 06:52:41.754  5634  5680 I jxcore-log: 
,09-28 06:52:41.755  5634  5680 I jxcore-log: not ok 526 test exited without ending
09-28 06:52:41.755  5634  5680 I jxcore-log: 
09-28 06:52:41.755  5634  5680 I jxcore-log:   ---
09-28 06:52:41.755  5634  5680 I jxcore-log: 
09-28 06:52:41.755  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.755  5634  5680 I jxcore-log: 
09-28 06:52:41.755  5634  5680 I jxcore-log:   ...
09-28 06:52:41.755  5634  5680 I jxcore-log: 
,09-28 06:52:41.756  5634  5680 I jxcore-log: not ok 527 test exited without ending
09-28 06:52:41.756  5634  5680 I jxcore-log: 
09-28 06:52:41.756  5634  5680 I jxcore-log:   ---
09-28 06:52:41.756  5634  5680 I jxcore-log: 
09-28 06:52:41.756  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.756  5634  5680 I jxcore-log: 
,09-28 06:52:41.756  5634  5680 I jxcore-log:   ...
09-28 06:52:41.756  5634  5680 I jxcore-log: 
09-28 06:52:41.757  5634  5680 I jxcore-log: not ok 528 test exited without ending
09-28 06:52:41.757  5634  5680 I jxcore-log: 
09-28 06:52:41.757  5634  5680 I jxcore-log:   ---
09-28 06:52:41.757  5634  5680 I jxcore-log: 
,09-28 06:52:41.757  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.757  5634  5680 I jxcore-log: 
09-28 06:52:41.757  5634  5680 I jxcore-log:   ...
09-28 06:52:41.757  5634  5680 I jxcore-log: 
09-28 06:52:41.758  5634  5680 I jxcore-log: not ok 529 test exited without ending
09-28 06:52:41.758  5634  5680 I jxcore-log: 
09-28 06:52:41.758  5634  5680 I jxcore-log:   ---
09-28 06:52:41.758  5634  5680 I jxcore-log: 
,09-28 06:52:41.758  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.758  5634  5680 I jxcore-log: 
09-28 06:52:41.758  5634  5680 I jxcore-log:   ...
09-28 06:52:41.758  5634  5680 I jxcore-log: 
09-28 06:52:41.759  5634  5680 I jxcore-log: not ok 530 test exited without ending
09-28 06:52:41.759  5634  5680 I jxcore-log: 
09-28 06:52:41.759  5634  5680 I jxcore-log:   ---
09-28 06:52:41.759  5634  5680 I jxcore-log: 
09-28 06:52:41.759  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.759  5634  5680 I jxcore-log: 
,09-28 06:52:41.759  5634  5680 I jxcore-log:   ...
09-28 06:52:41.759  5634  5680 I jxcore-log: 
09-28 06:52:41.759  5634  5680 I jxcore-log: not ok 531 test exited without ending
09-28 06:52:41.759  5634  5680 I jxcore-log: 
09-28 06:52:41.760  5634  5680 I jxcore-log:   ---
09-28 06:52:41.760  5634  5680 I jxcore-log: 
09-28 06:52:41.760  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.760  5634  5680 I jxcore-log: 
,09-28 06:52:41.760  5634  5680 I jxcore-log:   ...
09-28 06:52:41.760  5634  5680 I jxcore-log: 
09-28 06:52:41.760  5634  5680 I jxcore-log: not ok 532 test exited without ending
09-28 06:52:41.760  5634  5680 I jxcore-log: 
09-28 06:52:41.760  5634  5680 I jxcore-log:   ---
09-28 06:52:41.760  5634  5680 I jxcore-log: 
,09-28 06:52:41.760  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.760  5634  5680 I jxcore-log: 
09-28 06:52:41.760  5634  5680 I jxcore-log:   ...
09-28 06:52:41.760  5634  5680 I jxcore-log: 
09-28 06:52:41.761  5634  5680 I jxcore-log: not ok 533 test exited without ending
09-28 06:52:41.761  5634  5680 I jxcore-log: 
,09-28 06:52:41.761  5634  5680 I jxcore-log:   ---
09-28 06:52:41.761  5634  5680 I jxcore-log: 
09-28 06:52:41.761  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.761  5634  5680 I jxcore-log: 
09-28 06:52:41.761  5634  5680 I jxcore-log:   ...
09-28 06:52:41.761  5634  5680 I jxcore-log: 
09-28 06:52:41.762  5634  5680 I jxcore-log: not ok 534 test exited without ending
09-28 06:52:41.762  5634  5680 I jxcore-log: 
,09-28 06:52:41.762  5634  5680 I jxcore-log:   ---
09-28 06:52:41.762  5634  5680 I jxcore-log: 
09-28 06:52:41.762  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.762  5634  5680 I jxcore-log: 
09-28 06:52:41.762  5634  5680 I jxcore-log:   ...
09-28 06:52:41.762  5634  5680 I jxcore-log: 
09-28 06:52:41.763  5634  5680 I jxcore-log: not ok 535 test exited without ending
09-28 06:52:41.763  5634  5680 I jxcore-log: 
,09-28 06:52:41.763  5634  5680 I jxcore-log:   ---
09-28 06:52:41.763  5634  5680 I jxcore-log: 
09-28 06:52:41.763  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.763  5634  5680 I jxcore-log: 
09-28 06:52:41.763  5634  5680 I jxcore-log:   ...
09-28 06:52:41.763  5634  5680 I jxcore-log: 
,09-28 06:52:41.764  5634  5680 I jxcore-log: not ok 536 test exited without ending
09-28 06:52:41.764  5634  5680 I jxcore-log: 
09-28 06:52:41.764  5634  5680 I jxcore-log:   ---
09-28 06:52:41.764  5634  5680 I jxcore-log: 
09-28 06:52:41.764  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.764  5634  5680 I jxcore-log: 
09-28 06:52:41.764  5634  5680 I jxcore-log:   ...
09-28 06:52:41.764  5634  5680 I jxcore-log: 
,09-28 06:52:41.764  5634  5680 I jxcore-log: not ok 537 test exited without ending
09-28 06:52:41.764  5634  5680 I jxcore-log: 
09-28 06:52:41.765  5634  5680 I jxcore-log:   ---
09-28 06:52:41.765  5634  5680 I jxcore-log: 
09-28 06:52:41.765  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.765  5634  5680 I jxcore-log: 
09-28 06:52:41.765  5634  5680 I jxcore-log:   ...
09-28 06:52:41.765  5634  5680 I jxcore-log: 
,09-28 06:52:41.765  5634  5680 I jxcore-log: not ok 538 test exited without ending
09-28 06:52:41.765  5634  5680 I jxcore-log: 
09-28 06:52:41.765  5634  5680 I jxcore-log:   ---
09-28 06:52:41.765  5634  5680 I jxcore-log: 
09-28 06:52:41.765  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.765  5634  5680 I jxcore-log: 
09-28 06:52:41.765  5634  5680 I jxcore-log:   ...
09-28 06:52:41.765  5634  5680 I jxcore-log: 
,09-28 06:52:41.766  5634  5680 I jxcore-log: not ok 539 test exited without ending
09-28 06:52:41.766  5634  5680 I jxcore-log: 
09-28 06:52:41.766  5634  5680 I jxcore-log:   ---
09-28 06:52:41.766  5634  5680 I jxcore-log: 
09-28 06:52:41.766  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.766  5634  5680 I jxcore-log: 
09-28 06:52:41.766  5634  5680 I jxcore-log:   ...
09-28 06:52:41.766  5634  5680 I jxcore-log: 
,09-28 06:52:41.767  5634  5680 I jxcore-log: not ok 540 test exited without ending
09-28 06:52:41.767  5634  5680 I jxcore-log: 
09-28 06:52:41.767  5634  5680 I jxcore-log:   ---
09-28 06:52:41.767  5634  5680 I jxcore-log: 
09-28 06:52:41.767  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.767  5634  5680 I jxcore-log: 
09-28 06:52:41.767  5634  5680 I jxcore-log:   ...
09-28 06:52:41.767  5634  5680 I jxcore-log: 
,09-28 06:52:41.768  5634  5680 I jxcore-log: not ok 541 test exited without ending
09-28 06:52:41.768  5634  5680 I jxcore-log: 
09-28 06:52:41.768  5634  5680 I jxcore-log:   ---
09-28 06:52:41.768  5634  5680 I jxcore-log: 
09-28 06:52:41.768  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.768  5634  5680 I jxcore-log: 
,09-28 06:52:41.768  5634  5680 I jxcore-log:   ...
09-28 06:52:41.768  5634  5680 I jxcore-log: 
09-28 06:52:41.769  5634  5680 I jxcore-log: not ok 542 test exited without ending
09-28 06:52:41.769  5634  5680 I jxcore-log: 
09-28 06:52:41.769  5634  5680 I jxcore-log:   ---
09-28 06:52:41.769  5634  5680 I jxcore-log: 
09-28 06:52:41.769  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.769  5634  5680 I jxcore-log: 
,09-28 06:52:41.769  5634  5680 I jxcore-log:   ...
09-28 06:52:41.769  5634  5680 I jxcore-log: 
09-28 06:52:41.770  5634  5680 I jxcore-log: not ok 543 test exited without ending
09-28 06:52:41.770  5634  5680 I jxcore-log: 
09-28 06:52:41.770  5634  5680 I jxcore-log:   ---
09-28 06:52:41.770  5634  5680 I jxcore-log: 
09-28 06:52:41.770  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.770  5634  5680 I jxcore-log: 
09-28 06:52:41.770  5634  5680 I jxcore-log:   ...
09-28 06:52:41.770  5634  5680 I jxcore-log: 
,09-28 06:52:41.771  5634  5680 I jxcore-log: not ok 544 test exited without ending
09-28 06:52:41.771  5634  5680 I jxcore-log: 
09-28 06:52:41.771  5634  5680 I jxcore-log:   ---
09-28 06:52:41.771  5634  5680 I jxcore-log: 
09-28 06:52:41.771  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.771  5634  5680 I jxcore-log: 
09-28 06:52:41.771  5634  5680 I jxcore-log:   ...
09-28 06:52:41.771  5634  5680 I jxcore-log: 
,09-28 06:52:41.772  5634  5680 I jxcore-log: not ok 545 test exited without ending
09-28 06:52:41.772  5634  5680 I jxcore-log: 
09-28 06:52:41.772  5634  5680 I jxcore-log:   ---
09-28 06:52:41.772  5634  5680 I jxcore-log: 
,09-28 06:52:41.772  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.772  5634  5680 I jxcore-log: 
09-28 06:52:41.772  5634  5680 I jxcore-log:   ...
09-28 06:52:41.772  5634  5680 I jxcore-log: 
09-28 06:52:41.773  5634  5680 I jxcore-log: not ok 546 test exited without ending
09-28 06:52:41.773  5634  5680 I jxcore-log: 
,09-28 06:52:41.773  5634  5680 I jxcore-log:   ---
09-28 06:52:41.773  5634  5680 I jxcore-log: 
09-28 06:52:41.773  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.773  5634  5680 I jxcore-log: 
09-28 06:52:41.773  5634  5680 I jxcore-log:   ...
09-28 06:52:41.773  5634  5680 I jxcore-log: 
,09-28 06:52:41.774  5634  5680 I jxcore-log: not ok 547 test exited without ending
09-28 06:52:41.774  5634  5680 I jxcore-log: 
09-28 06:52:41.774  5634  5680 I jxcore-log:   ---
09-28 06:52:41.774  5634  5680 I jxcore-log: 
09-28 06:52:41.774  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.774  5634  5680 I jxcore-log: 
09-28 06:52:41.774  5634  5680 I jxcore-log:   ...
09-28 06:52:41.774  5634  5680 I jxcore-log: 
,09-28 06:52:41.775  5634  5680 I jxcore-log: not ok 548 test exited without ending
09-28 06:52:41.775  5634  5680 I jxcore-log: 
09-28 06:52:41.775  5634  5680 I jxcore-log:   ---
09-28 06:52:41.775  5634  5680 I jxcore-log: 
09-28 06:52:41.775  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.775  5634  5680 I jxcore-log: 
09-28 06:52:41.775  5634  5680 I jxcore-log:   ...
09-28 06:52:41.775  5634  5680 I jxcore-log: 
,09-28 06:52:41.775  5634  5680 I jxcore-log: not ok 549 test exited without ending
09-28 06:52:41.775  5634  5680 I jxcore-log: 
09-28 06:52:41.775  5634  5680 I jxcore-log:   ---
09-28 06:52:41.775  5634  5680 I jxcore-log: 
09-28 06:52:41.776  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.776  5634  5680 I jxcore-log: 
,09-28 06:52:41.776  5634  5680 I jxcore-log:   ...
09-28 06:52:41.776  5634  5680 I jxcore-log: 
09-28 06:52:41.776  5634  5680 I jxcore-log: not ok 550 test exited without ending
09-28 06:52:41.776  5634  5680 I jxcore-log: 
09-28 06:52:41.776  5634  5680 I jxcore-log:   ---
09-28 06:52:41.776  5634  5680 I jxcore-log: 
09-28 06:52:41.776  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.776  5634  5680 I jxcore-log: 
,09-28 06:52:41.776  5634  5680 I jxcore-log:   ...
09-28 06:52:41.776  5634  5680 I jxcore-log: 
,09-28 06:52:41.777  5634  5680 I jxcore-log: not ok 551 test exited without ending
09-28 06:52:41.777  5634  5680 I jxcore-log: 
09-28 06:52:41.777  5634  5680 I jxcore-log:   ---
09-28 06:52:41.777  5634  5680 I jxcore-log: 
09-28 06:52:41.777  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.777  5634  5680 I jxcore-log: 
09-28 06:52:41.777  5634  5680 I jxcore-log:   ...
09-28 06:52:41.777  5634  5680 I jxcore-log: 
09-28 06:52:41.778  5634  5680 I jxcore-log: not ok 552 test exited without ending
09-28 06:52:41.778  5634  5680 I jxcore-log: 
09-28 06:52:41.778  5634  5680 I jxcore-log:   ---
09-28 06:52:41.778  5634  5680 I jxcore-log: 
,09-28 06:52:41.778  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.778  5634  5680 I jxcore-log: 
09-28 06:52:41.778  5634  5680 I jxcore-log:   ...
09-28 06:52:41.778  5634  5680 I jxcore-log: 
,09-28 06:52:41.779  5634  5680 I jxcore-log: not ok 553 test exited without ending
09-28 06:52:41.779  5634  5680 I jxcore-log: 
09-28 06:52:41.779  5634  5680 I jxcore-log:   ---
09-28 06:52:41.779  5634  5680 I jxcore-log: 
09-28 06:52:41.779  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.779  5634  5680 I jxcore-log: 
09-28 06:52:41.779  5634  5680 I jxcore-log:   ...
09-28 06:52:41.779  5634  5680 I jxcore-log: 
,09-28 06:52:41.780  5634  5680 I jxcore-log: not ok 554 test exited without ending
09-28 06:52:41.780  5634  5680 I jxcore-log: 
09-28 06:52:41.780  5634  5680 I jxcore-log:   ---
09-28 06:52:41.780  5634  5680 I jxcore-log: 
09-28 06:52:41.780  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.780  5634  5680 I jxcore-log: 
09-28 06:52:41.780  5634  5680 I jxcore-log:   ...
09-28 06:52:41.780  5634  5680 I jxcore-log: 
,09-28 06:52:41.781  5634  5680 I jxcore-log: not ok 555 test exited without ending
09-28 06:52:41.781  5634  5680 I jxcore-log: 
09-28 06:52:41.781  5634  5680 I jxcore-log:   ---
09-28 06:52:41.781  5634  5680 I jxcore-log: 
09-28 06:52:41.781  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.781  5634  5680 I jxcore-log: 
09-28 06:52:41.781  5634  5680 I jxcore-log:   ...
09-28 06:52:41.781  5634  5680 I jxcore-log: 
,09-28 06:52:41.782  5634  5680 I jxcore-log: not ok 556 test exited without ending
09-28 06:52:41.782  5634  5680 I jxcore-log: 
09-28 06:52:41.782  5634  5680 I jxcore-log:   ---
09-28 06:52:41.782  5634  5680 I jxcore-log: 
09-28 06:52:41.782  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.782  5634  5680 I jxcore-log: 
09-28 06:52:41.782  5634  5680 I jxcore-log:   ...
09-28 06:52:41.782  5634  5680 I jxcore-log: 
,09-28 06:52:41.783  5634  5680 I jxcore-log: not ok 557 test exited without ending
09-28 06:52:41.783  5634  5680 I jxcore-log: 
09-28 06:52:41.783  5634  5680 I jxcore-log:   ---
09-28 06:52:41.783  5634  5680 I jxcore-log: 
09-28 06:52:41.783  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.783  5634  5680 I jxcore-log: 
09-28 06:52:41.783  5634  5680 I jxcore-log:   ...
09-28 06:52:41.783  5634  5680 I jxcore-log: 
,09-28 06:52:41.783  5634  5680 I jxcore-log: not ok 558 test exited without ending
09-28 06:52:41.783  5634  5680 I jxcore-log: 
09-28 06:52:41.784  5634  5680 I jxcore-log:   ---
09-28 06:52:41.784  5634  5680 I jxcore-log: 
09-28 06:52:41.784  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.784  5634  5680 I jxcore-log: 
,09-28 06:52:41.784  5634  5680 I jxcore-log:   ...
09-28 06:52:41.784  5634  5680 I jxcore-log: 
09-28 06:52:41.784  5634  5680 I jxcore-log: not ok 559 test exited without ending
09-28 06:52:41.784  5634  5680 I jxcore-log: 
09-28 06:52:41.784  5634  5680 I jxcore-log:   ---
09-28 06:52:41.784  5634  5680 I jxcore-log: 
09-28 06:52:41.784  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.784  5634  5680 I jxcore-log: 
,09-28 06:52:41.785  5634  5680 I jxcore-log:   ...
09-28 06:52:41.785  5634  5680 I jxcore-log: 
09-28 06:52:41.785  5634  5680 I jxcore-log: not ok 560 test exited without ending
09-28 06:52:41.785  5634  5680 I jxcore-log: 
09-28 06:52:41.785  5634  5680 I jxcore-log:   ---
09-28 06:52:41.785  5634  5680 I jxcore-log: 
09-28 06:52:41.785  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.785  5634  5680 I jxcore-log: 
,09-28 06:52:41.785  5634  5680 I jxcore-log:   ...
09-28 06:52:41.785  5634  5680 I jxcore-log: 
09-28 06:52:41.786  5634  5680 I jxcore-log: not ok 561 test exited without ending
09-28 06:52:41.786  5634  5680 I jxcore-log: 
,09-28 06:52:41.786  5634  5680 I jxcore-log:   ---
09-28 06:52:41.786  5634  5680 I jxcore-log: 
09-28 06:52:41.786  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.786  5634  5680 I jxcore-log: 
09-28 06:52:41.786  5634  5680 I jxcore-log:   ...
09-28 06:52:41.786  5634  5680 I jxcore-log: 
,09-28 06:52:41.787  5634  5680 I jxcore-log: not ok 562 test exited without ending
09-28 06:52:41.787  5634  5680 I jxcore-log: 
09-28 06:52:41.787  5634  5680 I jxcore-log:   ---
09-28 06:52:41.787  5634  5680 I jxcore-log: 
09-28 06:52:41.787  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.787  5634  5680 I jxcore-log: 
09-28 06:52:41.787  5634  5680 I jxcore-log:   ...
09-28 06:52:41.787  5634  5680 I jxcore-log: 
,09-28 06:52:41.788  5634  5680 I jxcore-log: not ok 563 test exited without ending
09-28 06:52:41.788  5634  5680 I jxcore-log: 
09-28 06:52:41.788  5634  5680 I jxcore-log:   ---
09-28 06:52:41.788  5634  5680 I jxcore-log: 
09-28 06:52:41.788  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.788  5634  5680 I jxcore-log: 
09-28 06:52:41.788  5634  5680 I jxcore-log:   ...
09-28 06:52:41.788  5634  5680 I jxcore-log: 
,09-28 06:52:41.789  5634  5680 I jxcore-log: not ok 564 test exited without ending
09-28 06:52:41.789  5634  5680 I jxcore-log: 
09-28 06:52:41.789  5634  5680 I jxcore-log:   ---
09-28 06:52:41.789  5634  5680 I jxcore-log: 
09-28 06:52:41.789  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.789  5634  5680 I jxcore-log: 
09-28 06:52:41.789  5634  5680 I jxcore-log:   ...
09-28 06:52:41.789  5634  5680 I jxcore-log: 
,09-28 06:52:41.790  5634  5680 I jxcore-log: not ok 565 test exited without ending
09-28 06:52:41.790  5634  5680 I jxcore-log: 
09-28 06:52:41.790  5634  5680 I jxcore-log:   ---
09-28 06:52:41.790  5634  5680 I jxcore-log: 
,09-28 06:52:41.790  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.790  5634  5680 I jxcore-log: 
09-28 06:52:41.790  5634  5680 I jxcore-log:   ...
09-28 06:52:41.790  5634  5680 I jxcore-log: 
,09-28 06:52:41.791  5634  5680 I jxcore-log: not ok 566 test exited without ending
09-28 06:52:41.791  5634  5680 I jxcore-log: 
09-28 06:52:41.791  5634  5680 I jxcore-log:   ---
09-28 06:52:41.791  5634  5680 I jxcore-log: 
09-28 06:52:41.791  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.791  5634  5680 I jxcore-log: 
09-28 06:52:41.791  5634  5680 I jxcore-log:   ...
09-28 06:52:41.791  5634  5680 I jxcore-log: 
,09-28 06:52:41.792  5634  5680 I jxcore-log: not ok 567 test exited without ending
09-28 06:52:41.792  5634  5680 I jxcore-log: 
09-28 06:52:41.792  5634  5680 I jxcore-log:   ---
09-28 06:52:41.792  5634  5680 I jxcore-log: 
09-28 06:52:41.792  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.792  5634  5680 I jxcore-log: 
09-28 06:52:41.792  5634  5680 I jxcore-log:   ...
09-28 06:52:41.792  5634  5680 I jxcore-log: 
,09-28 06:52:41.793  5634  5680 I jxcore-log: not ok 568 test exited without ending
09-28 06:52:41.793  5634  5680 I jxcore-log: 
09-28 06:52:41.793  5634  5680 I jxcore-log:   ---
09-28 06:52:41.793  5634  5680 I jxcore-log: 
09-28 06:52:41.793  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.793  5634  5680 I jxcore-log: 
09-28 06:52:41.793  5634  5680 I jxcore-log:   ...
09-28 06:52:41.793  5634  5680 I jxcore-log: 
,09-28 06:52:41.793  5634  5680 I jxcore-log: not ok 569 test exited without ending
09-28 06:52:41.793  5634  5680 I jxcore-log: 
09-28 06:52:41.794  5634  5680 I jxcore-log:   ---
09-28 06:52:41.794  5634  5680 I jxcore-log: 
09-28 06:52:41.794  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.794  5634  5680 I jxcore-log: 
09-28 06:52:41.794  5634  5680 I jxcore-log:   ...
09-28 06:52:41.794  5634  5680 I jxcore-log: 
,09-28 06:52:41.795  5634  5680 I jxcore-log: not ok 570 test exited without ending
09-28 06:52:41.795  5634  5680 I jxcore-log: 
09-28 06:52:41.795  5634  5680 I jxcore-log:   ---
09-28 06:52:41.795  5634  5680 I jxcore-log: 
09-28 06:52:41.795  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.795  5634  5680 I jxcore-log: 
,09-28 06:52:41.795  5634  5680 I jxcore-log:   ...
09-28 06:52:41.795  5634  5680 I jxcore-log: 
09-28 06:52:41.795  5634  5680 I jxcore-log: not ok 571 test exited without ending
09-28 06:52:41.795  5634  5680 I jxcore-log: 
09-28 06:52:41.796  5634  5680 I jxcore-log:   ---
09-28 06:52:41.796  5634  5680 I jxcore-log: 
,09-28 06:52:41.796  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.796  5634  5680 I jxcore-log: 
09-28 06:52:41.796  5634  5680 I jxcore-log:   ...
09-28 06:52:41.796  5634  5680 I jxcore-log: 
09-28 06:52:41.796  5634  5680 I jxcore-log: not ok 572 test exited without ending
09-28 06:52:41.796  5634  5680 I jxcore-log: 
,09-28 06:52:41.796  5634  5680 I jxcore-log:   ---
09-28 06:52:41.796  5634  5680 I jxcore-log: 
09-28 06:52:41.796  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.796  5634  5680 I jxcore-log: 
09-28 06:52:41.797  5634  5680 I jxcore-log:   ...
09-28 06:52:41.797  5634  5680 I jxcore-log: 
,09-28 06:52:41.797  5634  5680 I jxcore-log: not ok 573 test exited without ending
09-28 06:52:41.797  5634  5680 I jxcore-log: 
09-28 06:52:41.797  5634  5680 I jxcore-log:   ---
09-28 06:52:41.797  5634  5680 I jxcore-log: 
09-28 06:52:41.797  5634  5680 I jxcore-log:     operator: fail
09-28 06:52:41.797  5634  5680 I jxcore-log: 
09-28 06:52:41.797  5634  5680 I jxcore-log:   ...
09-28 06:52:41.797  5634  5680 I jxcore-log: 
09-28 06:52:41.798  5634  5680 I jxcore-log: 
09-28 06:52:41.798  5634  5680 I jxcore-log: 
,09-28 06:52:41.798  5634  5680 I jxcore-log: 1..573
09-28 06:52:41.798  5634  5680 I jxcore-log: 
09-28 06:52:41.798  5634  5680 I jxcore-log: # tests 573
09-28 06:52:41.798  5634  5680 I jxcore-log: 
09-28 06:52:41.798  5634  5680 I jxcore-log: # pass  80
09-28 06:52:41.798  5634  5680 I jxcore-log: 
09-28 06:52:41.798  5634  5680 I jxcore-log: # fail  493
09-28 06:52:41.798  5634  5680 I jxcore-log: 
,09-28 06:52:41.799  5634  5680 I jxcore-log: 
09-28 06:52:41.799  5634  5680 I jxcore-log: 
,09-28 06:52:41.862  5983  5983 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-28 06:52:41.867  5983  5983 D AndroidRuntime: CheckJNI is OFF
,09-28 06:52:41.896  5983  5983 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-28 06:52:41.930  5983  5983 I Radio-JNI: register_android_hardware_Radio DONE
,09-28 06:52:41.947  5983  5983 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-28 06:52:41.957   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-28 06:52:41.958   927   940 I ActivityManager: Killing 5634:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-28 06:52:42.057   927  3414 D GraphicsStats: Buffer count: 2
,09-28 06:52:42.057   927  3863 I WindowState: WIN DEATH: Window{654778f u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-28 06:52:42.057   927  3010 D WifiService: Client connection lost with reason: 4
,09-28 06:52:42.114   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-28 06:52:42.115   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-28 06:52:42.114   927   950 I art     : Starting a blocking GC Explicit
09-28 06:52:42.116   927   940 E ActivityManager: Failure starting process com.test.thalitest
09-28 06:52:42.116   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-28 06:52:42.116   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:52:42.116   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:52:42.116   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 06:52:42.116   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-28 06:52:42.116   927   940 I ActivityManager:   Force finishing activity ActivityRecord{59c8890 u0 com.test.thalitest/.MainActivity t2}
,09-28 06:52:42.128   927  3153 W ActivityManager: Spurious death for ProcessRecord{8671f5d 0:com.test.thalitest/u0a77}, curProc for 5634: null
,09-28 06:52:42.131   927   945 W WindowManager: Attempted to add application window with unknown token Token{4a23589 ActivityRecord{59c8890 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-28 06:52:42.131   927   945 W WindowManager: Token{4a23589 ActivityRecord{59c8890 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{4a23589 ActivityRecord{59c8890 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-28 06:52:42.131   927   945 W WindowManager: view not successfully added to wm, removing view
09-28 06:52:42.132   927   945 W WindowManager: Exception when adding starting window
09-28 06:52:42.132   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{51d26cc V.E...... R.....ID 0,0-0,0} not attached to window manager
09-28 06:52:42.132   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-28 06:52:42.132   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-28 06:52:42.132   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-28 06:52:42.132   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-28 06:52:42.132   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-28 06:52:42.132   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:52:42.132   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:52:42.132   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 06:52:42.132   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 06:52:42.219   927   950 I art     : Explicit concurrent mark sweep GC freed 131968(10MB) AllocSpace objects, 87(3MB) LOS objects, 33% free, 29MB/44MB, paused 1.705ms total 104.113ms
,09-28 06:52:42.238   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-28 06:52:42.240  5983  5983 I art     : System.exit called, status: 0
,09-28 06:52:42.240  5983  5983 I AndroidRuntime: VM exiting with result code 0.
,09-28 06:52:42.246   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-28 06:52:42.255   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-28 06:52:42.258  5873  5873 D BluetoothMapAppObserver: onReceive
,09-28 06:52:42.259  5873  5873 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-28 06:52:42.261  4070  4179 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-28 06:52:42.262  3652  3652 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-28 06:52:42.275   927  2961 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-28 06:52:42.284  3652  5994 I Keyboard.Facilitator.DecoderInitializer: run()
,09-28 06:52:42.288  3652  5994 I Decoder : createOrResetDecoder
,09-28 06:52:42.315  3396  5996 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-28 06:52:42.322  3811  3811 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-28 06:52:42.328  3575  3575 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-28 06:52:42.328  3575  3575 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-28 06:52:42.343  3575  3575 I ConfigService: onCreate
,09-28 06:52:42.344  3724  6000 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-28 06:52:42.345  3724  6000 D AccountUtils: Clearing selected account for com.test.thalitest
,09-28 06:52:42.346   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-28 06:52:42.357    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 06:52:42.361    29    29 W kworker/3:1: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 06:52:42.377  3652  5994 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-28 06:52:42.377    29    29 W kworker/3:1: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 06:52:42.393  3396  3422 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj7E4D55926) - 
,09-28 06:52:42.409  3724  6000 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-28 06:52:42.426  3724  6000 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:52:42.426  3724  6000 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:52:42.427  3724  6000 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 06:52:42.428  3724  6000 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,--------- beginning of crash
09-28 06:52:42.463  3396  3422 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-28 06:52:42.463  3396  3422 E AndroidRuntime: Process: android.process.acore, PID: 3396
09-28 06:52:42.463  3396  3422 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-28 06:52:42.463  3396  3422 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 06:52:42.480  3724  3724 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-28 06:52:42.480  3724  3724 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-28 06:52:42.491  3724  3724 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-28 06:52:42.491  3724  3724 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-28 06:52:42.516  3908  6011 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-28 06:52:42.529  3396  3422 I Process : Sending signal. PID: 3396 SIG: 9
,09-28 06:52:42.529   927  3830 I ActivityManager: Start proc 6015:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-28 06:52:42.549  3908  6011 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-28 06:52:42.569  3724  6010 W BaseAppContext: Using Auth Proxy for data requests.
,09-28 06:52:42.580  3724  6010 W BaseAppContext: Using Auth Proxy for data requests.
,09-28 06:52:42.589   927  3109 I ActivityManager: Start proc 6020:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-28 06:52:42.599  3724  3724 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-28 06:52:42.611  3724  6026 I GMPM-SVC: App measurement is starting up
,09-28 06:52:42.618  3724  6026 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-28 06:52:42.619  3724  6026 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-28 06:52:42.765   382   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
