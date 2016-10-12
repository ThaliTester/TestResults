#### Test 8711940474d511d_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-12 09:16:39.714   927  5407 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,--------- beginning of system
10-12 09:16:39.879   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-12 09:16:40.099   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-12 09:16:40.099   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
10-12 09:16:40.189  5667  5667 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-12 09:16:40.195  5667  5667 D AndroidRuntime: CheckJNI is OFF
10-12 09:16:40.218  5667  5667 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-12 09:16:40.250  5667  5667 I Radio-JNI: register_android_hardware_Radio DONE
10-12 09:16:40.265  5667  5667 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-12 09:16:40.271   927   937 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-12 09:16:40.314   927   937 I ActivityManager: Start proc 5676:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-12 09:16:40.336  5667  5667 D AndroidRuntime: Shutting down VM
,10-12 09:16:40.658   927  3874 I WindowManager: Screenshot max retries 4 of Token{d312d46 ActivityRecord{103c521 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{3cef759 u0 Starting com.test.thalitest} drawState=2
,10-12 09:16:40.734  5676  5676 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-12 09:16:40.767  5676  5676 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-12 09:16:40.790  5676  5676 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 42-61)
,10-12 09:16:40.790  5676  5676 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 09:16:40.812  5676  5676 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {787d207}
,10-12 09:16:40.812  5676  5676 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 09:16:40.813  5676  5676 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 09:16:40.819  5676  5676 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-12 09:16:40.820  5676  5676 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-12 09:16:40.855  5676  5676 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-12 09:16:40.868  5676  5676 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-12 09:16:40.869  5676  5676 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 09:16:40.869  5676  5676 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-12 09:16:40.869  5676  5676 I Adreno  : Build Date                       : 12/06/15
10-12 09:16:40.869  5676  5676 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-12 09:16:40.869  5676  5676 I Adreno  : Local Branch                     : mybranch17112971
10-12 09:16:40.869  5676  5676 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-12 09:16:40.869  5676  5676 I Adreno  : Remote Branch                    : NONE
10-12 09:16:40.869  5676  5676 I Adreno  : Reconstruct Branch               : NOTHING
,10-12 09:16:40.925   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c6a264:true
,10-12 09:16:40.958   682   682 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15961]" dev="sockfs" ino=15961 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 09:16:40.958   682   682 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[15961]" dev="sockfs" ino=15961 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 09:16:40.972  5676  5676 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-12 09:16:40.980  5676  5676 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-12 09:16:41.005   407   407 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34215]" dev="sockfs" ino=34215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 09:16:41.005   407   407 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34215]" dev="sockfs" ino=34215 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-12 09:16:41.009  5676  5713 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-12 09:16:41.011  3846  3846 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30318]" dev="sockfs" ino=30318 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-12 09:16:41.011  3846  3846 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30318]" dev="sockfs" ino=30318 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-12 09:16:41.017  5676  5700 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-12 09:16:41.039  5676  5713 I OpenGLRenderer: Initialized EGL, version 1.4
,10-12 09:16:41.117   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +453ms (total +833ms)
,10-12 09:16:41.148  5676  5676 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5676
,10-12 09:16:41.234  5676  5676 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-12 09:16:41.288   927  2984 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:16:41.368  5676  5716 D jxcore_app_log: JniHelper::setJavaVM(0xf517c000), pthread_self() = -604243664
,10-12 09:16:41.371  5676  5716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-12 09:16:41.371  5676  5716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-12 09:16:41.371  5676  5716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-12 09:16:41.371  5676  5716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-12 09:16:41.371  5676  5716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-12 09:16:41.371  5676  5716 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eae198c added. We now have 1 listener(s)
,10-12 09:16:41.373  5676  5716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-12 09:16:41.373  5676  5716 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:16:41.374  5676  5716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-12 09:16:41.374  5676  5716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-12 09:16:41.377  5676  5716 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe94278 added. We now have 1 listener(s)
,10-12 09:16:41.377  5676  5716 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:16:41.381   927  2992 D WifiService: New client listening to asynchronous messages
,10-12 09:16:41.382  5676  5716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:16:41.382  5676  5716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-12 09:16:41.382  5676  5716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-12 09:16:41.382  5676  5716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-12 09:16:41.382  5676  5716 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-12 09:16:41.384  5676  5716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:16:41.384  5676  5716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-12 09:16:41.388  5676  5716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:16:41.388  5676  5716 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:16:41.388  5676  5716 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,10-12 09:16:41.388  5676  5716 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:16:41.388  5676  5716 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 09:16:41.391  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:16:41.393  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:16:41.484  5676  5676 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-12 09:16:41.788  5676  5722 W jxcore-log: Initializing JXcore engine
,10-12 09:16:41.788  5676  5722 W jxcore-log: JXcore engine is ready
,10-12 09:16:41.818  5722  5722 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12094 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-12 09:16:41.818  5722  5722 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15398]" dev="sockfs" ino=15398 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-12 09:16:41.818  5722  5722 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-12 09:16:41.818  5722  5722 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34192]" dev="sockfs" ino=34192 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-12 09:16:41.826  5676  5722 W jxcore-log: Starting JXcore engine
,10-12 09:16:41.880  5676  5722 W jxcore-log: Platform android
10-12 09:16:41.880  5676  5722 W jxcore-log: 
10-12 09:16:41.880  5676  5722 W jxcore-log: Process ARCH arm
10-12 09:16:41.880  5676  5722 W jxcore-log: 
,10-12 09:16:42.026  5676  5722 I jxcore-log: JXcore Cordova bridge is ready!
10-12 09:16:42.026  5676  5722 I jxcore-log: 
,10-12 09:16:42.026  5676  5722 W jxcore-log: JXcore engine is started
,10-12 09:16:42.034  5676  5716 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-12 09:16:42.038  5676  5676 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-12 09:16:42.895   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 09:16:50.100   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:16:51.101   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:16:52.103   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:16:52.117  5676  5722 I jxcore-log: 2016-10-12 13:16:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-12 09:16:52.117  5676  5722 I jxcore-log: 
,10-12 09:16:52.119  5676  5722 I jxcore-log: 2016-10-12 13:16:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-12 09:16:52.119  5676  5722 I jxcore-log: 
,10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:16:52.123  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:16:52.124  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:16:52.126  5676  5722 I jxcore-log: 2016-10-12 13:16:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-12 09:16:52.126  5676  5722 I jxcore-log: 
10-12 09:16:52.127  5676  5722 I jxcore-log: 2016-10-12 13:16:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-12 09:16:52.127  5676  5722 I jxcore-log: 
,10-12 09:16:52.381  5676  5722 I jxcore-log: 2016-10-12 13:16:52 - DEBUG UnitTest_app: 'Running unit tests'
10-12 09:16:52.381  5676  5722 I jxcore-log: 
,10-12 09:16:52.382  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:16:52.382  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4756a12 added. We now have 2 listener(s)
10-12 09:16:52.383  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 09:16:52.383  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-12 09:16:52.383  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:16:52.383  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:16:52.383  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83bd5e3 added. We now have 2 listener(s)
10-12 09:16:52.383  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:16:52.384  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:16:52.385  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:16:52.387  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:16:52.388  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:52.388  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:16:52.388  5676  5722 D executeNativeTests: Running unit tests
,10-12 09:16:52.394  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:16:52.399  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:16:52.426  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:16:52.426  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 added. We now have 3 listener(s)
,10-12 09:16:52.427  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:16:52.427  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:16:52.427  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:16:52.427  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:16:52.427  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e added. We now have 3 listener(s)
10-12 09:16:52.427  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:16:52.428  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 09:16:52.429  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:16:52.432  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:16:52.433  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:52.433  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:16:52.434  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 09:16:52.434  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:16:52.434  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 09:16:52.434  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:16:52.435  5676  5722 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-12 09:16:52.435  5676  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 09:16:52.435  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-12 09:16:52.435  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 09:16:52.435  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:16:52.435  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 09:16:52.436  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:16:52.436  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:16:52.436  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:16:52.436  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:16:52.436  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:16:52.436  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.436  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:16:52.436  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:16:52.436  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:16:52.437  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 removed from the list
10-12 09:16:52.437  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:16:52.437  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e removed from the list
10-12 09:16:52.439  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:16:52.440  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:16:52.440  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:16:52.440  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.440  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:16:52.441  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:16:52.441  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:16:52.441  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:16:52.441  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:16:52.442  5676  5722 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-12 09:16:52.442  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:16:52.442  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:16:52.442  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:16:52.442  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:16:52.442  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.442  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: r,elease: 2 listener(s) left
10-12 09:16:52.442  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:16:52.442  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:16:52.442  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:16:52.443  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:16:52.443  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:16:52.443  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.443  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:16:52.443  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.443  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:16:52.443  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:16:52.443  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:16:52.443  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:16:52.443  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-12 09:16:52.446  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-12 09:16:52.447  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-12 09:16:52.447  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-12 09:16:52.447  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-12 09:16:52.447  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-12 09:16:52.447  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-12 09:16:52.447  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-12 09:16:52.447  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:16:52.447  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:16:52.447  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:16:52.447  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:16:52.447  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.447  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:16:52.447  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:16:52.447  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:16:52.447  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:16:52.447  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:16:52.447  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:16:52.447  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.447  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:16:52.447  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:52.447  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:16:52.448  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:16:52.448  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:16:52.448  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:16:52.448  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:16:52.448  5676  5722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-12 09:16:52.449  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:16:52.452  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:16:52.452  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:16:52.453  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:16:52.453  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:16:52.453  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 09:16:52.453  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 09:16:52.453  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:16:52.453  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:16:52.454  5676  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 09:16:52.454  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 09:16:52.455  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:16:52.457  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:16:52.458  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 09:16:52.460  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 09:16:52.460  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 09:16:52.461  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-12 09:16:52.462  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-12 09:16:52.462  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 09:16:52.462  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 09:16:52.462  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 09:16:52.463  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 09:16:52.463  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 09:16:52.463  5676  5722 D BluetoothAdapter: STATE_ON
10-12 09:16:52.465  4616  4847 D BtGatt.GattService: registerClient() - UUID=b418986d-0572-4a22-9b81-95ac1b3dd2b0
10-12 09:16:52.465  4616  4678 D BtGatt.GattService: onClientRegistered() - UUID=b418986d-0572-4a22-9b81-95ac1b3dd2b0, clientIf=5
10-12 09:16:52.466  5676  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 09:16:52.467  4616  4827 D BtGatt.GattService: start scan with filters
10-12 09:16:52.472  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 09:16:52.472  4616  4681 D BtGatt.ScanManager: handling starting scan
10-12 09:16:52.473  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:16:52.473  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:16:52.473  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 09:16:52.473  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:16:52.473  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 09:16:52.473  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 09:16:52.474  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:16:52.474  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:16:52.474  4616  4681 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:16:52.474  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:16:52.475  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:16:52.476  5676  5722 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 09:16:52.481  4616  4678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 09:16:52.481  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:16:52.482  4616  4681 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 09:16:52.488  4616  4678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 09:16:52.488  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:16:52.488  4616  4681 D BtGatt.ScanManager: Starting BLE batch scan
10-12 09:16:52.488  4616  4681 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 09:16:52.498  4616  4678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 09:16:52.498  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:16:52.504  4616  4678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 09:16:52.504  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:16:52.976  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-12 09:16:52.977  5676  5676 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:16:52.977  5676  5676 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 09:16:53.104   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:16:54.106   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:16:55.107   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-12 09:16:57.480  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:16:57.480  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 09:16:57.480  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 09:16:57.481  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:57.481  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-12 09:16:57.481  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:16:57.481  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 09:16:57.481  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:16:57.481  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:16:57.481  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:16:57.482  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:16:57.482  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 09:16:57.483  5676  5722 D BluetoothAdapter: STATE_ON
,10-12 09:16:57.484  4616  4827 D BtGatt.GattService: stopScan() - queue size =1
10-12 09:16:57.486  4616  4630 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 09:16:57.487  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:16:57.487  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 09:16:57.487  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-12 09:16:57.487  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:16:57.487  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-12 09:16:57.488  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:16:57.488  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 09:16:57.488  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 09:16:57.492  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:16:57.493  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:16:57.493  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 09:16:57.493  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:16:57.493  4616  4616 D BtGatt.ScanManager: awakened up at time 236764
,10-12 09:16:57.493  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:16:57.500  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:16:57.500  4616  4678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 09:16:57.500  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:16:57.501  4616  4681 D BtGatt.ScanManager: stopping BLe Batch
,10-12 09:16:57.503  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 09:16:57.503  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:16:57.503  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:16:57.503  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:16:57.503  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:16:57.503  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:16:57.503  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:16:57.503  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:16:57.503  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:16:57.503  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:16:57.504  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:16:57.504  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:16:57.513  4616  4678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 09:16:57.514  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:16:57.514  4616  4681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:16:57.538  4616  4678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-12 09:16:57.538  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:16:57.538  4616  4678 D BtGatt.GattService: current time is 236809736752
,10-12 09:16:57.539  4616  4678 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 61, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -94, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
10-12 09:16:57.541  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-12 09:16:57.542  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-12 09:16:57.543  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,10-12 09:16:57.543  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-12 09:16:57.543  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-12 09:16:57.543  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,10-12 09:16:58.004  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:17:00.107   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:01.109   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:02.110   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:02.506  5676  5722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-12 09:17:02.512  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:02.522  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:17:02.527  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:17:02.528  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:17:02.528  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:17:02.528  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 09:17:02.528  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 09:17:02.528  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:17:02.529  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 09:17:02.534  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:02.536  5676  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 09:17:02.536  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 09:17:02.539  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:02.544  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 09:17:02.546  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 09:17:02.546  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:17:02.553  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 09:17:02.553  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 09:17:02.553  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 09:17:02.553  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-12 09:17:02.554  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 09:17:02.554  5676  5722 D BluetoothAdapter: STATE_ON
,10-12 09:17:02.558  4616  4827 D BtGatt.GattService: registerClient() - UUID=4afe4285-9f4a-43d7-afee-6288eac2fca5
10-12 09:17:02.559  4616  4678 D BtGatt.GattService: onClientRegistered() - UUID=4afe4285-9f4a-43d7-afee-6288eac2fca5, clientIf=5
,10-12 09:17:02.560  5676  5687 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 09:17:02.560  4616  4630 D BtGatt.GattService: start scan with filters
,10-12 09:17:02.564  4616  4681 D BtGatt.ScanManager: handling starting scan
10-12 09:17:02.564  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 09:17:02.564  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:17:02.565  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:17:02.565  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 09:17:02.565  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:17:02.565  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 09:17:02.565  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 09:17:02.569  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 09:17:02.569  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:17:02.570  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:17:02.572  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:17:02.575  4616  4678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 09:17:02.575  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:17:02.576  4616  4681 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 09:17:02.576  5676  5722 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 09:17:02.579  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:17:02.579  5676  5722 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-12 09:17:02.579  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-12 09:17:02.579  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 09:17:02.580  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:02.580  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:17:02.580  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:02.580  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 09:17:02.580  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:17:02.580  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:17:02.580  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:17:02.580  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:17:02.580  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 09:17:02.581  5676  5722 D BluetoothAdapter: STATE_ON
10-12 09:17:02.582  4616  4827 D BtGatt.GattService: stopScan() - queue size =1
10-12 09:17:02.583  4616  4678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 09:17:02.583  4616  4629 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:17:02.583  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:17:02.583  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:17:02.584  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 09:17:02.584  4616  4681 D BtGatt.ScanManager: Starting BLE batch scan
,10-12 09:17:02.584  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 09:17:02.584  4616  4681 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 09:17:02.584  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:17:02.584  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:17:02.584  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:17:02.584  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 09:17:02.584  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 09:17:02.586  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:17:02.586  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:17:02.586  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 09:17:02.586  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:17:02.586  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:17:02.587  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:17:02.588  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:02.588  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:17:02.588  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:02.588  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:17:02.588  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:17:02.588  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:02.588  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:17:02.588  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:02.588  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:02.588  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:02.588  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:02.589  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:02.589  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:02.589  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:02.591  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:02.591  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 09:17:02.591  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:02.591  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:02.592  5676  5722 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-12 09:17:02.595  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:17:02.598  4616  4678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 09:17:02.599  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:02.601  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:17:02.604  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:02.604  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 09:17:02.605  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:17:02.605  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 09:17:02.605  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 09:17:02.605  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:17:02.605  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:17:02.607  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:02.608  4616  4678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 09:17:02.608  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:17:02.611  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:02.612  5676  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 09:17:02.612  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 09:17:02.615  4616  4678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 09:17:02.615  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:17:02.615  4616  4681 D BtGatt.ScanManager: stopping BLe Batch
,10-12 09:17:02.616  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 09:17:02.617  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 09:17:02.617  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:17:02.621  4616  4678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 09:17:02.621  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:17:02.621  4616  4681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:17:02.622  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 09:17:02.622  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 09:17:02.622  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 09:17:02.622  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 09:17:02.622  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-12 09:17:02.623  5676  5722 D BluetoothAdapter: STATE_ON
,10-12 09:17:02.625  4616  4847 D BtGatt.GattService: registerClient() - UUID=3dd1a38b-4a6b-4b85-bcdb-1acebf6b3da6
10-12 09:17:02.625  4616  4678 D BtGatt.GattService: onClientRegistered() - UUID=3dd1a38b-4a6b-4b85-bcdb-1acebf6b3da6, clientIf=5
10-12 09:17:02.626  5676  5686 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 09:17:02.626  4616  4629 D BtGatt.GattService: start scan with filters
10-12 09:17:02.627  4616  4678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-12 09:17:02.627  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:17:02.630  4616  4681 D BtGatt.ScanManager: handling starting scan
,10-12 09:17:02.630  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 09:17:02.630  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:17:02.630  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:17:02.630  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 09:17:02.630  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:17:02.630  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 09:17:02.630  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 09:17:02.633  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 09:17:02.633  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:17:02.633  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:17:02.634  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 09:17:02.636  4616  4678 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 09:17:02.636  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:17:02.636  4616  4681 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 09:17:02.637  5676  5722 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 09:17:02.643  4616  4678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 09:17:02.643  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:17:02.643  4616  4681 D BtGatt.ScanManager: Starting BLE batch scan
10-12 09:17:02.643  4616  4681 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 09:17:02.653  4616  4678 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-12 09:17:02.653  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:17:02.658  4616  4678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 09:17:02.658  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:17:03.111   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:03.134  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-12 09:17:03.135  5676  5676 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:17:03.135  5676  5676 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 09:17:04.113   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:05.113   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-12 09:17:07.638  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:17:07.638  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-12 09:17:07.638  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 09:17:07.638  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:07.639  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:17:07.639  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:17:07.639  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 09:17:07.639  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:17:07.639  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-12 09:17:07.639  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:17:07.640  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:17:07.640  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-12 09:17:07.642  5676  5722 D BluetoothAdapter: STATE_ON
,10-12 09:17:07.644  4616  4629 D BtGatt.GattService: stopScan() - queue size =1
10-12 09:17:07.646  4616  4847 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:17:07.646  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:17:07.647  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-12 09:17:07.647  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 09:17:07.647  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:17:07.647  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:17:07.647  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:17:07.647  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 09:17:07.648  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 09:17:07.651  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:17:07.651  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:17:07.651  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 09:17:07.651  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-12 09:17:07.651  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:17:07.653  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:17:07.655  4616  4616 D BtGatt.ScanManager: awakened up at time 246926
,10-12 09:17:07.656  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:17:07.656  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:17:07.656  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:17:07.657  4616  4678 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 09:17:07.658  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:17:07.658  4616  4681 D BtGatt.ScanManager: stopping BLe Batch
,10-12 09:17:07.668  4616  4678 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-12 09:17:07.668  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:17:07.668  4616  4681 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:17:07.685  4616  4678 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,10-12 09:17:07.685  4616  4678 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:17:07.685  4616  4678 D BtGatt.GattService: current time is 246956323234
10-12 09:17:07.685  4616  4678 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -77, 94, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -80, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -81, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
10-12 09:17:07.686  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-12 09:17:07.686  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-12 09:17:07.686  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-12 09:17:07.686  4616  4678 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,10-12 09:17:08.157  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:17:08.157  5676  5676 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:08.158  5676  5676 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 09:17:12.656  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:17:12.657  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.657  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.657  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.657  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.658  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 09:17:12.658  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.658  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
,10-12 09:17:12.658  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.658  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
,10-12 09:17:12.658  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.659  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.660  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.660  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.663  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.663  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 09:17:12.663  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.663  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.665  5676  5722 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-12 09:17:12.667  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:17:12.667  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.667  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.667  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 09:17:12.667  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.668  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:12.668  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.668  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.668  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:17:12.668  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.668  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.668  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.669  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.669  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.669  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.671  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.671  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 09:17:12.671  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.672  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.674  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-12 09:17:12.674  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.675  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.675  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.675  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 09:17:12.675  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.675  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.676  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:17:12.676  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.676  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.677  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.677  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:17:12.677  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.677  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.677  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.677  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:12.678  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.679  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:12.679  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.679  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.680  5676  5722 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-12 09:17:12.680  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.681  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.681  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 09:17:12.681  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.681  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.681  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.681  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.681  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.681  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.681  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.682  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:17:12.682  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.682  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.682  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.682  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:12.684  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.684  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:12.684  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.684  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.685  5676  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-12 09:17:12.685  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.686  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 09:17:12.686  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.686  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.686  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.686  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.686  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:17:12.686  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.686  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.686  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.687  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.687  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.687  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:12.687  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.687  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.689  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.689  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:12.690  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.690  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.691  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 09:17:12.691  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:17:12.691  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:17:12.691  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 09:17:12.691  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:17:12.692  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:17:12.692  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 09:17:12.692  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:17:12.692  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 09:17:12.692  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.692  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 09:17:12.692  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.693  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.693  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.693  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.693  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.693  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.693  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.693  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
,10-12 09:17:12.693  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.693  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.694  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.694  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.694  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.696  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.696  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 09:17:12.696  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.696  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.697  5676  5722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 09:17:12.697  5676  5722 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 09:17:12.698  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-12 09:17:12.702  5676  5722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 09:17:12.702  5676  5722 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-12 09:17:12.703  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-12 09:17:12.704  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-12 09:17:12.705  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-12 09:17:12.705  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-12 09:17:12.705  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-12 09:17:12.705  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-12 09:17:12.705  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-12 09:17:12.705  5676  5722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-12 09:17:12.705  5676  5722 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 09:17:12.706  5676  5722 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-12 09:17:12.706  5676  5722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 09:17:12.706  5676  5722 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 09:17:12.706  5676  5722 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-12 09:17:12.706  5676  5722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 09:17:12.706  5676  5722 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 09:17:12.706  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-12 09:17:12.710  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-12 09:17:12.711  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-12 09:17:12.711  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-12 09:17:12.712  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-12 09:17:12.713  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-12 09:17:12.713  5676  5722 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-12 09:17:12.713  5676  5722 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 09:17:12.713  5676  5722 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-12 09:17:12.714  5676  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-12 09:17:12.714  5676  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-12 09:17:12.714  5676  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-12 09:17:12.714  5676  5723 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-12 09:17:12.714  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.714  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.715  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.715  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.715  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.715  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.715  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.715  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-12 09:17:12.718  4827  4827 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33064]" dev="sockfs" ino=33064 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:17:12.718  4827  4827 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33064]" dev="sockfs" ino=33064 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:17:12.716  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.717  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.717  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.717  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.717  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.717  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.717  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.717  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.718  5676  5723 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-12 09:17:12.718  5676  5723 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:17:12.718  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.718  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:12.718  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.718  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.719  5676  5722 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-12 09:17:12.720  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.720  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.721  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.721  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.721  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.721  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.721  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.721  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.721  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.721  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.721  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.721  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.721  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.721  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.721  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.722  5676  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-12 09:17:12.722  5676  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-12 09:17:12.723  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.723  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:12.723  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.723  5676  5724 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-12 09:17:12.723  4616  4825 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
10-12 09:17:12.723  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.723  5676  5723 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-12 09:17:12.723  5676  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-12 09:17:12.723  5676  5723 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-12 09:17:12.724  5676  5722 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-12 09:17:12.724  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.724  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.724  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.724  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.724  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.724  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.724  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.725  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.725  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.725  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.725  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.725  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.725  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.725  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.725  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.726  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.727  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:12.727  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.727  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.728  5676  5722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-12 09:17:12.728  5676  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-12 09:17:12.728  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 09:17:12.728  5676  5722 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-12 09:17:12.728  5676  5722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 09:17:12.728  5676  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-12 09:17:12.728  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 09:17:12.728  5676  5722 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-12 09:17:12.728  5676  5722 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 09:17:12.728  5676  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 09:17:12.728  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 09:17:12.729  5676  5722 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-12 09:17:12.729  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:12.729  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:12.729  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:12.729  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.729  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.729  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.729  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.729  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.729  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.729  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.729  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.730  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.730  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.730  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.730  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.731  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:12.731  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:12.731  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.731  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.732  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:12.732  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.732  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:12.732  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:12.732  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:12.732  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:12.733  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:12.733  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:12.733  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:12.733  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:15.114   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:16.115   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:16.179   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 09:17:17.116   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:17.734  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:17:17.734  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.734  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:17.734  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.734  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:17.735  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:17.735  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:17.735  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:17.736  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:17.736  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:17.736  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:17.736  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:17:17.736  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.736  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:17.737  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:17.737  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.737  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.737  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:17.737  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:17:17.737  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.737  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.738  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.740  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:17.741  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:17.741  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:17:17.741  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.747  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-12 09:17:17.748  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:17:17.751  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 09:17:17.752  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-12 09:17:17.753  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 09:17:17.753  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-12 09:17:17.753  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-12 09:17:17.753  5676  5676 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-12 09:17:17.753  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-12 09:17:17.753  5676  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 09:17:17.754  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:17.754  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 09:17:17.754  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-12 09:17:17.755  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 09:17:17.755  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.755  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:17:17.755  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 09:17:17.755  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:17.755  5676  5676 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-12 09:17:17.755  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.755  5676  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:17:17.755  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:17:17.755  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:17:17.756  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:17:17.756  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.756  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:17.755  4827  4827 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31647]" dev="sockfs" ino=31647 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:17:17.755  4827  4827 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31647]" dev="sockfs" ino=31647 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 09:17:17.758  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:17:17.758  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.758  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:17:17.758  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,10-12 09:17:17.759  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:17:17.759  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:17:17.759  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 09:17:17.759  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 09:17:17.759  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:17.759  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:17:17.759  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.759  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 09:17:17.759  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:17.759  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.760  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.760  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:17:17.760  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.760  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.760  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.760  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.760  5676  5725 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 09:17:17.760  5676  5725 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 09:17:17.761  5676  5725 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 09:17:17.761  5676  5676 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 09:17:17.762  5676  5676 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:17.762  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:17.762  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:17.762  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.762  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.764  5676  5722 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-12 09:17:17.764  5676  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 09:17:17.765  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 09:17:17.765  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:17:17.765  5676  5722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 09:17:17.765  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:17.765  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:17.765  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:17.766  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:17.766  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.766  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.766  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:17.766  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:17.766  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09,:17:17.766  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.766  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:17.766  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.767  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.767  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.767  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.768  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:17.769  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:17.769  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.769  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.776  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:17.776  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:17.776  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:17.776  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:17:17.777  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.777  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:17.777  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:17.777  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:17.777  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.777  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.777  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:17.777  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.777  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.777  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.777  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:17.778  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:17.778  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:17.778  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.779  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.780  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:17:17.780  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:17:17.780  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:17:17.780  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 09:17:17.780  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.780  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.780  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:17:17.780  5676  5722 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8002009 not in the list
10-12 09:17:17.780  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.781  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
10-12 09:17:17.781  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:17.781  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:17:17.781  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.781  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:17.781  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:17.782  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:17:17.782  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:17:17.782  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:17.782  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c6920e not in the list
,10-12 09:17:17.784  5676  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-12 09:17:17.784  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 09:17:17.784  5676  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-12 09:17:17.784  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 09:17:17.784  5676  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-12 09:17:17.784  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-12 09:17:17.787  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-12 09:17:17.787  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-12 09:17:17.788  5676  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,10-12 09:17:17.789  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 09:17:17.789  5676  5722 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-12 09:17:17.789  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 09:17:17.789  5676  5722 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-12 09:17:17.789  5676  5722 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-12 09:17:17.790  5676  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,10-12 09:17:17.790  5676  5722 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-12 09:17:17.790  5676  5722 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,10-12 09:17:17.791  5676  5722 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-12 09:17:17.791  5676  5722 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-12 09:17:17.791  5676  5722 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-12 09:17:17.792  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:17:17.792  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c65a40 added. We now have 3 listener(s)
,10-12 09:17:17.792  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:17:17.794  5676  5722 D BluetoothAdapter: enable(): BT is already enabled..!
,10-12 09:17:17.794   927  3190 D WifiService: setWifiEnabled: true pid=5676, uid=10077
10-12 09:17:17.795   927  3190 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:17:17.849  4616  4820 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
10-12 09:17:17.849  4616  4820 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-12 09:17:18.117   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:18.260  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:17:19.118   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:19.208   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 09:17:20.119   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-12 09:17:21.292   927  2984 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:17:22.800  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 09:17:22.800  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8741d79 added. We now have 4 listener(s)
10-12 09:17:22.800  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:17:22.812  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:17:22.812  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8741d79 removed from the list
10-12 09:17:22.813  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:22.813  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:17:22.813  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:22.814  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:17:22.814  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f019abe added. We now have 4 listener(s)
,10-12 09:17:22.815  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:17:22.817  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:22.817  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f019abe removed from the list
10-12 09:17:22.817  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:17:22.818  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:17:22.818  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:22.820  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:17:22.820  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc8f71f added. We now have 4 listener(s)
10-12 09:17:22.820  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:17:22.825   927   938 D WifiService: setWifiEnabled: false pid=5676, uid=10077
10-12 09:17:22.825   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:17:22.830   927  2984 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-12 09:17:22.830   927  2984 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-12 09:17:22.830   927  2984 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:17:22.831   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:17:22.836  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:17:22.836  4616  4674 D BluetoothAdapterState: Current state: ON, message: 23
10-12 09:17:22.837  4616  4674 D BluetoothAdapterProperties: Setting state to 13
10-12 09:17:22.837  4616  4674 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-12 09:17:22.838  4616  4674 D BluetoothAdapterProperties: onBluetoothDisable()
10-12 09:17:22.839  4616  4674 I BluetoothAdapterState: Entering PendingCommandState
10-12 09:17:22.841  4616  4678 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:17:22.842  4616  4674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-12 09:17:22.848   927  5408 D DhcpClient: Clearing IP address
,10-12 09:17:22.849  4616  4616 D BluetoothMapService: onReceive
10-12 09:17:22.849  4616  4616 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-12 09:17:22.849  4616  4616 D BluetoothMapService: STATE_TURNING_OFF
10-12 09:17:22.849   508   924 D CommandListener: Clearing all IP addresses on wlan0
10-12 09:17:22.849  4616  4616 D BluetoothMapService: MAP Service closeService in
10-12 09:17:22.849  4616  4616 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 09:17:22.850  4616  4616 D ObexServerSockets0: shutdown(block = true)
10-12 09:17:22.850  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.850  4616  4616 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:22.850  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:22.850  4616  4616 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 09:17:22.850  4616  4825 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 09:17:22.854  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.854  4616  4850 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-12 09:17:22.855  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:22.855  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:17:22.855  4616  4849 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-12 09:17:22.856  4616  4616 I BtOppRfcommListener: stopping Accept Thread
10-12 09:17:22.856  4616  5346 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 09:17:22.857  4616  5346 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-12 09:17:22.858   508   924 D CommandListener: Setting iface cfg
10-12 09:17:22.859  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:22.861  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:22.865  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:22.865  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:22.866  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.866  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:17:22.868  3604  5463 V NativeCrypto: Read error: ssl=0x7fa40b7e80: I/O error during system call, Connection timed out
,10-12 09:17:22.869  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:22.870  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:22.871  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.871  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:22.873  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:22.874   927  5409 D DhcpClient: Receive thread stopped
10-12 09:17:22.875  3604  5463 V NativeCrypto: SSL shutdown failed: ssl=0x7fa40b7e80: I/O error during system call, Broken pipe
,10-12 09:17:22.877   927  3181 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,10-12 09:17:22.877   927  5404 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-12 09:17:22.879  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:22.879  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:22.879   927  5404 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-12 09:17:22.880  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:22.880   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-12 09:17:22.880  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:17:22.880   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-12 09:17:22.881   927  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-12 09:17:22.882   927   940 I ActivityManager: Start proc 5729:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-12 09:17:22.883  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:22.883  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:22.884  4616  4616 D HeadsetService: Received stop request...Stopping profile...
,10-12 09:17:22.885  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.885  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:22.885  3811  3836 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:22.886   927   927 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:22.886   927   927 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:22.886  3148  3160 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:22.886  3148  3148 D HeadsetProfile: Bluetooth service disconnected
10-12 09:17:22.887   927   927 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:22.888   927   927 D RttService: SCAN_AVAILABLE : 1
10-12 09:17:22.888   927  3098 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-12 09:17:22.889   534   534 E Parcel  : Reading a NULL string not supported here.
10-12 09:17:22.889   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-12 09:17:22.889   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-12 09:17:22.891  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:22.891  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:22.893  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.893  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:22.894  4616  4616 D A2dpService: Received stop request...Stopping profile...
10-12 09:17:22.895  4616  4830 D A2dpStateMachine: Exit Disconnected: -1
10-12 09:17:22.896   927   927 D BluetoothA2dp: Proxy object disconnected
,10-12 09:17:22.897  4616  4616 V BluetoothAdapterState: isTurningOff()=true
,10-12 09:17:22.897  4616  4616 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:22.897  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:22.897  4616  4616 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:22.897   927  2998 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-12 09:17:22.898  3148  3148 D BluetoothA2dp: Proxy object disconnected
10-12 09:17:22.899  4616  4616 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-12 09:17:22.899  3775  3938 W QCNEJ   : |CORE| network lost: 100
10-12 09:17:22.899  4616  4616 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,10-12 09:17:22.900  4616  4678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-12 09:17:22.900  4616  4820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:22.900  4616  4820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:22.900  4616  4820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:22.900  4616  4678 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-12 09:17:22.900  3775  3938 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-12 09:17:22.901  4616  4616 D HidService: Received stop request...Stopping profile...
10-12 09:17:22.901  4616  4616 D HidService: Stopping Bluetooth HidService
,10-12 09:17:22.907  4616  4616 D HealthService: Received stop request...Stopping profile...
10-12 09:17:22.909  4616  4616 D PanService: Received stop request...Stopping profile...
,10-12 09:17:22.910  4616  4616 D BluetoothMapService: Received stop request...Stopping profile...
,10-12 09:17:22.910  4616  4616 D BluetoothMapService: stop()
,10-12 09:17:22.912  4616  4616 D BluetoothMapAppObserver: deinitObservers()
,10-12 09:17:22.912  4616  4616 D BluetoothMapAppObserver: removeReceiver()
,10-12 09:17:22.914  4616  4616 V BluetoothAdapterState: isTurningOff()=true
,10-12 09:17:22.914  4616  4616 V BluetoothAdapterState: isTurningOn()=false
,10-12 09:17:22.914  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:22.915  4616  4616 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:22.915  4616  4678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 09:17:22.915  4616  4820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:22.916  4616  4820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:22.916  4616  4820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 09:17:22.916  4616  4820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:17:22.916  4616  4820 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 09:17:22.916  4616  4820 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:17:22.917  4616  4616 D SapService: Received stop request...Stopping profile...
,10-12 09:17:22.917  4616  4616 V SapService: stop()
10-12 09:17:22.918  4616  4616 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:22.918  4616  4616 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:22.918  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:22.918  4616  4616 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:22.919  4616  4616 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 09:17:22.919  4616  4616 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 09:17:22.919  4616  4678 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-12 09:17:22.919  4616  4616 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:22.919  4616  4616 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:22.919  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:22.919  4616  4616 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:22.919  4616  4616 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-12 09:17:22.919  4616  4678 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 09:17:22.919  4616  4616 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 09:17:22.920  4616  4616 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:22.920  4616  4616 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:22.920  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:22.920  4616  4616 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:22.920   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 09:17:22.920  4616  4616 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 09:17:22.920  4616  4616 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-12 09:17:22.921  3148  3148 D BluetoothInputDevice: Proxy object disconnected
,10-12 09:17:22.921  3148  3148 D HidProfile: Bluetooth service disconnected
10-12 09:17:22.921  4616  4616 D BluetoothMapService: MAP Service closeService in
10-12 09:17:22.921  3148  3148 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 09:17:22.921  3148  3148 D PanProfile: Bluetooth service disconnected
10-12 09:17:22.921  3148  3148 D BluetoothMap: Proxy object disconnected
10-12 09:17:22.921  3148  3148 D MapProfile: Bluetooth service disconnected
10-12 09:17:22.921  4616  4616 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:22.921  4616  4616 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:22.921  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:22.921  4616  4616 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:22.922  4616  4616 D BluetoothMapService: cleanup()
,10-12 09:17:22.922  4616  4616 D BluetoothMapService: MAP Service closeService in
10-12 09:17:22.922  4616  4616 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:22.923  4616  4616 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:22.923  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:22.923  4616  4616 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:22.924  4616  4674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-12 09:17:22.924  4616  4674 D BluetoothAdapterProperties: Setting state to 15
10-12 09:17:22.924  4616  4674 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 09:17:22.924   927  2984 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-12 09:17:22.924  4616  4674 I BluetoothAdapterState: Entering BleOnState
10-12 09:17:22.925  3148  3162 D BluetoothMap: onBluetoothStateChange: up=false
,10-12 09:17:22.925  3148  4005 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:17:22.925   927  2984 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:17:22.926   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:17:22.926  3148  3160 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 09:17:22.926   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:22.926   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:22.926  3148  4011 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:22.927  3811  4028 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:22.927   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:22.927  3148  3162 D BluetoothPan: onBluetoothStateChange on: false
10-12 09:17:22.928  3148  4005 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 09:17:22.928  4616  4674 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 09:17:22.929  4616  4674 D BluetoothAdapterProperties: Setting state to 16
10-12 09:17:22.929  4616  4674 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 09:17:22.929  4616  4674 D BluetoothAdapterProperties: onBleDisable
10-12 09:17:22.929  4616  4674 I BluetoothAdapterState: Entering PendingCommandState
10-12 09:17:22.929  4616  4675 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-12 09:17:22.930  4616  4678 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:17:22.931  4616  4820 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 09:17:22.931  4616  4820 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:22.933  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:22.933  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:22.935  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:22.935  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:22.937  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:22.937  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:22.938   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 09:17:22.938   508   924 D CommandListener: Clearing all IP addresses on wlan0
10-12 09:17:22.938   508   924 D TetherController: Setting IP forward enable = 0
10-12 09:17:22.939  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:22.939   927  2998 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-12 09:17:22.940   927  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 09:17:22.940  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:22.941   927   944 D Tethering: MasterInitialState.processMessage what=3
10-12 09:17:22.942  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:22.943   927  2984 D DhcpClient: doQuit
10-12 09:17:22.943   927  2984 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 09:17:22.943  5303  5303 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@548b712 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-12 09:17:22.943  3472  3472 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-12 09:17:22.945  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:22.945   927  5408 D DhcpClient: onQuitting
10-12 09:17:22.948  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:22.948  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:22.948  5074  5098 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 09:17:22.948  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.948  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:22.950  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:22.951  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:22.951  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.951  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name:, null
10-12 09:17:22.950  5074  5098 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:17:22.951  5074  5098 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-12 09:17:22.951  5074  5098 E SarControlService: no key has been found,reset the power
10-12 09:17:22.952  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:17:22.952  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:17:22.952  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 09:17:22.952  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.952  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:22.953  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:22.953  5099  5099 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 09:17:22.954  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:22.954  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:17:22.956  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:22.957  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:22.958  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 09:17:22.958  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:17:22.958  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:17:22.959  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:17:22.959  5099  5099 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 09:17:22.960  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000ea03000000000000ffffffff]
10-12 09:17:22.960  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:17:22.960  5099  5113 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-12 09:17:22.960  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:17:22.961  5074  5085 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-12 09:17:22.966  5729  5729 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-12 09:17:22.967  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000eb03000000000000ffffffff]
10-12 09:17:22.967  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:17:22.967  5099  5113 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,10-12 09:17:22.968  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:17:22.968  5074  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 09:17:22.968  3472  3472 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-12 09:17:22.974  3472  3472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-12 09:17:22.976   508   917 W SocketClient: write error (Broken pipe)
10-12 09:17:22.976   508   917 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-12 09:17:22.976   508   917 W SocketListener: Error sending broadcast (Broken pipe)
,10-12 09:17:22.979  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 09:17:22.984   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@269be8c:true
,10-12 09:17:22.986  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:17:22.997   927  5198 I ActivityManager: Start proc 5760:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-12 09:17:22.999   508   924 E Netd    : netlink response contains error (No such file or directory)
,10-12 09:17:23.000   508   924 D TetherController: Setting IP forward enable = 0
,10-12 09:17:23.000   927  2998 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-12 09:17:23.006  3472  3472 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-12 09:17:23.014  3472  3472 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-12 09:17:23.016  5729  5729 D LocalBluetoothProfileManager: Adding local MAP profile
10-12 09:17:23.019   927  2984 D wifi    : In wifi stop Hal
10-12 09:17:23.019  5049  5049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:17:23.019   927  2984 D wifi    : halHandle = 0x7f925a7400, mVM = 0x7faebcd140, mCls = 0x100a02
,10-12 09:17:23.019   927  3471 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 09:17:23.019   927  3471 D WifiHAL : Got a signal to exit!!!
,10-12 09:17:23.019   927  3471 I WifiHAL : Exit wifi_event_loop
10-12 09:17:23.019   927  2984 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-12 09:17:23.019   927  2984 E WifiHAL : Event processing terminated
10-12 09:17:23.020   927  2984 D wifi    : In wifi cleaned up handler
10-12 09:17:23.020   927  2984 I WifiHAL : Internal cleanup completed
10-12 09:17:23.022  5729  5729 D BluetoothMap: Create BluetoothMap proxy object
10-12 09:17:23.022  4079  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:17:23.022  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:23.024  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:23.025  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:23.035  5729  5729 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-12 09:17:23.041   927  3471 D wifi    : set interface wlan0 flags (DOWN)
,10-12 09:17:23.042   927  2984 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 09:17:23.049  5760  5760 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-12 09:17:23.053  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:17:23.061   927  3190 I ActivityManager: Killing 5014:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-12 09:17:23.138  4616  4678 I bt_hci  : shut_down
,10-12 09:17:23.143  4616  4684 D bt_hwcfg: hw_epilog_process
,10-12 09:17:23.143  4616  4684 I bt_vendor: low_power_mode_cb
,10-12 09:17:23.146  4616  4684 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-12 09:17:23.146  4616  4684 I bt_vendor: epilog_cb
10-12 09:17:23.146  4616  4684 I bt_hci  : epilog_finished_callback
,10-12 09:17:23.148  4616  4678 I bt_hci_h4: hal_close
10-12 09:17:23.149  4616  4678 I bt_userial_vendor: device fd = 54 close
,10-12 09:17:23.244   927   944 D Tethering: InitialState.processMessage what=4
,10-12 09:17:23.247   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-12 09:17:23.261  4616  4675 D bt_stack_manager: event_shut_down_stack finished.
,10-12 09:17:23.261  4616  4674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-12 09:17:23.263  4616  4674 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-12 09:17:23.263  4616  4616 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 09:17:23.264  4616  4616 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 09:17:23.264  4616  4616 D BtGatt.GattService: stop()
10-12 09:17:23.265  4616  4616 D BtGatt.AdvertiseManager: advertise clients cleared
,10-12 09:17:23.267  4616  4616 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:17:23.267  4616  4616 V BluetoothAdapterState: isTurningOn()=false
,10-12 09:17:23.267  4616  4616 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:23.267  4616  4616 V BluetoothAdapterState: isBleTurningOff()=true
10-12 09:17:23.267  4616  4674 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-12 09:17:23.267  4616  4674 D BluetoothAdapterProperties: Setting state to 10
10-12 09:17:23.267  4616  4674 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-12 09:17:23.268  4616  4674 I BluetoothAdapterState: Entering OffState
10-12 09:17:23.269   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-12 09:17:23.275  4616  4616 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-12 09:17:23.275  4616  4616 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-12 09:17:23.275  4616  4616 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-12 09:17:23.276  4616  4675 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-12 09:17:23.285  4616  4616 I art     : System.exit called, status: 0
,10-12 09:17:23.286  4616  4616 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-12 09:17:23.328  5760  5760 D StrictMode: StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-12 09:17:23.328  5760  5760 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.328  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:17:23.329  5760  5760 D StrictMode: StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:17:23.329  5760  5760 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:17:23.329   927  3190 I ActivityManager: Process com.android.bluetooth (pid 4616) has died
10-12 09:17:23.329  5760  5760 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.k.d(PG:583)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:17:23.329  5760  5760 D StrictMode: StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:17:23.329  5760  5760 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.329  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:17:23.331  5760  5760 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:17:23.331  5760  5760 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:17:23.337  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 09:17:23.351   927  3618 I ActivityManager: Start proc 5795:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
10-12 09:17:23.355  5729  5729 D DockEventReceiver: finishStartingService: stopping service
10-12 09:17:23.357   927  5198 I ActivityManager: Killing 5483:com.qualcomm.timeservice/1000 (adj 15): empty #17
,10-12 09:17:23.433  5795  5795 D AdapterServiceConfig: Adding HeadsetService
10-12 09:17:23.434  5795  5795 D AdapterServiceConfig: Adding A2dpService
10-12 09:17:23.434  5795  5795 D AdapterServiceConfig: Adding HidService
10-12 09:17:23.434  5795  5795 D AdapterServiceConfig: Adding HealthService
,10-12 09:17:23.434  5795  5795 D AdapterServiceConfig: Adding PanService
10-12 09:17:23.434  5795  5795 D AdapterServiceConfig: Adding GattService
10-12 09:17:23.434  5795  5795 D AdapterServiceConfig: Adding BluetoothMapService
10-12 09:17:23.434  5795  5795 D AdapterServiceConfig: Adding SapService
10-12 09:17:23.437   927  3190 I ActivityManager: Killing 5467:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-12 09:17:23.465  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:17:23.476  3721  3721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 09:17:23.480  3721  3721 D SystemUpdateService: onCreate
,10-12 09:17:23.484  3721  3721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 09:17:23.493  3721  3721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-12 09:17:23.498  3721  5433 I iu.UploadsManager: num queued entries: 0
10-12 09:17:23.498  3721  5433 I iu.UploadsManager: num updated entries: 0
,10-12 09:17:23.500  3721  3721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 09:17:23.502  3721  3721 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 09:17:23.503  3721  5807 I SystemUpdateService: active receiver: enabled
,10-12 09:17:23.513   927   937 I ActivityManager: Start proc 5809:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-12 09:17:23.517  3721  5433 I iu.SyncManager: NEXT; no task
,10-12 09:17:23.522  3721  5807 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 09:17:23.530  3721  5807 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-12 09:17:23.530  3721  5807 I SystemUpdateService: now status is 0 (complete)
10-12 09:17:23.530  3721  5807 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 09:17:23.530  3721  5807 I SystemUpdateService: file has been verified
10-12 09:17:23.530  3721  5807 I SystemUpdateService: OTA package size = 21989297
,10-12 09:17:23.551  5809  5809 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-12 09:17:23.555  3721  5807 I SystemUpdateService: showing system update notification
,10-12 09:17:23.560  5809  5809 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:17:23.565  5809  5809 D SprintDMHelper: simOperator: 
,10-12 09:17:23.566  5809  5809 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 09:17:23.577   927  3189 I ActivityManager: Start proc 5821:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-12 09:17:23.607  3721  3721 D SystemUpdateService: onDestroy
,10-12 09:17:23.609   927  3618 I ActivityManager: Killing 5303:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-12 09:17:23.677  5049  5835 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-12 09:17:23.683   927  5198 I ActivityManager: Start proc 5836:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-12 09:17:23.685   927   938 I ActivityManager: Killing 4700:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-12 09:17:23.735  5836  5836 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-12 09:17:23.889  5760  5781 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-12 09:17:23.919   927  5198 I ActivityManager: Killing 5148:com.google.android.deskclock/u0a66 (adj 15): empty #17
,10-12 09:17:23.933   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f7f72ec:true
,10-12 09:17:23.967   927   937 I ActivityManager: Start proc 5850:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-12 09:17:23.998  5850  5850 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-12 09:17:24.006   927  3618 I ActivityManager: Killing 5536:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-12 09:17:27.858   927  3181 D WifiService: setWifiEnabled: true pid=5676, uid=10077
,10-12 09:17:27.859   927  3181 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:17:27.869   508   924 D SoftapController: Softap fwReload - Ok
,10-12 09:17:27.873   508   924 D CommandListener: Setting iface cfg
,10-12 09:17:27.874   508   924 D CommandListener: Trying to bring down wlan0
,10-12 09:17:27.875   508   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:17:27.881   927  2984 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 09:17:28.451   927  2984 D wifi    : set interface wlan0 flags (UP)
,10-12 09:17:28.453   927  2984 I WifiHAL : Initializing wifi
,10-12 09:17:28.453   927  2984 I WifiHAL : Creating socket
,10-12 09:17:28.454   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-12 09:17:28.457   927  2984 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-12 09:17:28.458   927  2984 D wifi    : Did set static halHandle = 0x7f925a7400
10-12 09:17:28.458   927  2984 D wifi    : halHandle = 0x7f925a7400, mVM = 0x7faebcd140, mCls = 0x101972
10-12 09:17:28.458   927  2984 D wifi    : array field set
10-12 09:17:28.458   927  2984 I WifiNative-HAL: interface[0] = wlan0
,10-12 09:17:28.460   927  5868 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547916248064
,10-12 09:17:28.460   927  5868 D wifi    : waitForHalEvents called, vm = 0x7faebcd140, obj = 0x101972, env = 0x7f8f544080
,10-12 09:17:28.465   927  2984 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 09:17:28.470  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:28.471  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:28.472  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:28.528  5869  5869 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 09:17:28.540  5869  5869 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:17:28.571  5869  5869 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:17:28.571  5869  5869 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 09:17:28.585   927  2984 D WifiConfigStore: Loading config and enabling all networks 
,10-12 09:17:28.587  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:28.588  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:28.588  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:28.588  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:28.589  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:28.589  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:28.589  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:28.589  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:17:28.592  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:28.592  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:28.592  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:28.592  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:17:28.597   927  2984 D WifiConfigStore: loaded 0 passpoint configs
,10-12 09:17:28.597   927  2984 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-12 09:17:28.598   927  2984 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-12 09:17:28.599   927  2984 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-12 09:17:28.600   927  2984 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-12 09:17:28.600   927  2984 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 09:17:28.601   927  2984 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 09:17:28.601   927  2984 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-12 09:17:28.605   927  2984 D WifiNative-HAL: Setting external_sim to 1
,10-12 09:17:28.605  5049  5049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:17:28.605   927  2984 D wifi    : setting dfs flag to true, 0x7f96e7cae0
10-12 09:17:28.606   927  2984 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 09:17:28.606   927  2984 D wifi    : setting scan oui 0x7f96e7cae0
10-12 09:17:28.606   927  2984 D WifiHAL : Sending mac address OUI
,10-12 09:17:28.610   927  2984 E native  : do suspend false
,10-12 09:17:28.618   927  2984 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-12 09:17:28.618   927   927 D RttService: SCAN_AVAILABLE : 3
10-12 09:17:28.618   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 09:17:28.618   927  3098 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 09:17:28.619   508   924 D CommandListener: Setting iface cfg
,10-12 09:17:28.624   927  2983 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-12 09:17:28.624   927  2983 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-12 09:17:28.632   927  2983 D WifiNative-HAL: p2pGetDeviceAddress
,10-12 09:17:28.636   927  2983 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 09:17:28.636   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267907 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-12 09:17:31.771  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:17:31.775  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:17:31.782  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:17:31.831   927  2984 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-12 09:17:31.832   927  2984 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-12 09:17:31.832   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:17:31.844   927  2984 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 09:17:31.879   927  2984 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 09:17:31.881  5869  5869 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 09:17:32.323  5869  5869 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 09:17:32.357  5869  5869 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 09:17:32.358  5869  5869 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 09:17:32.367   927  2984 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 09:17:32.368   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-12 09:17:32.368   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 09:17:32.383   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:17:32.396   508   924 D CommandListener: Setting iface cfg
,10-12 09:17:32.403   927  2984 D WifiStateMachine: Start Dhcp Watchdog 2
,10-12 09:17:32.413   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-12 09:17:32.413   927  2984 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-12 09:17:32.413   927  2998 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-12 09:17:32.416   927  5877 D DhcpClient: Receive thread started
,10-12 09:17:32.496   927  2984 E native  : do suspend false
,10-12 09:17:32.509   927  5876 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 09:17:32.524   927  5877 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172569, domain null
10-12 09:17:32.525   927  5876 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172569 seconds
,10-12 09:17:32.527   927  5876 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 09:17:32.539   927  5877 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
10-12 09:17:32.540   927  5876 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-12 09:17:32.543   508   924 D CommandListener: Setting iface cfg
,10-12 09:17:32.548   927  2984 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 09:17:32.553   927  5876 D DhcpClient: Scheduling renewal in 86399s
,10-12 09:17:32.560   927  2984 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 09:17:32.562   927  2984 D WifiConfigStore: No blacklist allowed without epno enabled
10-12 09:17:32.563   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-12 09:17:32.565   927  2998 D ConnectivityService: Adding iface wlan0 to network 101
,10-12 09:17:32.580   927  2984 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-12 09:17:32.610   927  2998 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-12 09:17:32.610   927  2998 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
10-12 09:17:32.613   927  2998 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-12 09:17:32.617   927  2998 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-12 09:17:32.619   927  2998 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-12 09:17:32.626   927  2998 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-12 09:17:32.629   927  2998 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-12 09:17:32.629   927  2998 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-12 09:17:32.629   927  2998 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-12 09:17:32.629   927  2984 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-12 09:17:32.629   927  2998 D ConnectivityService:    accepting network in place of null
10-12 09:17:32.629   927  2984 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:17:32.630   927  2998 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 09:17:32.645   927  5875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271916, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-12 09:17:32.650   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:17:32.671   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:17:32.674   927  2998 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-12 09:17:32.674  3775  3938 W QCNEJ   : |CORE| network available: 101
,10-12 09:17:32.674   927  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 09:17:32.675   927  2998 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-12 09:17:32.679  3775  3938 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-12 09:17:32.681  3775  3938 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-12 09:17:32.682  3775  3938 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-12 09:17:32.682   927   944 D Tethering: MasterInitialState.processMessage what=3
,10-12 09:17:32.683  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:32.683  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:32.684  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.684  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:17:32.686  5074  5098 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 09:17:32.686  5074  5098 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:17:32.686  5074  5098 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-12 09:17:32.687  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:32.687  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:32.687  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.687  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:17:32.689  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.689  5074  5098 E SarControlService: no key has been found,reset the power
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:17:32.689  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 09:17:32.689  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:17:32.689  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:32.689  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:17:32.689  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:17:32.690  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 09:17:32.690  3721  3721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 09:17:32.692  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-12 09:17:32.692  5099  5099 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 09:17:32.693  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 09:17:32.693  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:17:32.694  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:17:32.694  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:17:32.694  5099  5099 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-12 09:17:32.698  3721  3721 D SystemUpdateService: onCreate
,10-12 09:17:32.700  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000ec03000000000000ffffffff]
,10-12 09:17:32.700  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:17:32.700  5099  5113 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-12 09:17:32.700  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:17:32.701  5074  5085 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 09:17:32.702  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000ed03000000000000ffffffff]
10-12 09:17:32.702  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:17:32.703  5099  5113 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-12 09:17:32.703  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:17:32.703  5074  5084 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 09:17:32.704  3721  3721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 09:17:32.713  3721  3721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 09:17:32.718  3721  5433 I iu.UploadsManager: num queued entries: 0
,10-12 09:17:32.718  3721  5433 I iu.UploadsManager: num updated entries: 0
,10-12 09:17:32.720  3721  5887 I SystemUpdateService: active receiver: enabled
,10-12 09:17:32.724  3721  3721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 09:17:32.725  3721  3721 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 09:17:32.726  5809  5809 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:17:32.730  5809  5809 D SprintDMHelper: simOperator: 
,10-12 09:17:32.730  5809  5809 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 09:17:32.739   927  5874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,10-12 09:17:32.752  3721  5887 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 09:17:32.753  3721  5433 I iu.SyncManager: NEXT; no task
,10-12 09:17:32.766  3721  5887 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-12 09:17:32.766  3721  5887 I SystemUpdateService: now status is 0 (complete)
10-12 09:17:32.766  3721  5887 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 09:17:32.766  3721  5887 I SystemUpdateService: file has been verified
10-12 09:17:32.766  3721  5887 I SystemUpdateService: OTA package size = 21989297
,10-12 09:17:32.771  3721  5887 I SystemUpdateService: showing system update notification
,10-12 09:17:32.780  3721  3721 D SystemUpdateService: onDestroy
,10-12 09:17:32.802   927  5874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 13:17:32 GMT], X-Android-Received-Millis=[1476278252802], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476278252778]}
,10-12 09:17:32.803   927  2998 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-12 09:17:32.803   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-12 09:17:32.803   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-12 09:17:32.804   927  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 09:17:32.842  5049  5892 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-12 09:17:32.869   927  3869 D WifiService: setWifiEnabled: false pid=5676, uid=10077
,10-12 09:17:32.869   927  3869 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:17:32.870   927  2984 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-12 09:17:32.870   927  2984 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-12 09:17:32.871   927  2984 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:17:32.871   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:17:32.877   927  5876 D DhcpClient: Clearing IP address
,10-12 09:17:32.877   508   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:17:32.879   508   924 D CommandListener: Setting iface cfg
10-12 09:17:32.881   927  5877 D DhcpClient: Receive thread stopped
,10-12 09:17:32.884  3604  5898 V NativeCrypto: Read error: ssl=0x7f93e07380: I/O error during system call, Connection timed out
,10-12 09:17:32.885  3604  5898 V NativeCrypto: SSL shutdown failed: ssl=0x7f93e07380: I/O error during system call, Broken pipe
,10-12 09:17:32.890   927  3181 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
10-12 09:17:32.891   927  5874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-12 09:17:32.891   927  5874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
10-12 09:17:32.894   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-12 09:17:32.894   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-12 09:17:32.896   534   534 E Parcel  : Reading a NULL string not supported here.
10-12 09:17:32.900   927   927 D RttService: SCAN_AVAILABLE : 1
,10-12 09:17:32.900   927  3098 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 09:17:32.901   927  2998 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-12 09:17:32.903   927  2984 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-12 09:17:32.904  3775  3938 W QCNEJ   : |CORE| network lost: 101
10-12 09:17:32.904   927  5874 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-12 09:17:32.905  3775  3938 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-12 09:17:32.907   927  2984 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 09:17:32.924   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:17:32.943   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:17:32.944   927  2998 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-12 09:17:32.944   508   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:17:32.944   927  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 09:17:32.945   927   944 D Tethering: MasterInitialState.processMessage what=3
10-12 09:17:32.947  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:32.947  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:32.947  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.948  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:32.949  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:32.949  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:32.949  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.949  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:32.949   927  2984 D DhcpClient: doQuit
10-12 09:17:32.949   927  2984 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 09:17:32.950  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:32.950  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:32.950  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.950  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:32.950  5869  5869 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-12 09:17:32.950   927  5876 D DhcpClient: onQuitting
10-12 09:17:32.951  5074  5098 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 09:17:32.951  5074  5098 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:17:32.951  5074  5098 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,10-12 09:17:32.951  5074  5098 E SarControlService: no key has been found,reset the power
10-12 09:17:32.951  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:17:32.951  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:17:32.951  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 09:17:32.952  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:17:32.952  5099  5099 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-12 09:17:32.954  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-12 09:17:32.954  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:17:32.954  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:17:32.955  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:17:32.955  5099  5099 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 09:17:32.956  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:32.956  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:32.956  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.956  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:32.957  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:32.957  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:32.957  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.957  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:32.958  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMo,nitor:     - is Wi-Fi enabled: false
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:32.959  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:32.959  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:32.959  3721  3721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 09:17:32.959  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:32.960  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000ee03000000000000ffffffff]
10-12 09:17:32.960  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:17:32.960  5099  5113 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-12 09:17:32.960  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:17:32.961  5074  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 09:17:32.964  3721  3721 D SystemUpdateService: onCreate
10-12 09:17:32.964  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000ef03000000000000ffffffff]
10-12 09:17:32.965  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:17:32.965  5099  5113 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-12 09:17:32.966  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:17:32.966  5074  5085 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-12 09:17:32.969  3721  3721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-12 09:17:32.971  5869  5869 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-12 09:17:32.976  5869  5869 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-12 09:17:32.976  3721  3721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-12 09:17:32.980  3721  5907 I SystemUpdateService: active receiver: enabled
,10-12 09:17:32.984  3721  3721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 09:17:32.985  3721  3721 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 09:17:32.987  5809  5809 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 09:17:32.991  5809  5809 D SprintDMHelper: simOperator: 
,10-12 09:17:32.991  5809  5809 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 09:17:32.992  5869  5869 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-12 09:17:32.982  3721  5433 I iu.UploadsManager: num queued entries: 0
,10-12 09:17:33.001  3721  5433 I iu.UploadsManager: num updated entries: 0
,10-12 09:17:33.004  5869  5869 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-12 09:17:33.006  5049  5911 I Babel   : connection state changed from CONNECTED to DISCONNECTED
10-12 09:17:33.009   508   924 E Netd    : netlink response contains error (No such file or directory)
,10-12 09:17:33.010  5049  5049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:17:33.010   927  2998 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-12 09:17:33.010   927  2998 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 09:17:33.010   927  2984 D wifi    : In wifi stop Hal
10-12 09:17:33.010   927  2984 D wifi    : halHandle = 0x7f925a7400, mVM = 0x7faebcd140, mCls = 0x101972
10-12 09:17:33.011   927  5868 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 09:17:33.011   927  5868 D WifiHAL : Got a signal to exit!!!
10-12 09:17:33.011   927  5868 I WifiHAL : Exit wifi_event_loop
10-12 09:17:33.011   927  2984 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-12 09:17:33.011   927  2984 E WifiHAL : Event processing terminated
,10-12 09:17:33.011   927  2984 D wifi    : In wifi cleaned up handler
,10-12 09:17:33.011   927  2984 I WifiHAL : Internal cleanup completed
10-12 09:17:33.013  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:33.014  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:33.015  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:33.016  4079  4246 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 09:17:33.015  3721  5907 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 09:17:33.024  3721  5433 I iu.SyncManager: NEXT; no task
,10-12 09:17:33.024  3721  5907 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-12 09:17:33.025  3721  5907 I SystemUpdateService: now status is 0 (complete)
10-12 09:17:33.025  3721  5907 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 09:17:33.025  3721  5907 I SystemUpdateService: file has been verified
10-12 09:17:33.025  3721  5907 I SystemUpdateService: OTA package size = 21989297
,10-12 09:17:33.030  3721  5907 I SystemUpdateService: showing system update notification
,10-12 09:17:33.037   927  5868 D wifi    : set interface wlan0 flags (DOWN)
,10-12 09:17:33.037   927  2984 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 09:17:33.039  3721  3721 D SystemUpdateService: onDestroy
,10-12 09:17:33.239   927   944 D Tethering: InitialState.processMessage what=4
,10-12 09:17:33.245   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-12 09:17:33.675   927  2998 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-12 09:17:35.120   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:36.121   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:37.122   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:37.901   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@87520b0:true
,10-12 09:17:37.902  5795  5795 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 09:17:37.906  5795  5795 I bt_bluedroid: init
,10-12 09:17:37.906  5795  5913 I BluetoothAdapterState: Entering OffState
,10-12 09:17:37.910  5795  5914 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-12 09:17:37.910  5795  5914 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 09:17:37.910  5795  5914 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-12 09:17:37.910  5795  5914 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-12 09:17:37.911  5795  5795 I bt_bluedroid: get_profile_interface socket
,10-12 09:17:37.913  5795  5917 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 09:17:37.914  5795  5795 I bt_bluedroid: get_profile_interface sdp
,10-12 09:17:37.916  5795  5917 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 09:17:37.922  5795  5806 I bt_bluedroid: config_hci_snoop_log
,10-12 09:17:37.924   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-12 09:17:37.929  5795  5913 D BluetoothAdapterState: Current state: OFF, message: 0
,10-12 09:17:37.929  5795  5913 D BluetoothAdapterProperties: Setting state to 14
,10-12 09:17:37.929  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-12 09:17:37.931  5795  5913 D BluetoothBondStateMachine: make
10-12 09:17:37.933  5795  5918 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 09:17:37.936  5795  5913 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:17:37.938  5795  5795 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 09:17:37.941  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:37.942  5795  5795 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 09:17:37.943  5795  5795 D BtGatt.GattService: Received start request. Starting profile...
10-12 09:17:37.943  5795  5795 D BtGatt.GattService: start()
10-12 09:17:37.943  5795  5795 I bt_bluedroid: get_profile_interface gatt
,10-12 09:17:37.945  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:17:37.945  5795  5795 D BtGatt.AdvertiseManager: advertise manager created
,10-12 09:17:37.952  5795  5795 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:17:37.952  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:37.952  5795  5795 V BluetoothAdapterState: isBleTurningOn()=true
10-12 09:17:37.952  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:37.952  5795  5913 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-12 09:17:37.954  5795  5913 I bt_bluedroid: bt_bluedroid
10-12 09:17:37.954  5795  5914 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-12 09:17:37.955  5795  5914 I bt_hci  : start_up
,10-12 09:17:37.961  5795  5914 I bt_vendor: alloc value 0xf3dec871
,10-12 09:17:37.962  5795  5914 I bt_vendor: init
10-12 09:17:37.962  5795  5914 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 09:17:37.962  5795  5914 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 09:17:38.072  5795  5914 D bt_hci  : start_up starting async portion
10-12 09:17:38.073  5795  5921 I bt_hci  : event_finish_startup
10-12 09:17:38.073  5795  5921 I bt_hci_h4: hal_open
,10-12 09:17:38.073  5795  5921 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-12 09:17:38.076  5795  5921 I bt_userial_vendor: device fd = 54 open
,10-12 09:17:38.071  5922  5922 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 09:17:38.090  5795  5921 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 09:17:38.095  5795  5921 D bt_hwcfg: Chipset BCM4358A3
10-12 09:17:38.095  5795  5921 D bt_hwcfg: Target name = [BCM4358A3]
10-12 09:17:38.095  5795  5921 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 09:17:38.123   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:38.486  5795  5921 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-12 09:17:38.487  5795  5921 D bt_hwcfg: Settlement delay -- 100 ms
10-12 09:17:38.487  5795  5921 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 09:17:38.620  5795  5921 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 09:17:38.621  5795  5921 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-12 09:17:38.622  5795  5921 I bt_hwcfg: vendor lib fwcfg completed
,10-12 09:17:38.622  5795  5921 I bt_vendor: firmware callback
10-12 09:17:38.622  5795  5921 I bt_hci  : firmware_config_callback
10-12 09:17:38.631  5795  5924 I bt_btu  : btu_task pending for preload complete event
,10-12 09:17:38.631  5795  5924 I bt_btu_task: Bluetooth chip preload is complete
10-12 09:17:38.631  5795  5924 I bt_btu  : btu_task received preload complete event
,10-12 09:17:38.639  5795  5924 I         : BTE_InitTraceLevels -- TRC_HCI
10-12 09:17:38.639  5795  5924 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_AVDT
10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_AVRC
10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_A2D
10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_BNEP
10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_BTM
10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_GAP
,10-12 09:17:38.640  5795  5924 I         : BTE_InitTraceLevels -- TRC_PAN
10-12 09:17:38.641  5795  5924 I         : BTE_InitTraceLevels -- TRC_SDP
10-12 09:17:38.641  5795  5924 I         : BTE_InitTraceLevels -- TRC_GATT
10-12 09:17:38.641  5795  5924 I         : BTE_InitTraceLevels -- TRC_SMP
10-12 09:17:38.641  5795  5924 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-12 09:17:38.641  5795  5924 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 09:17:38.724  5795  5924 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d6a549
10-12 09:17:38.724  5795  5924 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d6a549 
,10-12 09:17:38.734  5795  5917 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 09:17:38.735  5795  5917 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-12 09:17:38.736  5795  5917 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-12 09:17:38.738  5795  5917 D BluetoothAdapterProperties: Name is: Nexus 6P
10-12 09:17:38.741  5795  5917 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:17:38.741  5795  5917 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 09:17:38.742  5795  5917 D bt_hci  : do_postload posting postload work item
10-12 09:17:38.742  5795  5921 I bt_hci  : event_postload
10-12 09:17:38.742  5795  5921 I bt_vendor: sco_config_cb
10-12 09:17:38.742  5795  5921 I bt_hci  : sco_config_callback postload finished.
,10-12 09:17:38.746  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:38.750  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:38.751  5795  5921 I bt_vendor: low_power_mode_cb
10-12 09:17:38.752  5795  5917 D bt_bte_conf: Device ID record 1 : primary
,10-12 09:17:38.752  5795  5917 D bt_bte_conf:   vendorId            = 000f
10-12 09:17:38.752  5795  5917 D bt_bte_conf:   vendorIdSource      = 0001
,10-12 09:17:38.752  5795  5917 D bt_bte_conf:   product             = 1200
10-12 09:17:38.752  5795  5917 D bt_bte_conf:   version             = 1436
10-12 09:17:38.752  5795  5917 D bt_bte_conf:   clientExecutableURL = 
10-12 09:17:38.753  5795  5917 D bt_bte_conf:   serviceDescription  = 
10-12 09:17:38.753  5795  5917 D bt_bte_conf:   documentationURL    = 
10-12 09:17:38.754  5795  5917 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-12 09:17:38.755  5795  5914 D bt_stack_manager: event_start_up_stack finished
10-12 09:17:38.755  5795  5913 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-12 09:17:38.757  5795  5913 D BluetoothAdapterProperties: Setting state to 15
10-12 09:17:38.757  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-12 09:17:38.757  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:38.758  5795  5913 I BluetoothAdapterState: Entering BleOnState
,10-12 09:17:38.761  5795  5913 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-12 09:17:38.761  5795  5913 D BluetoothAdapterProperties: Setting state to 11
10-12 09:17:38.761  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-12 09:17:38.765  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:38.767  5795  5795 D HeadsetService: Received start request. Starting profile...
10-12 09:17:38.769  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:38.773  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:38.774  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:38.775  5795  5795 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 09:17:38.775  5795  5795 D HeadsetStateMachine: make
,10-12 09:17:38.782  5795  5913 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:17:38.784  5795  5795 D HeadsetStateMachine: max_hf_connections = 1
,10-12 09:17:38.784  5795  5795 I bt_bluedroid: get_profile_interface handsfree
10-12 09:17:38.784  5795  5917 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-12 09:17:38.784  5795  5917 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,10-12 09:17:38.787  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:38.788  5795  5795 D A2dpService: Received start request. Starting profile...
10-12 09:17:38.789  5795  5795 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-12 09:17:38.789  5795  5795 I bt_bluedroid: get_profile_interface avrcp
,10-12 09:17:38.794  5795  5795 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-12 09:17:38.795  5795  5795 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 09:17:38.795  5795  5795 D A2dpStateMachine: make
10-12 09:17:38.796  5795  5795 I bt_bluedroid: get_profile_interface a2dp
,10-12 09:17:38.796  5795  5917 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-12 09:17:38.798  5795  5932 D A2dpStateMachine: Enter Disconnected: -2
,10-12 09:17:38.799  5795  5795 I BluetoothHidServiceJni: classInitNative: succeeds
,10-12 09:17:38.800  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 09:17:38.800  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:38.803  5729  5729 D BluetoothInputDevice: Proxy object connected
,10-12 09:17:38.803  5795  5795 D HidService: Received start request. Starting profile...
10-12 09:17:38.803  5795  5795 I bt_bluedroid: get_profile_interface hidhost
10-12 09:17:38.803  5795  5917 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d4b56d
10-12 09:17:38.803  5795  5795 D HidService: setHidService(): set to: null
10-12 09:17:38.804  5729  5729 D HidProfile: Bluetooth service connected
10-12 09:17:38.804  5795  5917 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-12 09:17:38.804  5795  5795 I BluetoothHealthServiceJni: classInitNative: succeeds
10-12 09:17:38.805  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:38.806  5795  5795 D HealthService: Received start request. Starting profile...
,10-12 09:17:38.807  5795  5795 I bt_bluedroid: get_profile_interface health
,10-12 09:17:38.807  5795  5795 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-12 09:17:38.808  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:17:38.809  5729  5729 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 09:17:38.809  5795  5795 D PanService: Received start request. Starting profile...
10-12 09:17:38.810  5795  5795 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 09:17:38.810  5795  5795 I bt_bluedroid: get_profile_interface pan
10-12 09:17:38.810  5729  5729 D PanProfile: Bluetooth service connected
10-12 09:17:38.810  5795  5917 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-12 09:17:38.813  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:38.814  5729  5729 D BluetoothMap: Proxy object connected
,10-12 09:17:38.815  5729  5729 D MapProfile: Bluetooth service connected
10-12 09:17:38.815  5729  5729 D BluetoothMap: getConnectedDevices()
10-12 09:17:38.815  5795  5795 D BluetoothMapService: Received start request. Starting profile...
10-12 09:17:38.815  5795  5795 D BluetoothMapService: start()
,10-12 09:17:38.818  5795  5795 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-12 09:17:38.819  5795  5795 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-12 09:17:38.819  5795  5795 D BluetoothMapAppObserver: createReceiver()
10-12 09:17:38.820  5795  5795 D BluetoothMapAppObserver: initObservers()
10-12 09:17:38.821  5795  5795 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-12 09:17:38.827  5795  5795 V SapService: SapBinder()
,10-12 09:17:38.827  5795  5795 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:38.827  5795  5795 D SapService: Received start request. Starting profile...
,10-12 09:17:38.827  5795  5795 V SapService: start()
10-12 09:17:38.830  5795  5795 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:38.830  5795  5795 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:38.830  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:38.830  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:38.830  5795  5795 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:38.830  5795  5795 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:38.830  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:38.831  5795  5930 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:38.831  5795  5795 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:38.832  5795  5795 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:38.832  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:38.832  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:38.832  5795  5795 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:38.832  5795  5795 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:38.832  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 09:17:38.832  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:38.833  5795  5795 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:38.833  5795  5795 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:38.833  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:38.833  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:38.833  5795  5913 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-12 09:17:38.833  5795  5913 D BluetoothAdapterProperties: ScanMode =  20
10-12 09:17:38.833  5729  5729 D BluetoothMap: Bluetooth is Not enabled
10-12 09:17:38.833  5795  5913 D BluetoothAdapterProperties: State =  11
10-12 09:17:38.835  5795  5917 D BluetoothAdapterProperties: Scan Mode:21
10-12 09:17:38.835  5795  5917 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 09:17:38.835  5795  5913 D BluetoothAdapterProperties: Setting state to 12
,10-12 09:17:38.835  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-12 09:17:38.835  5676  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 09:17:38.835  5795  5913 I BluetoothAdapterState: Entering OnState
10-12 09:17:38.836  5729  5749 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 09:17:38.837  3148  3160 D BluetoothMap: onBluetoothStateChange: up=true
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:38.838  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:38.838  3148  3148 D BluetoothMap: Proxy object connected
10-12 09:17:38.839  3148  3148 D MapProfile: Bluetooth service connected
10-12 09:17:38.839  3148  3162 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:17:38.839  3148  3148 D BluetoothMap: getConnectedDevices()
10-12 09:17:38.840   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:17:38.841  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:38.841  5729  5740 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:17:38.842  5729  5741 D BluetoothMap: onBluetoothStateChange: up=true
10-12 09:17:38.842  3148  4011 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:17:38.842  3148  3148 D BluetoothA2dp: Proxy object connected
10-12 09:17:38.842   927   927 D BluetoothA2dp: Proxy object connected
10-12 09:17:38.844   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:38.844  5729  5749 D BluetoothPan: onBluetoothStateChange on: true
10-12 09:17:38.844   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:38.845  3148  3162 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:38.845  3148  3148 D BluetoothInputDevice: Proxy object connected
10-12 09:17:38.845  3148  3148 D HidProfile: Bluetooth service connected
10-12 09:17:38.845  3811  4028 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:38.846  5795  5795 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 09:17:38.846   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:38.846  3148  3160 D BluetoothPan: onBluetoothStateChange on: true
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:38.846  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:38.846  5795  5795 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-12 09:17:38.848  3148  3148 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 09:17:38.848  3148  4005 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 09:17:38.848  3148  3148 D PanProfile: Bluetooth service connected
10-12 09:17:38.849  5795  5795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:17:38.849  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:38.850   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,10-12 09:17:38.854  5795  5795 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:38.854  5729  5729 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:38.855  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:38.857  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:38.857  5676  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 09:17:38.858  5729  5729 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-12 09:17:38.859  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:38.859  5795  5795 D ObexServerSockets: Succeed to create listening sockets 
10-12 09:17:38.859  5795  5795 D ObexServerSockets0: startAccept()
10-12 09:17:38.860  5795  5795 D ObexServerSockets0: prepareForNewConnect()
10-12 09:17:38.860  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:38.862  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:38.862  5795  5795 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-12 09:17:38.863  5795  5795 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-12 09:17:38.863  5795  5795 D BluetoothMapService: onReceive
,10-12 09:17:38.863  5795  5795 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 09:17:38.863  5795  5795 D BluetoothMapService: STATE_ON
10-12 09:17:38.864  5795  5941 D ObexServerSockets0: Accepting socket connection...
10-12 09:17:38.864  5795  5940 D ObexServerSockets0: Accepting socket connection...
,10-12 09:17:38.865  5795  5942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:38.866  5795  5942 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 09:17:38.867  5795  5942 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-12 09:17:38.868  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 09:17:38.871  5729  5729 D BluetoothA2dp: Proxy object connected
,10-12 09:17:38.875  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:17:38.877  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:17:38.882  3148  3148 D BluetoothPbap: Proxy object connected
10-12 09:17:38.882  5729  5729 D BluetoothPbap: Proxy object connected
10-12 09:17:38.882  3148  3148 D PbapServerProfile: Bluetooth service connected
10-12 09:17:38.883  5729  5729 D PbapServerProfile: Bluetooth service connected
,10-12 09:17:38.888  5795  5795 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-12 09:17:38.889  5795  5795 D ObexServerSockets0: prepareForNewConnect()
,10-12 09:17:38.892  5795  5946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:38.905  5795  5950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:38.906  5795  5950 I BtOppRfcommListener: Accept thread started.
,10-12 09:17:38.946  3811  3836 D BluetoothHeadset: Proxy object connected
,10-12 09:17:38.946   927   927 D BluetoothHeadset: Proxy object connected
10-12 09:17:38.946  3811  3834 D BluetoothHeadset: Proxy object connected
,10-12 09:17:38.946   927   927 D BluetoothHeadset: Proxy object connected
,10-12 09:17:38.947   927   944 D BluetoothHeadset: Proxy object connected
10-12 09:17:38.947  3148  3160 D BluetoothHeadset: Proxy object connected
10-12 09:17:38.947  3148  3148 D HeadsetProfile: Bluetooth service connected
10-12 09:17:38.947   927   927 D BluetoothHeadset: Proxy object connected
,10-12 09:17:38.961  5729  5749 D BluetoothHeadset: Proxy object connected
,10-12 09:17:38.962  5729  5729 D HeadsetProfile: Bluetooth service connected
,10-12 09:17:39.124   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:17:40.124   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-12 09:17:40.633   927  2998 D ConnectivityService: handlePromptUnvalidated 101
,10-12 09:17:42.886  5795  5913 D BluetoothAdapterState: Current state: ON, message: 23
,10-12 09:17:42.886  5795  5913 D BluetoothAdapterProperties: Setting state to 13
10-12 09:17:42.887  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-12 09:17:42.888  5795  5913 D BluetoothAdapterProperties: onBluetoothDisable()
10-12 09:17:42.892  5795  5913 I BluetoothAdapterState: Entering PendingCommandState
10-12 09:17:42.897  5795  5795 D BluetoothMapService: onReceive
10-12 09:17:42.897  5795  5795 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 09:17:42.897  5795  5795 D BluetoothMapService: STATE_TURNING_OFF
10-12 09:17:42.898  5795  5795 D BluetoothMapService: MAP Service closeService in
10-12 09:17:42.898  5795  5917 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:17:42.898  5795  5795 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 09:17:42.898  5795  5795 D ObexServerSockets0: shutdown(block = true)
10-12 09:17:42.898  5795  5913 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-12 09:17:42.899  5795  5940 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-12 09:17:42.901  5795  5795 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-12 09:17:42.901  5795  5941 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-12 09:17:42.903  5795  5795 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 09:17:42.903  5795  5926 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-12 09:17:42.907  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:42.907  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:17:42.909  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:42.909  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:42.912  5795  5795 I BtOppRfcommListener: stopping Accept Thread
10-12 09:17:42.912  5795  5950 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,10-12 09:17:42.913  5795  5950 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-12 09:17:42.914  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:42.914  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:42.915  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:42.915  5795  5795 D HeadsetService: Received stop request...Stopping profile...
10-12 09:17:42.915  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:17:42.919  5795  5795 D A2dpService: Received stop request...Stopping profile...
,10-12 09:17:42.919  5729  5740 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:42.920  5795  5932 D A2dpStateMachine: Exit Disconnected: -1
10-12 09:17:42.920  3811  3836 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:42.920   927   927 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:42.920   927   927 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:42.921  3148  4005 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:42.921  3148  3148 D HeadsetProfile: Bluetooth service disconnected
10-12 09:17:42.921   927   927 D BluetoothHeadset: Proxy object disconnected
10-12 09:17:42.921  3148  3148 D BluetoothA2dp: Proxy object disconnected
10-12 09:17:42.921  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:42.921  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:17:42.922  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 09:17:42.922   927   927 D BluetoothA2dp: Proxy object disconnected
,10-12 09:17:42.922  5795  5795 D HidService: Received stop request...Stopping profile...
,10-12 09:17:42.922  5676  5676 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 09:17:42.922  5795  5795 D HidService: Stopping Bluetooth HidService
10-12 09:17:42.922  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:42.924  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.925  3148  3148 D BluetoothInputDevice: Proxy object disconnected
10-12 09:17:42.925  3148  3148 D HidProfile: Bluetooth service disconnected
10-12 09:17:42.925  5729  5729 D HeadsetProfile: Bluetooth service disconnected
10-12 09:17:42.925  5729  5729 D BluetoothA2dp: Proxy object disconnected
10-12 09:17:42.926  5795  5795 D HealthService: Received stop request...Stopping profile...
,10-12 09:17:42.928  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.928  5729  5729 D DockEventReceiver: finishStartingService: stopping service
10-12 09:17:42.929  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.929  5795  5795 D PanService: Received stop request...Stopping profile...
10-12 09:17:42.930  5729  5729 D BluetoothInputDevice: Proxy object disconnected
,10-12 09:17:42.930  5729  5729 D HidProfile: Bluetooth service disconnected
10-12 09:17:42.930  5729  5729 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-12 09:17:42.930  5729  5729 D PanProfile: Bluetooth service disconnected
10-12 09:17:42.930  3148  3148 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 09:17:42.930  3148  3148 D PanProfile: Bluetooth service disconnected
10-12 09:17:42.931  5795  5795 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:42.931  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:42.931  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:42.931  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:42.932  5795  5795 D BluetoothMapService: Received stop request...Stopping profile...
10-12 09:17:42.932  5795  5795 D BluetoothMapService: stop()
10-12 09:17:42.932  5795  5795 D BluetoothMapAppObserver: deinitObservers()
10-12 09:17:42.932  5795  5795 D BluetoothMapAppObserver: removeReceiver()
,10-12 09:17:42.934  3148  3148 D BluetoothMap: Proxy object disconnected
,10-12 09:17:42.934  3148  3148 D MapProfile: Bluetooth service disconnected
10-12 09:17:42.934  5729  5729 D BluetoothMap: Proxy object disconnected
10-12 09:17:42.934  5729  5729 D MapProfile: Bluetooth service disconnected
,10-12 09:17:42.936  5795  5795 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-12 09:17:42.936  5795  5795 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-12 09:17:42.936  5795  5924 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:42.936  5795  5924 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:42.936  5795  5924 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:42.936  5795  5917 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-12 09:17:42.936  5795  5917 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-12 09:17:42.936  5795  5795 D SapService: Received stop request...Stopping profile...
10-12 09:17:42.936  5795  5795 V SapService: stop()
10-12 09:17:42.937  5795  5795 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:42.937  5795  5795 V BluetoothAdapterState: isTurningOn()=false
,10-12 09:17:42.937  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 09:17:42.937  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:42.938  5795  5917 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 09:17:42.938  5795  5795 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:42.938  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:42.938  5795  5924 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 09:17:42.938  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 09:17:42.938  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:42.938  5795  5924 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-12 09:17:42.939  5795  5924 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-12 09:17:42.939  5795  5795 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 09:17:42.939  5795  5795 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 09:17:42.939  5795  5924 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:17:42.939  5795  5924 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 09:17:42.939  5795  5924 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 09:17:42.939  5795  5795 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:42.939  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:42.939  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:42.939  5795  5917 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-12 09:17:42.939  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:42.940  5795  5795 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-12 09:17:42.940  5795  5917 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 09:17:42.942  5795  5795 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 09:17:42.941  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 09:17:42.942  5795  5795 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:42.942  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:42.942  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:42.942  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:42.942  5795  5795 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 09:17:42.942  5795  5795 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-12 09:17:42.943  5795  5795 D BluetoothMapService: MAP Service closeService in
10-12 09:17:42.943  5795  5795 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:42.943  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:42.943  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:42.943  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:42.943  5795  5795 D BluetoothMapService: cleanup()
10-12 09:17:42.943  5795  5795 D BluetoothMapService: MAP Service closeService in
10-12 09:17:42.943  5795  5795 V BluetoothAdapterState: isTurningOff()=true
10-12 09:17:42.944  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:42.944  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:42.944  5795  5795 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:42.944  5795  5913 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-12 09:17:42.944  5795  5913 D BluetoothAdapterProperties: Setting state to 15
10-12 09:17:42.944  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 09:17:42.945  3148  3148 D BluetoothPbap: Proxy object disconnected
10-12 09:17:42.945  3148  3148 D PbapServerProfile: Bluetooth service disconnected
10-12 09:17:42.945  5729  5729 D BluetoothPbap: Proxy object disconnected
10-12 09:17:42.945  5795  5913 I BluetoothAdapterState: Entering BleOnState
10-12 09:17:42.946  5729  5729 D PbapServerProfile: Bluetooth service disconnected
10-12 09:17:42.946  5729  5741 D BluetoothPbap: onBluetoothStateChange: up=false
,10-12 09:17:42.948  5729  5740 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-12 09:17:42.948  3148  4005 D BluetoothMap: onBluetoothStateChange: up=false
10-12 09:17:42.948  3148  4011 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:17:42.949   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:17:42.949  5729  5749 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 09:17:42.950  5729  5741 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 09:17:42.950  5729  5740 D BluetoothMap: onBluetoothStateChange: up=false
10-12 09:17:42.951  3148  3162 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 09:17:42.951   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:42.951  5729  5749 D BluetoothPan: onBluetoothStateChange on: false
10-12 09:17:42.952   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-12 09:17:42.952  3148  3160 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:42.952  3811  3834 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:42.953   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 09:17:42.953  3148  4005 D BluetoothPan: onBluetoothStateChange on: false
10-12 09:17:42.953  3148  4011 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 09:17:42.954  5795  5913 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 09:17:42.954  5795  5913 D BluetoothAdapterProperties: Setting state to 16
10-12 09:17:42.954  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 09:17:42.955  5795  5913 D BluetoothAdapterProperties: onBleDisable
10-12 09:17:42.955  5795  5913 I BluetoothAdapterState: Entering PendingCommandState
10-12 09:17:42.955  5795  5914 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-12 09:17:42.957  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.958  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 09:17:42.958  5795  5924 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 09:17:42.959  5795  5924 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-12 09:17:42.959  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.960  5795  5917 D BluetoothAdapterProperties: Scan Mode:20
10-12 09:17:42.960  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.962  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.963  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:42.967  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:17:42.969  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:42.977  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:17:43.165  5795  5917 I bt_hci  : shut_down
,10-12 09:17:43.170  5795  5921 D bt_hwcfg: hw_epilog_process
,10-12 09:17:43.170  5795  5921 I bt_vendor: low_power_mode_cb
,10-12 09:17:43.172  5795  5921 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-12 09:17:43.172  5795  5921 I bt_vendor: epilog_cb
10-12 09:17:43.172  5795  5921 I bt_hci  : epilog_finished_callback
,10-12 09:17:43.174  5795  5917 I bt_hci_h4: hal_close
10-12 09:17:43.174  5795  5917 I bt_userial_vendor: device fd = 54 close
,10-12 09:17:43.285  5795  5914 D bt_stack_manager: event_shut_down_stack finished.
,10-12 09:17:43.286  5795  5913 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-12 09:17:43.290  5795  5795 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 09:17:43.290  5795  5913 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-12 09:17:43.291  5795  5795 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 09:17:43.291  5795  5795 D BtGatt.GattService: stop()
10-12 09:17:43.291  5795  5795 D BtGatt.AdvertiseManager: advertise clients cleared
,10-12 09:17:43.294  5795  5795 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:17:43.294  5795  5795 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:43.294  5795  5795 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:43.294  5795  5795 V BluetoothAdapterState: isBleTurningOff()=true
,10-12 09:17:43.295  5795  5913 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-12 09:17:43.296  5795  5913 D BluetoothAdapterProperties: Setting state to 10
10-12 09:17:43.297  5795  5913 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-12 09:17:43.297  5795  5913 I BluetoothAdapterState: Entering OffState
10-12 09:17:43.298   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-12 09:17:43.310  5795  5795 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-12 09:17:43.310  5795  5795 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-12 09:17:43.310  5795  5795 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-12 09:17:43.313  5795  5914 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-12 09:17:43.321  5795  5795 I art     : System.exit called, status: 0
10-12 09:17:43.322  5795  5795 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-12 09:17:43.359   927  3181 I ActivityManager: Process com.android.bluetooth (pid 5795) has died
,10-12 09:17:47.886  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:47.886  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:47.891  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:17:47.892  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc8f71f removed from the list
10-12 09:17:47.892  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:47.892  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:47.892  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:47.894  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:17:47.895  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f901835 added. We now have 4 listener(s)
,10-12 09:17:47.895  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:17:47.899  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:17:47.899  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f901835 removed from the list
10-12 09:17:47.899  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:47.899  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:17:47.900  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:17:47.902  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:17:47.902  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b8a4ca added. We now have 4 listener(s)
10-12 09:17:47.903  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:17:52.913  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:52.947   927   944 I ActivityManager: Start proc 5960:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 09:17:53.034  5960  5960 D AdapterServiceConfig: Adding HeadsetService
,10-12 09:17:53.034  5960  5960 D AdapterServiceConfig: Adding A2dpService
,10-12 09:17:53.045  5960  5960 D AdapterServiceConfig: Adding HidService
,10-12 09:17:53.046  5960  5960 D AdapterServiceConfig: Adding HealthService
10-12 09:17:53.046  5960  5960 D AdapterServiceConfig: Adding PanService
10-12 09:17:53.046  5960  5960 D AdapterServiceConfig: Adding GattService
10-12 09:17:53.046  5960  5960 D AdapterServiceConfig: Adding BluetoothMapService
10-12 09:17:53.046  5960  5960 D AdapterServiceConfig: Adding SapService
,10-12 09:17:53.056   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ee38e9:true
,10-12 09:17:53.056  5960  5960 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 09:17:53.060  5960  5960 I bt_bluedroid: init
,10-12 09:17:53.062  5960  5972 I BluetoothAdapterState: Entering OffState
,10-12 09:17:53.065  5960  5973 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-12 09:17:53.065  5960  5973 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 09:17:53.065  5960  5973 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-12 09:17:53.065  5960  5973 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-12 09:17:53.066  5960  5960 I bt_bluedroid: get_profile_interface socket
,10-12 09:17:53.068  5960  5976 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 09:17:53.068  5960  5960 I bt_bluedroid: get_profile_interface sdp
10-12 09:17:53.069  5960  5976 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 09:17:53.077  5960  5971 I bt_bluedroid: config_hci_snoop_log
,10-12 09:17:53.078   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
10-12 09:17:53.081  5960  5972 D BluetoothAdapterState: Current state: OFF, message: 0
,10-12 09:17:53.081  5960  5972 D BluetoothAdapterProperties: Setting state to 14
10-12 09:17:53.081  5960  5972 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-12 09:17:53.084  5960  5972 D BluetoothBondStateMachine: make
,10-12 09:17:53.085  5960  5977 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 09:17:53.088  5960  5972 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:17:53.089  5960  5960 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 09:17:53.091  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:17:53.093  5960  5960 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 09:17:53.094  5960  5960 D BtGatt.GattService: Received start request. Starting profile...
10-12 09:17:53.094  5960  5960 D BtGatt.GattService: start()
10-12 09:17:53.094  5960  5960 I bt_bluedroid: get_profile_interface gatt
,10-12 09:17:53.095  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:53.095  5960  5960 D BtGatt.AdvertiseManager: advertise manager created
,10-12 09:17:53.101  5960  5960 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:17:53.101  5960  5960 V BluetoothAdapterState: isTurningOn()=false
10-12 09:17:53.101  5960  5960 V BluetoothAdapterState: isBleTurningOn()=true
10-12 09:17:53.101  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:53.102  5960  5972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-12 09:17:53.103  5960  5972 I bt_bluedroid: bt_bluedroid
,10-12 09:17:53.104  5960  5973 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-12 09:17:53.104  5960  5973 I bt_hci  : start_up
,10-12 09:17:53.110  5960  5973 I bt_vendor: alloc value 0xf3e3b871
,10-12 09:17:53.110  5960  5973 I bt_vendor: init
10-12 09:17:53.110  5960  5973 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 09:17:53.110  5960  5973 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 09:17:53.220  5960  5973 D bt_hci  : start_up starting async portion
10-12 09:17:53.220  5960  5980 I bt_hci  : event_finish_startup
,10-12 09:17:53.220  5960  5980 I bt_hci_h4: hal_open
10-12 09:17:53.220  5960  5980 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-12 09:17:53.218  5981  5981 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 09:17:53.223  5960  5980 I bt_userial_vendor: device fd = 54 open
,10-12 09:17:53.242  5960  5980 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 09:17:53.245  5960  5980 D bt_hwcfg: Chipset BCM4358A3
,10-12 09:17:53.245  5960  5980 D bt_hwcfg: Target name = [BCM4358A3]
10-12 09:17:53.246  5960  5980 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 09:17:53.758  5960  5980 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-12 09:17:53.758  5960  5980 D bt_hwcfg: Settlement delay -- 100 ms
10-12 09:17:53.760  5960  5980 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 09:17:53.893  5960  5980 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 09:17:53.894  5960  5980 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-12 09:17:53.896  5960  5980 I bt_hwcfg: vendor lib fwcfg completed
10-12 09:17:53.897  5960  5980 I bt_vendor: firmware callback
10-12 09:17:53.897  5960  5980 I bt_hci  : firmware_config_callback
,10-12 09:17:53.908  5960  5983 I bt_btu  : btu_task pending for preload complete event
,10-12 09:17:53.908  5960  5983 I bt_btu_task: Bluetooth chip preload is complete
10-12 09:17:53.908  5960  5983 I bt_btu  : btu_task received preload complete event
,10-12 09:17:53.917  5960  5983 I         : BTE_InitTraceLevels -- TRC_HCI
,10-12 09:17:53.917  5960  5983 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-12 09:17:53.917  5960  5983 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_AVDT
10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_AVRC
10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_A2D
,10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_BNEP
10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_BTM
10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_GAP
,10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_PAN
10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_SDP
10-12 09:17:53.918  5960  5983 I         : BTE_InitTraceLevels -- TRC_GATT
10-12 09:17:53.919  5960  5983 I         : BTE_InitTraceLevels -- TRC_SMP
10-12 09:17:53.919  5960  5983 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-12 09:17:53.919  5960  5983 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 09:17:54.012  5960  5983 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3db9549
10-12 09:17:54.012  5960  5983 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3db9549 
,10-12 09:17:54.038  5960  5976 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 09:17:54.040  5960  5976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 09:17:54.041  5960  5976 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 09:17:54.043  5960  5976 D BluetoothAdapterProperties: Name is: Nexus 6P
10-12 09:17:54.046  5960  5976 D BluetoothAdapterProperties: Scan Mode:20
,10-12 09:17:54.046  5960  5976 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 09:17:54.047  5960  5976 D bt_hci  : do_postload posting postload work item
10-12 09:17:54.047  5960  5980 I bt_hci  : event_postload
,10-12 09:17:54.047  5960  5980 I bt_vendor: sco_config_cb
10-12 09:17:54.047  5960  5980 I bt_hci  : sco_config_callback postload finished.
,10-12 09:17:54.052  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:54.057  5960  5976 D bt_bte_conf: Device ID record 1 : primary
10-12 09:17:54.057  5960  5976 D bt_bte_conf:   vendorId            = 000f
10-12 09:17:54.057  5960  5976 D bt_bte_conf:   vendorIdSource      = 0001
10-12 09:17:54.057  5960  5976 D bt_bte_conf:   product             = 1200
,10-12 09:17:54.057  5960  5976 D bt_bte_conf:   version             = 1436
10-12 09:17:54.057  5960  5976 D bt_bte_conf:   clientExecutableURL = 
10-12 09:17:54.057  5960  5976 D bt_bte_conf:   serviceDescription  = 
10-12 09:17:54.057  5960  5976 D bt_bte_conf:   documentationURL    = 
10-12 09:17:54.058  5960  5976 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-12 09:17:54.058  5960  5973 D bt_stack_manager: event_start_up_stack finished
10-12 09:17:54.058  5960  5980 I bt_vendor: low_power_mode_cb
,10-12 09:17:54.059  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:54.059  5960  5972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-12 09:17:54.059  5960  5972 D BluetoothAdapterProperties: Setting state to 15
10-12 09:17:54.059  5960  5972 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-12 09:17:54.061  5960  5972 I BluetoothAdapterState: Entering BleOnState
,10-12 09:17:54.064  5960  5972 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-12 09:17:54.064  5960  5972 D BluetoothAdapterProperties: Setting state to 11
10-12 09:17:54.064  5960  5972 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-12 09:17:54.072  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:54.074  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:54.076  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:54.082  5960  5960 D HeadsetService: Received start request. Starting profile...
10-12 09:17:54.085  5960  5960 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 09:17:54.085  5960  5960 D HeadsetStateMachine: make
10-12 09:17:54.088  5960  5972 I BluetoothAdapterState: Entering PendingCommandState
,10-12 09:17:54.094  5960  5960 D HeadsetStateMachine: max_hf_connections = 1
,10-12 09:17:54.094  5960  5960 I bt_bluedroid: get_profile_interface handsfree
10-12 09:17:54.094  5960  5976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-12 09:17:54.094  5960  5976 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
10-12 09:17:54.097  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:17:54.098  5960  5960 D A2dpService: Received start request. Starting profile...
10-12 09:17:54.098  5960  5960 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-12 09:17:54.099  5960  5960 I bt_bluedroid: get_profile_interface avrcp
,10-12 09:17:54.105  5960  5960 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-12 09:17:54.105  5960  5960 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 09:17:54.106  5960  5960 D A2dpStateMachine: make
,10-12 09:17:54.107  5960  5960 I bt_bluedroid: get_profile_interface a2dp
10-12 09:17:54.107  5960  5976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-12 09:17:54.110  5960  5991 D A2dpStateMachine: Enter Disconnected: -2
,10-12 09:17:54.110  5960  5960 I BluetoothHidServiceJni: classInitNative: succeeds
10-12 09:17:54.111  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:17:54.111  5960  5960 D HidService: Received start request. Starting profile...
10-12 09:17:54.112  5960  5960 I bt_bluedroid: get_profile_interface hidhost
10-12 09:17:54.112  5960  5960 D HidService: setHidService(): set to: null
10-12 09:17:54.112  5960  5976 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d9a56d
10-12 09:17:54.112  5960  5976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-12 09:17:54.112  5960  5960 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-12 09:17:54.113  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:17:54.114  5960  5960 D HealthService: Received start request. Starting profile...
,10-12 09:17:54.116  5960  5960 I bt_bluedroid: get_profile_interface health
,10-12 09:17:54.117  5960  5960 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-12 09:17:54.117  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:54.118  5960  5960 D PanService: Received start request. Starting profile...
10-12 09:17:54.118  5960  5960 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 09:17:54.118  5960  5960 I bt_bluedroid: get_profile_interface pan
10-12 09:17:54.119  5960  5976 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-12 09:17:54.121  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:17:54.122  5960  5960 D BluetoothMapService: Received start request. Starting profile...
10-12 09:17:54.122  5960  5960 D BluetoothMapService: start()
,10-12 09:17:54.124  5960  5960 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-12 09:17:54.125  5960  5960 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-12 09:17:54.125  5960  5960 D BluetoothMapAppObserver: createReceiver()
10-12 09:17:54.127  5960  5960 D BluetoothMapAppObserver: initObservers()
10-12 09:17:54.127  5960  5960 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-12 09:17:54.134  5960  5960 V SapService: SapBinder()
10-12 09:17:54.135  5960  5960 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
,10-12 09:17:54.135  5960  5960 D SapService: Received start request. Starting profile...
10-12 09:17:54.135  5960  5960 V SapService: start()
,10-12 09:17:54.139  5960  5960 V BluetoothAdapterState: isTurningOff()=false
,10-12 09:17:54.139  5960  5960 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:54.139  5960  5960 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:54.140  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:54.140  5960  5960 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:54.140  5960  5960 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:54.140  5960  5960 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:54.140  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 09:17:54.140  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:54.140  5960  5989 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 09:17:54.140  5960  5960 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:54.140  5960  5960 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:54.141  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:54.142  5960  5960 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:54.142  5960  5960 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:54.142  5960  5960 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:54.142  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
10-12 09:17:54.143  5960  5960 V BluetoothAdapterState: isTurningOff()=false
10-12 09:17:54.143  5960  5960 V BluetoothAdapterState: isTurningOn()=true
10-12 09:17:54.143  5960  5960 V BluetoothAdapterState: isBleTurningOn()=false
10-12 09:17:54.143  5960  5960 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 09:17:54.143  5960  5972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-12 09:17:54.143  5960  5972 D BluetoothAdapterProperties: ScanMode =  20
10-12 09:17:54.143  5960  5972 D BluetoothAdapterProperties: State =  11
10-12 09:17:54.144  5960  5972 D BluetoothAdapterProperties: Setting state to 12
10-12 09:17:54.144  5960  5972 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-12 09:17:54.145  5960  5972 I BluetoothAdapterState: Entering OnState
10-12 09:17:54.145  5729  5749 D BluetoothPbap: onBluetoothStateChange: up=true
,10-12 09:17:54.146  5960  5976 D BluetoothAdapterProperties: Scan Mode:21
10-12 09:17:54.146  5960  5976 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 09:17:54.147  5676  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-12 09:17:54.148  5729  5741 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:54.149  3148  4011 D BluetoothMap: onBluetoothStateChange: up=true
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:54.151  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 09:17:54.152  3148  3148 D BluetoothMap: Proxy object connected
10-12 09:17:54.152  3148  3148 D MapProfile: Bluetooth service connected
10-12 09:17:54.152  3148  3148 D BluetoothMap: getConnectedDevices()
10-12 09:17:54.152  3148  3160 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:17:54.153  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:54.154   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:17:54.155  5729  5740 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:17:54.155  5960  5960 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-12 09:17:54.156  5960  5960 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-12 09:17:54.157  5729  5749 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 09:17:54.158  5729  5741 D BluetoothMap: onBluetoothStateChange: up=true
,10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:54.159  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:17:54.160  5960  5960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:54.160  3148  4005 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 09:17:54.161  5960  5960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 09:17:54.161  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:17:54.162   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:54.162  5729  5741 D BluetoothPan: onBluetoothStateChange on: true
,10-12 09:17:54.162  5960  5960 D ObexServerSockets: Succeed to create listening sockets 
10-12 09:17:54.163  5960  5960 D ObexServerSockets0: startAccept()
10-12 09:17:54.163  5960  5960 D ObexServerSockets0: prepareForNewConnect()
10-12 09:17:54.164   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:54.164  3148  3162 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:54.165  3811  4028 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:54.165  5960  5960 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-12 09:17:54.165  5960  5960 D BluetoothSdpJni: SDP Create record success - handle: 0
10-12 09:17:54.165   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 09:17:54.165  5960  5998 D ObexServerSockets0: Accepting socket connection...
10-12 09:17:54.165  3148  4011 D BluetoothPan: onBluetoothStateChange on: true
10-12 09:17:54.166  5729  5729 D BluetoothMap: Proxy object connected
10-12 09:17:54.166  5729  5729 D MapProfile: Bluetooth service connected
10-12 09:17:54.166  5729  5729 D BluetoothMap: getConnectedDevices()
10-12 09:17:54.166  5960  5999 D ObexServerSockets0: Accepting socket connection...
10-12 09:17:54.166   927   927 D BluetoothA2dp: Proxy object connected
10-12 09:17:54.167  3148  3148 D BluetoothA2dp: Proxy object connected
,10-12 09:17:54.170  5729  5729 D BluetoothA2dp: Proxy object connected
,10-12 09:17:54.170  3148  3160 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 09:17:54.171  3148  3148 D BluetoothInputDevice: Proxy object connected
10-12 09:17:54.171  3148  3148 D HidProfile: Bluetooth service connected
,10-12 09:17:54.171  5729  5729 D BluetoothInputDevice: Proxy object connected
10-12 09:17:54.172  5729  5729 D HidProfile: Bluetooth service connected
10-12 09:17:54.172   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-12 09:17:54.173  5676  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 09:17:54.174  5960  5960 D BluetoothMapService: onReceive
,10-12 09:17:54.174  5960  5960 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 09:17:54.174  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:17:54.175  5960  5960 D BluetoothMapService: STATE_ON
10-12 09:17:54.175  5729  5729 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 09:17:54.175  5729  5729 D PanProfile: Bluetooth service connected
10-12 09:17:54.176  3148  3148 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 09:17:54.176  3148  3148 D PanProfile: Bluetooth service connected
10-12 09:17:54.176  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:17:54.178  5960  6001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:54.179  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 09:17:54.180  5960  6001 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 09:17:54.180  5960  6001 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-12 09:17:54.186  3604  3604 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 09:17:54.186  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-12 09:17:54.192  5729  5729 D BluetoothPbap: Proxy object connected
10-12 09:17:54.193  5729  5729 D PbapServerProfile: Bluetooth service connected
,10-12 09:17:54.195  3148  3148 D BluetoothPbap: Proxy object connected
10-12 09:17:54.195  3148  3148 D PbapServerProfile: Bluetooth service connected
,10-12 09:17:54.199  5960  5960 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-12 09:17:54.199  5960  5960 D ObexServerSockets0: prepareForNewConnect()
10-12 09:17:54.201  5960  6005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:54.214  5960  6009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 09:17:54.216  5960  6009 I BtOppRfcommListener: Accept thread started.
,10-12 09:17:54.251  5729  5740 D BluetoothHeadset: Proxy object connected
10-12 09:17:54.251  3811  3836 D BluetoothHeadset: Proxy object connected
10-12 09:17:54.251   927   927 D BluetoothHeadset: Proxy object connected
,10-12 09:17:54.251   927   927 D BluetoothHeadset: Proxy object connected
10-12 09:17:54.252  3148  3162 D BluetoothHeadset: Proxy object connected
10-12 09:17:54.252  3148  3148 D HeadsetProfile: Bluetooth service connected
10-12 09:17:54.252   927   927 D BluetoothHeadset: Proxy object connected
10-12 09:17:54.254  5729  5729 D HeadsetProfile: Bluetooth service connected
,10-12 09:17:54.263   927   944 D BluetoothHeadset: Proxy object connected
,10-12 09:17:54.264   927   944 D BluetoothHeadset: Proxy object connected
,10-12 09:17:54.264  3148  4011 D BluetoothHeadset: Proxy object connected
10-12 09:17:54.265  3148  3148 D HeadsetProfile: Bluetooth service connected
,10-12 09:17:54.266  3811  3834 D BluetoothHeadset: Proxy object connected
,10-12 09:17:54.267   927   944 D BluetoothHeadset: Proxy object connected
,10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:17:57.930  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:17:57.936  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:17:57.937  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:17:57.937  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b8a4ca removed from the list
10-12 09:17:57.937  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:17:57.937  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:17:57.938  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:17:57.942  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 09:17:57.943  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe63b added. We now have 4 listener(s)
,10-12 09:17:57.943  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 09:17:57.946   927  3874 D WifiService: setWifiEnabled: false pid=5676, uid=10077
,10-12 09:17:57.946   927  3874 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:18:00.125   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:01.126   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:02.127   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:02.957  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:18:02.960   927  3181 D WifiService: setWifiEnabled: true pid=5676, uid=10077
,10-12 09:18:02.960   927  3181 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 09:18:02.969   508   924 D SoftapController: Softap fwReload - Ok
,10-12 09:18:02.975   508   924 D CommandListener: Setting iface cfg
,10-12 09:18:02.975   508   924 D CommandListener: Trying to bring down wlan0
10-12 09:18:02.976   508   924 D CommandListener: Clearing all IP addresses on wlan0
,10-12 09:18:02.983   927  2984 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 09:18:03.129   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:03.657   927  2984 D wifi    : set interface wlan0 flags (UP)
,10-12 09:18:03.659   927  2984 I WifiHAL : Initializing wifi
,10-12 09:18:03.659   927  2984 I WifiHAL : Creating socket
,10-12 09:18:03.667   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-12 09:18:03.667   927  2984 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-12 09:18:03.668   927  2984 D wifi    : Did set static halHandle = 0x7f925a7400
10-12 09:18:03.668   927  2984 D wifi    : halHandle = 0x7f925a7400, mVM = 0x7faebcd140, mCls = 0x15ee
10-12 09:18:03.668   927  2984 D wifi    : array field set
10-12 09:18:03.668   927  2984 I WifiNative-HAL: interface[0] = wlan0
,10-12 09:18:03.671   927  6014 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547916248064
,10-12 09:18:03.671   927  6014 D wifi    : waitForHalEvents called, vm = 0x7faebcd140, obj = 0x15ee, env = 0x7f8f544980
,10-12 09:18:03.728  6015  6015 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 09:18:03.750  6015  6015 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:18:03.761  6015  6015 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 09:18:03.761  6015  6015 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 09:18:03.772   927  2984 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 09:18:03.778  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:18:03.781  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:18:03.791   927  2984 D WifiConfigStore: Loading config and enabling all networks 
,10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:18:03.796  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:18:03.798  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 09:18:03.801  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 09:18:03.803  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 09:18:03.804   927  2984 D WifiConfigStore: loaded 0 passpoint configs
10-12 09:18:03.804   927  2984 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-12 09:18:03.804   927  2984 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-12 09:18:03.805   927  2984 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-12 09:18:03.806   927  2984 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-12 09:18:03.807   927  2984 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 09:18:03.807   927  2984 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 09:18:03.807   927  2984 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-12 09:18:03.810   927  2984 D WifiNative-HAL: Setting external_sim to 1
,10-12 09:18:03.811  5049  5049 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 09:18:03.811   927  2984 D wifi    : setting dfs flag to true, 0x7f968ff3a0
10-12 09:18:03.811   927  2984 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 09:18:03.811   927  2984 D wifi    : setting scan oui 0x7f968ff3a0
10-12 09:18:03.812   927  2984 D WifiHAL : Sending mac address OUI
,10-12 09:18:03.816   927  2984 E native  : do suspend false
,10-12 09:18:03.826   927  2984 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-12 09:18:03.826   927   927 D RttService: SCAN_AVAILABLE : 3
10-12 09:18:03.826   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 09:18:03.827   927  3098 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-12 09:18:03.827   508   924 D CommandListener: Setting iface cfg
,10-12 09:18:03.832   927  2983 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
10-12 09:18:03.832   927  2983 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-12 09:18:03.842   927  2983 D WifiNative-HAL: p2pGetDeviceAddress
10-12 09:18:03.843   927  2983 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 09:18:03.849   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=303120 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,10-12 09:18:04.130   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:05.131   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-12 09:18:07.037  6015  6015 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:18:07.046  6015  6015 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:18:07.052  6015  6015 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:18:07.059  6015  6015 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 09:18:07.084   927  2984 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-12 09:18:07.084   927  2984 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-12 09:18:07.085   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:18:07.095   927  2984 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 09:18:07.130   927  2984 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 09:18:07.132  6015  6015 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 09:18:07.552  6015  6015 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 09:18:07.586  6015  6015 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 09:18:07.587  6015  6015 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 09:18:07.592   927  2984 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 09:18:07.592   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-12 09:18:07.593   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 09:18:07.605   927  2984 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 09:18:07.615   508   924 D CommandListener: Setting iface cfg
,10-12 09:18:07.619   927  2984 D WifiStateMachine: Start Dhcp Watchdog 3
,10-12 09:18:07.627   927  2984 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-12 09:18:07.627   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-12 09:18:07.627   927  2998 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-12 09:18:07.647   927  6020 D DhcpClient: Receive thread started
,10-12 09:18:07.726   927  2984 E native  : do suspend false
,10-12 09:18:07.738   927  6019 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 09:18:07.750   927  6020 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-12 09:18:07.750   927  6019 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-12 09:18:07.752   927  6019 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 09:18:07.768   927  6020 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-12 09:18:07.769   927  6019 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-12 09:18:07.773   508   924 D CommandListener: Setting iface cfg
,10-12 09:18:07.778   927  2984 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 09:18:07.781   927  6019 D DhcpClient: Scheduling renewal in 86399s
,10-12 09:18:07.790   927  2984 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 09:18:07.792   927  2984 D WifiConfigStore: No blacklist allowed without epno enabled
10-12 09:18:07.793   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-12 09:18:07.795   927  2998 D ConnectivityService: Adding iface wlan0 to network 102
,10-12 09:18:07.806   927  2984 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-12 09:18:07.844   927  2998 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-12 09:18:07.844   927  2998 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-12 09:18:07.851   927  2998 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-12 09:18:07.856   927  2998 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-12 09:18:07.857   927  2998 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-12 09:18:07.864   927  2998 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:18:07.869   927  2998 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-12 09:18:07.870   927  2998 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-12 09:18:07.870   927  2998 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-12 09:18:07.870   927  2984 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-12 09:18:07.870   927  2998 D ConnectivityService:    accepting network in place of null
10-12 09:18:07.870   927  2984 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 09:18:07.871   927  2998 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 09:18:07.883   927  6018 D NetlinkSocketObserver: NeighborEvent{elapsedMs=307154, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-12 09:18:07.894   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:18:07.918   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 09:18:07.921   927  2998 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-12 09:18:07.921   927  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 09:18:07.921  3775  3938 W QCNEJ   : |CORE| network available: 102
,10-12 09:18:07.922   927  2998 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-12 09:18:07.923   927   944 D Tethering: MasterInitialState.processMessage what=3
10-12 09:18:07.923  3775  3938 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-12 09:18:07.924  3775  3938 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-12 09:18:07.924  3775  3938 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:07.932  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:18:07.934  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:18:07.934  5074  5098 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 09:18:07.934  5074  5098 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 09:18:07.934  5074  5098 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-12 09:18:07.935  5074  5098 E SarControlService: no key has been found,reset the power
10-12 09:18:07.935  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 09:18:07.936  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 09:18:07.936  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 09:18:07.936  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:18:07.937  5099  5099 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:07.938  5676  5676 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:18:07.939  5074  5111 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-12 09:18:07.939  5074  5111 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 09:18:07.940  5074  5111 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 09:18:07.940  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 09:18:07.940  5099  5099 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 09:18:07.940  5676  5676 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:07.943  3721  3721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 09:18:07.944  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000f003000000000000ffffffff]
10-12 09:18:07.944  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:18:07.944  5099  5113 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-12 09:18:07.944  5099  5113 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b1eec08 HexData = [00000000f103000000000000ffffffff]
10-12 09:18:07.944  5099  5113 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 09:18:07.944  5099  5113 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-12 09:18:07.945  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:18:07.945  5074  5084 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-12 09:18:07.947  5099  5099 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 09:18:07.947  5074  5085 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 09:18:07.948  3721  3721 D SystemUpdateService: onCreate
10-12 09:18:07.950   927  6017 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,10-12 09:18:07.952  3721  3721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 09:18:07.961  3721  3721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 09:18:07.966  3721  5433 I iu.UploadsManager: num queued entries: 0
,10-12 09:18:07.967  3721  5433 I iu.UploadsManager: num updated entries: 0
10-12 09:18:07.967  3721  5433 I iu.SyncManager: NEXT; no task
,10-12 09:18:07.970  3721  3721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 09:18:07.971  3721  3721 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 09:18:07.973  5809  5809 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:07.974  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:18:07.976  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:18:07.976  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:07.976  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe63b removed from the list
10-12 09:18:07.976  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:18:07.977  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:07.977  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:07.977  5809  5809 D SprintDMHelper: simOperator: 
10-12 09:18:07.977  5809  5809 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-12 09:18:07.980  5676  5722 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-12 09:18:07.980  5676  5722 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-12 09:18:07.982  5676  5722 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@96c6f15 Bundle[{}]
10-12 09:18:07.982  5676  5722 I io.jxcore.node.LifeCycleMonitor: start: OK
10-12 09:18:07.983  5676  5722 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-12 09:18:07.983  5676  5722 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-12 09:18:07.984  5676  5722 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-12 09:18:07.984  3721  6030 I SystemUpdateService: active receiver: enabled
10-12 09:18:07.984  5676  5722 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-12 09:18:07.985  5676  5722 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-12 09:18:07.991  5676  5722 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
10-12 09:18:07.991  5676  5722 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-12 09:18:07.991  5676  5722 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-12 09:18:07.993  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:07.993  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8d3158 added. We now have 3 listener(s)
,10-12 09:18:07.995  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 09:18:07.995  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:07.995  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:18:07.995  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 09:18:07.995  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23702b1 added. We now have 4 listener(s)
,10-12 09:18:07.996  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:07.996  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:18:07.997   927  6017 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 13:18:07 GMT], X-Android-Received-Millis=[1476278287996], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476278287974]}
10-12 09:18:07.997   927  2998 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 09:18:07.997   927  2998 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-12 09:18:07.998   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-12 09:18:07.999   927  2998 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 09:18:07.999  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:18:08.004  3721  6030 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:08.004  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:18:08.006  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.006  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:18:08.006  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.006  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0cab17 added. We now have 4 listener(s)
10-12 09:18:08.007  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.008  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.008  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:18:08.008  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.008  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e500b04 added. We now have 5 listener(s)
10-12 09:18:08.008  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.008  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:18:08.008  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:18:08.008  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:18:08.008  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.008  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.008  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:18:08.008  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:18:08.008  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.008  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.008  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8d3158 removed from the list
10-12 09:18:08.008  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.008  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23702b1 removed from the list
10-12 09:18:08.010  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:18:08.010  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 09:18:08.010  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:18:08.011  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 09:18:08.011  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.011  3721  6030 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-12 09:18:08.011  3721  6030 I SystemUpdateService: now status is 0 (complete)
10-12 09:18:08.011  3721  6030 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 09:18:08.011  3721  6030 I SystemUpdateService: file has been verified
10-12 09:18:08.011  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.011  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.011  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.012  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23702b1 not in the list
10-12 09:18:08.012  3721  6030 I SystemUpdateService: OTA package size = 21989297
10-12 09:18:08.012  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.012  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:18:08.012  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.013  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.013  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.013  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e500b04 removed from the list
10-12 09:18:08.013  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.013  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.013  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.013  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.013  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.013  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0cab17 removed from the list
10-12 09:18:08.013  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.014  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48818ed added. We now have 3 listener(s)
10-12 09:18:08.015  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.015  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.015  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:18:08.015  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.015  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d90322 added. We now have 4 listener(s)
10-12 09:18:08.015  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.015  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:18:08.017  3721  6030 I SystemUpdateService: showing system update notification
10-12 09:18:08.017  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:08.020  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active networ,k type is Wi-Fi: true
10-12 09:18:08.022  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.022  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:18:08.022  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.022  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@944d370 added. We now have 4 listener(s)
,10-12 09:18:08.024  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.024  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.024  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:18:08.024  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.024  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a56e9 added. We now have 5 listener(s)
10-12 09:18:08.024  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.024  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:18:08.024  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 09:18:08.024  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 09:18:08.024  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:18:08.024  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:18:08.026  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:18:08.027  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:18:08.030  5676  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 09:18:08.030  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 09:18:08.034  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 09:18:08.035  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 09:18:08.035  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:18:08.039  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 09:18:08.039  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 09:18:08.039  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 09:18:08.039  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 09:18:08.039  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 09:18:08.039  5676  5722 D BluetoothAdapter: STATE_ON
10-12 09:18:08.041  5960  5997 D BtGatt.GattService: registerClient() - UUID=7a5d5dbb-160f-4bf8-9449-faca956b01e1
10-12 09:18:08.042  5960  5976 D BtGatt.GattService: onClientRegistered() - UUID=7a5d5dbb-160f-4bf8-9449-faca956b01e1, clientIf=5
,10-12 09:18:08.043  5676  5777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 09:18:08.043  5960  5971 D BtGatt.GattService: start scan with filters
,10-12 09:18:08.046  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 09:18:08.046  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:18:08.046  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:18:08.046  5960  5979 D BtGatt.ScanManager: handling starting scan
10-12 09:18:08.046  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 09:18:08.046  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:18:08.046  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,10-12 09:18:08.047  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 09:18:08.048  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:18:08.048  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 09:18:08.048  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:18:08.048  5960  5979 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5dfc21e
10-12 09:18:08.050  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:18:08.052  5676  5722 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-12 09:18:08.052  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 09:18:08.052  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 09:18:08.052  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.052  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:18:08.052  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.052  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 09:18:08.052  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-12 09:18:08.053  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:18:08.053  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:18:08.053  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:18:08.053  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-12 09:18:08.055  5960  5976 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 09:18:08.055  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.056  5960  5979 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 09:18:08.058  5676  5722 D BluetoothAdapter: STATE_ON
,10-12 09:18:08.059  5960  6000 D BtGatt.GattService: stopScan() - queue size =1
10-12 09:18:08.060  5960  5997 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:18:08.060  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:18:08.060  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 09:18:08.060  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 09:18:08.060  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:18:08.060  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:18:08.060  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:18:08.060  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 09:18:08.060  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 09:18:08.061  5960  5976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 09:18:08.061  3721  3721 D SystemUpdateService: onDestroy
10-12 09:18:08.061  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.061  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:18:08.061  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:18:08.061  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 09:18:08.061  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:18:08.061  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:18:08.061  5960  5979 D BtGatt.ScanManager: Starting BLE batch scan
10-12 09:18:08.061  5960  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 09:18:08.061  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 09:18:08.063  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:18:08.063  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:18:08.063  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:18:08.067  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:18:08.067  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:18:08.067  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:18:08.067  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.067  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.068  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:18:08.068  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.068  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.068  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48818ed removed from the list
10-12 09:18:08.068  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.068  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d90322 removed from the list
10-12 09:18:08.068  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:18:08.068  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:18:08.069  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.069  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:18:08.070  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.070  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.070  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.070  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d90322 not in the list
,10-12 09:18:08.071  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.071  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:18:08.071  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 09:18:08.071  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.071  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.072  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a56e9 removed from the list
10-12 09:18:08.072  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.072  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.072  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.072  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:18:08.072  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.072  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@944d370 removed from the list
10-12 09:18:08.072  5960  5976 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 09:18:08.072  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.072  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.072  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f878a5 added. We now have 3 listener(s)
10-12 09:18:08.074  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.074  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.074  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:18:08.074  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.074  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2bd47a added. We now have 4 listener(s)
10-12 09:18:08.074  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.074  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:18:08.076  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:18:08.077  5960  5976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 09:18:08.077  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:08.080  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:18:08.082  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 09:18:08.082  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:18:08.082  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.082  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adba088 added. We now have 4 listener(s)
10-12 09:18:08.083  5960  5976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 09:18:08.083  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.083  5960  5979 D BtGatt.ScanManager: stopping BLe Batch
10-12 09:18:08.084  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.084  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.084  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:18:08.084  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.084  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cfa21 added. We now have 5 listener(s)
10-12 09:18:08.084  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.084  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:18:08.084  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:18:08.085  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:18:08.085  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 09:18:08.085  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-12 09:18:08.085  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:18:08.085  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:18:08.087  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:18:08.089  5960  5976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 09:18:08.089  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.089  5676  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 09:18:08.089  5960  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 09:18:08.089  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 09:18:08.093  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 09:18:08.093  5960  5976 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 09:18:08.093  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.094  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 09:18:08.094  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:18:08.096  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 09:18:08.096  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-12 09:18:08.096  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 09:18:08.096  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 09:18:08.096  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 09:18:08.097  5676  5722 D BluetoothAdapter: STATE_ON
10-12 09:18:08.098  5960  5997 D BtGatt.GattService: registerClient() - UUID=af3504d2-e7ea-418f-8cb0-9a6d66f5a533
10-12 09:18:08.098  5960  5976 D BtGatt.GattService: onClientRegistered() - UUID=af3504d2-e7ea-418f-8cb0-9a6d66f5a533, clientIf=5
,10-12 09:18:08.099  5676  5777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 09:18:08.099  5960  5971 D BtGatt.GattService: start scan with filters
10-12 09:18:08.101  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-12 09:18:08.101  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:18:08.101  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:18:08.101  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 09:18:08.101  5960  5979 D BtGatt.ScanManager: handling starting scan
10-12 09:18:08.101  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:18:08.101  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 09:18:08.101  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 09:18:08.103  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:18:08.103  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 09:18:08.103  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:18:08.104  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:18:08.106  5960  5976 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 09:18:08.106  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:18:08.106  5676  5722 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 09:18:08.106  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.106  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:18:08.106  5960  5979 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 09:18:08.106  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:18:08.106  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:18:08.106  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.106  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.106  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:18:08.106  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.106  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.106  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7f878a5 removed from the list
10-12 09:18:08.106  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.106  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2bd47a removed from the list
10-12 09:18:08.106  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:18:08.106  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:18:08.107  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.107  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-12 09:18:08.107  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.107  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:18:08.108  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.108  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.108  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.108  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2bd47a not in the list
,10-12 09:18:08.108  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 09:18:08.108  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:18:08.108  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:18:08.108  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:18:08.108  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 09:18:08.109  5676  5722 D BluetoothAdapter: STATE_ON
10-12 09:18:08.110  5960  5997 D BtGatt.GattService: stopScan() - queue size =1
10-12 09:18:08.110  5960  5976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 09:18:08.110  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.111  5960  5996 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 09:18:08.111  5960  5979 D BtGatt.ScanManager: Starting BLE batch scan
10-12 09:18:08.111  5960  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 09:18:08.111  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:18:08.111  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 09:18:08.111  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 09:18:08.111  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:18:08.111  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-12 09:18:08.111  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:18:08.111  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 09:18:08.111  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 09:18:08.112  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 09:18:08.112  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:18:08.112  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 09:18:08.112  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:18:08.112  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:18:08.113  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.114  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.114  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.114  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.114  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:18:08.114  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b9cfa21 removed from the list
10-12 09:18:08.114  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.114  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 09:18:08.114  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.114  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.114  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:18:08.114  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.114  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.114  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adba088 removed from the list
10-12 09:18:08.115  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.115  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ae175d added. We now have 3 listener(s)
10-12 09:18:08.116  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.116  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.116  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 09:18:08.116  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.116  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22c78d2 added. We now have 4 listener(s)
10-12 09:18:08.116  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.117  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 09:18:08.119  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:18:08.119  5960  5976 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 09:18:08.119  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:08.125  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:18:08.125  5960  5976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 09:18:08.125  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.127  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.127  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:18:08.127  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 09:18:08.127  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1abf8a0 added. We now have 4 listener(s)
10-12 09:18:08.129  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.129  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.129  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:18:08.129  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:18:08.129  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.129  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b9cc59 added. We now have 5 listener(s)
10-12 09:18:08.130  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.130  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:18:08.130  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-12 09:18:08.130  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 09:18:08.130  5960  5976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 09:18:08.130  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 09:18:08.130  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.130  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 09:18:08.130  5960  5979 D BtGatt.ScanManager: stopping BLe Batch
,10-12 09:18:08.132  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 09:18:08.133  5676  5722 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 09:18:08.133  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 09:18:08.136  5960  5976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 09:18:08.136  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.136  5960  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 09:18:08.136  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 09:18:08.137  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 09:18:08.137  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 09:18:08.140  5960  5976 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 09:18:08.140  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.140  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 09:18:08.140  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 09:18:08.140  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 09:18:08.140  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-12 09:18:08.140  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-12 09:18:08.141  5676  5722 D BluetoothAdapter: STATE_ON
,10-12 09:18:08.143  5960  5997 D BtGatt.GattService: registerClient() - UUID=20a3efe6-0a6f-45d3-844f-7e2a0abbb871
10-12 09:18:08.143  5960  5976 D BtGatt.GattService: onClientRegistered() - UUID=20a3efe6-0a6f-45d3-844f-7e2a0abbb871, clientIf=5
,10-12 09:18:08.143  5676  5777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-12 09:18:08.143  5960  5996 D BtGatt.GattService: start scan with filters
10-12 09:18:08.145  5960  5979 D BtGatt.ScanManager: handling starting scan
10-12 09:18:08.145  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 09:18:08.145  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 09:18:08.145  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:18:08.145  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 09:18:08.145  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 09:18:08.145  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 09:18:08.146  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 09:18:08.147  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 09:18:08.147  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 09:18:08.147  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 09:18:08.148  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 09:18:08.150  5960  5976 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 09:18:08.150  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.150  5960  5979 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 09:18:08.154  5960  5976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 09:18:08.154  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.154  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 09:18:08.154  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 09:18:08.154  5960  5979 D BtGatt.ScanManager: Starting BLE batch scan
10-12 09:18:08.154  5960  5979 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 09:18:08.154  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:18:08.154  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.154  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.154  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 09:18:08.154  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.154  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.154  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ae175d removed from the list
10-12 09:18:08.154  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.155  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22c78d2 removed from the list
10-12 09:18:08.155  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:18:08.155  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:18:08.155  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.155  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-12 09:18:08.155  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.155  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:18:08.157  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.157  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.157  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.157  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22c78d2 not in the list
10-12 09:18:08.157  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-12 09:18:08.157  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 09:18:08.157  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 09:18:08.157  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 09:18:08.157  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 09:18:08.158  5676  5722 D BluetoothAdapter: STATE_ON
10-12 09:18:08.158  5960  6000 D BtGatt.GattService: stopScan() - queue size =1
10-12 09:18:08.158  5960  5971 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 09:18:08.159  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 09:18:08.159  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 09:18:08.159  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 09:18:08.159  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 09:18:08.159  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 09:18:08.159  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 09:18:08.159  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-12 09:18:08.159  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 09:18:08.160  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:18:08.160  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 09:18:08.160  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 09:18:08.160  5676  5722 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 09:18:08.160  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 09:18:08.161  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.162  5960  5976 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 09:18:08.162  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.166  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 09:18:08.166  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.166  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.166  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:18:08.166  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b9cc59 removed from the list
10-12 09:18:08.166  5676  5676 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 09:18:08.166  5676  5676 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 09:18:08.166  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.166  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.166  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.166  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.166  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.167  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1abf8a0 removed from the list
,10-12 09:18:08.167  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.167  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e31d515 added. We now have 3 listener(s)
,10-12 09:18:08.168  5960  5976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 09:18:08.168  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 09:18:08.169  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.169  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.169  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:18:08.169  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.169  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d62502a added. We now have 4 listener(s)
,10-12 09:18:08.169  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.170  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 09:18:08.172  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 09:18:08.174  5960  5976 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-12 09:18:08.174  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.174  5960  5979 D BtGatt.ScanManager: stopping BLe Batch
,10-12 09:18:08.179  5960  5976 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-12 09:18:08.179  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.179  5960  5979 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 09:18:08.179  5676  5722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 09:18:08.181  5049  6035 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-12 09:18:08.182  5676  5722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 09:18:08.182  5676  5722 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 09:18:08.182  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 09:18:08.182  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc3bb8 added. We now have 4 listener(s)
10-12 09:18:08.183  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 09:18:08.183  5960  5976 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 09:18:08.183  5960  5976 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 09:18:08.183  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 09:18:08.183  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 09:18:08.184  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 09:18:08.184  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7ad91 added. We now have 5 listener(s)
,10-12 09:18:08.184  5676  5722 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 09:18:08.184  5676  5722 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 09:18:08.184  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:18:08.184  5676  5722 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 09:18:08.184  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.184  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:18:08.184  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.184  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 09:18:08.184  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 09:18:08.184  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.184  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e31d515 removed from the list
10-12 09:18:08.184  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.184  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d62502a removed from the list
10-12 09:18:08.186  5676  5676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 09:18:08.186  5676  5722 D io.jxcore.node.ConnectivityMonitor: stop
10-12 09:18:08.186  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 09:18:08.187  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.187  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.188  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-12 09:18:08.188  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.188  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 09:18:08.188  5676  5722 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d62502a not in the list
10-12 09:18:08.188  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.188  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.188  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 09:18:08.189  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 09:18:08.189  5676  5722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 09:18:08.189  5676  5722 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e7ad91 removed from the list
10-12 09:18:08.189  5676  5722 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 09:18:08.189  5676  5722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 09:18:08.189  5676  5722 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 09:18:08.189  5676  5722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 09:18:08.189  5676  5722 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 09:18:08.189  5676  5722 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc3bb8 removed from the list
10-12 09:18:08.190  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-12 09:18:08.190  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,10-12 09:18:08.190  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 09:18:08.190  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:18:08.190  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-12 09:18:08.190  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-12 09:18:08.564  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:18:08.614  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:18:08.667  5676  5676 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 09:18:10.337  5676  6042 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 09:18:10.337  5676  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:18:10.647   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:18:11.133  5676  6042 W !!      : call onHalfStreamCopied
,10-12 09:18:11.133  5676  6042 I testCopyDataAndClose: closing input stream
,10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 09:18:11.908  5676  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 09:18:15.688  5676  6043 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:15.688  5676  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:18:15.875   927  2998 D ConnectivityService: handlePromptUnvalidated 102
,10-12 09:18:17.688  5676  5722 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-12 09:18:17.688  5676  5722 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:18:17.688  5676  5722 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-12 09:18:17.799  5676  6044 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 09:18:17.799  5676  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:18:17.827  5676  6043 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-12 09:18:17.827  5676  6043 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:17.827  5676  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,10-12 09:18:18.844   927  2984 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 09:18:19.486  5676  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 09:18:19.706   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 09:18:23.231  5676  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 09:18:23.232  5676  6045 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-12 09:18:23.232  5676  6045 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 09:18:23.232  5676  6045 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 09:18:23.232  5676  6045 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:23.232  5676  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-12 09:18:23.234  5676  5722 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-12 09:18:23.237  5676  6046 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:23.237  5676  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 09:18:23.237  5676  6046 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,10-12 09:18:23.238  5676  6046 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:23.238  5676  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-12 09:18:23.238  5676  6046 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-12 09:18:23.238  5676  6046 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 09:18:23.238  5676  6046 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-12 09:18:23.243  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-12 09:18:23.243  5676  5722 I jxcore-log: 
10-12 09:18:23.243  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-12 09:18:23.243  5676  5722 I jxcore-log: 
10-12 09:18:23.244  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-12 09:18:23.244  5676  5722 I jxcore-log: 
10-12 09:18:23.244  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-12 09:18:23.244  5676  5722 I jxcore-log: 
10-12 09:18:23.244  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'Total duration:  90814'
10-12 09:18:23.244  5676  5722 I jxcore-log: 
10-12 09:18:23.247  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-12 09:18:23.247  5676  5722 I jxcore-log: 
,10-12 09:18:23.250  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.250  5676  5722 I jxcore-log: 
,10-12 09:18:23.251  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.251  5676  5722 I jxcore-log: 
10-12 09:18:23.252  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.252  5676  5722 I jxcore-log: 
10-12 09:18:23.252  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.252  5676  5722 I jxcore-log: 
10-12 09:18:23.252  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-12 09:18:23.252  5676  5722 I jxcore-log: 
,10-12 09:18:23.253  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:18:23.253  5676  5722 I jxcore-log: 
10-12 09:18:23.253  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.253  5676  5722 I jxcore-log: 
10-12 09:18:23.253  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.253  5676  5722 I jxcore-log: 
10-12 09:18:23.253  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-12 09:18:23.253  5676  5722 I jxcore-log: 
,10-12 09:18:23.254  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:18:23.254  5676  5722 I jxcore-log: 
10-12 09:18:23.254  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:18:23.254  5676  5722 I jxcore-log: 
,10-12 09:18:23.254  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.254  5676  5722 I jxcore-log: 
10-12 09:18:23.254  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.254  5676  5722 I jxcore-log: 
10-12 09:18:23.255  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.255  5676  5722 I jxcore-log: 
10-12 09:18:23.255  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.255  5676  5722 I jxcore-log: 
,10-12 09:18:23.255  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.255  5676  5722 I jxcore-log: 
10-12 09:18:23.256  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.256  5676  5722 I jxcore-log: 
,10-12 09:18:23.256  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.256  5676  5722 I jxcore-log: 
10-12 09:18:23.256  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.256  5676  5722 I jxcore-log: 
10-12 09:18:23.256  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.256  5676  5722 I jxcore-log: 
10-12 09:18:23.257  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.257  5676  5722 I jxcore-log: 
10-12 09:18:23.257  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.257  5676  5722 I jxcore-log: 
,10-12 09:18:23.257  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.257  5676  5722 I jxcore-log: 
10-12 09:18:23.258  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.258  5676  5722 I jxcore-log: 
10-12 09:18:23.259  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.259  5676  5722 I jxcore-log: 
10-12 09:18:23.259  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.259  5676  5722 I jxcore-log: 
10-12 09:18:23.259  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.259  5676  5722 I jxcore-log: 
10-12 09:18:23.259  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.259  5676  5722 I jxcore-log: 
,10-12 09:18:23.260  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.260  5676  5722 I jxcore-log: 
10-12 09:18:23.260  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.260  5676  5722 I jxcore-log: 
10-12 09:18:23.260  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.260  5676  5722 I jxcore-log: 
10-12 09:18:23.260  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.260  5676  5722 I jxcore-log: 
10-12 09:18:23.261  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.261  5676  5722 I jxcore-log: 
,10-12 09:18:23.261  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.261  5676  5722 I jxcore-log: 
10-12 09:18:23.261  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.261  5676  5722 I jxcore-log: 
10-12 09:18:23.261  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.261  5676  5722 I jxcore-log: 
,10-12 09:18:23.261  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.261  5676  5722 I jxcore-log: 
10-12 09:18:23.262  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.262  5676  5722 I jxcore-log: 
10-12 09:18:23.262  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.262  5676  5722 I jxcore-log: 
10-12 09:18:23.262  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.262  5676  5722 I jxcore-log: 
,10-12 09:18:23.262  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 09:18:23.262  5676  5722 I jxcore-log: 
10-12 09:18:23.262  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.262  5676  5722 I jxcore-log: 
10-12 09:18:23.263  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 09:18:23.263  5676  5722 I jxcore-log: 
10-12 09:18:23.263  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.263  5676  5722 I jxcore-log: 
10-12 09:18:23.263  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.263  5676  5722 I jxcore-log: 
10-12 09:18:23.263  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.263  5676  5722 I jxcore-log: 
10-12 09:18:23.264  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.264  5676  5722 I jxcore-log: 
,10-12 09:18:23.264  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.264  5676  5722 I jxcore-log: 
10-12 09:18:23.264  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 09:18:23.264  5676  5722 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-12 09:18:23.264  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.264  5676  5722 I jxcore-log: 
10-12 09:18:23.264  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.264  5676  5722 I jxcore-log: 
10-12 09:18:23.265  5676  5722 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 09:18:23.265  5676  5722 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,10-12 09:18:23.265  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 09:18:23.265  5676  5722 I jxcore-log: 
10-12 09:18:23.265  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:18:23.265  5676  5722 I jxcore-log: 
10-12 09:18:23.265  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:18:23.265  5676  5722 I jxcore-log: 
10-12 09:18:23.265  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 09:18:23.265  5676  5722 I jxcore-log: 
10-12 09:18:23.271  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-12 09:18:23.271  5676  5722 I jxcore-log: 
10-12 09:18:23.271  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - WARN testUtils: 'myNameCallback not set!'
10-12 09:18:23.271  5676  5722 I jxcore-log: 
10-12 09:18:23.272  5676  5722 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-12 09:18:23.273  5676  5722 I jxcore-log: 2016-10-12 13:18:23 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-12 09:18:23.273  5676  5722 I jxcore-log: 
,10-12 09:18:23.274  5676  5676 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-12 09:18:25.308  5676  5722 I jxcore-log: 2016-10-12 13:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-12 09:18:25.308  5676  5722 I jxcore-log: 
,10-12 09:18:25.648  5676  5722 I jxcore-log: 2016-10-12 13:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-12 09:18:25.648  5676  5722 I jxcore-log: 
,10-12 09:18:25.666  5676  5722 I jxcore-log: 2016-10-12 13:18:25 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-12 09:18:25.666  5676  5722 I jxcore-log: 
,10-12 09:18:25.762   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:18:26.761  5676  5722 I jxcore-log: 2016-10-12 13:18:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-12 09:18:26.761  5676  5722 I jxcore-log: 
,10-12 09:18:26.926  5676  5722 I jxcore-log: 2016-10-12 13:18:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-12 09:18:26.926  5676  5722 I jxcore-log: 
,10-12 09:18:26.931  5676  5722 I jxcore-log: 2016-10-12 13:18:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-12 09:18:26.931  5676  5722 I jxcore-log: 
,10-12 09:18:26.936  5676  5722 I jxcore-log: 2016-10-12 13:18:26 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-12 09:18:26.936  5676  5722 I jxcore-log: 
,10-12 09:18:27.419  5676  5722 I jxcore-log: 2016-10-12 13:18:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-12 09:18:27.419  5676  5722 I jxcore-log: 
,10-12 09:18:27.463  5676  5722 I jxcore-log: 2016-10-12 13:18:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-12 09:18:27.463  5676  5722 I jxcore-log: 
,10-12 09:18:27.476  5676  5722 I jxcore-log: 2016-10-12 13:18:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-12 09:18:27.476  5676  5722 I jxcore-log: 
,10-12 09:18:27.480  5676  5722 I jxcore-log: 2016-10-12 13:18:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-12 09:18:27.480  5676  5722 I jxcore-log: 
,10-12 09:18:27.779  5676  5722 I jxcore-log: 2016-10-12 13:18:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-12 09:18:27.779  5676  5722 I jxcore-log: 
,10-12 09:18:27.904  5676  5722 I jxcore-log: 2016-10-12 13:18:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-12 09:18:27.904  5676  5722 I jxcore-log: 
,10-12 09:18:28.142  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-12 09:18:28.142  5676  5722 I jxcore-log: 
,10-12 09:18:28.291  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-12 09:18:28.291  5676  5722 I jxcore-log: 
,10-12 09:18:28.296  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-12 09:18:28.296  5676  5722 I jxcore-log: 
,10-12 09:18:28.301  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-12 09:18:28.301  5676  5722 I jxcore-log: 
,10-12 09:18:28.306  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-12 09:18:28.306  5676  5722 I jxcore-log: 
,10-12 09:18:28.333  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-12 09:18:28.333  5676  5722 I jxcore-log: 
,10-12 09:18:28.369  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-12 09:18:28.369  5676  5722 I jxcore-log: 
,10-12 09:18:28.377  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-12 09:18:28.377  5676  5722 I jxcore-log: 
,10-12 09:18:28.383  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-12 09:18:28.383  5676  5722 I jxcore-log: 
,10-12 09:18:28.398  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-12 09:18:28.398  5676  5722 I jxcore-log: 
,10-12 09:18:28.403  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-12 09:18:28.403  5676  5722 I jxcore-log: 
,10-12 09:18:28.409  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-12 09:18:28.409  5676  5722 I jxcore-log: 
,10-12 09:18:28.414  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-12 09:18:28.414  5676  5722 I jxcore-log: 
,10-12 09:18:28.428  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-12 09:18:28.428  5676  5722 I jxcore-log: 
,10-12 09:18:28.450  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-12 09:18:28.450  5676  5722 I jxcore-log: 
,10-12 09:18:28.460  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-12 09:18:28.460  5676  5722 I jxcore-log: 
,10-12 09:18:28.473  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-12 09:18:28.473  5676  5722 I jxcore-log: 
,10-12 09:18:28.483  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-12 09:18:28.483  5676  5722 I jxcore-log: 
,10-12 09:18:28.496  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-12 09:18:28.496  5676  5722 I jxcore-log: 
,10-12 09:18:28.506  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-12 09:18:28.506  5676  5722 I jxcore-log: 
,10-12 09:18:28.511  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-12 09:18:28.511  5676  5722 I jxcore-log: 
,10-12 09:18:28.532  5676  5722 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-12 09:18:28.533  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - INFO testUtils: 'BLE multiple advertisement supported'
10-12 09:18:28.533  5676  5722 I jxcore-log: 
,10-12 09:18:28.850  5676  5722 I jxcore-log: 2016-10-12 13:18:28 - DEBUG CoordinatedClient: 'connected to the test server'
10-12 09:18:28.850  5676  5722 I jxcore-log: 
,10-12 09:18:29.507  5676  5722 I jxcore-log: TAP version 13
10-12 09:18:29.507  5676  5722 I jxcore-log: 
,10-12 09:18:29.548  5676  5722 I jxcore-log: # setup
10-12 09:18:29.548  5676  5722 I jxcore-log: 
,10-12 09:18:30.132   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-12 09:18:30.133   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-12 09:18:30.547  5676  5722 I jxcore-log: # calling createNativeListener directly rejects
10-12 09:18:30.547  5676  5722 I jxcore-log: 
,10-12 09:18:30.972  5676  5722 I jxcore-log: 2016-10-12 13:18:30 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:30.972  5676  5722 I jxcore-log: 
,10-12 09:18:30.978  5676  5722 I jxcore-log: 2016-10-12 13:18:30 - DEBUG createNativeListener: 'listening 41297'
10-12 09:18:30.978  5676  5722 I jxcore-log: 
,10-12 09:18:30.988  5676  5722 I jxcore-log: ok 1 Should throw
10-12 09:18:30.988  5676  5722 I jxcore-log: 
,10-12 09:18:30.997  5676  5722 I jxcore-log: # teardown
10-12 09:18:30.997  5676  5722 I jxcore-log: 
,10-12 09:18:31.298  5676  5722 I jxcore-log: # setup
10-12 09:18:31.298  5676  5722 I jxcore-log: 
,10-12 09:18:32.198  5676  5722 I jxcore-log: # emits incomingConnectionState
10-12 09:18:32.198  5676  5722 I jxcore-log: 
,10-12 09:18:32.388  5676  5722 I jxcore-log: 2016-10-12 13:18:32 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:32.388  5676  5722 I jxcore-log: 
,10-12 09:18:32.394  5676  5722 I jxcore-log: 2016-10-12 13:18:32 - DEBUG createNativeListener: 'listening 38833'
10-12 09:18:32.394  5676  5722 I jxcore-log: 
,10-12 09:18:32.403  5676  5722 I jxcore-log: 2016-10-12 13:18:32 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:32.403  5676  5722 I jxcore-log: 
,10-12 09:18:32.407  5676  5722 I jxcore-log: 2016-10-12 13:18:32 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:32.407  5676  5722 I jxcore-log: 
,10-12 09:18:32.417  5676  5722 I jxcore-log: 2016-10-12 13:18:32 - DEBUG createNativeListener: 'new mux'
10-12 09:18:32.417  5676  5722 I jxcore-log: 
,10-12 09:18:32.423  5676  5722 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-12 09:18:32.423  5676  5722 I jxcore-log: 
,10-12 09:18:32.445  5676  5722 I jxcore-log: 2016-10-12 13:18:32 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:32.445  5676  5722 I jxcore-log: 
,10-12 09:18:32.446  5676  5722 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-12 09:18:32.446  5676  5722 I jxcore-log: 
,10-12 09:18:32.453  5676  5722 I jxcore-log: # teardown
10-12 09:18:32.453  5676  5722 I jxcore-log: 
,10-12 09:18:33.430  5676  5722 I jxcore-log: # setup
10-12 09:18:33.430  5676  5722 I jxcore-log: 
,10-12 09:18:33.608  5676  5722 I jxcore-log: # emits routerPortConnectionFailed
10-12 09:18:33.608  5676  5722 I jxcore-log: 
,10-12 09:18:34.664  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:34.664  5676  5722 I jxcore-log: 
,10-12 09:18:34.667  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'listening 44891'
10-12 09:18:34.667  5676  5722 I jxcore-log: 
,10-12 09:18:34.674  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:34.674  5676  5722 I jxcore-log: 
,10-12 09:18:34.676  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:34.676  5676  5722 I jxcore-log: 
,10-12 09:18:34.678  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'new mux'
10-12 09:18:34.678  5676  5722 I jxcore-log: 
,10-12 09:18:34.701  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:34.701  5676  5722 I jxcore-log: 
,10-12 09:18:34.703  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:34.703  5676  5722 I jxcore-log: 
,10-12 09:18:34.708  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: ' $c@net.js:837:7
10-12 09:18:34.708  5676  5722 I jxcore-log: $09@net.js:829:13
10-12 09:18:34.708  5676  5722 I jxcore-log: '
10-12 09:18:34.708  5676  5722 I jxcore-log: 
,10-12 09:18:34.708  5676  5722 I jxcore-log: ok 4 tried to connect to right port
10-12 09:18:34.708  5676  5722 I jxcore-log: 
,10-12 09:18:34.710  5676  5722 I jxcore-log: ok 5 failed due to refused connection
10-12 09:18:34.710  5676  5722 I jxcore-log: 
10-12 09:18:34.711  5676  5722 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-12 09:18:34.711  5676  5722 I jxcore-log: 
,10-12 09:18:34.714  5676  5722 I jxcore-log: # teardown
10-12 09:18:34.714  5676  5722 I jxcore-log: 
,10-12 09:18:34.716  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:34.716  5676  5722 I jxcore-log: 
,10-12 09:18:34.915  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'mux close'
10-12 09:18:34.915  5676  5722 I jxcore-log: 
,10-12 09:18:34.921  5676  5722 I jxcore-log: 2016-10-12 13:18:34 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:34.921  5676  5722 I jxcore-log: 
,10-12 09:18:34.937  5676  5722 I jxcore-log: # setup
10-12 09:18:34.937  5676  5722 I jxcore-log: 
,10-12 09:18:35.784  5676  5722 I jxcore-log: # native server connections all up
10-12 09:18:35.784  5676  5722 I jxcore-log: 
,10-12 09:18:36.186  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:36.186  5676  5722 I jxcore-log: 
,10-12 09:18:36.193  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'listening 46320'
10-12 09:18:36.193  5676  5722 I jxcore-log: 
,10-12 09:18:36.203  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:36.203  5676  5722 I jxcore-log: 
,10-12 09:18:36.204  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:36.204  5676  5722 I jxcore-log: 
,10-12 09:18:36.206  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'new mux'
10-12 09:18:36.206  5676  5722 I jxcore-log: 
,10-12 09:18:36.238  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:36.238  5676  5722 I jxcore-log: 
,10-12 09:18:36.243  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:36.243  5676  5722 I jxcore-log: 
10-12 09:18:36.246  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:36.246  5676  5722 I jxcore-log: 
,10-12 09:18:36.250  5676  5722 I jxcore-log: 2016-10-12 13:18:36 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:36.250  5676  5722 I jxcore-log: 
,10-12 09:18:36.273  5676  5722 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-12 09:18:36.273  5676  5722 I jxcore-log: 
,10-12 09:18:36.274  5676  5722 I jxcore-log: ok 8 Send/recvd #1 should be same
10-12 09:18:36.274  5676  5722 I jxcore-log: 
10-12 09:18:36.276  5676  5722 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-12 09:18:36.276  5676  5722 I jxcore-log: 
10-12 09:18:36.277  5676  5722 I jxcore-log: ok 10 Send/recvd #2 should be same
10-12 09:18:36.277  5676  5722 I jxcore-log: 
,10-12 09:18:36.280  5676  5722 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-12 09:18:36.280  5676  5722 I jxcore-log: 
,10-12 09:18:36.287  5676  5722 I jxcore-log: # teardown
10-12 09:18:36.287  5676  5722 I jxcore-log: 
,10-12 09:18:37.008  5676  5722 I jxcore-log: 2016-10-12 13:18:37 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:37.008  5676  5722 I jxcore-log: 
,10-12 09:18:37.013  5676  5722 I jxcore-log: 2016-10-12 13:18:37 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:37.013  5676  5722 I jxcore-log: 
,10-12 09:18:37.016  5676  5722 I jxcore-log: 2016-10-12 13:18:37 - DEBUG createNativeListener: 'mux close'
10-12 09:18:37.016  5676  5722 I jxcore-log: 
,10-12 09:18:37.022  5676  5722 I jxcore-log: 2016-10-12 13:18:37 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:37.022  5676  5722 I jxcore-log: 
,10-12 09:18:37.037  5676  5722 I jxcore-log: # setup
10-12 09:18:37.037  5676  5722 I jxcore-log: 
,10-12 09:18:37.418  5676  5722 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-12 09:18:37.418  5676  5722 I jxcore-log: 
,10-12 09:18:38.128  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:38.128  5676  5722 I jxcore-log: 
,10-12 09:18:38.134  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'listening 43114'
10-12 09:18:38.134  5676  5722 I jxcore-log: 
,10-12 09:18:38.143  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:38.143  5676  5722 I jxcore-log: 
,10-12 09:18:38.145  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:38.145  5676  5722 I jxcore-log: 
,10-12 09:18:38.151  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new mux'
10-12 09:18:38.151  5676  5722 I jxcore-log: 
,10-12 09:18:38.163  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:38.163  5676  5722 I jxcore-log: 
,10-12 09:18:38.166  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:38.166  5676  5722 I jxcore-log: 
,10-12 09:18:38.178  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:38.178  5676  5722 I jxcore-log: 
,10-12 09:18:38.191  5676  5722 I jxcore-log: ok 12 socket shouldn't close until after stream
10-12 09:18:38.191  5676  5722 I jxcore-log: 
,10-12 09:18:38.192  5676  5722 I jxcore-log: ok 13 incoming remains open
10-12 09:18:38.192  5676  5722 I jxcore-log: 
,10-12 09:18:38.199  5676  5722 I jxcore-log: # teardown
10-12 09:18:38.199  5676  5722 I jxcore-log: 
,10-12 09:18:38.640  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'mux close'
10-12 09:18:38.640  5676  5722 I jxcore-log: 
,10-12 09:18:38.650  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:38.650  5676  5722 I jxcore-log: 
,10-12 09:18:38.661  5676  5722 I jxcore-log: # setup
10-12 09:18:38.661  5676  5722 I jxcore-log: 
,10-12 09:18:38.711  5676  5722 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-12 09:18:38.711  5676  5722 I jxcore-log: 
,10-12 09:18:38.752  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:38.752  5676  5722 I jxcore-log: 
,10-12 09:18:38.756  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'listening 47026'
10-12 09:18:38.756  5676  5722 I jxcore-log: 
,10-12 09:18:38.762  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:38.762  5676  5722 I jxcore-log: 
,10-12 09:18:38.764  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:38.764  5676  5722 I jxcore-log: 
10-12 09:18:38.766  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new mux'
10-12 09:18:38.766  5676  5722 I jxcore-log: 
,10-12 09:18:38.776  5676  5722 I jxcore-log: ok 14 we should not have gotten an error
10-12 09:18:38.776  5676  5722 I jxcore-log: 
,10-12 09:18:38.781  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:38.781  5676  5722 I jxcore-log: 
,10-12 09:18:38.786  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:38.786  5676  5722 I jxcore-log: 
,10-12 09:18:38.796  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:38.796  5676  5722 I jxcore-log: 
,10-12 09:18:38.798  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:38.798  5676  5722 I jxcore-log: 
,10-12 09:18:38.806  5676  5722 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-12 09:18:38.806  5676  5722 I jxcore-log: 
,10-12 09:18:38.807  5676  5722 I jxcore-log: ok 16 incoming is cleaned up
10-12 09:18:38.807  5676  5722 I jxcore-log: 
,10-12 09:18:38.816  5676  5722 I jxcore-log: # teardown
10-12 09:18:38.816  5676  5722 I jxcore-log: 
,10-12 09:18:38.863  5676  5722 I jxcore-log: # setup
10-12 09:18:38.863  5676  5722 I jxcore-log: 
,10-12 09:18:38.898  5676  5722 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-12 09:18:38.898  5676  5722 I jxcore-log: 
,10-12 09:18:38.995  5676  5722 I jxcore-log: 2016-10-12 13:18:38 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:38.995  5676  5722 I jxcore-log: 
,10-12 09:18:39.001  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'listening 41653'
10-12 09:18:39.001  5676  5722 I jxcore-log: 
,10-12 09:18:39.010  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.010  5676  5722 I jxcore-log: 
,10-12 09:18:39.012  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.012  5676  5722 I jxcore-log: 
,10-12 09:18:39.016  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.016  5676  5722 I jxcore-log: 
,10-12 09:18:39.028  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.028  5676  5722 I jxcore-log: 
,10-12 09:18:39.031  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.031  5676  5722 I jxcore-log: 
,10-12 09:18:39.047  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.047  5676  5722 I jxcore-log: 
,10-12 09:18:39.056  5676  5722 I jxcore-log: ok 17 stream was closed
10-12 09:18:39.056  5676  5722 I jxcore-log: 
,10-12 09:18:39.056  5676  5722 I jxcore-log: ok 18 incoming should survive
10-12 09:18:39.056  5676  5722 I jxcore-log: 
10-12 09:18:39.056  5676  5722 I jxcore-log: ok 19 mux should have no streams
10-12 09:18:39.056  5676  5722 I jxcore-log: 
,10-12 09:18:39.062  5676  5722 I jxcore-log: # teardown
10-12 09:18:39.062  5676  5722 I jxcore-log: 
,10-12 09:18:39.088  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.088  5676  5722 I jxcore-log: 
,10-12 09:18:39.100  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.100  5676  5722 I jxcore-log: 
,10-12 09:18:39.110  5676  5722 I jxcore-log: # setup
10-12 09:18:39.110  5676  5722 I jxcore-log: 
,10-12 09:18:39.179  5676  5722 I jxcore-log: # native server - closing the whole server cleans everything up
10-12 09:18:39.179  5676  5722 I jxcore-log: 
,10-12 09:18:39.223  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:39.223  5676  5722 I jxcore-log: 
,10-12 09:18:39.232  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'listening 45488'
10-12 09:18:39.232  5676  5722 I jxcore-log: 
,10-12 09:18:39.240  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.240  5676  5722 I jxcore-log: 
,10-12 09:18:39.242  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.242  5676  5722 I jxcore-log: 
,10-12 09:18:39.244  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.244  5676  5722 I jxcore-log: 
,10-12 09:18:39.254  5676  5722 I jxcore-log: ok 20 we should not have gotten an error
10-12 09:18:39.254  5676  5722 I jxcore-log: 
,10-12 09:18:39.260  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.260  5676  5722 I jxcore-log: 
,10-12 09:18:39.263  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.263  5676  5722 I jxcore-log: 
,10-12 09:18:39.271  5676  5722 I jxcore-log: ok 21 Buffers are identical
10-12 09:18:39.271  5676  5722 I jxcore-log: 
,10-12 09:18:39.273  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.273  5676  5722 I jxcore-log: 
10-12 09:18:39.275  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.275  5676  5722 I jxcore-log: 
,10-12 09:18:39.278  5676  5722 I jxcore-log: ok 22 native server is nulled out
10-12 09:18:39.278  5676  5722 I jxcore-log: 
,10-12 09:18:39.278  5676  5722 I jxcore-log: ok 23 native server should be closed
10-12 09:18:39.278  5676  5722 I jxcore-log: 
10-12 09:18:39.279  5676  5722 I jxcore-log: ok 24 incoming has been removed
10-12 09:18:39.279  5676  5722 I jxcore-log: 
10-12 09:18:39.279  5676  5722 I jxcore-log: ok 25 Incoming should be done
10-12 09:18:39.279  5676  5722 I jxcore-log: 
10-12 09:18:39.279  5676  5722 I jxcore-log: ok 26 The mux object should be closed
10-12 09:18:39.279  5676  5722 I jxcore-log: 
10-12 09:18:39.279  5676  5722 I jxcore-log: ok 27 The mux stream should be closed
10-12 09:18:39.279  5676  5722 I jxcore-log: 
10-12 09:18:39.280  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.280  5676  5722 I jxcore-log: 
,10-12 09:18:39.295  5676  5722 I jxcore-log: # teardown
10-12 09:18:39.295  5676  5722 I jxcore-log: 
,10-12 09:18:39.321  5676  5722 I jxcore-log: # setup
10-12 09:18:39.321  5676  5722 I jxcore-log: 
,10-12 09:18:39.350  5676  5722 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-12 09:18:39.350  5676  5722 I jxcore-log: 
,10-12 09:18:39.378  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:39.378  5676  5722 I jxcore-log: 
,10-12 09:18:39.381  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'listening 41529'
10-12 09:18:39.381  5676  5722 I jxcore-log: 
,10-12 09:18:39.407  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.407  5676  5722 I jxcore-log: 
,10-12 09:18:39.408  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.408  5676  5722 I jxcore-log: 
10-12 09:18:39.409  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.409  5676  5722 I jxcore-log: 
,10-12 09:18:39.412  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.412  5676  5722 I jxcore-log: 
,10-12 09:18:39.413  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.413  5676  5722 I jxcore-log: 
,10-12 09:18:39.414  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.414  5676  5722 I jxcore-log: 
10-12 09:18:39.417  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.417  5676  5722 I jxcore-log: 
10-12 09:18:39.417  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.417  5676  5722 I jxcore-log: 
10-12 09:18:39.419  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.419  5676  5722 I jxcore-log: 
,10-12 09:18:39.423  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.423  5676  5722 I jxcore-log: 
,10-12 09:18:39.424  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.424  5676  5722 I jxcore-log: 
,10-12 09:18:39.425  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.425  5676  5722 I jxcore-log: 
,10-12 09:18:39.428  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.428  5676  5722 I jxcore-log: 
,10-12 09:18:39.429  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.429  5676  5722 I jxcore-log: 
,10-12 09:18:39.432  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.432  5676  5722 I jxcore-log: 
,10-12 09:18:39.441  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.441  5676  5722 I jxcore-log: 
,10-12 09:18:39.441  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.441  5676  5722 I jxcore-log: 
,10-12 09:18:39.442  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.442  5676  5722 I jxcore-log: 
,10-12 09:18:39.443  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.443  5676  5722 I jxcore-log: 
,10-12 09:18:39.443  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.443  5676  5722 I jxcore-log: 
,10-12 09:18:39.444  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.444  5676  5722 I jxcore-log: 
,10-12 09:18:39.445  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.445  5676  5722 I jxcore-log: 
,10-12 09:18:39.445  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.445  5676  5722 I jxcore-log: 
10-12 09:18:39.446  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.446  5676  5722 I jxcore-log: 
,10-12 09:18:39.447  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.447  5676  5722 I jxcore-log: 
,10-12 09:18:39.447  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.447  5676  5722 I jxcore-log: 
,10-12 09:18:39.448  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.448  5676  5722 I jxcore-log: 
,10-12 09:18:39.449  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:39.449  5676  5722 I jxcore-log: 
,10-12 09:18:39.449  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:39.449  5676  5722 I jxcore-log: 
10-12 09:18:39.450  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new mux'
10-12 09:18:39.450  5676  5722 I jxcore-log: 
,10-12 09:18:39.503  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.503  5676  5722 I jxcore-log: 
,10-12 09:18:39.505  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.505  5676  5722 I jxcore-log: 
,10-12 09:18:39.507  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.507  5676  5722 I jxcore-log: 
,10-12 09:18:39.508  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.508  5676  5722 I jxcore-log: 
,10-12 09:18:39.509  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.509  5676  5722 I jxcore-log: 
,10-12 09:18:39.510  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.510  5676  5722 I jxcore-log: 
,10-12 09:18:39.511  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.511  5676  5722 I jxcore-log: 
,10-12 09:18:39.512  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.512  5676  5722 I jxcore-log: 
,10-12 09:18:39.513  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.513  5676  5722 I jxcore-log: 
,10-12 09:18:39.514  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.514  5676  5722 I jxcore-log: 
,10-12 09:18:39.515  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.515  5676  5722 I jxcore-log: 
,10-12 09:18:39.516  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.516  5676  5722 I jxcore-log: 
10-12 09:18:39.517  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.517  5676  5722 I jxcore-log: 
10-12 09:18:39.518  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.518  5676  5722 I jxcore-log: 
,10-12 09:18:39.518  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.518  5676  5722 I jxcore-log: 
,10-12 09:18:39.519  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.519  5676  5722 I jxcore-log: 
,10-12 09:18:39.520  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.520  5676  5722 I jxcore-log: 
,10-12 09:18:39.521  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.521  5676  5722 I jxcore-log: 
,10-12 09:18:39.522  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.522  5676  5722 I jxcore-log: 
,10-12 09:18:39.523  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.523  5676  5722 I jxcore-log: 
10-12 09:18:39.524  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.524  5676  5722 I jxcore-log: 
,10-12 09:18:39.524  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.524  5676  5722 I jxcore-log: 
,10-12 09:18:39.525  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.525  5676  5722 I jxcore-log: 
,10-12 09:18:39.526  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.526  5676  5722 I jxcore-log: 
,10-12 09:18:39.527  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.527  5676  5722 I jxcore-log: 
,10-12 09:18:39.528  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.528  5676  5722 I jxcore-log: 
,10-12 09:18:39.529  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.529  5676  5722 I jxcore-log: 
,10-12 09:18:39.529  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.529  5676  5722 I jxcore-log: 
10-12 09:18:39.530  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.530  5676  5722 I jxcore-log: 
,10-12 09:18:39.531  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.531  5676  5722 I jxcore-log: 
,10-12 09:18:39.531  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.531  5676  5722 I jxcore-log: 
,10-12 09:18:39.532  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.532  5676  5722 I jxcore-log: 
,10-12 09:18:39.533  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.533  5676  5722 I jxcore-log: 
,10-12 09:18:39.534  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.534  5676  5722 I jxcore-log: 
,10-12 09:18:39.535  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.535  5676  5722 I jxcore-log: 
,10-12 09:18:39.536  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.536  5676  5722 I jxcore-log: 
10-12 09:18:39.536  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.536  5676  5722 I jxcore-log: 
,10-12 09:18:39.537  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.537  5676  5722 I jxcore-log: 
,10-12 09:18:39.538  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.538  5676  5722 I jxcore-log: 
,10-12 09:18:39.538  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.538  5676  5722 I jxcore-log: 
,10-12 09:18:39.539  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.539  5676  5722 I jxcore-log: 
,10-12 09:18:39.540  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.540  5676  5722 I jxcore-log: 
10-12 09:18:39.541  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.541  5676  5722 I jxcore-log: 
,10-12 09:18:39.542  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.542  5676  5722 I jxcore-log: 
10-12 09:18:39.542  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.542  5676  5722 I jxcore-log: 
,10-12 09:18:39.543  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.543  5676  5722 I jxcore-log: 
,10-12 09:18:39.544  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.544  5676  5722 I jxcore-log: 
10-12 09:18:39.544  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.544  5676  5722 I jxcore-log: 
,10-12 09:18:39.551  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.551  5676  5722 I jxcore-log: 
,10-12 09:18:39.553  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.553  5676  5722 I jxcore-log: 
,10-12 09:18:39.554  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.554  5676  5722 I jxcore-log: 
,10-12 09:18:39.555  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.555  5676  5722 I jxcore-log: 
10-12 09:18:39.555  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.555  5676  5722 I jxcore-log: 
,10-12 09:18:39.556  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.556  5676  5722 I jxcore-log: 
10-12 09:18:39.557  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.557  5676  5722 I jxcore-log: 
,10-12 09:18:39.557  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.557  5676  5722 I jxcore-log: 
,10-12 09:18:39.559  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.559  5676  5722 I jxcore-log: 
,10-12 09:18:39.560  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.560  5676  5722 I jxcore-log: 
,10-12 09:18:39.560  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.560  5676  5722 I jxcore-log: 
,10-12 09:18:39.561  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.561  5676  5722 I jxcore-log: 
10-12 09:18:39.562  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.562  5676  5722 I jxcore-log: 
,10-12 09:18:39.563  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.563  5676  5722 I jxcore-log: 
,10-12 09:18:39.563  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.563  5676  5722 I jxcore-log: 
10-12 09:18:39.564  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.564  5676  5722 I jxcore-log: 
,10-12 09:18:39.565  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.565  5676  5722 I jxcore-log: 
,10-12 09:18:39.566  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.566  5676  5722 I jxcore-log: 
10-12 09:18:39.567  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.567  5676  5722 I jxcore-log: 
,10-12 09:18:39.567  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.567  5676  5722 I jxcore-log: 
10-12 09:18:39.568  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.568  5676  5722 I jxcore-log: 
,10-12 09:18:39.569  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.569  5676  5722 I jxcore-log: 
10-12 09:18:39.569  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.569  5676  5722 I jxcore-log: 
,10-12 09:18:39.570  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.570  5676  5722 I jxcore-log: 
,10-12 09:18:39.571  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.571  5676  5722 I jxcore-log: 
10-12 09:18:39.572  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.572  5676  5722 I jxcore-log: 
,10-12 09:18:39.575  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.575  5676  5722 I jxcore-log: 
,10-12 09:18:39.576  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.576  5676  5722 I jxcore-log: 
,10-12 09:18:39.576  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.576  5676  5722 I jxcore-log: 
,10-12 09:18:39.577  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.577  5676  5722 I jxcore-log: 
10-12 09:18:39.578  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:39.578  5676  5722 I jxcore-log: 
,10-12 09:18:39.578  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:39.578  5676  5722 I jxcore-log: 
,10-12 09:18:39.623  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.623  5676  5722 I jxcore-log: 
,10-12 09:18:39.624  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.624  5676  5722 I jxcore-log: 
,10-12 09:18:39.625  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.625  5676  5722 I jxcore-log: 
10-12 09:18:39.626  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.626  5676  5722 I jxcore-log: 
,10-12 09:18:39.626  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.626  5676  5722 I jxcore-log: 
10-12 09:18:39.627  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.627  5676  5722 I jxcore-log: 
,10-12 09:18:39.627  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.627  5676  5722 I jxcore-log: 
,10-12 09:18:39.628  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.628  5676  5722 I jxcore-log: 
10-12 09:18:39.628  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.628  5676  5722 I jxcore-log: 
,10-12 09:18:39.629  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.629  5676  5722 I jxcore-log: 
10-12 09:18:39.629  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.629  5676  5722 I jxcore-log: 
,10-12 09:18:39.630  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.630  5676  5722 I jxcore-log: 
10-12 09:18:39.630  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.630  5676  5722 I jxcore-log: 
10-12 09:18:39.630  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.630  5676  5722 I jxcore-log: 
10-12 09:18:39.631  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.631  5676  5722 I jxcore-log: 
,10-12 09:18:39.632  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.632  5676  5722 I jxcore-log: 
10-12 09:18:39.632  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.632  5676  5722 I jxcore-log: 
10-12 09:18:39.633  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.633  5676  5722 I jxcore-log: 
10-12 09:18:39.633  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.633  5676  5722 I jxcore-log: 
,10-12 09:18:39.634  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.634  5676  5722 I jxcore-log: 
10-12 09:18:39.634  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.634  5676  5722 I jxcore-log: 
10-12 09:18:39.634  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.634  5676  5722 I jxcore-log: 
10-12 09:18:39.635  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.635  5676  5722 I jxcore-log: 
,10-12 09:18:39.635  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.635  5676  5722 I jxcore-log: 
10-12 09:18:39.636  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.636  5676  5722 I jxcore-log: 
10-12 09:18:39.636  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.636  5676  5722 I jxcore-log: 
10-12 09:18:39.637  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.637  5676  5722 I jxcore-log: 
,10-12 09:18:39.637  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.637  5676  5722 I jxcore-log: 
10-12 09:18:39.638  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.638  5676  5722 I jxcore-log: 
10-12 09:18:39.638  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.638  5676  5722 I jxcore-log: 
10-12 09:18:39.638  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.638  5676  5722 I jxcore-log: 
10-12 09:18:39.639  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.639  5676  5722 I jxcore-log: 
10-12 09:18:39.639  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.639  5676  5722 I jxcore-log: 
10-12 09:18:39.640  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.640  5676  5722 I jxcore-log: 
10-12 09:18:39.640  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.640  5676  5722 I jxcore-log: 
10-12 09:18:39.640  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.640  5676  5722 I jxcore-log: 
10-12 09:18:39.641  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.641  5676  5722 I jxcore-log: 
10-12 09:18:39.641  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.641  5676  5722 I jxcore-log: 
10-12 09:18:39.642  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.642  5676  5722 I jxcore-log: 
10-12 09:18:39.642  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.642  5676  5722 I jxcore-log: 
10-12 09:18:39.643  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.643  5676  5722 I jxcore-log: 
10-12 09:18:39.643  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.643  5676  5722 I jxcore-log: 
10-12 09:18:39.643  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.643  5676  5722 I jxcore-log: 
10-12 09:18:39.644  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.644  5676  5722 I jxcore-log: 
10-12 09:18:39.645  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.645  5676  5722 I jxcore-log: 
10-12 09:18:39.646  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.646  5676  5722 I jxcore-log: 
10-12 09:18:39.648  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.648  5676  5722 I jxcore-log: 
10-12 09:18:39.649  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.649  5676  5722 I jxcore-log: 
10-12 09:18:39.650  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:39.650  5676  5722 I jxcore-log: 
10-12 09:18:39.650  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'mux close'
10-12 09:18:39.650  5676  5722 I jxcore-log: 
10-12 09:18:39.652  5676  5722 I jxcore-log: ok 28 native server is nulled out
10-12 09:18:39.652  5676  5722 I jxcore-log: 
10-12 09:18:39.652  5676  5722 I jxcore-log: ok 29 native server should be closed
10-12 09:18:39.652  5676  5722 I jxcore-log: 
10-12 09:18:39.652  5676  5722 I jxcore-log: ok 30 incoming has been removed
10-12 09:18:39.652  5676  5722 I jxcore-log: 
10-12 09:18:39.653  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.653  5676  5722 I jxcore-log: 
10-12 09:18:39.654  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.654  5676  5722 I jxcore-log: 
10-12 09:18:39.654  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.654  5676  5722 I jxcore-log: 
10-12 09:18:39.654  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.654  5676  5722 I jxcore-log: 
10-12 09:18:39.655  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.655  5676  5722 I jxcore-log: 
10-12 09:18:39.655  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.655  5676  5722 I jxcore-log: 
10-12 09:18:39.655  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.655  5676  5722 I jxcore-log: 
10-12 09:18:39.655  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.655  5676  5722 I jxcore-log: 
10-12 09:18:39.655  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.655  5676  5722 I jxcore-log: 
10-12 09:18:39.656  5676  5722 I jxcore-log: 2016-10-12 13:18:39 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:39.656  5676  5722 I jxcore-log: 
,10-12 09:18:39.727  5676  5722 I jxcore-log: # teardown
10-12 09:18:39.727  5676  5722 I jxcore-log: 
,10-12 09:18:39.835  5676  5722 I jxcore-log: # setup
10-12 09:18:39.835  5676  5722 I jxcore-log: 
,10-12 09:18:42.538  5676  5722 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-12 09:18:42.538  5676  5722 I jxcore-log: 
,10-12 09:18:43.456  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:43.456  5676  5722 I jxcore-log: 
,10-12 09:18:43.461  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'listening 43122'
10-12 09:18:43.461  5676  5722 I jxcore-log: 
,10-12 09:18:43.468  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:43.468  5676  5722 I jxcore-log: 
10-12 09:18:43.470  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:43.470  5676  5722 I jxcore-log: 
,10-12 09:18:43.472  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'new mux'
10-12 09:18:43.472  5676  5722 I jxcore-log: 
,10-12 09:18:43.480  5676  5722 I jxcore-log: ok 31 we should not have gotten an error
10-12 09:18:43.480  5676  5722 I jxcore-log: 
,10-12 09:18:43.484  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:43.484  5676  5722 I jxcore-log: 
,10-12 09:18:43.486  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:43.486  5676  5722 I jxcore-log: 
,10-12 09:18:43.493  5676  5722 I jxcore-log: ok 32 Buffers are identical
10-12 09:18:43.493  5676  5722 I jxcore-log: 
,10-12 09:18:43.494  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:43.494  5676  5722 I jxcore-log: 
10-12 09:18:43.496  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'mux close'
10-12 09:18:43.496  5676  5722 I jxcore-log: 
,10-12 09:18:43.506  5676  5722 I jxcore-log: 2016-10-12 13:18:43 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:43.506  5676  5722 I jxcore-log: 
,10-12 09:18:43.506  5676  5722 I jxcore-log: ok 33 server should be fine
10-12 09:18:43.506  5676  5722 I jxcore-log: 
10-12 09:18:43.507  5676  5722 I jxcore-log: ok 34 server should be open
10-12 09:18:43.507  5676  5722 I jxcore-log: 
10-12 09:18:43.507  5676  5722 I jxcore-log: ok 35 incoming has been removed
10-12 09:18:43.507  5676  5722 I jxcore-log: 
,10-12 09:18:43.507  5676  5722 I jxcore-log: ok 36 The mux object should be closed
10-12 09:18:43.507  5676  5722 I jxcore-log: 
10-12 09:18:43.507  5676  5722 I jxcore-log: ok 37 The mux stream should be closed
10-12 09:18:43.507  5676  5722 I jxcore-log: 
,10-12 09:18:43.513  5676  5722 I jxcore-log: # teardown
10-12 09:18:43.513  5676  5722 I jxcore-log: 
,10-12 09:18:43.865  5676  5722 I jxcore-log: # setup
10-12 09:18:43.865  5676  5722 I jxcore-log: 
,10-12 09:18:44.701  5676  5722 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-12 09:18:44.701  5676  5722 I jxcore-log: 
,10-12 09:18:45.091  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'creating native server'
10-12 09:18:45.091  5676  5722 I jxcore-log: 
,10-12 09:18:45.097  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'listening 37926'
10-12 09:18:45.097  5676  5722 I jxcore-log: 
,10-12 09:18:45.106  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'new incoming socket'
10-12 09:18:45.106  5676  5722 I jxcore-log: 
,10-12 09:18:45.108  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'creating incoming mux'
10-12 09:18:45.108  5676  5722 I jxcore-log: 
,10-12 09:18:45.109  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'new mux'
10-12 09:18:45.109  5676  5722 I jxcore-log: 
,10-12 09:18:45.118  5676  5722 I jxcore-log: ok 38 we should not have gotten an error
10-12 09:18:45.118  5676  5722 I jxcore-log: 
,10-12 09:18:45.123  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'new stream: '
10-12 09:18:45.123  5676  5722 I jxcore-log: 
,10-12 09:18:45.126  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'new outgoing socket'
10-12 09:18:45.126  5676  5722 I jxcore-log: 
,10-12 09:18:45.133   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:45.134  5676  5722 I jxcore-log: ok 39 Buffers are identical
10-12 09:18:45.134  5676  5722 I jxcore-log: 
,10-12 09:18:45.140  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'incoming socket timeout'
10-12 09:18:45.140  5676  5722 I jxcore-log: 
,10-12 09:18:45.141  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'stream close:'
10-12 09:18:45.141  5676  5722 I jxcore-log: 
,10-12 09:18:45.144  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'mux close'
10-12 09:18:45.144  5676  5722 I jxcore-log: 
,10-12 09:18:45.150  5676  5722 I jxcore-log: 2016-10-12 13:18:45 - DEBUG createNativeListener: 'incoming socket close'
10-12 09:18:45.150  5676  5722 I jxcore-log: 
,10-12 09:18:45.151  5676  5722 I jxcore-log: ok 40 server should be fine
10-12 09:18:45.151  5676  5722 I jxcore-log: 
,10-12 09:18:45.151  5676  5722 I jxcore-log: ok 41 server should be open
10-12 09:18:45.151  5676  5722 I jxcore-log: 
,10-12 09:18:45.152  5676  5722 I jxcore-log: ok 42 incoming has been removed
10-12 09:18:45.152  5676  5722 I jxcore-log: 
,10-12 09:18:45.153  5676  5722 I jxcore-log: ok 43 The mux object should be closed
10-12 09:18:45.153  5676  5722 I jxcore-log: 
10-12 09:18:45.153  5676  5722 I jxcore-log: ok 44 The mux stream should be closed
10-12 09:18:45.153  5676  5722 I jxcore-log: 
,10-12 09:18:45.161  5676  5722 I jxcore-log: # teardown
10-12 09:18:45.161  5676  5722 I jxcore-log: 
,10-12 09:18:46.020  5676  5722 I jxcore-log: # setup
10-12 09:18:46.020  5676  5722 I jxcore-log: 
,10-12 09:18:46.134   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:46.200  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-12 09:18:46.200  5676  5722 I jxcore-log: 
,10-12 09:18:47.136   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:47.262  5676  5722 I jxcore-log: 2016-10-12 13:18:47 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-12 09:18:47.262  5676  5722 I jxcore-log: 
,10-12 09:18:47.263  5676  5722 I jxcore-log: ok 45 Got right error
10-12 09:18:47.263  5676  5722 I jxcore-log: 
,10-12 09:18:47.268  5676  5722 I jxcore-log: # teardown
10-12 09:18:47.268  5676  5722 I jxcore-log: 
,10-12 09:18:47.660  5676  5722 I jxcore-log: # setup
10-12 09:18:47.660  5676  5722 I jxcore-log: 
,10-12 09:18:47.846   927  2984 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:18:48.136   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:48.369  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-12 09:18:48.369  5676  5722 I jxcore-log: 
,10-12 09:18:48.835  5676  5722 I jxcore-log: 2016-10-12 13:18:48 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-12 09:18:48.835  5676  5722 I jxcore-log: 
,10-12 09:18:48.836  5676  5722 I jxcore-log: ok 46 Got socket hang up
10-12 09:18:48.836  5676  5722 I jxcore-log: 
,10-12 09:18:48.842  5676  5722 I jxcore-log: # teardown
10-12 09:18:48.842  5676  5722 I jxcore-log: 
,10-12 09:18:49.137   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:49.706  5676  5722 I jxcore-log: # setup
10-12 09:18:49.706  5676  5722 I jxcore-log: 
,10-12 09:18:50.118  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-12 09:18:50.118  5676  5722 I jxcore-log: 
,10-12 09:18:50.138   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-12 09:18:50.959  5676  5722 I jxcore-log: 2016-10-12 13:18:50 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-12 09:18:50.959  5676  5722 I jxcore-log: 
,10-12 09:18:50.960  5676  5722 I jxcore-log: ok 47 Got 500 as expected
10-12 09:18:50.960  5676  5722 I jxcore-log: 
,10-12 09:18:50.964  5676  5722 I jxcore-log: # teardown
10-12 09:18:50.964  5676  5722 I jxcore-log: 
,10-12 09:18:51.557  5676  5722 I jxcore-log: # setup
10-12 09:18:51.557  5676  5722 I jxcore-log: 
,10-12 09:18:52.161  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-12 09:18:52.161  5676  5722 I jxcore-log: 
,10-12 09:18:54.134  5676  5722 I jxcore-log: ok 48 should be equal
10-12 09:18:54.134  5676  5722 I jxcore-log: 
,10-12 09:18:54.135  5676  5722 I jxcore-log: ok 49 revs are equal
10-12 09:18:54.135  5676  5722 I jxcore-log: 
,10-12 09:18:54.139  5676  5722 I jxcore-log: # teardown
10-12 09:18:54.139  5676  5722 I jxcore-log: 
,10-12 09:18:54.244  5676  5722 I jxcore-log: # setup
10-12 09:18:54.244  5676  5722 I jxcore-log: 
,10-12 09:18:54.931  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-12 09:18:54.931  5676  5722 I jxcore-log: 
,10-12 09:18:55.139   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:56.141   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:56.297  5676  5722 I jxcore-log: ok 50 should be equal
10-12 09:18:56.297  5676  5722 I jxcore-log: 
,10-12 09:18:56.297  5676  5722 I jxcore-log: ok 51 revs are equal
10-12 09:18:56.297  5676  5722 I jxcore-log: 
,10-12 09:18:56.301  5676  5722 I jxcore-log: # teardown
10-12 09:18:56.301  5676  5722 I jxcore-log: 
,10-12 09:18:56.907  5676  5722 I jxcore-log: # setup
10-12 09:18:56.907  5676  5722 I jxcore-log: 
,10-12 09:18:57.142   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:57.592  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-12 09:18:57.592  5676  5722 I jxcore-log: 
,10-12 09:18:58.144   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:59.145   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:18:59.545  5676  5722 I jxcore-log: ok 52 should be equal
10-12 09:18:59.545  5676  5722 I jxcore-log: 
,10-12 09:18:59.546  5676  5722 I jxcore-log: ok 53 revs are equal
10-12 09:18:59.546  5676  5722 I jxcore-log: 
,10-12 09:18:59.711  5676  5722 I jxcore-log: ok 54 should be equal
10-12 09:18:59.711  5676  5722 I jxcore-log: 
,10-12 09:18:59.712  5676  5722 I jxcore-log: ok 55 revs are equal
10-12 09:18:59.712  5676  5722 I jxcore-log: 
,10-12 09:18:59.920  5676  5722 I jxcore-log: ok 56 should be equal
10-12 09:18:59.920  5676  5722 I jxcore-log: 
,10-12 09:18:59.921  5676  5722 I jxcore-log: ok 57 revs are equal
10-12 09:18:59.921  5676  5722 I jxcore-log: 
,10-12 09:18:59.930  5676  5722 I jxcore-log: # teardown
10-12 09:18:59.930  5676  5722 I jxcore-log: 
,10-12 09:18:59.983  5676  5722 I jxcore-log: # setup
10-12 09:18:59.983  5676  5722 I jxcore-log: 
,10-12 09:19:00.145   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-12 09:19:00.869  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-12 09:19:00.869  5676  5722 I jxcore-log: 
,10-12 09:19:02.008  5676  5722 I jxcore-log: 2016-10-12 13:19:02 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-12 09:19:02.008  5676  5722 I jxcore-log: 
,10-12 09:19:02.010  5676  5722 I jxcore-log: ok 58 Our rev is old so we should fail
10-12 09:19:02.010  5676  5722 I jxcore-log: 
,10-12 09:19:02.028  5676  5722 I jxcore-log: # teardown
10-12 09:19:02.028  5676  5722 I jxcore-log: 
,10-12 09:19:02.628  5676  5722 I jxcore-log: # setup
10-12 09:19:02.628  5676  5722 I jxcore-log: 
,10-12 09:19:03.524  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-12 09:19:03.524  5676  5722 I jxcore-log: 
,10-12 09:19:04.096  5676  5722 I jxcore-log: ok 59 confirm stop caused failure
10-12 09:19:04.096  5676  5722 I jxcore-log: 
,10-12 09:19:04.110  5676  5722 I jxcore-log: # teardown
10-12 09:19:04.110  5676  5722 I jxcore-log: 
,10-12 09:19:04.860  5676  5722 I jxcore-log: # setup
10-12 09:19:04.860  5676  5722 I jxcore-log: 
,10-12 09:19:05.171  5676  5722 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-12 09:19:05.171  5676  5722 I jxcore-log: 
,10-12 09:19:06.393  5676  5722 I jxcore-log: 2016-10-12 13:19:06 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-12 09:19:06.393  5676  5722 I jxcore-log: 
,10-12 09:19:06.394  5676  5722 I jxcore-log: ok 60 stop caused us to fail
10-12 09:19:06.394  5676  5722 I jxcore-log: 
10-12 09:19:06.395  5676  5722 I jxcore-log: ok 61 We specifically failed on a stop before put
10-12 09:19:06.395  5676  5722 I jxcore-log: 
,10-12 09:19:06.411  5676  5722 I jxcore-log: # teardown
10-12 09:19:06.411  5676  5722 I jxcore-log: 
,10-12 09:19:06.471  5676  5722 I jxcore-log: # setup
10-12 09:19:06.471  5676  5722 I jxcore-log: 
,10-12 09:19:06.528  5676  5722 I jxcore-log: # #update - fail if stop is called
10-12 09:19:06.528  5676  5722 I jxcore-log: 
,10-12 09:19:06.630  5676  5722 I jxcore-log: ok 62 failed due to stop
10-12 09:19:06.630  5676  5722 I jxcore-log: 
,10-12 09:19:06.631  5676  5722 I jxcore-log: ok 63 failed due to stop
10-12 09:19:06.631  5676  5722 I jxcore-log: 
,10-12 09:19:06.640  5676  5722 I jxcore-log: # teardown
10-12 09:19:06.640  5676  5722 I jxcore-log: 
,10-12 09:19:06.713  5676  5722 I jxcore-log: # setup
10-12 09:19:06.713  5676  5722 I jxcore-log: 
,10-12 09:19:06.769  5676  5722 I jxcore-log: # #update - set seq for first time
10-12 09:19:06.769  5676  5722 I jxcore-log: 
,10-12 09:19:07.476  5676  5722 I jxcore-log: ok 64 should be equal
10-12 09:19:07.476  5676  5722 I jxcore-log: 
,10-12 09:19:07.499  5676  5722 I jxcore-log: # teardown
10-12 09:19:07.499  5676  5722 I jxcore-log: 
,10-12 09:19:07.541  5676  5722 I jxcore-log: # setup
10-12 09:19:07.541  5676  5722 I jxcore-log: 
,10-12 09:19:07.602  5676  5722 I jxcore-log: # #update - Fail on bad seq value
10-12 09:19:07.602  5676  5722 I jxcore-log: 
,10-12 09:19:07.846   927  2984 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:19:08.135  5676  5722 I jxcore-log: 2016-10-12 13:19:08 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-12 09:19:08.135  5676  5722 I jxcore-log: 
,10-12 09:19:08.137  5676  5722 I jxcore-log: ok 65 Expected bad seq error
10-12 09:19:08.137  5676  5722 I jxcore-log: 
,10-12 09:19:08.158  5676  5722 I jxcore-log: # teardown
10-12 09:19:08.158  5676  5722 I jxcore-log: 
,10-12 09:19:08.213  5676  5722 I jxcore-log: # setup
10-12 09:19:08.213  5676  5722 I jxcore-log: 
,10-12 09:19:08.258  5676  5722 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-12 09:19:08.258  5676  5722 I jxcore-log: 
,10-12 09:19:08.366  5676  5722 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-12 09:19:08.366  5676  5722 E jxcore-log: 
,10-12 09:19:08.368  5676  5722 E jxcore-log: Trace: 
10-12 09:19:08.368  5676  5722 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-12 09:19:08.368  5676  5722 E jxcore-log:     at addListener@events.js:140:1
10-12 09:19:08.368  5676  5722 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
10-12 09:19:08.368  5676  5722 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-12 09:19:08.368  5676  5722 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-12 09:19:08.368  5676  5722 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-12 09:19:08.368  5676  5722 E jxcore-log: 
,10-12 09:19:09.196  5676  5722 I jxcore-log: ok 66 Different promises
10-12 09:19:09.196  5676  5722 I jxcore-log: 
,10-12 09:19:09.197  5676  5722 I jxcore-log: ok 67 Timer was cancelled
10-12 09:19:09.197  5676  5722 I jxcore-log: 
,10-12 09:19:09.366  5676  5722 I jxcore-log: ok 68 should be equal
10-12 09:19:09.366  5676  5722 I jxcore-log: 
,10-12 09:19:09.415  5676  5722 I jxcore-log: # teardown
10-12 09:19:09.415  5676  5722 I jxcore-log: 
,10-12 09:19:10.146   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:10.725  5676  5722 I jxcore-log: # setup
10-12 09:19:10.725  5676  5722 I jxcore-log: 
,10-12 09:19:11.148   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:12.023  5676  5722 I jxcore-log: # #update - do we wait for blocked update
10-12 09:19:12.023  5676  5722 I jxcore-log: 
,10-12 09:19:12.149   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:13.110  5676  5722 I jxcore-log: ok 69 One go and one blocked
10-12 09:19:13.110  5676  5722 I jxcore-log: 
,10-12 09:19:13.111  5676  5722 I jxcore-log: ok 70 All blocked
10-12 09:19:13.111  5676  5722 I jxcore-log: 
10-12 09:19:13.112  5676  5722 I jxcore-log: ok 71 Still blocked
10-12 09:19:13.112  5676  5722 I jxcore-log: 
,10-12 09:19:13.128  5676  5722 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-12 09:19:13.128  5676  5722 E jxcore-log: 
,10-12 09:19:13.130  5676  5722 E jxcore-log: Trace: 
10-12 09:19:13.130  5676  5722 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-12 09:19:13.130  5676  5722 E jxcore-log:     at addListener@events.js:140:1
10-12 09:19:13.130  5676  5722 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
10-12 09:19:13.130  5676  5722 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-12 09:19:13.130  5676  5722 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-12 09:19:13.130  5676  5722 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-12 09:19:13.130  5676  5722 E jxcore-log: 
,10-12 09:19:13.150   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:13.814  5676  5722 I jxcore-log: ok 72 should be equal
10-12 09:19:13.814  5676  5722 I jxcore-log: 
,10-12 09:19:13.845  5676  5722 I jxcore-log: # teardown
10-12 09:19:13.845  5676  5722 I jxcore-log: 
,10-12 09:19:14.025  5676  5722 I jxcore-log: # setup
10-12 09:19:14.025  5676  5722 I jxcore-log: 
,10-12 09:19:14.152   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:15.152   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-12 09:19:15.614  5676  5722 I jxcore-log: # #update - test that we wait long enough
10-12 09:19:15.614  5676  5722 I jxcore-log: 
,10-12 09:19:17.180  5676  5722 I jxcore-log: ok 73 We waited long enough
10-12 09:19:17.180  5676  5722 I jxcore-log: 
,10-12 09:19:17.389  5676  5722 I jxcore-log: ok 74 should be equal
10-12 09:19:17.389  5676  5722 I jxcore-log: 
,10-12 09:19:17.442  5676  5722 I jxcore-log: # teardown
10-12 09:19:17.442  5676  5722 I jxcore-log: 
,10-12 09:19:18.200  5676  5722 I jxcore-log: # setup
10-12 09:19:18.200  5676  5722 I jxcore-log: 
,10-12 09:19:19.712  5676  5722 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-12 09:19:19.712  5676  5722 I jxcore-log: 
,10-12 09:19:22.412  5676  5722 I jxcore-log: ok 75 Should have gotten same timer promise
10-12 09:19:22.412  5676  5722 I jxcore-log: 
,10-12 09:19:22.413  5676  5722 I jxcore-log: ok 76 Still same timer promise
10-12 09:19:22.413  5676  5722 I jxcore-log: 
,10-12 09:19:23.021  5676  5722 I jxcore-log: ok 77 We waited long enough
10-12 09:19:23.021  5676  5722 I jxcore-log: 
,10-12 09:19:23.146  5676  5722 I jxcore-log: ok 78 should be equal
10-12 09:19:23.146  5676  5722 I jxcore-log: 
,10-12 09:19:23.208  5676  5722 I jxcore-log: # teardown
10-12 09:19:23.208  5676  5722 I jxcore-log: 
,10-12 09:19:24.336  5676  5722 I jxcore-log: # setup
10-12 09:19:24.336  5676  5722 I jxcore-log: 
,10-12 09:19:25.076  5676  5722 I jxcore-log: # Coordinated seq test
10-12 09:19:25.076  5676  5722 I jxcore-log: 
,10-12 09:19:25.599  5676  5722 I jxcore-log: 2016-10-12 13:19:25 - DEBUG thaliWifiInfrastructure: 'listening 41454'
10-12 09:19:25.599  5676  5722 I jxcore-log: 
,10-12 09:19:27.848   927  2984 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:19:28.020  5676  5722 I jxcore-log: ok 79 should be equal
10-12 09:19:28.020  5676  5722 I jxcore-log: 
,10-12 09:19:30.154   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:30.250  5676  5722 I jxcore-log: ok 80 should be equal
10-12 09:19:30.250  5676  5722 I jxcore-log: 
,10-12 09:19:30.272  5676  5722 I jxcore-log: # teardown
10-12 09:19:30.272  5676  5722 I jxcore-log: 
,10-12 09:19:31.156   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:32.157   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:33.158   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:34.159   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:35.160   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-12 09:19:55.161   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:56.163   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:57.164   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:58.165   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:19:59.167   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 09:20:00.167   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-12 09:20:07.850   927  2984 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:20:11.493   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:20:14.527   927  2998 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 09:20:25.168   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-12 09:20:25.168   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-12 09:20:27.852   927  2984 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 09:20:30.291  5676  5722 I jxcore-log: 2016-10-12 13:20:30 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-12 09:20:30.291  5676  5722 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-12 09:20:30.291  5676  5722 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-12 09:20:30.291  5676  5722 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-12 09:20:30.291  5676  5722 I jxcore-log:     at $9@timers.js:120:1
10-12 09:20:30.291  5676  5722 I jxcore-log: ''
10-12 09:20:30.291  5676  5722 I jxcore-log: 
,10-12 09:20:30.294  5676  5722 I jxcore-log: 2016-10-12 13:20:30 - DEBUG CoordinatedClient: 'test client failed'
10-12 09:20:30.294  5676  5722 I jxcore-log: 
,10-12 09:20:30.305  5676  5722 I jxcore-log: 2016-10-12 13:20:30 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-12 09:20:30.305  5676  5722 I jxcore-log: 
,10-12 09:20:30.313  5676  5722 I jxcore-log: 2016-10-12 13:20:30 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-12 09:20:30.313  5676  5722 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-12 09:20:30.313  5676  5722 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-12 09:20:30.313  5676  5722 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-12 09:20:30.313  5676  5722 I jxcore-log:     at $9@timers.js:120:1
10-12 09:20:30.313  5676  5722 I jxcore-log: ''
10-12 09:20:30.313  5676  5722 I jxcore-log: 
,10-12 09:20:30.314  5676  5722 I jxcore-log: 2016-10-12 13:20:30 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-12 09:20:30.314  5676  5722 I jxcore-log: 
,10-12 09:20:30.388   927  2967 W InputDispatcher: channel '9496c94 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-12 09:20:30.389   927  2967 E InputDispatcher: channel '9496c94 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
10-12 09:20:30.398   927  3181 I WindowState: WIN DEATH: Window{9496c94 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-12 09:20:30.398   927  3181 W InputDispatcher: Attempted to unregister already unregistered input channel '9496c94 com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-12 09:20:30.399   927  2992 D WifiService: Client connection lost with reason: 4
,10-12 09:20:30.400   927  3618 D GraphicsStats: Buffer count: 2
,10-12 09:20:30.405   927  5198 I ActivityManager: Process com.test.thalitest (pid 5676) has died
10-12 09:20:30.405   528   528 I Zygote  : Process 5676 exited cleanly (139)
,10-12 09:20:30.429   927  5198 I ActivityManager: Start proc 6060:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-12 09:20:30.754   927  3874 I WindowManager: Screenshot max retries 4 of Token{d312d46 ActivityRecord{103c521 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{249af9b u0 Starting com.test.thalitest} drawState=4
,10-12 09:20:30.834  6060  6060 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-12 09:20:30.852  6060  6060 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-12 09:20:30.857  6060  6060 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 126-128)
,10-12 09:20:30.857  6060  6060 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 09:20:30.866  6060  6060 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {be8f046}
10-12 09:20:30.866  6060  6060 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 09:20:30.866  6060  6060 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 09:20:30.869  6060  6060 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-12 09:20:30.870  6060  6060 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-12 09:20:30.881  6060  6060 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-12 09:20:30.888  6060  6060 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-12 09:20:30.888  6060  6060 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 09:20:30.888  6060  6060 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-12 09:20:30.888  6060  6060 I Adreno  : Build Date                       : 12/06/15
10-12 09:20:30.888  6060  6060 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-12 09:20:30.888  6060  6060 I Adreno  : Local Branch                     : mybranch17112971
10-12 09:20:30.888  6060  6060 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-12 09:20:30.888  6060  6060 I Adreno  : Remote Branch                    : NONE
10-12 09:20:30.888  6060  6060 I Adreno  : Reconstruct Branch               : NOTHING
,10-12 09:20:30.899  6057  6057 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-12 09:20:30.918  6057  6057 D AndroidRuntime: CheckJNI is OFF
,10-12 09:20:30.930   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0ad50:true
,10-12 09:20:30.943  6057  6057 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-12 09:20:30.941   681   681 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[19177]" dev="sockfs" ino=19177 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 09:20:30.941   681   681 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[19177]" dev="sockfs" ino=19177 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 09:20:30.953  6060  6060 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-12 09:20:30.961  6060  6060 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-12 09:20:30.967  6057  6057 I Radio-JNI: register_android_hardware_Radio DONE
,10-12 09:20:30.982  6057  6057 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-12 09:20:30.990   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-12 09:20:30.991   927   940 I ActivityManager: Killing 6060:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-12 09:20:31.042   927   940 I ActivityManager: Start proc 6103:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-12 09:20:31.043   927   940 I ActivityManager:   Force finishing activity ActivityRecord{103c521 u0 com.test.thalitest/.MainActivity t2}
,10-12 09:20:31.051   927  3869 W ActivityManager: Spurious death for ProcessRecord{6420a80 0:com.test.thalitest/u0a77}, curProc for 6060: null
,10-12 09:20:31.060   927   945 W WindowManager: Failed looking up window
10-12 09:20:31.060   927   945 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@8c037aa does not exist
10-12 09:20:31.060   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-12 09:20:31.060   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-12 09:20:31.060   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-12 09:20:31.060   927   945 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-12 09:20:31.060   927   945 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-12 09:20:31.060   927   945 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-12 09:20:31.060   927   945 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-12 09:20:31.060   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:20:31.060   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.060   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 09:20:31.060   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-12 09:20:31.166   927   950 I art     : Starting a blocking GC Explicit
,10-12 09:20:31.186  6103  6103 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,10-12 09:20:31.186  6103  6103 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,10-12 09:20:31.186  6103  6103 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
10-12 09:20:31.186  6103  6103 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,10-12 09:20:31.202  6103  6103 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
10-12 09:20:31.203  6103  6103 E AndroidRuntime: FATAL EXCEPTION: main
10-12 09:20:31.203  6103  6103 E AndroidRuntime: Process: com.test.thalitest, PID: 6103
10-12 09:20:31.203  6103  6103 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:578)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4685)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:424)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:570)
10-12 09:20:31.203  6103  6103 E AndroidRuntime: 	... 9 more
,10-12 09:20:31.208  6103  6103 I Process : Sending signal. PID: 6103 SIG: 9
,10-12 09:20:31.238   927  3874 I ActivityManager: Process com.test.thalitest (pid 6103) has died
,10-12 09:20:31.264   927   950 I art     : Explicit concurrent mark sweep GC freed 89987(6MB) AllocSpace objects, 48(1576KB) LOS objects, 33% free, 29MB/43MB, paused 1.616ms total 97.966ms
,10-12 09:20:31.284   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-12 09:20:31.287  6057  6057 I art     : System.exit called, status: 0
,10-12 09:20:31.287  6057  6057 I AndroidRuntime: VM exiting with result code 0.
,10-12 09:20:31.301   927   950 I ActivityManager: Start proc 6117:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-12 09:20:31.301   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-12 09:20:31.310  5960  5960 D BluetoothMapAppObserver: onReceive
,10-12 09:20:31.310  5960  5960 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-12 09:20:31.318  3689  3689 I Keyboard.Facilitator: resetDictionaries() : en_US
10-12 09:20:31.320  4079  4191 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-12 09:20:31.321   927  2968 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-12 09:20:31.343  3689  6129 I Keyboard.Facilitator.DecoderInitializer: run()
,10-12 09:20:31.356  3689  6129 I Decoder : createOrResetDecoder
,10-12 09:20:31.358  3421  6132 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-12 09:20:31.360  3811  3811 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-12 09:20:31.386  3604  3604 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-12 09:20:31.386  3604  3604 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-12 09:20:31.395    28    28 W kworker/2:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 09:20:31.401    28    28 W kworker/2:1: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 09:20:31.410   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-12 09:20:31.411    28    28 W kworker/2:1: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-12 09:20:31.415  3849  3959 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-12 09:20:31.429   927  3190 I ActivityManager: Start proc 6137:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
10-12 09:20:31.429  3721  6136 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-12 09:20:31.429  3721  6136 D AccountUtils: Clearing selected account for com.test.thalitest
,10-12 09:20:31.429  3849  3959 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-12 09:20:31.429  3849  3959 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3849
10-12 09:20:31.429  3849  3959 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.429  3849  3959 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 09:20:31.431   927  3874 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-12 09:20:31.433   927  6147 E DropBoxManagerService: Can't write: system_app_crash
10-12 09:20:31.433   927  6147 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 09:20:31.433   927  6147 E DropBoxManagerService: 	... 5 more
10-12 09:20:31.439  3849  3959 I Process : Sending signal. PID: 3849 SIG: 9
,10-12 09:20:31.454  3421  3443 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj45223F935) - 
,10-12 09:20:31.455  3421  3443 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-12 09:20:31.455  3421  3443 E AndroidRuntime: Process: android.process.acore, PID: 3421
10-12 09:20:31.455  3421  3443 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.455  3421  3443 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 09:20:31.459   927  6153 E DropBoxManagerService: Can't write: system_app_crash
10-12 09:20:31.459   927  6153 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 09:20:31.459   927  6153 E DropBoxManagerService: 	... 5 more
,10-12 09:20:31.466  3604  3604 I ConfigService: onCreate
,10-12 09:20:31.469  3604  6154 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-12 09:20:31.469  3604  6154 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-12 09:20:31.469  3604  6154 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-12 09:20:31.471  3604  6154 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-12 09:20:31.489  3689  6129 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-12 09:20:31.506  3421  6132 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-12 09:20:31.507  3421  6132 I Process : Sending signal. PID: 3421 SIG: 9
,10-12 09:20:31.563   927   937 D GraphicsStats: Buffer count: 1
,10-12 09:20:31.563   927   938 I WindowState: WIN DEATH: Window{625f771 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-12 09:20:31.569   927  5198 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3849) has died
,10-12 09:20:31.569   927  5198 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-12 09:20:31.571   927  5198 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-12 09:20:31.589   927   940 I ActivityManager: Start proc 6156:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-12 09:20:31.597   927  5198 I ActivityManager: Process android.process.acore (pid 3421) has died
,10-12 09:20:31.597   927  5198 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-12 09:20:31.632  6156  6156 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:20:31.632  6156  6156 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-12 09:20:31.632  6156  6156 D AndroidRuntime: Shutting down VM
,10-12 09:20:31.638  6156  6156 E AndroidRuntime: FATAL EXCEPTION: main
10-12 09:20:31.638  6156  6156 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6156
10-12 09:20:31.638  6156  6156 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-12 09:20:31.638  6156  6156 E AndroidRuntime: 	... 10 more
,10-12 09:20:31.642   927  3869 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-12 09:20:31.642   927  6169 E DropBoxManagerService: Can't write: system_app_crash
10-12 09:20:31.642   927  6169 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 09:20:31.642   927  6169 E DropBoxManagerService: 	... 5 more
,10-12 09:20:31.643  6156  6156 I Process : Sending signal. PID: 6156 SIG: 9
,10-12 09:20:31.666   927  3181 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6156) has died
,10-12 09:20:31.667   927  3181 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-12 09:20:31.682   927   940 I ActivityManager: Start proc 6170:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-12 09:20:31.727  6170  6170 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:20:31.727  6170  6170 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:20:31.727  6170  6170 D AndroidRuntime: Shutting down VM
,10-12 09:20:31.734  6170  6170 E AndroidRuntime: FATAL EXCEPTION: main
10-12 09:20:31.734  6170  6170 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6170
10-12 09:20:31.734  6170  6170 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-12 09:20:31.734  6170  6170 E AndroidRuntime: 	... 10 more
10-12 09:20:31.738   927  6182 E DropBoxManagerService: Can't write: system_app_crash
10-12 09:20:31.738   927  6182 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 09:20:31.738   927  6182 E DropBoxManagerService: 	... 5 more
10-12 09:20:31.737   927   938 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-12 09:20:31.738  6170  6170 I Process : Sending signal. PID: 6170 SIG: 9
10-12 09:20:31.755   927  3869 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6170) has died
10-12 09:20:31.756   927  3869 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-12 09:20:31.771   927   940 I ActivityManager: Start proc 6183:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-12 09:20:31.790   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
