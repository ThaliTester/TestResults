#### Test 87899936285db68_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-07 05:40:02.557   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-07 05:40:02.557   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,--------- beginning of system
10-07 05:40:03.305   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-07 05:40:03.511  5634  5634 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-07 05:40:03.517  5634  5634 D AndroidRuntime: CheckJNI is OFF
10-07 05:40:03.547  5634  5634 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-07 05:40:03.582  5634  5634 I Radio-JNI: register_android_hardware_Radio DONE
10-07 05:40:03.597  5634  5634 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-07 05:40:03.602   927  3366 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-07 05:40:03.644   927  3366 I ActivityManager: Start proc 5643:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-07 05:40:03.657  5634  5634 D AndroidRuntime: Shutting down VM
,10-07 05:40:03.990   927  3686 I WindowManager: Screenshot max retries 4 of Token{e4151ee ActivityRecord{b707369 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{3ca26a1 u0 Starting com.test.thalitest} drawState=4
,10-07 05:40:04.058  5643  5643 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-07 05:40:04.093  5643  5643 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-07 05:40:04.116  5643  5643 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 578-597)
,10-07 05:40:04.116  5643  5643 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-07 05:40:04.133  5643  5643 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e0ece41}
,10-07 05:40:04.134  5643  5643 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-07 05:40:04.134  5643  5643 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-07 05:40:04.137  5643  5643 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-07 05:40:04.138  5643  5643 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-07 05:40:04.169  5643  5643 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-07 05:40:04.178  5643  5643 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-07 05:40:04.178  5643  5643 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-07 05:40:04.178  5643  5643 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-07 05:40:04.178  5643  5643 I Adreno  : Build Date                       : 12/06/15
10-07 05:40:04.178  5643  5643 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-07 05:40:04.178  5643  5643 I Adreno  : Local Branch                     : mybranch17112971
10-07 05:40:04.178  5643  5643 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-07 05:40:04.178  5643  5643 I Adreno  : Remote Branch                    : NONE
10-07 05:40:04.178  5643  5643 I Adreno  : Reconstruct Branch               : NOTHING
,10-07 05:40:04.209   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f8ec54c:true
,10-07 05:40:04.235   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24514]" dev="sockfs" ino=24514 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:04.235   406   406 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[24514]" dev="sockfs" ino=24514 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:04.247  5643  5643 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-07 05:40:04.255  5643  5643 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-07 05:40:04.279  3404  3404 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31355]" dev="sockfs" ino=31355 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:04.280  5643  5680 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-07 05:40:04.279  3404  3404 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31355]" dev="sockfs" ino=31355 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:04.282  3118  3118 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[24526]" dev="sockfs" ino=24526 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:04.282  3118  3118 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[24526]" dev="sockfs" ino=24526 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:04.286  5643  5667 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-07 05:40:04.304  5643  5680 I OpenGLRenderer: Initialized EGL, version 1.4
,10-07 05:40:04.372   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +381ms (total +758ms)
,10-07 05:40:04.416  5643  5643 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5643
,10-07 05:40:04.510  5643  5643 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-07 05:40:04.549   927  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 05:40:04.680  5643  5682 D jxcore_app_log: JniHelper::setJavaVM(0xf55fc000), pthread_self() = -580912848
,10-07 05:40:04.684  5643  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-07 05:40:04.684  5643  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-07 05:40:04.684  5643  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-07 05:40:04.684  5643  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-07 05:40:04.684  5643  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-07 05:40:04.684  5643  5682 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aab907e added. We now have 1 listener(s)
,10-07 05:40:04.686  5643  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-07 05:40:04.687  5643  5682 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:40:04.687  5643  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 05:40:04.688  5643  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-07 05:40:04.690  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-07 05:40:04.691  5643  5682 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df3d8f5 added. We now have 1 listener(s)
10-07 05:40:04.691  5643  5682 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:40:04.698   927  2932 D WifiService: New client listening to asynchronous messages
,10-07 05:40:04.698  5643  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 05:40:04.698  5643  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-07 05:40:04.698  5643  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-07 05:40:04.698  5643  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-07 05:40:04.698  5643  5682 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-07 05:40:04.701  5643  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:04.701  5643  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-07 05:40:04.706  5643  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:04.706  5643  5682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:04.706  5643  5682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-07 05:40:04.706  5643  5682 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:40:04.707  5643  5682 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-07 05:40:04.709  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:04.712  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:04.735  5643  5643 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-07 05:40:05.007  5643  5689 W jxcore-log: Initializing JXcore engine
10-07 05:40:05.007  5643  5689 W jxcore-log: JXcore engine is ready
,10-07 05:40:05.032  5689  5689 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12559 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
10-07 05:40:05.032  5689  5689 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16492]" dev="sockfs" ino=16492 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-07 05:40:05.032  5689  5689 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-07 05:40:05.032  5689  5689 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30317]" dev="sockfs" ino=30317 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-07 05:40:05.042  5643  5689 W jxcore-log: Starting JXcore engine
,10-07 05:40:05.097  5643  5689 W jxcore-log: Platform android
10-07 05:40:05.097  5643  5689 W jxcore-log: 
,10-07 05:40:05.097  5643  5689 W jxcore-log: Process ARCH arm
10-07 05:40:05.097  5643  5689 W jxcore-log: 
,10-07 05:40:05.190  5643  5689 I jxcore-log: JXcore Cordova bridge is ready!
10-07 05:40:05.190  5643  5689 I jxcore-log: 
,10-07 05:40:05.191  5643  5689 W jxcore-log: JXcore engine is started
,10-07 05:40:05.199  5643  5682 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-07 05:40:05.209  5643  5643 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-07 05:40:06.335   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 05:40:12.559   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:13.560   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:14.561   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:14.853  5643  5689 I jxcore-log: 2016-10-07 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-07 05:40:14.853  5643  5689 I jxcore-log: 
,10-07 05:40:14.855  5643  5689 I jxcore-log: 2016-10-07 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-07 05:40:14.855  5643  5689 I jxcore-log: 
,10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:14.859  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 05:40:14.863  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 05:40:14.865  5643  5689 I jxcore-log: 2016-10-07 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-07 05:40:14.865  5643  5689 I jxcore-log: 
,10-07 05:40:14.867  5643  5689 I jxcore-log: 2016-10-07 09:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-07 05:40:14.867  5643  5689 I jxcore-log: 
,10-07 05:40:15.115  5643  5689 I jxcore-log: 2016-10-07 09:40:15 - DEBUG UnitTest_app: 'Running unit tests'
10-07 05:40:15.115  5643  5689 I jxcore-log: 
,10-07 05:40:15.116  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 05:40:15.116  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8be7fbe added. We now have 2 listener(s)
10-07 05:40:15.117  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:40:15.117  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 05:40:15.117  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 05:40:15.117  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:40:15.117  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efc781f added. We now have 2 listener(s)
10-07 05:40:15.117  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:40:15.118  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 05:40:15.119  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:15.122  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 05:40:15.123  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:15.123  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 05:40:15.124  5643  5689 D executeNativeTests: Running unit tests
,10-07 05:40:15.129  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:15.135  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:15.161  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 05:40:15.161  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 added. We now have 3 listener(s)
,10-07 05:40:15.161  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 05:40:15.161  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 05:40:15.161  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:40:15.161  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 05:40:15.162  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a added. We now have 3 listener(s)
10-07 05:40:15.162  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:40:15.162  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 05:40:15.163  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:15.166  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:15.166  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:15.167  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:40:15.168  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-07 05:40:15.168  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-07 05:40:15.168  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 05:40:15.168  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 05:40:15.169  5643  5689 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-07 05:40:15.169  5643  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-07 05:40:15.169  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 05:40:15.169  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 05:40:15.169  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 05:40:15.169  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 05:40:15.169  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:15.169  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:15.169  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:15.170  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:15.170  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:40:15.170  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:40:15.170  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:15.170  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:40:15.170  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 removed from the list
10-07 05:40:15.170  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:15.170  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a removed from the list
10-07 05:40:15.172  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:15.179  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:15.179  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:15.179  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:15.180  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:40:15.180  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:15.180  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:15.180  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:15.180  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:15.180  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
,10-07 05:40:15.181  5643  5689 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-07 05:40:15.182  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:15.182  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:15.182  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:15.182  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:15.182  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:15.182  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:15.182  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:15.182  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:15.182  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:15.182  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:15.182  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:15.182  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:15.182  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:15.182  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:40:15.182  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:15.183  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:15.183  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:15.183  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:15.183  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-07 05:40:15.185  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-07 05:40:15.186  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:15.186  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:15.186  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:15.186  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:15.186  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:15.186  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:15.186  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:15.186  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:15.186  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:15.186  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:15.186  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:15.187  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:15.187  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:15.187  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:15.187  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:15.187  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:15.187  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:15.187  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:15.187  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:15.187  5643  5689 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-07 05:40:15.188  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:15.190  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:15.191  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:15.191  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:40:15.191  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:40:15.191  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 05:40:15.192  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 05:40:15.192  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:15.192  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 05:40:15.193  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:15.195  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:15.196  5643  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 05:40:15.196  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 05:40:15.198  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 05:40:15.199  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 05:40:15.199  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-07 05:40:15.200  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-07 05:40:15.201  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-07 05:40:15.201  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 05:40:15.201  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 05:40:15.201  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 05:40:15.202  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 05:40:15.202  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 05:40:15.202  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:40:15.204  4561  4579 D BtGatt.GattService: registerClient() - UUID=b26f5cd4-b208-4733-b7dd-fd9fc47f1d83
10-07 05:40:15.205  4561  4633 D BtGatt.GattService: onClientRegistered() - UUID=b26f5cd4-b208-4733-b7dd-fd9fc47f1d83, clientIf=5
10-07 05:40:15.206  5643  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 05:40:15.206  4561  4580 D BtGatt.GattService: start scan with filters
10-07 05:40:15.210  4561  4638 D BtGatt.ScanManager: handling starting scan
10-07 05:40:15.210  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 05:40:15.210  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 05:40:15.210  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:40:15.210  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 05:40:15.210  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 05:40:15.210  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 05:40:15.210  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 05:40:15.211  4561  4638 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:40:15.211  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:40:15.212  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 05:40:15.212  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:40:15.212  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 05:40:15.213  5643  5689 I io.jxcore.node.ConnectionHelper: start: OK
10-07 05:40:15.218  4561  4633 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 05:40:15.218  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:15.219  4561  4638 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 05:40:15.225  4561  4633 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 05:40:15.225  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:15.225  4561  4638 D BtGatt.ScanManager: Starting BLE batch scan
10-07 05:40:15.225  4561  4638 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 05:40:15.235  4561  4633 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 05:40:15.235  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:15.241  4561  4633 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 05:40:15.241  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:40:15.410   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 05:40:15.562   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:15.714  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-07 05:40:15.715  5643  5643 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:40:15.715  5643  5643 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 05:40:16.563   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:17.564   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-07 05:40:20.218  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 05:40:20.218  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:20.218  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 05:40:20.218  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:20.218  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-07 05:40:20.218  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:20.218  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 05:40:20.219  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-07 05:40:20.219  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 05:40:20.219  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 05:40:20.219  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-07 05:40:20.220  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 05:40:20.221  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:40:20.221  4561  4803 D BtGatt.GattService: stopScan() - queue size =1
10-07 05:40:20.223  4561  4783 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 05:40:20.226  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 05:40:20.226  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 05:40:20.226  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 05:40:20.226  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:40:20.227  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-07 05:40:20.227  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 05:40:20.227  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 05:40:20.227  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 05:40:20.230  4561  4561 D BtGatt.ScanManager: awakened up at time 236711
,10-07 05:40:20.230  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:40:20.231  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 05:40:20.231  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 05:40:20.231  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 05:40:20.232  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 05:40:20.233  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:40:20.236  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:20.236  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-07 05:40:20.236  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:20.236  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:40:20.236  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:20.236  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:40:20.236  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:20.236  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:20.236  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 05:40:20.236  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:20.237  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:20.237  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:20.237  4561  4633 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 05:40:20.237  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:20.238  4561  4638 D BtGatt.ScanManager: stopping BLe Batch
,10-07 05:40:20.248  4561  4633 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 05:40:20.248  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:40:20.249  4561  4638 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 05:40:20.272  4561  4633 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-07 05:40:20.273  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:20.273  4561  4633 D BtGatt.GattService: current time is 236754244149
10-07 05:40:20.274  4561  4633 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -79, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -80, 72, 104, -106, -124, 109, 1, -128, -91, 74, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -78, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-07 05:40:20.276  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-07 05:40:20.277  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-07 05:40:20.277  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
,10-07 05:40:20.277  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-07 05:40:20.278  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-07 05:40:20.278  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-07 05:40:20.278  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-07 05:40:20.737  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 05:40:21.464   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 05:40:22.565   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:23.567   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:24.568   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:25.239  5643  5689 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-07 05:40:25.244  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:25.256  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:25.259  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:25.260  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:40:25.260  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 05:40:25.260  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 05:40:25.260  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 05:40:25.260  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:25.260  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 05:40:25.265  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:25.266  5643  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 05:40:25.267  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 05:40:25.270  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:25.273  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 05:40:25.274  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 05:40:25.274  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 05:40:25.280  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-07 05:40:25.280  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 05:40:25.280  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 05:40:25.280  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 05:40:25.281  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 05:40:25.281  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:40:25.283  4561  4803 D BtGatt.GattService: registerClient() - UUID=aa9bd094-b2ac-46d6-99a4-a3e1dcc6624e
,10-07 05:40:25.284  4561  4633 D BtGatt.GattService: onClientRegistered() - UUID=aa9bd094-b2ac-46d6-99a4-a3e1dcc6624e, clientIf=5
10-07 05:40:25.284  5643  5653 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 05:40:25.285  4561  4783 D BtGatt.GattService: start scan with filters
,10-07 05:40:25.288  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 05:40:25.288  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 05:40:25.288  4561  4638 D BtGatt.ScanManager: handling starting scan
,10-07 05:40:25.288  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:40:25.288  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 05:40:25.288  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 05:40:25.288  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 05:40:25.288  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 05:40:25.292  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:40:25.292  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 05:40:25.292  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:40:25.294  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 05:40:25.295  4561  4633 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 05:40:25.296  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.296  4561  4638 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-07 05:40:25.297  5643  5689 I io.jxcore.node.ConnectionHelper: start: OK
,10-07 05:40:25.301  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:25.301  5643  5689 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-07 05:40:25.301  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:25.301  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 05:40:25.301  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:25.301  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 05:40:25.301  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:25.301  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 05:40:25.301  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 05:40:25.301  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 05:40:25.301  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 05:40:25.301  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 05:40:25.301  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 05:40:25.302  4561  4633 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 05:40:25.302  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.302  4561  4638 D BtGatt.ScanManager: Starting BLE batch scan
10-07 05:40:25.302  4561  4638 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-07 05:40:25.306  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:40:25.307  4561  4579 D BtGatt.GattService: stopScan() - queue size =1
10-07 05:40:25.308  4561  4783 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 05:40:25.309  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 05:40:25.309  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 05:40:25.309  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 05:40:25.309  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:40:25.309  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 05:40:25.309  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 05:40:25.309  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 05:40:25.309  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 05:40:25.310  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:40:25.310  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-07 05:40:25.311  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 05:40:25.311  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 05:40:25.311  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 05:40:25.311  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:40:25.312  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 05:40:25.312  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:40:25.312  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:25.312  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-07 05:40:25.312  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:40:25.312  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 05:40:25.312  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:25.313  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:25.313  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:25.313  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:25.313  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:25.313  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:25.313  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:25.313  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:25.315  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:25.315  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-07 05:40:25.315  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:25.315  4561  4633 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 05:40:25.315  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.315  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:25.316  5643  5689 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-07 05:40:25.318  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:25.321  4561  4633 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 05:40:25.321  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:25.322  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 05:40:25.324  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:25.324  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 05:40:25.324  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:40:25.324  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 05:40:25.324  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 05:40:25.324  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:25.324  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-07 05:40:25.327  5643  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 05:40:25.328  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 05:40:25.328  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:25.329  4561  4633 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 05:40:25.329  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.330  4561  4638 D BtGatt.ScanManager: stopping BLe Batch
,10-07 05:40:25.332  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:25.333  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 05:40:25.333  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 05:40:25.334  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-07 05:40:25.336  4561  4633 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 05:40:25.336  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.336  4561  4638 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 05:40:25.336  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 05:40:25.336  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-07 05:40:25.337  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 05:40:25.337  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 05:40:25.337  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 05:40:25.337  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:40:25.339  4561  4579 D BtGatt.GattService: registerClient() - UUID=0b10a05a-26b9-4ac7-8cdb-3736dd050eee
10-07 05:40:25.339  4561  4633 D BtGatt.GattService: onClientRegistered() - UUID=0b10a05a-26b9-4ac7-8cdb-3736dd050eee, clientIf=5
10-07 05:40:25.340  5643  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-07 05:40:25.340  4561  4783 D BtGatt.GattService: start scan with filters
,10-07 05:40:25.343  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-07 05:40:25.343  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 05:40:25.343  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:40:25.343  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 05:40:25.343  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 05:40:25.343  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 05:40:25.343  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 05:40:25.346  4561  4633 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
10-07 05:40:25.346  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:40:25.346  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.346  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 05:40:25.346  4561  4633 D BtGatt.GattService: current time is 241827667155
10-07 05:40:25.346  4561  4633 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -87, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-07 05:40:25.347  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-07 05:40:25.347  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 05:40:25.347  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 05:40:25.348  4561  4638 D BtGatt.ScanManager: handling starting scan
,10-07 05:40:25.351  5643  5689 I io.jxcore.node.ConnectionHelper: start: OK
,10-07 05:40:25.353  4561  4633 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-07 05:40:25.353  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:25.353  4561  4638 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 05:40:25.358  4561  4633 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 05:40:25.358  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:40:25.358  4561  4638 D BtGatt.ScanManager: Starting BLE batch scan
10-07 05:40:25.358  4561  4638 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-07 05:40:25.366  4561  4633 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-07 05:40:25.366  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:40:25.371  4561  4633 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-07 05:40:25.371  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:40:25.569   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:25.848  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-07 05:40:25.848  5643  5643 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:40:25.848  5643  5643 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 05:40:26.570   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:27.507   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-07 05:40:27.519   927  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-07 05:40:27.571   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-07 05:40:30.351  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 05:40:30.352  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:30.352  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-07 05:40:30.352  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:40:30.352  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 05:40:30.352  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 05:40:30.352  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 05:40:30.353  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 05:40:30.353  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-07 05:40:30.353  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 05:40:30.353  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-07 05:40:30.353  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 05:40:30.356  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:40:30.357  4561  4783 D BtGatt.GattService: stopScan() - queue size =1
10-07 05:40:30.360  4561  4803 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 05:40:30.360  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 05:40:30.360  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 05:40:30.361  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 05:40:30.361  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:40:30.361  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 05:40:30.361  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 05:40:30.361  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 05:40:30.361  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 05:40:30.364  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:40:30.364  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 05:40:30.364  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 05:40:30.364  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 05:40:30.365  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 05:40:30.366  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:40:30.367  4561  4561 D BtGatt.ScanManager: awakened up at time 246848
,10-07 05:40:30.369  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:40:30.369  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:40:30.369  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 05:40:30.372  4561  4633 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 05:40:30.372  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:30.373  4561  4638 D BtGatt.ScanManager: stopping BLe Batch
,10-07 05:40:30.379  4561  4633 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-07 05:40:30.379  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:30.379  4561  4638 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 05:40:30.397  4561  4633 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-07 05:40:30.397  4561  4633 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:40:30.397  4561  4633 D BtGatt.GattService: current time is 246878526617
10-07 05:40:30.397  4561  4633 D BtGatt.GattService: Batch record : [-80, 72, 104, -106, -124, 109, 1, -128, -87, 75, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 51, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -85, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -81, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -82, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -81, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-07 05:40:30.398  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 11, 0]
10-07 05:40:30.398  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-07 05:40:30.398  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-07 05:40:30.398  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-07 05:40:30.398  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-07 05:40:30.398  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-07 05:40:30.399  4561  4633 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-07 05:40:30.528   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-07 05:40:30.531   927  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-07 05:40:30.870  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 05:40:30.871  5643  5643 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:30.871  5643  5643 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-07 05:40:35.370  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 05:40:35.371  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.371  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 05:40:35.371  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.371  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.372  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:40:35.372  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 05:40:35.372  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.372  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.372  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
,10-07 05:40:35.373  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.373  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.374  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.374  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.378  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.378  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.379  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:40:35.379  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
,10-07 05:40:35.380  5643  5689 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-07 05:40:35.382  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 05:40:35.382  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.382  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:35.383  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 05:40:35.383  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.383  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.383  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:35.383  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.383  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.384  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
,10-07 05:40:35.384  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.384  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.384  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.384  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.384  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.388  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.388  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.388  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.388  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.391  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-07 05:40:35.391  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:35.391  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.392  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:35.392  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.392  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.393  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.393  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 05:40:35.393  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.393  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.393  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.393  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.393  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.393  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.393  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.393  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.395  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.395  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-07 05:40:35.396  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.396  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.397  5643  5689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-07 05:40:35.397  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:35.397  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.397  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 05:40:35.397  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.398  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.398  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.398  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:35.398  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.398  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.398  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.398  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 05:40:35.398  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.398  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.398  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.398  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.400  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.400  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.400  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.401  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
,10-07 05:40:35.402  5643  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-07 05:40:35.402  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:35.402  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.402  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:35.402  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.402  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.403  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.403  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:35.403  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.403  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.403  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.403  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.403  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.403  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.403  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.403  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.405  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 05:40:35.405  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.405  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:40:35.406  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.407  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-07 05:40:35.407  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-07 05:40:35.407  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 05:40:35.407  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-07 05:40:35.407  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 05:40:35.408  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 05:40:35.408  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-07 05:40:35.408  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 05:40:35.408  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-07 05:40:35.408  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:35.408  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 05:40:35.408  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:35.408  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.409  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.409  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.409  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:35.410  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
,10-07 05:40:35.410  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.411  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.411  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.411  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.411  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.412  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.412  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.416  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.416  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.416  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:40:35.416  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.417  5643  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 05:40:35.417  5643  5689 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-07 05:40:35.417  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-07 05:40:35.422  5643  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-07 05:40:35.422  5643  5689 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-07 05:40:35.422  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-07 05:40:35.422  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,10-07 05:40:35.422  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-07 05:40:35.422  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-07 05:40:35.423  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-07 05:40:35.424  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-07 05:40:35.425  5643  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-07 05:40:35.425  5643  5689 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 05:40:35.425  5643  5689 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-07 05:40:35.425  5643  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 05:40:35.426  5643  5689 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 05:40:35.426  5643  5689 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-07 05:40:35.426  5643  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 05:40:35.426  5643  5689 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-07 05:40:35.426  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-07 05:40:35.432  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,10-07 05:40:35.433  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,10-07 05:40:35.434  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-07 05:40:35.434  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-07 05:40:35.434  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-07 05:40:35.435  5643  5689 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-07 05:40:35.435  5643  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-07 05:40:35.435  5643  5689 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-07 05:40:35.435  5643  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-07 05:40:35.435  5643  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-07 05:40:35.435  5643  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-07 05:40:35.435  5643  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-07 05:40:35.436  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 05:40:35.436  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.436  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:35.436  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.436  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.437  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.437  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 05:40:35.437  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-07 05:40:35.438  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.438  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.438  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.438  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.438  5643  5690 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,10-07 05:40:35.438  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.438  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.438  5643  5690 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 05:40:35.438  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.438  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.438  5643  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
,10-07 05:40:35.439  5643  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-07 05:40:35.439  5643  5691 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-07 05:40:35.440  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.440  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.440  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.440  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.441  5643  5689 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-07 05:40:35.442  4579  4579 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31378]" dev="sockfs" ino=31378 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 05:40:35.442  4579  4579 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31378]" dev="sockfs" ino=31378 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-07 05:40:35.443  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:35.443  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-07 05:40:35.443  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 05:40:35.443  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.443  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.443  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.443  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:35.443  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.443  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.443  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.443  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.443  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:40:35.443  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.444  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.444  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.444  5643  5690 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-07 05:40:35.444  5643  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-07 05:40:35.444  5643  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-07 05:40:35.445  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.445  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.445  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.445  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.446  5643  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-07 05:40:35.446  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:35.447  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.447  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:35.447  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 05:40:35.447  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.447  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.447  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:35.447  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.447  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.447  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
,10-07 05:40:35.447  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.447  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.447  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.447  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.447  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.450  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.450  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.450  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.450  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.451  5643  5689 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-07 05:40:35.451  5643  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,10-07 05:40:35.451  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 05:40:35.451  5643  5689 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-07 05:40:35.451  5643  5689 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-07 05:40:35.451  5643  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-07 05:40:35.451  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-07 05:40:35.452  5643  5689 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,10-07 05:40:35.452  5643  5689 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-07 05:40:35.452  5643  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,10-07 05:40:35.452  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-07 05:40:35.452  5643  5689 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-07 05:40:35.452  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:35.452  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:35.452  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:35.452  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.452  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.452  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.452  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 05:40:35.452  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.452  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.452  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.453  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.453  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.453  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:35.453  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.453  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.454  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:35.454  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:35.454  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.454  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.454  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:35.454  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.454  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:35.455  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:35.455  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:35.455  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:35.455  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:35.455  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:35.455  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:35.455  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:37.572   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:38.573   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:39.574   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:40.456  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:40:40.456  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.456  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:40.456  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.456  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.457  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:40.457  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
,10-07 05:40:40.457  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:40.457  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:40.457  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 05:40:40.458  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:40.458  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.458  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.458  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:40.458  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
,10-07 05:40:40.458  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.458  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.459  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:40.459  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.459  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:40.459  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.459  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:40.464  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:40.464  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:40.464  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.465  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.468  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-07 05:40:40.475  4803  4803 W Binder_5: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32843]" dev="sockfs" ino=32843 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:40.475  4803  4803 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32843]" dev="sockfs" ino=32843 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-07 05:40:40.469  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:40.471  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-07 05:40:40.474  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-07 05:40:40.474  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-07 05:40:40.474  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-07 05:40:40.474  5643  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-07 05:40:40.474  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-07 05:40:40.475  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 05:40:40.475  5643  5643 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-07 05:40:40.475  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:40.475  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-07 05:40:40.475  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-07 05:40:40.475  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-07 05:40:40.475  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.475  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-07 05:40:40.475  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-07 05:40:40.476  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:40.476  5643  5643 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-07 05:40:40.476  5643  5692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 05:40:40.476  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.476  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 05:40:40.476  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-07 05:40:40.476  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 05:40:40.476  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.476  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.477  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:40:40.477  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.477  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:40:40.477  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:40.477  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:40.477  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:40.477  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:40:40.477  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:40.477  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:40:40.477  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:40:40.478  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.478  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-07 05:40:40.478  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:40.478  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.478  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.478  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:40.478  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.478  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.478  5643  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-07 05:40:40.478  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.478  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:40.478  5643  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-07 05:40:40.478  5643  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-07 05:40:40.479  5643  5643 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-07 05:40:40.479  5643  5643 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:40.479  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:40.480  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:40.480  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.480  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.481  5643  5689 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-07 05:40:40.481  5643  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-07 05:40:40.481  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-07 05:40:40.481  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 05:40:40.481  5643  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-07 05:40:40.482  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:40.482  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:40.482  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:40.482  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:40.482  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.482  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.482  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:40.482  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:40.482  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.483  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.483  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 05:40:40.483  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.483  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.484  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.484  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.485  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:40.485  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:40.485  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.485  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.491  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:40.491  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:40.491  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:40.491  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:40.491  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.491  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:40.491  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:40.491  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:40.491  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.491  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.491  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:40.491  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.491  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.491  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.492  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.494  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:40.494  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:40.494  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.494  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
,10-07 05:40:40.495  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:40:40.495  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:40:40.495  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:40:40.496  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:40:40.496  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.496  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.496  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:40:40.496  5643  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7ea1a5 not in the list
10-07 05:40:40.496  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.496  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.496  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:40.496  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.496  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:40:40.496  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:40.496  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:40.497  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:40:40.497  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:40:40.497  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:40:40.497  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc9497a not in the list
10-07 05:40:40.498  5643  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-07 05:40:40.498  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-07 05:40:40.498  5643  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-07 05:40:40.499  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-07 05:40:40.499  5643  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-07 05:40:40.499  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-07 05:40:40.501  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-07 05:40:40.501  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-07 05:40:40.502  5643  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-07 05:40:40.502  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-07 05:40:40.502  5643  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-07 05:40:40.502  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-07 05:40:40.502  5643  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-07 05:40:40.502  5643  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-07 05:40:40.503  5643  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-07 05:40:40.503  5643  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-07 05:40:40.503  5643  5689 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-07 05:40:40.503  5643  5689 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,10-07 05:40:40.503  5643  5689 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-07 05:40:40.504  5643  5689 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-07 05:40:40.504  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:40:40.504  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39e6bcc added. We now have 3 listener(s)
10-07 05:40:40.504  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:40:40.506  5643  5689 D BluetoothAdapter: enable(): BT is already enabled..!
10-07 05:40:40.507   927  3846 D WifiService: setWifiEnabled: true pid=5643, uid=10077
10-07 05:40:40.507   927  3846 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 05:40:40.569  4561  4769 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
10-07 05:40:40.569  4561  4780 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-07 05:40:40.575   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:40.977  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 05:40:41.575   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:42.576   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-07 05:40:44.552   927  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 05:40:45.513  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 05:40:45.513  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b143e15 added. We now have 4 listener(s)
10-07 05:40:45.513  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:40:45.526  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:40:45.526  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b143e15 removed from the list
10-07 05:40:45.526  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:40:45.526  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:45.527  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:45.528  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:40:45.528  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc7052a added. We now have 4 listener(s)
10-07 05:40:45.528  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:40:45.532  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:40:45.533  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc7052a removed from the list
10-07 05:40:45.533  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 05:40:45.533  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:40:45.533  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:40:45.534  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:40:45.535  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fcc2f1b added. We now have 4 listener(s)
10-07 05:40:45.535  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:40:45.541   927  3846 D WifiService: setWifiEnabled: false pid=5643, uid=10077
10-07 05:40:45.541   927  3846 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 05:40:45.547   927  2931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-07 05:40:45.547   927  2931 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-07 05:40:45.547   927  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 05:40:45.548   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 05:40:45.554  4561  4629 D BluetoothAdapterState: Current state: ON, message: 23
,10-07 05:40:45.554  4561  4629 D BluetoothAdapterProperties: Setting state to 13
,10-07 05:40:45.554  4561  4629 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-07 05:40:45.556  4561  4629 D BluetoothAdapterProperties: onBluetoothDisable()
10-07 05:40:45.557  4561  4629 I BluetoothAdapterState: Entering PendingCommandState
10-07 05:40:45.560  4561  4633 D BluetoothAdapterProperties: Scan Mode:20
10-07 05:40:45.561  4561  4629 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-07 05:40:45.563  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:40:45.567  4561  4561 D HeadsetService: Received stop request...Stopping profile...
,10-07 05:40:45.572   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 05:40:45.572   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 05:40:45.572  3073  3289 D BluetoothHeadset: Proxy object disconnected
10-07 05:40:45.572  3073  3073 D HeadsetProfile: Bluetooth service disconnected
10-07 05:40:45.573  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:45.573  3750  3948 D BluetoothHeadset: Proxy object disconnected
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:45.573  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 05:40:45.573   927   927 D BluetoothHeadset: Proxy object disconnected
,10-07 05:40:45.574  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.574  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:45.577  4561  4561 D A2dpService: Received stop request...Stopping profile...
,10-07 05:40:45.577   927  5378 D DhcpClient: Clearing IP address
,10-07 05:40:45.578   509   918 D CommandListener: Clearing all IP addresses on wlan0
10-07 05:40:45.578  4561  4785 D A2dpStateMachine: Exit Disconnected: -1
10-07 05:40:45.580   927   927 D BluetoothA2dp: Proxy object disconnected
10-07 05:40:45.581  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-07 05:40:45.581  3073  3073 D BluetoothA2dp: Proxy object disconnected
10-07 05:40:45.581  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.581  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.581  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:40:45.582  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:45.582  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:45.582   509   918 D CommandListener: Setting iface cfg
10-07 05:40:45.582  4561  4561 D HidService: Received stop request...Stopping profile...
10-07 05:40:45.582  4561  4561 D HidService: Stopping Bluetooth HidService
10-07 05:40:45.584  3073  3073 D BluetoothInputDevice: Proxy object disconnected
10-07 05:40:45.584  3073  3073 D HidProfile: Bluetooth service disconnected
,10-07 05:40:45.584  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:45.584  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:45.586  4561  4561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-07 05:40:45.586  4561  4561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-07 05:40:45.586  4561  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:40:45.586  4561  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:40:45.586  4561  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:40:45.586  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:45.586  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:45.586  4561  4633 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-07 05:40:45.586  4561  4561 D HealthService: Received stop request...Stopping profile...
10-07 05:40:45.587  4561  4633 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-07 05:40:45.588  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.588  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:45.588  4561  4561 D PanService: Received stop request...Stopping profile...
10-07 05:40:45.588   927  5379 D DhcpClient: Receive thread stopped
10-07 05:40:45.590  3073  3073 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-07 05:40:45.590  3073  3073 D PanProfile: Bluetooth service disconnected
10-07 05:40:45.592  4561  4561 D BluetoothMapService: Received stop request...Stopping profile...
10-07 05:40:45.592  4561  4561 D BluetoothMapService: stop()
10-07 05:40:45.592  4561  4561 D BluetoothMapAppObserver: deinitObservers()
10-07 05:40:45.593  4561  4561 D BluetoothMapAppObserver: removeReceiver()
10-07 05:40:45.594  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:40:45.594  3073  3073 D BluetoothMap: Proxy object disconnected
,10-07 05:40:45.594  3073  3073 D MapProfile: Bluetooth service disconnected
,10-07 05:40:45.595  3533  5436 V NativeCrypto: Read error: ssl=0x7f8ff86600: I/O error during system call, Connection timed out
10-07 05:40:45.596  4561  4561 D SapService: Received stop request...Stopping profile...
10-07 05:40:45.596  4561  4561 V SapService: stop()
10-07 05:40:45.597  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:45.598  3533  5436 V NativeCrypto: SSL shutdown failed: ssl=0x7f8ff86600: I/O error during system call, Broken pipe
10-07 05:40:45.599  4561  4561 V BluetoothAdapterState: isTurningOff()=true
,10-07 05:40:45.600  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.600  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.600  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:40:45.600  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:45.601  4561  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:40:45.601   927   937 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-07 05:40:45.601  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-07 05:40:45.601  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.601  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.601  4561  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:40:45.601  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:40:45.601  4561  4633 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-07 05:40:45.601  4561  4769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 05:40:45.601  4561  4561 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-07 05:40:45.601  4561  4769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 05:40:45.601  4561  4769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 05:40:45.601  4561  4561 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-07 05:40:45.601  4561  4769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 05:40:45.601   927  5376 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-07 05:40:45.602  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-07 05:40:45.602  4561  4633 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 05:40:45.602  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.602  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.602  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:40:45.602  4561  4561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-07 05:40:45.603  4561  4561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-07 05:40:45.603  4561  4633 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-07 05:40:45.603  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-07 05:40:45.603  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.603  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.603  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:40:45.603  4561  4561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-07 05:40:45.604  4561  4561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-07 05:40:45.605  4561  4561 D BluetoothMapService: MAP Service closeService in
10-07 05:40:45.605  4561  4561 D BluetoothMapMasInstance0: MAP Service shutdown
10-07 05:40:45.605  4561  4561 D ObexServerSockets0: shutdown(block = true)
10-07 05:40:45.606  4561  4561 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 05:40:45.606  4561  4804 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-07 05:40:45.606  4561  4561 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 05:40:45.607  4561  4805 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-07 05:40:45.607  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-07 05:40:45.608  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.608  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.608  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:40:45.608   927  5376 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-07 05:40:45.608  4561  4561 D BluetoothMapService: cleanup()
10-07 05:40:45.608  4561  4561 D BluetoothMapService: MAP Service closeService in
10-07 05:40:45.608  4561  4780 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-07 05:40:45.608   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-07 05:40:45.609   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-07 05:40:45.609  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-07 05:40:45.609  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.609  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.609  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:40:45.610  4561  4629 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-07 05:40:45.610  4561  4629 D BluetoothAdapterProperties: Setting state to 15
10-07 05:40:45.610  4561  4629 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,10-07 05:40:45.610  4561  4561 I BtOppRfcommListener: stopping Accept Thread
10-07 05:40:45.610   927  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-07 05:40:45.610  4561  4629 I BluetoothAdapterState: Entering BleOnState
10-07 05:40:45.610  4561  5317 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-07 05:40:45.611  4561  5317 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-07 05:40:45.612  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:45.612  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:45.613  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.613  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:45.617  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:45.617  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:45.618  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.618  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:45.621   927   940 I ActivityManager: Start proc 5697:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-07 05:40:45.621  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.622  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.622  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.622  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.622  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.622  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.622  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.622  5643  5643 V io.jxcore,.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:45.622  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:45.622   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-07 05:40:45.622  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.622   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-07 05:40:45.622  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:45.623  3073  3937 D BluetoothMap: onBluetoothStateChange: up=false
10-07 05:40:45.623   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:40:45.624   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 05:40:45.624  3073  3289 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:40:45.624   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:40:45.625  3073  3091 D BluetoothPan: onBluetoothStateChange on: false
,10-07 05:40:45.625  3073  3086 D BluetoothPbap: onBluetoothStateChange: up=false
,10-07 05:40:45.632   535   535 E Parcel  : Reading a NULL string not supported here.
,10-07 05:40:45.632   927  2933 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-07 05:40:45.633   927   927 D RttService: SCAN_AVAILABLE : 1
10-07 05:40:45.633  3750  3790 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:40:45.633   927  3039 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-07 05:40:45.633  3073  3937 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-07 05:40:45.634  3715  3872 W QCNEJ   : |CORE| network lost: 100
10-07 05:40:45.634  3715  3872 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-07 05:40:45.635   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:40:45.635  3073  3091 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-07 05:40:45.636  4561  4629 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-07 05:40:45.636  4561  4629 D BluetoothAdapterProperties: Setting state to 16
10-07 05:40:45.636  4561  4629 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-07 05:40:45.638  4561  4629 D BluetoothAdapterProperties: onBleDisable
,10-07 05:40:45.638  4561  4629 I BluetoothAdapterState: Entering PendingCommandState
,10-07 05:40:45.639   927  2931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-07 05:40:45.639  4561  4630 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-07 05:40:45.640  4561  4633 D BluetoothAdapterProperties: Scan Mode:20
10-07 05:40:45.641  4561  4769 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-07 05:40:45.641  4561  4769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:40:45.643  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:45.643  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:45.646  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:45.647  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:45.648  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:45.649  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:45.651   927  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 05:40:45.652  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:45.654  5643  5643 V io.jxcore.node.ConnectivityMonitor: updat,eConnectivityInfo: No relevant state changes
10-07 05:40:45.656  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:45.672   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 05:40:45.687  5697  5697 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-07 05:40:45.699  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 05:40:45.700   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-07 05:40:45.701   509   918 D CommandListener: Clearing all IP addresses on wlan0
,10-07 05:40:45.701   509   918 D TetherController: Setting IP forward enable = 0
10-07 05:40:45.701   927  2933 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,10-07 05:40:45.703   927  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-07 05:40:45.705   927  2931 D DhcpClient: doQuit
10-07 05:40:45.705   927  2931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-07 05:40:45.705   927  5378 D DhcpClient: onQuitting
10-07 05:40:45.706  3415  3415 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-07 05:40:45.707   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-07 05:40:45.710  5287  5287 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ef6ff3d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-07 05:40:45.712  4901  4901 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-07 05:40:45.714  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:45.715  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:40:45.716  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.716  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:45.716  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 05:40:45.717  5038  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-07 05:40:45.717  5038  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 05:40:45.717  5038  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,10-07 05:40:45.717  5038  5061 E SarControlService: no key has been found,reset the power
10-07 05:40:45.718  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:45.718  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:40:45.718  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-07 05:40:45.718  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 05:40:45.719  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 05:40:45.719  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.719  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:45.719  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:40:45.720  5063  5063 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-07 05:40:45.722  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-07 05:40:45.722  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-07 05:40:45.722  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 05:40:45.723  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:45.723  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:45.723  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:45.723  5063  5063 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-07 05:40:45.724  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000ea03000000000000ffffffff]
10-07 05:40:45.724  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:45.724  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-07 05:40:45.724  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:40:45.724  5063  5077 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,10-07 05:40:45.725  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-07 05:40:45.725  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-07 05:40:45.725  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:45.730   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cd73474:true
10-07 05:40:45.730  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:45.732  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000eb03000000000000ffffffff]
10-07 05:40:45.733  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:45.733  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 05:40:45.733  5063  5077 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-07 05:40:45.734  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 05:40:45.735  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-07 05:40:45.736  3415  3415 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-07 05:40:45.738   927   938 I ActivityManager: Start proc 5724:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-07 05:40:45.740  3415  3415 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-07 05:40:45.766   509   918 E Netd    : netlink response contains error (No such file or directory)
,10-07 05:40:45.766   509   918 D TetherController: Setting IP forward enable = 0
10-07 05:40:45.767   927  2933 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-07 05:40:45.771  5697  5697 D LocalBluetoothProfileManager: Adding local MAP profile
,10-07 05:40:45.773  5697  5697 D BluetoothMap: Create BluetoothMap proxy object
,10-07 05:40:45.781  3415  3415 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-07 05:40:45.790  5724  5724 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-07 05:40:45.792  5697  5697 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-07 05:40:45.802  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,10-07 05:40:45.804  3415  3415 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-07 05:40:45.813   927  3118 I ActivityManager: Killing 4947:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-07 05:40:45.852  4561  4633 I bt_hci  : shut_down
,10-07 05:40:45.857  4561  4639 I bt_vendor: low_power_mode_cb
,10-07 05:40:45.861  4561  4639 D bt_hwcfg: hw_epilog_process
,10-07 05:40:45.863  4561  4639 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-07 05:40:45.863  4561  4639 I bt_vendor: epilog_cb
10-07 05:40:45.863  4561  4639 I bt_hci  : epilog_finished_callback
,10-07 05:40:45.866  4561  4633 I bt_hci_h4: hal_close
10-07 05:40:45.866  4561  4633 I bt_userial_vendor: device fd = 54 close
,10-07 05:40:45.907   927  2931 D wifi    : In wifi stop Hal
10-07 05:40:45.907   927  2931 D wifi    : halHandle = 0x7f8ea48e00, mVM = 0x7fab14d140, mCls = 0x100a06
10-07 05:40:45.907   927  3414 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-07 05:40:45.907   927  3414 D WifiHAL : Got a signal to exit!!!
,10-07 05:40:45.907   927  3414 I WifiHAL : Exit wifi_event_loop
10-07 05:40:45.908   927  2931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-07 05:40:45.908   927  2931 E WifiHAL : Event processing terminated
,10-07 05:40:45.908  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 05:40:45.908   927  2931 D wifi    : In wifi cleaned up handler
10-07 05:40:45.908   927  2931 I WifiHAL : Internal cleanup completed
10-07 05:40:45.910  4022  4178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 05:40:45.910  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:45.912  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:45.913  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:45.933   927  3414 D wifi    : set interface wlan0 flags (DOWN)
,10-07 05:40:45.934   927  2931 D WifiNative-HAL: HAL event thread stopped successfully
,10-07 05:40:45.973  4561  4630 D bt_stack_manager: event_shut_down_stack finished.
,10-07 05:40:45.974  4561  4629 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-07 05:40:45.976  4561  4629 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-07 05:40:45.976  4561  4561 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 05:40:45.976  4561  4561 D BtGatt.GattService: Received stop request...Stopping profile...
10-07 05:40:45.976  4561  4561 D BtGatt.GattService: stop()
10-07 05:40:45.976  4561  4561 D BtGatt.AdvertiseManager: advertise clients cleared
,10-07 05:40:45.978  4561  4561 V BluetoothAdapterState: isTurningOff()=false
10-07 05:40:45.978  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-07 05:40:45.978  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:40:45.978  4561  4561 V BluetoothAdapterState: isBleTurningOff()=true
10-07 05:40:45.979  4561  4629 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-07 05:40:45.979  4561  4629 D BluetoothAdapterProperties: Setting state to 10
10-07 05:40:45.979  4561  4629 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-07 05:40:45.980  4561  4629 I BluetoothAdapterState: Entering OffState
,10-07 05:40:45.980   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-07 05:40:45.986  4561  4561 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-07 05:40:45.987  4561  4561 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-07 05:40:45.987  4561  4561 I BluetoothServiceJni: cleanupNative: return from cleanup
10-07 05:40:45.988  4561  4630 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-07 05:40:46.002  4561  4630 D bt_stack_manager: event_clean_up_stack finished.
,10-07 05:40:46.011  4561  4561 I art     : System.exit called, status: 0
,10-07 05:40:46.011  4561  4561 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-07 05:40:46.044  5724  5724 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-07 05:40:46.044  5724  5724 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 05:40:46.044  5724  5724 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 05:40:46.044  5724  5724 D StrictMode: StrictMode policy violation; ~duration=160 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:170)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 05:40:46.044  5724  5724 D StrictMode: StrictMode policy violation; ~duration=158 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.k.d(PG:583)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:170)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.044  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 05:40:46.045  5724  5724 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 05:40:46.045  5724  5724 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.io.File.exists(File.java:361)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 05:40:46.045  5724  5724 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-07 05:40:46.045  5724  5724 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-07 05:40:46.050  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 05:40:46.058  5697  5697 D DockEventReceiver: finishStartingService: stopping service
10-07 05:40:46.060   927  3106 I ActivityManager: Killing 5118:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-07 05:40:46.100   927   937 I ActivityManager: Process com.android.bluetooth (pid 4561) has died
10-07 05:40:46.102  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 05:40:46.117   927  3846 I ActivityManager: Start proc 5761:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-07 05:40:46.136   927   944 D Tethering: InitialState.processMessage what=4
,10-07 05:40:46.139   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-07 05:40:46.183  5761  5761 D AdapterServiceConfig: Adding HeadsetService
,10-07 05:40:46.183  5761  5761 D AdapterServiceConfig: Adding A2dpService
,10-07 05:40:46.184  5761  5761 D AdapterServiceConfig: Adding HidService
10-07 05:40:46.184  5761  5761 D AdapterServiceConfig: Adding HealthService
10-07 05:40:46.184  5761  5761 D AdapterServiceConfig: Adding PanService
10-07 05:40:46.184  5761  5761 D AdapterServiceConfig: Adding GattService
10-07 05:40:46.184  5761  5761 D AdapterServiceConfig: Adding BluetoothMapService
10-07 05:40:46.184  5761  5761 D AdapterServiceConfig: Adding SapService
10-07 05:40:46.187   927  3367 I ActivityManager: Killing 5456:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-07 05:40:46.225  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-07 05:40:46.228  3656  3656 D SystemUpdateService: onCreate
,10-07 05:40:46.231  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-07 05:40:46.243  3656  3656 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-07 05:40:46.248  3656  5773 I SystemUpdateService: active receiver: enabled
,10-07 05:40:46.249  3656  5405 I iu.UploadsManager: num queued entries: 0
,10-07 05:40:46.250  3656  5405 I iu.UploadsManager: num updated entries: 0
,10-07 05:40:46.250  3656  5405 I iu.SyncManager: NEXT; no task
,10-07 05:40:46.253  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 05:40:46.254  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-07 05:40:46.257  3656  5773 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 05:40:46.260  3656  5773 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-07 05:40:46.260  3656  5773 I SystemUpdateService: now status is 0 (complete)
10-07 05:40:46.260  3656  5773 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 05:40:46.260  3656  5773 I SystemUpdateService: file has been verified
10-07 05:40:46.260  3656  5773 I SystemUpdateService: OTA package size = 21989297
,10-07 05:40:46.267   927   938 I ActivityManager: Start proc 5775:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-07 05:40:46.282  3656  5773 I SystemUpdateService: showing system update notification
,10-07 05:40:46.297  5775  5775 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-07 05:40:46.300  5775  5775 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 05:40:46.306  5775  5775 D SprintDMHelper: simOperator: 
,10-07 05:40:46.306  5775  5775 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 05:40:46.319   927  3118 I ActivityManager: Start proc 5787:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-07 05:40:46.341  3656  3656 D SystemUpdateService: onDestroy
,10-07 05:40:46.342   927   938 I ActivityManager: Killing 5440:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-07 05:40:46.407  5006  5801 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-07 05:40:46.416   927  3841 I ActivityManager: Start proc 5802:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-07 05:40:46.418   927  3841 I ActivityManager: Killing 5287:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-07 05:40:46.472  5802  5802 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-07 05:40:46.597  5724  5751 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-07 05:40:46.658   927  3118 I ActivityManager: Killing 4643:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-07 05:40:46.673   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@756e7d:true
,10-07 05:40:46.701   927  3686 I ActivityManager: Start proc 5816:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-07 05:40:46.728  5816  5816 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-07 05:40:46.737   927  3686 I ActivityManager: Killing 5508:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-07 05:40:50.596   927  3846 D WifiService: setWifiEnabled: true pid=5643, uid=10077
,10-07 05:40:50.596   927  3846 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 05:40:50.604   509   918 D SoftapController: Softap fwReload - Ok
,10-07 05:40:50.610   509   918 D CommandListener: Setting iface cfg
,10-07 05:40:50.611   509   918 D CommandListener: Trying to bring down wlan0
,10-07 05:40:50.613   509   918 D CommandListener: Clearing all IP addresses on wlan0
,10-07 05:40:50.621   927  2931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-07 05:40:51.198   927  2931 D wifi    : set interface wlan0 flags (UP)
,10-07 05:40:51.201   927  2931 I WifiHAL : Initializing wifi
10-07 05:40:51.201   927  2931 I WifiHAL : Creating socket
10-07 05:40:51.201   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-07 05:40:51.204   927  2931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-07 05:40:51.204   927  2931 D wifi    : Did set static halHandle = 0x7f8ea48e00
10-07 05:40:51.204   927  2931 D wifi    : halHandle = 0x7f8ea48e00, mVM = 0x7fab14d140, mCls = 0x1956
10-07 05:40:51.204   927  2931 D wifi    : array field set
10-07 05:40:51.204   927  2931 I WifiNative-HAL: interface[0] = wlan0
10-07 05:40:51.206   927  5836 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547853995520
10-07 05:40:51.206   927  5836 D wifi    : waitForHalEvents called, vm = 0x7fab14d140, obj = 0x1956, env = 0x7f8c77c740
,10-07 05:40:51.270  5837  5837 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-07 05:40:51.287  5837  5837 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 05:40:51.308   927  2931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-07 05:40:51.312  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:51.313  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:51.313  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:51.331  5837  5837 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 05:40:51.331  5837  5837 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-07 05:40:51.347   927  2931 D WifiConfigStore: Loading config and enabling all networks 
,10-07 05:40:51.347  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:51.348  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:51.348  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:51.348  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:51.349  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:51.349  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:51.350  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:51.350  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:40:51.351  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:51.351  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:51.351  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:51.351  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:40:51.362   927  2931 D WifiConfigStore: loaded 0 passpoint configs
,10-07 05:40:51.362   927  2931 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-07 05:40:51.363   927  2931 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-07 05:40:51.364   927  2931 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-07 05:40:51.365   927  2931 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-07 05:40:51.365   927  2931 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,10-07 05:40:51.365   927  2931 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-07 05:40:51.365   927  2931 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-07 05:40:51.369   927  2931 D WifiNative-HAL: Setting external_sim to 1
,10-07 05:40:51.369  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-07 05:40:51.369   927  2931 D wifi    : setting dfs flag to true, 0x7f92a1d240
10-07 05:40:51.370   927  2931 D WifiStateMachine: Setting OUI to DA-A1-19
10-07 05:40:51.370   927  2931 D wifi    : setting scan oui 0x7f92a1d240
10-07 05:40:51.370   927  2931 D WifiHAL : Sending mac address OUI
10-07 05:40:51.374   927  2931 E native  : do suspend false
,10-07 05:40:51.381   927  2931 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-07 05:40:51.381   509   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-07 05:40:51.381   927   927 D RttService: SCAN_AVAILABLE : 3
,10-07 05:40:51.382   927  3039 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-07 05:40:51.382   509   918 D CommandListener: Setting iface cfg
,10-07 05:40:51.385   927  2923 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
10-07 05:40:51.385   927  2923 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-07 05:40:51.393   927  2923 D WifiNative-HAL: p2pGetDeviceAddress
10-07 05:40:51.393   927  2923 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-07 05:40:51.400   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267881 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-07 05:40:54.560  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:40:54.564  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:40:54.570  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:40:54.574  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:40:54.638   927  2931 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-07 05:40:54.639   927  2931 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-07 05:40:54.639   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 05:40:54.651   927  2931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-07 05:40:54.686   927  2931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-07 05:40:54.688  5837  5837 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-07 05:40:55.116  5837  5837 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-07 05:40:55.159  5837  5837 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-07 05:40:55.161  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-07 05:40:55.173   927  2931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 05:40:55.174   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-07 05:40:55.174   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-07 05:40:55.190   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 05:40:55.204   509   918 D CommandListener: Setting iface cfg
,10-07 05:40:55.211   927  2931 D WifiStateMachine: Start Dhcp Watchdog 2
,10-07 05:40:55.218   927  5843 D DhcpClient: Receive thread started
,10-07 05:40:55.223   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 05:40:55.223   927  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-07 05:40:55.223   927  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-07 05:40:55.304   927  2931 E native  : do suspend false
,10-07 05:40:55.318   927  5842 D DhcpClient: Broadcasting DHCPDISCOVER
,10-07 05:40:55.335   927  5843 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172569, domain null
,10-07 05:40:55.336   927  5842 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172569 seconds
,10-07 05:40:55.338   927  5842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-07 05:40:55.356   927  5843 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-07 05:40:55.358   927  5842 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-07 05:40:55.361   509   918 D CommandListener: Setting iface cfg
10-07 05:40:55.367   927  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-07 05:40:55.374   927  5842 D DhcpClient: Scheduling renewal in 86399s
,10-07 05:40:55.381   927  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-07 05:40:55.382   927  2931 D WifiConfigStore: No blacklist allowed without epno enabled
10-07 05:40:55.383   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-07 05:40:55.384   927  2933 D ConnectivityService: Adding iface wlan0 to network 101
,10-07 05:40:55.389   927  2931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-07 05:40:55.424   927  2933 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-07 05:40:55.425   927  2933 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-07 05:40:55.427   927  2933 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-07 05:40:55.430   927  2933 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-07 05:40:55.432   927  2933 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-07 05:40:55.439   927  2933 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 05:40:55.444   927  2933 D ConnectivityService: scheduleUnvalidatedPrompt 101
10-07 05:40:55.445   927  2933 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-07 05:40:55.445   927  2933 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-07 05:40:55.445   927  2933 D ConnectivityService:    accepting network in place of null
10-07 05:40:55.445   927  2931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-07 05:40:55.445   927  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 05:40:55.446   927  2933 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 05:40:55.455   927  5841 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271936, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-07 05:40:55.466   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 05:40:55.487   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 05:40:55.490   927  2933 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-07 05:40:55.490   927  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-07 05:40:55.490  3715  3872 W QCNEJ   : |CORE| network available: 101
10-07 05:40:55.491   927  2933 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-07 05:40:55.492   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-07 05:40:55.493  3715  3872 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-07 05:40:55.494  3715  3872 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-07 05:40:55.495  3715  3872 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-07 05:40:55.498  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:55.498  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:55.498  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.498  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:55.500  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:55.500  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 05:40:55.501  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.501  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:55.502  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:40:55.503  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:40:55.503  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.503  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 05:40:55.507  5038  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-07 05:40:55.507  5038  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 05:40:55.507  5038  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-07 05:40:55.507  5038  5061 E SarControlService: no key has been found,reset the power
10-07 05:40:55.507  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 05:40:55.507  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 05:40:55.508  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-07 05:40:55.508  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:40:55.508  5063  5063 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-07 05:40:55.509  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 05:40:55.509  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 05:40:55.509  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 05:40:55.510  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:40:55.510  5063  5063 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 05:40:55.511  4901  4901 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-07 05:40:55.514  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 05:40:55.517  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000ec03000000000000ffffffff]
10-07 05:40:55.517  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 05:40:55.517  5063  5077 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-07 05:40:55.518  3656  3656 D SystemUpdateService: onCreate
10-07 05:40:55.518  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 05:40:55.519  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-07 05:40:55.522   927  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-07 05:40:55.524  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-07 05:40:55.524  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000ed03000000000000ffffffff]
,10-07 05:40:55.524  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 05:40:55.524  5063  5077 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-07 05:40:55.527  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 05:40:55.527  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-07 05:40:55.535  3656  3656 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-07 05:40:55.540  3656  5405 I iu.UploadsManager: num queued entries: 0
,10-07 05:40:55.540  3656  5405 I iu.UploadsManager: num updated entries: 0
10-07 05:40:55.541  3656  5405 I iu.SyncManager: NEXT; no task
,10-07 05:40:55.544  3656  5853 I SystemUpdateService: active receiver: enabled
,10-07 05:40:55.546  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 05:40:55.548  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 05:40:55.549  5775  5775 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 05:40:55.553  5775  5775 D SprintDMHelper: simOperator: 
,10-07 05:40:55.553  5775  5775 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 05:40:55.571   927  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 07 Oct 2016 09:40:55 GMT], X-Android-Received-Millis=[1475833255571], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475833255544]}
,10-07 05:40:55.572   927  2933 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-07 05:40:55.572   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-07 05:40:55.572   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-07 05:40:55.573   927  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-07 05:40:55.575  3656  5853 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 05:40:55.591  3656  5853 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-07 05:40:55.591  3656  5853 I SystemUpdateService: now status is 0 (complete)
10-07 05:40:55.591  3656  5853 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 05:40:55.591  3656  5853 I SystemUpdateService: file has been verified
10-07 05:40:55.591  3656  5853 I SystemUpdateService: OTA package size = 21989297
,10-07 05:40:55.597  3656  5853 I SystemUpdateService: showing system update notification
,10-07 05:40:55.601   927   938 D WifiService: setWifiEnabled: false pid=5643, uid=10077
10-07 05:40:55.601   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 05:40:55.603   927  2931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-07 05:40:55.603   927  2931 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-07 05:40:55.603   927  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 05:40:55.603   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 05:40:55.610   927  5842 D DhcpClient: Clearing IP address
,10-07 05:40:55.611   509   918 D CommandListener: Clearing all IP addresses on wlan0
,10-07 05:40:55.612   509   918 D CommandListener: Setting iface cfg
,10-07 05:40:55.615  3656  3656 D SystemUpdateService: onDestroy
10-07 05:40:55.616   927  5843 D DhcpClient: Receive thread stopped
10-07 05:40:55.617  5006  5857 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-07 05:40:55.623   927  3841 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
10-07 05:40:55.623   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-07 05:40:55.623   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-07 05:40:55.623   927  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-07 05:40:55.623   927  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-07 05:40:55.628   927   927 D RttService: SCAN_AVAILABLE : 1
10-07 05:40:55.628   927  2933 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-07 05:40:55.628   927  3039 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-07 05:40:55.629   927  2931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/216.58.214.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-07 05:40:55.629  5006  585,7 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
10-07 05:40:55.629  5006  5857 W Babel_NetworkConnectionCheckingService: 	... 23 more
10-07 05:40:55.629  5006  5857 I Babel   : connection state changed from DISCONNECTED to CONNECTED
10-07 05:40:55.630  3715  3872 W QCNEJ   : |CORE| network lost: 101
10-07 05:40:55.631  3715  3872 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-07 05:40:55.633   927  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 05:40:55.634   535   535 E Parcel  : Reading a NULL string not supported here.
10-07 05:40:55.634   927  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,10-07 05:40:55.652   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 05:40:55.672   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-07 05:40:55.673   509   918 D CommandListener: Clearing all IP addresses on wlan0
,10-07 05:40:55.673   927  2933 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-07 05:40:55.673   927  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-07 05:40:55.675   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-07 05:40:55.677  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:55.677  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:40:55.677  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.677  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:55.678   927  2931 D DhcpClient: doQuit
10-07 05:40:55.678   927  2931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-07 05:40:55.678  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.678   927  5842 D DhcpClient: onQuitting
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:55.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:55.678  5837  5837 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-07 05:40:55.678  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.679  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:40:55.679  4901  4901 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-07 05:40:55.682  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:55.682  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:55.682  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.682  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:55.683  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:55.683  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:55.683  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.683  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:55.684  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 05:40:55.685  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonit,or:     - is Bluetooth enabled: false
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:40:55.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:40:55.685  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:40:55.683  5038  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-07 05:40:55.685  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:40:55.685  5038  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 05:40:55.686  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:55.686  5038  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-07 05:40:55.687  5038  5061 E SarControlService: no key has been found,reset the power
,10-07 05:40:55.687  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-07 05:40:55.687  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 05:40:55.687  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 05:40:55.687  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:40:55.687  5063  5063 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-07 05:40:55.688  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 05:40:55.689  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 05:40:55.689  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 05:40:55.689  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:40:55.689  5063  5063 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 05:40:55.690  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-07 05:40:55.693  3656  3656 D SystemUpdateService: onCreate
10-07 05:40:55.694  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000ee03000000000000ffffffff]
10-07 05:40:55.694  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 05:40:55.694  5063  5077 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,10-07 05:40:55.695  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-07 05:40:55.695  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 05:40:55.695  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 05:40:55.697  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000ef03000000000000ffffffff]
10-07 05:40:55.697  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 05:40:55.697  5063  5077 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-07 05:40:55.697  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 05:40:55.698  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-07 05:40:55.700  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-07 05:40:55.706  3656  5871 I SystemUpdateService: active receiver: enabled
,10-07 05:40:55.708  3656  3656 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-07 05:40:55.713  3656  5405 I iu.UploadsManager: num queued entries: 0
,10-07 05:40:55.713  3656  5405 I iu.UploadsManager: num updated entries: 0
10-07 05:40:55.714  3656  5405 I iu.SyncManager: NEXT; no task
,10-07 05:40:55.716  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 05:40:55.717  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-07 05:40:55.720  5775  5775 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 05:40:55.724  5775  5775 D SprintDMHelper: simOperator: 
10-07 05:40:55.724  5775  5775 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 05:40:55.731  3656  5871 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 05:40:55.731   509   918 E Netd    : netlink response contains error (No such file or directory)
10-07 05:40:55.732   927  2933 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-07 05:40:55.732   927  2933 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-07 05:40:55.735  5837  5837 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-07 05:40:55.736  5006  5875 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-07 05:40:55.739  3656  5871 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-07 05:40:55.739  3656  5871 I SystemUpdateService: now status is 0 (complete)
,10-07 05:40:55.739  3656  5871 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 05:40:55.739  3656  5871 I SystemUpdateService: file has been verified
10-07 05:40:55.740  3656  5871 I SystemUpdateService: OTA package size = 21989297
,10-07 05:40:55.746  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-07 05:40:55.756  3656  5871 I SystemUpdateService: showing system update notification
,10-07 05:40:55.762  3656  3656 D SystemUpdateService: onDestroy
,10-07 05:40:55.850   927  2931 D wifi    : In wifi stop Hal
10-07 05:40:55.851   927  2931 D wifi    : halHandle = 0x7f8ea48e00, mVM = 0x7fab14d140, mCls = 0x1956
10-07 05:40:55.851   927  5836 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-07 05:40:55.851   927  5836 D WifiHAL : Got a signal to exit!!!
10-07 05:40:55.851   927  5836 I WifiHAL : Exit wifi_event_loop
,10-07 05:40:55.852   927  2931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-07 05:40:55.852   927  2931 E WifiHAL : Event processing terminated
10-07 05:40:55.852   927  2931 D wifi    : In wifi cleaned up handler
10-07 05:40:55.852   927  2931 I WifiHAL : Internal cleanup completed
10-07 05:40:55.852  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:55.854  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:40:55.854  4022  4178 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 05:40:55.855  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-07 05:40:55.855  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:40:55.875   927  5836 D wifi    : set interface wlan0 flags (DOWN)
10-07 05:40:55.876   927  2931 D WifiNative-HAL: HAL event thread stopped successfully
,10-07 05:40:56.082   927   944 D Tethering: InitialState.processMessage what=4
,10-07 05:40:56.089   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-07 05:40:56.491   927  2933 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-07 05:40:57.578   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:58.579   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:40:59.580   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:41:00.580   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:41:00.640   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12da071:true
,10-07 05:41:00.641  5761  5761 D BluetoothAdapterState: make() - Creating AdapterState
,10-07 05:41:00.647  5761  5761 I bt_bluedroid: init
10-07 05:41:00.647  5761  5877 I BluetoothAdapterState: Entering OffState
,10-07 05:41:00.651  5761  5878 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-07 05:41:00.652  5761  5878 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-07 05:41:00.652  5761  5878 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-07 05:41:00.652  5761  5878 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-07 05:41:00.654  5761  5761 I bt_bluedroid: get_profile_interface socket
,10-07 05:41:00.657  5761  5881 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 05:41:00.657  5761  5761 I bt_bluedroid: get_profile_interface sdp
,10-07 05:41:00.660  5761  5881 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 05:41:00.667  5761  5772 I bt_bluedroid: config_hci_snoop_log
,10-07 05:41:00.669   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-07 05:41:00.676  5761  5877 D BluetoothAdapterState: Current state: OFF, message: 0
10-07 05:41:00.676  5761  5877 D BluetoothAdapterProperties: Setting state to 14
10-07 05:41:00.676  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-07 05:41:00.679  5761  5877 D BluetoothBondStateMachine: make
,10-07 05:41:00.682  5761  5882 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-07 05:41:00.688  5761  5877 I BluetoothAdapterState: Entering PendingCommandState
,10-07 05:41:00.689  5761  5761 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-07 05:41:00.693  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:00.694  5761  5761 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 05:41:00.695  5761  5761 D BtGatt.GattService: Received start request. Starting profile...
10-07 05:41:00.695  5761  5761 D BtGatt.GattService: start()
10-07 05:41:00.696  5761  5761 I bt_bluedroid: get_profile_interface gatt
,10-07 05:41:00.697  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:00.697  5761  5761 D BtGatt.AdvertiseManager: advertise manager created
,10-07 05:41:00.706  5761  5761 V BluetoothAdapterState: isTurningOff()=false
,10-07 05:41:00.706  5761  5761 V BluetoothAdapterState: isTurningOn()=false
10-07 05:41:00.706  5761  5761 V BluetoothAdapterState: isBleTurningOn()=true
10-07 05:41:00.706  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:00.707  5761  5877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-07 05:41:00.709  5761  5877 I bt_bluedroid: bt_bluedroid
10-07 05:41:00.709  5761  5878 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-07 05:41:00.710  5761  5878 I bt_hci  : start_up
,10-07 05:41:00.719  5761  5878 I bt_vendor: alloc value 0xf426c871
,10-07 05:41:00.719  5761  5878 I bt_vendor: init
,10-07 05:41:00.719  5761  5878 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,10-07 05:41:00.720  5761  5878 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-07 05:41:00.832  5761  5878 D bt_hci  : start_up starting async portion
10-07 05:41:00.833  5761  5885 I bt_hci  : event_finish_startup
10-07 05:41:00.833  5761  5885 I bt_hci_h4: hal_open
,10-07 05:41:00.833  5761  5885 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-07 05:41:00.835  5886  5886 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 05:41:00.837  5761  5885 I bt_userial_vendor: device fd = 54 open
,10-07 05:41:00.852  5761  5885 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 05:41:00.855  5761  5885 D bt_hwcfg: Chipset BCM4358A3
10-07 05:41:00.855  5761  5885 D bt_hwcfg: Target name = [BCM4358A3]
10-07 05:41:00.856  5761  5885 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-07 05:41:01.235  5761  5885 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-07 05:41:01.235  5761  5885 D bt_hwcfg: Settlement delay -- 100 ms
,10-07 05:41:01.236  5761  5885 I bt_hwcfg: Setting fw settlement delay to 100 
,10-07 05:41:01.370  5761  5885 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 05:41:01.370  5761  5885 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-07 05:41:01.372  5761  5885 I bt_hwcfg: vendor lib fwcfg completed
10-07 05:41:01.372  5761  5885 I bt_vendor: firmware callback
10-07 05:41:01.373  5761  5885 I bt_hci  : firmware_config_callback
,10-07 05:41:01.381  5761  5888 I bt_btu  : btu_task pending for preload complete event
10-07 05:41:01.381  5761  5888 I bt_btu_task: Bluetooth chip preload is complete
,10-07 05:41:01.381  5761  5888 I bt_btu  : btu_task received preload complete event
,10-07 05:41:01.389  5761  5888 I         : BTE_InitTraceLevels -- TRC_HCI
,10-07 05:41:01.389  5761  5888 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-07 05:41:01.389  5761  5888 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_AVRC
10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_A2D
10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_BNEP
10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_BTM
,10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_GAP
10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_PAN
,10-07 05:41:01.390  5761  5888 I         : BTE_InitTraceLevels -- TRC_SDP
10-07 05:41:01.391  5761  5888 I         : BTE_InitTraceLevels -- TRC_GATT
10-07 05:41:01.391  5761  5888 I         : BTE_InitTraceLevels -- TRC_SMP
,10-07 05:41:01.391  5761  5888 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-07 05:41:01.391  5761  5888 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-07 05:41:01.470  5761  5888 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41ea549
,10-07 05:41:01.470  5761  5888 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41ea549 
,10-07 05:41:01.483  5761  5881 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-07 05:41:01.484  5761  5881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-07 05:41:01.485  5761  5881 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 05:41:01.487  5761  5881 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 05:41:01.490  5761  5881 D BluetoothAdapterProperties: Scan Mode:20
,10-07 05:41:01.491  5761  5881 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 05:41:01.491  5761  5881 D bt_hci  : do_postload posting postload work item
,10-07 05:41:01.491  5761  5885 I bt_hci  : event_postload
,10-07 05:41:01.491  5761  5885 I bt_vendor: sco_config_cb
10-07 05:41:01.491  5761  5885 I bt_hci  : sco_config_callback postload finished.
10-07 05:41:01.494  5761  5881 D bt_bte_conf: Device ID record 1 : primary
10-07 05:41:01.494  5761  5881 D bt_bte_conf:   vendorId            = 000f
,10-07 05:41:01.494  5761  5881 D bt_bte_conf:   vendorIdSource      = 0001
10-07 05:41:01.494  5761  5881 D bt_bte_conf:   product             = 1200
10-07 05:41:01.494  5761  5881 D bt_bte_conf:   version             = 1436
10-07 05:41:01.494  5761  5881 D bt_bte_conf:   clientExecutableURL = 
10-07 05:41:01.494  5761  5881 D bt_bte_conf:   serviceDescription  = 
10-07 05:41:01.494  5761  5881 D bt_bte_conf:   documentationURL    = 
,10-07 05:41:01.495  5761  5881 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-07 05:41:01.495  5761  5878 D bt_stack_manager: event_start_up_stack finished
10-07 05:41:01.495  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:01.496  5761  5877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-07 05:41:01.496  5761  5877 D BluetoothAdapterProperties: Setting state to 15
10-07 05:41:01.496  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-07 05:41:01.497  5761  5877 I BluetoothAdapterState: Entering BleOnState
10-07 05:41:01.499  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:01.499  5761  5885 I bt_vendor: low_power_mode_cb
10-07 05:41:01.505  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:01.506  5761  5877 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-07 05:41:01.507  5761  5877 D BluetoothAdapterProperties: Setting state to 11
10-07 05:41:01.507  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-07 05:41:01.513  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:01.514  5761  5761 D HeadsetService: Received start request. Starting profile...
10-07 05:41:01.515  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:01.516  5761  5761 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-07 05:41:01.517  5761  5761 D HeadsetStateMachine: make
10-07 05:41:01.517  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:01.518  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:01.523  5761  5877 I BluetoothAdapterState: Entering PendingCommandState
,10-07 05:41:01.525  5761  5761 D HeadsetStateMachine: max_hf_connections = 1
10-07 05:41:01.525  5761  5761 I bt_bluedroid: get_profile_interface handsfree
,10-07 05:41:01.526  5761  5881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-07 05:41:01.526  5761  5881 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-07 05:41:01.530  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:01.531  5761  5761 D A2dpService: Received start request. Starting profile...
,10-07 05:41:01.531  5761  5761 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-07 05:41:01.531  5761  5761 I bt_bluedroid: get_profile_interface avrcp
,10-07 05:41:01.537  5761  5761 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-07 05:41:01.537  5761  5761 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-07 05:41:01.537  5761  5761 D A2dpStateMachine: make
10-07 05:41:01.538  5761  5761 I bt_bluedroid: get_profile_interface a2dp
,10-07 05:41:01.540  5761  5896 D A2dpStateMachine: Enter Disconnected: -2
,10-07 05:41:01.540  5761  5761 I BluetoothHidServiceJni: classInitNative: succeeds
,10-07 05:41:01.541  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:01.542  5761  5881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-07 05:41:01.543  5761  5761 D HidService: Received start request. Starting profile...
,10-07 05:41:01.543  5761  5761 I bt_bluedroid: get_profile_interface hidhost
10-07 05:41:01.543  5761  5761 D HidService: setHidService(): set to: null
10-07 05:41:01.543  5761  5881 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf41cb56d
10-07 05:41:01.543  5761  5881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-07 05:41:01.544  5761  5761 I BluetoothHealthServiceJni: classInitNative: succeeds
10-07 05:41:01.544  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:01.545  5761  5761 D HealthService: Received start request. Starting profile...
10-07 05:41:01.546  5697  5697 D BluetoothInputDevice: Proxy object connected
10-07 05:41:01.546  5761  5761 I bt_bluedroid: get_profile_interface health
,10-07 05:41:01.546  5697  5697 D HidProfile: Bluetooth service connected
,10-07 05:41:01.548  5761  5761 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-07 05:41:01.549  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:01.549  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 05:41:01.550  5697  5697 D BluetoothPan: BluetoothPAN Proxy object connected
,10-07 05:41:01.550  5761  5761 D PanService: Received start request. Starting profile...
10-07 05:41:01.550  5697  5697 D PanProfile: Bluetooth service connected
10-07 05:41:01.551  5761  5761 D BluetoothPanServiceJni: initializeNative(L110): pan
10-07 05:41:01.551  5761  5761 I bt_bluedroid: get_profile_interface pan
,10-07 05:41:01.551  5761  5881 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-07 05:41:01.553  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:01.555  5761  5761 D BluetoothMapService: Received start request. Starting profile...
,10-07 05:41:01.555  5761  5761 D BluetoothMapService: start()
10-07 05:41:01.557  5761  5761 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-07 05:41:01.558  5761  5761 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-07 05:41:01.558  5761  5761 D BluetoothMapAppObserver: createReceiver()
10-07 05:41:01.559  5761  5761 D BluetoothMapAppObserver: initObservers()
10-07 05:41:01.559  5761  5761 D BluetoothMapAppObserver: getEnabledAccountItems()
10-07 05:41:01.562  5697  5697 D BluetoothMap: Proxy object connected
,10-07 05:41:01.563  5697  5697 D MapProfile: Bluetooth service connected
10-07 05:41:01.563  5697  5697 D BluetoothMap: getConnectedDevices()
10-07 05:41:01.564  5697  5697 D BluetoothMap: Bluetooth is Not enabled
,10-07 05:41:01.567  5761  5761 V SapService: SapBinder()
,10-07 05:41:01.567  5761  5761 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:01.568  5761  5761 D SapService: Received start request. Starting profile...
10-07 05:41:01.568  5761  5761 V SapService: start()
,10-07 05:41:01.569  5761  5761 V BluetoothAdapterState: isTurningOff()=false
,10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:01.570  5761  5894 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:01.570  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isTurningOn()=true
,10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:01.571  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:01.572  5761  5761 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:01.572  5761  5761 V BluetoothAdapterState: isTurningOn()=true
,10-07 05:41:01.572  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:01.572  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:01.572  5761  5877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-07 05:41:01.572  5761  5877 D BluetoothAdapterProperties: ScanMode =  20
10-07 05:41:01.572  5761  5877 D BluetoothAdapterProperties: State =  11
10-07 05:41:01.574  5761  5881 D BluetoothAdapterProperties: Scan Mode:21
10-07 05:41:01.575  5761  5881 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 05:41:01.575  5643  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 05:41:01.576  5761  5877 D BluetoothAdapterProperties: Setting state to 12
,10-07 05:41:01.576  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-07 05:41:01.577  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:01.577  5761  5877 I BluetoothAdapterState: Entering OnState
10-07 05:41:01.577  3073  3086 D BluetoothMap: onBluetoothStateChange: up=true
10-07 05:41:01.580  3073  3073 D BluetoothMap: Proxy object connected
10-07 05:41:01.580  5697  5709 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 05:41:01.580  3073  3073 D MapProfile: Bluetooth service connected
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:01.580  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:41:01.580  3073  3073 D BluetoothMap: getConnectedDevices()
10-07 05:41:01.581   537   537 I ServiceManager: Waiting for service AtCmdFwd...
10-07 05:41:01.581   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:01.581   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 05:41:01.582  3073  3937 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:01.583  5697  5708 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 05:41:01.583   927   927 D BluetoothA2dp: Proxy object connected
,10-07 05:41:01.583   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:01.583  3073  3289 D BluetoothPan: onBluetoothStateChange on: true
10-07 05:41:01.584  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:41:01.585  5761  5761 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 05:41:01.585  3073  3073 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 05:41:01.585  3073  3086 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 05:41:01.585  3073  3073 D PanProfile: Bluetooth service connected
,10-07 05:41:01.586  5761  5761 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-07 05:41:01.587  3750  3790 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:01.588  3073  3937 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 05:41:01.588  5761  5761 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:01.588  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:41:01.590   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-07 05:41:01.590  5697  5709 D BluetoothMap: onBluetoothStateChange: up=true
10-07 05:41:01.590  5761  5761 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 05:41:01.590  3073  3091 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 05:41:01.590  3073  3073 D BluetoothInputDevice: Proxy object connected
10-07 05:41:01.590  3073  3073 D HidProfile: Bluetooth service connected
10-07 05:41:01.592  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:41:01.592  5761  5761 D ObexServerSockets: Succeed to create listening sockets 
10-07 05:41:01.592  5761  5761 D ObexServerSockets0: startAccept()
10-07 05:41:01.592  5761  5761 D ObexServerSockets0: prepareForNewConnect()
10-07 05:41:01.592  3073  3073 D BluetoothA2dp: Proxy object connected
10-07 05:41:01.593  5697  5708 D BluetoothPan: onBluetoothStateChange on: true
,10-07 05:41:01.594   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-07 05:41:01.595  5643  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-07 05:41:01.596  5761  5903 D ObexServerSockets0: Accepting socket connection...
10-07 05:41:01.596  5761  5904 D ObexServerSockets0: Accepting socket connection...
,10-07 05:41:01.597  5761  5761 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-07 05:41:01.597  5697  5697 D LocalBluetoothProfileManager: Adding local A2DP profile
10-07 05:41:01.597  5761  5761 D BluetoothSdpJni: SDP Create record success - handle: 0
10-07 05:41:01.598  5761  5761 D BluetoothMapService: onReceive
10-07 05:41:01.598  5761  5761 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 05:41:01.598  5761  5761 D BluetoothMapService: STATE_ON
,10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:01.600  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:01.600  5761  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 05:41:01.602  5697  5697 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-07 05:41:01.602  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:41:01.602  5761  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-07 05:41:01.602  5761  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
10-07 05:41:01.603  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:01.605  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:01.609  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 05:41:01.613  5697  5697 D BluetoothA2dp: Proxy object connected
,10-07 05:41:01.620  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 05:41:01.621  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,10-07 05:41:01.623  3073  3073 D BluetoothPbap: Proxy object connected
,10-07 05:41:01.623  3073  3073 D PbapServerProfile: Bluetooth service connected
10-07 05:41:01.624  5761  5761 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 05:41:01.624  5697  5697 D BluetoothPbap: Proxy object connected
10-07 05:41:01.624  5761  5761 D ObexServerSockets0: prepareForNewConnect()
10-07 05:41:01.624  5697  5697 D PbapServerProfile: Bluetooth service connected
10-07 05:41:01.626  5761  5908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 05:41:01.646  5761  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 05:41:01.647  5761  5914 I BtOppRfcommListener: Accept thread started.
,10-07 05:41:01.682   927   927 D BluetoothHeadset: Proxy object connected
,10-07 05:41:01.682   927   927 D BluetoothHeadset: Proxy object connected
10-07 05:41:01.683  3073  3289 D BluetoothHeadset: Proxy object connected
10-07 05:41:01.683  3073  3086 D BluetoothHeadset: Proxy object connected
10-07 05:41:01.683  3073  3073 D HeadsetProfile: Bluetooth service connected
10-07 05:41:01.683  3750  3948 D BluetoothHeadset: Proxy object connected
10-07 05:41:01.684   927   944 D BluetoothHeadset: Proxy object connected
,10-07 05:41:01.685  3073  3073 D HeadsetProfile: Bluetooth service connected
,10-07 05:41:01.683   927   927 D BluetoothHeadset: Proxy object connected
,10-07 05:41:01.687  3750  3776 D BluetoothHeadset: Proxy object connected
10-07 05:41:01.691   927   944 D BluetoothHeadset: Proxy object connected
,10-07 05:41:01.705  5697  5709 D BluetoothHeadset: Proxy object connected
,10-07 05:41:01.706  5697  5697 D HeadsetProfile: Bluetooth service connected
,10-07 05:41:02.582   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-07 05:41:03.452   927  2933 D ConnectivityService: handlePromptUnvalidated 101
,10-07 05:41:05.614  5761  5877 D BluetoothAdapterState: Current state: ON, message: 23
10-07 05:41:05.615  5761  5877 D BluetoothAdapterProperties: Setting state to 13
,10-07 05:41:05.616  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-07 05:41:05.617  5761  5877 D BluetoothAdapterProperties: onBluetoothDisable()
10-07 05:41:05.618  5761  5877 I BluetoothAdapterState: Entering PendingCommandState
,10-07 05:41:05.620  5761  5881 D BluetoothAdapterProperties: Scan Mode:20
,10-07 05:41:05.621  5761  5877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-07 05:41:05.626  5761  5761 D HeadsetService: Received stop request...Stopping profile...
,10-07 05:41:05.627  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:05.627  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:05.628  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:41:05.628  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:41:05.629   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 05:41:05.630   927   927 D BluetoothHeadset: Proxy object disconnected
,10-07 05:41:05.630  3073  3091 D BluetoothHeadset: Proxy object disconnected
10-07 05:41:05.630  5761  5761 D A2dpService: Received stop request...Stopping profile...
10-07 05:41:05.631  3073  3073 D HeadsetProfile: Bluetooth service disconnected
10-07 05:41:05.631  5697  5708 D BluetoothHeadset: Proxy object disconnected
,10-07 05:41:05.632  3750  3790 D BluetoothHeadset: Proxy object disconnected
,10-07 05:41:05.632  5761  5896 D A2dpStateMachine: Exit Disconnected: -1
10-07 05:41:05.632   927   927 D BluetoothHeadset: Proxy object disconnected
10-07 05:41:05.632  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:05.632  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:41:05.634   927   927 D BluetoothA2dp: Proxy object disconnected
10-07 05:41:05.634  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:41:05.634  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:05.635  3073  3073 D BluetoothA2dp: Proxy object disconnected
10-07 05:41:05.637  5761  5761 V BluetoothAdapterState: isTurningOff()=true
10-07 05:41:05.637  5761  5761 V BluetoothAdapterState: isTurningOn()=false
10-07 05:41:05.637  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 05:41:05.637  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:05.639  5697  5697 D HeadsetProfile: Bluetooth service disconnected
,10-07 05:41:05.639  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:05.639  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:41:05.639  5697  5697 D BluetoothA2dp: Proxy object disconnected
10-07 05:41:05.640  5643  5643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-07 05:41:05.641  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:05.642  5761  5761 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-07 05:41:05.642  5761  5761 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-07 05:41:05.642  5761  5881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-07 05:41:05.643  5761  5888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:41:05.643  5761  5888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:41:05.643  5761  5888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:41:05.644  5761  5761 D HidService: Received stop request...Stopping profile...
,10-07 05:41:05.645  5761  5761 D HidService: Stopping Bluetooth HidService
10-07 05:41:05.646  5761  5881 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-07 05:41:05.647  3073  3073 D BluetoothInputDevice: Proxy object disconnected
10-07 05:41:05.647  3073  3073 D HidProfile: Bluetooth service disconnected
10-07 05:41:05.647  5761  5761 V BluetoothAdapterState: isTurningOff()=true
10-07 05:41:05.647  5761  5761 V BluetoothAdapterState: isTurningOn()=false
,10-07 05:41:05.647  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:05.647  5697  5697 D BluetoothInputDevice: Proxy object disconnected
10-07 05:41:05.647  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:05.647  5697  5697 D HidProfile: Bluetooth service disconnected
,10-07 05:41:05.649  5761  5881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-07 05:41:05.649  5761  5888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:41:05.649  5761  5888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-07 05:41:05.649  5761  5888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 05:41:05.649  5761  5888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-07 05:41:05.649  5761  5888 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-07 05:41:05.650  5761  5888 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-07 05:41:05.652  5761  5761 D HealthService: Received stop request...Stopping profile...
10-07 05:41:05.654  5761  5761 D PanService: Received stop request...Stopping profile...
10-07 05:41:05.655  3073  3073 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-07 05:41:05.655  3073  3073 D PanProfile: Bluetooth service disconnected
,10-07 05:41:05.655  5697  5697 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-07 05:41:05.655  5697  5697 D PanProfile: Bluetooth service disconnected
,10-07 05:41:05.657  5761  5761 D BluetoothMapService: Received stop request...Stopping profile...
10-07 05:41:05.657  5761  5761 D BluetoothMapService: stop()
10-07 05:41:05.657  5761  5761 D BluetoothMapAppObserver: deinitObservers()
,10-07 05:41:05.658  5761  5761 D BluetoothMapAppObserver: removeReceiver()
10-07 05:41:05.659  3073  3073 D BluetoothMap: Proxy object disconnected
10-07 05:41:05.660  3073  3073 D MapProfile: Bluetooth service disconnected
10-07 05:41:05.660  5761  5761 V BluetoothAdapterState: isTurningOff()=true
,10-07 05:41:05.660  5761  5761 V BluetoothAdapterState: isTurningOn()=false
10-07 05:41:05.660  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:05.660  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:05.660  5761  5761 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-07 05:41:05.660  5761  5761 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-07 05:41:05.660  5761  5881 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 05:41:05.661  5761  5761 D SapService: Received stop request...Stopping profile...
10-07 05:41:05.661  5761  5761 V SapService: stop()
10-07 05:41:05.662  5761  5761 V BluetoothAdapterState: isTurningOff()=true
10-07 05:41:05.662  5761  5761 V BluetoothAdapterState: isTurningOn()=false
10-07 05:41:05.662  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 05:41:05.663  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:05.663  5761  5761 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-07 05:41:05.663  5761  5881 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-07 05:41:05.663  5761  5761 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-07 05:41:05.664  5761  5761 V BluetoothAdapterState: isTurningOff()=true
10-07 05:41:05.664  5761  5761 V BluetoothAdapterState: isTurningOn()=false
,10-07 05:41:05.664  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:05.664  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:05.664  5761  5761 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-07 05:41:05.664  5761  5761 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-07 05:41:05.665  5761  5761 D BluetoothMapService: MAP Service closeService in
10-07 05:41:05.665  5761  5761 D BluetoothMapMasInstance0: MAP Service shutdown
10-07 05:41:05.665  5761  5761 D ObexServerSockets0: shutdown(block = true)
10-07 05:41:05.666  5761  5903 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-07 05:41:05.667  5761  5761 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-07 05:41:05.667  5761  5761 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-07 05:41:05.667  5761  5904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-07 05:41:05.667  5761  5890 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-07 05:41:05.667  5761  5761 V BluetoothAdapterState: isTurningOff()=true
10-07 05:41:05.667  5761  5761 V BluetoothAdapterState: isTurningOn()=false
10-07 05:41:05.667  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:05.667  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:05.668  5761  5761 D BluetoothMapService: cleanup()
10-07 05:41:05.668  5761  5761 D BluetoothMapService: MAP Service closeService in
,10-07 05:41:05.668  5761  5761 V BluetoothAdapterState: isTurningOff()=true
10-07 05:41:05.668  5761  5761 V BluetoothAdapterState: isTurningOn()=false
10-07 05:41:05.668  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:05.668  5761  5761 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:05.669  5761  5761 I BtOppRfcommListener: stopping Accept Thread
10-07 05:41:05.670  5761  5914 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-07 05:41:05.670  5761  5877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-07 05:41:05.670  5761  5877 D BluetoothAdapterProperties: Setting state to 15
10-07 05:41:05.670  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-07 05:41:05.670  5697  5697 D BluetoothMap: Proxy object disconnected
10-07 05:41:05.670  5697  5697 D MapProfile: Bluetooth service disconnected
10-07 05:41:05.671  5761  5877 I BluetoothAdapterState: Entering BleOnState
10-07 05:41:05.671  3073  3937 D BluetoothMap: onBluetoothStateChange: up=false
10-07 05:41:05.672  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-07 05:41:05.672  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:05.672  5761  5914 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-07 05:41:05.673  5697  5708 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 05:41:05.675  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:05.677  5697  5709 D BluetoothPbap: onBluetoothStateChange: up=false
10-07 05:41:05.677  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:05.677   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:41:05.678  5697  5708 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:41:05.678   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 05:41:05.678  3073  3937 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:41:05.678  5697  5709 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-07 05:41:05.679   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:41:05.679  3073  3289 D BluetoothPan: onBluetoothStateChange on: false
,10-07 05:41:05.680  3073  3086 D BluetoothPbap: onBluetoothStateChange: up=false
,10-07 05:41:05.680  3750  3948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:41:05.681  3073  3091 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-07 05:41:05.681   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-07 05:41:05.682  5697  5708 D BluetoothMap: onBluetoothStateChange: up=false
10-07 05:41:05.688  3073  3937 D BluetoothA2dp: onBluetoothStateChange: up=false
10-07 05:41:05.688  5697  5709 D BluetoothPan: onBluetoothStateChange on: false
10-07 05:41:05.689  5761  5877 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-07 05:41:05.689  5761  5877 D BluetoothAdapterProperties: Setting state to 16
10-07 05:41:05.689  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-07 05:41:05.690  5761  5877 D BluetoothAdapterProperties: onBleDisable
10-07 05:41:05.690  5761  5877 I BluetoothAdapterState: Entering PendingCommandState
10-07 05:41:05.690  5761  5878 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-07 05:41:05.691  5761  5888 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-07 05:41:05.691  5761  5888 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-07 05:41:05.694  5697  5697 D DockEventReceiver: finishStartingService: stopping service
10-07 05:41:05.695  5761  5881 D BluetoothAdapterProperties: Scan Mode:20
10-07 05:41:05.695  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:05.697  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:05.699  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 05:41:05.699  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:05.701  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:05.703  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:05.705  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:05.708  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 05:41:05.713  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 05:41:05.717  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,10-07 05:41:05.905  5761  5881 I bt_hci  : shut_down
,10-07 05:41:05.914  5761  5885 D bt_hwcfg: hw_epilog_process
,10-07 05:41:05.914  5761  5885 I bt_vendor: low_power_mode_cb
,10-07 05:41:05.917  5761  5885 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-07 05:41:05.917  5761  5885 I bt_vendor: epilog_cb
10-07 05:41:05.917  5761  5885 I bt_hci  : epilog_finished_callback
,10-07 05:41:05.922  5761  5881 I bt_hci_h4: hal_close
,10-07 05:41:05.923  5761  5881 I bt_userial_vendor: device fd = 54 close
,10-07 05:41:06.033  5761  5878 D bt_stack_manager: event_shut_down_stack finished.
,10-07 05:41:06.034  5761  5877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-07 05:41:06.038  5761  5877 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-07 05:41:06.038  5761  5761 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 05:41:06.041  5761  5761 D BtGatt.GattService: Received stop request...Stopping profile...
,10-07 05:41:06.041  5761  5761 D BtGatt.GattService: stop()
,10-07 05:41:06.041  5761  5761 D BtGatt.AdvertiseManager: advertise clients cleared
,10-07 05:41:06.045  5761  5761 V BluetoothAdapterState: isTurningOff()=false
,10-07 05:41:06.045  5761  5761 V BluetoothAdapterState: isTurningOn()=false
10-07 05:41:06.045  5761  5761 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:06.046  5761  5761 V BluetoothAdapterState: isBleTurningOff()=true
10-07 05:41:06.046  5761  5877 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-07 05:41:06.046  5761  5877 D BluetoothAdapterProperties: Setting state to 10
10-07 05:41:06.047  5761  5877 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-07 05:41:06.048  5761  5877 I BluetoothAdapterState: Entering OffState
10-07 05:41:06.049   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-07 05:41:06.064  5761  5761 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-07 05:41:06.064  5761  5761 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-07 05:41:06.064  5761  5761 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-07 05:41:06.067  5761  5878 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-07 05:41:06.075  5761  5761 I art     : System.exit called, status: 0
,10-07 05:41:06.075  5761  5761 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-07 05:41:06.106   927   937 I ActivityManager: Process com.android.bluetooth (pid 5761) has died
,10-07 05:41:10.612  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:10.613  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:41:10.617  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:41:10.617  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fcc2f1b removed from the list
10-07 05:41:10.618  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:10.618  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:10.618  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:41:10.624  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 05:41:10.624  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@807a691 added. We now have 4 listener(s)
,10-07 05:41:10.625  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:41:10.627  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:41:10.627  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@807a691 removed from the list
10-07 05:41:10.627  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:10.627  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:10.628  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:41:10.629  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 05:41:10.630  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@52849f6 added. We now have 4 listener(s)
,10-07 05:41:10.630  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:41:15.638  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:15.673   927   944 I ActivityManager: Start proc 5923:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-07 05:41:15.755  5923  5923 D AdapterServiceConfig: Adding HeadsetService
,10-07 05:41:15.756  5923  5923 D AdapterServiceConfig: Adding A2dpService
10-07 05:41:15.756  5923  5923 D AdapterServiceConfig: Adding HidService
10-07 05:41:15.756  5923  5923 D AdapterServiceConfig: Adding HealthService
10-07 05:41:15.756  5923  5923 D AdapterServiceConfig: Adding PanService
10-07 05:41:15.756  5923  5923 D AdapterServiceConfig: Adding GattService
10-07 05:41:15.756  5923  5923 D AdapterServiceConfig: Adding BluetoothMapService
,10-07 05:41:15.757  5923  5923 D AdapterServiceConfig: Adding SapService
,10-07 05:41:15.767   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bace116:true
,10-07 05:41:15.767  5923  5923 D BluetoothAdapterState: make() - Creating AdapterState
,10-07 05:41:15.770  5923  5923 I bt_bluedroid: init
,10-07 05:41:15.771  5923  5935 I BluetoothAdapterState: Entering OffState
,10-07 05:41:15.774  5923  5936 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-07 05:41:15.774  5923  5936 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-07 05:41:15.774  5923  5936 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-07 05:41:15.774  5923  5936 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-07 05:41:15.775  5923  5923 I bt_bluedroid: get_profile_interface socket
10-07 05:41:15.777  5923  5923 I bt_bluedroid: get_profile_interface sdp
10-07 05:41:15.777  5923  5939 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-07 05:41:15.779  5923  5939 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 05:41:15.783  5923  5934 I bt_bluedroid: config_hci_snoop_log
,10-07 05:41:15.784   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-07 05:41:15.788  5923  5935 D BluetoothAdapterState: Current state: OFF, message: 0
,10-07 05:41:15.788  5923  5935 D BluetoothAdapterProperties: Setting state to 14
10-07 05:41:15.788  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-07 05:41:15.790  5923  5935 D BluetoothBondStateMachine: make
,10-07 05:41:15.792  5923  5940 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-07 05:41:15.795  5923  5935 I BluetoothAdapterState: Entering PendingCommandState
,10-07 05:41:15.796  5923  5923 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-07 05:41:15.799  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:15.800  5923  5923 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-07 05:41:15.800  5923  5923 D BtGatt.GattService: Received start request. Starting profile...
10-07 05:41:15.800  5923  5923 D BtGatt.GattService: start()
10-07 05:41:15.800  5923  5923 I bt_bluedroid: get_profile_interface gatt
10-07 05:41:15.802  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:15.802  5923  5923 D BtGatt.AdvertiseManager: advertise manager created
,10-07 05:41:15.808  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:15.808  5923  5923 V BluetoothAdapterState: isTurningOn()=false
,10-07 05:41:15.808  5923  5923 V BluetoothAdapterState: isBleTurningOn()=true
10-07 05:41:15.808  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:15.809  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-07 05:41:15.811  5923  5935 I bt_bluedroid: bt_bluedroid
,10-07 05:41:15.812  5923  5936 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-07 05:41:15.812  5923  5936 I bt_hci  : start_up
,10-07 05:41:15.818  5923  5936 I bt_vendor: alloc value 0xf42bf871
,10-07 05:41:15.818  5923  5936 I bt_vendor: init
10-07 05:41:15.818  5923  5936 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-07 05:41:15.818  5923  5936 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-07 05:41:15.931  5923  5936 D bt_hci  : start_up starting async portion
,10-07 05:41:15.931  5923  5943 I bt_hci  : event_finish_startup
10-07 05:41:15.932  5923  5943 I bt_hci_h4: hal_open
,10-07 05:41:15.932  5923  5943 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-07 05:41:15.936  5923  5943 I bt_userial_vendor: device fd = 54 open
,10-07 05:41:15.932  5944  5944 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 05:41:15.954  5923  5943 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-07 05:41:15.957  5923  5943 D bt_hwcfg: Chipset BCM4358A3
,10-07 05:41:15.957  5923  5943 D bt_hwcfg: Target name = [BCM4358A3]
10-07 05:41:15.958  5923  5943 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-07 05:41:16.495  5923  5943 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-07 05:41:16.495  5923  5943 D bt_hwcfg: Settlement delay -- 100 ms
10-07 05:41:16.496  5923  5943 I bt_hwcfg: Setting fw settlement delay to 100 
,10-07 05:41:16.629  5923  5943 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-07 05:41:16.630  5923  5943 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-07 05:41:16.631  5923  5943 I bt_hwcfg: vendor lib fwcfg completed
10-07 05:41:16.631  5923  5943 I bt_vendor: firmware callback
10-07 05:41:16.631  5923  5943 I bt_hci  : firmware_config_callback
,10-07 05:41:16.641  5923  5946 I bt_btu  : btu_task pending for preload complete event
10-07 05:41:16.641  5923  5946 I bt_btu_task: Bluetooth chip preload is complete
10-07 05:41:16.641  5923  5946 I bt_btu  : btu_task received preload complete event
,10-07 05:41:16.648  5923  5946 I         : BTE_InitTraceLevels -- TRC_HCI
,10-07 05:41:16.648  5923  5946 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-07 05:41:16.648  5923  5946 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-07 05:41:16.648  5923  5946 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_AVRC
10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_A2D
10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_BNEP
10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_BTM
,10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_GAP
10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_PAN
10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_SDP
,10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_GATT
10-07 05:41:16.649  5923  5946 I         : BTE_InitTraceLevels -- TRC_SMP
10-07 05:41:16.650  5923  5946 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-07 05:41:16.650  5923  5946 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-07 05:41:16.734  5923  5946 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf423d549
,10-07 05:41:16.735  5923  5946 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf423d549 
,10-07 05:41:16.744  5923  5939 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-07 05:41:16.746  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-07 05:41:16.747  5923  5939 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-07 05:41:16.750  5923  5939 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-07 05:41:16.754  5923  5939 D BluetoothAdapterProperties: Scan Mode:20
,10-07 05:41:16.755  5923  5939 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 05:41:16.755  5923  5939 D bt_hci  : do_postload posting postload work item
,10-07 05:41:16.756  5923  5943 I bt_hci  : event_postload
,10-07 05:41:16.756  5923  5943 I bt_vendor: sco_config_cb
,10-07 05:41:16.756  5923  5943 I bt_hci  : sco_config_callback postload finished.
10-07 05:41:16.758  5923  5939 D bt_bte_conf: Device ID record 1 : primary
,10-07 05:41:16.758  5923  5939 D bt_bte_conf:   vendorId            = 000f
10-07 05:41:16.759  5923  5939 D bt_bte_conf:   vendorIdSource      = 0001
10-07 05:41:16.759  5923  5939 D bt_bte_conf:   product             = 1200
10-07 05:41:16.759  5923  5939 D bt_bte_conf:   version             = 1436
10-07 05:41:16.759  5923  5939 D bt_bte_conf:   clientExecutableURL = 
,10-07 05:41:16.759  5923  5939 D bt_bte_conf:   serviceDescription  = 
,10-07 05:41:16.759  5923  5939 D bt_bte_conf:   documentationURL    = 
10-07 05:41:16.759  5923  5939 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-07 05:41:16.760  5923  5936 D bt_stack_manager: event_start_up_stack finished
10-07 05:41:16.761  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:16.761  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-07 05:41:16.761  5923  5935 D BluetoothAdapterProperties: Setting state to 15
10-07 05:41:16.761  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-07 05:41:16.763  5923  5935 I BluetoothAdapterState: Entering BleOnState
,10-07 05:41:16.765  5923  5943 I bt_vendor: low_power_mode_cb
10-07 05:41:16.767  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:16.769  5923  5935 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-07 05:41:16.769  5923  5935 D BluetoothAdapterProperties: Setting state to 11
10-07 05:41:16.769  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-07 05:41:16.777  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:16.779  5923  5923 D HeadsetService: Received start request. Starting profile...
,10-07 05:41:16.779  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:16.781  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:16.782  5923  5923 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-07 05:41:16.783  5923  5923 D HeadsetStateMachine: make
,10-07 05:41:16.795  5923  5935 I BluetoothAdapterState: Entering PendingCommandState
,10-07 05:41:16.797  5923  5923 D HeadsetStateMachine: max_hf_connections = 1
,10-07 05:41:16.797  5923  5923 I bt_bluedroid: get_profile_interface handsfree
10-07 05:41:16.797  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-07 05:41:16.798  5923  5939 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,10-07 05:41:16.801  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:16.801  5923  5923 D A2dpService: Received start request. Starting profile...
,10-07 05:41:16.802  5923  5923 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-07 05:41:16.802  5923  5923 I bt_bluedroid: get_profile_interface avrcp
,10-07 05:41:16.808  5923  5923 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-07 05:41:16.808  5923  5923 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-07 05:41:16.808  5923  5923 D A2dpStateMachine: make
10-07 05:41:16.809  5923  5923 I bt_bluedroid: get_profile_interface a2dp
,10-07 05:41:16.810  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-07 05:41:16.811  5923  5954 D A2dpStateMachine: Enter Disconnected: -2
10-07 05:41:16.812  5923  5923 I BluetoothHidServiceJni: classInitNative: succeeds
10-07 05:41:16.813  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:16.813  5923  5923 D HidService: Received start request. Starting profile...
10-07 05:41:16.813  5923  5923 I bt_bluedroid: get_profile_interface hidhost
,10-07 05:41:16.814  5923  5923 D HidService: setHidService(): set to: null
10-07 05:41:16.814  5923  5939 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf421e56d
10-07 05:41:16.814  5923  5939 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-07 05:41:16.814  5923  5923 I BluetoothHealthServiceJni: classInitNative: succeeds
10-07 05:41:16.815  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:16.816  5923  5923 D HealthService: Received start request. Starting profile...
,10-07 05:41:16.817  5923  5923 I bt_bluedroid: get_profile_interface health
10-07 05:41:16.819  5923  5923 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-07 05:41:16.820  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:16.820  5923  5923 D PanService: Received start request. Starting profile...
10-07 05:41:16.820  5923  5923 D BluetoothPanServiceJni: initializeNative(L110): pan
10-07 05:41:16.820  5923  5923 I bt_bluedroid: get_profile_interface pan
10-07 05:41:16.821  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-07 05:41:16.821  5923  5939 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-07 05:41:16.823  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:16.824  5923  5923 D BluetoothMapService: Received start request. Starting profile...
,10-07 05:41:16.824  5923  5923 D BluetoothMapService: start()
10-07 05:41:16.826  5923  5923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-07 05:41:16.827  5923  5923 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-07 05:41:16.827  5923  5923 D BluetoothMapAppObserver: createReceiver()
10-07 05:41:16.828  5923  5923 D BluetoothMapAppObserver: initObservers()
10-07 05:41:16.828  5923  5923 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-07 05:41:16.835  5923  5923 V SapService: SapBinder()
,10-07 05:41:16.835  5923  5923 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
10-07 05:41:16.836  5923  5923 D SapService: Received start request. Starting profile...
10-07 05:41:16.836  5923  5923 V SapService: start()
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:16.838  5923  5952 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isTurningOn()=true
,10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:16.838  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
,10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:16.839  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:16.840  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:16.840  5923  5923 V BluetoothAdapterState: isTurningOn()=true
,10-07 05:41:16.840  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
,10-07 05:41:16.840  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:16.841  5923  5923 V BluetoothAdapterState: isTurningOff()=false
10-07 05:41:16.841  5923  5923 V BluetoothAdapterState: isTurningOn()=true
10-07 05:41:16.841  5923  5923 V BluetoothAdapterState: isBleTurningOn()=false
10-07 05:41:16.841  5923  5923 V BluetoothAdapterState: isBleTurningOff()=false
10-07 05:41:16.841  5923  5935 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-07 05:41:16.841  5923  5935 D BluetoothAdapterProperties: ScanMode =  20
10-07 05:41:16.841  5923  5935 D BluetoothAdapterProperties: State =  11
10-07 05:41:16.844  5923  5939 D BluetoothAdapterProperties: Scan Mode:21
10-07 05:41:16.844  5923  5939 D BluetoothAdapterProperties: Discoverable Timeout:120
10-07 05:41:16.844  5643  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-07 05:41:16.845  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:16.845  5923  5935 D BluetoothAdapterProperties: Setting state to 12
10-07 05:41:16.845  5923  5935 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-07 05:41:16.846  3073  3086 D BluetoothMap: onBluetoothStateChange: up=true
10-07 05:41:16.847  5697  5709 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 05:41:16.847  5923  5935 I BluetoothAdapterState: Entering OnState
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:16.849  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:41:16.849  3073  3073 D BluetoothMap: Proxy object connected
,10-07 05:41:16.849  3073  3073 D MapProfile: Bluetooth service connected
10-07 05:41:16.849  3073  3073 D BluetoothMap: getConnectedDevices()
10-07 05:41:16.851  5697  5697 D BluetoothA2dp: Proxy object connected
10-07 05:41:16.852  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:16.853  5697  5708 D BluetoothPbap: onBluetoothStateChange: up=true
,10-07 05:41:16.854  5923  5923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-07 05:41:16.855  5923  5923 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-07 05:41:16.855   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:16.855  5697  5709 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:16.856   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 05:41:16.856  5923  5923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 05:41:16.856   927   927 D BluetoothA2dp: Proxy object connected
10-07 05:41:16.856  3073  3289 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:16.857  5697  5917 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 05:41:16.858  5923  5923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-07 05:41:16.858   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:16.858  3073  3937 D BluetoothPan: onBluetoothStateChange on: true
10-07 05:41:16.859  5923  5923 D ObexServerSockets: Succeed to create listening sockets 
10-07 05:41:16.859  5923  5923 D ObexServerSockets0: startAccept()
10-07 05:41:16.859  5923  5923 D ObexServerSockets0: prepareForNewConnect()
10-07 05:41:16.860  3073  3086 D BluetoothPbap: onBluetoothStateChange: up=true
10-07 05:41:16.861  5923  5923 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-07 05:41:16.861  5923  5923 D BluetoothSdpJni: SDP Create record success - handle: 0
10-07 05:41:16.861  3750  3776 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:16.862  5923  5960 D ObexServerSockets0: Accepting socket connection...
10-07 05:41:16.862  5923  5961 D ObexServerSockets0: Accepting socket connection...
,10-07 05:41:16.862  3073  3091 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-07 05:41:16.863  3073  3073 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 05:41:16.863  3073  3073 D PanProfile: Bluetooth service connected
10-07 05:41:16.864  3073  3073 D BluetoothInputDevice: Proxy object connected
10-07 05:41:16.864   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-07 05:41:16.864  3073  3073 D HidProfile: Bluetooth service connected
10-07 05:41:16.864  5697  5709 D BluetoothMap: onBluetoothStateChange: up=true
10-07 05:41:16.864  5697  5697 D BluetoothInputDevice: Proxy object connected
,10-07 05:41:16.864  5697  5697 D HidProfile: Bluetooth service connected
10-07 05:41:16.867  3073  3937 D BluetoothA2dp: onBluetoothStateChange: up=true
10-07 05:41:16.868  3073  3073 D BluetoothA2dp: Proxy object connected
10-07 05:41:16.868  5697  5708 D BluetoothPan: onBluetoothStateChange on: true
10-07 05:41:16.869  5697  5697 D BluetoothMap: Proxy object connected
10-07 05:41:16.869  5697  5697 D MapProfile: Bluetooth service connected
10-07 05:41:16.869  5697  5697 D BluetoothMap: getConnectedDevices()
,10-07 05:41:16.871  5923  5923 D BluetoothMapService: onReceive
10-07 05:41:16.871  5923  5923 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-07 05:41:16.872   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-07 05:41:16.872  5923  5923 D BluetoothMapService: STATE_ON
10-07 05:41:16.872  5697  5697 D BluetoothPan: BluetoothPAN Proxy object connected
10-07 05:41:16.872  5697  5697 D PanProfile: Bluetooth service connected
10-07 05:41:16.872  5643  5643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-07 05:41:16.875  5923  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 05:41:16.876  5923  5963 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-07 05:41:16.876  5923  5963 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:16.876  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:16.878  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-07 05:41:16.879  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:16.883  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:16.884  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,10-07 05:41:16.886  3533  3533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-07 05:41:16.892  5697  5697 D BluetoothPbap: Proxy object connected
,10-07 05:41:16.892  5697  5697 D PbapServerProfile: Bluetooth service connected
,10-07 05:41:16.897  5923  5923 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-07 05:41:16.897  5923  5923 D ObexServerSockets0: prepareForNewConnect()
10-07 05:41:16.898  3073  3073 D BluetoothPbap: Proxy object connected
10-07 05:41:16.898  3073  3073 D PbapServerProfile: Bluetooth service connected
10-07 05:41:16.901  5923  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 05:41:16.913  5923  5971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-07 05:41:16.914  5923  5971 I BtOppRfcommListener: Accept thread started.
,10-07 05:41:16.957   927   927 D BluetoothHeadset: Proxy object connected
,10-07 05:41:16.957   927   927 D BluetoothHeadset: Proxy object connected
10-07 05:41:16.957  3073  3091 D BluetoothHeadset: Proxy object connected
10-07 05:41:16.958  3073  3073 D HeadsetProfile: Bluetooth service connected
,10-07 05:41:16.958  5697  5917 D BluetoothHeadset: Proxy object connected
,10-07 05:41:16.958   927   944 D BluetoothHeadset: Proxy object connected
10-07 05:41:16.959  3750  3790 D BluetoothHeadset: Proxy object connected
10-07 05:41:16.959   927   927 D BluetoothHeadset: Proxy object connected
10-07 05:41:16.961  5697  5697 D HeadsetProfile: Bluetooth service connected
10-07 05:41:16.963  3750  3948 D BluetoothHeadset: Proxy object connected
,10-07 05:41:16.964   927   944 D BluetoothHeadset: Proxy object connected
,10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:20.654  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:20.659  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:20.660  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:20.660  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@52849f6 removed from the list
10-07 05:41:20.660  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:20.660  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:20.661  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:41:20.664  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 05:41:20.664  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f4a1f7 added. We now have 4 listener(s)
10-07 05:41:20.664  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:41:20.667   927  3848 D WifiService: setWifiEnabled: false pid=5643, uid=10077
,10-07 05:41:20.667   927  3848 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 05:41:22.583   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:41:23.584   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:41:24.585   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:41:25.586   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:41:25.676  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:25.677   927   938 D WifiService: setWifiEnabled: true pid=5643, uid=10077
10-07 05:41:25.677   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-07 05:41:25.686   509   918 D SoftapController: Softap fwReload - Ok
,10-07 05:41:25.692   509   918 D CommandListener: Setting iface cfg
,10-07 05:41:25.692   509   918 D CommandListener: Trying to bring down wlan0
,10-07 05:41:25.695   509   918 D CommandListener: Clearing all IP addresses on wlan0
,10-07 05:41:25.701   927  2931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-07 05:41:26.319   927  2931 D wifi    : set interface wlan0 flags (UP)
,10-07 05:41:26.321   927  2931 I WifiHAL : Initializing wifi
10-07 05:41:26.322   927  2931 I WifiHAL : Creating socket
,10-07 05:41:26.330   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-07 05:41:26.331   927  2931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-07 05:41:26.331   927  2931 D wifi    : Did set static halHandle = 0x7f8ea48e00
10-07 05:41:26.331   927  2931 D wifi    : halHandle = 0x7f8ea48e00, mVM = 0x7fab14d140, mCls = 0x101622
,10-07 05:41:26.332   927  2931 D wifi    : array field set
10-07 05:41:26.332   927  2931 I WifiNative-HAL: interface[0] = wlan0
10-07 05:41:26.334   927  5976 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547853995520
,10-07 05:41:26.335   927  5976 D wifi    : waitForHalEvents called, vm = 0x7fab14d140, obj = 0x101622, env = 0x7f8c77dc40
10-07 05:41:26.339   927  2931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-07 05:41:26.341   927  2931 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,10-07 05:41:26.346  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:26.349  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:26.393  5977  5977 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-07 05:41:26.413  5977  5977 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 05:41:26.449  5977  5977 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-07 05:41:26.449  5977  5977 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-07 05:41:26.587   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:41:27.361   927  2931 D WifiConfigStore: Loading config and enabling all networks 
,10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:27.367  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:27.373  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:27.382  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:27.387  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:27.389   927  2931 D WifiConfigStore: loaded 0 passpoint configs
,10-07 05:41:27.389   927  2931 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-07 05:41:27.390   927  2931 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-07 05:41:27.391   927  2931 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-07 05:41:27.393   927  2931 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-07 05:41:27.393   927  2931 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-07 05:41:27.393   927  2931 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-07 05:41:27.393   927  2931 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-07 05:41:27.398   927  2931 D WifiNative-HAL: Setting external_sim to 1
,10-07 05:41:27.398  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-07 05:41:27.399   927  2931 D wifi    : setting dfs flag to true, 0x7f92a11300
10-07 05:41:27.400   927  2931 D WifiStateMachine: Setting OUI to DA-A1-19
10-07 05:41:27.400   927  2931 D wifi    : setting scan oui 0x7f92a11300
10-07 05:41:27.400   927  2931 D WifiHAL : Sending mac address OUI
,10-07 05:41:27.406   927  2931 E native  : do suspend false
,10-07 05:41:27.417   927  2931 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-07 05:41:27.417   509   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-07 05:41:27.418   927   927 D RttService: SCAN_AVAILABLE : 3
,10-07 05:41:27.418   927  3039 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-07 05:41:27.419   509   918 D CommandListener: Setting iface cfg
,10-07 05:41:27.424   927  2923 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
10-07 05:41:27.424   927  2923 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-07 05:41:27.436   927  2923 D WifiNative-HAL: p2pGetDeviceAddress
10-07 05:41:27.437   927  2923 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-07 05:41:27.443   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303924 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,10-07 05:41:27.588   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-07 05:41:30.595  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:41:30.601  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:41:30.608  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:41:30.612  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-07 05:41:30.667   927  2931 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-07 05:41:30.669   927  2931 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-07 05:41:30.669   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 05:41:30.682   927  2931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:30.688  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:41:30.690  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:30.691  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.691  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f4a1f7 removed from the list
10-07 05:41:30.691  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:30.691  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.691  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.694  5643  5689 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-07 05:41:30.694  5643  5689 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-07 05:41:30.696  5643  5689 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@49eb61f Bundle[{}]
10-07 05:41:30.697  5643  5689 I io.jxcore.node.LifeCycleMonitor: start: OK
10-07 05:41:30.697  5643  5689 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-07 05:41:30.697  5643  5689 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-07 05:41:30.698  5643  5689 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-07 05:41:30.698  5643  5689 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-07 05:41:30.699  5643  5689 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-07 05:41:30.706  5643  5689 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
10-07 05:41:30.706  5643  5689 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-07 05:41:30.707  5643  5689 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
10-07 05:41:30.708  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 05:41:30.708  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78c6864 added. We now have 3 listener(s)
10-07 05:41:30.710  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 05:41:30.710  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.711  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.711  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.711  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef1acd added. We now have 4 listener(s)
10-07 05:41:30.711  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.712  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-07 05:41:30.716  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 05:41:30.720   927  2931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:30.721  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:30.722  5977  5977 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-07 05:41:30.723  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:41:30.723  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:41:30.723  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.723  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c76693 added. We now have 4 listener(s)
10-07 05:41:30.724  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.724  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:41:30.724  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.725  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.725  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.725  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d9a6d0 added. We now have 5 listener(s)
10-07 05:41:30.725  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.725  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:41:30.725  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:30.725  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:41:30.725  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.725  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.725  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.725  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.725  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-07 05:41:30.725  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78c6864 removed from the list
10-07 05:41:30.725  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.726  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef1acd removed from the list
10-07 05:41:30.726  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:30.726  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:30.726  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:41:30.727  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.727  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.727  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.727  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.728  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.728  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fef1acd not in the list
10-07 05:41:30.728  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.728  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.728  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.728  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.728  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:41:30.729  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d9a6d0 removed from the list
10-07 05:41:30.729  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.729  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.729  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.729  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.729  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.729  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c76693 removed from the list
10-07 05:41:30.730  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.730  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5f96c9 added. We now have 3 listener(s)
10-07 05:41:30.731  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:41:30.731  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-07 05:41:30.731  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.731  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.731  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31aa1ce added. We now have 4 listener(s)
10-07 05:41:30.731  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.731  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 05:41:30.733  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:30.736  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:30.739  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:30.739  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:41:30.739  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.739  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7a5ffc added. We now have 4 listener(s)
10-07 05:41:30.741  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.741  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:41:30.741  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.741  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.741  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.741  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@941d685 added. We now have 5 listener(s)
10-07 05:41:30.741  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.741  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:41:30.741  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 05:41:30.741  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-07 05:41:30.741  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:41:30.741  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 05:41:30.742  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.744  5643  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-07 05:41:30.744  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 05:41:30.747  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 05:41:30.747  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 05:41:30.747  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 05:41:30.750  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 05:41:30.750  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 05:41:30.750  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-07 05:41:30.750  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 05:41:30.750  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 05:41:30.751  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:41:30.753  5923  5934 D BtGatt.GattService: registerClient() - UUID=f0216006-e460-495a-913c-d0df80ac7914
10-07 05:41:30.753  5923  5939 D BtGatt.GattService: onClientRegistered() - UUID=f0216006-e460-495a-913c-d0df80ac7914, clientIf=5
10-07 05:41:30.754  5643  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-07 05:41:30.754  5923  5959 D BtGatt.GattService: start scan with filters
,10-07 05:41:30.757  5923  5942 D BtGatt.ScanManager: handling starting scan
10-07 05:41:30.757  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 05:41:30.757  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 05:41:30.757  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:41:30.757  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 05:41:30.757  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 05:41:30.758  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 05:41:30.758  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 05:41:30.760  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 05:41:30.760  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 05:41:30.760  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:41:30.761  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 05:41:30.762  5923  5942 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b7d40
,10-07 05:41:30.764  5643  5689 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-07 05:41:30.764  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:30.764  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-07 05:41:30.764  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.764  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 05:41:30.764  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.764  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-07 05:41:30.764  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 05:41:30.764  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 05:41:30.764  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 05:41:30.764  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-07 05:41:30.764  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-07 05:41:30.765  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:41:30.765  5923  5959 D BtGatt.GattService: stopScan() - queue size =1
10-07 05:41:30.766  5923  5962 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-07 05:41:30.766  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-07 05:41:30.766  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 05:41:30.766  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 05:41:30.767  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:41:30.767  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-07 05:41:30.767  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 05:41:30.767  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 05:41:30.767  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 05:41:30.768  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:41:30.768  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 05:41:30.768  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 05:41:30.768  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-07 05:41:30.768  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 05:41:30.768  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.769  5923  5939 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 05:41:30.769  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.769  5923  5942 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-07 05:41:30.769  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:41:30.769  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:41:30.769  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 05:41:30.772  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-07 05:41:30.772  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:30.772  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:41:30.772  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.773  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.773  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.773  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 05:41:30.773  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.773  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a5f96c9 removed from the list
10-07 05:41:30.773  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.773  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31aa1ce removed from the list
10-07 05:41:30.773  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:30.773  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:41:30.774  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.774  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.774  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.774  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.774  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.775  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31aa1ce not in the list
10-07 05:41:30.775  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.775  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.775  5923  5939 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 05:41:30.775  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.775  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.776  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-07 05:41:30.776  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:41:30.776  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@941d685 removed from the list
10-07 05:41:30.776  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-07 05:41:30.776  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.776  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.776  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.776  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.776  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7a5ffc removed from the list
10-07 05:41:30.776  5923  5942 D BtGatt.ScanManager: Starting BLE batch scan
10-07 05:41:30.776  5923  5942 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 05:41:30.776  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.776  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4e5601 added. We now have 3 listener(s)
10-07 05:41:30.778  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 05:41:30.778  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.778  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.778  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.778  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7551ca6 added. We now have 4 listener(s)
10-07 05:41:30.778  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.778  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 05:41:30.780  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:30.784  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:30.786  5923  5939 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 05:41:30.786  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:41:30.787  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:41:30.787  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:41:30.787  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.787  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60cb294 added. We now have 4 listener(s)
,10-07 05:41:30.789  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 05:41:30.789  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.789  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.789  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.789  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@449513d added. We now have 5 listener(s)
10-07 05:41:30.790  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.790  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:41:30.790  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.790  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:41:30.790  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-07 05:41:30.790  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 05:41:30.791  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:41:30.791  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 05:41:30.791  5923  5939 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 05:41:30.791  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.792  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-07 05:41:30.795  5643  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-07 05:41:30.795  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-07 05:41:30.797  5923  5939 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 05:41:30.797  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.798  5923  5942 D BtGatt.ScanManager: stopping BLe Batch
,10-07 05:41:30.799  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-07 05:41:30.799  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 05:41:30.800  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 05:41:30.802  5923  5939 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-07 05:41:30.802  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.803  5923  5942 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 05:41:30.803  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-07 05:41:30.803  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 05:41:30.803  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 05:41:30.803  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 05:41:30.803  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 05:41:30.803  5643  5689 D BluetoothAdapter: STATE_ON
,10-07 05:41:30.805  5923  5962 D BtGatt.GattService: registerClient() - UUID=26a770e0-fa2d-403e-966d-e19c9b60600d
10-07 05:41:30.806  5923  5939 D BtGatt.GattService: onClientRegistered() - UUID=26a770e0-fa2d-403e-966d-e19c9b60600d, clientIf=5
,10-07 05:41:30.806  5643  5653 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-07 05:41:30.806  5923  5934 D BtGatt.GattService: start scan with filters
,10-07 05:41:30.808  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 05:41:30.808  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 05:41:30.808  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:41:30.808  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 05:41:30.809  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 05:41:30.809  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,10-07 05:41:30.809  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-07 05:41:30.809  5923  5939 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 05:41:30.809  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:41:30.810  5923  5942 D BtGatt.ScanManager: handling starting scan
10-07 05:41:30.811  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:41:30.811  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 05:41:30.811  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-07 05:41:30.812  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-07 05:41:30.814  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-07 05:41:30.814  5643  5689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-07 05:41:30.814  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:41:30.814  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:30.814  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:41:30.814  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.814  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.814  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 05:41:30.814  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-07 05:41:30.814  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.814  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4e5601 removed from the list
10-07 05:41:30.814  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.814  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7551ca6 removed from the list
10-07 05:41:30.814  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:30.814  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.815  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:41:30.815  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-07 05:41:30.815  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.815  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.816  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.816  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.816  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.816  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7551ca6 not in the list
10-07 05:41:30.816  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-07 05:41:30.816  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 05:41:30.816  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 05:41:30.816  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 05:41:30.816  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 05:41:30.816  5923  5939 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 05:41:30.816  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.817  5923  5942 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-07 05:41:30.817  5643  5689 D BluetoothAdapter: STATE_ON
,10-07 05:41:30.818  5923  5934 D BtGatt.GattService: stopScan() - queue size =1
10-07 05:41:30.818  5923  5950 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 05:41:30.818  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 05:41:30.818  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 05:41:30.818  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 05:41:30.819  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-07 05:41:30.819  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 05:41:30.819  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 05:41:30.819  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 05:41:30.819  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 05:41:30.820  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:41:30.820  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 05:41:30.820  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 05:41:30.820  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 05:41:30.820  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-07 05:41:30.820  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.821  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.821  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.821  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.821  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:41:30.821  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@449513d removed from the list
10-07 05:41:30.821  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.821  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:41:30.821  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:41:30.821  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:41:30.821  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.821  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.821  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.821  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60cb294 removed from the list
10-07 05:41:30.822  5923  5939 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 05:41:30.822  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.822  5923  5942 D BtGatt.ScanManager: Starting BLE batch scan
,10-07 05:41:30.822  5923  5942 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 05:41:30.822  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.822  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfec439 added. We now have 3 listener(s)
,10-07 05:41:30.823  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-07 05:41:30.823  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.823  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-07 05:41:30.823  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.823  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8591a7e added. We now have 4 listener(s)
10-07 05:41:30.823  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.824  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-07 05:41:30.826  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 05:41:30.831  5923  5939 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 05:41:30.831  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:30.832  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-07 05:41:30.833  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-07 05:41:30.833  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
10-07 05:41:30.834  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.834  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a13c02c added. We now have 4 listener(s)
,10-07 05:41:30.835  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.836  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:41:30.836  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.836  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.837  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.837  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-07 05:41:30.837  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfe6af5 added. We now have 5 listener(s)
10-07 05:41:30.837  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.837  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:41:30.837  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-07 05:41:30.837  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-07 05:41:30.837  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-07 05:41:30.837  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-07 05:41:30.838  5923  5939 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-07 05:41:30.838  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:41:30.840  5643  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-07 05:41:30.840  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-07 05:41:30.844  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-07 05:41:30.844  5923  5939 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 05:41:30.844  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.845  5923  5942 D BtGatt.ScanManager: stopping BLe Batch
10-07 05:41:30.845  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-07 05:41:30.845  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-07 05:41:30.848  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-07 05:41:30.848  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-07 05:41:30.848  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-07 05:41:30.848  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-07 05:41:30.848  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-07 05:41:30.849  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:41:30.850  5923  5939 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 05:41:30.850  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.850  5923  5942 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-07 05:41:30.852  5923  5933 D BtGatt.GattService: registerClient() - UUID=76067d16-26be-4aec-9bc0-d3ea45262878
10-07 05:41:30.852  5923  5939 D BtGatt.GattService: onClientRegistered() - UUID=76067d16-26be-4aec-9bc0-d3ea45262878, clientIf=5
,10-07 05:41:30.852  5643  5653 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-07 05:41:30.853  5923  5950 D BtGatt.GattService: start scan with filters
10-07 05:41:30.854  5923  5939 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 05:41:30.855  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:41:30.855  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-07 05:41:30.856  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-07 05:41:30.856  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-07 05:41:30.856  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-07 05:41:30.856  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-07 05:41:30.856  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-07 05:41:30.856  5923  5942 D BtGatt.ScanManager: handling starting scan
10-07 05:41:30.856  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-07 05:41:30.857  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:41:30.858  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-07 05:41:30.858  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-07 05:41:30.859  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-07 05:41:30.861  5923  5939 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-07 05:41:30.861  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.861  5923  5942 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-07 05:41:30.862  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:41:30.862  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:30.862  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-07 05:41:30.862  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.862  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.862  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-07 05:41:30.862  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.863  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.863  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfec439 removed from the list
10-07 05:41:30.863  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.863  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8591a7e removed from the list
10-07 05:41:30.863  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
10-07 05:41:30.863  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.863  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-07 05:41:30.863  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-07 05:41:30.863  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.863  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.864  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.865  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.865  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.865  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8591a7e not in the list
10-07 05:41:30.865  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-07 05:41:30.865  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-07 05:41:30.865  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-07 05:41:30.865  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-07 05:41:30.865  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-07 05:41:30.865  5923  5939 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-07 05:41:30.865  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.865  5923  5942 D BtGatt.ScanManager: Starting BLE batch scan
10-07 05:41:30.865  5923  5942 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-07 05:41:30.866  5643  5689 D BluetoothAdapter: STATE_ON
10-07 05:41:30.866  5923  5934 D BtGatt.GattService: stopScan() - queue size =1
10-07 05:41:30.867  5923  5933 D BtGatt.GattService: unregisterClient() - clientIf=5
10-07 05:41:30.867  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-07 05:41:30.867  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-07 05:41:30.867  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-07 05:41:30.867  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-07 05:41:30.867  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-07 05:41:30.867  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-07 05:41:30.867  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-07 05:41:30.867  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-07 05:41:30.868  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-07 05:41:30.868  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-07 05:41:30.868  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-07 05:41:30.869  5643  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-07 05:41:30.869  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-07 05:41:30.870  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-07 05:41:30.871  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.871  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.871  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-07 05:41:30.871  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:41:30.871  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfe6af5 removed from the list
10-07 05:41:30.871  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.871  5643  5643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-07 05:41:30.871  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.871  5643  5643 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-07 05:41:30.871  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.872  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.872  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.872  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a13c02c removed from the list
10-07 05:41:30.872  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-07 05:41:30.872  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@217c171 added. We now have 3 listener(s)
,10-07 05:41:30.874  5923  5939 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-07 05:41:30.874  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.874  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:41:30.874  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.874  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.874  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.875  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73fb56 added. We now have 4 listener(s)
10-07 05:41:30.875  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-07 05:41:30.875  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-07 05:41:30.878  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-07 05:41:30.880  5923  5939 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-07 05:41:30.880  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-07 05:41:30.881  5643  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-07 05:41:30.883  5643  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-07 05:41:30.883  5643  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-07 05:41:30.883  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-07 05:41:30.883  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80be8c4 added. We now have 4 listener(s)
10-07 05:41:30.885  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.885  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-07 05:41:30.885  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-07 05:41:30.885  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-07 05:41:30.885  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-07 05:41:30.885  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99603ad added. We now have 5 listener(s)
10-07 05:41:30.885  5643  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-07 05:41:30.885  5643  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-07 05:41:30.885  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:30.885  5643  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-07 05:41:30.885  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.885  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.885  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-07 05:41:30.885  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.885  5923  5939 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-07 05:41:30.886  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.886  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.886  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@217c171 removed from the list
10-07 05:41:30.886  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.886  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73fb56 removed from the list
10-07 05:41:30.886  5923  5942 D BtGatt.ScanManager: stopping BLe Batch
10-07 05:41:30.886  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-07 05:41:30.886  5643  5689 D io.jxcore.node.ConnectivityMonitor: stop
,10-07 05:41:30.886  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.887  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.887  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.888  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.889  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.889  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.889  5643  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f73fb56 not in the list
10-07 05:41:30.889  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.889  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.890  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-07 05:41:30.890  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-07 05:41:30.890  5643  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-07 05:41:30.891  5643  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99603ad removed from the list
10-07 05:41:30.891  5643  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-07 05:41:30.891  5643  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-07 05:41:30.891  5643  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-07 05:41:30.891  5643  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-07 05:41:30.891  5643  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-07 05:41:30.891  5923  5939 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-07 05:41:30.891  5643  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@80be8c4 removed from the list
10-07 05:41:30.891  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-07 05:41:30.891  5923  5942 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-07 05:41:30.891  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-07 05:41:30.891  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-07 05:41:30.892  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-07 05:41:30.892  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:41:30.892  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is adver,tising: false - Stop operation: Should affect listening to advertisements only
10-07 05:41:30.892  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:30.896  5923  5939 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-07 05:41:30.896  5923  5939 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-07 05:41:31.193  5977  5977 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-07 05:41:31.270  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 05:41:31.301  5977  5977 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
10-07 05:41:31.303  5977  5977 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-07 05:41:31.318   927  2931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-07 05:41:31.318   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-07 05:41:31.318   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-07 05:41:31.322  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-07 05:41:31.337   927  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-07 05:41:31.351   509   918 D CommandListener: Setting iface cfg
,10-07 05:41:31.357   927  2931 D WifiStateMachine: Start Dhcp Watchdog 3
,10-07 05:41:31.366   927  5982 D DhcpClient: Receive thread started
,10-07 05:41:31.372  5643  5643 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-07 05:41:31.372   927  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-07 05:41:31.372   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 05:41:31.372   927  2933 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-07 05:41:31.463   927  2931 E native  : do suspend false
,10-07 05:41:31.484   927  5981 D DhcpClient: Broadcasting DHCPDISCOVER
,10-07 05:41:31.497   927  5982 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,10-07 05:41:31.498   927  5981 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,10-07 05:41:31.501   927  5981 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-07 05:41:31.513   927  5982 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-07 05:41:31.514   927  5981 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-07 05:41:31.518   509   918 D CommandListener: Setting iface cfg
10-07 05:41:31.523   927  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-07 05:41:31.529   927  5981 D DhcpClient: Scheduling renewal in 86399s
,10-07 05:41:31.546   927  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-07 05:41:31.547   927  2931 D WifiConfigStore: No blacklist allowed without epno enabled
10-07 05:41:31.549   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-07 05:41:31.550   927  2931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-07 05:41:31.560   927  2933 D ConnectivityService: Adding iface wlan0 to network 102
,10-07 05:41:31.597   927  2933 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-07 05:41:31.597   927  2933 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-07 05:41:31.599   927  2933 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-07 05:41:31.602   927  2933 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-07 05:41:31.604   927  2933 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-07 05:41:31.613   927  2933 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 05:41:31.618   927  2933 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-07 05:41:31.618   927  2933 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-07 05:41:31.618   927  2933 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-07 05:41:31.618   927  2933 D ConnectivityService:    accepting network in place of null
10-07 05:41:31.618   927  2931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-07 05:41:31.618   927  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-07 05:41:31.619   927  2933 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-07 05:41:31.630   927  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308111, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-07 05:41:31.641   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 05:41:31.664   509   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-07 05:41:31.668   927  2933 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-07 05:41:31.668   927  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-07 05:41:31.668  3715  3872 W QCNEJ   : |CORE| network available: 102
10-07 05:41:31.669   927  2933 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-07 05:41:31.670  3715  3872 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-07 05:41:31.671  3715  3872 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-07 05:41:31.671  3715  3872 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-07 05:41:31.673   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:41:31.678  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-07 05:41:31.682  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-07 05:41:31.685  5643  5643 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-07 05:41:31.687  5643  5643 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-07 05:41:31.694  5038  5061 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-07 05:41:31.694  5038  5061 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-07 05:41:31.694  5038  5061 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-07 05:41:31.694  5038  5061 E SarControlService: no key has been found,reset the power
10-07 05:41:31.695  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-07 05:41:31.695  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-07 05:41:31.695  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-07 05:41:31.695  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:41:31.695  5063  5063 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-07 05:41:31.696  5038  5075 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-07 05:41:31.697  5038  5075 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-07 05:41:31.697  5038  5075 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-07 05:41:31.697  4901  4901 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-07 05:41:31.699  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-07 05:41:31.700  3656  3656 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-07 05:41:31.699  5063  5063 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-07 05:41:31.704   927  5979 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-07 05:41:31.705  3656  3656 D SystemUpdateService: onCreate
10-07 05:41:31.709  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000f003000000000000ffffffff]
10-07 05:41:31.709  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 05:41:31.709  5063  5077 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-07 05:41:31.709  5063  5077 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@436434b HexData = [00000000f103000000000000ffffffff]
10-07 05:41:31.709  5063  5077 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-07 05:41:31.709  5063  5077 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-07 05:41:31.710  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 05:41:31.710  5038  5048 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-07 05:41:31.710  5063  5063 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-07 05:41:31.710  5038  5049 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-07 05:41:31.711  3656  3656 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-07 05:41:31.721  3656  3656 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-07 05:41:31.726  3656  5405 I iu.UploadsManager: num queued entries: 0
10-07 05:41:31.727  3656  5405 I iu.UploadsManager: num updated entries: 0
,10-07 05:41:31.728  3656  5405 I iu.SyncManager: NEXT; no task
,10-07 05:41:31.731  3656  5992 I SystemUpdateService: active receiver: enabled
,10-07 05:41:31.733  3656  3656 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-07 05:41:31.734  3656  3656 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-07 05:41:31.736  5775  5775 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-07 05:41:31.739  5775  5775 D SprintDMHelper: simOperator: 
10-07 05:41:31.739  5775  5775 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-07 05:41:31.754   927  5979 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 07 Oct 2016 09:41:31 GMT], X-Android-Received-Millis=[1475833291752], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475833291728]}
,10-07 05:41:31.754   927  2933 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-07 05:41:31.754   927  2933 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-07 05:41:31.754   927  2933 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-07 05:41:31.755   927  2933 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-07 05:41:31.764  3656  5992 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-07 05:41:31.778  3656  5992 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-07 05:41:31.778  3656  5992 I SystemUpdateService: now status is 0 (complete)
10-07 05:41:31.778  3656  5992 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-07 05:41:31.778  3656  5992 I SystemUpdateService: file has been verified
10-07 05:41:31.779  3656  5992 I SystemUpdateService: OTA package size = 21989297
,10-07 05:41:31.786  3656  5992 I SystemUpdateService: showing system update notification
,10-07 05:41:31.801  3656  3656 D SystemUpdateService: onDestroy
,10-07 05:41:31.834  5006  5997 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-07 05:41:33.042  5643  6004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 05:41:33.042  5643  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 05:41:33.836  5643  6004 W !!      : call onHalfStreamCopied
,10-07 05:41:33.836  5643  6004 I testCopyDataAndClose: closing input stream
,10-07 05:41:34.611  5643  6004 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 05:41:34.611  5643  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 05:41:34.611  5643  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 05:41:34.611  5643  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 05:41:34.611  5643  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 05:41:34.612  5643  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-07 05:41:34.612  5643  6004 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-07 05:41:34.612  5643  6004 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 05:41:34.612  5643  6004 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 05:41:34.612  5643  6004 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-07 05:41:34.612  5643  6004 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-07 05:41:38.390  5643  6005 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-07 05:41:38.390  5643  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 05:41:39.624   927  2933 D ConnectivityService: handlePromptUnvalidated 102
,10-07 05:41:40.390  5643  5689 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-07 05:41:40.390  5643  5689 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 05:41:40.390  5643  5689 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-07 05:41:40.518  5643  6005 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-07 05:41:40.518  5643  6005 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-07 05:41:40.518  5643  6005 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,10-07 05:41:40.534  5643  6006 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 05:41:40.534  5643  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-07 05:41:42.137  5643  6006 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-07 05:41:42.437   927  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-07 05:41:45.928  5643  6007 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].,
10-07 05:41:45.928  5643  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 05:41:45.928  5643  6007 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-07 05:41:45.928  5643  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 05:41:45.929  5643  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-07 05:41:45.929  5643  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-07 05:41:45.929  5643  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-07 05:41:45.929  5643  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-07 05:41:45.929  5643  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-07 05:41:45.929  5643  6007 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-07 05:41:45.929  5643  6007 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-07 05:41:45.930  5643  6007 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-07 05:41:45.930  5643  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-07 05:41:45.931  5643  5689 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-07 05:41:45.934  5643  6008 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 05:41:45.934  5643  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-07 05:41:45.935  5643  6008 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
10-07 05:41:45.935  5643  6008 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 05:41:45.935  5643  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-07 05:41:45.936  5643  6008 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-07 05:41:45.936  5643  6008 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-07 05:41:45.936  5643  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-07 05:41:45.941  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-07 05:41:45.941  5643  5689 I jxcore-log: 
10-07 05:41:45.941  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-07 05:41:45.941  5643  5689 I jxcore-log: 
10-07 05:41:45.942  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-07 05:41:45.942  5643  5689 I jxcore-log: 
,10-07 05:41:45.942  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-07 05:41:45.942  5643  5689 I jxcore-log: 
10-07 05:41:45.943  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'Total duration:  90779'
10-07 05:41:45.943  5643  5689 I jxcore-log: 
10-07 05:41:45.945  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-07 05:41:45.945  5643  5689 I jxcore-log: 
,10-07 05:41:45.950  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.950  5643  5689 I jxcore-log: 
,10-07 05:41:45.951  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.951  5643  5689 I jxcore-log: 
10-07 05:41:45.952  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.952  5643  5689 I jxcore-log: 
,10-07 05:41:45.952  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.952  5643  5689 I jxcore-log: 
10-07 05:41:45.952  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-07 05:41:45.952  5643  5689 I jxcore-log: 
10-07 05:41:45.953  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 05:41:45.953  5643  5689 I jxcore-log: 
10-07 05:41:45.953  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.953  5643  5689 I jxcore-log: 
,10-07 05:41:45.953  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.953  5643  5689 I jxcore-log: 
10-07 05:41:45.953  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-07 05:41:45.953  5643  5689 I jxcore-log: 
10-07 05:41:45.954  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 05:41:45.954  5643  5689 I jxcore-log: 
10-07 05:41:45.954  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 05:41:45.954  5643  5689 I jxcore-log: 
10-07 05:41:45.954  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.954  5643  5689 I jxcore-log: 
10-07 05:41:45.954  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.954  5643  5689 I jxcore-log: 
10-07 05:41:45.955  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.955  5643  5689 I jxcore-log: 
10-07 05:41:45.955  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.955  5643  5689 I jxcore-log: 
,10-07 05:41:45.955  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.955  5643  5689 I jxcore-log: 
10-07 05:41:45.956  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.956  5643  5689 I jxcore-log: 
10-07 05:41:45.956  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.956  5643  5689 I jxcore-log: 
10-07 05:41:45.956  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.956  5643  5689 I jxcore-log: 
10-07 05:41:45.956  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.956  5643  5689 I jxcore-log: 
,10-07 05:41:45.957  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.957  5643  5689 I jxcore-log: 
10-07 05:41:45.957  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.957  5643  5689 I jxcore-log: 
10-07 05:41:45.957  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.957  5643  5689 I jxcore-log: 
10-07 05:41:45.958  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.958  5643  5689 I jxcore-log: 
,10-07 05:41:45.959  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.959  5643  5689 I jxcore-log: 
10-07 05:41:45.959  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.959  5643  5689 I jxcore-log: 
10-07 05:41:45.959  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.959  5643  5689 I jxcore-log: 
10-07 05:41:45.960  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.960  5643  5689 I jxcore-log: 
,10-07 05:41:45.960  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.960  5643  5689 I jxcore-log: 
10-07 05:41:45.960  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.960  5643  5689 I jxcore-log: 
10-07 05:41:45.960  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.960  5643  5689 I jxcore-log: 
10-07 05:41:45.960  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.960  5643  5689 I jxcore-log: 
10-07 05:41:45.961  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.961  5643  5689 I jxcore-log: 
10-07 05:41:45.961  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.961  5643  5689 I jxcore-log: 
,10-07 05:41:45.961  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.961  5643  5689 I jxcore-log: 
10-07 05:41:45.961  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.961  5643  5689 I jxcore-log: 
10-07 05:41:45.962  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.962  5643  5689 I jxcore-log: 
10-07 05:41:45.962  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.962  5643  5689 I jxcore-log: 
,10-07 05:41:45.962  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.962  5643  5689 I jxcore-log: 
10-07 05:41:45.962  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-07 05:41:45.962  5643  5689 I jxcore-log: 
10-07 05:41:45.962  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.962  5643  5689 I jxcore-log: 
10-07 05:41:45.963  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.963  5643  5689 I jxcore-log: 
,10-07 05:41:45.963  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.963  5643  5689 I jxcore-log: 
10-07 05:41:45.963  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.963  5643  5689 I jxcore-log: 
10-07 05:41:45.963  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.963  5643  5689 I jxcore-log: 
10-07 05:41:45.963  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-07 05:41:45.963  5643  5689 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,10-07 05:41:45.964  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.964  5643  5689 I jxcore-log: 
10-07 05:41:45.964  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.964  5643  5689 I jxcore-log: 
10-07 05:41:45.964  5643  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-07 05:41:45.964  5643  5689 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-07 05:41:45.964  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-07 05:41:45.964  5643  5689 I jxcore-log: 
10-07 05:41:45.965  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 05:41:45.965  5643  5689 I jxcore-log: 
10-07 05:41:45.965  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 05:41:45.965  5643  5689 I jxcore-log: 
,10-07 05:41:45.965  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-07 05:41:45.965  5643  5689 I jxcore-log: 
10-07 05:41:45.965  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.965  5643  5689 I jxcore-log: 
10-07 05:41:45.965  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-07 05:41:45.965  5643  5689 I jxcore-log: 
10-07 05:41:45.968  5643  5643 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-07 05:41:45.971  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-07 05:41:45.971  5643  5689 I jxcore-log: 
,10-07 05:41:45.971  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - WARN testUtils: 'myNameCallback not set!'
10-07 05:41:45.971  5643  5689 I jxcore-log: 
10-07 05:41:45.972  5643  5689 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-07 05:41:45.973  5643  5689 I jxcore-log: 2016-10-07 09:41:45 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-07 05:41:45.973  5643  5689 I jxcore-log: 
,10-07 05:41:47.971  5643  5689 I jxcore-log: 2016-10-07 09:41:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-07 05:41:47.971  5643  5689 I jxcore-log: 
,10-07 05:41:48.301  5643  5689 I jxcore-log: 2016-10-07 09:41:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-07 05:41:48.301  5643  5689 I jxcore-log: 
,10-07 05:41:48.316  5643  5689 I jxcore-log: 2016-10-07 09:41:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-07 05:41:48.316  5643  5689 I jxcore-log: 
,10-07 05:41:49.400  5643  5689 I jxcore-log: 2016-10-07 09:41:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-07 05:41:49.400  5643  5689 I jxcore-log: 
,10-07 05:41:49.559  5643  5689 I jxcore-log: 2016-10-07 09:41:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-07 05:41:49.559  5643  5689 I jxcore-log: 
,10-07 05:41:49.564  5643  5689 I jxcore-log: 2016-10-07 09:41:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-07 05:41:49.564  5643  5689 I jxcore-log: 
,10-07 05:41:49.569  5643  5689 I jxcore-log: 2016-10-07 09:41:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-07 05:41:49.569  5643  5689 I jxcore-log: 
,10-07 05:41:50.113  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-07 05:41:50.113  5643  5689 I jxcore-log: 
,10-07 05:41:50.164  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-07 05:41:50.164  5643  5689 I jxcore-log: 
,10-07 05:41:50.177  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-07 05:41:50.177  5643  5689 I jxcore-log: 
,10-07 05:41:50.181  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-07 05:41:50.181  5643  5689 I jxcore-log: 
,10-07 05:41:50.457  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-07 05:41:50.457  5643  5689 I jxcore-log: 
,10-07 05:41:50.582  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-07 05:41:50.582  5643  5689 I jxcore-log: 
,10-07 05:41:50.814  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-07 05:41:50.814  5643  5689 I jxcore-log: 
,10-07 05:41:50.824  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-07 05:41:50.824  5643  5689 I jxcore-log: 
,10-07 05:41:50.829  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-07 05:41:50.829  5643  5689 I jxcore-log: 
,10-07 05:41:50.960  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-07 05:41:50.960  5643  5689 I jxcore-log: 
,10-07 05:41:50.968  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-07 05:41:50.968  5643  5689 I jxcore-log: 
,10-07 05:41:50.995  5643  5689 I jxcore-log: 2016-10-07 09:41:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-07 05:41:50.995  5643  5689 I jxcore-log: 
,10-07 05:41:51.029  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-07 05:41:51.029  5643  5689 I jxcore-log: 
,10-07 05:41:51.035  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-07 05:41:51.035  5643  5689 I jxcore-log: 
,10-07 05:41:51.041  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-07 05:41:51.041  5643  5689 I jxcore-log: 
,10-07 05:41:51.054  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-07 05:41:51.054  5643  5689 I jxcore-log: 
,10-07 05:41:51.058  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-07 05:41:51.058  5643  5689 I jxcore-log: 
,10-07 05:41:51.063  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-07 05:41:51.063  5643  5689 I jxcore-log: 
,10-07 05:41:51.068  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-07 05:41:51.068  5643  5689 I jxcore-log: 
,10-07 05:41:51.080  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-07 05:41:51.080  5643  5689 I jxcore-log: 
,10-07 05:41:51.099  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-07 05:41:51.099  5643  5689 I jxcore-log: 
,10-07 05:41:51.107  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-07 05:41:51.107  5643  5689 I jxcore-log: 
,10-07 05:41:51.118  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-07 05:41:51.118  5643  5689 I jxcore-log: 
,10-07 05:41:51.127  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-07 05:41:51.127  5643  5689 I jxcore-log: 
,10-07 05:41:51.138  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-07 05:41:51.138  5643  5689 I jxcore-log: 
,10-07 05:41:51.148  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-07 05:41:51.148  5643  5689 I jxcore-log: 
,10-07 05:41:51.153  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-07 05:41:51.153  5643  5689 I jxcore-log: 
,10-07 05:41:51.170  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUpdatingAdvertisingAndParallelDataTransferCoordinated.js'
10-07 05:41:51.170  5643  5689 I jxcore-log: 
,10-07 05:41:51.263  5643  5689 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-07 05:41:51.264  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - INFO testUtils: 'BLE multiple advertisement supported'
10-07 05:41:51.264  5643  5689 I jxcore-log: 
,10-07 05:41:51.363  5643  5689 I jxcore-log: 2016-10-07 09:41:51 - DEBUG CoordinatedClient: 'connected to the test server'
10-07 05:41:51.363  5643  5689 I jxcore-log: 
,10-07 05:41:51.867  5643  5689 I jxcore-log: TAP version 13
10-07 05:41:51.867  5643  5689 I jxcore-log: 
,10-07 05:41:51.909  5643  5689 I jxcore-log: # setup
10-07 05:41:51.909  5643  5689 I jxcore-log: 
,10-07 05:41:52.490  5643  5689 I jxcore-log: # calling createNativeListener directly rejects
10-07 05:41:52.490  5643  5689 I jxcore-log: 
,10-07 05:41:52.588   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-07 05:41:52.589   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-07 05:41:52.932  5643  5689 I jxcore-log: 2016-10-07 09:41:52 - DEBUG createNativeListener: 'creating native server'
10-07 05:41:52.932  5643  5689 I jxcore-log: 
,10-07 05:41:52.939  5643  5689 I jxcore-log: 2016-10-07 09:41:52 - DEBUG createNativeListener: 'listening 38186'
10-07 05:41:52.939  5643  5689 I jxcore-log: 
,10-07 05:41:52.947  5643  5689 I jxcore-log: ok 1 Should throw
10-07 05:41:52.947  5643  5689 I jxcore-log: 
,10-07 05:41:52.958  5643  5689 I jxcore-log: # teardown
10-07 05:41:52.958  5643  5689 I jxcore-log: 
,10-07 05:41:53.275  5643  5689 I jxcore-log: # setup
10-07 05:41:53.275  5643  5689 I jxcore-log: 
,10-07 05:41:53.897  5643  5689 I jxcore-log: # emits incomingConnectionState
10-07 05:41:53.897  5643  5689 I jxcore-log: 
,10-07 05:41:54.093  5643  5689 I jxcore-log: 2016-10-07 09:41:54 - DEBUG createNativeListener: 'creating native server'
10-07 05:41:54.093  5643  5689 I jxcore-log: 
,10-07 05:41:54.098  5643  5689 I jxcore-log: 2016-10-07 09:41:54 - DEBUG createNativeListener: 'listening 44165'
10-07 05:41:54.098  5643  5689 I jxcore-log: 
,10-07 05:41:54.107  5643  5689 I jxcore-log: 2016-10-07 09:41:54 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:41:54.107  5643  5689 I jxcore-log: 
,10-07 05:41:54.112  5643  5689 I jxcore-log: 2016-10-07 09:41:54 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:41:54.112  5643  5689 I jxcore-log: 
,10-07 05:41:54.121  5643  5689 I jxcore-log: 2016-10-07 09:41:54 - DEBUG createNativeListener: 'new mux'
10-07 05:41:54.121  5643  5689 I jxcore-log: 
,10-07 05:41:54.126  5643  5689 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-07 05:41:54.126  5643  5689 I jxcore-log: 
,10-07 05:41:54.145  5643  5689 I jxcore-log: 2016-10-07 09:41:54 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:41:54.145  5643  5689 I jxcore-log: 
,10-07 05:41:54.146  5643  5689 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-07 05:41:54.146  5643  5689 I jxcore-log: 
,10-07 05:41:54.154  5643  5689 I jxcore-log: # teardown
10-07 05:41:54.154  5643  5689 I jxcore-log: 
,10-07 05:41:55.018  5643  5689 I jxcore-log: # setup
10-07 05:41:55.018  5643  5689 I jxcore-log: 
,10-07 05:41:55.335  5643  5689 I jxcore-log: # emits routerPortConnectionFailed
10-07 05:41:55.335  5643  5689 I jxcore-log: 
,10-07 05:41:56.194  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'creating native server'
10-07 05:41:56.194  5643  5689 I jxcore-log: 
,10-07 05:41:56.198  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'listening 38236'
10-07 05:41:56.198  5643  5689 I jxcore-log: 
,10-07 05:41:56.205  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:41:56.205  5643  5689 I jxcore-log: 
,10-07 05:41:56.206  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:41:56.206  5643  5689 I jxcore-log: 
,10-07 05:41:56.208  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'new mux'
10-07 05:41:56.208  5643  5689 I jxcore-log: 
,10-07 05:41:56.235  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'new stream: '
10-07 05:41:56.235  5643  5689 I jxcore-log: 
,10-07 05:41:56.238  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:41:56.238  5643  5689 I jxcore-log: 
,10-07 05:41:56.242  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: ' $c@net.js:837:7
10-07 05:41:56.242  5643  5689 I jxcore-log: $09@net.js:829:13
10-07 05:41:56.242  5643  5689 I jxcore-log: '
10-07 05:41:56.242  5643  5689 I jxcore-log: 
,10-07 05:41:56.243  5643  5689 I jxcore-log: ok 4 tried to connect to right port
10-07 05:41:56.243  5643  5689 I jxcore-log: 
,10-07 05:41:56.244  5643  5689 I jxcore-log: ok 5 failed due to refused connection
10-07 05:41:56.244  5643  5689 I jxcore-log: 
10-07 05:41:56.244  5643  5689 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-07 05:41:56.244  5643  5689 I jxcore-log: 
,10-07 05:41:56.249  5643  5689 I jxcore-log: # teardown
10-07 05:41:56.249  5643  5689 I jxcore-log: 
,10-07 05:41:56.251  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'stream close:'
10-07 05:41:56.251  5643  5689 I jxcore-log: 
,10-07 05:41:56.689  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'mux close'
10-07 05:41:56.689  5643  5689 I jxcore-log: 
,10-07 05:41:56.695  5643  5689 I jxcore-log: 2016-10-07 09:41:56 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:41:56.695  5643  5689 I jxcore-log: 
,10-07 05:41:56.707  5643  5689 I jxcore-log: # setup
10-07 05:41:56.707  5643  5689 I jxcore-log: 
,10-07 05:41:57.406  5643  5689 I jxcore-log: # native server connections all up
10-07 05:41:57.406  5643  5689 I jxcore-log: 
,10-07 05:41:57.807  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'creating native server'
10-07 05:41:57.807  5643  5689 I jxcore-log: 
,10-07 05:41:57.815  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'listening 38315'
10-07 05:41:57.815  5643  5689 I jxcore-log: 
,10-07 05:41:57.824  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:41:57.824  5643  5689 I jxcore-log: 
,10-07 05:41:57.825  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:41:57.825  5643  5689 I jxcore-log: 
,10-07 05:41:57.827  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'new mux'
10-07 05:41:57.827  5643  5689 I jxcore-log: 
,10-07 05:41:57.857  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'new stream: '
10-07 05:41:57.857  5643  5689 I jxcore-log: 
,10-07 05:41:57.860  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:41:57.860  5643  5689 I jxcore-log: 
,10-07 05:41:57.862  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'new stream: '
10-07 05:41:57.862  5643  5689 I jxcore-log: 
,10-07 05:41:57.864  5643  5689 I jxcore-log: 2016-10-07 09:41:57 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:41:57.864  5643  5689 I jxcore-log: 
,10-07 05:41:57.883  5643  5689 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-07 05:41:57.883  5643  5689 I jxcore-log: 
,10-07 05:41:57.884  5643  5689 I jxcore-log: ok 8 Send/recvd #1 should be same
10-07 05:41:57.884  5643  5689 I jxcore-log: 
,10-07 05:41:57.886  5643  5689 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-07 05:41:57.886  5643  5689 I jxcore-log: 
10-07 05:41:57.887  5643  5689 I jxcore-log: ok 10 Send/recvd #2 should be same
10-07 05:41:57.887  5643  5689 I jxcore-log: 
,10-07 05:41:57.890  5643  5689 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-07 05:41:57.890  5643  5689 I jxcore-log: 
,10-07 05:41:57.897  5643  5689 I jxcore-log: # teardown
10-07 05:41:57.897  5643  5689 I jxcore-log: 
,10-07 05:41:58.728  5643  5689 I jxcore-log: 2016-10-07 09:41:58 - DEBUG createNativeListener: 'stream close:'
10-07 05:41:58.728  5643  5689 I jxcore-log: 
,10-07 05:41:58.733  5643  5689 I jxcore-log: 2016-10-07 09:41:58 - DEBUG createNativeListener: 'stream close:'
10-07 05:41:58.733  5643  5689 I jxcore-log: 
,10-07 05:41:58.738  5643  5689 I jxcore-log: 2016-10-07 09:41:58 - DEBUG createNativeListener: 'mux close'
10-07 05:41:58.738  5643  5689 I jxcore-log: 
,10-07 05:41:58.745  5643  5689 I jxcore-log: 2016-10-07 09:41:58 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:41:58.745  5643  5689 I jxcore-log: 
,10-07 05:41:58.759  5643  5689 I jxcore-log: # setup
10-07 05:41:58.759  5643  5689 I jxcore-log: 
,10-07 05:41:59.150  5643  5689 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-07 05:41:59.150  5643  5689 I jxcore-log: 
,10-07 05:41:59.861  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'creating native server'
10-07 05:41:59.861  5643  5689 I jxcore-log: 
,10-07 05:41:59.865  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'listening 44644'
10-07 05:41:59.865  5643  5689 I jxcore-log: 
,10-07 05:41:59.874  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:41:59.874  5643  5689 I jxcore-log: 
,10-07 05:41:59.875  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:41:59.875  5643  5689 I jxcore-log: 
,10-07 05:41:59.879  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'new mux'
10-07 05:41:59.879  5643  5689 I jxcore-log: 
,10-07 05:41:59.889  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'new stream: '
10-07 05:41:59.889  5643  5689 I jxcore-log: 
,10-07 05:41:59.892  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:41:59.892  5643  5689 I jxcore-log: 
,10-07 05:41:59.903  5643  5689 I jxcore-log: 2016-10-07 09:41:59 - DEBUG createNativeListener: 'stream close:'
10-07 05:41:59.903  5643  5689 I jxcore-log: 
,10-07 05:41:59.913  5643  5689 I jxcore-log: ok 12 socket shouldn't close until after stream
10-07 05:41:59.913  5643  5689 I jxcore-log: 
,10-07 05:41:59.913  5643  5689 I jxcore-log: ok 13 incoming remains open
10-07 05:41:59.913  5643  5689 I jxcore-log: 
,10-07 05:41:59.918  5643  5689 I jxcore-log: # teardown
10-07 05:41:59.918  5643  5689 I jxcore-log: 
,10-07 05:42:00.368  5643  5689 I jxcore-log: 2016-10-07 09:42:00 - DEBUG createNativeListener: 'mux close'
10-07 05:42:00.368  5643  5689 I jxcore-log: 
,10-07 05:42:00.377  5643  5689 I jxcore-log: 2016-10-07 09:42:00 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:00.377  5643  5689 I jxcore-log: 
,10-07 05:42:00.388  5643  5689 I jxcore-log: # setup
10-07 05:42:00.388  5643  5689 I jxcore-log: 
,10-07 05:42:01.099  5643  5689 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-07 05:42:01.099  5643  5689 I jxcore-log: 
,10-07 05:42:01.498  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'creating native server'
10-07 05:42:01.498  5643  5689 I jxcore-log: 
,10-07 05:42:01.504  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'listening 44708'
10-07 05:42:01.504  5643  5689 I jxcore-log: 
,10-07 05:42:01.514  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:01.514  5643  5689 I jxcore-log: 
,10-07 05:42:01.517  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:01.517  5643  5689 I jxcore-log: 
,10-07 05:42:01.520  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'new mux'
10-07 05:42:01.520  5643  5689 I jxcore-log: 
,10-07 05:42:01.537  5643  5689 I jxcore-log: ok 14 we should not have gotten an error
10-07 05:42:01.537  5643  5689 I jxcore-log: 
,10-07 05:42:01.544  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:01.544  5643  5689 I jxcore-log: 
,10-07 05:42:01.552  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:01.552  5643  5689 I jxcore-log: 
,10-07 05:42:01.566  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:01.566  5643  5689 I jxcore-log: 
,10-07 05:42:01.573  5643  5689 I jxcore-log: 2016-10-07 09:42:01 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:01.573  5643  5689 I jxcore-log: 
,10-07 05:42:01.582  5643  5689 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-07 05:42:01.582  5643  5689 I jxcore-log: 
,10-07 05:42:01.583  5643  5689 I jxcore-log: ok 16 incoming is cleaned up
10-07 05:42:01.583  5643  5689 I jxcore-log: 
,10-07 05:42:01.594  5643  5689 I jxcore-log: # teardown
10-07 05:42:01.594  5643  5689 I jxcore-log: 
,10-07 05:42:02.327  5643  5689 I jxcore-log: # setup
10-07 05:42:02.327  5643  5689 I jxcore-log: 
,10-07 05:42:02.376  5643  5689 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-07 05:42:02.376  5643  5689 I jxcore-log: 
,10-07 05:42:02.416  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating native server'
10-07 05:42:02.416  5643  5689 I jxcore-log: 
,10-07 05:42:02.421  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'listening 49102'
10-07 05:42:02.421  5643  5689 I jxcore-log: 
,10-07 05:42:02.428  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.428  5643  5689 I jxcore-log: 
,10-07 05:42:02.430  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.430  5643  5689 I jxcore-log: 
,10-07 05:42:02.433  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.433  5643  5689 I jxcore-log: 
,10-07 05:42:02.444  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.444  5643  5689 I jxcore-log: 
,10-07 05:42:02.446  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.446  5643  5689 I jxcore-log: 
,10-07 05:42:02.459  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:02.459  5643  5689 I jxcore-log: 
,10-07 05:42:02.467  5643  5689 I jxcore-log: ok 17 stream was closed
10-07 05:42:02.467  5643  5689 I jxcore-log: 
,10-07 05:42:02.468  5643  5689 I jxcore-log: ok 18 incoming should survive
10-07 05:42:02.468  5643  5689 I jxcore-log: 
10-07 05:42:02.468  5643  5689 I jxcore-log: ok 19 mux should have no streams
10-07 05:42:02.468  5643  5689 I jxcore-log: 
,10-07 05:42:02.474  5643  5689 I jxcore-log: # teardown
10-07 05:42:02.474  5643  5689 I jxcore-log: 
,10-07 05:42:02.512  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'mux close'
10-07 05:42:02.512  5643  5689 I jxcore-log: 
,10-07 05:42:02.523  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:02.523  5643  5689 I jxcore-log: 
,10-07 05:42:02.536  5643  5689 I jxcore-log: # setup
10-07 05:42:02.536  5643  5689 I jxcore-log: 
,10-07 05:42:02.605  5643  5689 I jxcore-log: # native server - closing the whole server cleans everything up
10-07 05:42:02.605  5643  5689 I jxcore-log: 
,10-07 05:42:02.651  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating native server'
10-07 05:42:02.651  5643  5689 I jxcore-log: 
,10-07 05:42:02.658  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'listening 46266'
10-07 05:42:02.658  5643  5689 I jxcore-log: 
,10-07 05:42:02.667  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.667  5643  5689 I jxcore-log: 
,10-07 05:42:02.668  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.668  5643  5689 I jxcore-log: 
,10-07 05:42:02.670  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.670  5643  5689 I jxcore-log: 
,10-07 05:42:02.683  5643  5689 I jxcore-log: ok 20 we should not have gotten an error
10-07 05:42:02.683  5643  5689 I jxcore-log: 
,10-07 05:42:02.689  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.689  5643  5689 I jxcore-log: 
,10-07 05:42:02.692  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.692  5643  5689 I jxcore-log: 
,10-07 05:42:02.700  5643  5689 I jxcore-log: ok 21 Buffers are identical
10-07 05:42:02.700  5643  5689 I jxcore-log: 
,10-07 05:42:02.702  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:02.702  5643  5689 I jxcore-log: 
,10-07 05:42:02.705  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'mux close'
10-07 05:42:02.705  5643  5689 I jxcore-log: 
,10-07 05:42:02.708  5643  5689 I jxcore-log: ok 22 native server is nulled out
10-07 05:42:02.708  5643  5689 I jxcore-log: 
,10-07 05:42:02.708  5643  5689 I jxcore-log: ok 23 native server should be closed
10-07 05:42:02.708  5643  5689 I jxcore-log: 
10-07 05:42:02.708  5643  5689 I jxcore-log: ok 24 incoming has been removed
10-07 05:42:02.708  5643  5689 I jxcore-log: 
10-07 05:42:02.708  5643  5689 I jxcore-log: ok 25 Incoming should be done
10-07 05:42:02.708  5643  5689 I jxcore-log: 
10-07 05:42:02.709  5643  5689 I jxcore-log: ok 26 The mux object should be closed
10-07 05:42:02.709  5643  5689 I jxcore-log: 
10-07 05:42:02.709  5643  5689 I jxcore-log: ok 27 The mux stream should be closed
10-07 05:42:02.709  5643  5689 I jxcore-log: 
10-07 05:42:02.710  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:02.710  5643  5689 I jxcore-log: 
,10-07 05:42:02.722  5643  5689 I jxcore-log: # teardown
10-07 05:42:02.722  5643  5689 I jxcore-log: 
,10-07 05:42:02.763  5643  5689 I jxcore-log: # setup
10-07 05:42:02.763  5643  5689 I jxcore-log: 
,10-07 05:42:02.793  5643  5689 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-07 05:42:02.793  5643  5689 I jxcore-log: 
,10-07 05:42:02.848  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating native server'
10-07 05:42:02.848  5643  5689 I jxcore-log: 
,10-07 05:42:02.852  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'listening 43528'
10-07 05:42:02.852  5643  5689 I jxcore-log: 
,10-07 05:42:02.877  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.877  5643  5689 I jxcore-log: 
,10-07 05:42:02.878  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.878  5643  5689 I jxcore-log: 
10-07 05:42:02.879  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.879  5643  5689 I jxcore-log: 
,10-07 05:42:02.881  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.881  5643  5689 I jxcore-log: 
10-07 05:42:02.882  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.882  5643  5689 I jxcore-log: 
10-07 05:42:02.883  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.883  5643  5689 I jxcore-log: 
10-07 05:42:02.885  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.885  5643  5689 I jxcore-log: 
,10-07 05:42:02.886  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.886  5643  5689 I jxcore-log: 
,10-07 05:42:02.887  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.887  5643  5689 I jxcore-log: 
,10-07 05:42:02.892  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.892  5643  5689 I jxcore-log: 
,10-07 05:42:02.893  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.893  5643  5689 I jxcore-log: 
10-07 05:42:02.894  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.894  5643  5689 I jxcore-log: 
,10-07 05:42:02.897  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.897  5643  5689 I jxcore-log: 
,10-07 05:42:02.898  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.898  5643  5689 I jxcore-log: 
,10-07 05:42:02.899  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.899  5643  5689 I jxcore-log: 
,10-07 05:42:02.901  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.901  5643  5689 I jxcore-log: 
,10-07 05:42:02.902  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.902  5643  5689 I jxcore-log: 
,10-07 05:42:02.903  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.903  5643  5689 I jxcore-log: 
,10-07 05:42:02.911  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.911  5643  5689 I jxcore-log: 
,10-07 05:42:02.911  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.911  5643  5689 I jxcore-log: 
,10-07 05:42:02.912  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.912  5643  5689 I jxcore-log: 
,10-07 05:42:02.913  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.913  5643  5689 I jxcore-log: 
,10-07 05:42:02.913  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.913  5643  5689 I jxcore-log: 
10-07 05:42:02.914  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.914  5643  5689 I jxcore-log: 
,10-07 05:42:02.915  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.915  5643  5689 I jxcore-log: 
,10-07 05:42:02.916  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.916  5643  5689 I jxcore-log: 
10-07 05:42:02.916  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.916  5643  5689 I jxcore-log: 
,10-07 05:42:02.917  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:02.917  5643  5689 I jxcore-log: 
,10-07 05:42:02.918  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:02.918  5643  5689 I jxcore-log: 
10-07 05:42:02.918  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new mux'
10-07 05:42:02.918  5643  5689 I jxcore-log: 
,10-07 05:42:02.971  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.971  5643  5689 I jxcore-log: 
,10-07 05:42:02.973  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.973  5643  5689 I jxcore-log: 
,10-07 05:42:02.975  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.975  5643  5689 I jxcore-log: 
,10-07 05:42:02.976  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.976  5643  5689 I jxcore-log: 
,10-07 05:42:02.977  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.977  5643  5689 I jxcore-log: 
,10-07 05:42:02.978  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.978  5643  5689 I jxcore-log: 
,10-07 05:42:02.979  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.979  5643  5689 I jxcore-log: 
,10-07 05:42:02.980  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.980  5643  5689 I jxcore-log: 
,10-07 05:42:02.981  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.981  5643  5689 I jxcore-log: 
,10-07 05:42:02.983  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.983  5643  5689 I jxcore-log: 
10-07 05:42:02.983  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.983  5643  5689 I jxcore-log: 
,10-07 05:42:02.984  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.984  5643  5689 I jxcore-log: 
,10-07 05:42:02.985  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.985  5643  5689 I jxcore-log: 
10-07 05:42:02.986  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.986  5643  5689 I jxcore-log: 
,10-07 05:42:02.987  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.987  5643  5689 I jxcore-log: 
10-07 05:42:02.987  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.987  5643  5689 I jxcore-log: 
,10-07 05:42:02.989  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.989  5643  5689 I jxcore-log: 
,10-07 05:42:02.990  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.990  5643  5689 I jxcore-log: 
,10-07 05:42:02.990  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.990  5643  5689 I jxcore-log: 
10-07 05:42:02.991  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.991  5643  5689 I jxcore-log: 
,10-07 05:42:02.992  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.992  5643  5689 I jxcore-log: 
10-07 05:42:02.993  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.993  5643  5689 I jxcore-log: 
10-07 05:42:02.993  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.993  5643  5689 I jxcore-log: 
,10-07 05:42:02.994  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.994  5643  5689 I jxcore-log: 
10-07 05:42:02.996  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.996  5643  5689 I jxcore-log: 
,10-07 05:42:02.997  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.997  5643  5689 I jxcore-log: 
10-07 05:42:02.997  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.997  5643  5689 I jxcore-log: 
10-07 05:42:02.998  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.998  5643  5689 I jxcore-log: 
,10-07 05:42:02.998  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:02.998  5643  5689 I jxcore-log: 
10-07 05:42:02.999  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:02.999  5643  5689 I jxcore-log: 
,10-07 05:42:03.000  5643  5689 I jxcore-log: 2016-10-07 09:42:02 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.000  5643  5689 I jxcore-log: 
10-07 05:42:03.000  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.000  5643  5689 I jxcore-log: 
,10-07 05:42:03.001  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.001  5643  5689 I jxcore-log: 
,10-07 05:42:03.002  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.002  5643  5689 I jxcore-log: 
10-07 05:42:03.003  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.003  5643  5689 I jxcore-log: 
,10-07 05:42:03.003  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.003  5643  5689 I jxcore-log: 
10-07 05:42:03.004  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.004  5643  5689 I jxcore-log: 
,10-07 05:42:03.005  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.005  5643  5689 I jxcore-log: 
10-07 05:42:03.005  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.005  5643  5689 I jxcore-log: 
,10-07 05:42:03.006  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.006  5643  5689 I jxcore-log: 
10-07 05:42:03.007  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.007  5643  5689 I jxcore-log: 
,10-07 05:42:03.007  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.007  5643  5689 I jxcore-log: 
,10-07 05:42:03.008  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.008  5643  5689 I jxcore-log: 
10-07 05:42:03.009  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.009  5643  5689 I jxcore-log: 
,10-07 05:42:03.009  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.009  5643  5689 I jxcore-log: 
10-07 05:42:03.010  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.010  5643  5689 I jxcore-log: 
,10-07 05:42:03.011  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.011  5643  5689 I jxcore-log: 
10-07 05:42:03.011  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.011  5643  5689 I jxcore-log: 
,10-07 05:42:03.017  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.017  5643  5689 I jxcore-log: 
,10-07 05:42:03.018  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.018  5643  5689 I jxcore-log: 
,10-07 05:42:03.019  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.019  5643  5689 I jxcore-log: 
10-07 05:42:03.020  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.020  5643  5689 I jxcore-log: 
,10-07 05:42:03.020  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.020  5643  5689 I jxcore-log: 
10-07 05:42:03.021  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.021  5643  5689 I jxcore-log: 
,10-07 05:42:03.021  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.021  5643  5689 I jxcore-log: 
,10-07 05:42:03.022  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.022  5643  5689 I jxcore-log: 
10-07 05:42:03.023  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.023  5643  5689 I jxcore-log: 
,10-07 05:42:03.024  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.024  5643  5689 I jxcore-log: 
10-07 05:42:03.024  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.024  5643  5689 I jxcore-log: 
10-07 05:42:03.025  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.025  5643  5689 I jxcore-log: 
,10-07 05:42:03.026  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.026  5643  5689 I jxcore-log: 
,10-07 05:42:03.027  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.027  5643  5689 I jxcore-log: 
10-07 05:42:03.027  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.027  5643  5689 I jxcore-log: 
,10-07 05:42:03.028  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.028  5643  5689 I jxcore-log: 
10-07 05:42:03.029  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.029  5643  5689 I jxcore-log: 
10-07 05:42:03.029  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.029  5643  5689 I jxcore-log: 
,10-07 05:42:03.030  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.030  5643  5689 I jxcore-log: 
10-07 05:42:03.031  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.031  5643  5689 I jxcore-log: 
,10-07 05:42:03.031  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.031  5643  5689 I jxcore-log: 
10-07 05:42:03.032  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.032  5643  5689 I jxcore-log: 
10-07 05:42:03.032  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.032  5643  5689 I jxcore-log: 
,10-07 05:42:03.033  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.033  5643  5689 I jxcore-log: 
10-07 05:42:03.034  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.034  5643  5689 I jxcore-log: 
,10-07 05:42:03.035  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.035  5643  5689 I jxcore-log: 
10-07 05:42:03.036  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.036  5643  5689 I jxcore-log: 
10-07 05:42:03.036  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.036  5643  5689 I jxcore-log: 
,10-07 05:42:03.037  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.037  5643  5689 I jxcore-log: 
10-07 05:42:03.037  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.037  5643  5689 I jxcore-log: 
10-07 05:42:03.038  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:03.038  5643  5689 I jxcore-log: 
10-07 05:42:03.039  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:03.039  5643  5689 I jxcore-log: 
,10-07 05:42:03.084  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.084  5643  5689 I jxcore-log: 
,10-07 05:42:03.085  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.085  5643  5689 I jxcore-log: 
,10-07 05:42:03.086  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.086  5643  5689 I jxcore-log: 
10-07 05:42:03.086  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.086  5643  5689 I jxcore-log: 
,10-07 05:42:03.087  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.087  5643  5689 I jxcore-log: 
,10-07 05:42:03.088  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.088  5643  5689 I jxcore-log: 
10-07 05:42:03.088  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.088  5643  5689 I jxcore-log: 
10-07 05:42:03.089  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.089  5643  5689 I jxcore-log: 
,10-07 05:42:03.089  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.089  5643  5689 I jxcore-log: 
10-07 05:42:03.090  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.090  5643  5689 I jxcore-log: 
,10-07 05:42:03.090  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.090  5643  5689 I jxcore-log: 
,10-07 05:42:03.090  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.090  5643  5689 I jxcore-log: 
,10-07 05:42:03.091  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.091  5643  5689 I jxcore-log: 
10-07 05:42:03.091  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.091  5643  5689 I jxcore-log: 
10-07 05:42:03.092  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.092  5643  5689 I jxcore-log: 
,10-07 05:42:03.093  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.093  5643  5689 I jxcore-log: 
,10-07 05:42:03.093  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.093  5643  5689 I jxcore-log: 
10-07 05:42:03.093  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.093  5643  5689 I jxcore-log: 
,10-07 05:42:03.094  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.094  5643  5689 I jxcore-log: 
10-07 05:42:03.094  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.094  5643  5689 I jxcore-log: 
,10-07 05:42:03.095  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.095  5643  5689 I jxcore-log: 
10-07 05:42:03.095  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.095  5643  5689 I jxcore-log: 
10-07 05:42:03.096  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.096  5643  5689 I jxcore-log: 
,10-07 05:42:03.096  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.096  5643  5689 I jxcore-log: 
10-07 05:42:03.097  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.097  5643  5689 I jxcore-log: 
,10-07 05:42:03.097  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.097  5643  5689 I jxcore-log: 
10-07 05:42:03.098  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.098  5643  5689 I jxcore-log: 
10-07 05:42:03.098  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.098  5643  5689 I jxcore-log: 
,10-07 05:42:03.098  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.098  5643  5689 I jxcore-log: 
10-07 05:42:03.099  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.099  5643  5689 I jxcore-log: 
10-07 05:42:03.099  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.099  5643  5689 I jxcore-log: 
,10-07 05:42:03.100  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.100  5643  5689 I jxcore-log: 
10-07 05:42:03.100  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.100  5643  5689 I jxcore-log: 
10-07 05:42:03.101  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.101  5643  5689 I jxcore-log: 
,10-07 05:42:03.101  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.101  5643  5689 I jxcore-log: 
10-07 05:42:03.101  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.101  5643  5689 I jxcore-log: 
10-07 05:42:03.102  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.102  5643  5689 I jxcore-log: 
,10-07 05:42:03.102  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.102  5643  5689 I jxcore-log: 
10-07 05:42:03.103  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.103  5643  5689 I jxcore-log: 
,10-07 05:42:03.103  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.103  5643  5689 I jxcore-log: 
10-07 05:42:03.104  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.104  5643  5689 I jxcore-log: 
10-07 05:42:03.104  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.104  5643  5689 I jxcore-log: 
,10-07 05:42:03.104  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.104  5643  5689 I jxcore-log: 
10-07 05:42:03.105  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.105  5643  5689 I jxcore-log: 
10-07 05:42:03.106  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.106  5643  5689 I jxcore-log: 
,10-07 05:42:03.107  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.107  5643  5689 I jxcore-log: 
10-07 05:42:03.109  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.109  5643  5689 I jxcore-log: 
10-07 05:42:03.110  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.110  5643  5689 I jxcore-log: 
10-07 05:42:03.110  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:03.110  5643  5689 I jxcore-log: 
,10-07 05:42:03.111  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'mux close'
10-07 05:42:03.111  5643  5689 I jxcore-log: 
,10-07 05:42:03.113  5643  5689 I jxcore-log: ok 28 native server is nulled out
10-07 05:42:03.113  5643  5689 I jxcore-log: 
,10-07 05:42:03.113  5643  5689 I jxcore-log: ok 29 native server should be closed
10-07 05:42:03.113  5643  5689 I jxcore-log: 
10-07 05:42:03.113  5643  5689 I jxcore-log: ok 30 incoming has been removed
10-07 05:42:03.113  5643  5689 I jxcore-log: 
10-07 05:42:03.114  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.114  5643  5689 I jxcore-log: 
10-07 05:42:03.115  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.115  5643  5689 I jxcore-log: 
,10-07 05:42:03.115  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.115  5643  5689 I jxcore-log: 
10-07 05:42:03.115  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.115  5643  5689 I jxcore-log: 
10-07 05:42:03.116  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.116  5643  5689 I jxcore-log: 
10-07 05:42:03.116  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.116  5643  5689 I jxcore-log: 
10-07 05:42:03.116  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.116  5643  5689 I jxcore-log: 
,10-07 05:42:03.116  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.116  5643  5689 I jxcore-log: 
10-07 05:42:03.116  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.116  5643  5689 I jxcore-log: 
10-07 05:42:03.117  5643  5689 I jxcore-log: 2016-10-07 09:42:03 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:03.117  5643  5689 I jxcore-log: 
,10-07 05:42:03.190  5643  5689 I jxcore-log: # teardown
10-07 05:42:03.190  5643  5689 I jxcore-log: 
,10-07 05:42:03.280  5643  5689 I jxcore-log: # setup
10-07 05:42:03.280  5643  5689 I jxcore-log: 
,10-07 05:42:05.086  5643  5689 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-07 05:42:05.086  5643  5689 I jxcore-log: 
,10-07 05:42:05.135  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'creating native server'
10-07 05:42:05.135  5643  5689 I jxcore-log: 
,10-07 05:42:05.140  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'listening 39497'
10-07 05:42:05.140  5643  5689 I jxcore-log: 
,10-07 05:42:05.148  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:05.148  5643  5689 I jxcore-log: 
,10-07 05:42:05.150  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:05.150  5643  5689 I jxcore-log: 
,10-07 05:42:05.153  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new mux'
10-07 05:42:05.153  5643  5689 I jxcore-log: 
,10-07 05:42:05.161  5643  5689 I jxcore-log: ok 31 we should not have gotten an error
10-07 05:42:05.161  5643  5689 I jxcore-log: 
,10-07 05:42:05.164  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:05.164  5643  5689 I jxcore-log: 
,10-07 05:42:05.166  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:05.166  5643  5689 I jxcore-log: 
,10-07 05:42:05.173  5643  5689 I jxcore-log: ok 32 Buffers are identical
10-07 05:42:05.173  5643  5689 I jxcore-log: 
,10-07 05:42:05.174  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:05.174  5643  5689 I jxcore-log: 
10-07 05:42:05.176  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'mux close'
10-07 05:42:05.176  5643  5689 I jxcore-log: 
,10-07 05:42:05.186  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:05.186  5643  5689 I jxcore-log: 
,10-07 05:42:05.187  5643  5689 I jxcore-log: ok 33 server should be fine
10-07 05:42:05.187  5643  5689 I jxcore-log: 
10-07 05:42:05.187  5643  5689 I jxcore-log: ok 34 server should be open
10-07 05:42:05.187  5643  5689 I jxcore-log: 
10-07 05:42:05.187  5643  5689 I jxcore-log: ok 35 incoming has been removed
10-07 05:42:05.187  5643  5689 I jxcore-log: 
10-07 05:42:05.188  5643  5689 I jxcore-log: ok 36 The mux object should be closed
10-07 05:42:05.188  5643  5689 I jxcore-log: 
10-07 05:42:05.188  5643  5689 I jxcore-log: ok 37 The mux stream should be closed
10-07 05:42:05.188  5643  5689 I jxcore-log: 
,10-07 05:42:05.193  5643  5689 I jxcore-log: # teardown
10-07 05:42:05.193  5643  5689 I jxcore-log: 
,10-07 05:42:05.263  5643  5689 I jxcore-log: # setup
10-07 05:42:05.263  5643  5689 I jxcore-log: 
,10-07 05:42:05.312  5643  5689 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-07 05:42:05.312  5643  5689 I jxcore-log: 
,10-07 05:42:05.348  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'creating native server'
10-07 05:42:05.348  5643  5689 I jxcore-log: 
,10-07 05:42:05.353  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'listening 39255'
10-07 05:42:05.353  5643  5689 I jxcore-log: 
,10-07 05:42:05.360  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new incoming socket'
10-07 05:42:05.360  5643  5689 I jxcore-log: 
,10-07 05:42:05.362  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'creating incoming mux'
10-07 05:42:05.362  5643  5689 I jxcore-log: 
,10-07 05:42:05.365  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new mux'
10-07 05:42:05.365  5643  5689 I jxcore-log: 
,10-07 05:42:05.372  5643  5689 I jxcore-log: ok 38 we should not have gotten an error
10-07 05:42:05.372  5643  5689 I jxcore-log: 
,10-07 05:42:05.377  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new stream: '
10-07 05:42:05.377  5643  5689 I jxcore-log: 
,10-07 05:42:05.380  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'new outgoing socket'
10-07 05:42:05.380  5643  5689 I jxcore-log: 
,10-07 05:42:05.389  5643  5689 I jxcore-log: ok 39 Buffers are identical
10-07 05:42:05.389  5643  5689 I jxcore-log: 
,10-07 05:42:05.393  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'incoming socket timeout'
10-07 05:42:05.393  5643  5689 I jxcore-log: 
,10-07 05:42:05.395  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'stream close:'
10-07 05:42:05.395  5643  5689 I jxcore-log: 
,10-07 05:42:05.397  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'mux close'
10-07 05:42:05.397  5643  5689 I jxcore-log: 
,10-07 05:42:05.401  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG createNativeListener: 'incoming socket close'
10-07 05:42:05.401  5643  5689 I jxcore-log: 
10-07 05:42:05.402  5643  5689 I jxcore-log: ok 40 server should be fine
10-07 05:42:05.402  5643  5689 I jxcore-log: 
10-07 05:42:05.402  5643  5689 I jxcore-log: ok 41 server should be open
10-07 05:42:05.402  5643  5689 I jxcore-log: 
,10-07 05:42:05.403  5643  5689 I jxcore-log: ok 42 incoming has been removed
10-07 05:42:05.403  5643  5689 I jxcore-log: 
10-07 05:42:05.403  5643  5689 I jxcore-log: ok 43 The mux object should be closed
10-07 05:42:05.403  5643  5689 I jxcore-log: 
10-07 05:42:05.403  5643  5689 I jxcore-log: ok 44 The mux stream should be closed
10-07 05:42:05.403  5643  5689 I jxcore-log: 
,10-07 05:42:05.410  5643  5689 I jxcore-log: # teardown
10-07 05:42:05.410  5643  5689 I jxcore-log: 
,10-07 05:42:05.460  5643  5689 I jxcore-log: # setup
10-07 05:42:05.460  5643  5689 I jxcore-log: 
,10-07 05:42:05.486  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-07 05:42:05.486  5643  5689 I jxcore-log: 
,10-07 05:42:05.652  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-07 05:42:05.652  5643  5689 I jxcore-log: 
,10-07 05:42:05.652  5643  5689 I jxcore-log: ok 45 Got right error
10-07 05:42:05.652  5643  5689 I jxcore-log: 
,10-07 05:42:05.657  5643  5689 I jxcore-log: # teardown
10-07 05:42:05.657  5643  5689 I jxcore-log: 
,10-07 05:42:05.690  5643  5689 I jxcore-log: # setup
10-07 05:42:05.690  5643  5689 I jxcore-log: 
,10-07 05:42:05.717  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-07 05:42:05.717  5643  5689 I jxcore-log: 
,10-07 05:42:05.809  5643  5689 I jxcore-log: 2016-10-07 09:42:05 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-07 05:42:05.809  5643  5689 I jxcore-log: 
,10-07 05:42:05.810  5643  5689 I jxcore-log: ok 46 Got socket hang up
10-07 05:42:05.810  5643  5689 I jxcore-log: 
,10-07 05:42:05.815  5643  5689 I jxcore-log: # teardown
10-07 05:42:05.815  5643  5689 I jxcore-log: 
,10-07 05:42:05.875  5643  5689 I jxcore-log: # setup
10-07 05:42:05.875  5643  5689 I jxcore-log: 
,10-07 05:42:05.932  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-07 05:42:05.932  5643  5689 I jxcore-log: 
,10-07 05:42:06.117  5643  5689 I jxcore-log: 2016-10-07 09:42:06 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-07 05:42:06.117  5643  5689 I jxcore-log: 
10-07 05:42:06.118  5643  5689 I jxcore-log: ok 47 Got 500 as expected
10-07 05:42:06.118  5643  5689 I jxcore-log: 
,10-07 05:42:06.122  5643  5689 I jxcore-log: # teardown
10-07 05:42:06.122  5643  5689 I jxcore-log: 
,10-07 05:42:06.162  5643  5689 I jxcore-log: # setup
10-07 05:42:06.162  5643  5689 I jxcore-log: 
,10-07 05:42:06.207  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-07 05:42:06.207  5643  5689 I jxcore-log: 
,10-07 05:42:07.589   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:07.767  5643  5689 I jxcore-log: ok 48 should be equal
10-07 05:42:07.767  5643  5689 I jxcore-log: 
,10-07 05:42:07.768  5643  5689 I jxcore-log: ok 49 revs are equal
10-07 05:42:07.768  5643  5689 I jxcore-log: 
,10-07 05:42:07.776  5643  5689 I jxcore-log: # teardown
10-07 05:42:07.776  5643  5689 I jxcore-log: 
,10-07 05:42:07.847  5643  5689 I jxcore-log: # setup
10-07 05:42:07.847  5643  5689 I jxcore-log: 
,10-07 05:42:08.590   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:08.678  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-07 05:42:08.678  5643  5689 I jxcore-log: 
,10-07 05:42:09.591   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:10.290  5643  5689 I jxcore-log: ok 50 should be equal
10-07 05:42:10.290  5643  5689 I jxcore-log: 
,10-07 05:42:10.291  5643  5689 I jxcore-log: ok 51 revs are equal
10-07 05:42:10.291  5643  5689 I jxcore-log: 
,10-07 05:42:10.297  5643  5689 I jxcore-log: # teardown
10-07 05:42:10.297  5643  5689 I jxcore-log: 
,10-07 05:42:10.339  5643  5689 I jxcore-log: # setup
10-07 05:42:10.339  5643  5689 I jxcore-log: 
,10-07 05:42:10.391  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-07 05:42:10.391  5643  5689 I jxcore-log: 
,10-07 05:42:10.592   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:10.912  5643  5689 I jxcore-log: ok 52 should be equal
10-07 05:42:10.912  5643  5689 I jxcore-log: 
,10-07 05:42:10.912  5643  5689 I jxcore-log: ok 53 revs are equal
10-07 05:42:10.912  5643  5689 I jxcore-log: 
,10-07 05:42:11.047  5643  5689 I jxcore-log: ok 54 should be equal
10-07 05:42:11.047  5643  5689 I jxcore-log: 
,10-07 05:42:11.047  5643  5689 I jxcore-log: ok 55 revs are equal
10-07 05:42:11.047  5643  5689 I jxcore-log: 
,10-07 05:42:11.183  5643  5689 I jxcore-log: ok 56 should be equal
10-07 05:42:11.183  5643  5689 I jxcore-log: 
,10-07 05:42:11.183  5643  5689 I jxcore-log: ok 57 revs are equal
10-07 05:42:11.183  5643  5689 I jxcore-log: 
,10-07 05:42:11.189  5643  5689 I jxcore-log: # teardown
10-07 05:42:11.189  5643  5689 I jxcore-log: 
,10-07 05:42:11.226  5643  5689 I jxcore-log: # setup
10-07 05:42:11.226  5643  5689 I jxcore-log: 
,10-07 05:42:11.294  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-07 05:42:11.294  5643  5689 I jxcore-log: 
,10-07 05:42:11.559   927  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 05:42:11.593   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:11.894  5643  5689 I jxcore-log: 2016-10-07 09:42:11 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-07 05:42:11.894  5643  5689 I jxcore-log: 
,10-07 05:42:11.895  5643  5689 I jxcore-log: ok 58 Our rev is old so we should fail
10-07 05:42:11.895  5643  5689 I jxcore-log: 
,10-07 05:42:11.899  5643  5689 I jxcore-log: # teardown
10-07 05:42:11.899  5643  5689 I jxcore-log: 
,10-07 05:42:11.981  5643  5689 I jxcore-log: # setup
10-07 05:42:11.981  5643  5689 I jxcore-log: 
,10-07 05:42:12.000  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-07 05:42:12.000  5643  5689 I jxcore-log: 
,10-07 05:42:12.094  5643  5689 I jxcore-log: ok 59 confirm stop caused failure
10-07 05:42:12.094  5643  5689 I jxcore-log: 
,10-07 05:42:12.105  5643  5689 I jxcore-log: # teardown
10-07 05:42:12.105  5643  5689 I jxcore-log: 
,10-07 05:42:12.136  5643  5689 I jxcore-log: # setup
10-07 05:42:12.136  5643  5689 I jxcore-log: 
,10-07 05:42:12.186  5643  5689 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-07 05:42:12.186  5643  5689 I jxcore-log: 
,10-07 05:42:12.520  5643  5689 I jxcore-log: 2016-10-07 09:42:12 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-07 05:42:12.520  5643  5689 I jxcore-log: 
,10-07 05:42:12.521  5643  5689 I jxcore-log: ok 60 stop caused us to fail
10-07 05:42:12.521  5643  5689 I jxcore-log: 
10-07 05:42:12.522  5643  5689 I jxcore-log: ok 61 We specifically failed on a stop before put
10-07 05:42:12.522  5643  5689 I jxcore-log: 
,10-07 05:42:12.528  5643  5689 I jxcore-log: # teardown
10-07 05:42:12.528  5643  5689 I jxcore-log: 
,10-07 05:42:12.571  5643  5689 I jxcore-log: # setup
10-07 05:42:12.571  5643  5689 I jxcore-log: 
,10-07 05:42:12.593   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-07 05:42:12.624  5643  5689 I jxcore-log: # #update - fail if stop is called
10-07 05:42:12.624  5643  5689 I jxcore-log: 
,10-07 05:42:12.738  5643  5689 I jxcore-log: ok 62 failed due to stop
10-07 05:42:12.738  5643  5689 I jxcore-log: 
,10-07 05:42:12.740  5643  5689 I jxcore-log: ok 63 failed due to stop
10-07 05:42:12.740  5643  5689 I jxcore-log: 
,10-07 05:42:12.750  5643  5689 I jxcore-log: # teardown
10-07 05:42:12.750  5643  5689 I jxcore-log: 
,10-07 05:42:12.773  5643  5689 I jxcore-log: # setup
10-07 05:42:12.773  5643  5689 I jxcore-log: 
,10-07 05:42:12.824  5643  5689 I jxcore-log: # #update - set seq for first time
10-07 05:42:12.824  5643  5689 I jxcore-log: 
,10-07 05:42:13.278  5643  5689 I jxcore-log: ok 64 should be equal
10-07 05:42:13.278  5643  5689 I jxcore-log: 
,10-07 05:42:13.285  5643  5689 I jxcore-log: # teardown
10-07 05:42:13.285  5643  5689 I jxcore-log: 
,10-07 05:42:13.435  5643  5689 I jxcore-log: # setup
10-07 05:42:13.435  5643  5689 I jxcore-log: 
,10-07 05:42:13.454  5643  5689 I jxcore-log: # #update - Fail on bad seq value
10-07 05:42:13.454  5643  5689 I jxcore-log: 
,10-07 05:42:14.155  5643  5689 I jxcore-log: 2016-10-07 09:42:14 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-07 05:42:14.155  5643  5689 I jxcore-log: 
,10-07 05:42:14.157  5643  5689 I jxcore-log: ok 65 Expected bad seq error
10-07 05:42:14.157  5643  5689 I jxcore-log: 
,10-07 05:42:14.167  5643  5689 I jxcore-log: # teardown
10-07 05:42:14.167  5643  5689 I jxcore-log: 
,10-07 05:42:14.252  5643  5689 I jxcore-log: # setup
10-07 05:42:14.252  5643  5689 I jxcore-log: 
,10-07 05:42:14.294  5643  5689 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-07 05:42:14.294  5643  5689 I jxcore-log: 
,10-07 05:42:14.722  5643  5689 I jxcore-log: ok 66 Different promises
10-07 05:42:14.722  5643  5689 I jxcore-log: 
,10-07 05:42:14.724  5643  5689 I jxcore-log: ok 67 Timer was cancelled
10-07 05:42:14.724  5643  5689 I jxcore-log: 
,10-07 05:42:14.858  5643  5689 I jxcore-log: ok 68 should be equal
10-07 05:42:14.858  5643  5689 I jxcore-log: 
,10-07 05:42:14.865  5643  5689 I jxcore-log: # teardown
10-07 05:42:14.865  5643  5689 I jxcore-log: 
,10-07 05:42:14.912  5643  5689 I jxcore-log: # setup
10-07 05:42:14.912  5643  5689 I jxcore-log: 
,10-07 05:42:14.962  5643  5689 I jxcore-log: # #update - do we wait for blocked update
10-07 05:42:14.962  5643  5689 I jxcore-log: 
,10-07 05:42:15.037  5643  5689 I jxcore-log: ok 69 One go and one blocked
10-07 05:42:15.037  5643  5689 I jxcore-log: 
,10-07 05:42:15.038  5643  5689 I jxcore-log: ok 70 All blocked
10-07 05:42:15.038  5643  5689 I jxcore-log: 
10-07 05:42:15.038  5643  5689 I jxcore-log: ok 71 Still blocked
10-07 05:42:15.038  5643  5689 I jxcore-log: 
,10-07 05:42:15.465  5643  5689 I jxcore-log: ok 72 should be equal
10-07 05:42:15.465  5643  5689 I jxcore-log: 
,10-07 05:42:15.474  5643  5689 I jxcore-log: # teardown
10-07 05:42:15.474  5643  5689 I jxcore-log: 
,10-07 05:42:15.537  5643  5689 I jxcore-log: # setup
10-07 05:42:15.537  5643  5689 I jxcore-log: 
,10-07 05:42:15.580  5643  5689 I jxcore-log: # #update - test that we wait long enough
10-07 05:42:15.580  5643  5689 I jxcore-log: 
,10-07 05:42:16.952  5643  5689 I jxcore-log: ok 73 We waited long enough
10-07 05:42:16.952  5643  5689 I jxcore-log: 
,10-07 05:42:17.088  5643  5689 I jxcore-log: ok 74 should be equal
10-07 05:42:17.088  5643  5689 I jxcore-log: 
,10-07 05:42:17.093  5643  5689 I jxcore-log: # teardown
10-07 05:42:17.093  5643  5689 I jxcore-log: 
,10-07 05:42:17.129  5643  5689 I jxcore-log: # setup
10-07 05:42:17.129  5643  5689 I jxcore-log: 
,10-07 05:42:17.188  5643  5689 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-07 05:42:17.188  5643  5689 I jxcore-log: 
,10-07 05:42:17.593   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:17.604  5643  5689 I jxcore-log: ok 75 Should have gotten same timer promise
10-07 05:42:17.604  5643  5689 I jxcore-log: 
,10-07 05:42:17.604  5643  5689 I jxcore-log: ok 76 Still same timer promise
10-07 05:42:17.604  5643  5689 I jxcore-log: 
,10-07 05:42:18.384  5643  5689 I jxcore-log: ok 77 We waited long enough
10-07 05:42:18.384  5643  5689 I jxcore-log: 
,10-07 05:42:18.457  5643  5689 I jxcore-log: ok 78 should be equal
10-07 05:42:18.457  5643  5689 I jxcore-log: 
,10-07 05:42:18.465  5643  5689 I jxcore-log: # teardown
10-07 05:42:18.465  5643  5689 I jxcore-log: 
,10-07 05:42:18.529  5643  5689 I jxcore-log: # setup
10-07 05:42:18.529  5643  5689 I jxcore-log: 
,10-07 05:42:18.594   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:18.601  5643  5689 I jxcore-log: # Coordinated seq test
10-07 05:42:18.601  5643  5689 I jxcore-log: 
,10-07 05:42:18.764  5643  5689 I jxcore-log: 2016-10-07 09:42:18 - DEBUG thaliWifiInfrastructure: 'listening 40255'
10-07 05:42:18.764  5643  5689 I jxcore-log: 
,10-07 05:42:19.595   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:20.596   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:20.793  5643  5689 I jxcore-log: ok 79 should be equal
10-07 05:42:20.793  5643  5689 I jxcore-log: 
,10-07 05:42:21.072  5643  5689 I jxcore-log: ok 80 should be equal
10-07 05:42:21.072  5643  5689 I jxcore-log: 
,10-07 05:42:21.090  5643  5689 I jxcore-log: # teardown
10-07 05:42:21.090  5643  5689 I jxcore-log: 
,10-07 05:42:21.597   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:22.597   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-07 05:42:31.561   927  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 05:42:32.599   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:33.600   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:34.601   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:35.603   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:36.604   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:37.605   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-07 05:42:52.606   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:53.608   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:54.609   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:55.611   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:56.612   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:42:57.613   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-07 05:43:06.237   927  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-07 05:43:11.423   927  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-07 05:43:11.563   927  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-07 05:43:17.614   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:43:18.615   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:43:19.617   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:43:20.618   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:43:21.107  5643  5689 I jxcore-log: 2016-10-07 09:43:21 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-07 05:43:21.107  5643  5689 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-07 05:43:21.107  5643  5689 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-07 05:43:21.107  5643  5689 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-07 05:43:21.107  5643  5689 I jxcore-log:     at $9@timers.js:120:1
10-07 05:43:21.107  5643  5689 I jxcore-log: ''
10-07 05:43:21.107  5643  5689 I jxcore-log: 
,10-07 05:43:21.108  5643  5689 I jxcore-log: 2016-10-07 09:43:21 - DEBUG CoordinatedClient: 'test client failed'
10-07 05:43:21.108  5643  5689 I jxcore-log: 
,10-07 05:43:21.119  5643  5689 I jxcore-log: 2016-10-07 09:43:21 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-07 05:43:21.119  5643  5689 I jxcore-log: 
,10-07 05:43:21.123  5643  5689 I jxcore-log: 2016-10-07 09:43:21 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-07 05:43:21.123  5643  5689 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-07 05:43:21.123  5643  5689 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-07 05:43:21.123  5643  5689 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-07 05:43:21.123  5643  5689 I jxcore-log:     at $9@timers.js:120:1
10-07 05:43:21.123  5643  5689 I jxcore-log: ''
10-07 05:43:21.123  5643  5689 I jxcore-log: 
,10-07 05:43:21.125  5643  5689 I jxcore-log: 2016-10-07 09:43:21 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-07 05:43:21.125  5643  5689 I jxcore-log: 
,10-07 05:43:21.194   927  2896 W InputDispatcher: channel '2f4197c com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-07 05:43:21.194   927  2896 E InputDispatcher: channel '2f4197c com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-07 05:43:21.203   927  2932 D WifiService: Client connection lost with reason: 4
,10-07 05:43:21.203   927  3118 D GraphicsStats: Buffer count: 2
,10-07 05:43:21.203   927  3848 I WindowState: WIN DEATH: Window{2f4197c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-07 05:43:21.203   927  3848 W InputDispatcher: Attempted to unregister already unregistered input channel '2f4197c com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-07 05:43:21.210   529   529 I Zygote  : Process 5643 exited cleanly (139)
,10-07 05:43:21.215   927  3118 I ActivityManager: Process com.test.thalitest (pid 5643) has died
,10-07 05:43:21.244   927  3118 I ActivityManager: Start proc 6022:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-07 05:43:21.572   927   938 I WindowManager: Screenshot max retries 4 of Token{e4151ee ActivityRecord{b707369 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{7d763a0 u0 Starting com.test.thalitest} drawState=4
,10-07 05:43:21.620   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-07 05:43:21.657  6022  6022 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-07 05:43:21.658  6020  6020 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-07 05:43:21.674  6020  6020 D AndroidRuntime: CheckJNI is OFF
,10-07 05:43:21.677  6022  6022 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-07 05:43:21.682  6022  6022 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8160-8163)
,10-07 05:43:21.682  6022  6022 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-07 05:43:21.690  6022  6022 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a9db128}
,10-07 05:43:21.691  6022  6022 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-07 05:43:21.691  6022  6022 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-07 05:43:21.694  6022  6022 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-07 05:43:21.695  6022  6022 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-07 05:43:21.699  6020  6020 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-07 05:43:21.704  6022  6022 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-07 05:43:21.712  6022  6022 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-07 05:43:21.712  6022  6022 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-07 05:43:21.712  6022  6022 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-07 05:43:21.712  6022  6022 I Adreno  : Build Date                       : 12/06/15
10-07 05:43:21.712  6022  6022 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-07 05:43:21.712  6022  6022 I Adreno  : Local Branch                     : mybranch17112971
10-07 05:43:21.712  6022  6022 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-07 05:43:21.712  6022  6022 I Adreno  : Remote Branch                    : NONE
10-07 05:43:21.712  6022  6022 I Adreno  : Reconstruct Branch               : NOTHING
,10-07 05:43:21.723  6020  6020 I Radio-JNI: register_android_hardware_Radio DONE
,10-07 05:43:21.738  6020  6020 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-07 05:43:21.742   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e611c91:true
,10-07 05:43:21.744   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-07 05:43:21.744   927   940 I ActivityManager: Killing 6022:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-07 05:43:21.871   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
10-07 05:43:21.871   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-07 05:43:21.873   927   940 E ActivityManager: Failure starting process com.test.thalitest
10-07 05:43:21.873   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-07 05:43:21.873   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:43:21.873   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:43:21.873   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 05:43:21.873   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-07 05:43:21.875   927   940 I ActivityManager:   Force finishing activity ActivityRecord{b707369 u0 com.test.thalitest/.MainActivity t2}
,10-07 05:43:21.876   927   950 I art     : Starting a blocking GC Explicit
,10-07 05:43:21.895   927   945 W WindowManager: Failed looking up window
10-07 05:43:21.895   927   945 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@b85d4a3 does not exist
10-07 05:43:21.895   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-07 05:43:21.895   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-07 05:43:21.895   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-07 05:43:21.895   927   945 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-07 05:43:21.895   927   945 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-07 05:43:21.895   927   945 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-07 05:43:21.895   927   945 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-07 05:43:21.895   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:43:21.895   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:43:21.895   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-07 05:43:21.895   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-07 05:43:21.898   927   938 W ActivityManager: Spurious death for ProcessRecord{aa207f7 0:com.test.thalitest/u0a77}, curProc for 6022: null
,10-07 05:43:21.972   927   950 I art     : Explicit concurrent mark sweep GC freed 80672(5MB) AllocSpace objects, 43(1732KB) LOS objects, 33% free, 29MB/43MB, paused 1.520ms total 95.810ms
,10-07 05:43:21.993   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-07 05:43:21.996  6020  6020 I art     : System.exit called, status: 0
,10-07 05:43:21.996  6020  6020 I AndroidRuntime: VM exiting with result code 0.
,10-07 05:43:22.011   927   950 I ActivityManager: Start proc 6059:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-07 05:43:22.011   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-07 05:43:22.015   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-07 05:43:22.022  5923  5923 D BluetoothMapAppObserver: onReceive
,10-07 05:43:22.022  5923  5923 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-07 05:43:22.024   927  2897 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-07 05:43:22.026  4022  4122 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-07 05:43:22.029  3620  3620 I Keyboard.Facilitator: resetDictionaries() : en_US
10-07 05:43:22.052  3750  3750 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-07 05:43:22.062  3620  6073 I Keyboard.Facilitator.DecoderInitializer: run()
,10-07 05:43:22.065  3350  6074 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-07 05:43:22.076   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-07 05:43:22.094  3620  6073 I Decoder : createOrResetDecoder
,10-07 05:43:22.099  3533  3533 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-07 05:43:22.099  3533  3533 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-07 05:43:22.109   436   436 W kworker/1:3: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 05:43:22.115   436   436 W kworker/1:3: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 05:43:22.132   436   436 W kworker/1:3: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-07 05:43:22.146  3656  6078 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-07 05:43:22.147  3656  6078 D AccountUtils: Clearing selected account for com.test.thalitest
,10-07 05:43:22.163  3533  3533 I ConfigService: onCreate
,10-07 05:43:22.167  3533  6081 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,10-07 05:43:22.179  3620  6073 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-07 05:43:22.191  3656  6078 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-07 05:43:22.217  3656  6078 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:43:22.217  3656  6078 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:43:22.218  3656  6078 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
10-07 05:43:22.251  3350  3377 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-07 05:43:22.251  3350  3377 E AndroidRuntime: Process: android.process.acore, PID: 3350
10-07 05:43:22.251  3350  3377 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-07 05:43:22.251  3350  3377 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-07 05:43:22.265  3350  3377 I Process : Sending signal. PID: 3350 SIG: 9
,10-07 05:43:22.500   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
