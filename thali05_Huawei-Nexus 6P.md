#### Test 90157400a66ed30_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-20 08:06:58.551   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-20 08:06:58.551   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-20 08:06:59.028  5649  5649 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-20 08:06:59.033  5649  5649 D AndroidRuntime: CheckJNI is OFF
10-20 08:06:59.061  5649  5649 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-20 08:06:59.098  5649  5649 I Radio-JNI: register_android_hardware_Radio DONE
10-20 08:06:59.115  5649  5649 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-20 08:06:59.121   928   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-20 08:06:59.167   928   938 I ActivityManager: Start proc 5658:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-20 08:06:59.185  5649  5649 D AndroidRuntime: Shutting down VM
,10-20 08:06:59.517   928  3451 I WindowManager: Screenshot max retries 4 of Token{4696c ActivityRecord{207621f u0 com.test.thalitest/.MainActivity t2}} appWin=Window{44d7617 u0 Starting com.test.thalitest} drawState=2
,10-20 08:06:59.604  5658  5658 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-20 08:06:59.629  5658  5658 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-20 08:06:59.651  5658  5658 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 9876-9894)
,10-20 08:06:59.651  5658  5658 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-20 08:06:59.668  5658  5658 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {717d031}
,10-20 08:06:59.668  5658  5658 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-20 08:06:59.668  5658  5658 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-20 08:06:59.672  5658  5658 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-20 08:06:59.673  5658  5658 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-20 08:06:59.702  5658  5658 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-20 08:06:59.711  5658  5658 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-20 08:06:59.711  5658  5658 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-20 08:06:59.711  5658  5658 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-20 08:06:59.711  5658  5658 I Adreno  : Build Date                       : 12/06/15
10-20 08:06:59.711  5658  5658 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-20 08:06:59.711  5658  5658 I Adreno  : Local Branch                     : mybranch17112971
10-20 08:06:59.711  5658  5658 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-20 08:06:59.711  5658  5658 I Adreno  : Remote Branch                    : NONE
10-20 08:06:59.711  5658  5658 I Adreno  : Reconstruct Branch               : NOTHING
,10-20 08:06:59.741   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c193b7a:true
,10-20 08:06:59.763   742   742 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34159]" dev="sockfs" ino=34159 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-20 08:06:59.763   742   742 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34159]" dev="sockfs" ino=34159 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-20 08:06:59.774  5658  5658 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-20 08:06:59.782  5658  5658 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-20 08:06:59.803   742   742 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32275]" dev="sockfs" ino=32275 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-20 08:06:59.805  5658  5695 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-20 08:06:59.803   742   742 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32275]" dev="sockfs" ino=32275 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-20 08:06:59.806   938   938 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14232]" dev="sockfs" ino=14232 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-20 08:06:59.806   938   938 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14232]" dev="sockfs" ino=14232 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-20 08:06:59.810  5658  5682 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-20 08:06:59.833  5658  5695 I OpenGLRenderer: Initialized EGL, version 1.4
,10-20 08:06:59.905   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +384ms (total +767ms)
,10-20 08:06:59.949  5658  5658 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5658
,10-20 08:07:00.033  5658  5658 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-20 08:07:00.190  5658  5697 D jxcore_app_log: JniHelper::setJavaVM(0xf543c000), pthread_self() = -578029264
,10-20 08:07:00.194  5658  5697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-20 08:07:00.194  5658  5697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-20 08:07:00.194  5658  5697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-20 08:07:00.194  5658  5697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-20 08:07:00.194  5658  5697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-20 08:07:00.194  5658  5697 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44e334f added. We now have 1 listener(s)
,10-20 08:07:00.197  5658  5697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-20 08:07:00.197  5658  5697 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:07:00.198  5658  5697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:07:00.198  5658  5697 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-20 08:07:00.200  5658  5697 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d8f72ba added. We now have 1 listener(s)
10-20 08:07:00.200  5658  5697 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:07:00.204   928  3008 D WifiService: New client listening to asynchronous messages
,10-20 08:07:00.204  5658  5697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-20 08:07:00.204  5658  5697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-20 08:07:00.205  5658  5697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-20 08:07:00.205  5658  5697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-20 08:07:00.205  5658  5697 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-20 08:07:00.206  5658  5697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:07:00.207  5658  5697 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-20 08:07:00.211  5658  5697 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:00.211  5658  5697 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:00.211  5658  5697 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-20 08:07:00.211  5658  5697 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:07:00.211  5658  5697 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-20 08:07:00.314  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:00.318  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:00.321  5658  5658 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-20 08:07:00.447   928  3007 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-20 08:07:00.816  5658  5704 W jxcore-log: Initializing JXcore engine
,10-20 08:07:00.816  5658  5704 W jxcore-log: JXcore engine is ready
,10-20 08:07:00.840  5704  5704 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11734 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-20 08:07:00.840  5704  5704 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14379]" dev="sockfs" ino=14379 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-20 08:07:00.840  5704  5704 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-20 08:07:00.840  5704  5704 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30280]" dev="sockfs" ino=30280 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-20 08:07:00.848  5658  5704 W jxcore-log: Starting JXcore engine
,10-20 08:07:00.898  5658  5704 W jxcore-log: Platform android
10-20 08:07:00.898  5658  5704 W jxcore-log: 
,10-20 08:07:00.898  5658  5704 W jxcore-log: Process ARCH arm
10-20 08:07:00.898  5658  5704 W jxcore-log: 
,10-20 08:07:01.077  5658  5704 I jxcore-log: JXcore Cordova bridge is ready!
10-20 08:07:01.077  5658  5704 I jxcore-log: 
,10-20 08:07:01.078  5658  5704 W jxcore-log: JXcore engine is started
,10-20 08:07:01.094  5658  5697 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-20 08:07:01.099  5658  5658 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-20 08:07:05.214   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-20 08:07:08.552   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:09.554   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:10.555   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:10.858  5658  5704 I jxcore-log: 2016-10-20 12:07:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-20 08:07:10.858  5658  5704 I jxcore-log: 
,10-20 08:07:10.860  5658  5704 I jxcore-log: 2016-10-20 12:07:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-20 08:07:10.860  5658  5704 I jxcore-log: 
,10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:10.864  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:07:10.866  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:07:10.867  5658  5704 I jxcore-log: 2016-10-20 12:07:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-20 08:07:10.867  5658  5704 I jxcore-log: 
,10-20 08:07:10.869  5658  5704 I jxcore-log: 2016-10-20 12:07:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-20 08:07:10.869  5658  5704 I jxcore-log: 
,10-20 08:07:11.120  5658  5704 I jxcore-log: 2016-10-20 12:07:11 - DEBUG UnitTest_app: 'Running unit tests'
10-20 08:07:11.120  5658  5704 I jxcore-log: 
,10-20 08:07:11.120  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-20 08:07:11.120  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa30b1 added. We now have 2 listener(s)
10-20 08:07:11.121  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-20 08:07:11.121  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:07:11.121  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-20 08:07:11.121  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:07:11.121  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d32d996 added. We now have 2 listener(s)
,10-20 08:07:11.122  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:07:11.122  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-20 08:07:11.124  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:11.128  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:07:11.128  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:11.129  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:07:11.129  5658  5704 D executeNativeTests: Running unit tests
,10-20 08:07:11.135  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:11.140  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:11.166  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-20 08:07:11.166  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 added. We now have 3 listener(s)
10-20 08:07:11.167  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-20 08:07:11.167  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:07:11.167  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:07:11.167  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:07:11.167  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d added. We now have 3 listener(s)
10-20 08:07:11.167  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:07:11.167  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-20 08:07:11.169  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:11.171  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:11.172  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:07:11.172  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-20 08:07:11.173  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-20 08:07:11.173  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-20 08:07:11.173  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-20 08:07:11.173  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-20 08:07:11.174  5658  5704 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-20 08:07:11.174  5658  5704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-20 08:07:11.174  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-20 08:07:11.174  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-20 08:07:11.174  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-20 08:07:11.174  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-20 08:07:11.174  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:11.175  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:11.175  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:11.175  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:11.175  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.175  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:07:11.175  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:11.175  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:07:11.175  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 removed from the list
10-20 08:07:11.175  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:11.175  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d removed from the list
10-20 08:07:11.179  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:11.184  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:11.185  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:11.185  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.185  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.185  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.186  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:11.186  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:11.186  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:11.186  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:11.187  5658  5704 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-20 08:07:11.187  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:11.187  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:11.187  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-20 08:07:11.187  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:11.187  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.187  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.187  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:11.187  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
,10-20 08:07:11.187  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:11.187  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:11.187  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:11.187  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.187  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.187  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.187  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.188  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-20 08:07:11.188  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:11.188  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:11.188  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:11.190  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-20 08:07:11.190  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-20 08:07:11.190  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-20 08:07:11.191  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-20 08:07:11.192  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:11.192  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:11.192  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:11.192  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:11.192  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.192  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.192  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:11.192  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:11.192  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:11.192  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:11.192  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:11.192  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.192  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.192  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:11.192  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:11.193  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:11.193  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:11.193  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:11.193  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:11.194  5658  5704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-20 08:07:11.194  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:11.197  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:11.198  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:11.198  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:07:11.198  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:07:11.198  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-20 08:07:11.198  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-20 08:07:11.198  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:07:11.198  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-20 08:07:11.200  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:11.201  5658  5704 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-20 08:07:11.201  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-20 08:07:11.201  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:11.203  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-20 08:07:11.204  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-20 08:07:11.204  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-20 08:07:11.205  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-20 08:07:11.206  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-20 08:07:11.206  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-20 08:07:11.206  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-20 08:07:11.206  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-20 08:07:11.207  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-20 08:07:11.207  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-20 08:07:11.208  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:07:11.209  4625  4868 D BtGatt.GattService: registerClient() - UUID=1e513ecd-e4aa-4ed5-99c7-aba88cb11abe
10-20 08:07:11.210  4625  4702 D BtGatt.GattService: onClientRegistered() - UUID=1e513ecd-e4aa-4ed5-99c7-aba88cb11abe, clientIf=5
10-20 08:07:11.211  5658  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-20 08:07:11.212  4625  4876 D BtGatt.GattService: start scan with filters
10-20 08:07:11.220  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-20 08:07:11.220  4625  4707 D BtGatt.ScanManager: handling starting scan
10-20 08:07:11.220  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-20 08:07:11.220  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:07:11.220  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-20 08:07:11.220  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-20 08:07:11.220  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-20 08:07:11.220  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-20 08:07:11.221  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-20 08:07:11.222  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-20 08:07:11.222  4625  4707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:07:11.222  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-20 08:07:11.222  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-20 08:07:11.223  5658  5704 I io.jxcore.node.ConnectionHelper: start: OK
10-20 08:07:11.230  4625  4702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-20 08:07:11.230  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:07:11.230  4625  4707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-20 08:07:11.236  4625  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-20 08:07:11.236  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:11.237  4625  4707 D BtGatt.ScanManager: Starting BLE batch scan
10-20 08:07:11.237  4625  4707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-20 08:07:11.247  4625  4702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-20 08:07:11.247  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:11.253  4625  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-20 08:07:11.253  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:11.255   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-20 08:07:11.556   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:11.724  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-20 08:07:11.724  5658  5658 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:07:11.724  5658  5658 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-20 08:07:12.558   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:13.558   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-20 08:07:16.227  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:16.228  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:16.228  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-20 08:07:16.228  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:16.228  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-20 08:07:16.228  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:16.228  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-20 08:07:16.228  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-20 08:07:16.228  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-20 08:07:16.228  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-20 08:07:16.229  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-20 08:07:16.229  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-20 08:07:16.230  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:07:16.231  4625  4876 D BtGatt.GattService: stopScan() - queue size =1
10-20 08:07:16.232  4625  4643 D BtGatt.GattService: unregisterClient() - clientIf=5
10-20 08:07:16.233  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-20 08:07:16.233  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-20 08:07:16.233  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-20 08:07:16.233  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-20 08:07:16.233  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-20 08:07:16.233  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-20 08:07:16.233  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-20 08:07:16.233  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-20 08:07:16.237  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-20 08:07:16.238  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-20 08:07:16.238  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-20 08:07:16.238  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-20 08:07:16.239  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-20 08:07:16.241  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:07:16.243  4625  4625 D BtGatt.ScanManager: awakened up at time 236486
,10-20 08:07:16.244  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:16.244  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:07:16.245  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:07:16.245  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:16.245  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:07:16.245  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:07:16.245  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:16.245  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:16.245  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:16.246  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:16.246  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:16.246  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:16.250  4625  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-20 08:07:16.250  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:16.251  4625  4707 D BtGatt.ScanManager: stopping BLe Batch
,10-20 08:07:16.259  4625  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-20 08:07:16.260  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:16.260  4625  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-20 08:07:16.292  4625  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-20 08:07:16.292  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:16.292  4625  4702 D BtGatt.GattService: current time is 236536114806
10-20 08:07:16.293  4625  4702 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -79, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -85, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -82, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 50, -35, 86, -77, -92, -11, 1, 0, -98, 69, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -114, -54, 49, 3, 1, -33, 18, -106, 111, 35, 108, 28, 6, 8, 116, 105, 110, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
10-20 08:07:16.295  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-20 08:07:16.297  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-20 08:07:16.298  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-20 08:07:16.298  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-20 08:07:16.299  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-20 08:07:16.299  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-20 08:07:16.299  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -114, -54, 49, 3, 1, -33, 18, -106, 111, 35, 108, 6, 8, 116, 105, 110, 54, 56, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,10-20 08:07:16.746  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-20 08:07:18.560   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:19.561   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:20.562   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:21.248  5658  5704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-20 08:07:21.254  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:21.266  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:07:21.271  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:07:21.272  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:07:21.272  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-20 08:07:21.273  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-20 08:07:21.273  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-20 08:07:21.273  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:07:21.273  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-20 08:07:21.281  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:21.284  5658  5704 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-20 08:07:21.285  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-20 08:07:21.289  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:21.294  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-20 08:07:21.295  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-20 08:07:21.295  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-20 08:07:21.299  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-20 08:07:21.299  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-20 08:07:21.299  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-20 08:07:21.300  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-20 08:07:21.300  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-20 08:07:21.301  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:07:21.303  4625  4642 D BtGatt.GattService: registerClient() - UUID=cb7da531-a542-48fc-93c7-fe807ca08da4
,10-20 08:07:21.304  4625  4702 D BtGatt.GattService: onClientRegistered() - UUID=cb7da531-a542-48fc-93c7-fe807ca08da4, clientIf=5
,10-20 08:07:21.305  5658  5668 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-20 08:07:21.305  4625  4876 D BtGatt.GattService: start scan with filters
10-20 08:07:21.309  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-20 08:07:21.309  4625  4707 D BtGatt.ScanManager: handling starting scan
10-20 08:07:21.309  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-20 08:07:21.309  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:07:21.309  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-20 08:07:21.309  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-20 08:07:21.309  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-20 08:07:21.310  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-20 08:07:21.313  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-20 08:07:21.313  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-20 08:07:21.314  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-20 08:07:21.315  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-20 08:07:21.318  5658  5704 I io.jxcore.node.ConnectionHelper: start: OK
10-20 08:07:21.320  4625  4702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-20 08:07:21.320  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:21.320  4625  4707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-20 08:07:21.321  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:21.321  5658  5704 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-20 08:07:21.321  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:21.321  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-20 08:07:21.321  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:21.321  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-20 08:07:21.321  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:21.321  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-20 08:07:21.322  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-20 08:07:21.322  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-20 08:07:21.322  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-20 08:07:21.322  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-20 08:07:21.322  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-20 08:07:21.323  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:07:21.323  4625  4876 D BtGatt.GattService: stopScan() - queue size =1
10-20 08:07:21.324  4625  4643 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-20 08:07:21.325  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-20 08:07:21.325  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-20 08:07:21.325  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-20 08:07:21.325  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:07:21.325  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-20 08:07:21.325  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-20 08:07:21.325  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-20 08:07:21.325  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-20 08:07:21.326  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:07:21.326  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-20 08:07:21.327  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-20 08:07:21.327  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-20 08:07:21.327  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-20 08:07:21.327  4625  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-20 08:07:21.327  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:21.327  4625  4707 D BtGatt.ScanManager: Starting BLE batch scan
10-20 08:07:21.327  4625  4707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-20 08:07:21.327  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:07:21.328  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:21.329  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:21.329  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-20 08:07:21.329  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:21.329  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:07:21.329  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:21.329  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:21.329  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:07:21.329  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:21.329  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:07:21.329  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:21.329  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:21.330  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:21.330  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:21.331  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:21.331  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:21.331  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:21.331  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:21.332  5658  5704 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-20 08:07:21.334  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:21.339  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:07:21.340  4625  4702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-20 08:07:21.340  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:21.341  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:21.342  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:07:21.342  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:07:21.342  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-20 08:07:21.342  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-20 08:07:21.342  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:07:21.342  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-20 08:07:21.346  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:21.347  4625  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-20 08:07:21.347  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:07:21.348  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:21.349  5658  5704 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-20 08:07:21.349  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-20 08:07:21.352  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-20 08:07:21.353  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-20 08:07:21.353  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-20 08:07:21.354  4625  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-20 08:07:21.354  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:21.354  4625  4707 D BtGatt.ScanManager: stopping BLe Batch
10-20 08:07:21.355  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-20 08:07:21.356  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-20 08:07:21.356  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-20 08:07:21.356  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-20 08:07:21.356  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-20 08:07:21.356  5658  5704 D BluetoothAdapter: STATE_ON
,10-20 08:07:21.358  4625  4876 D BtGatt.GattService: registerClient() - UUID=90e593b6-dcdf-497e-b47f-f068436b3871
10-20 08:07:21.359  4625  4702 D BtGatt.GattService: onClientRegistered() - UUID=90e593b6-dcdf-497e-b47f-f068436b3871, clientIf=5
,10-20 08:07:21.359  5658  5668 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-20 08:07:21.360  4625  4643 D BtGatt.GattService: start scan with filters
10-20 08:07:21.360  4625  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-20 08:07:21.360  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:21.360  4625  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-20 08:07:21.362  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-20 08:07:21.362  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-20 08:07:21.362  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:07:21.362  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-20 08:07:21.363  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-20 08:07:21.363  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-20 08:07:21.363  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-20 08:07:21.365  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-20 08:07:21.365  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-20 08:07:21.365  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-20 08:07:21.365  4625  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-20 08:07:21.365  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:21.366  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-20 08:07:21.367  4625  4707 D BtGatt.ScanManager: handling starting scan
,10-20 08:07:21.368  5658  5704 I io.jxcore.node.ConnectionHelper: start: OK
,10-20 08:07:21.372  4625  4702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-20 08:07:21.373  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:07:21.373  4625  4707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-20 08:07:21.378  4625  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-20 08:07:21.378  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:21.378  4625  4707 D BtGatt.ScanManager: Starting BLE batch scan
10-20 08:07:21.378  4625  4707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-20 08:07:21.386  4625  4702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-20 08:07:21.386  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:07:21.391  4625  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-20 08:07:21.391  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:07:21.564   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:21.867  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-20 08:07:21.867  5658  5658 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:07:21.867  5658  5658 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-20 08:07:22.565   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:23.356   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-20 08:07:23.566   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-20 08:07:26.369  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:26.369  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:26.369  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-20 08:07:26.370  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:26.370  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-20 08:07:26.370  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:26.370  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-20 08:07:26.370  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-20 08:07:26.371  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-20 08:07:26.371  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-20 08:07:26.371  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-20 08:07:26.371  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-20 08:07:26.376  5658  5704 D BluetoothAdapter: STATE_ON
,10-20 08:07:26.378  4625  4868 D BtGatt.GattService: stopScan() - queue size =1
10-20 08:07:26.379  4625  4642 D BtGatt.GattService: unregisterClient() - clientIf=5
10-20 08:07:26.380  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-20 08:07:26.381  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-20 08:07:26.381  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-20 08:07:26.381  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-20 08:07:26.381  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-20 08:07:26.381  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-20 08:07:26.381  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-20 08:07:26.382  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-20 08:07:26.385  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:07:26.385  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-20 08:07:26.385  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-20 08:07:26.385  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-20 08:07:26.386  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-20 08:07:26.387  4625  4625 D BtGatt.ScanManager: awakened up at time 246630
10-20 08:07:26.387  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-20 08:07:26.390  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:07:26.390  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:07:26.390  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-20 08:07:26.393  4625  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-20 08:07:26.393  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:26.394  4625  4707 D BtGatt.ScanManager: stopping BLe Batch
,10-20 08:07:26.405  4625  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-20 08:07:26.405  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:07:26.406  4625  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-20 08:07:26.429  4625  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-20 08:07:26.429  4625  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:07:26.429  4625  4702 D BtGatt.GattService: current time is 246672641648
10-20 08:07:26.429  4625  4702 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -78, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -82, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -89, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 57, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-20 08:07:26.430  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-20 08:07:26.430  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-20 08:07:26.431  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-20 08:07:26.431  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-20 08:07:26.431  4625  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-20 08:07:26.891  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-20 08:07:26.891  5658  5658 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:26.892  5658  5658 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-20 08:07:31.391  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:31.391  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.392  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-20 08:07:31.392  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.392  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.392  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-20 08:07:31.392  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.392  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.393  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:31.393  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.393  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.393  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.395  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.395  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.399  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-20 08:07:31.399  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.399  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.400  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.401  5658  5704 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-20 08:07:31.403  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:31.403  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.403  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.403  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.404  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:07:31.404  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.404  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.404  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.404  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:31.405  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.405  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.405  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.405  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.405  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.405  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.408  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.408  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.408  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.409  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
,10-20 08:07:31.411  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-20 08:07:31.411  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:31.411  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.411  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.411  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.411  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:07:31.411  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.412  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.412  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.412  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:31.412  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.412  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.412  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.412  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.412  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.412  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.414  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.414  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-20 08:07:31.414  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.415  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.416  5658  5704 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-20 08:07:31.416  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:31.416  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.416  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.416  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.416  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:07:31.417  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.417  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.417  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.417  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.417  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.417  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.417  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.417  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.417  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.417  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.419  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.419  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-20 08:07:31.419  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.420  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.421  5658  5704 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-20 08:07:31.421  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:31.421  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-20 08:07:31.421  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.421  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.421  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.422  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.422  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.422  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.422  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.422  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
,10-20 08:07:31.422  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.422  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.422  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.422  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.422  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.425  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.425  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.425  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.425  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
,10-20 08:07:31.426  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-20 08:07:31.426  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-20 08:07:31.427  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-20 08:07:31.427  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-20 08:07:31.427  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-20 08:07:31.428  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-20 08:07:31.428  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-20 08:07:31.428  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-20 08:07:31.428  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-20 08:07:31.428  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:31.428  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.428  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.428  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.429  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.429  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.429  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.429  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.429  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.429  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.430  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.430  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.431  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.431  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:07:31.431  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.436  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.436  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.436  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.436  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.437  5658  5704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-20 08:07:31.438  5658  5704 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-20 08:07:31.438  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-20 08:07:31.445  5658  5704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-20 08:07:31.445  5658  5704 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-20 08:07:31.446  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-20 08:07:31.446  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-20 08:07:31.446  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-20 08:07:31.446  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-20 08:07:31.446  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-20 08:07:31.447  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-20 08:07:31.447  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-20 08:07:31.447  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-20 08:07:31.447  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-20 08:07:31.447  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-20 08:07:31.447  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-20 08:07:31.447  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-20 08:07:31.448  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-20 08:07:31.448  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-20 08:07:31.448  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-20 08:07:31.448  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-20 08:07:31.448  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-20 08:07:31.448  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-20 08:07:31.448  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-20 08:07:31.449  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-20 08:07:31.449  5658  5704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,10-20 08:07:31.451  5658  5704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-20 08:07:31.452  5658  5704 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-20 08:07:31.452  5658  5704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-20 08:07:31.452  5658  5704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-20 08:07:31.452  5658  5704 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-20 08:07:31.452  5658  5704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-20 08:07:31.452  5658  5704 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-20 08:07:31.452  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-20 08:07:31.456  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-20 08:07:31.457  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-20 08:07:31.457  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-20 08:07:31.458  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-20 08:07:31.458  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-20 08:07:31.458  5658  5704 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-20 08:07:31.458  5658  5704 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-20 08:07:31.458  5658  5704 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-20 08:07:31.458  5658  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-20 08:07:31.459  5658  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-20 08:07:31.459  5658  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-20 08:07:31.459  5658  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,10-20 08:07:31.459  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:31.459  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.460  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.460  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.460  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.460  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.460  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.460  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,10-20 08:07:31.461  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.461  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.462  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.462  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.462  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.462  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.462  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.462  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.463  5658  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
,10-20 08:07:31.463  5658  5705 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-20 08:07:31.463  5658  5705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-20 08:07:31.463  4642  4642 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32966]" dev="sockfs" ino=32966 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-20 08:07:31.466  4642  4642 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32966]" dev="sockfs" ino=32966 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-20 08:07:31.464  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.464  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.465  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.465  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.466  5658  5704 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-20 08:07:31.466  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:31.467  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-20 08:07:31.467  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.467  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-20 08:07:31.467  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.467  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.467  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.467  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.467  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.467  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.467  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.467  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.467  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.467  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:07:31.467  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.469  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.469  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.469  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.469  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.471  5658  5704 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-20 08:07:31.471  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:31.471  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.471  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.472  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-20 08:07:31.472  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.472  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.472  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.472  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.472  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.472  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.472  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.472  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.472  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:31.472  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.472  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.474  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:31.474  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.474  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.474  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
,10-20 08:07:31.475  5658  5704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-20 08:07:31.475  5658  5704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-20 08:07:31.475  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-20 08:07:31.475  5658  5704 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-20 08:07:31.475  5658  5704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-20 08:07:31.475  5658  5704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-20 08:07:31.475  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-20 08:07:31.475  5658  5704 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-20 08:07:31.475  5658  5704 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-20 08:07:31.476  5658  5704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-20 08:07:31.476  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-20 08:07:31.476  5658  5704 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,10-20 08:07:31.476  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:31.476  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:31.476  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:31.476  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.476  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.476  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.476  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.476  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:31.476  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:31.476  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.476  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.476  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.476  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.476  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.477  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.478  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-20 08:07:31.478  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:31.478  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.478  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.478  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:31.478  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.478  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:31.479  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:31.479  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
,10-20 08:07:31.479  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:31.479  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:31.479  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:31.479  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:31.479  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:32.436   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-20 08:07:33.567   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:34.568   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:35.466   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-20 08:07:35.569   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:36.480  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:36.480  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.480  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-20 08:07:36.480  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.481  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.481  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:36.481  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:36.481  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:36.481  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:36.481  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:36.482  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:36.482  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.482  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.482  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-20 08:07:36.482  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:36.482  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.483  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.483  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:36.483  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.483  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:36.483  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.483  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.486  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:36.486  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:36.487  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.487  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.491  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-20 08:07:36.492  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:07:36.494  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-20 08:07:36.496  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-20 08:07:36.497  5658  5707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-20 08:07:36.497  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-20 08:07:36.498  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-20 08:07:36.498  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-20 08:07:36.498  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-20 08:07:36.499  5658  5658 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-20 08:07:36.499  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:36.499  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-20 08:07:36.499  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-20 08:07:36.499  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-20 08:07:36.499  5658  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-20 08:07:36.500  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.500  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-20 08:07:36.500  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-20 08:07:36.500  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:36.500  5658  5658 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-20 08:07:36.500  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.500  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-20 08:07:36.500  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-20 08:07:36.500  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-20 08:07:36.500  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.500  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.502  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:07:36.503  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.503  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:07:36.503  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:36.503  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-20 08:07:36.503  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:36.503  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:07:36.503  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:36.504  5658  5707 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-20 08:07:36.504  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:36.504  5658  5707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-20 08:07:36.504  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.504  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.504  5658  5707 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-20 08:07:36.504  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-20 08:07:36.500  4868  4868 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30333]" dev="sockfs" ino=30333 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-20 08:07:36.500  4868  4868 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30333]" dev="sockfs" ino=30333 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-20 08:07:36.504  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:36.505  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.505  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.505  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:36.505  5658  5658 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-20 08:07:36.505  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.505  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.505  5658  5658 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:36.505  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:07:36.505  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:36.507  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-20 08:07:36.507  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:36.508  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.508  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.509  5658  5704 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-20 08:07:36.510  5658  5704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-20 08:07:36.510  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-20 08:07:36.510  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-20 08:07:36.510  5658  5704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-20 08:07:36.510  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:36.511  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:36.511  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:36.511  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:36.511  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.511  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:36.511  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:36.511  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:36.511  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.511  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.511  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:36.511  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.511  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.512  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.512  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.514  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:36.515  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-20 08:07:36.515  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.515  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
,10-20 08:07:36.521  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:07:36.521  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:36.521  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:07:36.521  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:36.521  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.521  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.521  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:36.521  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:36.521  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.522  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.522  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
,10-20 08:07:36.522  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.522  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.522  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.522  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.523  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:36.523  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:36.523  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.523  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.524  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:07:36.524  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:07:36.524  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-20 08:07:36.524  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:07:36.524  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.524  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.524  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:07:36.524  5658  5704 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f34334 not in the list
10-20 08:07:36.524  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.524  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.524  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:36.524  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.524  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:36.525  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:36.525  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:36.526  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:07:36.526  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:07:36.526  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:07:36.526  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@145a55d not in the list
10-20 08:07:36.527  5658  5704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-20 08:07:36.528  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-20 08:07:36.528  5658  5704 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-20 08:07:36.528  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-20 08:07:36.528  5658  5704 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-20 08:07:36.528  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-20 08:07:36.530  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-20 08:07:36.530  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-20 08:07:36.531  5658  5704 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,10-20 08:07:36.532  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-20 08:07:36.532  5658  5704 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-20 08:07:36.532  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-20 08:07:36.532  5658  5704 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-20 08:07:36.532  5658  5704 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-20 08:07:36.533  5658  5704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-20 08:07:36.533  5658  5704 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-20 08:07:36.533  5658  5704 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-20 08:07:36.533  5658  5704 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-20 08:07:36.533  5658  5704 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-20 08:07:36.533  5658  5704 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-20 08:07:36.534  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:07:36.535  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3e5ef7 added. We now have 3 listener(s)
,10-20 08:07:36.535  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:07:36.536  5658  5704 D BluetoothAdapter: enable(): BT is already enabled..!
10-20 08:07:36.537   928   939 D WifiService: setWifiEnabled: true pid=5658, uid=10077
10-20 08:07:36.537   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-20 08:07:36.569   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:36.594  4625  4830 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-20 08:07:36.594  4625  4861 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-20 08:07:36.594  5658  5705 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-20 08:07:36.595  5658  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-20 08:07:36.595  5658  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,10-20 08:07:37.004  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-20 08:07:37.570   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:38.495   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-20 08:07:38.571   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-20 08:07:40.450   928  3007 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-20 08:07:41.542  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-20 08:07:41.543  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b87e164 added. We now have 4 listener(s)
10-20 08:07:41.543  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:07:41.555  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:41.555  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b87e164 removed from the list
,10-20 08:07:41.555  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:41.555  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:41.556  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:07:41.558  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:07:41.558  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6df9fcd added. We now have 4 listener(s)
10-20 08:07:41.558  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:07:41.561  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:07:41.561  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6df9fcd removed from the list
10-20 08:07:41.561  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:07:41.562  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:07:41.562  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:07:41.563  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:07:41.563  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@575b082 added. We now have 4 listener(s)
10-20 08:07:41.563  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:07:41.567   928  3451 D WifiService: setWifiEnabled: false pid=5658, uid=10077
10-20 08:07:41.567   928  3451 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-20 08:07:41.571   928  3007 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-20 08:07:41.571   928  3007 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-20 08:07:41.571   928  3007 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-20 08:07:41.571   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:07:41.577  4625  4689 D BluetoothAdapterState: Current state: ON, message: 23
10-20 08:07:41.577  4625  4689 D BluetoothAdapterProperties: Setting state to 13
,10-20 08:07:41.577  4625  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-20 08:07:41.579  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:07:41.582  4625  4689 D BluetoothAdapterProperties: onBluetoothDisable()
,10-20 08:07:41.584  4625  4625 D BluetoothMapService: onReceive
,10-20 08:07:41.584  4625  4625 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-20 08:07:41.584  4625  4625 D BluetoothMapService: STATE_TURNING_OFF
,10-20 08:07:41.584  4625  4625 D BluetoothMapService: MAP Service closeService in
10-20 08:07:41.585  4625  4625 D BluetoothMapMasInstance0: MAP Service shutdown
10-20 08:07:41.585  4625  4625 D ObexServerSockets0: shutdown(block = true)
10-20 08:07:41.585  4625  4877 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-20 08:07:41.586  4625  4625 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-20 08:07:41.585  4625  4689 I BluetoothAdapterState: Entering PendingCommandState
10-20 08:07:41.586  4625  4861 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-20 08:07:41.586  4625  4625 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-20 08:07:41.586  4625  4878 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-20 08:07:41.588  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:41.588  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:41.590  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.590  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:41.590  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:07:41.590  4625  4625 I BtOppRfcommListener: stopping Accept Thread
10-20 08:07:41.590  4625  5323 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-20 08:07:41.591  4625  5323 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-20 08:07:41.593   928  5405 D DhcpClient: Clearing IP address
10-20 08:07:41.593  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:41.593   508   922 D CommandListener: Clearing all IP addresses on wlan0
10-20 08:07:41.596  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.600  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:41.600  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:41.601  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.601  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:07:41.604   508   922 D CommandListener: Setting iface cfg
,10-20 08:07:41.604  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:41.605  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:41.605  3615  5459 V NativeCrypto: Read error: ssl=0x7fa58d7580: I/O error during system call, Connection timed out
10-20 08:07:41.605  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.605  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:41.607  3615  5459 V NativeCrypto: SSL shutdown failed: ssl=0x7fa58d7580: I/O error during system call, Broken pipe
10-20 08:07:41.608  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.609   928  4227 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-20 08:07:41.609   928  5403 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,10-20 08:07:41.611   928  5403 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-20 08:07:41.612   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-20 08:07:41.612   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-20 08:07:41.613   928  3009 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-20 08:07:41.614   928   941 I ActivityManager: Start proc 5711:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-20 08:07:41.615  4625  4702 D BluetoothAdapterProperties: Scan Mode:20
10-20 08:07:41.615  4625  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-20 08:07:41.617   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-20 08:07:41.617   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-20 08:07:41.618   928  5406 D DhcpClient: Receive thread stopped
10-20 08:07:41.621  4625  4625 D HeadsetService: Received stop request...Stopping profile...
10-20 08:07:41.622  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.622  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:41.622   534   534 E Parcel  : Reading a NULL string not supported here.
10-20 08:07:41.622  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.622  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:41.626  3161  3173 D BluetoothHeadset: Proxy object disconnected
10-20 08:07:41.627  3819  4049 D BluetoothHeadset: Proxy object disconnected
10-20 08:07:41.627   928   928 D BluetoothHeadset: Proxy object disconnected
10-20 08:07:41.627   928   928 D BluetoothHeadset: Proxy object disconnected
10-20 08:07:41.627   928   928 D BluetoothHeadset: Proxy object disconnected
10-20 08:07:41.628  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.628  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:07:41.630   928   928 D RttService: SCAN_AVAILABLE : 1
,10-20 08:07:41.629  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:07:41.631  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:41.631   928  3115 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-20 08:07:41.634  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:41.634   928  3009 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-20 08:07:41.635  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.635  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:41.635  4625  4625 D A2dpService: Received stop request...Stopping profile...
10-20 08:07:41.635  3778  3925 W QCNEJ   : |CORE| network lost: 100
10-20 08:07:41.636  4625  4870 D A2dpStateMachine: Exit Disconnected: -1
10-20 08:07:41.636  3778  3925 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-20 08:07:41.637   928   928 D BluetoothA2dp: Proxy object disconnected
,10-20 08:07:41.638  4625  4625 D HidService: Received stop request...Stopping profile...
10-20 08:07:41.638  4625  4625 D HidService: Stopping Bluetooth HidService
10-20 08:07:41.639   928  3007 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-20 08:07:41.639  4625  4625 D HealthService: Received stop request...Stopping profile...
10-20 08:07:41.641  3161  3161 D HeadsetProfile: Bluetooth service disconnected
10-20 08:07:41.641  4625  4625 D PanService: Received stop request...Stopping profile...
10-20 08:07:41.643  4625  4625 D BluetoothMapService: Received stop request...Stopping profile...
,10-20 08:07:41.643  4625  4625 D BluetoothMapService: stop()
10-20 08:07:41.644  4625  4625 D BluetoothMapAppObserver: deinitObservers()
10-20 08:07:41.644  4625  4625 D BluetoothMapAppObserver: removeReceiver()
,10-20 08:07:41.645  4625  4625 V BluetoothAdapterState: isTurningOff()=true
10-20 08:07:41.646  4625  4625 V BluetoothAdapterState: isTurningOn()=false
,10-20 08:07:41.646  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:41.646  4625  4625 V BluetoothAdapterState: isBleTurningOff()=false
,10-20 08:07:41.647   928  3007 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-20 08:07:41.648  3161  3161 D BluetoothA2dp: Proxy object disconnected
10-20 08:07:41.648  3161  3161 D BluetoothInputDevice: Proxy object disconnected
10-20 08:07:41.649  3161  3161 D HidProfile: Bluetooth service disconnected
,10-20 08:07:41.650  4625  4625 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-20 08:07:41.650  4625  4702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,10-20 08:07:41.650  4625  4830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:07:41.650  4625  4625 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-20 08:07:41.650  4625  4830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:07:41.650  4625  4830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:07:41.651  4625  4702 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-20 08:07:41.652  4625  4625 D SapService: Received stop request...Stopping profile...
10-20 08:07:41.652  4625  4625 V SapService: stop()
10-20 08:07:41.653  4625  4625 V BluetoothAdapterState: isTurningOff()=true
10-20 08:07:41.653  4625  4625 V BluetoothAdapterState: isTurningOn()=false
10-20 08:07:41.653  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:41.653  4625  4625 V BluetoothAdapterState: isBleTurningOff()=false
,10-20 08:07:41.655  4625  4625 V BluetoothAdapterState: isTurningOff()=true
10-20 08:07:41.655  4625  4830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:07:41.655  4625  4625 V BluetoothAdapterState: isTurningOn()=false
,10-20 08:07:41.655  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:41.655  4625  4830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:07:41.655  4625  4625 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:41.655  4625  4702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-20 08:07:41.656  4625  4625 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-20 08:07:41.656  4625  4625 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-20 08:07:41.656  4625  4625 V BluetoothAdapterState: isTurningOff()=true
10-20 08:07:41.656  4625  4625 V BluetoothAdapterState: isTurningOn()=false
10-20 08:07:41.656  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
,10-20 08:07:41.656  4625  4830 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-20 08:07:41.656  4625  4625 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:41.656  4625  4830 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-20 08:07:41.656  4625  4830 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-20 08:07:41.657  4625  4830 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-20 08:07:41.657  4625  4625 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-20 08:07:41.657  4625  4702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-20 08:07:41.657  4625  4702 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-20 08:07:41.657  4625  4625 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-20 08:07:41.658  4625  4625 V BluetoothAdapterState: isTurningOff()=true
10-20 08:07:41.658  4625  4625 V BluetoothAdapterState: isTurningOn()=false
10-20 08:07:41.658  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
,10-20 08:07:41.658  4625  4625 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:41.658  4625  4625 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-20 08:07:41.658  4625  4625 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-20 08:07:41.659  4625  4625 D BluetoothMapService: MAP Service closeService in
10-20 08:07:41.659  4625  4625 V BluetoothAdapterState: isTurningOff()=true
10-20 08:07:41.659  4625  4625 V BluetoothAdapterState: isTurningOn()=false
10-20 08:07:41.659  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:41.659  4625  4625 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:41.660  4625  4625 D BluetoothMapService: cleanup()
10-20 08:07:41.660  4625  4625 D BluetoothMapService: MAP Service closeService in
,10-20 08:07:41.660  4625  4625 V BluetoothAdapterState: isTurningOff()=true
10-20 08:07:41.660  4625  4625 V BluetoothAdapterState: isTurningOn()=false
10-20 08:07:41.660  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:41.660  4625  4625 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:41.661  4625  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-20 08:07:41.661  4625  4689 D BluetoothAdapterProperties: Setting state to 15
,10-20 08:07:41.661  4625  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-20 08:07:41.661  4625  4689 I BluetoothAdapterState: Entering BleOnState
10-20 08:07:41.661  3819  3848 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:07:41.662   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:07:41.662  3161  3182 D BluetoothPan: onBluetoothStateChange on: false
10-20 08:07:41.663  3161  3173 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:07:41.663   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-20 08:07:41.663  3161  4007 D BluetoothA2dp: onBluetoothStateChange: up=false
10-20 08:07:41.664   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:07:41.665  3161  3926 D BluetoothMap: onBluetoothStateChange: up=false
10-20 08:07:41.665  3161  3182 D BluetoothPbap: onBluetoothStateChange: up=false
,10-20 08:07:41.667  3161  3173 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-20 08:07:41.668   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:07:41.668  4625  4689 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-20 08:07:41.668  4625  4689 D BluetoothAdapterProperties: Setting state to 16
10-20 08:07:41.668  4625  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-20 08:07:41.669  4625  4689 D BluetoothAdapterProperties: onBleDisable
10-20 08:07:41.669  5711  5711 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-20 08:07:41.669  4625  4689 I BluetoothAdapterState: Entering PendingCommandState
10-20 08:07:41.669  4625  4692 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-20 08:07:41.670  4625  4830 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,10-20 08:07:41.670  4625  4830 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:07:41.671  4625  4702 D BluetoothAdapterProperties: Scan Mode:20
,10-20 08:07:41.674  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:07:41.674   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-20 08:07:41.676  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:41.678  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:41.680  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.681  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.682  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:41.690  5711  5711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-20 08:07:41.697  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-20 08:07:41.698   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-20 08:07:41.698   508   922 D CommandListener: Clearing all IP addresses on wlan0
10-20 08:07:41.699   508   922 D TetherController: Setting IP forward enable = 0
10-20 08:07:41.699   928  3009 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-20 08:07:41.699   928  3009 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-20 08:07:41.699   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79a28e2:true
,10-20 08:07:41.711   928  4227 I ActivityManager: Start proc 5733:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-20 08:07:41.712   928  3007 D DhcpClient: doQuit
10-20 08:07:41.712   928  3007 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-20 08:07:41.712   928  5405 D DhcpClient: onQuitting
,10-20 08:07:41.713  3485  3485 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-20 08:07:41.714   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-20 08:07:41.718  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.718  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:41.719  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.719  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:41.722  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.722  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:41.722  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.722  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:41.724  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:41.724  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:07:41.725  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:41.725  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:41.727  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.730  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.732  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.732  5310  5310 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@738a02d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-20 08:07:41.735  5076  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-20 08:07:41.735  5076  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-20 08:07:41.735  5076  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-20 08:07:41.735  5076  5089 E SarControlService: no key has been found,reset the power
10-20 08:07:41.735  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-20 08:07:41.735  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-20 08:07:41.735  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-20 08:07:41.736  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-20 08:07:41.736  5102  5102 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-20 08:07:41.737  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-20 08:07:41.737  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-20 08:07:41.737  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-20 08:07:41.738  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-20 08:07:41.738  5102  5102 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-20 08:07:41.741  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000ea03000000000000ffffffff]
10-20 08:07:41.741  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:07:41.741  5102  5116 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-20 08:07:41.742  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-20 08:07:41.742  5076  5087 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-20 08:07:41.743  3485  3485 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-20 08:07:41.747  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000eb03000000000000ffffffff]
10-20 08:07:41.747  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:07:41.747  5102  5116 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-20 08:07:41.747  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-20 08:07:41.748  5076  5086 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-20 08:07:41.749  3485  3485 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-20 08:07:41.763  5711  5711 D LocalBluetoothProfileManager: Adding local MAP profile
,10-20 08:07:41.765  5711  5711 D BluetoothMap: Create BluetoothMap proxy object
,10-20 08:07:41.777  5733  5733 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-20 08:07:41.780  5711  5711 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-20 08:07:41.781  3485  3485 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-20 08:07:41.794  3485  3485 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-20 08:07:41.795  5711  5711 D DockEventReceiver: finishStartingService: stopping service
,10-20 08:07:41.802   928  3450 I ActivityManager: Killing 5039:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-20 08:07:41.874  4625  4702 I bt_hci  : shut_down
,10-20 08:07:41.875  4625  4708 D bt_hwcfg: hw_epilog_process
,10-20 08:07:41.876  4625  4708 I bt_vendor: low_power_mode_cb
,10-20 08:07:41.879  4625  4708 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-20 08:07:41.879  4625  4708 I bt_vendor: epilog_cb
10-20 08:07:41.879  4625  4708 I bt_hci  : epilog_finished_callback
,10-20 08:07:41.881  4625  4702 I bt_hci_h4: hal_close
,10-20 08:07:41.881  4625  4702 I bt_userial_vendor: device fd = 54 close
,10-20 08:07:41.898   928  3007 D wifi    : In wifi stop Hal
,10-20 08:07:41.898  4440  4440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-20 08:07:41.898   928  3007 D wifi    : halHandle = 0x7f89218480, mVM = 0x7fa584d140, mCls = 0x100a02
10-20 08:07:41.898   928  3483 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-20 08:07:41.898   928  3483 D WifiHAL : Got a signal to exit!!!
10-20 08:07:41.899   928  3483 I WifiHAL : Exit wifi_event_loop
,10-20 08:07:41.900  3933  4253 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-20 08:07:41.901  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:41.901   928  3007 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
,10-20 08:07:41.901   928  3007 E WifiHAL : Event processing terminated
10-20 08:07:41.902   928  3007 D wifi    : In wifi cleaned up handler
10-20 08:07:41.902   928  3007 I WifiHAL : Internal cleanup completed
,10-20 08:07:41.903  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:41.905  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:41.919   928  3483 D wifi    : set interface wlan0 flags (DOWN)
10-20 08:07:41.920   928  3007 D WifiNative-HAL: HAL event thread stopped successfully
,10-20 08:07:41.954  5733  5733 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.io.File.exists(File.java:361)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-20 08:07:41.954  5733  5733 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:07:41.954  5733  5733 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:07:41.954  5733  5733 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:170)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.954  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:07:41.955  5733  5733 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.r.k.d(PG:583)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:170)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:07:41.955  5733  5733 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.File.exists(File.java:361)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:07:41.955  5733  5733 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.File.exists(File.java:361)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:07:41.955  5733  5733 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:07:41.955  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:07:41.962  5711  5711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-20 08:07:41.967  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-20 08:07:41.975  5711  5711 D DockEventReceiver: finishStartingService: stopping service
10-20 08:07:41.978   928  4228 I ActivityManager: Killing 5431:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-20 08:07:42.002  4093  4093 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-20 08:07:42.002  4625  4692 D bt_stack_manager: event_shut_down_stack finished.
10-20 08:07:42.003  4625  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-20 08:07:42.005  4625  4625 D BtGatt.DebugUtils: handleDebugAction() action=null
10-20 08:07:42.005  4625  4689 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-20 08:07:42.005  4093  4093 D SystemUpdateService: onCreate
10-20 08:07:42.005  4625  4625 D BtGatt.GattService: Received stop request...Stopping profile...
10-20 08:07:42.005  4625  4625 D BtGatt.GattService: stop()
10-20 08:07:42.005  4625  4625 D BtGatt.AdvertiseManager: advertise clients cleared
10-20 08:07:42.007  4625  4625 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:42.007  4625  4625 V BluetoothAdapterState: isTurningOn()=false
10-20 08:07:42.007  4625  4625 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:42.007  4625  4625 V BluetoothAdapterState: isBleTurningOff()=true
10-20 08:07:42.007  4625  4689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-20 08:07:42.007  4625  4689 D BluetoothAdapterProperties: Setting state to 10
10-20 08:07:42.007  4625  4689 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-20 08:07:42.007  4625  4689 I BluetoothAdapterState: Entering OffState
10-20 08:07:42.008  4093  4093 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-20 08:07:42.009   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-20 08:07:42.017  4625  4625 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-20 08:07:42.017  4625  4625 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-20 08:07:42.017  4625  4625 I BluetoothServiceJni: cleanupNative: return from cleanup
10-20 08:07:42.018  4625  4692 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-20 08:07:42.023  4093  4093 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-20 08:07:42.030  4625  4692 D bt_stack_manager: event_clean_up_stack finished.
,10-20 08:07:42.039  4625  4625 I art     : System.exit called, status: 0
,10-20 08:07:42.039  4625  4625 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-20 08:07:42.041  4093  5429 I iu.UploadsManager: num queued entries: 0
,10-20 08:07:42.041  4093  5429 I iu.UploadsManager: num updated entries: 0
10-20 08:07:42.042  4093  5429 I iu.SyncManager: NEXT; no task
,10-20 08:07:42.051  4093  4093 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-20 08:07:42.052  4093  4093 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-20 08:07:42.057  4093  5769 I SystemUpdateService: active receiver: enabled
,10-20 08:07:42.062  4093  5769 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-20 08:07:42.064   928  3986 I ActivityManager: Start proc 5772:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-20 08:07:42.070  4093  5769 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-20 08:07:42.071  4093  5769 I SystemUpdateService: now status is 0 (complete)
10-20 08:07:42.071  4093  5769 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-20 08:07:42.071  4093  5769 I SystemUpdateService: file has been verified
10-20 08:07:42.072  4093  5769 I SystemUpdateService: OTA package size = 21989297
,10-20 08:07:42.078   928   939 I ActivityManager: Process com.android.bluetooth (pid 4625) has died
,10-20 08:07:42.099  5772  5772 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-20 08:07:42.101  5772  5772 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-20 08:07:42.112  5772  5772 D SprintDMHelper: simOperator: 
,10-20 08:07:42.112  5772  5772 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-20 08:07:42.122   928   945 D Tethering: InitialState.processMessage what=4
,10-20 08:07:42.123  4440  5785 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-20 08:07:42.125   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-20 08:07:42.138   928  3986 I ActivityManager: Start proc 5786:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-20 08:07:42.147  4093  5769 I SystemUpdateService: showing system update notification
,10-20 08:07:42.168  5786  5786 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-20 08:07:42.181   928  3450 I ActivityManager: Killing 5310:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-20 08:07:42.225  4093  4093 D SystemUpdateService: onDestroy
,10-20 08:07:42.229   928  3986 I ActivityManager: Killing 4715:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-20 08:07:42.349  5733  5757 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-20 08:07:42.358   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f6dc7b7:true
,10-20 08:07:42.817   508   922 E Netd    : netlink response contains error (No such file or directory)
,10-20 08:07:42.819   928  3009 E NetdConnector: NDC Command {112 network destroy 100} took too long (1106ms)
,10-20 08:07:42.819   928  3009 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-20 08:07:42.819   928  3009 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-20 08:07:42.822   928  3005 E NetdConnector: NDC Command {113 bandwidth setglobalalert 2097152} took too long (1103ms)
,10-20 08:07:42.823   928  3004 E NetdConnector: NDC Command {114 bandwidth gettetherstats} took too long (697ms)
,10-20 08:07:42.823   508   922 D TetherController: Setting IP forward enable = 0
,10-20 08:07:46.592   928  3986 D WifiService: setWifiEnabled: true pid=5658, uid=10077
,10-20 08:07:46.593   928  3986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-20 08:07:46.600   508   922 D SoftapController: Softap fwReload - Ok
,10-20 08:07:46.606   508   922 D CommandListener: Setting iface cfg
,10-20 08:07:46.606   508   922 D CommandListener: Trying to bring down wlan0
10-20 08:07:46.608   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-20 08:07:46.615   928  3007 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-20 08:07:47.187   928  3007 D wifi    : set interface wlan0 flags (UP)
,10-20 08:07:47.189   928  3007 I WifiHAL : Initializing wifi
10-20 08:07:47.190   928  3007 I WifiHAL : Creating socket
,10-20 08:07:47.192   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-20 08:07:47.192   928  3007 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-20 08:07:47.192   928  3007 D wifi    : Did set static halHandle = 0x7f89218480
,10-20 08:07:47.192   928  3007 D wifi    : halHandle = 0x7f89218480, mVM = 0x7fa584d140, mCls = 0x10189a
10-20 08:07:47.192   928  3007 D wifi    : array field set
10-20 08:07:47.193   928  3007 I WifiNative-HAL: interface[0] = wlan0
10-20 08:07:47.196   928  5808 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547761521792
10-20 08:07:47.196   928  5808 D wifi    : waitForHalEvents called, vm = 0x7fa584d140, obj = 0x10189a, env = 0x7f8892a840
,10-20 08:07:47.257  5809  5809 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-20 08:07:47.274  5809  5809 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-20 08:07:47.298   928  3007 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-20 08:07:47.305  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:47.306  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:47.308  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:47.343  5809  5809 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-20 08:07:47.343  5809  5809 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-20 08:07:47.368   928  3007 D WifiConfigStore: Loading config and enabling all networks 
,10-20 08:07:47.369  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:47.370  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:07:47.370  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:07:47.370  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:47.372  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:47.372  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:47.372  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:47.372  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:47.375  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:47.375  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:07:47.375  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:47.375  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:47.388   928  3007 D WifiConfigStore: loaded 0 passpoint configs
,10-20 08:07:47.388   928  3007 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-20 08:07:47.388   928  3007 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-20 08:07:47.389   928  3007 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-20 08:07:47.391   928  3007 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-20 08:07:47.391   928  3007 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-20 08:07:47.391   928  3007 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-20 08:07:47.391   928  3007 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-20 08:07:47.394   928  3007 D WifiNative-HAL: Setting external_sim to 1
,10-20 08:07:47.395  4440  4440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-20 08:07:47.395   928  3007 D wifi    : setting dfs flag to true, 0x7f8beff3a0
,10-20 08:07:47.396   928  3007 D WifiStateMachine: Setting OUI to DA-A1-19
10-20 08:07:47.396   928  3007 D wifi    : setting scan oui 0x7f8beff3a0
10-20 08:07:47.396   928  3007 D WifiHAL : Sending mac address OUI
,10-20 08:07:47.400   928  3007 E native  : do suspend false
,10-20 08:07:47.411   928  3007 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-20 08:07:47.411   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-20 08:07:47.411   928   928 D RttService: SCAN_AVAILABLE : 3
10-20 08:07:47.411   928  3115 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-20 08:07:47.412   508   922 D CommandListener: Setting iface cfg
,10-20 08:07:47.416   928  3006 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,10-20 08:07:47.417   928  3006 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-20 08:07:47.427   928  3006 D WifiNative-HAL: p2pGetDeviceAddress
,10-20 08:07:47.433   928  3006 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-20 08:07:47.433   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267676 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,10-20 08:07:50.512  5809  5809 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:07:50.516  5809  5809 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:07:50.522  5809  5809 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:07:50.526  5809  5809 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:07:50.569   928  3007 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-20 08:07:50.570   928  3007 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-20 08:07:50.571   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:07:50.582   928  3007 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-20 08:07:50.616   928  3007 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-20 08:07:50.619  5809  5809 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-20 08:07:51.043  5809  5809 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-20 08:07:51.077  5809  5809 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-20 08:07:51.079  5809  5809 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-20 08:07:51.091   928  3007 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-20 08:07:51.091   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:07:51.091   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-20 08:07:51.109   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:07:51.120   508   922 D CommandListener: Setting iface cfg
,10-20 08:07:51.126   928  3007 D WifiStateMachine: Start Dhcp Watchdog 2
,10-20 08:07:51.131   928  5817 D DhcpClient: Receive thread started
,10-20 08:07:51.136   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-20 08:07:51.136   928  3007 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-20 08:07:51.136   928  3009 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-20 08:07:51.217   928  3007 E native  : do suspend false
,10-20 08:07:51.233   928  5816 D DhcpClient: Broadcasting DHCPDISCOVER
,10-20 08:07:51.245   928  5817 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172569, domain null
,10-20 08:07:51.246   928  5816 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172569 seconds
,10-20 08:07:51.248   928  5816 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-20 08:07:51.263   928  5817 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-20 08:07:51.264   928  5816 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-20 08:07:51.268   508   922 D CommandListener: Setting iface cfg
,10-20 08:07:51.272   928  3007 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-20 08:07:51.279   928  5816 D DhcpClient: Scheduling renewal in 86399s
,10-20 08:07:51.286   928  3007 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-20 08:07:51.287   928  3007 D WifiConfigStore: No blacklist allowed without epno enabled
,10-20 08:07:51.288   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-20 08:07:51.290   928  3009 D ConnectivityService: Adding iface wlan0 to network 101
,10-20 08:07:51.295   928  3007 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-20 08:07:51.340   928  3009 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-20 08:07:51.340   928  3009 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-20 08:07:51.342   928  3009 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-20 08:07:51.346   928  3009 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-20 08:07:51.350   928  3009 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-20 08:07:51.358   928  3009 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-20 08:07:51.362   928  3009 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-20 08:07:51.362   928  3009 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-20 08:07:51.362   928  3009 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-20 08:07:51.363   928  3007 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-20 08:07:51.363   928  3009 D ConnectivityService:    accepting network in place of null
10-20 08:07:51.363   928  3007 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-20 08:07:51.363   928  3009 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-20 08:07:51.378   928  5815 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271621, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-20 08:07:51.393   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-20 08:07:51.418   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-20 08:07:51.421  3778  3925 W QCNEJ   : |CORE| network available: 101
10-20 08:07:51.422   928  3009 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-20 08:07:51.422   928  3009 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-20 08:07:51.423   928  3009 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-20 08:07:51.423  3778  3925 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-20 08:07:51.424  3778  3925 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-20 08:07:51.425  3778  3925 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-20 08:07:51.426   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-20 08:07:51.429  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:51.429  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:51.429  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.430  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:51.433  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:51.433  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:51.433  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.433  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:51.435  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:07:51.435  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:07:51.435  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.435  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:07:51.442  5076  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-20 08:07:51.442  5076  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-20 08:07:51.442  5076  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-20 08:07:51.442  5076  5089 E SarControlService: no key has been found,reset the power
10-20 08:07:51.442  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-20 08:07:51.442  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-20 08:07:51.442  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-20 08:07:51.443  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-20 08:07:51.443  5102  5102 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-20 08:07:51.444  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-20 08:07:51.444  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-20 08:07:51.445  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-20 08:07:51.445  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-20 08:07:51.445  5102  5102 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-20 08:07:51.448  4093  4093 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-20 08:07:51.450  4093  4093 D SystemUpdateService: onCreate
10-20 08:07:51.452  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000ec03000000000000ffffffff]
10-20 08:07:51.452  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:07:51.452  5102  5116 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-20 08:07:51.452  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-20 08:07:51.452  5076  5087 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-20 08:07:51.455   928  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,10-20 08:07:51.456  4093  4093 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-20 08:07:51.457  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000ed03000000000000ffffffff]
10-20 08:07:51.457  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:07:51.457  5102  5116 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-20 08:07:51.458  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-20 08:07:51.458  5076  5086 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-20 08:07:51.467  4093  4093 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-20 08:07:51.474  4093  5429 I iu.UploadsManager: num queued entries: 0
,10-20 08:07:51.474  4093  5429 I iu.UploadsManager: num updated entries: 0
10-20 08:07:51.475  4093  5429 I iu.SyncManager: NEXT; no task
,10-20 08:07:51.477  4093  4093 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-20 08:07:51.479  4093  4093 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-20 08:07:51.480  5772  5772 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-20 08:07:51.484  5772  5772 D SprintDMHelper: simOperator: 
,10-20 08:07:51.484  5772  5772 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-20 08:07:51.484  4093  5827 I SystemUpdateService: active receiver: enabled
,10-20 08:07:51.505  4093  5827 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-20 08:07:51.508   928  5814 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 20 Oct 2016 12:07:51 GMT], X-Android-Received-Millis=[1476965271507], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476965271481]}
,10-20 08:07:51.509   928  3009 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-20 08:07:51.509   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-20 08:07:51.509   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-20 08:07:51.510   928  3009 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-20 08:07:51.519  4093  5827 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-20 08:07:51.519  4093  5827 I SystemUpdateService: now status is 0 (complete)
,10-20 08:07:51.519  4093  5827 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-20 08:07:51.519  4093  5827 I SystemUpdateService: file has been verified
10-20 08:07:51.519  4093  5827 I SystemUpdateService: OTA package size = 21989297
,10-20 08:07:51.525  4093  5827 I SystemUpdateService: showing system update notification
,10-20 08:07:51.535  4093  4093 D SystemUpdateService: onDestroy
,10-20 08:07:51.582  4440  5831 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-20 08:07:51.598   928  3188 D WifiService: setWifiEnabled: false pid=5658, uid=10077
,10-20 08:07:51.598   928  3188 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-20 08:07:51.599   928  3007 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-20 08:07:51.599   928  3007 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-20 08:07:51.599   928  3007 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-20 08:07:51.599   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:07:51.607   928  5816 D DhcpClient: Clearing IP address
10-20 08:07:51.607   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-20 08:07:51.609   508   922 D CommandListener: Setting iface cfg
,10-20 08:07:51.614  3615  5838 V NativeCrypto: Read error: ssl=0x7f8a86c380: I/O error during system call, Connection timed out
,10-20 08:07:51.614  3615  5838 V NativeCrypto: SSL shutdown failed: ssl=0x7f8a86c380: I/O error during system call, Broken pipe
,10-20 08:07:51.618   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-20 08:07:51.619   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-20 08:07:51.622   534   534 E Parcel  : Reading a NULL string not supported here.
,10-20 08:07:51.627   928   928 D RttService: SCAN_AVAILABLE : 1
10-20 08:07:51.627   928  3115 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-20 08:07:51.628   928  3007 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-20 08:07:51.629   928  3009 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-20 08:07:51.630   928  5817 D DhcpClient: Receive thread stopped
10-20 08:07:51.631   928  3007 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-20 08:07:51.632  3778  3925 W QCNEJ   : |CORE| network lost: 101
10-20 08:07:51.632  3778  3925 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-20 08:07:51.650   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-20 08:07:51.670   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-20 08:07:51.670   928  3009 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-20 08:07:51.670   508   922 D CommandListener: Clearing all IP addresses on wlan0
10-20 08:07:51.670   928  3009 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-20 08:07:51.671   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-20 08:07:51.674  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:51.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:07:51.674  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.674  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:51.676  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:51.676  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:51.676  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.677  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:51.679  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:51.679  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:51.679  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.679  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:51.684  4093  4093 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-20 08:07:51.685  5076  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-20 08:07:51.685  5076  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-20 08:07:51.685  5076  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-20 08:07:51.685  5076  5089 E SarControlService: no key has been found,reset the power
10-20 08:07:51.685  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-20 08:07:51.685  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-20 08:07:51.685  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-20 08:07:51.686  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-20 08:07:51.686  5102  5102 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-20 08:07:51.687  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-20 08:07:51.687  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-20 08:07:51.687  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-20 08:07:51.688  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-20 08:07:51.688  5102  5102 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-20 08:07:51.691  4093  4093 D SystemUpdateService: onCreate
10-20 08:07:51.692  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000ee03000000000000ffffffff]
10-20 08:07:51.692  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:07:51.692  5102  5116 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-20 08:07:51.692  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-20 08:07:51.693  5076  5086 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-20 08:07:51.694  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000ef03000000000000ffffffff]
10-20 08:07:51.694  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:07:51.694  5102  5116 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-20 08:07:51.695  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-20 08:07:51.695  5076  5087 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-20 08:07:51.697  4093  4093 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-20 08:07:51.700  4093  5848 I SystemUpdateService: active receiver: enabled
,10-20 08:07:51.705  4093  4093 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-20 08:07:51.710  4093  5429 I iu.UploadsManager: num queued entries: 0
,10-20 08:07:51.711  4093  5429 I iu.UploadsManager: num updated entries: 0
10-20 08:07:51.711  4093  5429 I iu.SyncManager: NEXT; no task
,10-20 08:07:51.713  4093  4093 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-20 08:07:51.714  4093  4093 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-20 08:07:51.716  5772  5772 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-20 08:07:51.719   508   922 E Netd    : netlink response contains error (No such file or directory)
10-20 08:07:51.720  5772  5772 D SprintDMHelper: simOperator: 
10-20 08:07:51.720  5772  5772 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-20 08:07:51.721   928  3009 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-20 08:07:51.722   928  3007 D DhcpClient: doQuit
,10-20 08:07:51.722   928  3007 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-20 08:07:51.722   928  5816 D DhcpClient: onQuitting
10-20 08:07:51.720  4093  5848 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-20 08:07:51.723  5809  5809 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-20 08:07:51.727  4093  5848 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-20 08:07:51.727  4093  5848 I SystemUpdateService: now status is 0 (complete)
10-20 08:07:51.727  4093  5848 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-20 08:07:51.727  4093  5848 I SystemUpdateService: file has been verified
10-20 08:07:51.727  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.727  4093  5848 I SystemUpdateService: OTA package size = 21989297
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:51.727  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:51.727  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.727  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:51.728  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:51.728  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:51.729  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.729  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:51.730  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:51.730  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:51.730  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:07:51.730  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:51.732  4440  5851 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-20 08:07:51.739  5809  5809 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-20 08:07:51.742  5809  5809 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-20 08:07:51.751  4093  5848 I SystemUpdateService: showing system update notification
,10-20 08:07:51.758  4093  4093 D SystemUpdateService: onDestroy
,10-20 08:07:51.778  5809  5809 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-20 08:07:51.784  5809  5809 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-20 08:07:51.790  4440  4440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-20 08:07:51.790   928  3007 D wifi    : In wifi stop Hal
,10-20 08:07:51.790   928  3007 D wifi    : halHandle = 0x7f89218480, mVM = 0x7fa584d140, mCls = 0x10189a
10-20 08:07:51.790   928  5808 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-20 08:07:51.790   928  5808 D WifiHAL : Got a signal to exit!!!
10-20 08:07:51.790   928  5808 I WifiHAL : Exit wifi_event_loop
10-20 08:07:51.792   928  3007 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-20 08:07:51.792   928  3007 E WifiHAL : Event processing terminated
10-20 08:07:51.792  3933  4253 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-20 08:07:51.793   928  3007 D wifi    : In wifi cleaned up handler
10-20 08:07:51.793   928  3007 I WifiHAL : Internal cleanup completed
10-20 08:07:51.793  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:51.794  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:51.795  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:51.812   928  5808 D wifi    : set interface wlan0 flags (DOWN)
,10-20 08:07:51.812   928  3007 D WifiNative-HAL: HAL event thread stopped successfully
,10-20 08:07:52.019   928   945 D Tethering: InitialState.processMessage what=4
,10-20 08:07:52.026   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-20 08:07:52.421   928  3009 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-20 08:07:53.572   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:54.573   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:55.573   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:56.574   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:56.637   928   945 I ActivityManager: Start proc 5853:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-20 08:07:56.728  5853  5853 D AdapterServiceConfig: Adding HeadsetService
,10-20 08:07:56.728  5853  5853 D AdapterServiceConfig: Adding A2dpService
10-20 08:07:56.728  5853  5853 D AdapterServiceConfig: Adding HidService
10-20 08:07:56.728  5853  5853 D AdapterServiceConfig: Adding HealthService
10-20 08:07:56.728  5853  5853 D AdapterServiceConfig: Adding PanService
10-20 08:07:56.729  5853  5853 D AdapterServiceConfig: Adding GattService
10-20 08:07:56.729  5853  5853 D AdapterServiceConfig: Adding BluetoothMapService
10-20 08:07:56.729  5853  5853 D AdapterServiceConfig: Adding SapService
,10-20 08:07:56.739   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f1e3e8b:true
,10-20 08:07:56.739  5853  5853 D BluetoothAdapterState: make() - Creating AdapterState
,10-20 08:07:56.742  5853  5853 I bt_bluedroid: init
10-20 08:07:56.742  5853  5865 I BluetoothAdapterState: Entering OffState
,10-20 08:07:56.744  5853  5866 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-20 08:07:56.744  5853  5866 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-20 08:07:56.745  5853  5866 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-20 08:07:56.745  5853  5866 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-20 08:07:56.745  5853  5853 I bt_bluedroid: get_profile_interface socket
,10-20 08:07:56.747  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-20 08:07:56.747  5853  5853 I bt_bluedroid: get_profile_interface sdp
10-20 08:07:56.748  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-20 08:07:56.751  5853  5864 I bt_bluedroid: config_hci_snoop_log
,10-20 08:07:56.752   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-20 08:07:56.756  5853  5865 D BluetoothAdapterState: Current state: OFF, message: 0
,10-20 08:07:56.756  5853  5865 D BluetoothAdapterProperties: Setting state to 14
10-20 08:07:56.756  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-20 08:07:56.757  5853  5865 D BluetoothBondStateMachine: make
,10-20 08:07:56.758  5853  5870 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-20 08:07:56.761  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,10-20 08:07:56.762  5853  5853 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-20 08:07:56.764  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:07:56.764  5853  5853 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-20 08:07:56.765  5853  5853 D BtGatt.GattService: Received start request. Starting profile...
10-20 08:07:56.765  5853  5853 D BtGatt.GattService: start()
10-20 08:07:56.765  5853  5853 I bt_bluedroid: get_profile_interface gatt
10-20 08:07:56.766  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:07:56.766  5853  5853 D BtGatt.AdvertiseManager: advertise manager created
,10-20 08:07:56.770  5853  5853 V BluetoothAdapterState: isTurningOff()=false
,10-20 08:07:56.770  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:07:56.770  5853  5853 V BluetoothAdapterState: isBleTurningOn()=true
10-20 08:07:56.770  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:56.771  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-20 08:07:56.772  5853  5865 I bt_bluedroid: bt_bluedroid
10-20 08:07:56.772  5853  5866 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-20 08:07:56.772  5853  5866 I bt_hci  : start_up
,10-20 08:07:56.777  5853  5866 I bt_vendor: alloc value 0xf410b871
10-20 08:07:56.777  5853  5866 I bt_vendor: init
,10-20 08:07:56.777  5853  5866 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-20 08:07:56.777  5853  5866 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-20 08:07:56.890  5853  5866 D bt_hci  : start_up starting async portion
10-20 08:07:56.891  5853  5873 I bt_hci  : event_finish_startup
10-20 08:07:56.891  5853  5873 I bt_hci_h4: hal_open
,10-20 08:07:56.891  5853  5873 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-20 08:07:56.890  5874  5874 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-20 08:07:56.894  5853  5873 I bt_userial_vendor: device fd = 54 open
,10-20 08:07:56.908  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-20 08:07:56.911  5853  5873 D bt_hwcfg: Chipset BCM4358A3
,10-20 08:07:56.911  5853  5873 D bt_hwcfg: Target name = [BCM4358A3]
,10-20 08:07:56.911  5853  5873 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-20 08:07:57.296  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-20 08:07:57.296  5853  5873 D bt_hwcfg: Settlement delay -- 100 ms
,10-20 08:07:57.296  5853  5873 I bt_hwcfg: Setting fw settlement delay to 100 
,10-20 08:07:57.431  5853  5873 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-20 08:07:57.431  5853  5873 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-20 08:07:57.434  5853  5873 I bt_hwcfg: vendor lib fwcfg completed
,10-20 08:07:57.434  5853  5873 I bt_vendor: firmware callback
10-20 08:07:57.434  5853  5873 I bt_hci  : firmware_config_callback
,10-20 08:07:57.443  5853  5876 I bt_btu  : btu_task pending for preload complete event
,10-20 08:07:57.443  5853  5876 I bt_btu_task: Bluetooth chip preload is complete
,10-20 08:07:57.443  5853  5876 I bt_btu  : btu_task received preload complete event
,10-20 08:07:57.449  5853  5876 I         : BTE_InitTraceLevels -- TRC_HCI
,10-20 08:07:57.450  5853  5876 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-20 08:07:57.450  5853  5876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-20 08:07:57.450  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVDT
10-20 08:07:57.450  5853  5876 I         : BTE_InitTraceLevels -- TRC_AVRC
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_A2D
,10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_BNEP
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTM
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_GAP
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_PAN
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_SDP
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_GATT
,10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_SMP
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-20 08:07:57.451  5853  5876 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-20 08:07:57.534  5853  5876 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4089549
,10-20 08:07:57.534  5853  5876 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4089549 
,10-20 08:07:57.550  5853  5869 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-20 08:07:57.551  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-20 08:07:57.552  5853  5869 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-20 08:07:57.555  5853  5869 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-20 08:07:57.557  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
,10-20 08:07:57.557  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
10-20 08:07:57.558  5853  5869 D bt_hci  : do_postload posting postload work item
,10-20 08:07:57.559  5853  5873 I bt_hci  : event_postload
10-20 08:07:57.559  5853  5873 I bt_vendor: sco_config_cb
10-20 08:07:57.559  5853  5873 I bt_hci  : sco_config_callback postload finished.
10-20 08:07:57.562  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:57.564  5853  5869 D bt_bte_conf: Device ID record 1 : primary
10-20 08:07:57.564  5853  5869 D bt_bte_conf:   vendorId            = 000f
10-20 08:07:57.564  5853  5869 D bt_bte_conf:   vendorIdSource      = 0001
10-20 08:07:57.564  5853  5869 D bt_bte_conf:   product             = 1200
10-20 08:07:57.564  5853  5869 D bt_bte_conf:   version             = 1436
,10-20 08:07:57.564  5853  5869 D bt_bte_conf:   clientExecutableURL = 
10-20 08:07:57.564  5853  5869 D bt_bte_conf:   serviceDescription  = 
,10-20 08:07:57.565  5853  5869 D bt_bte_conf:   documentationURL    = 
,10-20 08:07:57.565  5853  5869 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-20 08:07:57.565  5853  5866 D bt_stack_manager: event_start_up_stack finished
,10-20 08:07:57.567  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-20 08:07:57.567  5853  5865 D BluetoothAdapterProperties: Setting state to 15
10-20 08:07:57.567  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-20 08:07:57.568  5853  5865 I BluetoothAdapterState: Entering BleOnState
10-20 08:07:57.569  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:57.571  5853  5873 I bt_vendor: low_power_mode_cb
10-20 08:07:57.573  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:57.575   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:07:57.577  5853  5865 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-20 08:07:57.577  5853  5865 D BluetoothAdapterProperties: Setting state to 11
10-20 08:07:57.577  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-20 08:07:57.582  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:57.585  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:07:57.585  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:57.586  5853  5853 D HeadsetService: Received start request. Starting profile...
10-20 08:07:57.587  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:57.589  5853  5853 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-20 08:07:57.590  5853  5853 D HeadsetStateMachine: make
,10-20 08:07:57.601  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,10-20 08:07:57.601  5853  5853 D HeadsetStateMachine: max_hf_connections = 1
10-20 08:07:57.601  5853  5853 I bt_bluedroid: get_profile_interface handsfree
,10-20 08:07:57.601  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-20 08:07:57.602  5853  5869 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-20 08:07:57.607  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:07:57.607  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-20 08:07:57.608  5853  5853 D A2dpService: Received start request. Starting profile...
,10-20 08:07:57.609  5853  5853 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-20 08:07:57.609  5853  5853 I bt_bluedroid: get_profile_interface avrcp
,10-20 08:07:57.614  5853  5853 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-20 08:07:57.614  5853  5853 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-20 08:07:57.615  5853  5853 D A2dpStateMachine: make
10-20 08:07:57.615  5853  5853 I bt_bluedroid: get_profile_interface a2dp
,10-20 08:07:57.616  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-20 08:07:57.617  5853  5884 D A2dpStateMachine: Enter Disconnected: -2
,10-20 08:07:57.618  5853  5853 I BluetoothHidServiceJni: classInitNative: succeeds
,10-20 08:07:57.618  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:07:57.620  5711  5711 D BluetoothInputDevice: Proxy object connected
10-20 08:07:57.620  5711  5711 D HidProfile: Bluetooth service connected
,10-20 08:07:57.621  5853  5853 D HidService: Received start request. Starting profile...
10-20 08:07:57.622  5853  5853 I bt_bluedroid: get_profile_interface hidhost
10-20 08:07:57.622  5853  5853 D HidService: setHidService(): set to: null
10-20 08:07:57.622  5853  5869 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf406a56d
10-20 08:07:57.622  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-20 08:07:57.622  5853  5853 I BluetoothHealthServiceJni: classInitNative: succeeds
10-20 08:07:57.623  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:07:57.623  5853  5853 D HealthService: Received start request. Starting profile...
,10-20 08:07:57.625  5853  5853 I bt_bluedroid: get_profile_interface health
10-20 08:07:57.625  5853  5853 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-20 08:07:57.626  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:07:57.627  5711  5711 D BluetoothPan: BluetoothPAN Proxy object connected
10-20 08:07:57.627  5853  5853 D PanService: Received start request. Starting profile...
10-20 08:07:57.627  5853  5853 D BluetoothPanServiceJni: initializeNative(L110): pan
10-20 08:07:57.628  5853  5853 I bt_bluedroid: get_profile_interface pan
10-20 08:07:57.628  5711  5711 D PanProfile: Bluetooth service connected
,10-20 08:07:57.628  5853  5869 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-20 08:07:57.630  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:07:57.631  5711  5711 D BluetoothMap: Proxy object connected
10-20 08:07:57.632  5711  5711 D MapProfile: Bluetooth service connected
,10-20 08:07:57.632  5711  5711 D BluetoothMap: getConnectedDevices()
10-20 08:07:57.633  5853  5853 D BluetoothMapService: Received start request. Starting profile...
10-20 08:07:57.634  5853  5853 D BluetoothMapService: start()
10-20 08:07:57.636  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-20 08:07:57.637  5853  5853 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-20 08:07:57.637  5853  5853 D BluetoothMapAppObserver: createReceiver()
10-20 08:07:57.638  5853  5853 D BluetoothMapAppObserver: initObservers()
10-20 08:07:57.638  5853  5853 D BluetoothMapAppObserver: getEnabledAccountItems()
10-20 08:07:57.644  5853  5853 V SapService: SapBinder()
10-20 08:07:57.644  5853  5853 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:07:57.645  5853  5853 D SapService: Received start request. Starting profile...
10-20 08:07:57.645  5853  5853 V SapService: start()
10-20 08:07:57.646  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:57.646  5853  5853 V BluetoothAdapterState: isTurningOn()=true
,10-20 08:07:57.646  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:57.646  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:57.646  5853  5882 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-20 08:07:57.647  5711  5711 D BluetoothMap: Bluetooth is Not enabled
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isTurningOn()=true
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isTurningOn()=true
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isTurningOn()=true
10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
,10-20 08:07:57.648  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isTurningOn()=true
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isTurningOn()=true
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:57.649  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:07:57.650  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:07:57.650  5853  5853 V BluetoothAdapterState: isTurningOn()=true
10-20 08:07:57.650  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:07:57.650  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
,10-20 08:07:57.651  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-20 08:07:57.651  5853  5865 D BluetoothAdapterProperties: ScanMode =  20
10-20 08:07:57.651  5853  5865 D BluetoothAdapterProperties: State =  11
10-20 08:07:57.651  5853  5865 D BluetoothAdapterProperties: Setting state to 12
10-20 08:07:57.651  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-20 08:07:57.652  5853  5865 I BluetoothAdapterState: Entering OnState
10-20 08:07:57.652  3819  4062 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:07:57.653  5658  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-20 08:07:57.653  5853  5869 D BluetoothAdapterProperties: Scan Mode:21
10-20 08:07:57.653  5853  5869 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-20 08:07:57.653  5711  5723 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-20 08:07:57.656   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:07:57.656  5711  5722 D BluetoothMap: onBluetoothStateChange: up=true
,10-20 08:07:57.657  3161  3182 D BluetoothPan: onBluetoothStateChange on: true
,10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:57.657  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:57.659  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:57.660  3161  3161 D BluetoothPan: BluetoothPAN Proxy object connected
,10-20 08:07:57.661  3161  3161 D PanProfile: Bluetooth service connected
10-20 08:07:57.661  3161  4007 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:07:57.661   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-20 08:07:57.662  3161  3173 D BluetoothA2dp: onBluetoothStateChange: up=true
10-20 08:07:57.662   928   928 D BluetoothA2dp: Proxy object connected
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:57.663  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:07:57.663  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-20 08:07:57.664  5853  5853 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-20 08:07:57.664  3161  3161 D BluetoothA2dp: Proxy object connected
10-20 08:07:57.664  5711  5723 D BluetoothPbap: onBluetoothStateChange: up=true
,10-20 08:07:57.665   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-20 08:07:57.666  5711  5722 D BluetoothPan: onBluetoothStateChange on: true
10-20 08:07:57.666  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-20 08:07:57.666  3161  3182 D BluetoothMap: onBluetoothStateChange: up=true
10-20 08:07:57.668  3161  4007 D BluetoothPbap: onBluetoothStateChange: up=true
10-20 08:07:57.668  5853  5853 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-20 08:07:57.669  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:07:57.671  3161  3161 D BluetoothMap: Proxy object connected
,10-20 08:07:57.671  3161  3161 D MapProfile: Bluetooth service connected
10-20 08:07:57.671  3161  3161 D BluetoothMap: getConnectedDevices()
10-20 08:07:57.671  3161  3926 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-20 08:07:57.673  5853  5853 D ObexServerSockets: Succeed to create listening sockets 
10-20 08:07:57.673  5853  5853 D ObexServerSockets0: startAccept()
10-20 08:07:57.673  5853  5853 D ObexServerSockets0: prepareForNewConnect()
10-20 08:07:57.673   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:07:57.673  3161  3161 D BluetoothInputDevice: Proxy object connected
10-20 08:07:57.673  3161  3161 D HidProfile: Bluetooth service connected
,10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:07:57.674  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:07:57.675   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-20 08:07:57.677  5853  5853 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-20 08:07:57.677  5853  5853 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-20 08:07:57.677  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:07:57.677  5658  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-20 08:07:57.677  5853  5891 D ObexServerSockets0: Accepting socket connection...
10-20 08:07:57.678  5853  5853 D BluetoothMapService: onReceive
10-20 08:07:57.678  5853  5853 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-20 08:07:57.678  5853  5853 D BluetoothMapService: STATE_ON
10-20 08:07:57.678  5853  5892 D ObexServerSockets0: Accepting socket connection...
10-20 08:07:57.679  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:07:57.680  5711  5711 D LocalBluetoothProfileManager: Adding local A2DP profile
10-20 08:07:57.681  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:57.681  5853  5893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-20 08:07:57.682  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:07:57.683  5853  5893 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-20 08:07:57.683  5853  5893 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-20 08:07:57.684  5711  5711 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-20 08:07:57.690  5711  5711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-20 08:07:57.692  5711  5711 D BluetoothA2dp: Proxy object connected
,10-20 08:07:57.696  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-20 08:07:57.699  5711  5711 D DockEventReceiver: finishStartingService: stopping service
,10-20 08:07:57.702  5711  5711 D BluetoothPbap: Proxy object connected
,10-20 08:07:57.702  5853  5853 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-20 08:07:57.703  5711  5711 D PbapServerProfile: Bluetooth service connected
10-20 08:07:57.703  5853  5853 D ObexServerSockets0: prepareForNewConnect()
,10-20 08:07:57.710  5853  5897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-20 08:07:57.714  3161  3161 D BluetoothPbap: Proxy object connected
,10-20 08:07:57.714  3161  3161 D PbapServerProfile: Bluetooth service connected
,10-20 08:07:57.726  5853  5901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-20 08:07:57.727  5853  5901 I BtOppRfcommListener: Accept thread started.
,10-20 08:07:57.754  3161  3173 D BluetoothHeadset: Proxy object connected
10-20 08:07:57.754  3161  3161 D HeadsetProfile: Bluetooth service connected
,10-20 08:07:57.754  3819  4049 D BluetoothHeadset: Proxy object connected
,10-20 08:07:57.755   928   928 D BluetoothHeadset: Proxy object connected
10-20 08:07:57.755   928   928 D BluetoothHeadset: Proxy object connected
10-20 08:07:57.755   928   928 D BluetoothHeadset: Proxy object connected
10-20 08:07:57.756   928   945 D BluetoothHeadset: Proxy object connected
,10-20 08:07:57.761  3161  3182 D BluetoothHeadset: Proxy object connected
,10-20 08:07:57.761  3161  3161 D HeadsetProfile: Bluetooth service connected
,10-20 08:07:57.766   928   945 D BluetoothHeadset: Proxy object connected
,10-20 08:07:57.773   928   945 D BluetoothHeadset: Proxy object connected
,10-20 08:07:57.786  5711  5722 D BluetoothHeadset: Proxy object connected
,10-20 08:07:57.788  5711  5711 D HeadsetProfile: Bluetooth service connected
,10-20 08:07:58.575   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-20 08:07:59.370   928  3009 D ConnectivityService: handlePromptUnvalidated 101
,10-20 08:08:01.615  5853  5865 D BluetoothAdapterState: Current state: ON, message: 23
10-20 08:08:01.615  5853  5865 D BluetoothAdapterProperties: Setting state to 13
10-20 08:08:01.615  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-20 08:08:01.617  5853  5865 D BluetoothAdapterProperties: onBluetoothDisable()
10-20 08:08:01.619  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
,10-20 08:08:01.623  5853  5853 D BluetoothMapService: onReceive
,10-20 08:08:01.623  5853  5853 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-20 08:08:01.623  5853  5853 D BluetoothMapService: STATE_TURNING_OFF
10-20 08:08:01.624  5853  5853 D BluetoothMapService: MAP Service closeService in
10-20 08:08:01.624  5853  5853 D BluetoothMapMasInstance0: MAP Service shutdown
10-20 08:08:01.624  5853  5853 D ObexServerSockets0: shutdown(block = true)
,10-20 08:08:01.625  5853  5853 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-20 08:08:01.625  5853  5853 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-20 08:08:01.625  5853  5891 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-20 08:08:01.625  5853  5892 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-20 08:08:01.625  5853  5878 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-20 08:08:01.626  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:01.626  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:08:01.627  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:08:01.627  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:08:01.629  5853  5853 I BtOppRfcommListener: stopping Accept Thread
10-20 08:08:01.629  5853  5901 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-20 08:08:01.630  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
10-20 08:08:01.630  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-20 08:08:01.631  5853  5901 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-20 08:08:01.632  5711  5711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-20 08:08:01.633  5853  5853 D HeadsetService: Received stop request...Stopping profile...
10-20 08:08:01.634  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:01.634  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:08:01.635  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:08:01.635  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:08:01.640  3161  3173 D BluetoothHeadset: Proxy object disconnected
10-20 08:08:01.640  5711  5711 D DockEventReceiver: finishStartingService: stopping service
10-20 08:08:01.640  3819  4062 D BluetoothHeadset: Proxy object disconnected
10-20 08:08:01.641  5711  5722 D BluetoothHeadset: Proxy object disconnected
10-20 08:08:01.641   928   928 D BluetoothHeadset: Proxy object disconnected
,10-20 08:08:01.642   928   928 D BluetoothHeadset: Proxy object disconnected
10-20 08:08:01.642   928   928 D BluetoothHeadset: Proxy object disconnected
10-20 08:08:01.642  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:01.642  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:08:01.642  5711  5711 D HeadsetProfile: Bluetooth service disconnected
10-20 08:08:01.643  5658  5658 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-20 08:08:01.643  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:08:01.644  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:01.645  5853  5853 D A2dpService: Received stop request...Stopping profile...
10-20 08:08:01.645  5853  5884 D A2dpStateMachine: Exit Disconnected: -1
10-20 08:08:01.646   928   928 D BluetoothA2dp: Proxy object disconnected
10-20 08:08:01.646  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:01.647  5711  5711 D BluetoothA2dp: Proxy object disconnected
10-20 08:08:01.648  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:01.651  5853  5853 D HidService: Received stop request...Stopping profile...
,10-20 08:08:01.651  5853  5853 D HidService: Stopping Bluetooth HidService
10-20 08:08:01.651  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-20 08:08:01.652  5853  5853 V BluetoothAdapterState: isTurningOff()=true
10-20 08:08:01.652  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:01.652  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:01.653  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:01.654  5853  5853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-20 08:08:01.654  5853  5853 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-20 08:08:01.654  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:08:01.654  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:08:01.655  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:08:01.655  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-20 08:08:01.655  5853  5853 D HealthService: Received stop request...Stopping profile...
10-20 08:08:01.655  5853  5869 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-20 08:08:01.656  5853  5853 D PanService: Received stop request...Stopping profile...
10-20 08:08:01.657  3161  3161 D HeadsetProfile: Bluetooth service disconnected
,10-20 08:08:01.657  3161  3161 D BluetoothA2dp: Proxy object disconnected
10-20 08:08:01.658  3161  3161 D BluetoothInputDevice: Proxy object disconnected
10-20 08:08:01.658  5853  5853 D BluetoothMapService: Received stop request...Stopping profile...
10-20 08:08:01.658  3161  3161 D HidProfile: Bluetooth service disconnected
10-20 08:08:01.658  5853  5853 D BluetoothMapService: stop()
10-20 08:08:01.658  3161  3161 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-20 08:08:01.658  3161  3161 D PanProfile: Bluetooth service disconnected
10-20 08:08:01.658  5853  5853 D BluetoothMapAppObserver: deinitObservers()
10-20 08:08:01.658  5853  5853 D BluetoothMapAppObserver: removeReceiver()
10-20 08:08:01.659  5711  5711 D BluetoothInputDevice: Proxy object disconnected
10-20 08:08:01.659  5711  5711 D HidProfile: Bluetooth service disconnected
10-20 08:08:01.659  5711  5711 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-20 08:08:01.659  5711  5711 D PanProfile: Bluetooth service disconnected
10-20 08:08:01.659  5711  5711 D BluetoothMap: Proxy object disconnected
10-20 08:08:01.659  5711  5711 D MapProfile: Bluetooth service disconnected
10-20 08:08:01.660  5853  5853 V BluetoothAdapterState: isTurningOff()=true
10-20 08:08:01.660  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:01.660  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:01.660  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:01.660  3161  3161 D BluetoothMap: Proxy object disconnected
,10-20 08:08:01.660  3161  3161 D MapProfile: Bluetooth service disconnected
10-20 08:08:01.662  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-20 08:08:01.662  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:08:01.662  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:08:01.662  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-20 08:08:01.662  5853  5853 D SapService: Received stop request...Stopping profile...
,10-20 08:08:01.662  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-20 08:08:01.662  5853  5853 V SapService: stop()
10-20 08:08:01.662  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-20 08:08:01.662  5853  5876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-20 08:08:01.665  5711  5711 D BluetoothPbap: Proxy object disconnected
,10-20 08:08:01.665  5711  5711 D PbapServerProfile: Bluetooth service disconnected
10-20 08:08:01.665  3161  3161 D BluetoothPbap: Proxy object disconnected
10-20 08:08:01.665  5853  5853 V BluetoothAdapterState: isTurningOff()=true
10-20 08:08:01.665  3161  3161 D PbapServerProfile: Bluetooth service disconnected
10-20 08:08:01.665  5853  5853 V BluetoothAdapterState: isTurningOn()=false
,10-20 08:08:01.665  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:01.665  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:01.665  5853  5853 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-20 08:08:01.665  5853  5853 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-20 08:08:01.666  5853  5869 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-20 08:08:01.666  5853  5853 V BluetoothAdapterState: isTurningOff()=true
10-20 08:08:01.666  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:01.666  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:01.666  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:01.666  5853  5853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-20 08:08:01.667  5853  5869 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-20 08:08:01.667  5853  5853 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-20 08:08:01.667  5853  5853 V BluetoothAdapterState: isTurningOff()=true
10-20 08:08:01.667  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:01.667  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:01.667  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:01.667  5853  5853 D BluetoothMapService: MAP Service closeService in
10-20 08:08:01.668  5853  5853 V BluetoothAdapterState: isTurningOff()=true
10-20 08:08:01.668  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:01.668  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:01.668  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:01.668  5853  5853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-20 08:08:01.668  5853  5853 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-20 08:08:01.669  5853  5853 D BluetoothMapService: cleanup()
10-20 08:08:01.669  5853  5853 D BluetoothMapService: MAP Service closeService in
10-20 08:08:01.670  5853  5853 V BluetoothAdapterState: isTurningOff()=true
10-20 08:08:01.670  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:01.670  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:01.670  5853  5853 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:01.670  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-20 08:08:01.670  5853  5865 D BluetoothAdapterProperties: Setting state to 15
10-20 08:08:01.670  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-20 08:08:01.671  5853  5865 I BluetoothAdapterState: Entering BleOnState
10-20 08:08:01.671  3819  4049 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-20 08:08:01.672  5711  5722 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-20 08:08:01.672   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:08:01.673  5711  5723 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:08:01.673  5711  5722 D BluetoothMap: onBluetoothStateChange: up=false
10-20 08:08:01.674  3161  3182 D BluetoothPan: onBluetoothStateChange on: false
10-20 08:08:01.674  3161  4007 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:08:01.674   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-20 08:08:01.675  5711  5723 D BluetoothA2dp: onBluetoothStateChange: up=false
10-20 08:08:01.675  3161  3926 D BluetoothA2dp: onBluetoothStateChange: up=false
10-20 08:08:01.676  5711  5722 D BluetoothPbap: onBluetoothStateChange: up=false
10-20 08:08:01.676   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:08:01.677  5711  5723 D BluetoothPan: onBluetoothStateChange on: false
10-20 08:08:01.678  3161  3173 D BluetoothMap: onBluetoothStateChange: up=false
10-20 08:08:01.679  3161  3182 D BluetoothPbap: onBluetoothStateChange: up=false
,10-20 08:08:01.680  3161  3926 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-20 08:08:01.681   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-20 08:08:01.681  5853  5865 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-20 08:08:01.681  5853  5865 D BluetoothAdapterProperties: Setting state to 16
10-20 08:08:01.681  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-20 08:08:01.684  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:01.684  5853  5865 D BluetoothAdapterProperties: onBleDisable
10-20 08:08:01.685  5853  5865 I BluetoothAdapterState: Entering PendingCommandState
10-20 08:08:01.685  5853  5866 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-20 08:08:01.685  5711  5711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-20 08:08:01.685  5853  5876 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-20 08:08:01.685  5853  5876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-20 08:08:01.686  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:01.687  5853  5869 D BluetoothAdapterProperties: Scan Mode:20
10-20 08:08:01.687  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:01.689  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:01.690  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-20 08:08:01.692  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:01.694  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:01.696  5711  5711 D DockEventReceiver: finishStartingService: stopping service
,10-20 08:08:01.897  5853  5869 I bt_hci  : shut_down
,10-20 08:08:01.906  5853  5873 D bt_hwcfg: hw_epilog_process
,10-20 08:08:01.907  5853  5873 I bt_vendor: low_power_mode_cb
,10-20 08:08:01.910  5853  5873 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-20 08:08:01.910  5853  5873 I bt_vendor: epilog_cb
10-20 08:08:01.910  5853  5873 I bt_hci  : epilog_finished_callback
,10-20 08:08:01.917  5853  5869 I bt_hci_h4: hal_close
,10-20 08:08:01.918  5853  5869 I bt_userial_vendor: device fd = 54 close
,10-20 08:08:02.034  5853  5866 D bt_stack_manager: event_shut_down_stack finished.
,10-20 08:08:02.035  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-20 08:08:02.039  5853  5853 D BtGatt.DebugUtils: handleDebugAction() action=null
10-20 08:08:02.039  5853  5865 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-20 08:08:02.040  5853  5853 D BtGatt.GattService: Received stop request...Stopping profile...
10-20 08:08:02.040  5853  5853 D BtGatt.GattService: stop()
10-20 08:08:02.041  5853  5853 D BtGatt.AdvertiseManager: advertise clients cleared
10-20 08:08:02.044  5853  5853 V BluetoothAdapterState: isTurningOff()=false
10-20 08:08:02.044  5853  5853 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:02.044  5853  5853 V BluetoothAdapterState: isBleTurningOn()=false
,10-20 08:08:02.044  5853  5853 V BluetoothAdapterState: isBleTurningOff()=true
10-20 08:08:02.045  5853  5865 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-20 08:08:02.045  5853  5865 D BluetoothAdapterProperties: Setting state to 10
10-20 08:08:02.046  5853  5865 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-20 08:08:02.047  5853  5865 I BluetoothAdapterState: Entering OffState
10-20 08:08:02.048   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-20 08:08:02.064  5853  5853 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-20 08:08:02.064  5853  5853 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,10-20 08:08:02.064  5853  5866 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-20 08:08:02.067  5853  5853 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-20 08:08:02.073  5853  5853 I art     : System.exit called, status: 0
,10-20 08:08:02.075  5853  5853 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-20 08:08:02.101   928  3450 I ActivityManager: Process com.android.bluetooth (pid 5853) has died
,10-20 08:08:06.614  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:06.614  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:08:06.619  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:08:06.619  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@575b082 removed from the list
10-20 08:08:06.620  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:06.620  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:08:06.620  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:08:06.622  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:06.623  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@393afd0 added. We now have 4 listener(s)
10-20 08:08:06.623  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:06.625  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:08:06.625  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@393afd0 removed from the list
10-20 08:08:06.625  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:06.625  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:06.625  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:08:06.627  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:06.628  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@536bc9 added. We now have 4 listener(s)
10-20 08:08:06.628  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:08:11.639  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:11.667   928   945 I ActivityManager: Start proc 5909:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-20 08:08:11.745  5909  5909 D AdapterServiceConfig: Adding HeadsetService
,10-20 08:08:11.745  5909  5909 D AdapterServiceConfig: Adding A2dpService
10-20 08:08:11.745  5909  5909 D AdapterServiceConfig: Adding HidService
10-20 08:08:11.745  5909  5909 D AdapterServiceConfig: Adding HealthService
10-20 08:08:11.746  5909  5909 D AdapterServiceConfig: Adding PanService
10-20 08:08:11.746  5909  5909 D AdapterServiceConfig: Adding GattService
10-20 08:08:11.746  5909  5909 D AdapterServiceConfig: Adding BluetoothMapService
10-20 08:08:11.746  5909  5909 D AdapterServiceConfig: Adding SapService
,10-20 08:08:11.756   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5748028:true
,10-20 08:08:11.757  5909  5909 D BluetoothAdapterState: make() - Creating AdapterState
,10-20 08:08:11.760  5909  5909 I bt_bluedroid: init
10-20 08:08:11.760  5909  5921 I BluetoothAdapterState: Entering OffState
,10-20 08:08:11.762  5909  5922 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-20 08:08:11.762  5909  5922 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-20 08:08:11.762  5909  5922 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-20 08:08:11.763  5909  5922 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-20 08:08:11.763  5909  5909 I bt_bluedroid: get_profile_interface socket
,10-20 08:08:11.765  5909  5925 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-20 08:08:11.765  5909  5909 I bt_bluedroid: get_profile_interface sdp
10-20 08:08:11.767  5909  5925 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-20 08:08:11.770  5909  5920 I bt_bluedroid: config_hci_snoop_log
10-20 08:08:11.771   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-20 08:08:11.775  5909  5921 D BluetoothAdapterState: Current state: OFF, message: 0
,10-20 08:08:11.776  5909  5921 D BluetoothAdapterProperties: Setting state to 14
10-20 08:08:11.776  5909  5921 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-20 08:08:11.777  5909  5921 D BluetoothBondStateMachine: make
,10-20 08:08:11.779  5909  5926 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-20 08:08:11.782  5909  5921 I BluetoothAdapterState: Entering PendingCommandState
,10-20 08:08:11.783  5909  5909 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-20 08:08:11.785  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:08:11.786  5909  5909 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-20 08:08:11.786  5909  5909 D BtGatt.GattService: Received start request. Starting profile...
10-20 08:08:11.787  5909  5909 D BtGatt.GattService: start()
10-20 08:08:11.787  5909  5909 I bt_bluedroid: get_profile_interface gatt
,10-20 08:08:11.788  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:08:11.788  5909  5909 D BtGatt.AdvertiseManager: advertise manager created
,10-20 08:08:11.793  5909  5909 V BluetoothAdapterState: isTurningOff()=false
,10-20 08:08:11.793  5909  5909 V BluetoothAdapterState: isTurningOn()=false
10-20 08:08:11.793  5909  5909 V BluetoothAdapterState: isBleTurningOn()=true
10-20 08:08:11.793  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
,10-20 08:08:11.794  5909  5921 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-20 08:08:11.795  5909  5921 I bt_bluedroid: bt_bluedroid
10-20 08:08:11.795  5909  5922 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-20 08:08:11.795  5909  5922 I bt_hci  : start_up
,10-20 08:08:11.801  5909  5922 I bt_vendor: alloc value 0xf410b871
,10-20 08:08:11.801  5909  5922 I bt_vendor: init
10-20 08:08:11.801  5909  5922 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-20 08:08:11.801  5909  5922 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-20 08:08:11.910  5909  5922 D bt_hci  : start_up starting async portion
,10-20 08:08:11.911  5909  5929 I bt_hci  : event_finish_startup
10-20 08:08:11.911  5909  5929 I bt_hci_h4: hal_open
10-20 08:08:11.911  5909  5929 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-20 08:08:11.912  5909  5929 I bt_userial_vendor: device fd = 54 open
10-20 08:08:11.910  5930  5930 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-20 08:08:11.926  5909  5929 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-20 08:08:11.928  5909  5929 D bt_hwcfg: Chipset BCM4358A3
10-20 08:08:11.928  5909  5929 D bt_hwcfg: Target name = [BCM4358A3]
10-20 08:08:11.929  5909  5929 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-20 08:08:12.437  5909  5929 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-20 08:08:12.438  5909  5929 D bt_hwcfg: Settlement delay -- 100 ms
10-20 08:08:12.438  5909  5929 I bt_hwcfg: Setting fw settlement delay to 100 
,10-20 08:08:12.571  5909  5929 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-20 08:08:12.572  5909  5929 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-20 08:08:12.573  5909  5929 I bt_hwcfg: vendor lib fwcfg completed
10-20 08:08:12.574  5909  5929 I bt_vendor: firmware callback
10-20 08:08:12.574  5909  5929 I bt_hci  : firmware_config_callback
,10-20 08:08:12.583  5909  5932 I bt_btu  : btu_task pending for preload complete event
10-20 08:08:12.583  5909  5932 I bt_btu_task: Bluetooth chip preload is complete
,10-20 08:08:12.583  5909  5932 I bt_btu  : btu_task received preload complete event
,10-20 08:08:12.591  5909  5932 I         : BTE_InitTraceLevels -- TRC_HCI
10-20 08:08:12.591  5909  5932 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_AVDT
10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_AVRC
10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_A2D
10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_BTM
10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_GAP
10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_PAN
10-20 08:08:12.592  5909  5932 I         : BTE_InitTraceLevels -- TRC_SDP
10-20 08:08:12.593  5909  5932 I         : BTE_InitTraceLevels -- TRC_GATT
,10-20 08:08:12.593  5909  5932 I         : BTE_InitTraceLevels -- TRC_SMP
10-20 08:08:12.593  5909  5932 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-20 08:08:12.593  5909  5932 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-20 08:08:12.690  5909  5932 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4089549
10-20 08:08:12.690  5909  5932 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4089549 
,10-20 08:08:12.718  5909  5925 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-20 08:08:12.720  5909  5925 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-20 08:08:12.721  5909  5925 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-20 08:08:12.723  5909  5925 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-20 08:08:12.727  5909  5925 D BluetoothAdapterProperties: Scan Mode:20
10-20 08:08:12.727  5909  5925 D BluetoothAdapterProperties: Discoverable Timeout:120
10-20 08:08:12.728  5909  5925 D bt_hci  : do_postload posting postload work item
10-20 08:08:12.728  5909  5929 I bt_hci  : event_postload
,10-20 08:08:12.730  5909  5925 D bt_bte_conf: Device ID record 1 : primary
,10-20 08:08:12.730  5909  5925 D bt_bte_conf:   vendorId            = 000f
10-20 08:08:12.730  5909  5925 D bt_bte_conf:   vendorIdSource      = 0001
10-20 08:08:12.730  5909  5925 D bt_bte_conf:   product             = 1200
10-20 08:08:12.730  5909  5925 D bt_bte_conf:   version             = 1436
10-20 08:08:12.730  5909  5925 D bt_bte_conf:   clientExecutableURL = 
10-20 08:08:12.730  5909  5925 D bt_bte_conf:   serviceDescription  = 
10-20 08:08:12.730  5909  5925 D bt_bte_conf:   documentationURL    = 
,10-20 08:08:12.730  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:12.733  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:12.728  5909  5929 I bt_vendor: sco_config_cb
,10-20 08:08:12.743  5909  5929 I bt_hci  : sco_config_callback postload finished.
10-20 08:08:12.730  5909  5925 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-20 08:08:12.748  5909  5922 D bt_stack_manager: event_start_up_stack finished
,10-20 08:08:12.749  5909  5921 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-20 08:08:12.749  5909  5921 D BluetoothAdapterProperties: Setting state to 15
10-20 08:08:12.749  5909  5921 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-20 08:08:12.750  5909  5921 I BluetoothAdapterState: Entering BleOnState
,10-20 08:08:12.753  5909  5929 I bt_vendor: low_power_mode_cb
,10-20 08:08:12.754  5909  5921 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-20 08:08:12.754  5909  5921 D BluetoothAdapterProperties: Setting state to 11
10-20 08:08:12.754  5909  5921 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-20 08:08:12.760  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:08:12.761  5909  5909 D HeadsetService: Received start request. Starting profile...
,10-20 08:08:12.764  5909  5909 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-20 08:08:12.764  5909  5909 D HeadsetStateMachine: make
10-20 08:08:12.765  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:12.767  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:12.776  5909  5921 I BluetoothAdapterState: Entering PendingCommandState
,10-20 08:08:12.782  5909  5909 D HeadsetStateMachine: max_hf_connections = 1
,10-20 08:08:12.782  5909  5909 I bt_bluedroid: get_profile_interface handsfree
10-20 08:08:12.783  5909  5925 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-20 08:08:12.783  5909  5925 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-20 08:08:12.786  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:08:12.787  5909  5909 D A2dpService: Received start request. Starting profile...
10-20 08:08:12.787  5909  5909 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-20 08:08:12.788  5909  5909 I bt_bluedroid: get_profile_interface avrcp
,10-20 08:08:12.794  5909  5909 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-20 08:08:12.794  5909  5909 I BluetoothA2dpServiceJni: classInitNative: succeeds
,10-20 08:08:12.794  5909  5909 D A2dpStateMachine: make
10-20 08:08:12.795  5909  5909 I bt_bluedroid: get_profile_interface a2dp
10-20 08:08:12.796  5909  5925 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-20 08:08:12.797  5909  5940 D A2dpStateMachine: Enter Disconnected: -2
10-20 08:08:12.798  5909  5909 I BluetoothHidServiceJni: classInitNative: succeeds
10-20 08:08:12.799  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:08:12.799  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-20 08:08:12.800  5909  5909 D HidService: Received start request. Starting profile...
,10-20 08:08:12.800  5909  5909 I bt_bluedroid: get_profile_interface hidhost
10-20 08:08:12.800  5909  5909 D HidService: setHidService(): set to: null
10-20 08:08:12.800  5909  5925 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf406a56d
10-20 08:08:12.800  5909  5925 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-20 08:08:12.801  5909  5909 I BluetoothHealthServiceJni: classInitNative: succeeds
10-20 08:08:12.801  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
10-20 08:08:12.802  5909  5909 D HealthService: Received start request. Starting profile...
,10-20 08:08:12.803  5909  5909 I bt_bluedroid: get_profile_interface health
,10-20 08:08:12.803  5909  5909 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-20 08:08:12.804  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:08:12.805  5909  5909 D PanService: Received start request. Starting profile...
,10-20 08:08:12.805  5909  5909 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-20 08:08:12.805  5909  5909 I bt_bluedroid: get_profile_interface pan
10-20 08:08:12.806  5909  5925 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-20 08:08:12.807  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:08:12.807  5909  5909 D BluetoothMapService: Received start request. Starting profile...
10-20 08:08:12.807  5909  5909 D BluetoothMapService: start()
,10-20 08:08:12.812  5909  5909 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-20 08:08:12.813  5909  5909 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-20 08:08:12.813  5909  5909 D BluetoothMapAppObserver: createReceiver()
,10-20 08:08:12.814  5909  5909 D BluetoothMapAppObserver: initObservers()
10-20 08:08:12.814  5909  5909 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-20 08:08:12.819  5909  5909 V SapService: SapBinder()
10-20 08:08:12.819  5909  5909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:08:12.820  5909  5909 D SapService: Received start request. Starting profile...
10-20 08:08:12.820  5909  5909 V SapService: start()
,10-20 08:08:12.821  5909  5909 V BluetoothAdapterState: isTurningOff()=false
10-20 08:08:12.821  5909  5909 V BluetoothAdapterState: isTurningOn()=true
10-20 08:08:12.821  5909  5909 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:12.821  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isTurningOff()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isTurningOn()=true
,10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isTurningOff()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isTurningOn()=true
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
,10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isTurningOff()=false
,10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isTurningOn()=true
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:12.822  5909  5909 V BluetoothAdapterState: isTurningOff()=false
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isTurningOn()=true
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isTurningOff()=false
,10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isTurningOn()=true
,10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:12.823  5909  5938 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isTurningOff()=false
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isTurningOn()=true
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isBleTurningOn()=false
10-20 08:08:12.823  5909  5909 V BluetoothAdapterState: isBleTurningOff()=false
10-20 08:08:12.824  5909  5921 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-20 08:08:12.824  5909  5921 D BluetoothAdapterProperties: ScanMode =  20
,10-20 08:08:12.824  5909  5921 D BluetoothAdapterProperties: State =  11
10-20 08:08:12.824  5909  5921 D BluetoothAdapterProperties: Setting state to 12
10-20 08:08:12.824  5909  5921 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-20 08:08:12.825  3819  4049 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:08:12.826  5658  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-20 08:08:12.826  5909  5925 D BluetoothAdapterProperties: Scan Mode:21
10-20 08:08:12.826  5909  5925 D BluetoothAdapterProperties: Discoverable Timeout:120
10-20 08:08:12.826  5711  5723 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-20 08:08:12.828  5909  5921 I BluetoothAdapterState: Entering OnState
,10-20 08:08:12.828   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:08:12.829  5711  5722 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-20 08:08:12.829  5711  5722 D BluetoothMap: onBluetoothStateChange: up=true
,10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:12.830  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:08:12.832  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:08:12.832  3161  3173 D BluetoothPan: onBluetoothStateChange on: true
10-20 08:08:12.835  3161  3182 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:08:12.836  5711  5711 D BluetoothInputDevice: Proxy object connected
10-20 08:08:12.836  5711  5711 D HidProfile: Bluetooth service connected
,10-20 08:08:12.837   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:12.837  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:08:12.838  5711  5711 D BluetoothMap: Proxy object connected
10-20 08:08:12.838  5711  5711 D MapProfile: Bluetooth service connected
10-20 08:08:12.838  5711  5711 D BluetoothMap: getConnectedDevices()
,10-20 08:08:12.838  3161  3161 D BluetoothPan: BluetoothPAN Proxy object connected
10-20 08:08:12.838  3161  3161 D PanProfile: Bluetooth service connected
10-20 08:08:12.839  5711  5722 D BluetoothA2dp: onBluetoothStateChange: up=true
10-20 08:08:12.839  5909  5909 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-20 08:08:12.839  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:08:12.839  5909  5909 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-20 08:08:12.841  3161  4007 D BluetoothA2dp: onBluetoothStateChange: up=true
10-20 08:08:12.841  5909  5909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-20 08:08:12.842  5711  5723 D BluetoothPbap: onBluetoothStateChange: up=true
10-20 08:08:12.843  5909  5909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-20 08:08:12.844   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:08:12.844  5711  5722 D BluetoothPan: onBluetoothStateChange on: true
10-20 08:08:12.845  5909  5909 D ObexServerSockets: Succeed to create listening sockets 
10-20 08:08:12.845  5909  5909 D ObexServerSockets0: startAccept()
10-20 08:08:12.845  5909  5909 D ObexServerSockets0: prepareForNewConnect()
10-20 08:08:12.846  3161  3173 D BluetoothMap: onBluetoothStateChange: up=true
10-20 08:08:12.847  5909  5909 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-20 08:08:12.847  5909  5909 D BluetoothSdpJni: SDP Create record success - handle: 0
10-20 08:08:12.847  5909  5947 D ObexServerSockets0: Accepting socket connection...
10-20 08:08:12.847  5909  5948 D ObexServerSockets0: Accepting socket connection...
10-20 08:08:12.848   928   928 D BluetoothA2dp: Proxy object connected
10-20 08:08:12.848  3161  4007 D BluetoothPbap: onBluetoothStateChange: up=true
10-20 08:08:12.848  3161  3161 D BluetoothA2dp: Proxy object connected
10-20 08:08:12.850  3161  3161 D BluetoothMap: Proxy object connected
10-20 08:08:12.850  3161  3161 D MapProfile: Bluetooth service connected
10-20 08:08:12.850  5711  5711 D BluetoothPan: BluetoothPAN Proxy object connected
10-20 08:08:12.850  3161  3161 D BluetoothMap: getConnectedDevices()
10-20 08:08:12.850  5711  5711 D PanProfile: Bluetooth service connected
10-20 08:08:12.850  5711  5711 D BluetoothA2dp: Proxy object connected
10-20 08:08:12.851  3161  3182 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-20 08:08:12.852   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-20 08:08:12.852  3161  3161 D BluetoothInputDevice: Proxy object connected
10-20 08:08:12.853  3161  3161 D HidProfile: Bluetooth service connected
10-20 08:08:12.854  5909  5909 D BluetoothMapService: onReceive
10-20 08:08:12.854  5909  5909 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-20 08:08:12.854  5658  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-20 08:08:12.854  5909  5909 D BluetoothMapService: STATE_ON
,10-20 08:08:12.855   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-20 08:08:12.856  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:12.856  5909  5950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-20 08:08:12.857  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:12.858  5909  5950 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-20 08:08:12.858  5909  5950 D BluetoothSdpJni: SDP Create record success - handle: 1
10-20 08:08:12.859  5711  5711 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-20 08:08:12.865  3615  3615 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-20 08:08:12.865  5711  5711 D DockEventReceiver: finishStartingService: stopping service
,10-20 08:08:12.874  5711  5711 D BluetoothPbap: Proxy object connected
,10-20 08:08:12.874  5711  5711 D PbapServerProfile: Bluetooth service connected
,10-20 08:08:12.878  3161  3161 D BluetoothPbap: Proxy object connected
,10-20 08:08:12.878  3161  3161 D PbapServerProfile: Bluetooth service connected
10-20 08:08:12.879  5909  5909 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-20 08:08:12.879  5909  5909 D ObexServerSockets0: prepareForNewConnect()
10-20 08:08:12.879  5909  5954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-20 08:08:12.895  5909  5958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-20 08:08:12.896  5909  5958 I BtOppRfcommListener: Accept thread started.
,10-20 08:08:12.928  3161  4007 D BluetoothHeadset: Proxy object connected
,10-20 08:08:12.928  3161  3161 D HeadsetProfile: Bluetooth service connected
10-20 08:08:12.928  3819  3851 D BluetoothHeadset: Proxy object connected
,10-20 08:08:12.929  5711  5946 D BluetoothHeadset: Proxy object connected
,10-20 08:08:12.929   928   945 D BluetoothHeadset: Proxy object connected
10-20 08:08:12.929   928   928 D BluetoothHeadset: Proxy object connected
10-20 08:08:12.929   928   928 D BluetoothHeadset: Proxy object connected
10-20 08:08:12.929   928   928 D BluetoothHeadset: Proxy object connected
10-20 08:08:12.929  5711  5722 D BluetoothHeadset: Proxy object connected
10-20 08:08:12.929  5711  5711 D HeadsetProfile: Bluetooth service connected
10-20 08:08:12.932  5711  5711 D HeadsetProfile: Bluetooth service connected
,10-20 08:08:12.937  3161  3173 D BluetoothHeadset: Proxy object connected
10-20 08:08:12.937  3161  3161 D HeadsetProfile: Bluetooth service connected
,10-20 08:08:12.945   928   945 D BluetoothHeadset: Proxy object connected
,10-20 08:08:12.953   928   945 D BluetoothHeadset: Proxy object connected
,10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:16.657  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:08:16.662  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:08:16.663  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:16.663  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@536bc9 removed from the list
,10-20 08:08:16.663  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
,10-20 08:08:16.664  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:16.664  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:16.665  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:16.666  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d252ce added. We now have 4 listener(s)
,10-20 08:08:16.666  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:16.669   928  3986 D WifiService: setWifiEnabled: false pid=5658, uid=10077
10-20 08:08:16.670   928  3986 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-20 08:08:18.577   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:08:19.578   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:08:20.580   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:08:21.581   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:08:21.680  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:21.681   928  3188 D WifiService: setWifiEnabled: true pid=5658, uid=10077
,10-20 08:08:21.681   928  3188 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-20 08:08:21.691   508   922 D SoftapController: Softap fwReload - Ok
,10-20 08:08:21.696   508   922 D CommandListener: Setting iface cfg
,10-20 08:08:21.696   508   922 D CommandListener: Trying to bring down wlan0
,10-20 08:08:21.697   508   922 D CommandListener: Clearing all IP addresses on wlan0
,10-20 08:08:21.704   928  3007 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-20 08:08:22.384   928  3007 D wifi    : set interface wlan0 flags (UP)
,10-20 08:08:22.384   928  3007 I WifiHAL : Initializing wifi
,10-20 08:08:22.385   928  3007 I WifiHAL : Creating socket
,10-20 08:08:22.391   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-20 08:08:22.397   928  3007 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-20 08:08:22.397   928  3007 D wifi    : Did set static halHandle = 0x7f89218480
10-20 08:08:22.398   928  3007 D wifi    : halHandle = 0x7f89218480, mVM = 0x7fa584d140, mCls = 0x201852
10-20 08:08:22.398   928  3007 D wifi    : array field set
,10-20 08:08:22.398   928  3007 I WifiNative-HAL: interface[0] = wlan0
10-20 08:08:22.400   928  5963 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547761521792
10-20 08:08:22.400   928  5963 D wifi    : waitForHalEvents called, vm = 0x7fa584d140, obj = 0x201852, env = 0x7f8a864c00
,10-20 08:08:22.457  5964  5964 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-20 08:08:22.479  5964  5964 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-20 08:08:22.490  5964  5964 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-20 08:08:22.490  5964  5964 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-20 08:08:22.501   928  3007 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-20 08:08:22.508  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:22.516   928  3007 D WifiConfigStore: Loading config and enabling all networks 
,10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:22.516  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-20 08:08:22.518  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-20 08:08:22.522  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-20 08:08:22.524  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-20 08:08:22.525  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:22.530   928  3007 D WifiConfigStore: loaded 0 passpoint configs
,10-20 08:08:22.530   928  3007 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-20 08:08:22.530   928  3007 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-20 08:08:22.532   928  3007 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-20 08:08:22.533   928  3007 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-20 08:08:22.533   928  3007 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-20 08:08:22.533   928  3007 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-20 08:08:22.533   928  3007 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-20 08:08:22.537   928  3007 D WifiNative-HAL: Setting external_sim to 1
,10-20 08:08:22.537   928  3007 D wifi    : setting dfs flag to true, 0x7f8b6fe6c0
10-20 08:08:22.537  4440  4440 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-20 08:08:22.537   928  3007 D WifiStateMachine: Setting OUI to DA-A1-19
10-20 08:08:22.538   928  3007 D wifi    : setting scan oui 0x7f8b6fe6c0
10-20 08:08:22.538   928  3007 D WifiHAL : Sending mac address OUI
,10-20 08:08:22.541   928  3007 E native  : do suspend false
,10-20 08:08:22.552   928  3007 D wifi    : android_net_wifi_setLinkLayerStats: 1,
,10-20 08:08:22.552   928   928 D RttService: SCAN_AVAILABLE : 3
10-20 08:08:22.552   508   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-20 08:08:22.552   928  3115 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-20 08:08:22.554   508   922 D CommandListener: Setting iface cfg
,10-20 08:08:22.559   928  3006 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,10-20 08:08:22.559   928  3006 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-20 08:08:22.569   928  3006 D WifiNative-HAL: p2pGetDeviceAddress
,10-20 08:08:22.570   928  3006 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-20 08:08:22.576   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302819 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,10-20 08:08:22.582   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:08:23.583   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-20 08:08:25.626  5964  5964 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:08:25.632  5964  5964 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:08:25.638  5964  5964 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:08:25.709   928  3007 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-20 08:08:25.710   928  3007 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-20 08:08:25.710   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:08:25.726   928  3007 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-20 08:08:25.765   928  3007 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-20 08:08:25.767  5964  5964 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-20 08:08:26.196  5964  5964 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-20 08:08:26.228  5964  5964 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-20 08:08:26.229  5964  5964 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-20 08:08:26.242   928  3007 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-20 08:08:26.242   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:08:26.242   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-20 08:08:26.261   928  3007 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-20 08:08:26.274   508   922 D CommandListener: Setting iface cfg
,10-20 08:08:26.279   928  3007 D WifiStateMachine: Start Dhcp Watchdog 3
,10-20 08:08:26.289   928  5969 D DhcpClient: Receive thread started
,10-20 08:08:26.289   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-20 08:08:26.289   928  3007 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-20 08:08:26.290   928  3009 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-20 08:08:26.370   928  3007 E native  : do suspend false
,10-20 08:08:26.390   928  5968 D DhcpClient: Broadcasting DHCPDISCOVER
,10-20 08:08:26.404   928  5969 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-20 08:08:26.405   928  5968 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-20 08:08:26.407   928  5968 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-20 08:08:26.432   928  5969 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-20 08:08:26.433   928  5968 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-20 08:08:26.435   508   922 D CommandListener: Setting iface cfg
,10-20 08:08:26.440   928  3007 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-20 08:08:26.445   928  5968 D DhcpClient: Scheduling renewal in 86399s
,10-20 08:08:26.457   928  3007 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-20 08:08:26.458   928  3007 D WifiConfigStore: No blacklist allowed without epno enabled
,10-20 08:08:26.459   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-20 08:08:26.461   928  3009 D ConnectivityService: Adding iface wlan0 to network 102
10-20 08:08:26.469   928  3007 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-20 08:08:26.517   928  3009 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-20 08:08:26.518   928  3009 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-20 08:08:26.520   928  3009 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-20 08:08:26.525   928  3009 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-20 08:08:26.529   928  3009 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-20 08:08:26.538   928  3009 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:08:26.542   928  3009 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-20 08:08:26.543   928  3009 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-20 08:08:26.543   928  3009 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-20 08:08:26.543   928  3009 D ConnectivityService:    accepting network in place of null
10-20 08:08:26.543   928  3007 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-20 08:08:26.543   928  3007 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-20 08:08:26.543   928  3009 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -62]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-20 08:08:26.557   928  5967 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306800, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-20 08:08:26.567   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-20 08:08:26.589   508   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-20 08:08:26.593   928  3009 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-20 08:08:26.593   928  3009 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-20 08:08:26.593  3778  3925 W QCNEJ   : |CORE| network available: 102
10-20 08:08:26.594   928  3009 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,10-20 08:08:26.595  3778  3925 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-20 08:08:26.595   928   945 D Tethering: MasterInitialState.processMessage what=3
10-20 08:08:26.596  3778  3925 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-20 08:08:26.596  3778  3925 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.603  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:08:26.606  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.609  5658  5658 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:08:26.611  5658  5658 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.612  5076  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-20 08:08:26.613  5076  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-20 08:08:26.613  5076  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-20 08:08:26.613  5076  5089 E SarControlService: no key has been found,reset the power
,10-20 08:08:26.613  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-20 08:08:26.613  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-20 08:08:26.613  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-20 08:08:26.614  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-20 08:08:26.614  5102  5102 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-20 08:08:26.615  5076  5114 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-20 08:08:26.615  5076  5114 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-20 08:08:26.615  5076  5114 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-20 08:08:26.616  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-20 08:08:26.617  4093  4093 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-20 08:08:26.620  5102  5102 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-20 08:08:26.621  4093  4093 D SystemUpdateService: onCreate
,10-20 08:08:26.624  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000f003000000000000ffffffff]
10-20 08:08:26.624  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:08:26.625  5102  5116 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-20 08:08:26.625  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-20 08:08:26.625  5076  5086 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-20 08:08:26.625  4093  4093 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-20 08:08:26.626  5102  5116 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@c3997bb HexData = [00000000f103000000000000ffffffff]
10-20 08:08:26.626  5102  5116 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-20 08:08:26.626  5102  5116 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,10-20 08:08:26.627  5102  5102 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-20 08:08:26.627  5076  5087 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-20 08:08:26.637  4093  4093 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-20 08:08:26.641  4093  5429 I iu.UploadsManager: num queued entries: 0
,10-20 08:08:26.641   928  5966 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
10-20 08:08:26.642  4093  5429 I iu.UploadsManager: num updated entries: 0
10-20 08:08:26.642  4093  5429 I iu.SyncManager: NEXT; no task
,10-20 08:08:26.645  4093  5979 I SystemUpdateService: active receiver: enabled
,10-20 08:08:26.646  4093  4093 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-20 08:08:26.648  4093  4093 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-20 08:08:26.649  5772  5772 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-20 08:08:26.653  5772  5772 D SprintDMHelper: simOperator: 
,10-20 08:08:26.653  5772  5772 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-20 08:08:26.679  4093  5979 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-20 08:08:26.688  4093  5979 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-20 08:08:26.688  4093  5979 I SystemUpdateService: now status is 0 (complete)
10-20 08:08:26.688  4093  5979 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-20 08:08:26.688  4093  5979 I SystemUpdateService: file has been verified
10-20 08:08:26.688  4093  5979 I SystemUpdateService: OTA package size = 21989297
,10-20 08:08:26.689   928  5966 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 20 Oct 2016 12:08:26 GMT], X-Android-Received-Millis=[1476965306688], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476965306668]}
,10-20 08:08:26.689   928  3009 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-20 08:08:26.690   928  3009 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-20 08:08:26.690   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-20 08:08:26.691   928  3009 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-20 08:08:26.694  4093  5979 I SystemUpdateService: showing system update notification
,10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.697  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:08:26.699  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.699  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.699  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d252ce removed from the list
10-20 08:08:26.699  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:26.699  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.699  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.702  5658  5704 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-20 08:08:26.703  5658  5704 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-20 08:08:26.704  5658  5704 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f66df8f Bundle[{}]
10-20 08:08:26.705  5658  5704 I io.jxcore.node.LifeCycleMonitor: start: OK
10-20 08:08:26.706  5658  5704 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-20 08:08:26.707  5658  5704 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-20 08:08:26.707  4093  4093 D SystemUpdateService: onDestroy
10-20 08:08:26.708  5658  5704 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-20 08:08:26.708  5658  5704 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-20 08:08:26.709  5658  5704 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-20 08:08:26.715  5658  5704 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
10-20 08:08:26.716  5658  5704 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-20 08:08:26.716  5658  5704 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
10-20 08:08:26.718  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.718  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1c35ef added. We now have 3 listener(s)
,10-20 08:08:26.719  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-20 08:08:26.720  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.720  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.720  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.720  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64bf8fc added. We now have 4 listener(s)
10-20 08:08:26.720  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:08:26.721  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-20 08:08:26.723  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.728  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:08:26.730  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:08:26.730  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-20 08:08:26.731  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-20 08:08:26.731  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444cdda added. We now have 4 listener(s)
10-20 08:08:26.732  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-20 08:08:26.733  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-20 08:08:26.733  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.733  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.733  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:26.733  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a0420b added. We now have 5 listener(s)
10-20 08:08:26.733  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.733  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:08:26.733  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-20 08:08:26.733  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:08:26.733  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.734  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.734  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:08:26.734  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.734  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:08:26.734  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1c35ef removed from the list
10-20 08:08:26.734  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.734  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64bf8fc removed from the list
10-20 08:08:26.735  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:26.736  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:26.736  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.736  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.736  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.737  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.737  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.737  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.737  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64bf8fc not in the list
,10-20 08:08:26.737  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.737  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:08:26.738  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-20 08:08:26.738  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.738  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.738  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a0420b removed from the list
10-20 08:08:26.738  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.738  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.738  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.738  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-20 08:08:26.739  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:08:26.739  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@444cdda removed from the list
10-20 08:08:26.739  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.739  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdda8e8 added. We now have 3 listener(s)
10-20 08:08:26.740  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:08:26.740  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.740  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.741  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-20 08:08:26.741  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647cb01 added. We now have 4 listener(s)
10-20 08:08:26.741  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.741  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-20 08:08:26.743  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.746  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:08:26.747  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:08:26.748  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-20 08:08:26.748  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-20 08:08:26.748  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef3e7 added. We now have 4 listener(s)
10-20 08:08:26.749  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:08:26.749  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.749  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.749  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.749  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@586b94 added. We now have 5 listener(s)
10-20 08:08:26.749  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.749  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:08:26.749  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-20 08:08:26.749  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-20 08:08:26.749  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:08:26.749  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-20 08:08:26.750  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:26.752  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:26.754  5658  5704 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-20 08:08:26.754  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-20 08:08:26.756  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-20 08:08:26.757  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-20 08:08:26.757  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-20 08:08:26.759  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-20 08:08:26.759  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-20 08:08:26.759  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-20 08:08:26.759  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-20 08:08:26.759  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-20 08:08:26.759  5658  5704 D BluetoothAdapter: STATE_ON
,10-20 08:08:26.763  5909  5919 D BtGatt.GattService: registerClient() - UUID=8fe70104-6d8f-4b00-8d3e-626ef4358bb3
,10-20 08:08:26.763  5909  5925 D BtGatt.GattService: onClientRegistered() - UUID=8fe70104-6d8f-4b00-8d3e-626ef4358bb3, clientIf=5
,10-20 08:08:26.764  5658  5668 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-20 08:08:26.765  5909  5945 D BtGatt.GattService: start scan with filters
10-20 08:08:26.767  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-20 08:08:26.767  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-20 08:08:26.767  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:08:26.767  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-20 08:08:26.767  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-20 08:08:26.767  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-20 08:08:26.767  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-20 08:08:26.767  5909  5928 D BtGatt.ScanManager: handling starting scan
,10-20 08:08:26.769  5909  5928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc956f0
,10-20 08:08:26.770  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-20 08:08:26.770  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-20 08:08:26.770  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-20 08:08:26.771  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-20 08:08:26.773  5658  5704 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-20 08:08:26.773  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-20 08:08:26.773  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-20 08:08:26.774  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.774  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-20 08:08:26.774  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.774  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-20 08:08:26.774  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-20 08:08:26.774  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-20 08:08:26.774  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-20 08:08:26.774  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-20 08:08:26.774  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-20 08:08:26.774  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:08:26.775  5909  5919 D BtGatt.GattService: stopScan() - queue size =1
10-20 08:08:26.775  5909  5945 D BtGatt.GattService: unregisterClient() - clientIf=5
10-20 08:08:26.775  5909  5925 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-20 08:08:26.775  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.775  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-20 08:08:26.775  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-20 08:08:26.775  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-20 08:08:26.775  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:08:26.776  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-20 08:08:26.776  5909  5928 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-20 08:08:26.776  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-20 08:08:26.776  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-20 08:08:26.776  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-20 08:08:26.780  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-20 08:08:26.780  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-20 08:08:26.780  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-20 08:08:26.780  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-20 08:08:26.780  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-20 08:08:26.780  5909  5925 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-20 08:08:26.780  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.780  5909  5928 D BtGatt.ScanManager: Starting BLE batch scan
10-20 08:08:26.781  5909  5928 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-20 08:08:26.781  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-20 08:08:26.782  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-20 08:08:26.782  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:08:26.782  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-20 08:08:26.784  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-20 08:08:26.784  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:08:26.784  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:08:26.784  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.784  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.784  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:08:26.784  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.784  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-20 08:08:26.784  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdda8e8 removed from the list
10-20 08:08:26.784  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.785  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647cb01 removed from the list
10-20 08:08:26.785  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:26.785  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.785  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.785  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.786  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.786  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.786  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-20 08:08:26.786  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@647cb01 not in the list
10-20 08:08:26.786  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.786  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.787  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.787  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.787  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.787  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@586b94 removed from the list
10-20 08:08:26.788  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.788  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.788  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.788  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.788  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:08:26.788  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef3e7 removed from the list
,10-20 08:08:26.789  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.789  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71aad00 added. We now have 3 listener(s)
10-20 08:08:26.789  5909  5925 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-20 08:08:26.789  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.790  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:08:26.790  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.791  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.791  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.791  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@511d939 added. We now have 4 listener(s)
10-20 08:08:26.791  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-20 08:08:26.793  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-20 08:08:26.795  5909  5925 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-20 08:08:26.795  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:08:26.796  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:08:26.797  4440  5983 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-20 08:08:26.801  5909  5925 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-20 08:08:26.801  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.801  5909  5928 D BtGatt.ScanManager: stopping BLe Batch
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.801  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:08:26.803  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.803  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:08:26.803  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.803  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec78df added. We now have 4 listener(s)
10-20 08:08:26.804  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:08:26.804  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.805  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-20 08:08:26.805  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.805  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fd992c added. We now have 5 listener(s)
10-20 08:08:26.805  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.805  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:08:26.805  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:26.805  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:08:26.806  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-20 08:08:26.806  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-20 08:08:26.806  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:08:26.806  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-20 08:08:26.806  5909  5925 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-20 08:08:26.806  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.806  5909  5928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-20 08:08:26.808  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-20 08:08:26.809  5658  5704 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-20 08:08:26.809  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-20 08:08:26.812  5909  5925 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-20 08:08:26.812  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:08:26.813  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-20 08:08:26.814  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-20 08:08:26.814  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-20 08:08:26.816  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-20 08:08:26.816  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-20 08:08:26.816  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-20 08:08:26.816  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-20 08:08:26.816  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-20 08:08:26.817  5658  5704 D BluetoothAdapter: STATE_ON
,10-20 08:08:26.818  5909  5949 D BtGatt.GattService: registerClient() - UUID=55561e2b-2e79-4a58-8e47-d68252e3edd6
,10-20 08:08:26.819  5909  5925 D BtGatt.GattService: onClientRegistered() - UUID=55561e2b-2e79-4a58-8e47-d68252e3edd6, clientIf=5
,10-20 08:08:26.819  5658  5668 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-20 08:08:26.819  5909  5919 D BtGatt.GattService: start scan with filters
10-20 08:08:26.821  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-20 08:08:26.821  5909  5928 D BtGatt.ScanManager: handling starting scan
10-20 08:08:26.821  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-20 08:08:26.821  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-20 08:08:26.821  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-20 08:08:26.821  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-20 08:08:26.821  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-20 08:08:26.821  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-20 08:08:26.823  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-20 08:08:26.823  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-20 08:08:26.823  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-20 08:08:26.824  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-20 08:08:26.825  5909  5925 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-20 08:08:26.825  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.826  5909  5928 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-20 08:08:26.826  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:08:26.826  5658  5704 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-20 08:08:26.826  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:08:26.826  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:08:26.826  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-20 08:08:26.826  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.827  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.827  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-20 08:08:26.827  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.827  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:08:26.827  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71aad00 removed from the list
10-20 08:08:26.827  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.827  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@511d939 removed from the list
,10-20 08:08:26.827  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:26.827  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-20 08:08:26.827  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-20 08:08:26.827  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-20 08:08:26.827  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.828  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:08:26.828  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.828  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.828  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.828  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@511d939 not in the list
10-20 08:08:26.828  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-20 08:08:26.829  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-20 08:08:26.829  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-20 08:08:26.829  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-20 08:08:26.829  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-20 08:08:26.829  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:08:26.830  5909  5919 D BtGatt.GattService: stopScan() - queue size =1
10-20 08:08:26.830  5909  5925 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-20 08:08:26.830  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.830  5909  5928 D BtGatt.ScanManager: Starting BLE batch scan
10-20 08:08:26.830  5909  5937 D BtGatt.GattService: unregisterClient() - clientIf=5
10-20 08:08:26.830  5909  5928 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-20 08:08:26.831  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-20 08:08:26.831  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-20 08:08:26.831  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-20 08:08:26.831  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-20 08:08:26.831  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-20 08:08:26.831  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-20 08:08:26.831  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-20 08:08:26.831  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-20 08:08:26.833  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:08:26.833  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-20 08:08:26.833  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-20 08:08:26.833  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-20 08:08:26.833  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-20 08:08:26.834  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.834  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.834  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.835  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.835  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:08:26.835  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fd992c removed from the list
,10-20 08:08:26.835  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.835  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:08:26.835  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.835  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:08:26.835  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.835  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.835  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-20 08:08:26.835  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cec78df removed from the list
10-20 08:08:26.835  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.835  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d411c18 added. We now have 3 listener(s)
10-20 08:08:26.837  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:08:26.837  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.837  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.837  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.838  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd87671 added. We now have 4 listener(s)
,10-20 08:08:26.838  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.838  5909  5925 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-20 08:08:26.838  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.838  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-20 08:08:26.841  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:08:26.843  5909  5925 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-20 08:08:26.843  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.845  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-20 08:08:26.847  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-20 08:08:26.848  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:08:26.848  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.848  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e66a4d7 added. We now have 4 listener(s)
10-20 08:08:26.848  5909  5925 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-20 08:08:26.848  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.848  5909  5928 D BtGatt.ScanManager: stopping BLe Batch
10-20 08:08:26.849  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:08:26.849  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.849  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.849  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-20 08:08:26.849  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37e1c4 added. We now have 5 listener(s)
10-20 08:08:26.849  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.849  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:08:26.849  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-20 08:08:26.849  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-20 08:08:26.849  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-20 08:08:26.849  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-20 08:08:26.850  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:26.853  5658  5704 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-20 08:08:26.853  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-20 08:08:26.853  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:26.854  5909  5925 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-20 08:08:26.854  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.854  5909  5928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-20 08:08:26.857  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-20 08:08:26.858  5909  5925 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-20 08:08:26.858  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:08:26.858  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-20 08:08:26.858  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-20 08:08:26.861  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-20 08:08:26.861  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-20 08:08:26.861  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-20 08:08:26.861  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-20 08:08:26.861  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-20 08:08:26.861  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:08:26.863  5909  5920 D BtGatt.GattService: registerClient() - UUID=cb5961b4-5ce9-4754-8902-fb92d7cd2291
10-20 08:08:26.863  5909  5925 D BtGatt.GattService: onClientRegistered() - UUID=cb5961b4-5ce9-4754-8902-fb92d7cd2291, clientIf=5
10-20 08:08:26.863  5658  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-20 08:08:26.863  5909  5919 D BtGatt.GattService: start scan with filters
,10-20 08:08:26.866  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-20 08:08:26.866  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-20 08:08:26.866  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:08:26.866  5909  5928 D BtGatt.ScanManager: handling starting scan
10-20 08:08:26.866  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-20 08:08:26.867  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-20 08:08:26.867  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-20 08:08:26.867  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-20 08:08:26.869  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-20 08:08:26.869  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-20 08:08:26.869  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-20 08:08:26.870  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-20 08:08:26.871  5909  5925 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-20 08:08:26.871  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.871  5909  5928 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-20 08:08:26.874  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:08:26.874  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:08:26.874  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:08:26.874  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.874  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.874  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-20 08:08:26.874  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.874  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-20 08:08:26.874  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d411c18 removed from the list
10-20 08:08:26.874  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.874  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd87671 removed from the list
10-20 08:08:26.874  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:26.874  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:08:26.874  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.875  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-20 08:08:26.875  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.875  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:08:26.875  5909  5925 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-20 08:08:26.875  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:08:26.876  5909  5928 D BtGatt.ScanManager: Starting BLE batch scan
10-20 08:08:26.876  5909  5928 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-20 08:08:26.876  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.876  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.876  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.876  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd87671 not in the list
10-20 08:08:26.876  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-20 08:08:26.876  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-20 08:08:26.876  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-20 08:08:26.876  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-20 08:08:26.876  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-20 08:08:26.877  5658  5704 D BluetoothAdapter: STATE_ON
10-20 08:08:26.878  5909  5945 D BtGatt.GattService: stopScan() - queue size =1
,10-20 08:08:26.879  5909  5920 D BtGatt.GattService: unregisterClient() - clientIf=5
10-20 08:08:26.879  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-20 08:08:26.879  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-20 08:08:26.879  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-20 08:08:26.879  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-20 08:08:26.879  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-20 08:08:26.879  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-20 08:08:26.879  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-20 08:08:26.879  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-20 08:08:26.880  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:08:26.880  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-20 08:08:26.880  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-20 08:08:26.880  5658  5704 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-20 08:08:26.880  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-20 08:08:26.881  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:08:26.882  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-20 08:08:26.882  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.882  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.882  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:08:26.882  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d37e1c4 removed from the list
10-20 08:08:26.882  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.882  5658  5658 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-20 08:08:26.882  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.882  5658  5658 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-20 08:08:26.882  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.882  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.882  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:08:26.882  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e66a4d7 removed from the list
10-20 08:08:26.883  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.883  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b35630 added. We now have 3 listener(s)
10-20 08:08:26.884  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-20 08:08:26.884  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-20 08:08:26.884  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.884  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.884  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3be82a9 added. We now have 4 listener(s)
10-20 08:08:26.884  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.885  5909  5925 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-20 08:08:26.885  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.885  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-20 08:08:26.887  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-20 08:08:26.890  5909  5925 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-20 08:08:26.890  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-20 08:08:26.892  5658  5704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-20 08:08:26.893  5658  5704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-20 08:08:26.894  5658  5704 D io.jxcore.node.ConnectivityMonitor: start: OK
10-20 08:08:26.894  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-20 08:08:26.894  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b57cf added. We now have 4 listener(s)
10-20 08:08:26.895  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-20 08:08:26.895  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-20 08:08:26.895  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-20 08:08:26.895  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-20 08:08:26.895  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12fa55c added. We now have 5 listener(s)
10-20 08:08:26.895  5658  5704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-20 08:08:26.895  5658  5704 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-20 08:08:26.895  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-20 08:08:26.895  5658  5704 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-20 08:08:26.895  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.895  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.896  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-20 08:08:26.896  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.896  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:08:26.896  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b35630 removed from the list
,10-20 08:08:26.896  5909  5925 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-20 08:08:26.896  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.896  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.896  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:26.896  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3be82a9 removed from the list
10-20 08:08:26.896  5658  5704 D io.jxcore.node.ConnectivityMonitor: stop
10-20 08:08:26.896  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.896  5909  5928 D BtGatt.ScanManager: stopping BLe Batch
10-20 08:08:26.896  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.896  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:08:26.898  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-20 08:08:26.899  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.899  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.899  5658  5704 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3be82a9 not in the list
10-20 08:08:26.899  5658  5658 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-20 08:08:26.899  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.899  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-20 08:08:26.900  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-20 08:08:26.900  5909  5925 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-20 08:08:26.900  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-20 08:08:26.900  5658  5704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-20 08:08:26.900  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-20 08:08:26.900  5658  5704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12fa55c removed from the list
10-20 08:08:26.900  5658  5704 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-20 08:08:26.900  5909  5928 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-20 08:08:26.900  5658  5704 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-20 08:08:26.900  5658  5704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-20 08:08:26.900  5658  5704 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-20 08:08:26.900  5658  5704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-20 08:08:26.900  5658  5704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b57cf removed from the list
,10-20 08:08:26.901  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-20 08:08:26.901  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-20 08:08:26.902  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-20 08:08:26.902  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:08:26.902  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-20 08:08:26.902  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-20 08:08:26.904  5909  5925 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-20 08:08:26.904  5909  5925 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-20 08:08:27.282  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-20 08:08:27.335  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-20 08:08:27.383  5658  5658 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-20 08:08:29.038  5658  5991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-20 08:08:29.038  5658  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-20 08:08:29.310   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:08:29.820  5658  5991 W !!      : call onHalfStreamCopied
,10-20 08:08:29.820  5658  5991 I testCopyDataAndClose: closing input stream
,10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
,10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-20 08:08:30.595  5658  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-20 08:08:32.338   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:08:34.358  5658  5992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:34.358  5658  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-20 08:08:34.545   928  3009 D ConnectivityService: handlePromptUnvalidated 102
,10-20 08:08:35.358   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:08:36.358  5658  5704 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
10-20 08:08:36.358  5658  5704 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-20 08:08:36.358  5658  5704 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,10-20 08:08:36.379  5658  5992 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-20 08:08:36.379  5658  5992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:36.379  5658  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,10-20 08:08:36.497  5658  5993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-20 08:08:36.497  5658  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-20 08:08:37.579   928  3007 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-20 08:08:38.120  5658  5993 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-20 08:08:38.121  5658  5993 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-20 08:08:38.121  5658  5993 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-20 08:08:38.121  5658  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-20 08:08:38.380   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:08:41.862  5658  5994 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:41.862  5658  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-20 08:08:41.862  5658  5994 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:41.862  5658  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-20 08:08:41.862  5658  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-20 08:08:41.862  5658  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-20 08:08:41.863  5658  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-20 08:08:41.863  5658  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-20 08:08:41.863  5658  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-20 08:08:41.864  5658  5994 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-20 08:08:41.864  5658  5994 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-20 08:08:41.864  5658  5994 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:41.864  5658  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-20 08:08:41.866  5658  5704 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-20 08:08:41.869  5658  5995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:41.869  5658  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-20 08:08:41.869  5658  5995 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
,10-20 08:08:41.870  5658  5995 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:41.870  5658  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-20 08:08:41.870  5658  5995 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-20 08:08:41.870  5658  5995 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-20 08:08:41.870  5658  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-20 08:08:41.875  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-20 08:08:41.875  5658  5704 I jxcore-log: 
10-20 08:08:41.875  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-20 08:08:41.875  5658  5704 I jxcore-log: 
10-20 08:08:41.875  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-20 08:08:41.875  5658  5704 I jxcore-log: 
,10-20 08:08:41.876  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-20 08:08:41.876  5658  5704 I jxcore-log: 
10-20 08:08:41.876  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'Total duration:  90707'
10-20 08:08:41.876  5658  5704 I jxcore-log: 
10-20 08:08:41.878  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-20 08:08:41.878  5658  5704 I jxcore-log: 
,10-20 08:08:41.881  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.881  5658  5704 I jxcore-log: 
10-20 08:08:41.882  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.882  5658  5704 I jxcore-log: 
,10-20 08:08:41.882  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.882  5658  5704 I jxcore-log: 
10-20 08:08:41.882  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.882  5658  5704 I jxcore-log: 
10-20 08:08:41.883  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-20 08:08:41.883  5658  5704 I jxcore-log: 
,10-20 08:08:41.883  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-20 08:08:41.883  5658  5704 I jxcore-log: 
10-20 08:08:41.883  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.883  5658  5704 I jxcore-log: 
10-20 08:08:41.884  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.884  5658  5704 I jxcore-log: 
,10-20 08:08:41.884  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-20 08:08:41.884  5658  5704 I jxcore-log: 
10-20 08:08:41.884  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-20 08:08:41.884  5658  5704 I jxcore-log: 
10-20 08:08:41.884  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-20 08:08:41.884  5658  5704 I jxcore-log: 
10-20 08:08:41.885  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.885  5658  5704 I jxcore-log: 
10-20 08:08:41.885  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.885  5658  5704 I jxcore-log: 
,10-20 08:08:41.885  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.885  5658  5704 I jxcore-log: 
10-20 08:08:41.885  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.885  5658  5704 I jxcore-log: 
10-20 08:08:41.886  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.886  5658  5704 I jxcore-log: 
10-20 08:08:41.886  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.886  5658  5704 I jxcore-log: 
,10-20 08:08:41.886  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.886  5658  5704 I jxcore-log: 
10-20 08:08:41.886  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.886  5658  5704 I jxcore-log: 
10-20 08:08:41.887  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.887  5658  5704 I jxcore-log: 
10-20 08:08:41.887  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.887  5658  5704 I jxcore-log: 
,10-20 08:08:41.887  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.887  5658  5704 I jxcore-log: 
10-20 08:08:41.887  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.887  5658  5704 I jxcore-log: 
10-20 08:08:41.889  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.889  5658  5704 I jxcore-log: 
10-20 08:08:41.889  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.889  5658  5704 I jxcore-log: 
10-20 08:08:41.889  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.889  5658  5704 I jxcore-log: 
10-20 08:08:41.890  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.890  5658  5704 I jxcore-log: 
,10-20 08:08:41.890  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.890  5658  5704 I jxcore-log: 
10-20 08:08:41.890  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.890  5658  5704 I jxcore-log: 
10-20 08:08:41.890  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.890  5658  5704 I jxcore-log: 
10-20 08:08:41.890  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.890  5658  5704 I jxcore-log: 
,10-20 08:08:41.891  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.891  5658  5704 I jxcore-log: 
10-20 08:08:41.891  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.891  5658  5704 I jxcore-log: 
10-20 08:08:41.891  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.891  5658  5704 I jxcore-log: 
10-20 08:08:41.891  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.891  5658  5704 I jxcore-log: 
10-20 08:08:41.892  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.892  5658  5704 I jxcore-log: 
10-20 08:08:41.892  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.892  5658  5704 I jxcore-log: 
,10-20 08:08:41.892  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.892  5658  5704 I jxcore-log: 
10-20 08:08:41.892  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.892  5658  5704 I jxcore-log: 
10-20 08:08:41.892  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.892  5658  5704 I jxcore-log: 
10-20 08:08:41.893  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-20 08:08:41.893  5658  5704 I jxcore-log: 
10-20 08:08:41.893  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.893  5658  5704 I jxcore-log: 
,10-20 08:08:41.893  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-20 08:08:41.893  5658  5704 I jxcore-log: 
10-20 08:08:41.893  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.893  5658  5704 I jxcore-log: 
10-20 08:08:41.893  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.893  5658  5704 I jxcore-log: 
10-20 08:08:41.894  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.894  5658  5704 I jxcore-log: 
10-20 08:08:41.894  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.894  5658  5704 I jxcore-log: 
10-20 08:08:41.894  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.894  5658  5704 I jxcore-log: 
10-20 08:08:41.894  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-20 08:08:41.894  5658  5704 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-20 08:08:41.895  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.895  5658  5704 I jxcore-log: 
10-20 08:08:41.895  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.895  5658  5704 I jxcore-log: 
10-20 08:08:41.895  5658  5704 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-20 08:08:41.895  5658  5704 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-20 08:08:41.895  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-20 08:08:41.895  5658  5704 I jxcore-log: 
10-20 08:08:41.895  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-20 08:08:41.895  5658  5704 I jxcore-log: 
10-20 08:08:41.896  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-20 08:08:41.896  5658  5704 I jxcore-log: 
10-20 08:08:41.896  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-20 08:08:41.896  5658  5704 I jxcore-log: 
10-20 08:08:41.901  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-20 08:08:41.901  5658  5704 I jxcore-log: 
10-20 08:08:41.901 , 5658  5704 I jxcore-log: 2016-10-20 12:08:41 - WARN testUtils: 'myNameCallback not set!'
10-20 08:08:41.901  5658  5704 I jxcore-log: 
10-20 08:08:41.903  5658  5704 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-20 08:08:41.902  5658  5658 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-20 08:08:41.903  5658  5704 I jxcore-log: 2016-10-20 12:08:41 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-20 08:08:41.903  5658  5704 I jxcore-log: 
,10-20 08:08:43.913  5658  5704 I jxcore-log: 2016-10-20 12:08:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-20 08:08:43.913  5658  5704 I jxcore-log: 
,10-20 08:08:44.241  5658  5704 I jxcore-log: 2016-10-20 12:08:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-20 08:08:44.241  5658  5704 I jxcore-log: 
,10-20 08:08:44.256  5658  5704 I jxcore-log: 2016-10-20 12:08:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-20 08:08:44.256  5658  5704 I jxcore-log: 
,10-20 08:08:44.430   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:08:45.358  5658  5704 I jxcore-log: 2016-10-20 12:08:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-20 08:08:45.358  5658  5704 I jxcore-log: 
,10-20 08:08:45.521  5658  5704 I jxcore-log: 2016-10-20 12:08:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-20 08:08:45.521  5658  5704 I jxcore-log: 
,10-20 08:08:45.527  5658  5704 I jxcore-log: 2016-10-20 12:08:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-20 08:08:45.527  5658  5704 I jxcore-log: 
,10-20 08:08:45.531  5658  5704 I jxcore-log: 2016-10-20 12:08:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-20 08:08:45.531  5658  5704 I jxcore-log: 
,10-20 08:08:46.004  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-20 08:08:46.004  5658  5704 I jxcore-log: 
,10-20 08:08:46.047  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-20 08:08:46.047  5658  5704 I jxcore-log: 
,10-20 08:08:46.060  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-20 08:08:46.060  5658  5704 I jxcore-log: 
,10-20 08:08:46.064  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-20 08:08:46.064  5658  5704 I jxcore-log: 
,10-20 08:08:46.341  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-20 08:08:46.341  5658  5704 I jxcore-log: 
,10-20 08:08:46.464  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-20 08:08:46.464  5658  5704 I jxcore-log: 
,10-20 08:08:46.835  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-20 08:08:46.835  5658  5704 I jxcore-log: 
,10-20 08:08:46.843  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-20 08:08:46.843  5658  5704 I jxcore-log: 
,10-20 08:08:46.847  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-20 08:08:46.847  5658  5704 I jxcore-log: 
,10-20 08:08:46.851  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-20 08:08:46.851  5658  5704 I jxcore-log: 
,10-20 08:08:46.856  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-20 08:08:46.856  5658  5704 I jxcore-log: 
,10-20 08:08:46.883  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-20 08:08:46.883  5658  5704 I jxcore-log: 
,10-20 08:08:46.916  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-20 08:08:46.916  5658  5704 I jxcore-log: 
,10-20 08:08:46.922  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-20 08:08:46.922  5658  5704 I jxcore-log: 
,10-20 08:08:46.928  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-20 08:08:46.928  5658  5704 I jxcore-log: 
,10-20 08:08:46.941  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-20 08:08:46.941  5658  5704 I jxcore-log: 
,10-20 08:08:46.946  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-20 08:08:46.946  5658  5704 I jxcore-log: 
,10-20 08:08:46.952  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-20 08:08:46.952  5658  5704 I jxcore-log: 
,10-20 08:08:46.957  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-20 08:08:46.957  5658  5704 I jxcore-log: 
,10-20 08:08:46.969  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-20 08:08:46.969  5658  5704 I jxcore-log: 
,10-20 08:08:46.991  5658  5704 I jxcore-log: 2016-10-20 12:08:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-20 08:08:46.991  5658  5704 I jxcore-log: 
,10-20 08:08:47.002  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-20 08:08:47.002  5658  5704 I jxcore-log: 
,10-20 08:08:47.014  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-20 08:08:47.014  5658  5704 I jxcore-log: 
,10-20 08:08:47.024  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-20 08:08:47.024  5658  5704 I jxcore-log: 
,10-20 08:08:47.036  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-20 08:08:47.036  5658  5704 I jxcore-log: 
,10-20 08:08:47.046  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-20 08:08:47.046  5658  5704 I jxcore-log: 
,10-20 08:08:47.051  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-20 08:08:47.051  5658  5704 I jxcore-log: 
,10-20 08:08:47.072  5658  5704 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-20 08:08:47.073  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - INFO testUtils: 'BLE multiple advertisement supported'
10-20 08:08:47.073  5658  5704 I jxcore-log: 
,10-20 08:08:47.166  5658  5704 I jxcore-log: 2016-10-20 12:08:47 - DEBUG CoordinatedClient: 'connected to the test server'
10-20 08:08:47.166  5658  5704 I jxcore-log: 
,10-20 08:08:47.713  5658  5704 I jxcore-log: TAP version 13
10-20 08:08:47.713  5658  5704 I jxcore-log: 
,10-20 08:08:47.755  5658  5704 I jxcore-log: # setup
10-20 08:08:47.755  5658  5704 I jxcore-log: 
,10-20 08:08:48.257  5658  5704 I jxcore-log: # calling createNativeListener directly rejects
10-20 08:08:48.257  5658  5704 I jxcore-log: 
,10-20 08:08:48.405  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:48.405  5658  5704 I jxcore-log: 
,10-20 08:08:48.411  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'listening 47586'
10-20 08:08:48.411  5658  5704 I jxcore-log: 
,10-20 08:08:48.420  5658  5704 I jxcore-log: ok 1 Should throw
10-20 08:08:48.420  5658  5704 I jxcore-log: 
,10-20 08:08:48.430  5658  5704 I jxcore-log: # teardown
10-20 08:08:48.430  5658  5704 I jxcore-log: 
,10-20 08:08:48.583   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-20 08:08:48.584   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-20 08:08:48.602  5658  5704 I jxcore-log: # setup
10-20 08:08:48.602  5658  5704 I jxcore-log: 
,10-20 08:08:48.733  5658  5704 I jxcore-log: # emits incomingConnectionState
10-20 08:08:48.733  5658  5704 I jxcore-log: 
,10-20 08:08:48.932  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:48.932  5658  5704 I jxcore-log: 
,10-20 08:08:48.937  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'listening 37276'
10-20 08:08:48.937  5658  5704 I jxcore-log: 
,10-20 08:08:48.948  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:48.948  5658  5704 I jxcore-log: 
,10-20 08:08:48.951  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:48.951  5658  5704 I jxcore-log: 
,10-20 08:08:48.961  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'new mux'
10-20 08:08:48.961  5658  5704 I jxcore-log: 
,10-20 08:08:48.968  5658  5704 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-20 08:08:48.968  5658  5704 I jxcore-log: 
,10-20 08:08:48.982  5658  5704 I jxcore-log: 2016-10-20 12:08:48 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:48.982  5658  5704 I jxcore-log: 
,10-20 08:08:48.983  5658  5704 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-20 08:08:48.983  5658  5704 I jxcore-log: 
,10-20 08:08:48.991  5658  5704 I jxcore-log: # teardown
10-20 08:08:48.991  5658  5704 I jxcore-log: 
,10-20 08:08:49.038  5658  5704 I jxcore-log: # setup
10-20 08:08:49.038  5658  5704 I jxcore-log: 
,10-20 08:08:49.380  5658  5704 I jxcore-log: # emits routerPortConnectionFailed
10-20 08:08:49.380  5658  5704 I jxcore-log: 
,10-20 08:08:49.718  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:49.718  5658  5704 I jxcore-log: 
,10-20 08:08:49.721  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'listening 42943'
10-20 08:08:49.721  5658  5704 I jxcore-log: 
,10-20 08:08:49.728  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:49.728  5658  5704 I jxcore-log: 
,10-20 08:08:49.730  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:49.730  5658  5704 I jxcore-log: 
,10-20 08:08:49.731  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'new mux'
10-20 08:08:49.731  5658  5704 I jxcore-log: 
,10-20 08:08:49.757  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:49.757  5658  5704 I jxcore-log: 
,10-20 08:08:49.761  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:49.761  5658  5704 I jxcore-log: 
,10-20 08:08:49.766  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: ' $c@net.js:837:7
10-20 08:08:49.766  5658  5704 I jxcore-log: $09@net.js:829:13
10-20 08:08:49.766  5658  5704 I jxcore-log: '
10-20 08:08:49.766  5658  5704 I jxcore-log: 
,10-20 08:08:49.767  5658  5704 I jxcore-log: ok 4 tried to connect to right port
10-20 08:08:49.767  5658  5704 I jxcore-log: 
,10-20 08:08:49.768  5658  5704 I jxcore-log: ok 5 failed due to refused connection
10-20 08:08:49.768  5658  5704 I jxcore-log: 
10-20 08:08:49.769  5658  5704 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-20 08:08:49.769  5658  5704 I jxcore-log: 
,10-20 08:08:49.773  5658  5704 I jxcore-log: # teardown
10-20 08:08:49.773  5658  5704 I jxcore-log: 
,10-20 08:08:49.775  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:49.775  5658  5704 I jxcore-log: 
,10-20 08:08:49.863  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'mux close'
10-20 08:08:49.863  5658  5704 I jxcore-log: 
,10-20 08:08:49.869  5658  5704 I jxcore-log: 2016-10-20 12:08:49 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:49.869  5658  5704 I jxcore-log: 
,10-20 08:08:49.881  5658  5704 I jxcore-log: # setup
10-20 08:08:49.881  5658  5704 I jxcore-log: 
,10-20 08:08:50.191  5658  5704 I jxcore-log: # native server connections all up
10-20 08:08:50.191  5658  5704 I jxcore-log: 
,10-20 08:08:50.305  5964  5964 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-20 08:08:50.453  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:50.453  5658  5704 I jxcore-log: 
,10-20 08:08:50.459  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'listening 43937'
10-20 08:08:50.459  5658  5704 I jxcore-log: 
,10-20 08:08:50.469  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:50.469  5658  5704 I jxcore-log: 
,10-20 08:08:50.471  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:50.471  5658  5704 I jxcore-log: 
,10-20 08:08:50.473  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'new mux'
10-20 08:08:50.473  5658  5704 I jxcore-log: 
,10-20 08:08:50.500  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:50.500  5658  5704 I jxcore-log: 
,10-20 08:08:50.503  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:50.503  5658  5704 I jxcore-log: 
,10-20 08:08:50.505  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:50.505  5658  5704 I jxcore-log: 
,10-20 08:08:50.508  5658  5704 I jxcore-log: 2016-10-20 12:08:50 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:50.508  5658  5704 I jxcore-log: 
,10-20 08:08:50.528  5658  5704 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-20 08:08:50.528  5658  5704 I jxcore-log: 
,10-20 08:08:50.529  5658  5704 I jxcore-log: ok 8 Send/recvd #1 should be same
10-20 08:08:50.529  5658  5704 I jxcore-log: 
10-20 08:08:50.531  5658  5704 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-20 08:08:50.531  5658  5704 I jxcore-log: 
10-20 08:08:50.532  5658  5704 I jxcore-log: ok 10 Send/recvd #2 should be same
10-20 08:08:50.532  5658  5704 I jxcore-log: 
,10-20 08:08:50.534  5658  5704 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-20 08:08:50.534  5658  5704 I jxcore-log: 
,10-20 08:08:50.541  5658  5704 I jxcore-log: # teardown
10-20 08:08:50.541  5658  5704 I jxcore-log: 
,10-20 08:08:51.404  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:51.404  5658  5704 I jxcore-log: 
,10-20 08:08:51.407  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:51.407  5658  5704 I jxcore-log: 
,10-20 08:08:51.412  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'mux close'
10-20 08:08:51.412  5658  5704 I jxcore-log: 
,10-20 08:08:51.419  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:51.419  5658  5704 I jxcore-log: 
,10-20 08:08:51.435  5658  5704 I jxcore-log: # setup
10-20 08:08:51.435  5658  5704 I jxcore-log: 
,10-20 08:08:51.476  5658  5704 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-20 08:08:51.476  5658  5704 I jxcore-log: 
,10-20 08:08:51.518  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:51.518  5658  5704 I jxcore-log: 
,10-20 08:08:51.522  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'listening 48964'
10-20 08:08:51.522  5658  5704 I jxcore-log: 
,10-20 08:08:51.529  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:51.529  5658  5704 I jxcore-log: 
,10-20 08:08:51.531  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:51.531  5658  5704 I jxcore-log: 
,10-20 08:08:51.535  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new mux'
10-20 08:08:51.535  5658  5704 I jxcore-log: 
,10-20 08:08:51.545  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:51.545  5658  5704 I jxcore-log: 
,10-20 08:08:51.548  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:51.548  5658  5704 I jxcore-log: 
,10-20 08:08:51.561  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:51.561  5658  5704 I jxcore-log: 
,10-20 08:08:51.573  5658  5704 I jxcore-log: ok 12 socket shouldn't close until after stream
10-20 08:08:51.573  5658  5704 I jxcore-log: 
,10-20 08:08:51.574  5658  5704 I jxcore-log: ok 13 incoming remains open
10-20 08:08:51.574  5658  5704 I jxcore-log: 
,10-20 08:08:51.581  5658  5704 I jxcore-log: # teardown
10-20 08:08:51.581  5658  5704 I jxcore-log: 
,10-20 08:08:51.617  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'mux close'
10-20 08:08:51.617  5658  5704 I jxcore-log: 
,10-20 08:08:51.622  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:51.622  5658  5704 I jxcore-log: 
,10-20 08:08:51.629  5658  5704 I jxcore-log: # setup
10-20 08:08:51.629  5658  5704 I jxcore-log: 
,10-20 08:08:51.686  5658  5704 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-20 08:08:51.686  5658  5704 I jxcore-log: 
,10-20 08:08:51.728  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:51.728  5658  5704 I jxcore-log: 
,10-20 08:08:51.732  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'listening 44749'
10-20 08:08:51.732  5658  5704 I jxcore-log: 
,10-20 08:08:51.739  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:51.739  5658  5704 I jxcore-log: 
,10-20 08:08:51.741  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:51.741  5658  5704 I jxcore-log: 
10-20 08:08:51.743  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new mux'
10-20 08:08:51.743  5658  5704 I jxcore-log: 
,10-20 08:08:51.753  5658  5704 I jxcore-log: ok 14 we should not have gotten an error
10-20 08:08:51.753  5658  5704 I jxcore-log: 
,10-20 08:08:51.758  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:51.758  5658  5704 I jxcore-log: 
,10-20 08:08:51.763  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:51.763  5658  5704 I jxcore-log: 
,10-20 08:08:51.773  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:51.773  5658  5704 I jxcore-log: 
,10-20 08:08:51.776  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:51.776  5658  5704 I jxcore-log: 
,10-20 08:08:51.785  5658  5704 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-20 08:08:51.785  5658  5704 I jxcore-log: 
,10-20 08:08:51.786  5658  5704 I jxcore-log: ok 16 incoming is cleaned up
10-20 08:08:51.786  5658  5704 I jxcore-log: 
,10-20 08:08:51.795  5658  5704 I jxcore-log: # teardown
10-20 08:08:51.795  5658  5704 I jxcore-log: 
,10-20 08:08:51.870  5658  5704 I jxcore-log: # setup
10-20 08:08:51.870  5658  5704 I jxcore-log: 
,10-20 08:08:51.930  5658  5704 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-20 08:08:51.930  5658  5704 I jxcore-log: 
,10-20 08:08:51.968  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:51.968  5658  5704 I jxcore-log: 
,10-20 08:08:51.973  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'listening 43363'
10-20 08:08:51.973  5658  5704 I jxcore-log: 
,10-20 08:08:51.981  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:51.981  5658  5704 I jxcore-log: 
,10-20 08:08:51.983  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:51.983  5658  5704 I jxcore-log: 
,10-20 08:08:51.987  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new mux'
10-20 08:08:51.987  5658  5704 I jxcore-log: 
,10-20 08:08:51.999  5658  5704 I jxcore-log: 2016-10-20 12:08:51 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:51.999  5658  5704 I jxcore-log: 
,10-20 08:08:52.002  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.002  5658  5704 I jxcore-log: 
,10-20 08:08:52.018  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.018  5658  5704 I jxcore-log: 
,10-20 08:08:52.028  5658  5704 I jxcore-log: ok 17 stream was closed
10-20 08:08:52.028  5658  5704 I jxcore-log: 
,10-20 08:08:52.028  5658  5704 I jxcore-log: ok 18 incoming should survive
10-20 08:08:52.028  5658  5704 I jxcore-log: 
10-20 08:08:52.028  5658  5704 I jxcore-log: ok 19 mux should have no streams
10-20 08:08:52.028  5658  5704 I jxcore-log: 
,10-20 08:08:52.034  5658  5704 I jxcore-log: # teardown
10-20 08:08:52.034  5658  5704 I jxcore-log: 
,10-20 08:08:52.056  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.056  5658  5704 I jxcore-log: 
,10-20 08:08:52.067  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.067  5658  5704 I jxcore-log: 
,10-20 08:08:52.078  5658  5704 I jxcore-log: # setup
10-20 08:08:52.078  5658  5704 I jxcore-log: 
,10-20 08:08:52.151  5658  5704 I jxcore-log: # native server - closing the whole server cleans everything up
10-20 08:08:52.151  5658  5704 I jxcore-log: 
,10-20 08:08:52.190  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:52.190  5658  5704 I jxcore-log: 
,10-20 08:08:52.199  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'listening 46685'
10-20 08:08:52.199  5658  5704 I jxcore-log: 
,10-20 08:08:52.207  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.207  5658  5704 I jxcore-log: 
,10-20 08:08:52.209  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.209  5658  5704 I jxcore-log: 
,10-20 08:08:52.211  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.211  5658  5704 I jxcore-log: 
,10-20 08:08:52.224  5658  5704 I jxcore-log: ok 20 we should not have gotten an error
10-20 08:08:52.224  5658  5704 I jxcore-log: 
,10-20 08:08:52.232  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.232  5658  5704 I jxcore-log: 
,10-20 08:08:52.237  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.237  5658  5704 I jxcore-log: 
,10-20 08:08:52.249  5658  5704 I jxcore-log: ok 21 Buffers are identical
10-20 08:08:52.249  5658  5704 I jxcore-log: 
,10-20 08:08:52.252  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.252  5658  5704 I jxcore-log: 
,10-20 08:08:52.256  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.256  5658  5704 I jxcore-log: 
,10-20 08:08:52.260  5658  5704 I jxcore-log: ok 22 native server is nulled out
10-20 08:08:52.260  5658  5704 I jxcore-log: 
,10-20 08:08:52.261  5658  5704 I jxcore-log: ok 23 native server should be closed
10-20 08:08:52.261  5658  5704 I jxcore-log: 
10-20 08:08:52.262  5658  5704 I jxcore-log: ok 24 incoming has been removed
10-20 08:08:52.262  5658  5704 I jxcore-log: 
10-20 08:08:52.262  5658  5704 I jxcore-log: ok 25 Incoming should be done
10-20 08:08:52.262  5658  5704 I jxcore-log: 
,10-20 08:08:52.263  5658  5704 I jxcore-log: ok 26 The mux object should be closed
10-20 08:08:52.263  5658  5704 I jxcore-log: 
10-20 08:08:52.263  5658  5704 I jxcore-log: ok 27 The mux stream should be closed
10-20 08:08:52.263  5658  5704 I jxcore-log: 
10-20 08:08:52.265  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.265  5658  5704 I jxcore-log: 
,10-20 08:08:52.283  5658  5704 I jxcore-log: # teardown
10-20 08:08:52.283  5658  5704 I jxcore-log: 
,10-20 08:08:52.308  5658  5704 I jxcore-log: # setup
10-20 08:08:52.308  5658  5704 I jxcore-log: 
,10-20 08:08:52.397  5658  5704 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-20 08:08:52.397  5658  5704 I jxcore-log: 
,10-20 08:08:52.458  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:52.458  5658  5704 I jxcore-log: 
,10-20 08:08:52.463  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'listening 43976'
10-20 08:08:52.463  5658  5704 I jxcore-log: 
,10-20 08:08:52.497  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.497  5658  5704 I jxcore-log: 
,10-20 08:08:52.498  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.498  5658  5704 I jxcore-log: 
10-20 08:08:52.499  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.499  5658  5704 I jxcore-log: 
,10-20 08:08:52.505  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.505  5658  5704 I jxcore-log: 
,10-20 08:08:52.506  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.506  5658  5704 I jxcore-log: 
10-20 08:08:52.507  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.507  5658  5704 I jxcore-log: 
,10-20 08:08:52.511  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.511  5658  5704 I jxcore-log: 
,10-20 08:08:52.511  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.511  5658  5704 I jxcore-log: 
10-20 08:08:52.513  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.513  5658  5704 I jxcore-log: 
,10-20 08:08:52.517  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.517  5658  5704 I jxcore-log: 
,10-20 08:08:52.518  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.518  5658  5704 I jxcore-log: 
10-20 08:08:52.519  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.519  5658  5704 I jxcore-log: 
,10-20 08:08:52.523  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.523  5658  5704 I jxcore-log: 
,10-20 08:08:52.524  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.524  5658  5704 I jxcore-log: 
,10-20 08:08:52.528  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.528  5658  5704 I jxcore-log: 
10-20 08:08:52.531  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.531  5658  5704 I jxcore-log: 
10-20 08:08:52.532  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.532  5658  5704 I jxcore-log: 
10-20 08:08:52.534  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.534  5658  5704 I jxcore-log: 
,10-20 08:08:52.537  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.537  5658  5704 I jxcore-log: 
,10-20 08:08:52.537  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.537  5658  5704 I jxcore-log: 
10-20 08:08:52.538  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.538  5658  5704 I jxcore-log: 
,10-20 08:08:52.546  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.546  5658  5704 I jxcore-log: 
,10-20 08:08:52.546  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.546  5658  5704 I jxcore-log: 
,10-20 08:08:52.548  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.548  5658  5704 I jxcore-log: 
,10-20 08:08:52.550  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.550  5658  5704 I jxcore-log: 
,10-20 08:08:52.551  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.551  5658  5704 I jxcore-log: 
,10-20 08:08:52.553  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.553  5658  5704 I jxcore-log: 
,10-20 08:08:52.555  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:52.555  5658  5704 I jxcore-log: 
,10-20 08:08:52.555  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:52.555  5658  5704 I jxcore-log: 
10-20 08:08:52.556  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new mux'
10-20 08:08:52.556  5658  5704 I jxcore-log: 
,10-20 08:08:52.629  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.629  5658  5704 I jxcore-log: 
,10-20 08:08:52.631  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.631  5658  5704 I jxcore-log: 
,10-20 08:08:52.632  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.632  5658  5704 I jxcore-log: 
,10-20 08:08:52.634  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.634  5658  5704 I jxcore-log: 
,10-20 08:08:52.634  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.634  5658  5704 I jxcore-log: 
,10-20 08:08:52.635  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.635  5658  5704 I jxcore-log: 
,10-20 08:08:52.637  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.637  5658  5704 I jxcore-log: 
,10-20 08:08:52.638  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.638  5658  5704 I jxcore-log: 
,10-20 08:08:52.639  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.639  5658  5704 I jxcore-log: 
,10-20 08:08:52.641  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.641  5658  5704 I jxcore-log: 
,10-20 08:08:52.641  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.641  5658  5704 I jxcore-log: 
,10-20 08:08:52.642  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.642  5658  5704 I jxcore-log: 
10-20 08:08:52.643  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.643  5658  5704 I jxcore-log: 
,10-20 08:08:52.644  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.644  5658  5704 I jxcore-log: 
,10-20 08:08:52.645  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.645  5658  5704 I jxcore-log: 
,10-20 08:08:52.646  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.646  5658  5704 I jxcore-log: 
,10-20 08:08:52.647  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.647  5658  5704 I jxcore-log: 
,10-20 08:08:52.648  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.648  5658  5704 I jxcore-log: 
,10-20 08:08:52.649  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.649  5658  5704 I jxcore-log: 
10-20 08:08:52.650  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.650  5658  5704 I jxcore-log: 
,10-20 08:08:52.651  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.651  5658  5704 I jxcore-log: 
,10-20 08:08:52.651  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.651  5658  5704 I jxcore-log: 
10-20 08:08:52.652  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.652  5658  5704 I jxcore-log: 
,10-20 08:08:52.653  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.653  5658  5704 I jxcore-log: 
,10-20 08:08:52.654  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.654  5658  5704 I jxcore-log: 
,10-20 08:08:52.655  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.655  5658  5704 I jxcore-log: 
10-20 08:08:52.656  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.656  5658  5704 I jxcore-log: 
,10-20 08:08:52.657  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.657  5658  5704 I jxcore-log: 
10-20 08:08:52.657  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.657  5658  5704 I jxcore-log: 
,10-20 08:08:52.658  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.658  5658  5704 I jxcore-log: 
10-20 08:08:52.659  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.659  5658  5704 I jxcore-log: 
,10-20 08:08:52.660  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.660  5658  5704 I jxcore-log: 
,10-20 08:08:52.661  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.661  5658  5704 I jxcore-log: 
10-20 08:08:52.662  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.662  5658  5704 I jxcore-log: 
10-20 08:08:52.662  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.662  5658  5704 I jxcore-log: 
10-20 08:08:52.663  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.663  5658  5704 I jxcore-log: 
,10-20 08:08:52.664  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.664  5658  5704 I jxcore-log: 
10-20 08:08:52.665  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.665  5658  5704 I jxcore-log: 
,10-20 08:08:52.665  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.665  5658  5704 I jxcore-log: 
,10-20 08:08:52.666  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.666  5658  5704 I jxcore-log: 
,10-20 08:08:52.667  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.667  5658  5704 I jxcore-log: 
10-20 08:08:52.668  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.668  5658  5704 I jxcore-log: 
10-20 08:08:52.669  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.669  5658  5704 I jxcore-log: 
,10-20 08:08:52.669  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.669  5658  5704 I jxcore-log: 
,10-20 08:08:52.670  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.670  5658  5704 I jxcore-log: 
10-20 08:08:52.671  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.671  5658  5704 I jxcore-log: 
,10-20 08:08:52.672  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.672  5658  5704 I jxcore-log: 
10-20 08:08:52.672  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.672  5658  5704 I jxcore-log: 
,10-20 08:08:52.679  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.679  5658  5704 I jxcore-log: 
,10-20 08:08:52.680  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.680  5658  5704 I jxcore-log: 
,10-20 08:08:52.681  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.681  5658  5704 I jxcore-log: 
10-20 08:08:52.682  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.682  5658  5704 I jxcore-log: 
,10-20 08:08:52.682  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.682  5658  5704 I jxcore-log: 
10-20 08:08:52.683  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.683  5658  5704 I jxcore-log: 
,10-20 08:08:52.684  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.684  5658  5704 I jxcore-log: 
10-20 08:08:52.684  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.684  5658  5704 I jxcore-log: 
,10-20 08:08:52.685  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.685  5658  5704 I jxcore-log: 
,10-20 08:08:52.686  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.686  5658  5704 I jxcore-log: 
10-20 08:08:52.687  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.687  5658  5704 I jxcore-log: 
,10-20 08:08:52.687  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.687  5658  5704 I jxcore-log: 
10-20 08:08:52.688  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.688  5658  5704 I jxcore-log: 
10-20 08:08:52.689  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.689  5658  5704 I jxcore-log: 
,10-20 08:08:52.689  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.689  5658  5704 I jxcore-log: 
,10-20 08:08:52.690  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.690  5658  5704 I jxcore-log: 
10-20 08:08:52.691  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.691  5658  5704 I jxcore-log: 
,10-20 08:08:52.692  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.692  5658  5704 I jxcore-log: 
,10-20 08:08:52.692  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.692  5658  5704 I jxcore-log: 
10-20 08:08:52.693  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.693  5658  5704 I jxcore-log: 
,10-20 08:08:52.693  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.693  5658  5704 I jxcore-log: 
10-20 08:08:52.694  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.694  5658  5704 I jxcore-log: 
,10-20 08:08:52.695  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.695  5658  5704 I jxcore-log: 
10-20 08:08:52.695  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.695  5658  5704 I jxcore-log: 
,10-20 08:08:52.696  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.696  5658  5704 I jxcore-log: 
,10-20 08:08:52.697  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.697  5658  5704 I jxcore-log: 
10-20 08:08:52.698  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.698  5658  5704 I jxcore-log: 
,10-20 08:08:52.698  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.698  5658  5704 I jxcore-log: 
10-20 08:08:52.699  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.699  5658  5704 I jxcore-log: 
,10-20 08:08:52.699  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.699  5658  5704 I jxcore-log: 
10-20 08:08:52.700  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:52.700  5658  5704 I jxcore-log: 
,10-20 08:08:52.701  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:52.701  5658  5704 I jxcore-log: 
,10-20 08:08:52.745  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.745  5658  5704 I jxcore-log: 
,10-20 08:08:52.746  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.746  5658  5704 I jxcore-log: 
,10-20 08:08:52.747  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.747  5658  5704 I jxcore-log: 
10-20 08:08:52.748  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.748  5658  5704 I jxcore-log: 
,10-20 08:08:52.748  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.748  5658  5704 I jxcore-log: 
10-20 08:08:52.749  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.749  5658  5704 I jxcore-log: 
,10-20 08:08:52.749  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.749  5658  5704 I jxcore-log: 
10-20 08:08:52.750  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.750  5658  5704 I jxcore-log: 
10-20 08:08:52.750  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.750  5658  5704 I jxcore-log: 
,10-20 08:08:52.751  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.751  5658  5704 I jxcore-log: 
10-20 08:08:52.751  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.751  5658  5704 I jxcore-log: 
10-20 08:08:52.752  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.752  5658  5704 I jxcore-log: 
10-20 08:08:52.752  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.752  5658  5704 I jxcore-log: 
,10-20 08:08:52.752  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.752  5658  5704 I jxcore-log: 
10-20 08:08:52.753  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.753  5658  5704 I jxcore-log: 
,10-20 08:08:52.754  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.754  5658  5704 I jxcore-log: 
10-20 08:08:52.754  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.754  5658  5704 I jxcore-log: 
,10-20 08:08:52.755  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.755  5658  5704 I jxcore-log: 
10-20 08:08:52.755  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.755  5658  5704 I jxcore-log: 
10-20 08:08:52.756  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.756  5658  5704 I jxcore-log: 
,10-20 08:08:52.756  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.756  5658  5704 I jxcore-log: 
10-20 08:08:52.756  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.756  5658  5704 I jxcore-log: 
10-20 08:08:52.757  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.757  5658  5704 I jxcore-log: 
,10-20 08:08:52.757  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.757  5658  5704 I jxcore-log: 
10-20 08:08:52.758  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.758  5658  5704 I jxcore-log: 
10-20 08:08:52.758  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.758  5658  5704 I jxcore-log: 
,10-20 08:08:52.759  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.759  5658  5704 I jxcore-log: 
10-20 08:08:52.759  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.759  5658  5704 I jxcore-log: 
10-20 08:08:52.759  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.759  5658  5704 I jxcore-log: 
,10-20 08:08:52.760  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.760  5658  5704 I jxcore-log: 
10-20 08:08:52.760  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.760  5658  5704 I jxcore-log: 
10-20 08:08:52.761  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.761  5658  5704 I jxcore-log: 
,10-20 08:08:52.761  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.761  5658  5704 I jxcore-log: 
10-20 08:08:52.762  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.762  5658  5704 I jxcore-log: 
,10-20 08:08:52.762  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.762  5658  5704 I jxcore-log: 
10-20 08:08:52.762  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.762  5658  5704 I jxcore-log: 
10-20 08:08:52.763  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.763  5658  5704 I jxcore-log: 
,10-20 08:08:52.763  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.763  5658  5704 I jxcore-log: 
10-20 08:08:52.764  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.764  5658  5704 I jxcore-log: 
,10-20 08:08:52.764  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.764  5658  5704 I jxcore-log: 
10-20 08:08:52.765  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.765  5658  5704 I jxcore-log: 
10-20 08:08:52.765  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.765  5658  5704 I jxcore-log: 
,10-20 08:08:52.765  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.765  5658  5704 I jxcore-log: 
10-20 08:08:52.766  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.766  5658  5704 I jxcore-log: 
10-20 08:08:52.767  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.767  5658  5704 I jxcore-log: 
,10-20 08:08:52.768  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.768  5658  5704 I jxcore-log: 
,10-20 08:08:52.770  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.770  5658  5704 I jxcore-log: 
10-20 08:08:52.771  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.771  5658  5704 I jxcore-log: 
,10-20 08:08:52.772  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:52.772  5658  5704 I jxcore-log: 
10-20 08:08:52.772  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'mux close'
10-20 08:08:52.772  5658  5704 I jxcore-log: 
,10-20 08:08:52.774  5658  5704 I jxcore-log: ok 28 native server is nulled out
10-20 08:08:52.774  5658  5704 I jxcore-log: 
,10-20 08:08:52.774  5658  5704 I jxcore-log: ok 29 native server should be closed
10-20 08:08:52.774  5658  5704 I jxcore-log: 
10-20 08:08:52.775  5658  5704 I jxcore-log: ok 30 incoming has been removed
10-20 08:08:52.775  5658  5704 I jxcore-log: 
10-20 08:08:52.775  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.775  5658  5704 I jxcore-log: 
,10-20 08:08:52.776  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.776  5658  5704 I jxcore-log: 
10-20 08:08:52.776  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.776  5658  5704 I jxcore-log: 
10-20 08:08:52.776  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.776  5658  5704 I jxcore-log: 
10-20 08:08:52.777  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.777  5658  5704 I jxcore-log: 
10-20 08:08:52.777  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.777  5658  5704 I jxcore-log: 
,10-20 08:08:52.777  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.777  5658  5704 I jxcore-log: 
10-20 08:08:52.777  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.777  5658  5704 I jxcore-log: 
10-20 08:08:52.777  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.777  5658  5704 I jxcore-log: 
10-20 08:08:52.778  5658  5704 I jxcore-log: 2016-10-20 12:08:52 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:52.778  5658  5704 I jxcore-log: 
,10-20 08:08:52.850  5658  5704 I jxcore-log: # teardown
10-20 08:08:52.850  5658  5704 I jxcore-log: 
,10-20 08:08:53.949  5658  5704 I jxcore-log: # setup
10-20 08:08:53.949  5658  5704 I jxcore-log: 
,10-20 08:08:54.771  5658  5704 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-20 08:08:54.771  5658  5704 I jxcore-log: 
,10-20 08:08:55.699  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:55.699  5658  5704 I jxcore-log: 
,10-20 08:08:55.704  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'listening 40376'
10-20 08:08:55.704  5658  5704 I jxcore-log: 
,10-20 08:08:55.711  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:55.711  5658  5704 I jxcore-log: 
,10-20 08:08:55.713  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:55.713  5658  5704 I jxcore-log: 
,10-20 08:08:55.715  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'new mux'
10-20 08:08:55.715  5658  5704 I jxcore-log: 
,10-20 08:08:55.722  5658  5704 I jxcore-log: ok 31 we should not have gotten an error
10-20 08:08:55.722  5658  5704 I jxcore-log: 
,10-20 08:08:55.726  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:55.726  5658  5704 I jxcore-log: 
,10-20 08:08:55.729  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:55.729  5658  5704 I jxcore-log: 
,10-20 08:08:55.738  5658  5704 I jxcore-log: ok 32 Buffers are identical
10-20 08:08:55.738  5658  5704 I jxcore-log: 
,10-20 08:08:55.739  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:55.739  5658  5704 I jxcore-log: 
10-20 08:08:55.741  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'mux close'
10-20 08:08:55.741  5658  5704 I jxcore-log: 
,10-20 08:08:55.752  5658  5704 I jxcore-log: 2016-10-20 12:08:55 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:55.752  5658  5704 I jxcore-log: 
,10-20 08:08:55.754  5658  5704 I jxcore-log: ok 33 server should be fine
10-20 08:08:55.754  5658  5704 I jxcore-log: 
,10-20 08:08:55.754  5658  5704 I jxcore-log: ok 34 server should be open
10-20 08:08:55.754  5658  5704 I jxcore-log: 
,10-20 08:08:55.755  5658  5704 I jxcore-log: ok 35 incoming has been removed
10-20 08:08:55.755  5658  5704 I jxcore-log: 
10-20 08:08:55.755  5658  5704 I jxcore-log: ok 36 The mux object should be closed
10-20 08:08:55.755  5658  5704 I jxcore-log: 
,10-20 08:08:55.755  5658  5704 I jxcore-log: ok 37 The mux stream should be closed
10-20 08:08:55.755  5658  5704 I jxcore-log: 
10-20 08:08:55.761  5658  5704 I jxcore-log: # teardown
10-20 08:08:55.761  5658  5704 I jxcore-log: 
,10-20 08:08:56.104  5658  5704 I jxcore-log: # setup
10-20 08:08:56.104  5658  5704 I jxcore-log: 
,10-20 08:08:56.932  5658  5704 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-20 08:08:56.932  5658  5704 I jxcore-log: 
,10-20 08:08:57.221  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'creating native server'
10-20 08:08:57.221  5658  5704 I jxcore-log: 
,10-20 08:08:57.228  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'listening 49801'
10-20 08:08:57.228  5658  5704 I jxcore-log: 
,10-20 08:08:57.237  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'new incoming socket'
10-20 08:08:57.237  5658  5704 I jxcore-log: 
10-20 08:08:57.238  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'creating incoming mux'
10-20 08:08:57.238  5658  5704 I jxcore-log: 
,10-20 08:08:57.240  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'new mux'
10-20 08:08:57.240  5658  5704 I jxcore-log: 
,10-20 08:08:57.248  5658  5704 I jxcore-log: ok 38 we should not have gotten an error
10-20 08:08:57.248  5658  5704 I jxcore-log: 
,10-20 08:08:57.252  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'new stream: '
10-20 08:08:57.252  5658  5704 I jxcore-log: 
,10-20 08:08:57.255  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'new outgoing socket'
10-20 08:08:57.255  5658  5704 I jxcore-log: 
,10-20 08:08:57.263  5658  5704 I jxcore-log: ok 39 Buffers are identical
10-20 08:08:57.263  5658  5704 I jxcore-log: 
,10-20 08:08:57.268  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'incoming socket timeout'
10-20 08:08:57.268  5658  5704 I jxcore-log: 
,10-20 08:08:57.270  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'stream close:'
10-20 08:08:57.270  5658  5704 I jxcore-log: 
,10-20 08:08:57.272  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'mux close'
10-20 08:08:57.272  5658  5704 I jxcore-log: 
,10-20 08:08:57.278  5658  5704 I jxcore-log: 2016-10-20 12:08:57 - DEBUG createNativeListener: 'incoming socket close'
10-20 08:08:57.278  5658  5704 I jxcore-log: 
,10-20 08:08:57.279  5658  5704 I jxcore-log: ok 40 server should be fine
10-20 08:08:57.279  5658  5704 I jxcore-log: 
,10-20 08:08:57.280  5658  5704 I jxcore-log: ok 41 server should be open
10-20 08:08:57.280  5658  5704 I jxcore-log: 
10-20 08:08:57.281  5658  5704 I jxcore-log: ok 42 incoming has been removed
10-20 08:08:57.281  5658  5704 I jxcore-log: 
10-20 08:08:57.281  5658  5704 I jxcore-log: ok 43 The mux object should be closed
10-20 08:08:57.281  5658  5704 I jxcore-log: 
,10-20 08:08:57.282  5658  5704 I jxcore-log: ok 44 The mux stream should be closed
10-20 08:08:57.282  5658  5704 I jxcore-log: 
,10-20 08:08:57.290  5658  5704 I jxcore-log: # teardown
10-20 08:08:57.290  5658  5704 I jxcore-log: 
,10-20 08:08:58.255  5658  5704 I jxcore-log: # setup
10-20 08:08:58.255  5658  5704 I jxcore-log: 
,10-20 08:08:58.429  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-20 08:08:58.429  5658  5704 I jxcore-log: 
,10-20 08:08:59.711  5658  5704 I jxcore-log: 2016-10-20 12:08:59 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-20 08:08:59.711  5658  5704 I jxcore-log: 
,10-20 08:08:59.712  5658  5704 I jxcore-log: ok 45 Got right error
10-20 08:08:59.712  5658  5704 I jxcore-log: 
,10-20 08:08:59.717  5658  5704 I jxcore-log: # teardown
10-20 08:08:59.717  5658  5704 I jxcore-log: 
,10-20 08:08:59.791  5658  5704 I jxcore-log: # setup
10-20 08:08:59.791  5658  5704 I jxcore-log: 
,10-20 08:09:00.599  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-20 08:09:00.599  5658  5704 I jxcore-log: 
,10-20 08:09:01.584  5658  5704 I jxcore-log: 2016-10-20 12:09:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-20 08:09:01.584  5658  5704 I jxcore-log: 
,10-20 08:09:01.586  5658  5704 I jxcore-log: ok 46 Got socket hang up
10-20 08:09:01.586  5658  5704 I jxcore-log: 
,10-20 08:09:01.592  5658  5704 I jxcore-log: # teardown
10-20 08:09:01.592  5658  5704 I jxcore-log: 
,10-20 08:09:01.939  5658  5704 I jxcore-log: # setup
10-20 08:09:01.939  5658  5704 I jxcore-log: 
,10-20 08:09:02.852  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-20 08:09:02.852  5658  5704 I jxcore-log: 
,10-20 08:09:03.501  5658  5704 I jxcore-log: 2016-10-20 12:09:03 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-20 08:09:03.501  5658  5704 I jxcore-log: 
,10-20 08:09:03.502  5658  5704 I jxcore-log: ok 47 Got 500 as expected
10-20 08:09:03.502  5658  5704 I jxcore-log: 
,10-20 08:09:03.505  5658  5704 I jxcore-log: # teardown
10-20 08:09:03.505  5658  5704 I jxcore-log: 
,10-20 08:09:03.584   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:04.298  5658  5704 I jxcore-log: # setup
10-20 08:09:04.298  5658  5704 I jxcore-log: 
,10-20 08:09:04.336  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-20 08:09:04.336  5658  5704 I jxcore-log: 
,10-20 08:09:04.585   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:05.587   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:06.469  5658  5704 I jxcore-log: ok 48 should be equal
10-20 08:09:06.469  5658  5704 I jxcore-log: 
,10-20 08:09:06.470  5658  5704 I jxcore-log: ok 49 revs are equal
10-20 08:09:06.470  5658  5704 I jxcore-log: 
,10-20 08:09:06.475  5658  5704 I jxcore-log: # teardown
10-20 08:09:06.475  5658  5704 I jxcore-log: 
,10-20 08:09:06.523   928  3007 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-20 08:09:06.588   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:07.289  5658  5704 I jxcore-log: # setup
10-20 08:09:07.289  5658  5704 I jxcore-log: 
,10-20 08:09:07.590   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:08.291  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-20 08:09:08.291  5658  5704 I jxcore-log: 
,10-20 08:09:08.591   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-20 08:09:09.903  5658  5704 I jxcore-log: ok 50 should be equal
10-20 08:09:09.903  5658  5704 I jxcore-log: 
,10-20 08:09:09.904  5658  5704 I jxcore-log: ok 51 revs are equal
10-20 08:09:09.904  5658  5704 I jxcore-log: 
,10-20 08:09:09.911  5658  5704 I jxcore-log: # teardown
10-20 08:09:09.911  5658  5704 I jxcore-log: 
,10-20 08:09:10.111  5658  5704 I jxcore-log: # setup
10-20 08:09:10.111  5658  5704 I jxcore-log: 
,10-20 08:09:11.360  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-20 08:09:11.360  5658  5704 I jxcore-log: 
,10-20 08:09:12.134  5658  5704 I jxcore-log: ok 52 should be equal
10-20 08:09:12.134  5658  5704 I jxcore-log: 
,10-20 08:09:12.135  5658  5704 I jxcore-log: ok 53 revs are equal
10-20 08:09:12.135  5658  5704 I jxcore-log: 
,10-20 08:09:12.318  5658  5704 I jxcore-log: ok 54 should be equal
10-20 08:09:12.318  5658  5704 I jxcore-log: 
,10-20 08:09:12.319  5658  5704 I jxcore-log: ok 55 revs are equal
10-20 08:09:12.319  5658  5704 I jxcore-log: 
,10-20 08:09:12.518  5658  5704 I jxcore-log: ok 56 should be equal
10-20 08:09:12.518  5658  5704 I jxcore-log: 
10-20 08:09:12.519  5658  5704 I jxcore-log: ok 57 revs are equal
10-20 08:09:12.519  5658  5704 I jxcore-log: 
,10-20 08:09:12.528  5658  5704 I jxcore-log: # teardown
10-20 08:09:12.528  5658  5704 I jxcore-log: 
,10-20 08:09:13.119  5658  5704 I jxcore-log: # setup
10-20 08:09:13.119  5658  5704 I jxcore-log: 
,10-20 08:09:13.402  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-20 08:09:13.402  5658  5704 I jxcore-log: 
,10-20 08:09:13.592   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:14.593   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:15.257  5658  5704 I jxcore-log: 2016-10-20 12:09:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-20 08:09:15.257  5658  5704 I jxcore-log: 
10-20 08:09:15.258  5658  5704 I jxcore-log: ok 58 Our rev is old so we should fail
10-20 08:09:15.258  5658  5704 I jxcore-log: 
,10-20 08:09:15.278  5658  5704 I jxcore-log: # teardown
10-20 08:09:15.278  5658  5704 I jxcore-log: 
,10-20 08:09:15.322  5658  5704 I jxcore-log: # setup
10-20 08:09:15.322  5658  5704 I jxcore-log: 
,10-20 08:09:15.417  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-20 08:09:15.417  5658  5704 I jxcore-log: 
,10-20 08:09:15.519  5658  5704 I jxcore-log: ok 59 confirm stop caused failure
10-20 08:09:15.519  5658  5704 I jxcore-log: 
,10-20 08:09:15.532  5658  5704 I jxcore-log: # teardown
10-20 08:09:15.532  5658  5704 I jxcore-log: 
,10-20 08:09:15.558  5658  5704 I jxcore-log: # setup
10-20 08:09:15.558  5658  5704 I jxcore-log: 
,10-20 08:09:15.587  5658  5704 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-20 08:09:15.587  5658  5704 I jxcore-log: 
,10-20 08:09:15.594   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:16.082  5658  5704 I jxcore-log: 2016-10-20 12:09:16 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-20 08:09:16.082  5658  5704 I jxcore-log: 
,10-20 08:09:16.083  5658  5704 I jxcore-log: ok 60 stop caused us to fail
10-20 08:09:16.083  5658  5704 I jxcore-log: 
10-20 08:09:16.083  5658  5704 I jxcore-log: ok 61 We specifically failed on a stop before put
10-20 08:09:16.083  5658  5704 I jxcore-log: 
,10-20 08:09:16.101  5658  5704 I jxcore-log: # teardown
10-20 08:09:16.101  5658  5704 I jxcore-log: 
,10-20 08:09:16.138  5658  5704 I jxcore-log: # setup
10-20 08:09:16.138  5658  5704 I jxcore-log: 
,10-20 08:09:16.191  5658  5704 I jxcore-log: # #update - fail if stop is called
10-20 08:09:16.191  5658  5704 I jxcore-log: 
,10-20 08:09:16.253  5658  5704 I jxcore-log: ok 62 failed due to stop
10-20 08:09:16.253  5658  5704 I jxcore-log: 
,10-20 08:09:16.255  5658  5704 I jxcore-log: ok 63 failed due to stop
10-20 08:09:16.255  5658  5704 I jxcore-log: 
,10-20 08:09:16.265  5658  5704 I jxcore-log: # teardown
10-20 08:09:16.265  5658  5704 I jxcore-log: 
,10-20 08:09:16.322  5658  5704 I jxcore-log: # setup
10-20 08:09:16.322  5658  5704 I jxcore-log: 
,10-20 08:09:16.353  5658  5704 I jxcore-log: # #update - set seq for first time
10-20 08:09:16.353  5658  5704 I jxcore-log: 
,10-20 08:09:16.594   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:17.004  5658  5704 I jxcore-log: ok 64 should be equal
10-20 08:09:17.004  5658  5704 I jxcore-log: 
,10-20 08:09:17.027  5658  5704 I jxcore-log: # teardown
10-20 08:09:17.027  5658  5704 I jxcore-log: 
,10-20 08:09:17.538  5658  5704 I jxcore-log: # setup
10-20 08:09:17.538  5658  5704 I jxcore-log: 
,10-20 08:09:17.596   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:18.597   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-20 08:09:18.633  5658  5704 I jxcore-log: # #update - Fail on bad seq value
10-20 08:09:18.633  5658  5704 I jxcore-log: 
,10-20 08:09:19.541  5658  5704 I jxcore-log: 2016-10-20 12:09:19 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-20 08:09:19.541  5658  5704 I jxcore-log: 
10-20 08:09:19.543  5658  5704 I jxcore-log: ok 65 Expected bad seq error
10-20 08:09:19.543  5658  5704 I jxcore-log: 
,10-20 08:09:19.564  5658  5704 I jxcore-log: # teardown
10-20 08:09:19.564  5658  5704 I jxcore-log: 
,10-20 08:09:20.388  5658  5704 I jxcore-log: # setup
10-20 08:09:20.388  5658  5704 I jxcore-log: 
,10-20 08:09:21.904  5658  5704 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-20 08:09:21.904  5658  5704 I jxcore-log: 
,10-20 08:09:22.589  5658  5704 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-20 08:09:22.589  5658  5704 E jxcore-log: 
,10-20 08:09:22.590  5658  5704 E jxcore-log: Trace: 
10-20 08:09:22.590  5658  5704 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-20 08:09:22.590  5658  5704 E jxcore-log:     at addListener@events.js:140:1
10-20 08:09:22.590  5658  5704 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
10-20 08:09:22.590  5658  5704 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-20 08:09:22.590  5658  5704 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-20 08:09:22.590  5658  5704 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-20 08:09:22.590  5658  5704 E jxcore-log: 
,10-20 08:09:23.065  5658  5704 I jxcore-log: ok 66 Different promises
10-20 08:09:23.065  5658  5704 I jxcore-log: 
10-20 08:09:23.067  5658  5704 I jxcore-log: ok 67 Timer was cancelled
10-20 08:09:23.067  5658  5704 I jxcore-log: 
,10-20 08:09:23.273  5658  5704 I jxcore-log: ok 68 should be equal
10-20 08:09:23.273  5658  5704 I jxcore-log: 
,10-20 08:09:23.302  5658  5704 I jxcore-log: # teardown
10-20 08:09:23.302  5658  5704 I jxcore-log: 
,10-20 08:09:24.593  5658  5704 I jxcore-log: # setup
10-20 08:09:24.593  5658  5704 I jxcore-log: 
,10-20 08:09:25.077  5658  5704 I jxcore-log: # #update - do we wait for blocked update
10-20 08:09:25.077  5658  5704 I jxcore-log: 
,10-20 08:09:25.448  5658  5704 I jxcore-log: ok 69 One go and one blocked
10-20 08:09:25.448  5658  5704 I jxcore-log: 
,10-20 08:09:25.449  5658  5704 I jxcore-log: ok 70 All blocked
10-20 08:09:25.449  5658  5704 I jxcore-log: 
10-20 08:09:25.449  5658  5704 I jxcore-log: ok 71 Still blocked
10-20 08:09:25.449  5658  5704 I jxcore-log: 
,10-20 08:09:25.464  5658  5704 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-20 08:09:25.464  5658  5704 E jxcore-log: 
,10-20 08:09:25.465  5658  5704 E jxcore-log: Trace: 
10-20 08:09:25.465  5658  5704 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-20 08:09:25.465  5658  5704 E jxcore-log:     at addListener@events.js:140:1
10-20 08:09:25.465  5658  5704 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
10-20 08:09:25.465  5658  5704 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-20 08:09:25.465  5658  5704 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-20 08:09:25.465  5658  5704 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-20 08:09:25.465  5658  5704 E jxcore-log: 
,10-20 08:09:26.120  5658  5704 I jxcore-log: ok 72 should be equal
10-20 08:09:26.120  5658  5704 I jxcore-log: 
,10-20 08:09:26.155  5658  5704 I jxcore-log: # teardown
10-20 08:09:26.155  5658  5704 I jxcore-log: 
,10-20 08:09:27.048  5658  5704 I jxcore-log: # setup
10-20 08:09:27.048  5658  5704 I jxcore-log: 
,10-20 08:09:28.388  5658  5704 I jxcore-log: # #update - test that we wait long enough
10-20 08:09:28.388  5658  5704 I jxcore-log: 
,10-20 08:09:28.598   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:29.599   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:30.186  5658  5704 I jxcore-log: ok 73 We waited long enough
10-20 08:09:30.186  5658  5704 I jxcore-log: 
,10-20 08:09:30.374  5658  5704 I jxcore-log: ok 74 should be equal
10-20 08:09:30.374  5658  5704 I jxcore-log: 
,10-20 08:09:30.431  5658  5704 I jxcore-log: # teardown
10-20 08:09:30.431  5658  5704 I jxcore-log: 
,10-20 08:09:30.484  5658  5704 I jxcore-log: # setup
10-20 08:09:30.484  5658  5704 I jxcore-log: 
,10-20 08:09:30.600   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:31.602   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:31.735  5658  5704 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-20 08:09:31.735  5658  5704 I jxcore-log: 
,10-20 08:09:32.603   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:32.706  5658  5704 I jxcore-log: ok 75 Should have gotten same timer promise
10-20 08:09:32.706  5658  5704 I jxcore-log: 
,10-20 08:09:32.707  5658  5704 I jxcore-log: ok 76 Still same timer promise
10-20 08:09:32.707  5658  5704 I jxcore-log: 
,10-20 08:09:33.305  5658  5704 I jxcore-log: ok 77 We waited long enough
10-20 08:09:33.305  5658  5704 I jxcore-log: 
,10-20 08:09:33.447  5658  5704 I jxcore-log: ok 78 should be equal
10-20 08:09:33.447  5658  5704 I jxcore-log: 
,10-20 08:09:33.519  5658  5704 I jxcore-log: # teardown
10-20 08:09:33.519  5658  5704 I jxcore-log: 
,10-20 08:09:33.603   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-20 08:09:34.432  5658  5704 I jxcore-log: # setup
10-20 08:09:34.432  5658  5704 I jxcore-log: 
,10-20 08:09:35.981  5658  5704 I jxcore-log: # Coordinated seq test
10-20 08:09:35.981  5658  5704 I jxcore-log: 
,10-20 08:09:36.300  5658  5704 I jxcore-log: 2016-10-20 12:09:36 - DEBUG thaliWifiInfrastructure: 'listening 46777'
10-20 08:09:36.300  5658  5704 I jxcore-log: 
,10-20 08:09:38.666  5658  5704 I jxcore-log: ok 79 should be equal
10-20 08:09:38.666  5658  5704 I jxcore-log: 
,10-20 08:09:38.681  5658  5704 I jxcore-log: ok 80 should be equal
10-20 08:09:38.681  5658  5704 I jxcore-log: 
,10-20 08:09:38.693  5658  5704 I jxcore-log: # teardown
10-20 08:09:38.693  5658  5704 I jxcore-log: 
,10-20 08:09:46.528   928  3007 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-20 08:09:48.605   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:49.606   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:50.607   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:51.609   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:52.611   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:09:53.612   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-20 08:10:06.529   928  3007 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-20 08:10:13.613   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:10:14.614   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:10:15.616   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:10:16.617   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:10:17.619   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-20 08:10:18.146   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:10:18.620   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-20 08:10:24.205   928  3009 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-20 08:10:38.711  5658  5704 I jxcore-log: 2016-10-20 12:10:38 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-20 08:10:38.711  5658  5704 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-20 08:10:38.711  5658  5704 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-20 08:10:38.711  5658  5704 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-20 08:10:38.711  5658  5704 I jxcore-log:     at $9@timers.js:120:1
10-20 08:10:38.711  5658  5704 I jxcore-log: ''
10-20 08:10:38.711  5658  5704 I jxcore-log: 
,10-20 08:10:38.713  5658  5704 I jxcore-log: 2016-10-20 12:10:38 - DEBUG CoordinatedClient: 'test client failed'
10-20 08:10:38.713  5658  5704 I jxcore-log: 
,10-20 08:10:38.726  5658  5704 I jxcore-log: 2016-10-20 12:10:38 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-20 08:10:38.726  5658  5704 I jxcore-log: 
,10-20 08:10:38.731  5658  5704 I jxcore-log: 2016-10-20 12:10:38 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-20 08:10:38.731  5658  5704 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-20 08:10:38.731  5658  5704 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-20 08:10:38.731  5658  5704 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-20 08:10:38.731  5658  5704 I jxcore-log:     at $9@timers.js:120:1
10-20 08:10:38.731  5658  5704 I jxcore-log: ''
10-20 08:10:38.731  5658  5704 I jxcore-log: 
,10-20 08:10:38.732  5658  5704 I jxcore-log: 2016-10-20 12:10:38 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-20 08:10:38.732  5658  5704 I jxcore-log: 
,10-20 08:10:38.808   928  2972 W InputDispatcher: channel 'f7772a com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-20 08:10:38.808   928  2972 E InputDispatcher: channel 'f7772a com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-20 08:10:38.822   928  3451 I WindowState: WIN DEATH: Window{f7772a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-20 08:10:38.823   928  3451 W InputDispatcher: Attempted to unregister already unregistered input channel 'f7772a com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-20 08:10:38.823   928  4228 D GraphicsStats: Buffer count: 2
10-20 08:10:38.825   928  3008 D WifiService: Client connection lost with reason: 4
10-20 08:10:38.833   528   528 I Zygote  : Process 5658 exited cleanly (139)
,10-20 08:10:38.834   928  3186 I ActivityManager: Process com.test.thalitest (pid 5658) has died
,10-20 08:10:38.863   928  3186 I ActivityManager: Start proc 6010:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-20 08:10:39.196   928  3188 I WindowManager: Screenshot max retries 4 of Token{4696c ActivityRecord{207621f u0 com.test.thalitest/.MainActivity t2}} appWin=Window{b9d82a2 u0 Starting com.test.thalitest} drawState=4
,10-20 08:10:39.295  6010  6010 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-20 08:10:39.307  6008  6008 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-20 08:10:39.317  6010  6010 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-20 08:10:39.322  6010  6010 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9563-9565)
,10-20 08:10:39.322  6010  6010 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-20 08:10:39.322  6008  6008 D AndroidRuntime: CheckJNI is OFF
,10-20 08:10:39.330  6010  6010 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {662c4d8}
10-20 08:10:39.331  6010  6010 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-20 08:10:39.331  6010  6010 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-20 08:10:39.334  6010  6010 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-20 08:10:39.335  6010  6010 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-20 08:10:39.346  6010  6010 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-20 08:10:39.347  6008  6008 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-20 08:10:39.353  6010  6010 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-20 08:10:39.353  6010  6010 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-20 08:10:39.354  6010  6010 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-20 08:10:39.354  6010  6010 I Adreno  : Build Date                       : 12/06/15
10-20 08:10:39.354  6010  6010 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-20 08:10:39.354  6010  6010 I Adreno  : Local Branch                     : mybranch17112971
10-20 08:10:39.354  6010  6010 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-20 08:10:39.354  6010  6010 I Adreno  : Remote Branch                    : NONE
10-20 08:10:39.354  6010  6010 I Adreno  : Reconstruct Branch               : NOTHING
,10-20 08:10:39.370  6008  6008 I Radio-JNI: register_android_hardware_Radio DONE
,10-20 08:10:39.385   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@135cdab:true
,10-20 08:10:39.385  6008  6008 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-20 08:10:39.392   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-20 08:10:39.392   928   941 I ActivityManager: Killing 6010:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-20 08:10:39.533   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-20 08:10:39.534   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-20 08:10:39.536   928   941 E ActivityManager: Failure starting process com.test.thalitest
10-20 08:10:39.536   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-20 08:10:39.536   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:10:39.536   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:10:39.536   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-20 08:10:39.536   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-20 08:10:39.538   928   941 I ActivityManager:   Force finishing activity ActivityRecord{207621f u0 com.test.thalitest/.MainActivity t2}
10-20 08:10:39.539   928   951 I art     : Starting a blocking GC Explicit
,10-20 08:10:39.555   928  3866 W ActivityManager: Spurious death for ProcessRecord{16f279e 0:com.test.thalitest/u0a77}, curProc for 6010: null
,10-20 08:10:39.556   928   946 W WindowManager: Failed looking up window
10-20 08:10:39.556   928   946 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@b98e66d does not exist
10-20 08:10:39.556   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-20 08:10:39.556   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-20 08:10:39.556   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-20 08:10:39.556   928   946 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-20 08:10:39.556   928   946 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-20 08:10:39.556   928   946 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-20 08:10:39.556   928   946 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-20 08:10:39.556   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:10:39.556   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:10:39.556   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-20 08:10:39.556   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-20 08:10:39.636   928   951 I art     : Explicit concurrent mark sweep GC freed 78430(5MB) AllocSpace objects, 40(1192KB) LOS objects, 33% free, 29MB/43MB, paused 1.889ms total 96.884ms
,10-20 08:10:39.654   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-20 08:10:39.659  6008  6008 I art     : System.exit called, status: 0
,10-20 08:10:39.659  6008  6008 I AndroidRuntime: VM exiting with result code 0.
,10-20 08:10:39.663   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-20 08:10:39.691   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-20 08:10:39.695  5909  5909 D BluetoothMapAppObserver: onReceive
,10-20 08:10:39.695  3685  3685 I Keyboard.Facilitator: resetDictionaries() : en_US
10-20 08:10:39.695  5909  5909 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-20 08:10:39.703  3685  6048 I Keyboard.Facilitator.DecoderInitializer: run()
,10-20 08:10:39.704  3933  4168 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-20 08:10:39.705   928  2973 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-20 08:10:39.707  4879  4888 W art     : Suspending all threads took: 14.238ms
,10-20 08:10:39.715  3685  6048 I Decoder : createOrResetDecoder
,10-20 08:10:39.742  3434  6051 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-20 08:10:39.757   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-20 08:10:39.771  3819  3819 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-20 08:10:39.770   313   313 W kworker/3:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-20 08:10:39.776   313   313 W kworker/3:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-20 08:10:39.788  3857  3982 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-20 08:10:39.789  3615  3615 I ConfigService: onCreate
,10-20 08:10:39.786   313   313 W kworker/3:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-20 08:10:39.805   928  4227 I ActivityManager: Start proc 6054:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-20 08:10:39.806  3857  3982 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-20 08:10:39.806  3857  3982 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3857
10-20 08:10:39.806  3857  3982 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:10:39.806  3857  3982 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-20 08:10:39.811   928  3186 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-20 08:10:39.812   928  6064 E DropBoxManagerService: Can't write: system_app_crash
10-20 08:10:39.812   928  6064 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-20 08:10:39.812   928  6064 E DropBoxManagerService: 	... 5 more
10-20 08:10:39.815  3857  3982 I Process : Sending signal. PID: 3857 SIG: 9
,10-20 08:10:39.818  3615  3615 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,10-20 08:10:39.819  3615  3615 D AndroidRuntime: Shutting down VM
,10-20 08:10:39.820  3615  3615 E AndroidRuntime: FATAL EXCEPTION: main
10-20 08:10:39.820  3615  3615 E AndroidRuntime: Process: com.google.process.gapps, PID: 3615
10-20 08:10:39.820  3615  3615 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-20 08:10:39.820  3615  3615 E AndroidRuntime: 	... 8 more
10-20 08:10:39.823  3615  3615 I Process : Sending signal. PID: 3615 SIG: 9
10-20 08:10:39.824   380   380 E lowmemorykiller: Error writing /proc/3615/oom_score_adj; errno=22
10-20 08:10:39.825   928  6068 E DropBoxManagerService: Can't write: system_app_crash
10-20 08:10:39.825   928  6068 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: Caused by: android.system.ErrnoException: op,en failed: EROFS (Read-only file system)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-20 08:10:39.825   928  6068 E DropBoxManagerService: 	... 5 more
10-20 08:10:39.830   380   380 E lowmemorykiller: Error writing /proc/3615/oom_score_adj; errno=22
10-20 08:10:39.830   928   941 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
10-20 08:10:39.831   928   941 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
10-20 08:10:39.831   928   941 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-20 08:10:39.831   928   941 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-20 08:10:39.835  3434  6051 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-20 08:10:39.841  3434  6051 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-20 08:10:39.841  3434  6051 E AndroidRuntime: Process: android.process.acore, PID: 3434
10-20 08:10:39.841  3434  6051 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-20 08:10:39.841  3434  6051 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-20 08:10:39.862   928  3008 D WifiService: Client connection lost with reason: 4
,10-20 08:10:39.863   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
10-20 08:10:39.864   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: Failed to get gconfig value
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: java.lang.NullPointerException: Attempt to invoke interface method 'java.lang.String com.google.android.gms.config.ConfigApi$Value.getAsString(java.lang.String)' on a null object reference
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at com.android.inputmethod.latin.GconfigFlagGetter.getInt(GconfigFlagGetter.java:83)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at com.android.inputmethod.latin.DecoderFlagGetter.getFlagValues(DecoderFlagGetter.java:67)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator.resetDecoderFlagValues(Delight3DictionaryFacilitator.java:94)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator.-wrap0(Delight3DictionaryFacilitator.java)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator$DecoderInitializer.run(Delight3DictionaryFacilitator.java:877)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at com.android.inputmethod.latin.utils.ExecutorUtils$RunnableChain.run(ExecutorUtils.java:148)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
10-20 08:10:39.864  3685  6048 W DecoderFlagGetter: 	at java.lang.Thread.run(Thread.java:818)
10-20 08:10:39.864   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
10-20 08:10:39.864  3685  6048 I Keyboard.Facilitator.MainLanguageModelLoader: run()
10-20 08:10:39.864   928   941 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 31000ms
,10-20 08:10:39.875   928   941 I ActivityManager: Start proc 6069:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,10-20 08:10:39.876   928  3986 W ActivityManager: Spurious death for ProcessRecord{3cc686 6069:com.google.process.gapps/u0a12}, curProc for 3615: null
,10-20 08:10:39.886  3434  6051 I Process : Sending signal. PID: 3434 SIG: 9
,10-20 08:10:39.886   928  2972 W InputDispatcher: channel '486f5fc com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-20 08:10:39.886   928  2972 E InputDispatcher: channel '486f5fc com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-20 08:10:39.889   928  3186 D GraphicsStats: Buffer count: 1
10-20 08:10:39.889   928  3188 I WindowState: WIN DEATH: Window{486f5fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING}
,10-20 08:10:39.889   928  3188 W InputDispatcher: Attempted to unregister already unregistered input channel '486f5fc com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-20 08:10:39.910   928  4228 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3857) has died
,10-20 08:10:39.911   928  4228 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40953ms
,10-20 08:10:39.920   928   946 E WindowState: getStack: Window{486f5fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{896cb17 token=Token{202e396 ActivityRecord{9ec22b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowAnimator.shouldForceHide:218 com.android.server.wm.WindowAnimator.updateWindowsLocked:266 
,10-20 08:10:39.920   928   946 E WindowState: getStack: Window{486f5fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{896cb17 token=Token{202e396 ActivityRecord{9ec22b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:287 com.android.server.wm.WindowAnimator.updateWindowsLocked:269 com.android.server.wm.WindowAnimator.animateLocked:678 
10-20 08:10:39.920   928   946 E WindowState: getStack: Window{486f5fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{896cb17 token=Token{202e396 ActivityRecord{9ec22b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1062 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1462 
10-20 08:10:39.921   928   946 E WindowState: getStack: Window{486f5fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{896cb17 token=Token{202e396 ActivityRecord{9ec22b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.getDisplayId:852 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1378 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
10-20 08:10:39.921   928   946 E WindowState: getStack: Window{486f5fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{896cb17 token=Token{202e396 ActivityRecord{9ec22b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1274 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:1464 
10-20 08:10:39.921   928   946 E WindowState: getStack: Window{486f5fc u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL EXITING} couldn't find task for AppWindowToken{896cb17 token=Token{202e396 ActivityRecord{9ec22b1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL t1}}} Callers=com.android.server.wm.WindowState.getDisplayContent:847 com.android.server.wm.WindowState.isDefaultDisplay:1380 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1285 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1445 
,10-20 08:10:39.962   928   939 I ActivityManager: Process android.process.acore (pid 3434) has died
10-20 08:10:39.962   928   939 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-20 08:10:40.180   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
