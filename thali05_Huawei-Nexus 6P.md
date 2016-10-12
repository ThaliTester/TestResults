#### Test 871194046935740_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of system
10-12 06:49:50.123   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
10-12 06:49:50.628  5650  5650 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-12 06:49:50.634  5650  5650 D AndroidRuntime: CheckJNI is OFF
10-12 06:49:50.666  5650  5650 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-12 06:49:50.716  5650  5650 I Radio-JNI: register_android_hardware_Radio DONE
10-12 06:49:50.731  5650  5650 D AndroidRuntime: Calling main entry com.android.commands.am.Am
10-12 06:49:50.736   925  3851 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-12 06:49:50.777   925  3851 I ActivityManager: Start proc 5659:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-12 06:49:50.803  5650  5650 D AndroidRuntime: Shutting down VM
10-12 06:49:50.890   548   548 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-12 06:49:50.891   548   548 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-12 06:49:51.118   925  3217 I WindowManager: Screenshot max retries 4 of Token{8476abe ActivityRecord{6ef2d79 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{30412b1 u0 Starting com.test.thalitest} drawState=4
,10-12 06:49:51.193  5659  5659 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-12 06:49:51.226  5659  5659 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-12 06:49:51.252  5659  5659 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 8814-8836)
,10-12 06:49:51.252  5659  5659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 06:49:51.273  5659  5659 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23bb59f}
,10-12 06:49:51.273  5659  5659 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-12 06:49:51.274  5659  5659 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 06:49:51.279  5659  5659 I BrowserStartupController: Initializing chromium process, singleProcess=true
10-12 06:49:51.280  5659  5659 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-12 06:49:51.322  5659  5659 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-12 06:49:51.337  5659  5659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-12 06:49:51.338  5659  5659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 06:49:51.338  5659  5659 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-12 06:49:51.338  5659  5659 I Adreno  : Build Date                       : 12/06/15
10-12 06:49:51.338  5659  5659 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-12 06:49:51.338  5659  5659 I Adreno  : Local Branch                     : mybranch17112971
10-12 06:49:51.338  5659  5659 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-12 06:49:51.338  5659  5659 I Adreno  : Remote Branch                    : NONE
10-12 06:49:51.338  5659  5659 I Adreno  : Reconstruct Branch               : NOTHING
,10-12 06:49:51.393   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@eb966e9:true
,10-12 06:49:51.428   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[27505]" dev="sockfs" ino=27505 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 06:49:51.428   406   406 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[27505]" dev="sockfs" ino=27505 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 06:49:51.440  5659  5659 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-12 06:49:51.449  5659  5659 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-12 06:49:51.474  3189  3189 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34858]" dev="sockfs" ino=34858 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 06:49:51.475  5659  5696 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-12 06:49:51.474  3189  3189 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34858]" dev="sockfs" ino=34858 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 06:49:51.474  3224  3224 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13787]" dev="sockfs" ino=13787 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-12 06:49:51.478  3224  3224 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[13787]" dev="sockfs" ino=13787 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-12 06:49:51.482  5659  5683 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-12 06:49:51.514  5659  5696 I OpenGLRenderer: Initialized EGL, version 1.4
,10-12 06:49:51.585   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +466ms (total +834ms)
,10-12 06:49:51.610  5659  5659 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5659
,10-12 06:49:51.698  5659  5659 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-12 06:49:51.835  5659  5699 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -563345104
,10-12 06:49:51.839  5659  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-12 06:49:51.839  5659  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-12 06:49:51.839  5659  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-12 06:49:51.839  5659  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-12 06:49:51.839  5659  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-12 06:49:51.839  5659  5699 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7480844 added. We now have 1 listener(s)
,10-12 06:49:51.842  5659  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-12 06:49:51.842  5659  5699 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 06:49:51.843  5659  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:49:51.843  5659  5699 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-12 06:49:51.846  5659  5699 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c37eff3 added. We now have 1 listener(s)
10-12 06:49:51.846  5659  5699 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:49:51.853   925  2978 D WifiService: New client listening to asynchronous messages
,10-12 06:49:51.855  5659  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 06:49:51.855  5659  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-12 06:49:51.855  5659  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-12 06:49:51.855  5659  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-12 06:49:51.855  5659  5699 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-12 06:49:51.857  5659  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 06:49:51.858  5659  5699 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-12 06:49:51.862  5659  5699 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:49:51.862  5659  5699 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:49:51.863  5659  5699 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-12 06:49:51.863  5659  5699 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:49:51.863  5659  5699 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-12 06:49:51.865  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:49:51.867  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:49:51.879  5659  5659 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-12 06:49:52.274  5659  5705 W jxcore-log: Initializing JXcore engine
,10-12 06:49:52.274  5659  5705 W jxcore-log: JXcore engine is ready
,10-12 06:49:52.304  5705  5705 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11596 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-12 06:49:52.304  5705  5705 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16398]" dev="sockfs" ino=16398 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-12 06:49:52.304  5705  5705 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,10-12 06:49:52.304  5705  5705 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34835]" dev="sockfs" ino=34835 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-12 06:49:52.315  5659  5705 W jxcore-log: Starting JXcore engine
,10-12 06:49:52.373  5659  5705 W jxcore-log: Platform android
10-12 06:49:52.373  5659  5705 W jxcore-log: 
,10-12 06:49:52.373  5659  5705 W jxcore-log: Process ARCH arm
10-12 06:49:52.373  5659  5705 W jxcore-log: 
,10-12 06:49:52.518  5659  5705 I jxcore-log: JXcore Cordova bridge is ready!
10-12 06:49:52.518  5659  5705 I jxcore-log: 
,10-12 06:49:52.518  5659  5705 W jxcore-log: JXcore engine is started
,10-12 06:49:52.526  5659  5699 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-12 06:49:52.532  5659  5659 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-12 06:49:54.470   925  2968 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 06:50:00.892   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:01.893   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:02.244  5659  5705 I jxcore-log: 2016-10-12 10:50:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-12 06:50:02.244  5659  5705 I jxcore-log: 
,10-12 06:50:02.246  5659  5705 I jxcore-log: 2016-10-12 10:50:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-12 06:50:02.246  5659  5705 I jxcore-log: 
,10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:02.250  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:50:02.251  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 06:50:02.253  5659  5705 I jxcore-log: 2016-10-12 10:50:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-12 06:50:02.253  5659  5705 I jxcore-log: 
,10-12 06:50:02.254  5659  5705 I jxcore-log: 2016-10-12 10:50:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-12 06:50:02.254  5659  5705 I jxcore-log: 
,10-12 06:50:02.495  5659  5705 I jxcore-log: 2016-10-12 10:50:02 - DEBUG UnitTest_app: 'Running unit tests'
10-12 06:50:02.495  5659  5705 I jxcore-log: 
,10-12 06:50:02.496  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:50:02.496  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c6a7c8a added. We now have 2 listener(s)
10-12 06:50:02.497  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-12 06:50:02.497  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:50:02.497  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:50:02.497  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 06:50:02.497  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80542fb added. We now have 2 listener(s)
10-12 06:50:02.497  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:50:02.498  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 06:50:02.500  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:02.502  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:50:02.503  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:02.503  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:50:02.504  5659  5705 D executeNativeTests: Running unit tests
,10-12 06:50:02.510  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:02.518  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:02.541  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 06:50:02.541  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 added. We now have 3 listener(s)
10-12 06:50:02.542  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:50:02.542  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:50:02.542  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 06:50:02.542  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:50:02.542  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 added. We now have 3 listener(s)
,10-12 06:50:02.542  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:50:02.542  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 06:50:02.544  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:02.546  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:50:02.547  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:02.547  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:50:02.548  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 06:50:02.548  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 06:50:02.549  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 06:50:02.549  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 06:50:02.549  5659  5705 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-12 06:50:02.549  5659  5705 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 06:50:02.549  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 06:50:02.549  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 06:50:02.549  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 06:50:02.550  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 06:50:02.550  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:02.550  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:02.550  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 06:50:02.551  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:02.551  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:02.551  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:50:02.551  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:02.551  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:50:02.551  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 removed from the list
10-12 06:50:02.551  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:02.551  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 removed from the list
10-12 06:50:02.557  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:02.562  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:02.562  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:02.563  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:02.563  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:02.563  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:02.563  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:02.563  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:02.564  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:02.564  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:02.564  5659  5705 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-12 06:50:02.565  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:02.565  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 06:50:02.565  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:02.565  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:02.565  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:02.565  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:02.565  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:02.565  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:02.565  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:02.565  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:02.565  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 06:50:02.565  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:02.565  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:02.565  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:02.565  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:02.566  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:02.566  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:02.566  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:02.566  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-12 06:50:02.569  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,10-12 06:50:02.570  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-12 06:50:02.570  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-12 06:50:02.570  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-12 06:50:02.570  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-12 06:50:02.570  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-12 06:50:02.570  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,10-12 06:50:02.570  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:02.570  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:02.570  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 06:50:02.570  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:02.570  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:02.570  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:02.570  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 06:50:02.570  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:02.570  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:02.570  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
,10-12 06:50:02.570  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:02.570  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:02.570  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:02.570  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:02.570  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:02.571  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:02.571  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:02.571  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:02.571  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:02.571  5659  5705 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-12 06:50:02.572  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:02.574  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:50:02.575  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:02.575  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:50:02.575  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:50:02.575  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-12 06:50:02.575  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 06:50:02.575  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:50:02.575  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 06:50:02.577  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:02.578  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:02.579  5659  5705 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 06:50:02.579  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 06:50:02.581  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 06:50:02.582  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 06:50:02.582  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 06:50:02.583  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-12 06:50:02.584  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-12 06:50:02.585  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 06:50:02.585  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 06:50:02.585  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-12 06:50:02.585  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 06:50:02.585  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 06:50:02.585  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:50:02.587  4605  4837 D BtGatt.GattService: registerClient() - UUID=fb5e2856-1924-4951-a903-75daebd902d4
,10-12 06:50:02.588  4605  4687 D BtGatt.GattService: onClientRegistered() - UUID=fb5e2856-1924-4951-a903-75daebd902d4, clientIf=5
,10-12 06:50:02.589  5659  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-12 06:50:02.590  4605  4624 D BtGatt.GattService: start scan with filters
10-12 06:50:02.599  4605  4692 D BtGatt.ScanManager: handling starting scan
10-12 06:50:02.599  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 06:50:02.599  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-12 06:50:02.599  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:50:02.599  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 06:50:02.599  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 06:50:02.599  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,10-12 06:50:02.599  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 06:50:02.600  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:50:02.600  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 06:50:02.600  4605  4692 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
10-12 06:50:02.600  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:50:02.601  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 06:50:02.602  5659  5705 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 06:50:02.608  4605  4687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 06:50:02.608  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:02.609  4605  4692 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 06:50:02.616  4605  4687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 06:50:02.616  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:02.616  4605  4692 D BtGatt.ScanManager: Starting BLE batch scan
,10-12 06:50:02.616  4605  4692 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 06:50:02.628  4605  4687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 06:50:02.628  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:02.635  4605  4687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 06:50:02.635  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:02.895   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:03.102  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-12 06:50:03.103  5659  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:50:03.103  5659  5659 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 06:50:03.896   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:04.897   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:05.898   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-12 06:50:07.606  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:07.606  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:07.607  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-12 06:50:07.607  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:07.607  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 06:50:07.607  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:07.607  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 06:50:07.607  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-12 06:50:07.607  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 06:50:07.607  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 06:50:07.608  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-12 06:50:07.608  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-12 06:50:07.609  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:50:07.610  4605  4846 D BtGatt.GattService: stopScan() - queue size =1
10-12 06:50:07.611  4605  4626 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 06:50:07.611  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-12 06:50:07.611  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 06:50:07.611  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 06:50:07.612  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:50:07.612  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 06:50:07.612  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 06:50:07.612  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-12 06:50:07.612  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 06:50:07.613  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:07.613  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 06:50:07.614  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 06:50:07.614  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-12 06:50:07.614  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 06:50:07.615  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:50:07.616  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:07.617  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:07.617  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:07.617  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:50:07.617  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:07.617  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
,10-12 06:50:07.617  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:07.617  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:07.617  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:07.617  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:07.617  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 06:50:07.617  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:07.621  4605  4605 D BtGatt.ScanManager: awakened up at time 235206
,10-12 06:50:07.627  4605  4687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 06:50:07.627  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:07.627  4605  4692 D BtGatt.ScanManager: stopping BLe Batch
,10-12 06:50:07.636  4605  4687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 06:50:07.636  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:07.637  4605  4692 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 06:50:07.658  4605  4687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
10-12 06:50:07.658  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:07.659  4605  4687 D BtGatt.GattService: current time is 235243825401
10-12 06:50:07.659  4605  4687 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -83, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -88, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-12 06:50:07.661  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-12 06:50:07.662  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-12 06:50:07.662  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-12 06:50:07.663  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-12 06:50:07.663  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-12 06:50:07.663  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-12 06:50:08.118  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 06:50:10.899   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:11.901   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:12.621  5659  5705 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-12 06:50:12.627  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:12.638  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:50:12.643  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 06:50:12.644  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:50:12.644  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:50:12.644  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 06:50:12.644  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 06:50:12.644  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:50:12.645  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 06:50:12.649  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:12.651  5659  5705 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 06:50:12.651  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 06:50:12.654  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:12.656  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 06:50:12.657  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 06:50:12.657  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 06:50:12.661  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 06:50:12.661  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 06:50:12.661  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 06:50:12.661  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 06:50:12.662  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-12 06:50:12.663  5659  5705 D BluetoothAdapter: STATE_ON
,10-12 06:50:12.665  4605  4624 D BtGatt.GattService: registerClient() - UUID=e57e0e82-1563-4995-b0ae-a808f362d14e
,10-12 06:50:12.666  4605  4687 D BtGatt.GattService: onClientRegistered() - UUID=e57e0e82-1563-4995-b0ae-a808f362d14e, clientIf=5
10-12 06:50:12.667  5659  5670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 06:50:12.667  4605  4845 D BtGatt.GattService: start scan with filters
,10-12 06:50:12.670  4605  4692 D BtGatt.ScanManager: handling starting scan
,10-12 06:50:12.671  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-12 06:50:12.671  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 06:50:12.671  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-12 06:50:12.671  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 06:50:12.671  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 06:50:12.671  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 06:50:12.672  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 06:50:12.674  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:50:12.674  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 06:50:12.674  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:50:12.678  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 06:50:12.679  4605  4687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 06:50:12.679  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.680  4605  4692 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 06:50:12.681  5659  5705 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 06:50:12.684  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:12.684  5659  5705 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-12 06:50:12.684  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:12.684  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 06:50:12.684  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:12.684  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 06:50:12.685  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:12.685  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 06:50:12.685  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 06:50:12.685  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 06:50:12.685  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 06:50:12.685  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 06:50:12.685  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-12 06:50:12.686  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:50:12.686  4605  4624 D BtGatt.GattService: stopScan() - queue size =1
10-12 06:50:12.687  4605  4837 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 06:50:12.687  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 06:50:12.688  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 06:50:12.688  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 06:50:12.688  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:50:12.688  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-12 06:50:12.688  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 06:50:12.688  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 06:50:12.688  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 06:50:12.688  4605  4687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 06:50:12.688  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.689  4605  4692 D BtGatt.ScanManager: Starting BLE batch scan
10-12 06:50:12.689  4605  4692 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 06:50:12.690  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:12.690  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 06:50:12.690  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 06:50:12.690  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 06:50:12.690  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 06:50:12.691  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:50:12.692  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:12.692  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:12.692  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:12.692  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:12.692  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 06:50:12.692  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:12.692  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:12.692  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:12.692  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:12.692  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:12.692  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:12.692  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:12.694  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:12.694  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:12.695  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:12.695  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:12.695  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:12.695  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:12.696  5659  5705 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-12 06:50:12.698  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:50:12.702  4605  4687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 06:50:12.702  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:12.703  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:50:12.707  4605  4687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-12 06:50:12.707  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:12.707  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.708  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:50:12.708  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:50:12.708  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 06:50:12.708  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 06:50:12.708  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:50:12.708  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-12 06:50:12.711  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:12.712  5659  5705 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-12 06:50:12.712  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 06:50:12.713  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:12.715  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 06:50:12.716  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 06:50:12.716  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 06:50:12.716  4605  4687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 06:50:12.716  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.716  4605  4692 D BtGatt.ScanManager: stopping BLe Batch
,10-12 06:50:12.719  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 06:50:12.719  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 06:50:12.719  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 06:50:12.719  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 06:50:12.719  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 06:50:12.720  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:50:12.721  4605  4687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 06:50:12.721  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.721  4605  4692 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 06:50:12.722  4605  4624 D BtGatt.GattService: registerClient() - UUID=837f9e65-4715-4425-b923-866bcb3ff774
,10-12 06:50:12.723  4605  4687 D BtGatt.GattService: onClientRegistered() - UUID=837f9e65-4715-4425-b923-866bcb3ff774, clientIf=5
10-12 06:50:12.723  5659  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 06:50:12.724  4605  4837 D BtGatt.GattService: start scan with filters
,10-12 06:50:12.727  4605  4687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-12 06:50:12.727  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.728  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 06:50:12.728  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 06:50:12.728  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:50:12.728  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 06:50:12.728  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 06:50:12.728  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 06:50:12.728  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 06:50:12.729  4605  4692 D BtGatt.ScanManager: handling starting scan
10-12 06:50:12.730  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:50:12.730  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 06:50:12.730  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 06:50:12.732  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 06:50:12.734  5659  5705 I io.jxcore.node.ConnectionHelper: start: OK
,10-12 06:50:12.736  4605  4687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-12 06:50:12.736  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.737  4605  4692 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-12 06:50:12.743  4605  4687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 06:50:12.743  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:12.743  4605  4692 D BtGatt.ScanManager: Starting BLE batch scan
10-12 06:50:12.743  4605  4692 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 06:50:12.766  4605  4687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-12 06:50:12.766  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:12.770  4605  4687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 06:50:12.770  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:12.902   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:13.232  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-12 06:50:13.232  5659  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:50:13.232  5659  5659 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 06:50:13.904   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:14.332   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 06:50:14.338   925  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-12 06:50:14.905   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:15.906   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-12 06:50:17.362   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 06:50:17.371   925  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-12 06:50:17.735  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:50:17.735  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-12 06:50:17.735  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-12 06:50:17.736  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:17.736  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-12 06:50:17.736  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:17.736  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 06:50:17.736  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 06:50:17.736  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 06:50:17.736  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-12 06:50:17.737  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 06:50:17.737  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 06:50:17.739  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:50:17.741  4605  4624 D BtGatt.GattService: stopScan() - queue size =1
10-12 06:50:17.743  4605  4837 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 06:50:17.743  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 06:50:17.744  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 06:50:17.744  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 06:50:17.744  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:50:17.744  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 06:50:17.744  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 06:50:17.744  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 06:50:17.745  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 06:50:17.748  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:17.748  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 06:50:17.748  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 06:50:17.748  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 06:50:17.749  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 06:50:17.749  4605  4605 D BtGatt.ScanManager: awakened up at time 245333
10-12 06:50:17.751  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 06:50:17.754  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:17.754  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:17.754  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:17.755  4605  4687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 06:50:17.755  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:17.755  4605  4692 D BtGatt.ScanManager: stopping BLe Batch
,10-12 06:50:17.761  4605  4687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 06:50:17.762  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:50:17.762  4605  4692 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 06:50:17.783  4605  4687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-12 06:50:17.783  4605  4687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:50:17.783  4605  4687 D BtGatt.GattService: current time is 245368392561
10-12 06:50:17.783  4605  4687 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -79, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -88, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -52, 11, 57, -70, 107, -17, 1, 0, -97, 25, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
10-12 06:50:17.784  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-12 06:50:17.784  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-12 06:50:17.784  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-12 06:50:17.784  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-12 06:50:17.784  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-12 06:50:17.785  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-12 06:50:17.785  4605  4687 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,10-12 06:50:18.255  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 06:50:18.255  5659  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 06:50:18.256  5659  5659 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-12 06:50:20.388   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 06:50:20.395   925  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-12 06:50:22.756  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:50:22.756  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.756  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.756  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.757  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.757  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:50:22.757  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.757  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
,10-12 06:50:22.757  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.757  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.758  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.758  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.760  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.761  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:22.764  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-12 06:50:22.764  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.764  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.764  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
,10-12 06:50:22.767  5659  5705 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-12 06:50:22.769  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:22.770  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 06:50:22.770  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.770  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.770  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:22.771  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.771  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.771  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.771  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.771  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
,10-12 06:50:22.772  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.772  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.772  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.772  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.773  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:22.775  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-12 06:50:22.776  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.776  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:22.776  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.778  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-12 06:50:22.778  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:50:22.778  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.778  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.779  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.779  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:22.779  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.779  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.779  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.779  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.779  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.779  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.780  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:22.780  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.780  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.780  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:22.782  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.783  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.783  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.783  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
,10-12 06:50:22.784  5659  5705 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-12 06:50:22.784  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:22.785  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.785  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.785  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.785  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:22.785  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.785  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.786  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.786  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.786  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.786  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.786  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.786  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:22.786  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.786  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.788  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.789  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.789  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.789  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.790  5659  5705 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-12 06:50:22.790  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:50:22.791  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.791  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.791  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.791  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.791  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.791  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.792  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.792  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:22.792  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.792  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.792  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.792  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.792  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.792  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.795  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.795  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.795  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.796  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
,10-12 06:50:22.797  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 06:50:22.797  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-12 06:50:22.797  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 06:50:22.797  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 06:50:22.797  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 06:50:22.797  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 06:50:22.797  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-12 06:50:22.798  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 06:50:22.798  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-12 06:50:22.798  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:22.798  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.798  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 06:50:22.798  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.798  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.799  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.799  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.799  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.799  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.799  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.799  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.799  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.799  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:22.799  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.799  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.801  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.801  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.801  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.801  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.803  5659  5705 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 06:50:22.803  5659  5705 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 06:50:22.803  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-12 06:50:22.809  5659  5705 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 06:50:22.809  5659  5705 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-12 06:50:22.809  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-12 06:50:22.809  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-12 06:50:22.809  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-12 06:50:22.809  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-12 06:50:22.810  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-12 06:50:22.811  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-12 06:50:22.812  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-12 06:50:22.812  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-12 06:50:22.812  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-12 06:50:22.812  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-12 06:50:22.812  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-12 06:50:22.812  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-12 06:50:22.812  5659  5705 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-12 06:50:22.813  5659  5705 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 06:50:22.813  5659  5705 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-12 06:50:22.813  5659  5705 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 06:50:22.813  5659  5705 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-12 06:50:22.813  5659  5705 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-12 06:50:22.813  5659  5705 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 06:50:22.814  5659  5705 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-12 06:50:22.814  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-12 06:50:22.818  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-12 06:50:22.819  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-12 06:50:22.819  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-12 06:50:22.820  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-12 06:50:22.820  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-12 06:50:22.820  5659  5705 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-12 06:50:22.821  5659  5705 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-12 06:50:22.821  5659  5705 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-12 06:50:22.821  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-12 06:50:22.821  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-12 06:50:22.821  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,10-12 06:50:22.821  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-12 06:50:22.822  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:22.822  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.822  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.822  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.822  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.822  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.822  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.822  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-12 06:50:22.824  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.824  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.824  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
,10-12 06:50:22.824  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.824  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.824  5659  5706 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-12 06:50:22.824  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.824  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.824  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.824  5659  5706 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 06:50:22.825  5659  5707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-12 06:50:22.826  5659  5707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-12 06:50:22.826  5659  5707 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-12 06:50:22.826  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.826  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.826  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.826  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.827  5659  5705 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-12 06:50:22.824  4837  4837 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33329]" dev="sockfs" ino=33329 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 06:50:22.827  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:50:22.827  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.828  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.824  4837  4837 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33329]" dev="sockfs" ino=33329 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 06:50:22.828  5659  5706 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-12 06:50:22.828  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.828  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-12 06:50:22.828  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.828  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-12 06:50:22.828  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.828  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.828  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.828  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.828  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.828  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 06:50:22.828  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.828  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.829  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.829  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.830  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.830  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.830  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.830  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.831  5659  5705 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-12 06:50:22.831  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:22.831  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.832  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.832  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.832  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.832  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:22.832  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.832  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.832  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.832  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.832  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.832  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.832  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.832  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.833  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.834  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.834  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.834  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.834  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.835  5659  5705 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,10-12 06:50:22.835  5659  5705 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-12 06:50:22.835  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 06:50:22.835  5659  5705 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-12 06:50:22.836  5659  5705 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 06:50:22.836  5659  5705 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-12 06:50:22.836  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 06:50:22.836  5659  5705 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-12 06:50:22.836  5659  5705 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-12 06:50:22.836  5659  5705 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-12 06:50:22.836  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-12 06:50:22.836  5659  5705 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-12 06:50:22.836  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:22.836  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:22.836  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:22.836  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:22.837  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:22.837  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.837  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.837  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.837  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.837  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.837  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.837  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.837  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.837  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.837  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.839  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:22.839  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:22.839  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.839  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.839  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 06:50:22.840  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.840  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:22.840  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:22.840  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:22.840  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:22.840  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:22.840  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:22.840  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:22.840  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:23.416   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 06:50:25.907   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:26.908   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:27.841  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:27.841  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.841  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 06:50:27.842  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:27.842  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:27.842  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:27.842  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
,10-12 06:50:27.842  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:27.843  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:27.843  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:27.844  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 06:50:27.844  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.844  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.844  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 06:50:27.844  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:27.844  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.844  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.845  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:27.845  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.845  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:27.845  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.845  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.848  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:27.848  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:27.848  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.848  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.854  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-12 06:50:27.854  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:50:27.856  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-12 06:50:27.858  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-12 06:50:27.859  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-12 06:50:27.860  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-12 06:50:27.860  5659  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-12 06:50:27.860  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-12 06:50:27.860  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 06:50:27.860  5659  5659 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-12 06:50:27.861  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 06:50:27.861  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-12 06:50:27.861  5659  5708 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 06:50:27.861  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-12 06:50:27.861  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-12 06:50:27.861  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.861  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 06:50:27.861  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-12 06:50:27.861  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:27.861  5659  5659 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-12 06:50:27.861  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.861  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 06:50:27.861  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 06:50:27.861  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 06:50:27.862  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.862  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:27.863  5659  5708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-12 06:50:27.863  5659  5708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-12 06:50:27.863  5659  5708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-12 06:50:27.863  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:27.864  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.864  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:50:27.864  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:27.864  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:27.864  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:27.864  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:50:27.864  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:27.864  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.864  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:50:27.864  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:27.864  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-12 06:50:27.861  4845  4845 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34893]" dev="sockfs" ino=34893 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 06:50:27.864  5659  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-12 06:50:27.864  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:27.864  5659  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:27.864  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.864  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.865  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:27.865  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.861  4845  4845 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34893]" dev="sockfs" ino=34893 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-12 06:50:27.865  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:27.865  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:27.866  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.867  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:27.867  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:27.867  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.867  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.868  5659  5705 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,10-12 06:50:27.869  5659  5705 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-12 06:50:27.869  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-12 06:50:27.869  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-12 06:50:27.869  5659  5705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-12 06:50:27.869  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:27.869  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:27.869  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:27.869  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-12 06:50:27.869  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.869  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.869  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:27.869  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:27.870  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.870  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.870  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:27.870  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.870  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:27.870  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.870  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.871  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:27.871  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:27.871  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.871  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.875  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:27.875  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:27.875  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-12 06:50:27.875  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:27.875  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.875  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.875  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:27.876  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
,10-12 06:50:27.876  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.876  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.876  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:27.876  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.876  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.876  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.876  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.879  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:27.879  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:27.879  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:27.879  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.880  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:50:27.880  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:50:27.880  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:50:27.880  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:50:27.880  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.881  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.881  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:50:27.881  5659  5705 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a3b4e1 not in the list
10-12 06:50:27.881  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.881  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
,10-12 06:50:27.881  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:27.881  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.881  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.881  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:27.881  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:27.883  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:50:27.883  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:50:27.883  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:50:27.883  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d6c206 not in the list
10-12 06:50:27.884  5659  5705 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-12 06:50:27.885  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 06:50:27.885  5659  5705 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-12 06:50:27.885  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-12 06:50:27.885  5659  5705 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-12 06:50:27.885  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-12 06:50:27.887  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-12 06:50:27.887  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-12 06:50:27.889  5659  5705 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-12 06:50:27.889  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 06:50:27.889  5659  5705 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-12 06:50:27.889  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-12 06:50:27.889  5659  5705 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-12 06:50:27.889  5659  5705 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-12 06:50:27.889  5659  5705 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-12 06:50:27.889  5659  5705 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-12 06:50:27.890  5659  5705 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-12 06:50:27.890  5659  5705 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-12 06:50:27.890  5659  5705 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-12 06:50:27.890  5659  5705 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,10-12 06:50:27.891  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:50:27.891  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8091978 added. We now have 3 listener(s)
10-12 06:50:27.891  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:50:27.892  5659  5705 D BluetoothAdapter: enable(): BT is already enabled..!
10-12 06:50:27.893   925  3847 D WifiService: setWifiEnabled: true pid=5659, uid=10077
10-12 06:50:27.893   925  3847 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 06:50:27.908   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:27.955  4605  4811 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-12 06:50:27.956  4605  4835 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-12 06:50:28.365  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 06:50:28.909   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:29.458   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-12 06:50:29.910   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:30.910   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-12 06:50:32.897  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 06:50:32.898  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c729851 added. We now have 4 listener(s)
,10-12 06:50:32.898  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:50:32.911  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:32.913  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c729851 removed from the list
,10-12 06:50:32.913  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:32.913  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:32.913  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:32.914  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 06:50:32.914  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d9b8b6 added. We now have 4 listener(s)
10-12 06:50:32.915  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:50:32.919  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:32.919  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d9b8b6 removed from the list
10-12 06:50:32.919  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:50:32.920  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:32.920  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:32.921  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:50:32.921  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bf49b7 added. We now have 4 listener(s)
10-12 06:50:32.921  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:50:32.926   925   936 D WifiService: setWifiEnabled: false pid=5659, uid=10077
10-12 06:50:32.927   925   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 06:50:32.936   925  2968 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-12 06:50:32.936   925  2968 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-12 06:50:32.937   925  2968 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 06:50:32.937   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-12 06:50:32.941  4605  4683 D BluetoothAdapterState: Current state: ON, message: 23
,10-12 06:50:32.941  4605  4683 D BluetoothAdapterProperties: Setting state to 13
10-12 06:50:32.942  4605  4683 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-12 06:50:32.943  4605  4683 D BluetoothAdapterProperties: onBluetoothDisable()
10-12 06:50:32.944  4605  4683 I BluetoothAdapterState: Entering PendingCommandState
,10-12 06:50:32.948  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 06:50:32.948  4605  4687 D BluetoothAdapterProperties: Scan Mode:20
10-12 06:50:32.950  4605  4683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-12 06:50:32.954  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:32.954  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:50:32.955  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:32.955  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:32.955  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:50:32.955  4605  4605 D HeadsetService: Received stop request...Stopping profile...
10-12 06:50:32.958   506   918 D CommandListener: Clearing all IP addresses on wlan0
10-12 06:50:32.958   925  5407 D DhcpClient: Clearing IP address
10-12 06:50:32.962  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:32.966  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:32.967   506   918 D CommandListener: Setting iface cfg
,10-12 06:50:32.969  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:32.970  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:50:32.970  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:32.970  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:32.971  3591  5460 V NativeCrypto: Read error: ssl=0x7f861f0100: I/O error during system call, Connection timed out
,10-12 06:50:32.973  3591  5460 V NativeCrypto: SSL shutdown failed: ssl=0x7f861f0100: I/O error during system call, Broken pipe
10-12 06:50:32.973   925  5408 D DhcpClient: Receive thread stopped
10-12 06:50:32.974   925  3217 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-12 06:50:32.974  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:32.974  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:50:32.975   925  5405 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-12 06:50:32.975  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:32.975  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:32.977   925  5405 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-12 06:50:32.977   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-12 06:50:32.978   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-12 06:50:32.979   925  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-12 06:50:32.979  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:32.980   925   938 I ActivityManager: Start proc 5713:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-12 06:50:32.982  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:32.986  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:32.988  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:32.989   925   925 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:32.989   925   925 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:32.989  4605  4605 D BluetoothMapService: onReceive
10-12 06:50:32.989   925   925 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:32.989  4605  4605 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 06:50:32.989  4605  4605 D BluetoothMapService: STATE_TURNING_OFF
10-12 06:50:32.989  4605  4605 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:32.989  3793  3827 D BluetoothHeadset: Proxy object disconnected
,10-12 06:50:32.989  4605  4605 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:32.989  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:32.989  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:32.990  3161  3172 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:32.990  4605  4605 D A2dpService: Received stop request...Stopping profile...
10-12 06:50:32.990   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-12 06:50:32.991   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-12 06:50:32.991  4605  4840 D A2dpStateMachine: Exit Disconnected: -1
10-12 06:50:32.992   925   925 D BluetoothA2dp: Proxy object disconnected
,10-12 06:50:32.995   925   925 D RttService: SCAN_AVAILABLE : 1
10-12 06:50:32.997  4605  4605 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-12 06:50:32.997  4605  4605 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-12 06:50:32.997   925  3088 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 06:50:32.997   546   546 E Parcel  : Reading a NULL string not supported here.
10-12 06:50:32.998  4605  4605 D HidService: Received stop request...Stopping profile...
10-12 06:50:32.998  4605  4605 D HidService: Stopping Bluetooth HidService
10-12 06:50:32.998  4605  4687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-12 06:50:32.998  4605  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:32.999  4605  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:32.999  4605  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:32.999  4605  4687 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-12 06:50:32.996  3161  3161 D HeadsetProfile: Bluetooth service disconnected
10-12 06:50:33.000  3161  3161 D BluetoothA2dp: Proxy object disconnected
10-12 06:50:33.000  3161  3161 D BluetoothInputDevice: Proxy object disconnected
10-12 06:50:33.000  3161  3161 D HidProfile: Bluetooth service disconnected
10-12 06:50:33.003  4605  4605 D HealthService: Received stop request...Stopping profile...
,10-12 06:50:33.005  4605  4605 D BluetoothMapService: MAP Service closeService in
10-12 06:50:33.005  4605  4605 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 06:50:33.005  4605  4605 D ObexServerSockets0: shutdown(block = true)
10-12 06:50:33.005   925  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-12 06:50:33.006  3762  3930 W QCNEJ   : |CORE| network lost: 100
,10-12 06:50:33.007  4605  4605 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 06:50:33.007  4605  4605 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 06:50:33.007  3762  3930 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-12 06:50:33.007  4605  4835 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 06:50:33.007  4605  4860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-12 06:50:33.007  4605  4861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-12 06:50:33.009  4605  4605 I BtOppRfcommListener: stopping Accept Thread
10-12 06:50:33.010  4605  5336 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 06:50:33.010  4605  5336 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-12 06:50:33.012  4605  4605 D PanService: Received stop request...Stopping profile...
10-12 06:50:33.013   925  2968 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-12 06:50:33.019  4605  4605 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:33.019  4605  4605 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:33.019  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:33.020  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 06:50:33.021  4605  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-12 06:50:33.021  4605  4687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 06:50:33.021  4605  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:33.021  4605  4811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 06:50:33.021  4605  4811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 06:50:33.021  4605  4811 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 06:50:33.021  4605  4811 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 06:50:33.021  4605  4605 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:33.021  4605  4605 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:33.021  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:33.021  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:33.022  4605  4605 D BluetoothMapService: Received stop request...Stopping profile...
,10-12 06:50:33.022  4605  4605 D BluetoothMapService: stop()
10-12 06:50:33.022  4605  4605 D BluetoothMapAppObserver: deinitObservers()
10-12 06:50:33.023  4605  4605 D BluetoothMapAppObserver: removeReceiver()
10-12 06:50:33.024  4605  4605 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 06:50:33.024  4605  4605 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-12 06:50:33.024  4605  4687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-12 06:50:33.024  4605  4605 D SapService: Received stop request...Stopping profile...
10-12 06:50:33.025  4605  4605 V SapService: stop()
10-12 06:50:33.025   925  2968 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 06:50:33.028  4605  4605 V BluetoothAdapterState: isTurningOff()=true
,10-12 06:50:33.029  4605  4605 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:33.029  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:33.029  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:33.029  4605  4605 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-12 06:50:33.029  4605  4687 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 06:50:33.029  4605  4605 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 06:50:33.031  3161  3161 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 06:50:33.031  3161  3161 D PanProfile: Bluetooth service disconnected
10-12 06:50:33.031  4605  4605 V BluetoothAdapterState: isTurningOff()=true
,10-12 06:50:33.031  4605  4605 V BluetoothAdapterState: isTurningOn()=false
,10-12 06:50:33.031  3161  3161 D BluetoothMap: Proxy object disconnected
10-12 06:50:33.031  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:33.031  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:33.031  3161  3161 D MapProfile: Bluetooth service disconnected
10-12 06:50:33.031  4605  4605 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 06:50:33.031  4605  4605 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-12 06:50:33.033  4605  4605 D BluetoothMapService: MAP Service closeService in
10-12 06:50:33.033  4605  4605 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:33.033  4605  4605 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:33.033  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:33.033  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:33.034  4605  4605 D BluetoothMapService: cleanup()
10-12 06:50:33.034  4605  4605 D BluetoothMapService: MAP Service closeService in
10-12 06:50:33.034  4605  4605 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:33.034  4605  4605 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:33.034  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:33.034  4605  4605 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:33.035  4605  4683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,10-12 06:50:33.035  4605  4683 D BluetoothAdapterProperties: Setting state to 15
10-12 06:50:33.035  4605  4683 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 06:50:33.035   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:33.036  3161  3985 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-12 06:50:33.036  4605  4683 I BluetoothAdapterState: Entering BleOnState,
10-12 06:50:33.037   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:33.037  3161  3172 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:33.037  3793  3827 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:33.038  3161  3174 D BluetoothMap: onBluetoothStateChange: up=false
10-12 06:50:33.038  3161  3985 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 06:50:33.039  3161  3172 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-12 06:50:33.040  3161  3174 D BluetoothPan: onBluetoothStateChange on: false
10-12 06:50:33.040   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:33.041   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 06:50:33.041  4605  4683 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 06:50:33.041  4605  4683 D BluetoothAdapterProperties: Setting state to 16
10-12 06:50:33.041  4605  4683 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 06:50:33.041  4605  4683 D BluetoothAdapterProperties: onBleDisable
10-12 06:50:33.042  4605  4683 I BluetoothAdapterState: Entering PendingCommandState
10-12 06:50:33.042  4605  4684 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-12 06:50:33.042  5713  5713 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-12 06:50:33.043  4605  4687 D BluetoothAdapterProperties: Scan Mode:20
10-12 06:50:33.044  4605  4811 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 06:50:33.044  4605  4811 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:33.045  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:33.045  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:33.046  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.046  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:33.048  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:33.048  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 06:50:33.049  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.049  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:33.050   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 06:50:33.050  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:33.051  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:33.051  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.051  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:33.052  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:33.053  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:33.054  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:33.059  5713  5713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 06:50:33.064   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@996abc4:true
10-12 06:50:33.065  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 06:50:33.073   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 06:50:33.073   506   918 D CommandListener: Clearing all IP addresses on wlan0
10-12 06:50:33.073   506   918 D TetherController: Setting IP forward enable = 0
10-12 06:50:33.075   925  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-12 06:50:33.075   925  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 06:50:33.078   925  3791 I ActivityManager: Start proc 5733:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-12 06:50:33.079   925  2968 D DhcpClient: doQuit
,10-12 06:50:33.079   925  2968 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 06:50:33.079   925  5407 D DhcpClient: onQuitting
10-12 06:50:33.080  3461  3461 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-12 06:50:33.082   925   942 D Tethering: MasterInitialState.processMessage what=3
10-12 06:50:33.085  5322  5322 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f9e6c7b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-12 06:50:33.088  4959  4959 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-12 06:50:33.091  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:33.091  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:33.092  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.092  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:33.095  5067  5090 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 06:50:33.095  5067  5090 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 06:50:33.095  5067  5090 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-12 06:50:33.096  5067  5090 E SarControlService: no key has been found,reset the power
10-12 06:50:33.096  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.096  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:33.096  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:33.096  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 06:50:33.096  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 06:50:33.096  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.096  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 06:50:33.096  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:33.096  5092  5092 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 06:50:33.097  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 06:50:33.097  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 06:50:33.098  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 06:50:33.098  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 06:50:33.098  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:33.099  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:33.099  5092  5092 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 06:50:33.099  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:33.101  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:33.101  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000ea03000000000000ffffffff]
10-12 06:50:33.101  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:50:33.101  5092  5106 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-12 06:50:33.101  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 06:50:33.101  5067  5077 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 06:50:33.103  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:33.104  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:33.105  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:33.107  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000eb03000000000000ffffffff]
10-12 06:50:33.107  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:50:33.107  5092  5106 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-12 06:50:33.108  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 06:50:33.108  5067  5078 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 06:50:33.109  3461  3461 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-12 06:50:33.115  5713  5713 D LocalBluetoothProfileManager: Adding local MAP profile
10-12 06:50:33.116  3461  3461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-12 06:50:33.118  5713  5713 D BluetoothMap: Create BluetoothMap proxy object
,10-12 06:50:33.134  5713  5713 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
10-12 06:50:33.137   506   918 E Netd    : netlink response contains error (No such file or directory)
10-12 06:50:33.138   506   918 D TetherController: Setting IP forward enable = 0
10-12 06:50:33.139   925  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 06:50:33.143  5733  5733 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
10-12 06:50:33.153  5713  5713 D DockEventReceiver: finishStartingService: stopping service
10-12 06:50:33.153  3461  3461 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-12 06:50:33.157   925  3173 I ActivityManager: Killing 5000:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-12 06:50:33.168  3461  3461 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-12 06:50:33.248  4605  4687 I bt_hci  : shut_down
,10-12 06:50:33.253  4605  4693 D bt_hwcfg: hw_epilog_process
,10-12 06:50:33.253  4605  4693 I bt_vendor: low_power_mode_cb
,10-12 06:50:33.255  4605  4693 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-12 06:50:33.255  4605  4693 I bt_vendor: epilog_cb
10-12 06:50:33.255  4605  4693 I bt_hci  : epilog_finished_callback
,10-12 06:50:33.258  4605  4687 I bt_hci_h4: hal_close
,10-12 06:50:33.258  4605  4687 I bt_userial_vendor: device fd = 54 close
,10-12 06:50:33.270   925  2968 D wifi    : In wifi stop Hal
,10-12 06:50:33.271   925  2968 D wifi    : halHandle = 0x7f6fc5ee00, mVM = 0x7f8c28d140, mCls = 0x100a02
10-12 06:50:33.272   925  3460 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 06:50:33.272   925  3460 D WifiHAL : Got a signal to exit!!!
10-12 06:50:33.272   925  3460 I WifiHAL : Exit wifi_event_loop
10-12 06:50:33.272  5041  5041 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 06:50:33.273  4069  4234 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 06:50:33.273   925  2968 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-12 06:50:33.273   925  2968 E WifiHAL : Event processing terminated
10-12 06:50:33.273   925  2968 D wifi    : In wifi cleaned up handler
10-12 06:50:33.273   925  2968 I WifiHAL : Internal cleanup completed
,10-12 06:50:33.274  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:33.276  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:33.278  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:33.294   925  3460 D wifi    : set interface wlan0 flags (DOWN)
,10-12 06:50:33.295   925  2968 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 06:50:33.333  5733  5733 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-12 06:50:33.333  5733  5733 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.333  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 06:50:33.334  5733  5733 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 06:50:33.334  5733  5733 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 06:50:33.334  5733  5733 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.k.d(PG:583)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:170)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 06:50:33.334  5733  5733 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 06:50:33.334  5733  5733 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.File.exists(File.java:361)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 06:50:33.334  5733  5733 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-12 06:50:33.334  5733  5733 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-12 06:50:33.339  5713  5713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 06:50:33.344  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 06:50:33.347  5713  5713 D DockEventReceiver: finishStartingService: stopping service
10-12 06:50:33.352   925  3791 I ActivityManager: Killing 5434:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
10-12 06:50:33.363  4605  4684 D bt_stack_manager: event_shut_down_stack finished.
10-12 06:50:33.363  4605  4683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-12 06:50:33.381  4605  4683 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-12 06:50:33.381  4605  4605 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 06:50:33.382  4605  4605 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 06:50:33.382  4605  4605 D BtGatt.GattService: stop()
10-12 06:50:33.382  4605  4605 D BtGatt.AdvertiseManager: advertise clients cleared
10-12 06:50:33.384  4605  4605 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:33.384  4605  4605 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:33.384  4605  4605 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:33.384  4605  4605 V BluetoothAdapterState: isBleTurningOff()=true
10-12 06:50:33.384  4605  4683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-12 06:50:33.384  4605  4683 D BluetoothAdapterProperties: Setting state to 10
10-12 06:50:33.384  4605  4683 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-12 06:50:33.385  3730  3730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 06:50:33.386  4605  4683 I BluetoothAdapterState: Entering OffState
10-12 06:50:33.386   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-12 06:50:33.392  4605  4605 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-12 06:50:33.392  4605  4605 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-12 06:50:33.392  4605  4605 I BluetoothServiceJni: cleanupNative: return from cleanup
10-12 06:50:33.394  4605  4684 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-12 06:50:33.402  3730  3730 D SystemUpdateService: onCreate
10-12 06:50:33.404  4605  4684 D bt_stack_manager: event_clean_up_stack finished.
10-12 06:50:33.406  3730  3730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-12 06:50:33.410  4605  4605 I art     : System.exit called, status: 0
10-12 06:50:33.410  4605  4605 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-12 06:50:33.415  3730  3730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-12 06:50:33.429  3730  3730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-12 06:50:33.430  3730  3730 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 06:50:33.442   925  3623 I ActivityManager: Start proc 5778:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-12 06:50:33.459  3730  5430 I iu.UploadsManager: num queued entries: 0
,10-12 06:50:33.460  3730  5430 I iu.UploadsManager: num updated entries: 0
,10-12 06:50:33.463   925   935 I ActivityManager: Process com.android.bluetooth (pid 4605) has died
,10-12 06:50:33.478  5778  5778 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-12 06:50:33.481  5778  5778 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 06:50:33.487  5778  5778 D SprintDMHelper: simOperator: 
10-12 06:50:33.487  5778  5778 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 06:50:33.489  3730  5776 I SystemUpdateService: active receiver: enabled
,10-12 06:50:33.497   925   942 D Tethering: InitialState.processMessage what=4
,10-12 06:50:33.499   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
10-12 06:50:33.499  5041  5790 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-12 06:50:33.505  3730  5776 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 06:50:33.507  3730  5430 I iu.SyncManager: NEXT; no task
,10-12 06:50:33.509  3730  5776 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-12 06:50:33.509  3730  5776 I SystemUpdateService: now status is 0 (complete)
,10-12 06:50:33.509  3730  5776 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 06:50:33.509  3730  5776 I SystemUpdateService: file has been verified
,10-12 06:50:33.509  3730  5776 I SystemUpdateService: OTA package size = 21989297
10-12 06:50:33.512   925  3623 I ActivityManager: Start proc 5792:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-12 06:50:33.531  3730  5776 I SystemUpdateService: showing system update notification
,10-12 06:50:33.542  5792  5792 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-12 06:50:33.549   925  3847 I ActivityManager: Killing 5322:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-12 06:50:33.611  3730  3730 D SystemUpdateService: onDestroy
,10-12 06:50:33.613   925  4805 I ActivityManager: Killing 4697:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-12 06:50:33.738  5733  5768 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-12 06:50:33.750   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a72e351:true
,10-12 06:50:37.959   925   935 D WifiService: setWifiEnabled: true pid=5659, uid=10077
,10-12 06:50:37.959   925   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 06:50:37.969   506   918 D SoftapController: Softap fwReload - Ok
,10-12 06:50:37.974   506   918 D CommandListener: Setting iface cfg
,10-12 06:50:37.974   506   918 D CommandListener: Trying to bring down wlan0
,10-12 06:50:37.976   506   918 D CommandListener: Clearing all IP addresses on wlan0
,10-12 06:50:37.981   925  2968 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 06:50:38.546   925  2968 D wifi    : set interface wlan0 flags (UP)
,10-12 06:50:38.549   925  2968 I WifiHAL : Initializing wifi
10-12 06:50:38.549   925  2968 I WifiHAL : Creating socket
10-12 06:50:38.550   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-12 06:50:38.555   925  2968 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-12 06:50:38.555   925  2968 D wifi    : Did set static halHandle = 0x7f6fc5ee00
10-12 06:50:38.555   925  2968 D wifi    : halHandle = 0x7f6fc5ee00, mVM = 0x7f8c28d140, mCls = 0x101982
,10-12 06:50:38.555   925  2968 D wifi    : array field set
10-12 06:50:38.555   925  2968 I WifiNative-HAL: interface[0] = wlan0
10-12 06:50:38.557   925  5809 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547336089088
10-12 06:50:38.557   925  5809 D wifi    : waitForHalEvents called, vm = 0x7f8c28d140, obj = 0x101982, env = 0x7f7272ee00
,10-12 06:50:38.626  5810  5810 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 06:50:38.638  5810  5810 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 06:50:38.658   925  2968 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 06:50:38.663  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:38.665  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:38.668  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:38.681  5810  5810 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-12 06:50:38.681  5810  5810 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 06:50:38.696   925  2968 D WifiConfigStore: Loading config and enabling all networks 
,10-12 06:50:38.698  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:38.698  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:38.698  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:38.698  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:38.699  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:38.699  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:38.700  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 06:50:38.700  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:38.701  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:38.701  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:38.701  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:38.701  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:38.709   925  2968 D WifiConfigStore: loaded 0 passpoint configs
10-12 06:50:38.709   925  2968 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-12 06:50:38.710   925  2968 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-12 06:50:38.710   925  2968 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-12 06:50:38.711   925  2968 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-12 06:50:38.711   925  2968 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 06:50:38.711   925  2968 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 06:50:38.711   925  2968 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-12 06:50:38.713   925  2968 D WifiNative-HAL: Setting external_sim to 1
10-12 06:50:38.714   925  2968 D wifi    : setting dfs flag to true, 0x7f72314720
,10-12 06:50:38.714  5041  5041 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 06:50:38.714   925  2968 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 06:50:38.714   925  2968 D wifi    : setting scan oui 0x7f72314720
10-12 06:50:38.714   925  2968 D WifiHAL : Sending mac address OUI
,10-12 06:50:38.718   925  2968 E native  : do suspend false
,10-12 06:50:38.731   925  2968 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-12 06:50:38.732   925   925 D RttService: SCAN_AVAILABLE : 3
10-12 06:50:38.732   506   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 06:50:38.732   925  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 06:50:38.733   506   918 D CommandListener: Setting iface cfg
,10-12 06:50:38.737   925  2966 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-12 06:50:38.738   925  2966 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-12 06:50:38.749   925  2966 D WifiNative-HAL: p2pGetDeviceAddress
,10-12 06:50:38.750   925  2966 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 06:50:38.757   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=266341 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,10-12 06:50:41.928  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:50:41.936  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:50:41.942  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:50:41.947  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:50:41.970   925  2968 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-12 06:50:41.971   925  2968 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-12 06:50:41.971   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 06:50:41.980   925  2968 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 06:50:42.014   925  2968 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 06:50:42.016  5810  5810 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 06:50:42.445  5810  5810 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 06:50:42.477  5810  5810 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 06:50:42.477  5810  5810 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 06:50:42.490   925  2968 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 06:50:42.490   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-12 06:50:42.490   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 06:50:42.507   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 06:50:42.517   506   918 D CommandListener: Setting iface cfg
,10-12 06:50:42.523   925  2968 D WifiStateMachine: Start Dhcp Watchdog 2
,10-12 06:50:42.531   925  5818 D DhcpClient: Receive thread started
,10-12 06:50:42.534   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-12 06:50:42.534   925  2968 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-12 06:50:42.534   925  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-12 06:50:42.616   925  2968 E native  : do suspend false
,10-12 06:50:42.629   925  5817 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 06:50:42.647   925  5818 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172572, domain null
,10-12 06:50:42.647   925  5817 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172572 seconds
,10-12 06:50:42.649   925  5817 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 06:50:42.677   925  5818 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-12 06:50:42.678   925  5817 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-12 06:50:42.680   506   918 D CommandListener: Setting iface cfg
10-12 06:50:42.686   925  2968 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 06:50:42.689   925  5817 D DhcpClient: Scheduling renewal in 86399s
,10-12 06:50:42.697   925  2968 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 06:50:42.698   925  2968 D WifiConfigStore: No blacklist allowed without epno enabled
,10-12 06:50:42.699   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-12 06:50:42.702   925  2968 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-12 06:50:42.702   925  2983 D ConnectivityService: Adding iface wlan0 to network 101
,10-12 06:50:42.754   925  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-12 06:50:42.754   925  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-12 06:50:42.756   925  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-12 06:50:42.758   925  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-12 06:50:42.761   925  2983 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-12 06:50:42.767   925  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-12 06:50:42.772   925  2983 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-12 06:50:42.772   925  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-12 06:50:42.772   925  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-12 06:50:42.772   925  2983 D ConnectivityService:    accepting network in place of null
10-12 06:50:42.772   925  2968 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-12 06:50:42.772   925  2968 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 06:50:42.773   925  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 06:50:42.797   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 06:50:42.818   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 06:50:42.821   925  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-12 06:50:42.821   925  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 06:50:42.821  3762  3930 W QCNEJ   : |CORE| network available: 101
,10-12 06:50:42.822   925  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-12 06:50:42.823   925   942 D Tethering: MasterInitialState.processMessage what=3
10-12 06:50:42.826  3762  3930 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-12 06:50:42.827  3762  3930 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-12 06:50:42.827  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:42.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:50:42.828  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:42.828  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 06:50:42.828  3762  3930 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-12 06:50:42.830  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:42.830  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:50:42.830  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:42.830  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:42.833  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:50:42.833  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:50:42.833  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:42.833  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:50:42.836  5067  5090 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-12 06:50:42.836  5067  5090 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 06:50:42.836  5067  5090 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-12 06:50:42.836  5067  5090 E SarControlService: no key has been found,reset the power
10-12 06:50:42.837  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 06:50:42.837  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 06:50:42.837  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 06:50:42.838   925  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=270422, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
10-12 06:50:42.838  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 06:50:42.838  5092  5092 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 06:50:42.838  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 06:50:42.839  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 06:50:42.839  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-12 06:50:42.840  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 06:50:42.840  5092  5092 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-12 06:50:42.841  4959  4959 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-12 06:50:42.843  3730  3730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 06:50:42.846  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000ec03000000000000ffffffff]
,10-12 06:50:42.846  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:50:42.846  5092  5106 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-12 06:50:42.847  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 06:50:42.847  5067  5077 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 06:50:42.847  3730  3730 D SystemUpdateService: onCreate
,10-12 06:50:42.853  3730  3730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 06:50:42.856  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000ed03000000000000ffffffff]
10-12 06:50:42.856  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:50:42.856  5092  5106 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,10-12 06:50:42.857  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 06:50:42.857  5067  5078 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-12 06:50:42.863  3730  3730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 06:50:42.871  3730  5430 I iu.UploadsManager: num queued entries: 0
,10-12 06:50:42.872  3730  5430 I iu.UploadsManager: num updated entries: 0
,10-12 06:50:42.872  3730  5430 I iu.SyncManager: NEXT; no task
,10-12 06:50:42.875  3730  3730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 06:50:42.876  3730  3730 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 06:50:42.878  5778  5778 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 06:50:42.882  5778  5778 D SprintDMHelper: simOperator: 
10-12 06:50:42.883  5778  5778 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-12 06:50:42.883  3730  5828 I SystemUpdateService: active receiver: enabled
,10-12 06:50:42.919  3730  5828 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 06:50:42.923   925  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-12 06:50:42.927  3730  5828 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-12 06:50:42.927  3730  5828 I SystemUpdateService: now status is 0 (complete)
10-12 06:50:42.927  3730  5828 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 06:50:42.927  3730  5828 I SystemUpdateService: file has been verified
10-12 06:50:42.927  3730  5828 I SystemUpdateService: OTA package size = 21989297
,10-12 06:50:42.933  3730  5828 I SystemUpdateService: showing system update notification
,10-12 06:50:42.946  3730  3730 D SystemUpdateService: onDestroy
,10-12 06:50:42.965   925  3224 D WifiService: setWifiEnabled: false pid=5659, uid=10077
,10-12 06:50:42.965   925  3224 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 06:50:42.967   925  2968 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-12 06:50:42.967   925  2968 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-12 06:50:42.967   925  2968 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-12 06:50:42.967   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 06:50:42.975   925  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 10:50:42 GMT], X-Android-Received-Millis=[1476269442974], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476269442949]}
,10-12 06:50:42.976   925  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-12 06:50:42.976   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-12 06:50:42.976   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-12 06:50:42.977   925  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 06:50:42.980   506   918 D CommandListener: Clearing all IP addresses on wlan0
,10-12 06:50:42.980   925  5817 D DhcpClient: Clearing IP address
10-12 06:50:42.982   506   918 D CommandListener: Setting iface cfg
,10-12 06:50:42.986   925  5818 D DhcpClient: Receive thread stopped
10-12 06:50:42.989  3591  5829 V NativeCrypto: Write error: ssl=0x7f71b5ef80: I/O error during system call, Broken pipe
,10-12 06:50:42.989  3591  5839 V NativeCrypto: Read error: ssl=0x7f71b5ef80: I/O error during system call, Connection timed out
10-12 06:50:42.989  3591  5829 V NativeCrypto: SSL shutdown failed: ssl=0x7f71b5ef80: I/O error during system call, Broken pipe
10-12 06:50:42.993   925   936 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
10-12 06:50:42.993   925  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-12 06:50:42.993   925  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-12 06:50:42.994  5041  5833 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-12 06:50:43.006   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-12 06:50:43.006   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-12 06:50:43.007   925  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.maybeThrowAfterRecvfrom(IoBridge.java:588)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:552)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:481)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Loope,r.java:148)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: recvfrom failed: ETIMEDOUT (Connection timed out)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfromBytes(Native Method)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.recvfrom(Posix.java:189)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.recvfrom(BlockGuardOs.java:250)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.recvfrom(IoBridge.java:549)
10-12 06:50:43.009  5041  5833 W Babel_NetworkConnectionCheckingService: 	... 21 more
10-12 06:50:43.009  5041  5833 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-12 06:50:43.011   925  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-12 06:50:43.012   546   546 E Parcel  : Reading a NULL string not supported here.
10-12 06:50:43.013  3762  3930 W QCNEJ   : |CORE| network lost: 101
,10-12 06:50:43.014   925   925 D RttService: SCAN_AVAILABLE : 1
10-12 06:50:43.014  3762  3930 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-12 06:50:43.014   925  3088 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-12 06:50:43.017   925  2968 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-12 06:50:43.020   925  2968 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 06:50:43.038   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 06:50:43.057   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-12 06:50:43.057   506   918 D CommandListener: Clearing all IP addresses on wlan0
,10-12 06:50:43.057   925  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-12 06:50:43.057   925  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-12 06:50:43.059   925   942 D Tethering: MasterInitialState.processMessage what=3
,10-12 06:50:43.061   925  2968 D DhcpClient: doQuit
10-12 06:50:43.061   925  2968 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-12 06:50:43.061   925  5817 D DhcpClient: onQuitting
10-12 06:50:43.062  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:43.062  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:43.062  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:43.062  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:43.062  5810  5810 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-12 06:50:43.063  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:43.063  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:43.063  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:43.063  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:43.065  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:43.065  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:43.065  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 06:50:43.065  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:43.068  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:43.068  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:43.068  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:43.068  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:43.069  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:43.070  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:43.070  4959  4959 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-12 06:50:43.073  3730  3730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-12 06:50:43.075  5067  5090 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-12 06:50:43.075  5067  5090 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 06:50:43.075  5067  5090 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-12 06:50:43.076  5067  5090 E SarControlService: no key has been found,reset the power
10-12 06:50:43.076  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 06:50:43.076  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 06:50:43.076  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 06:50:43.077  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 06:50:43.077  5092  5092 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-12 06:50:43.078  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 06:50:43.078  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 06:50:43.078  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 06:50:43.078  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 06:50:43.079  5092  5092 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-12 06:50:43.081  3730  3730 D SystemUpdateService: onCreate
10-12 06:50:43.083  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000ee03000000000000ffffffff]
,10-12 06:50:43.083  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:50:43.083  5092  5106 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-12 06:50:43.083  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 06:50:43.084  5067  5078 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-12 06:50:43.084  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000ef03000000000000ffffffff]
10-12 06:50:43.084  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:50:43.084  5092  5106 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-12 06:50:43.085  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-12 06:50:43.085  5067  5077 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 06:50:43.087  3730  3730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 06:50:43.090  3730  5848 I SystemUpdateService: active receiver: enabled
,10-12 06:50:43.093  5810  5810 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-12 06:50:43.096  3730  3730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-12 06:50:43.097  5810  5810 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-12 06:50:43.102  3730  5430 I iu.UploadsManager: num queued entries: 0
,10-12 06:50:43.102  3730  5430 I iu.UploadsManager: num updated entries: 0
10-12 06:50:43.103  3730  5430 I iu.SyncManager: NEXT; no task
,10-12 06:50:43.105  3730  3730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 06:50:43.107  3730  3730 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 06:50:43.109  5778  5778 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 06:50:43.113  5778  5778 D SprintDMHelper: simOperator: 
,10-12 06:50:43.113  5778  5778 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 06:50:43.116   506   918 E Netd    : netlink response contains error (No such file or directory)
,10-12 06:50:43.117   925  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-12 06:50:43.117   925  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-12 06:50:43.123  3730  5848 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 06:50:43.125  5041  5851 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-12 06:50:43.128  5810  5810 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-12 06:50:43.134  3730  5848 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-12 06:50:43.134  3730  5848 I SystemUpdateService: now status is 0 (complete)
10-12 06:50:43.134  3730  5848 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 06:50:43.134  3730  5848 I SystemUpdateService: file has been verified
10-12 06:50:43.134  3730  5848 I SystemUpdateService: OTA package size = 21989297
,10-12 06:50:43.142  3730  5848 I SystemUpdateService: showing system update notification
,10-12 06:50:43.143  5810  5810 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-12 06:50:43.152  3730  3730 D SystemUpdateService: onDestroy
,10-12 06:50:43.245   925  2968 D wifi    : In wifi stop Hal
,10-12 06:50:43.245   925  2968 D wifi    : halHandle = 0x7f6fc5ee00, mVM = 0x7f8c28d140, mCls = 0x101982
10-12 06:50:43.247   925  5809 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-12 06:50:43.247   925  5809 D WifiHAL : Got a signal to exit!!!
,10-12 06:50:43.248   925  5809 I WifiHAL : Exit wifi_event_loop
10-12 06:50:43.248   925  2968 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-12 06:50:43.249   925  2968 E WifiHAL : Event processing terminated
10-12 06:50:43.249   925  2968 D wifi    : In wifi cleaned up handler
10-12 06:50:43.249   925  2968 I WifiHAL : Internal cleanup completed
,10-12 06:50:43.249  4069  4234 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 06:50:43.252  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:43.253  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:43.254  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:43.254  5041  5041 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-12 06:50:43.271   925  5809 D wifi    : set interface wlan0 flags (DOWN)
,10-12 06:50:43.271   925  2968 D WifiNative-HAL: HAL event thread stopped successfully
,10-12 06:50:43.477   925   942 D Tethering: InitialState.processMessage what=4
,10-12 06:50:43.484   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-12 06:50:43.822   925  2983 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-12 06:50:45.912   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:46.913   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:47.914   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:48.006   925   942 I ActivityManager: Start proc 5855:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 06:50:48.102  5855  5855 D AdapterServiceConfig: Adding HeadsetService
,10-12 06:50:48.102  5855  5855 D AdapterServiceConfig: Adding A2dpService
10-12 06:50:48.102  5855  5855 D AdapterServiceConfig: Adding HidService
10-12 06:50:48.102  5855  5855 D AdapterServiceConfig: Adding HealthService
10-12 06:50:48.103  5855  5855 D AdapterServiceConfig: Adding PanService
10-12 06:50:48.103  5855  5855 D AdapterServiceConfig: Adding GattService
,10-12 06:50:48.103  5855  5855 D AdapterServiceConfig: Adding BluetoothMapService
10-12 06:50:48.103  5855  5855 D AdapterServiceConfig: Adding SapService
,10-12 06:50:48.116   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aa1d47c:true
,10-12 06:50:48.116  5855  5855 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 06:50:48.119  5855  5855 I bt_bluedroid: init
,10-12 06:50:48.119  5855  5867 I BluetoothAdapterState: Entering OffState
,10-12 06:50:48.121  5855  5868 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-12 06:50:48.121  5855  5868 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 06:50:48.121  5855  5868 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-12 06:50:48.121  5855  5868 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-12 06:50:48.122  5855  5855 I bt_bluedroid: get_profile_interface socket
,10-12 06:50:48.123  5855  5871 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 06:50:48.124  5855  5855 I bt_bluedroid: get_profile_interface sdp
10-12 06:50:48.125  5855  5871 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 06:50:48.129  5855  5866 I bt_bluedroid: config_hci_snoop_log
,10-12 06:50:48.130   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-12 06:50:48.133  5855  5867 D BluetoothAdapterState: Current state: OFF, message: 0
10-12 06:50:48.133  5855  5867 D BluetoothAdapterProperties: Setting state to 14
10-12 06:50:48.134  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-12 06:50:48.135  5855  5867 D BluetoothBondStateMachine: make
,10-12 06:50:48.137  5855  5872 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 06:50:48.140  5855  5867 I BluetoothAdapterState: Entering PendingCommandState
,10-12 06:50:48.141  5855  5855 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 06:50:48.143  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.144  5855  5855 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 06:50:48.145  5855  5855 D BtGatt.GattService: Received start request. Starting profile...
,10-12 06:50:48.145  5855  5855 D BtGatt.GattService: start()
10-12 06:50:48.145  5855  5855 I bt_bluedroid: get_profile_interface gatt
,10-12 06:50:48.146  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.146  5855  5855 D BtGatt.AdvertiseManager: advertise manager created
,10-12 06:50:48.152  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:48.152  5855  5855 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:48.152  5855  5855 V BluetoothAdapterState: isBleTurningOn()=true
10-12 06:50:48.152  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:48.152  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-12 06:50:48.153  5855  5867 I bt_bluedroid: bt_bluedroid
,10-12 06:50:48.153  5855  5868 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-12 06:50:48.153  5855  5868 I bt_hci  : start_up
,10-12 06:50:48.158  5855  5868 I bt_vendor: alloc value 0xf41cd871
,10-12 06:50:48.158  5855  5868 I bt_vendor: init
10-12 06:50:48.159  5855  5868 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 06:50:48.159  5855  5868 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 06:50:48.267  5855  5868 D bt_hci  : start_up starting async portion
10-12 06:50:48.267  5855  5875 I bt_hci  : event_finish_startup
,10-12 06:50:48.268  5876  5876 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-12 06:50:48.267  5855  5875 I bt_hci_h4: hal_open
10-12 06:50:48.267  5855  5875 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-12 06:50:48.270  5855  5875 I bt_userial_vendor: device fd = 54 open
,10-12 06:50:48.283  5855  5875 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 06:50:48.286  5855  5875 D bt_hwcfg: Chipset BCM4358A3
,10-12 06:50:48.286  5855  5875 D bt_hwcfg: Target name = [BCM4358A3]
10-12 06:50:48.287  5855  5875 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 06:50:48.668  5855  5875 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-12 06:50:48.669  5855  5875 D bt_hwcfg: Settlement delay -- 100 ms
10-12 06:50:48.669  5855  5875 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 06:50:48.803  5855  5875 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 06:50:48.803  5855  5875 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-12 06:50:48.804  5855  5875 I bt_hwcfg: vendor lib fwcfg completed
10-12 06:50:48.805  5855  5875 I bt_vendor: firmware callback
,10-12 06:50:48.805  5855  5875 I bt_hci  : firmware_config_callback
,10-12 06:50:48.813  5855  5878 I bt_btu  : btu_task pending for preload complete event
,10-12 06:50:48.813  5855  5878 I bt_btu_task: Bluetooth chip preload is complete
10-12 06:50:48.813  5855  5878 I bt_btu  : btu_task received preload complete event
,10-12 06:50:48.820  5855  5878 I         : BTE_InitTraceLevels -- TRC_HCI
,10-12 06:50:48.820  5855  5878 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-12 06:50:48.820  5855  5878 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-12 06:50:48.820  5855  5878 I         : BTE_InitTraceLevels -- TRC_AVDT
10-12 06:50:48.820  5855  5878 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-12 06:50:48.820  5855  5878 I         : BTE_InitTraceLevels -- TRC_A2D
10-12 06:50:48.820  5855  5878 I         : BTE_InitTraceLevels -- TRC_BNEP
10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_BTM
10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_GAP
10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_PAN
,10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_SDP
10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_GATT
10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_SMP
10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-12 06:50:48.821  5855  5878 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 06:50:48.900  5855  5878 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf414b549
,10-12 06:50:48.901  5855  5878 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf414b549 
,10-12 06:50:48.913  5855  5871 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 06:50:48.914  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 06:50:48.914   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:48.915  5855  5871 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 06:50:48.917  5855  5871 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 06:50:48.919  5855  5871 D BluetoothAdapterProperties: Scan Mode:20
10-12 06:50:48.920  5855  5871 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 06:50:48.920  5855  5871 D bt_hci  : do_postload posting postload work item
10-12 06:50:48.920  5855  5875 I bt_hci  : event_postload
10-12 06:50:48.920  5855  5875 I bt_vendor: sco_config_cb
10-12 06:50:48.920  5855  5875 I bt_hci  : sco_config_callback postload finished.
10-12 06:50:48.924  5855  5871 D bt_bte_conf: Device ID record 1 : primary
10-12 06:50:48.925  5855  5871 D bt_bte_conf:   vendorId            = 000f
,10-12 06:50:48.925  5855  5871 D bt_bte_conf:   vendorIdSource      = 0001
10-12 06:50:48.925  5855  5871 D bt_bte_conf:   product             = 1200
10-12 06:50:48.925  5855  5871 D bt_bte_conf:   version             = 1436
10-12 06:50:48.925  5855  5871 D bt_bte_conf:   clientExecutableURL = 
10-12 06:50:48.925  5855  5871 D bt_bte_conf:   serviceDescription  = 
10-12 06:50:48.925  5855  5871 D bt_bte_conf:   documentationURL    = 
10-12 06:50:48.925  5855  5871 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-12 06:50:48.925  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:48.926  5855  5868 D bt_stack_manager: event_start_up_stack finished
10-12 06:50:48.927  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-12 06:50:48.927  5855  5867 D BluetoothAdapterProperties: Setting state to 15
10-12 06:50:48.927  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-12 06:50:48.928  5855  5875 I bt_vendor: low_power_mode_cb
10-12 06:50:48.929  5855  5867 I BluetoothAdapterState: Entering BleOnState
,10-12 06:50:48.929  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:48.934  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:48.936  5855  5867 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-12 06:50:48.936  5855  5867 D BluetoothAdapterProperties: Setting state to 11
10-12 06:50:48.937  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-12 06:50:48.940  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.942  5855  5855 D HeadsetService: Received start request. Starting profile...
,10-12 06:50:48.943  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:48.945  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:48.945  5855  5855 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 06:50:48.945  5855  5855 D HeadsetStateMachine: make
,10-12 06:50:48.947  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:48.954  5855  5855 D HeadsetStateMachine: max_hf_connections = 1
10-12 06:50:48.954  5855  5855 I bt_bluedroid: get_profile_interface handsfree
10-12 06:50:48.954  5855  5867 I BluetoothAdapterState: Entering PendingCommandState
,10-12 06:50:48.954  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-12 06:50:48.955  5855  5871 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-12 06:50:48.957  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.958  5855  5855 D A2dpService: Received start request. Starting profile...
,10-12 06:50:48.959  5855  5855 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-12 06:50:48.960  5855  5855 I bt_bluedroid: get_profile_interface avrcp
,10-12 06:50:48.965  5855  5855 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-12 06:50:48.965  5855  5855 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 06:50:48.965  5855  5855 D A2dpStateMachine: make
,10-12 06:50:48.966  5855  5855 I bt_bluedroid: get_profile_interface a2dp
,10-12 06:50:48.967  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-12 06:50:48.968  5855  5886 D A2dpStateMachine: Enter Disconnected: -2
,10-12 06:50:48.969  5855  5855 I BluetoothHidServiceJni: classInitNative: succeeds
10-12 06:50:48.970  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
10-12 06:50:48.970  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 06:50:48.972  5713  5713 D BluetoothInputDevice: Proxy object connected
,10-12 06:50:48.972  5855  5855 D HidService: Received start request. Starting profile...
10-12 06:50:48.973  5855  5855 I bt_bluedroid: get_profile_interface hidhost
10-12 06:50:48.973  5855  5855 D HidService: setHidService(): set to: null
10-12 06:50:48.973  5855  5871 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf412c56d
10-12 06:50:48.973  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-12 06:50:48.973  5713  5713 D HidProfile: Bluetooth service connected
10-12 06:50:48.973  5855  5855 I BluetoothHealthServiceJni: classInitNative: succeeds
10-12 06:50:48.974  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.974  5855  5855 D HealthService: Received start request. Starting profile...
,10-12 06:50:48.976  5855  5855 I bt_bluedroid: get_profile_interface health
,10-12 06:50:48.976  5855  5855 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-12 06:50:48.977  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.978  5713  5713 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 06:50:48.978  5855  5855 D PanService: Received start request. Starting profile...
10-12 06:50:48.979  5855  5855 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 06:50:48.979  5855  5855 I bt_bluedroid: get_profile_interface pan
10-12 06:50:48.979  5713  5713 D PanProfile: Bluetooth service connected
10-12 06:50:48.979  5855  5871 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-12 06:50:48.982  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.983  5713  5713 D BluetoothMap: Proxy object connected
,10-12 06:50:48.984  5713  5713 D MapProfile: Bluetooth service connected
10-12 06:50:48.984  5713  5713 D BluetoothMap: getConnectedDevices()
10-12 06:50:48.984  5855  5855 D BluetoothMapService: Received start request. Starting profile...
10-12 06:50:48.984  5855  5855 D BluetoothMapService: start()
10-12 06:50:48.987  5855  5855 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-12 06:50:48.987  5855  5855 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-12 06:50:48.988  5855  5855 D BluetoothMapAppObserver: createReceiver()
10-12 06:50:48.989  5855  5855 D BluetoothMapAppObserver: initObservers()
,10-12 06:50:48.989  5855  5855 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-12 06:50:48.995  5713  5713 D BluetoothMap: Bluetooth is Not enabled
,10-12 06:50:48.995  5855  5855 V SapService: SapBinder()
10-12 06:50:48.995  5855  5855 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:50:48.996  5855  5855 D SapService: Received start request. Starting profile...
10-12 06:50:48.996  5855  5855 V SapService: start()
,10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isTurningOff()=false
,10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isTurningOn()=true
,10-12 06:50:48.998  5855  5884 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isTurningOn()=true
10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:48.998  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:48.999  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:48.999  5855  5855 V BluetoothAdapterState: isTurningOn()=true
10-12 06:50:48.999  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:48.999  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:48.999  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:48.999  5855  5855 V BluetoothAdapterState: isTurningOn()=true
,10-12 06:50:48.999  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isTurningOn()=true
10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isTurningOn()=true
10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 06:50:49.000  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:49.001  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:49.001  5855  5855 V BluetoothAdapterState: isTurningOn()=true
10-12 06:50:49.001  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:49.001  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:49.002  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-12 06:50:49.002  5855  5867 D BluetoothAdapterProperties: ScanMode =  20
10-12 06:50:49.002  5855  5867 D BluetoothAdapterProperties: State =  11
10-12 06:50:49.003  5855  5871 D BluetoothAdapterProperties: Scan Mode:21
10-12 06:50:49.003  5855  5867 D BluetoothAdapterProperties: Setting state to 12
10-12 06:50:49.003  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-12 06:50:49.003  5855  5871 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-12 06:50:49.004  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 06:50:49.004   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:50:49.004  5855  5867 I BluetoothAdapterState: Entering OnState
10-12 06:50:49.004  3161  3172 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-12 06:50:49.006   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:50:49.006  3161  3161 D BluetoothInputDevice: Proxy object connected
10-12 06:50:49.006  3161  3161 D HidProfile: Bluetooth service connected
10-12 06:50:49.007  3161  3985 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:50:49.007  3793  3825 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:49.008  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:49.008  5713  5724 D BluetoothMap: onBluetoothStateChange: up=true
10-12 06:50:49.008  3161  3174 D BluetoothMap: onBluetoothStateChange: up=true
10-12 06:50:49.010  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:49.012  3161  3161 D BluetoothMap: Proxy object connected
10-12 06:50:49.012  5713  5723 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 06:50:49.012  3161  3161 D MapProfile: Bluetooth service connected
10-12 06:50:49.012  3161  3161 D BluetoothMap: getConnectedDevices()
,10-12 06:50:49.012  3161  3985 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 06:50:49.014  3161  3174 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:49.014  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 06:50:49.014  5855  5855 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 06:50:49.015  5855  5855 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-12 06:50:49.015  3161  3172 D BluetoothPan: onBluetoothStateChange on: true
10-12 06:50:49.016  5855  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 06:50:49.016  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:49.017  3161  3161 D BluetoothPan: BluetoothPAN Proxy object connected
,10-12 06:50:49.017  3161  3161 D PanProfile: Bluetooth service connected
10-12 06:50:49.017  5713  5724 D BluetoothPan: onBluetoothStateChange on: true
10-12 06:50:49.018   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:50:49.018  5855  5855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 06:50:49.018   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-12 06:50:49.018  5713  5723 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:49.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:49.019  5855  5855 D ObexServerSockets: Succeed to create listening sockets 
10-12 06:50:49.019  5855  5855 D ObexServerSockets0: startAccept()
10-12 06:50:49.019  5855  5855 D ObexServerSockets0: prepareForNewConnect()
10-12 06:50:49.020   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
10-12 06:50:49.021  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:49.021  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 06:50:49.023  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:49.023  5855  5855 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-12 06:50:49.023  5855  5855 D BluetoothSdpJni: SDP Create record success - handle: 0
10-12 06:50:49.023  5855  5893 D ObexServerSockets0: Accepting socket connection...
10-12 06:50:49.024  5855  5894 D ObexServerSockets0: Accepting socket connection...
10-12 06:50:49.024   925   925 D BluetoothA2dp: Proxy object connected
,10-12 06:50:49.024  5855  5855 D BluetoothMapService: onReceive
10-12 06:50:49.024  5855  5855 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 06:50:49.024  5855  5855 D BluetoothMapService: STATE_ON
10-12 06:50:49.024  3161  3161 D BluetoothA2dp: Proxy object connected
10-12 06:50:49.024  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:49.026  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:49.026  5855  5895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 06:50:49.027  5855  5895 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 06:50:49.027  5855  5895 D BluetoothSdpJni: SDP Create record success - handle: 1
10-12 06:50:49.028  5713  5713 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-12 06:50:49.032  5713  5713 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-12 06:50:49.038  5713  5713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 06:50:49.039  5713  5713 D BluetoothA2dp: Proxy object connected
,10-12 06:50:49.043  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 06:50:49.048  5713  5713 D DockEventReceiver: finishStartingService: stopping service
,10-12 06:50:49.053  5855  5855 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 06:50:49.053  5855  5855 D ObexServerSockets0: prepareForNewConnect()
,10-12 06:50:49.053  5713  5713 D BluetoothPbap: Proxy object connected
10-12 06:50:49.053  5713  5713 D PbapServerProfile: Bluetooth service connected
,10-12 06:50:49.056  3161  3161 D BluetoothPbap: Proxy object connected
10-12 06:50:49.056  3161  3161 D PbapServerProfile: Bluetooth service connected
,10-12 06:50:49.060  5855  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 06:50:49.072  5855  5903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 06:50:49.073  5855  5903 I BtOppRfcommListener: Accept thread started.
,10-12 06:50:49.106   925   925 D BluetoothHeadset: Proxy object connected
,10-12 06:50:49.106   925   925 D BluetoothHeadset: Proxy object connected
10-12 06:50:49.106   925   925 D BluetoothHeadset: Proxy object connected
10-12 06:50:49.106   925   942 D BluetoothHeadset: Proxy object connected
10-12 06:50:49.106  3793  3827 D BluetoothHeadset: Proxy object connected
,10-12 06:50:49.107  3161  3985 D BluetoothHeadset: Proxy object connected
,10-12 06:50:49.107  3161  3161 D HeadsetProfile: Bluetooth service connected
10-12 06:50:49.108  3161  3174 D BluetoothHeadset: Proxy object connected
10-12 06:50:49.108  3793  4009 D BluetoothHeadset: Proxy object connected
,10-12 06:50:49.109  3161  3161 D HeadsetProfile: Bluetooth service connected
,10-12 06:50:49.118   925   942 D BluetoothHeadset: Proxy object connected
,10-12 06:50:49.134  5713  5724 D BluetoothHeadset: Proxy object connected
,10-12 06:50:49.135  5713  5713 D HeadsetProfile: Bluetooth service connected
,10-12 06:50:49.915   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:50:50.779   925  2983 D ConnectivityService: handlePromptUnvalidated 101
,10-12 06:50:50.916   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-12 06:50:52.979  5855  5867 D BluetoothAdapterState: Current state: ON, message: 23
10-12 06:50:52.979  5855  5867 D BluetoothAdapterProperties: Setting state to 13
,10-12 06:50:52.979  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-12 06:50:52.980  5855  5867 D BluetoothAdapterProperties: onBluetoothDisable()
,10-12 06:50:52.982  5855  5867 I BluetoothAdapterState: Entering PendingCommandState
,10-12 06:50:52.986  5855  5855 D BluetoothMapService: onReceive
,10-12 06:50:52.986  5855  5855 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-12 06:50:52.986  5855  5855 D BluetoothMapService: STATE_TURNING_OFF
10-12 06:50:52.987  5855  5855 D BluetoothMapService: MAP Service closeService in
10-12 06:50:52.987  5855  5855 D BluetoothMapMasInstance0: MAP Service shutdown
10-12 06:50:52.987  5855  5855 D ObexServerSockets0: shutdown(block = true)
10-12 06:50:52.989  5855  5855 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 06:50:52.989  5855  5855 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-12 06:50:52.989  5855  5880 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-12 06:50:52.990  5855  5894 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-12 06:50:52.990  5855  5893 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-12 06:50:52.990  5855  5871 D BluetoothAdapterProperties: Scan Mode:20
10-12 06:50:52.991  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-12 06:50:52.993  5713  5713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 06:50:52.994  5855  5855 I BtOppRfcommListener: stopping Accept Thread
10-12 06:50:52.995  5855  5903 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-12 06:50:52.995  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:52.995  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:52.997  5855  5903 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-12 06:50:52.999  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:52.999  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:53.001  5855  5855 D HeadsetService: Received stop request...Stopping profile...
,10-12 06:50:53.003  5713  5723 D BluetoothHeadset: Proxy object disconnected
,10-12 06:50:53.003   925   925 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:53.003   925   925 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:53.004   925   925 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:53.006  3793  3825 D BluetoothHeadset: Proxy object disconnected
10-12 06:50:53.007  5855  5855 D A2dpService: Received stop request...Stopping profile...
10-12 06:50:53.007  3161  3172 D BluetoothHeadset: Proxy object disconnected
,10-12 06:50:53.007  5855  5886 D A2dpStateMachine: Exit Disconnected: -1
10-12 06:50:53.009  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:53.009  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:50:53.011  5855  5855 D HidService: Received stop request...Stopping profile...
,10-12 06:50:53.011  5855  5855 D HidService: Stopping Bluetooth HidService
10-12 06:50:53.011   925   925 D BluetoothA2dp: Proxy object disconnected
10-12 06:50:53.014  5713  5713 D DockEventReceiver: finishStartingService: stopping service
,10-12 06:50:53.015  5855  5855 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:53.015  5855  5855 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:53.015  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:53.015  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:53.015  5713  5713 D HeadsetProfile: Bluetooth service disconnected
10-12 06:50:53.016  5713  5713 D BluetoothA2dp: Proxy object disconnected
10-12 06:50:53.016  5713  5713 D BluetoothInputDevice: Proxy object disconnected
10-12 06:50:53.016  5713  5713 D HidProfile: Bluetooth service disconnected
10-12 06:50:53.016  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:53.016  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:50:53.017  3161  3161 D HeadsetProfile: Bluetooth service disconnected
10-12 06:50:53.017  3161  3161 D BluetoothA2dp: Proxy object disconnected
10-12 06:50:53.017  3161  3161 D BluetoothInputDevice: Proxy object disconnected
10-12 06:50:53.017  3161  3161 D HidProfile: Bluetooth service disconnected
10-12 06:50:53.019  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:50:53.019  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 06:50:53.020  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-12 06:50:53.020  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:50:53.022  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:53.023  5855  5855 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-12 06:50:53.023  5855  5855 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-12 06:50:53.023  5855  5878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:53.023  5855  5878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:53.023  5855  5878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:53.024  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-12 06:50:53.024  5855  5871 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-12 06:50:53.024  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:53.025  5855  5855 D HealthService: Received stop request...Stopping profile...
10-12 06:50:53.026  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-12 06:50:53.027  5855  5855 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:53.027  5855  5855 V BluetoothAdapterState: isTurningOn()=false
,10-12 06:50:53.027  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:53.027  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 06:50:53.028  5855  5855 D PanService: Received stop request...Stopping profile...
,10-12 06:50:53.030  3161  3161 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 06:50:53.030  3161  3161 D PanProfile: Bluetooth service disconnected
10-12 06:50:53.030  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:53.031  5713  5713 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-12 06:50:53.031  5713  5713 D PanProfile: Bluetooth service disconnected
,10-12 06:50:53.033  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-12 06:50:53.033  5855  5878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:53.033  5855  5878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:53.033  5855  5878 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 06:50:53.033  5855  5878 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-12 06:50:53.033  5855  5878 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-12 06:50:53.033  5855  5878 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-12 06:50:53.033  5855  5855 D BluetoothMapService: Received stop request...Stopping profile...
10-12 06:50:53.034  5855  5855 D BluetoothMapService: stop()
,10-12 06:50:53.034  5855  5855 D BluetoothMapAppObserver: deinitObservers()
,10-12 06:50:53.034  5855  5855 D BluetoothMapAppObserver: removeReceiver()
10-12 06:50:53.035  3161  3161 D BluetoothMap: Proxy object disconnected
10-12 06:50:53.035  3161  3161 D MapProfile: Bluetooth service disconnected
10-12 06:50:53.036  5855  5855 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:53.036  5855  5855 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:53.036  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:53.036  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:53.036  5855  5855 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-12 06:50:53.037  5855  5855 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,10-12 06:50:53.037  5855  5871 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 06:50:53.037  5855  5855 D SapService: Received stop request...Stopping profile...
10-12 06:50:53.037  5855  5855 V SapService: stop()
10-12 06:50:53.040  3161  3161 D BluetoothPbap: Proxy object disconnected
10-12 06:50:53.040  5713  5713 D BluetoothMap: Proxy object disconnected
10-12 06:50:53.040  3161  3161 D PbapServerProfile: Bluetooth service disconnected
10-12 06:50:53.040  5713  5713 D MapProfile: Bluetooth service disconnected
10-12 06:50:53.040  5855  5855 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:53.040  5855  5855 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:53.040  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:53.040  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:53.040  5713  5713 D BluetoothPbap: Proxy object disconnected
10-12 06:50:53.040  5713  5713 D PbapServerProfile: Bluetooth service disconnected
10-12 06:50:53.040  5855  5855 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,10-12 06:50:53.041  5855  5871 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-12 06:50:53.041  5855  5855 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-12 06:50:53.041  5855  5855 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:53.042  5855  5855 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:53.042  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:53.042  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:53.042  5855  5855 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-12 06:50:53.042  5855  5855 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-12 06:50:53.043  5855  5855 D BluetoothMapService: MAP Service closeService in
10-12 06:50:53.043  5855  5855 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:53.043  5855  5855 V BluetoothAdapterState: isTurningOn()=false
,10-12 06:50:53.043  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:53.043  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:50:53.044  5855  5855 D BluetoothMapService: cleanup()
10-12 06:50:53.044  5855  5855 D BluetoothMapService: MAP Service closeService in
10-12 06:50:53.044  5855  5855 V BluetoothAdapterState: isTurningOff()=true
10-12 06:50:53.044  5855  5855 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:53.044  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
,10-12 06:50:53.044  5855  5855 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 06:50:53.045  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,10-12 06:50:53.045  5855  5867 D BluetoothAdapterProperties: Setting state to 15
10-12 06:50:53.055  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-12 06:50:53.055  5855  5867 I BluetoothAdapterState: Entering BleOnState
,10-12 06:50:53.056  5713  5724 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-12 06:50:53.058   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:53.058  3161  3172 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 06:50:53.059   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:53.059  5713  5723 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 06:50:53.060  3161  3985 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:53.060  3793  3827 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:53.060  5713  5724 D BluetoothMap: onBluetoothStateChange: up=false
10-12 06:50:53.061  3161  3174 D BluetoothMap: onBluetoothStateChange: up=false
10-12 06:50:53.061  5713  5723 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-12 06:50:53.062  3161  3172 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 06:50:53.062  3161  3985 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 06:50:53.063  3161  3174 D BluetoothPan: onBluetoothStateChange on: false
10-12 06:50:53.063  5713  5724 D BluetoothPan: onBluetoothStateChange on: false
10-12 06:50:53.064   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
10-12 06:50:53.064   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
10-12 06:50:53.064  5713  5723 D BluetoothPbap: onBluetoothStateChange: up=false
10-12 06:50:53.064  5855  5867 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-12 06:50:53.065  5855  5867 D BluetoothAdapterProperties: Setting state to 16
,10-12 06:50:53.065  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-12 06:50:53.065  5855  5867 D BluetoothAdapterProperties: onBleDisable
10-12 06:50:53.065  5855  5867 I BluetoothAdapterState: Entering PendingCommandState
10-12 06:50:53.066  5855  5868 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-12 06:50:53.066  5855  5878 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-12 06:50:53.067  5855  5878 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-12 06:50:53.067  5855  5871 D BluetoothAdapterProperties: Scan Mode:20
10-12 06:50:53.068  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:53.068  5713  5713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-12 06:50:53.069  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:53.070  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:53.071  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:50:53.073  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:53.074  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:50:53.077  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 06:50:53.077  5713  5713 D DockEventReceiver: finishStartingService: stopping service
,10-12 06:50:53.283  5855  5871 I bt_hci  : shut_down
,10-12 06:50:53.293  5855  5875 D bt_hwcfg: hw_epilog_process
,10-12 06:50:53.294  5855  5875 I bt_vendor: low_power_mode_cb
,10-12 06:50:53.297  5855  5875 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-12 06:50:53.297  5855  5875 I bt_vendor: epilog_cb
,10-12 06:50:53.297  5855  5875 I bt_hci  : epilog_finished_callback
,10-12 06:50:53.302  5855  5871 I bt_hci_h4: hal_close
10-12 06:50:53.303  5855  5871 I bt_userial_vendor: device fd = 54 close
,10-12 06:50:53.416  5855  5868 D bt_stack_manager: event_shut_down_stack finished.
,10-12 06:50:53.417  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-12 06:50:53.421  5855  5867 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-12 06:50:53.422  5855  5855 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-12 06:50:53.423  5855  5855 D BtGatt.GattService: Received stop request...Stopping profile...
10-12 06:50:53.423  5855  5855 D BtGatt.GattService: stop()
10-12 06:50:53.424  5855  5855 D BtGatt.AdvertiseManager: advertise clients cleared
,10-12 06:50:53.426  5855  5855 V BluetoothAdapterState: isTurningOff()=false
10-12 06:50:53.427  5855  5855 V BluetoothAdapterState: isTurningOn()=false
10-12 06:50:53.427  5855  5855 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:50:53.427  5855  5855 V BluetoothAdapterState: isBleTurningOff()=true
,10-12 06:50:53.427  5855  5867 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-12 06:50:53.428  5855  5867 D BluetoothAdapterProperties: Setting state to 10
10-12 06:50:53.428  5855  5867 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,10-12 06:50:53.429  5855  5867 I BluetoothAdapterState: Entering OffState
,10-12 06:50:53.430   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-12 06:50:53.444  5855  5855 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-12 06:50:53.444  5855  5855 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-12 06:50:53.445  5855  5855 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-12 06:50:53.447  5855  5868 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-12 06:50:53.452  5855  5855 I art     : System.exit called, status: 0
10-12 06:50:53.452  5855  5855 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-12 06:50:53.478   925  3217 I ActivityManager: Process com.android.bluetooth (pid 5855) has died
,10-12 06:50:57.976  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 06:50:57.976  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:57.981  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:57.981  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3bf49b7 removed from the list
,10-12 06:50:57.981  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 06:50:57.983  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:50:57.983  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:50:57.985  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 06:50:57.985  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@377688d added. We now have 4 listener(s)
10-12 06:50:57.986  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:50:57.987  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:50:57.987  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@377688d removed from the list
10-12 06:50:57.987  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 06:50:57.987  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:50:57.988  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:50:57.990  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:50:57.990  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c0aa42 added. We now have 4 listener(s)
10-12 06:50:57.990  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:51:03.001  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:51:03.037   925   942 I ActivityManager: Start proc 5911:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-12 06:51:03.148  5911  5911 D AdapterServiceConfig: Adding HeadsetService
,10-12 06:51:03.149  5911  5911 D AdapterServiceConfig: Adding A2dpService
10-12 06:51:03.149  5911  5911 D AdapterServiceConfig: Adding HidService
10-12 06:51:03.149  5911  5911 D AdapterServiceConfig: Adding HealthService
10-12 06:51:03.149  5911  5911 D AdapterServiceConfig: Adding PanService
10-12 06:51:03.149  5911  5911 D AdapterServiceConfig: Adding GattService
10-12 06:51:03.150  5911  5911 D AdapterServiceConfig: Adding BluetoothMapService
10-12 06:51:03.150  5911  5911 D AdapterServiceConfig: Adding SapService
,10-12 06:51:03.163   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41e2ac5:true
,10-12 06:51:03.164  5911  5911 D BluetoothAdapterState: make() - Creating AdapterState
,10-12 06:51:03.167  5911  5911 I bt_bluedroid: init
10-12 06:51:03.167  5911  5923 I BluetoothAdapterState: Entering OffState
,10-12 06:51:03.170  5911  5924 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-12 06:51:03.170  5911  5924 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-12 06:51:03.170  5911  5924 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-12 06:51:03.171  5911  5924 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-12 06:51:03.171  5911  5911 I bt_bluedroid: get_profile_interface socket
,10-12 06:51:03.174  5911  5927 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-12 06:51:03.174  5911  5911 I bt_bluedroid: get_profile_interface sdp
,10-12 06:51:03.177  5911  5927 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 06:51:03.182  5911  5922 I bt_bluedroid: config_hci_snoop_log
,10-12 06:51:03.183   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-12 06:51:03.188  5911  5923 D BluetoothAdapterState: Current state: OFF, message: 0
,10-12 06:51:03.188  5911  5923 D BluetoothAdapterProperties: Setting state to 14
10-12 06:51:03.188  5911  5923 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-12 06:51:03.190  5911  5923 D BluetoothBondStateMachine: make
,10-12 06:51:03.191  5911  5928 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-12 06:51:03.194  5911  5923 I BluetoothAdapterState: Entering PendingCommandState
,10-12 06:51:03.195  5911  5911 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-12 06:51:03.198  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
10-12 06:51:03.198  5911  5911 D BtGatt.DebugUtils: handleDebugAction() action=null
10-12 06:51:03.199  5911  5911 D BtGatt.GattService: Received start request. Starting profile...
10-12 06:51:03.199  5911  5911 D BtGatt.GattService: start()
10-12 06:51:03.199  5911  5911 I bt_bluedroid: get_profile_interface gatt
,10-12 06:51:03.200  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:03.201  5911  5911 D BtGatt.AdvertiseManager: advertise manager created
,10-12 06:51:03.206  5911  5911 V BluetoothAdapterState: isTurningOff()=false
10-12 06:51:03.206  5911  5911 V BluetoothAdapterState: isTurningOn()=false
10-12 06:51:03.206  5911  5911 V BluetoothAdapterState: isBleTurningOn()=true
,10-12 06:51:03.206  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:51:03.206  5911  5923 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-12 06:51:03.208  5911  5923 I bt_bluedroid: bt_bluedroid
,10-12 06:51:03.208  5911  5924 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-12 06:51:03.208  5911  5924 I bt_hci  : start_up
,10-12 06:51:03.214  5911  5924 I bt_vendor: alloc value 0xf41cd871
,10-12 06:51:03.214  5911  5924 I bt_vendor: init
10-12 06:51:03.214  5911  5924 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-12 06:51:03.214  5911  5924 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-12 06:51:03.322  5911  5924 D bt_hci  : start_up starting async portion
,10-12 06:51:03.323  5911  5931 I bt_hci  : event_finish_startup
10-12 06:51:03.324  5911  5931 I bt_hci_h4: hal_open
10-12 06:51:03.324  5911  5931 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-12 06:51:03.324  5932  5932 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-12 06:51:03.327  5911  5931 I bt_userial_vendor: device fd = 54 open
,10-12 06:51:03.344  5911  5931 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-12 06:51:03.348  5911  5931 D bt_hwcfg: Chipset BCM4358A3
10-12 06:51:03.349  5911  5931 D bt_hwcfg: Target name = [BCM4358A3]
,10-12 06:51:03.349  5911  5931 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-12 06:51:03.864  5911  5931 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-12 06:51:03.864  5911  5931 D bt_hwcfg: Settlement delay -- 100 ms
10-12 06:51:03.865  5911  5931 I bt_hwcfg: Setting fw settlement delay to 100 
,10-12 06:51:03.999  5911  5931 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-12 06:51:04.000  5911  5931 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-12 06:51:04.002  5911  5931 I bt_hwcfg: vendor lib fwcfg completed
10-12 06:51:04.002  5911  5931 I bt_vendor: firmware callback
10-12 06:51:04.002  5911  5931 I bt_hci  : firmware_config_callback
,10-12 06:51:04.010  5911  5934 I bt_btu  : btu_task pending for preload complete event
10-12 06:51:04.010  5911  5934 I bt_btu_task: Bluetooth chip preload is complete
,10-12 06:51:04.010  5911  5934 I bt_btu  : btu_task received preload complete event
,10-12 06:51:04.019  5911  5934 I         : BTE_InitTraceLevels -- TRC_HCI
10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_AVDT
10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_AVRC
10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_A2D
10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_BNEP
10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_BTM
,10-12 06:51:04.020  5911  5934 I         : BTE_InitTraceLevels -- TRC_GAP
10-12 06:51:04.021  5911  5934 I         : BTE_InitTraceLevels -- TRC_PAN
10-12 06:51:04.021  5911  5934 I         : BTE_InitTraceLevels -- TRC_SDP
10-12 06:51:04.021  5911  5934 I         : BTE_InitTraceLevels -- TRC_GATT
10-12 06:51:04.021  5911  5934 I         : BTE_InitTraceLevels -- TRC_SMP
,10-12 06:51:04.021  5911  5934 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-12 06:51:04.021  5911  5934 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-12 06:51:04.119  5911  5934 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf414b549
,10-12 06:51:04.119  5911  5934 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf414b549 
,10-12 06:51:04.151  5911  5927 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-12 06:51:04.154  5911  5927 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-12 06:51:04.154  5911  5927 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-12 06:51:04.157  5911  5927 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-12 06:51:04.161  5911  5927 D BluetoothAdapterProperties: Scan Mode:20
,10-12 06:51:04.162  5911  5927 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 06:51:04.162  5911  5927 D bt_hci  : do_postload posting postload work item
10-12 06:51:04.162  5911  5931 I bt_hci  : event_postload
,10-12 06:51:04.162  5911  5931 I bt_vendor: sco_config_cb
,10-12 06:51:04.162  5911  5931 I bt_hci  : sco_config_callback postload finished.
,10-12 06:51:04.164  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:04.166  5911  5927 D bt_bte_conf: Device ID record 1 : primary
,10-12 06:51:04.167  5911  5927 D bt_bte_conf:   vendorId            = 000f
10-12 06:51:04.167  5911  5927 D bt_bte_conf:   vendorIdSource      = 0001
10-12 06:51:04.167  5911  5927 D bt_bte_conf:   product             = 1200
10-12 06:51:04.167  5911  5927 D bt_bte_conf:   version             = 1436
,10-12 06:51:04.167  5911  5927 D bt_bte_conf:   clientExecutableURL = 
10-12 06:51:04.167  5911  5927 D bt_bte_conf:   serviceDescription  = 
10-12 06:51:04.167  5911  5927 D bt_bte_conf:   documentationURL    = 
10-12 06:51:04.167  5911  5927 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-12 06:51:04.167  5911  5924 D bt_stack_manager: event_start_up_stack finished
10-12 06:51:04.167  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:04.168  5911  5923 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-12 06:51:04.169  5911  5923 D BluetoothAdapterProperties: Setting state to 15
10-12 06:51:04.169  5911  5923 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-12 06:51:04.170  5911  5923 I BluetoothAdapterState: Entering BleOnState
10-12 06:51:04.171  5911  5931 I bt_vendor: low_power_mode_cb
,10-12 06:51:04.175  5911  5923 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-12 06:51:04.175  5911  5923 D BluetoothAdapterProperties: Setting state to 11
10-12 06:51:04.175  5911  5923 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-12 06:51:04.182  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:04.183  5911  5911 D HeadsetService: Received start request. Starting profile...
,10-12 06:51:04.187  5911  5911 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-12 06:51:04.187  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:04.187  5911  5911 D HeadsetStateMachine: make
,10-12 06:51:04.192  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:51:04.203  5911  5923 I BluetoothAdapterState: Entering PendingCommandState
,10-12 06:51:04.208  5911  5911 D HeadsetStateMachine: max_hf_connections = 1
,10-12 06:51:04.209  5911  5911 I bt_bluedroid: get_profile_interface handsfree
10-12 06:51:04.209  5911  5927 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,10-12 06:51:04.209  5911  5927 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-12 06:51:04.213  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:04.214  5911  5911 D A2dpService: Received start request. Starting profile...
,10-12 06:51:04.215  5911  5911 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-12 06:51:04.216  5911  5911 I bt_bluedroid: get_profile_interface avrcp
,10-12 06:51:04.222  5911  5911 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-12 06:51:04.222  5911  5911 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-12 06:51:04.223  5911  5911 D A2dpStateMachine: make
,10-12 06:51:04.224  5911  5911 I bt_bluedroid: get_profile_interface a2dp
,10-12 06:51:04.224  5911  5927 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-12 06:51:04.226  5911  5943 D A2dpStateMachine: Enter Disconnected: -2
10-12 06:51:04.226  5911  5911 I BluetoothHidServiceJni: classInitNative: succeeds
10-12 06:51:04.227  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
10-12 06:51:04.227  5911  5911 D HidService: Received start request. Starting profile...
10-12 06:51:04.227  5911  5911 I bt_bluedroid: get_profile_interface hidhost
10-12 06:51:04.228  5911  5911 D HidService: setHidService(): set to: null
10-12 06:51:04.228  5911  5927 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf412c56d
10-12 06:51:04.228  5911  5927 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-12 06:51:04.229  5911  5911 I BluetoothHealthServiceJni: classInitNative: succeeds
10-12 06:51:04.230  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:04.231  5911  5911 D HealthService: Received start request. Starting profile...
10-12 06:51:04.231  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 06:51:04.234  5911  5911 I bt_bluedroid: get_profile_interface health
10-12 06:51:04.234  5911  5911 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-12 06:51:04.235  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:04.236  5911  5911 D PanService: Received start request. Starting profile...
10-12 06:51:04.236  5911  5911 D BluetoothPanServiceJni: initializeNative(L110): pan
10-12 06:51:04.236  5911  5911 I bt_bluedroid: get_profile_interface pan
10-12 06:51:04.237  5911  5927 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-12 06:51:04.241  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:04.242  5911  5911 D BluetoothMapService: Received start request. Starting profile...
,10-12 06:51:04.242  5911  5911 D BluetoothMapService: start()
10-12 06:51:04.245  5911  5911 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-12 06:51:04.246  5911  5911 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-12 06:51:04.246  5911  5911 D BluetoothMapAppObserver: createReceiver()
,10-12 06:51:04.246  5911  5911 D BluetoothMapAppObserver: initObservers()
10-12 06:51:04.247  5911  5911 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-12 06:51:04.251  5911  5911 V SapService: SapBinder()
10-12 06:51:04.252  5911  5911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:04.252  5911  5911 D SapService: Received start request. Starting profile...
10-12 06:51:04.252  5911  5911 V SapService: start()
,10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isTurningOff()=false
,10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isTurningOn()=true
10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:51:04.254  5911  5941 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isTurningOff()=false
10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isTurningOn()=true
10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:51:04.254  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:51:04.255  5911  5911 V BluetoothAdapterState: isTurningOff()=false
10-12 06:51:04.255  5911  5911 V BluetoothAdapterState: isTurningOn()=true
,10-12 06:51:04.255  5911  5911 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:51:04.255  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:51:04.255  5911  5911 V BluetoothAdapterState: isTurningOff()=false
10-12 06:51:04.255  5911  5911 V BluetoothAdapterState: isTurningOn()=true
10-12 06:51:04.255  5911  5911 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isTurningOff()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isTurningOn()=true
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isTurningOff()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isTurningOn()=true
,10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
,10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isTurningOff()=false
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isTurningOn()=true
10-12 06:51:04.256  5911  5911 V BluetoothAdapterState: isBleTurningOn()=false
10-12 06:51:04.257  5911  5911 V BluetoothAdapterState: isBleTurningOff()=false
10-12 06:51:04.257  5911  5923 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-12 06:51:04.257  5911  5923 D BluetoothAdapterProperties: ScanMode =  20
10-12 06:51:04.257  5911  5923 D BluetoothAdapterProperties: State =  11
10-12 06:51:04.257  5911  5923 D BluetoothAdapterProperties: Setting state to 12
10-12 06:51:04.257  5911  5923 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-12 06:51:04.258  5911  5923 I BluetoothAdapterState: Entering OnState
10-12 06:51:04.258  5713  5724 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-12 06:51:04.259   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:51:04.259  3161  3985 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-12 06:51:04.263   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-12 06:51:04.264  5911  5927 D BluetoothAdapterProperties: Scan Mode:21
10-12 06:51:04.264  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 06:51:04.264  5911  5927 D BluetoothAdapterProperties: Discoverable Timeout:120
10-12 06:51:04.264  5713  5723 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 06:51:04.264  3161  3161 D BluetoothInputDevice: Proxy object connected
10-12 06:51:04.264  3161  3161 D HidProfile: Bluetooth service connected
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:51:04.268  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:51:04.268  3161  3172 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:51:04.269  3793  3825 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:51:04.269  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:51:04.270  5713  5723 D BluetoothMap: onBluetoothStateChange: up=true
10-12 06:51:04.272  5911  5911 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 06:51:04.272  3161  3985 D BluetoothMap: onBluetoothStateChange: up=true
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:51:04.272  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-12 06:51:04.272  5911  5911 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-12 06:51:04.273  5911  5911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 06:51:04.273  5713  5724 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-12 06:51:04.273  5911  5911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-12 06:51:04.273  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-12 06:51:04.274  5713  5713 D BluetoothA2dp: Proxy object connected
10-12 06:51:04.274  5911  5911 D ObexServerSockets: Succeed to create listening sockets 
10-12 06:51:04.274  5911  5911 D ObexServerSockets0: startAccept()
10-12 06:51:04.274  5911  5911 D ObexServerSockets0: prepareForNewConnect()
10-12 06:51:04.275  3161  3174 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 06:51:04.275  5911  5911 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,10-12 06:51:04.275  5911  5911 D BluetoothSdpJni: SDP Create record success - handle: 0
10-12 06:51:04.276  5713  5713 D BluetoothInputDevice: Proxy object connected
10-12 06:51:04.276  5713  5713 D HidProfile: Bluetooth service connected
10-12 06:51:04.277  3161  3172 D BluetoothA2dp: onBluetoothStateChange: up=true
10-12 06:51:04.277  5911  5949 D ObexServerSockets0: Accepting socket connection...
10-12 06:51:04.277  5911  5950 D ObexServerSockets0: Accepting socket connection...
10-12 06:51:04.277  3161  3161 D BluetoothMap: Proxy object connected
10-12 06:51:04.277  3161  3161 D MapProfile: Bluetooth service connected
10-12 06:51:04.277  3161  3161 D BluetoothMap: getConnectedDevices()
10-12 06:51:04.278  3161  3174 D BluetoothPan: onBluetoothStateChange on: true
10-12 06:51:04.279  5713  5724 D BluetoothPan: onBluetoothStateChange on: true
10-12 06:51:04.279  3161  3161 D BluetoothA2dp: Proxy object connected
10-12 06:51:04.280  3161  3161 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 06:51:04.280  3161  3161 D PanProfile: Bluetooth service connected
10-12 06:51:04.281  5713  5713 D BluetoothMap: Proxy object connected
,10-12 06:51:04.281  5713  5713 D MapProfile: Bluetooth service connected
10-12 06:51:04.281  5713  5713 D BluetoothMap: getConnectedDevices()
10-12 06:51:04.283   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
10-12 06:51:04.283   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-12 06:51:04.283   925   925 D BluetoothA2dp: Proxy object connected
,10-12 06:51:04.283  5713  5723 D BluetoothPbap: onBluetoothStateChange: up=true
10-12 06:51:04.285   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
10-12 06:51:04.286  5911  5911 D BluetoothMapService: onReceive
10-12 06:51:04.286  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-12 06:51:04.286  5911  5911 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-12 06:51:04.286  5911  5911 D BluetoothMapService: STATE_ON
10-12 06:51:04.287  5713  5713 D BluetoothPan: BluetoothPAN Proxy object connected
10-12 06:51:04.287  5713  5713 D PanProfile: Bluetooth service connected
10-12 06:51:04.287  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:51:04.288  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:04.288  5911  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 06:51:04.289  5911  5951 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-12 06:51:04.289  5911  5951 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-12 06:51:04.292  5713  5713 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-12 06:51:04.297  3591  3591 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-12 06:51:04.300  5713  5713 D DockEventReceiver: finishStartingService: stopping service
,10-12 06:51:04.301  5713  5713 D BluetoothPbap: Proxy object connected
10-12 06:51:04.301  5713  5713 D PbapServerProfile: Bluetooth service connected
10-12 06:51:04.302  5911  5954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 06:51:04.313  3161  3161 D BluetoothPbap: Proxy object connected
10-12 06:51:04.313  3161  3161 D PbapServerProfile: Bluetooth service connected
,10-12 06:51:04.315  5911  5911 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-12 06:51:04.315  5911  5911 D ObexServerSockets0: prepareForNewConnect()
,10-12 06:51:04.320  5911  5960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-12 06:51:04.322  5911  5960 I BtOppRfcommListener: Accept thread started.
,10-12 06:51:04.361  5713  5948 D BluetoothHeadset: Proxy object connected
,10-12 06:51:04.361   925   925 D BluetoothHeadset: Proxy object connected
10-12 06:51:04.361   925   925 D BluetoothHeadset: Proxy object connected
10-12 06:51:04.361   925   925 D BluetoothHeadset: Proxy object connected
10-12 06:51:04.362  3793  3827 D BluetoothHeadset: Proxy object connected
10-12 06:51:04.362  3161  3172 D BluetoothHeadset: Proxy object connected
10-12 06:51:04.362  3161  3161 D HeadsetProfile: Bluetooth service connected
10-12 06:51:04.363  5713  5713 D HeadsetProfile: Bluetooth service connected
10-12 06:51:04.364   925   942 D BluetoothHeadset: Proxy object connected
,10-12 06:51:04.369  3161  3985 D BluetoothHeadset: Proxy object connected
10-12 06:51:04.369  3161  3161 D HeadsetProfile: Bluetooth service connected
,10-12 06:51:04.370  3793  4009 D BluetoothHeadset: Proxy object connected
,10-12 06:51:04.383   925   942 D BluetoothHeadset: Proxy object connected
,10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:51:08.019  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 06:51:08.024  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:51:08.024  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:08.025  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5c0aa42 removed from the list
10-12 06:51:08.025  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
,10-12 06:51:08.025  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:08.025  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:08.027  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:08.027  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f4ca53 added. We now have 4 listener(s)
,10-12 06:51:08.027  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:08.031   925  3224 D WifiService: setWifiEnabled: false pid=5659, uid=10077
10-12 06:51:08.031   925  3224 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 06:51:10.917   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:11.919   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:12.920   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:13.042  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:51:13.043   925  3623 D WifiService: setWifiEnabled: true pid=5659, uid=10077
10-12 06:51:13.043   925  3623 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-12 06:51:13.053   506   918 D SoftapController: Softap fwReload - Ok
,10-12 06:51:13.059   506   918 D CommandListener: Setting iface cfg
,10-12 06:51:13.059   506   918 D CommandListener: Trying to bring down wlan0
,10-12 06:51:13.061   506   918 D CommandListener: Clearing all IP addresses on wlan0
,10-12 06:51:13.068   925  2968 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-12 06:51:13.752   925  2968 D wifi    : set interface wlan0 flags (UP)
,10-12 06:51:13.755   925  2968 I WifiHAL : Initializing wifi
10-12 06:51:13.755   925  2968 I WifiHAL : Creating socket
,10-12 06:51:13.760   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-12 06:51:13.762   925  2968 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-12 06:51:13.762   925  2968 D wifi    : Did set static halHandle = 0x7f6fc5ee00
10-12 06:51:13.763   925  2968 D wifi    : halHandle = 0x7f6fc5ee00, mVM = 0x7f8c28d140, mCls = 0x17f6
,10-12 06:51:13.763   925  2968 D wifi    : array field set
10-12 06:51:13.763   925  2968 I WifiNative-HAL: interface[0] = wlan0
10-12 06:51:13.765   925  5965 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547336089088
10-12 06:51:13.765   925  5965 D wifi    : waitForHalEvents called, vm = 0x7f8c28d140, obj = 0x17f6, env = 0x7f817e2380
,10-12 06:51:13.814  5966  5966 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-12 06:51:13.836  5966  5966 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 06:51:13.845  5966  5966 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-12 06:51:13.845  5966  5966 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-12 06:51:13.866   925  2968 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-12 06:51:13.879   925  2968 D WifiConfigStore: Loading config and enabling all networks 
,10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:51:13.881  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 06:51:13.884  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-12 06:51:13.887  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-12 06:51:13.889  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-12 06:51:13.890   925  2968 D WifiConfigStore: loaded 0 passpoint configs
,10-12 06:51:13.890   925  2968 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-12 06:51:13.890   925  2968 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-12 06:51:13.891  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:13.891   925  2968 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-12 06:51:13.892  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:13.892   925  2968 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-12 06:51:13.893   925  2968 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-12 06:51:13.893   925  2968 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-12 06:51:13.893   925  2968 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-12 06:51:13.898  5041  5041 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-12 06:51:13.898   925  2968 D WifiNative-HAL: Setting external_sim to 1
10-12 06:51:13.899   925  2968 D wifi    : setting dfs flag to true, 0x7f719cb4c0
,10-12 06:51:13.899   925  2968 D WifiStateMachine: Setting OUI to DA-A1-19
10-12 06:51:13.900   925  2968 D wifi    : setting scan oui 0x7f719cb4c0
10-12 06:51:13.900   925  2968 D WifiHAL : Sending mac address OUI
,10-12 06:51:13.904   925  2968 E native  : do suspend false
,10-12 06:51:13.912   925  2968 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-12 06:51:13.912   925   925 D RttService: SCAN_AVAILABLE : 3
10-12 06:51:13.912   506   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-12 06:51:13.912   925  3088 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-12 06:51:13.913   506   918 D CommandListener: Setting iface cfg
,10-12 06:51:13.918   925  2966 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
10-12 06:51:13.918   925  2966 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
10-12 06:51:13.921   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:13.926   925  2966 D WifiNative-HAL: p2pGetDeviceAddress
,10-12 06:51:13.926   925  2966 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-12 06:51:13.931   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=301516 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-12 06:51:14.922   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:15.923   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-12 06:51:17.114  5966  5966 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:51:17.123  5966  5966 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:51:17.128  5966  5966 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:51:17.135  5966  5966 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-12 06:51:17.162   925  2968 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-12 06:51:17.163   925  2968 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-12 06:51:17.163   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 06:51:17.173   925  2968 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-12 06:51:17.206   925  2968 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-12 06:51:17.208  5966  5966 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-12 06:51:17.628  5966  5966 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-12 06:51:17.665  5966  5966 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-12 06:51:17.667  5966  5966 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-12 06:51:17.675   925  2968 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 06:51:17.676   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-12 06:51:17.676   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-12 06:51:17.697   925  2968 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-12 06:51:17.710   506   918 D CommandListener: Setting iface cfg
,10-12 06:51:17.716   925  2968 D WifiStateMachine: Start Dhcp Watchdog 3
,10-12 06:51:17.723   925  5972 D DhcpClient: Receive thread started
,10-12 06:51:17.728   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 06:51:17.728   925  2968 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-12 06:51:17.728   925  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-12 06:51:17.809   925  2968 E native  : do suspend false
,10-12 06:51:17.825   925  5971 D DhcpClient: Broadcasting DHCPDISCOVER
,10-12 06:51:17.840   925  5972 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-12 06:51:17.841   925  5971 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-12 06:51:17.843   925  5971 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-12 06:51:17.857   925  5972 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-12 06:51:17.858   925  5971 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-12 06:51:17.861   506   918 D CommandListener: Setting iface cfg
,10-12 06:51:17.867   925  2968 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-12 06:51:17.871   925  5971 D DhcpClient: Scheduling renewal in 86399s
,10-12 06:51:17.880   925  2968 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-12 06:51:17.882   925  2968 D WifiConfigStore: No blacklist allowed without epno enabled
10-12 06:51:17.884   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-12 06:51:17.886   925  2983 D ConnectivityService: Adding iface wlan0 to network 102
,10-12 06:51:17.897   925  2968 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-12 06:51:17.931   925  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-12 06:51:17.931   925  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-12 06:51:17.932   925  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-12 06:51:17.934   925  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-12 06:51:17.935   925  2983 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-12 06:51:17.942   925  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 06:51:17.946   925  2983 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-12 06:51:17.946   925  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-12 06:51:17.946   925  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-12 06:51:17.946   925  2983 D ConnectivityService:    accepting network in place of null
10-12 06:51:17.947   925  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-12 06:51:17.947   925  2968 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-12 06:51:17.947   925  2968 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-12 06:51:17.960   925  5969 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305545, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-12 06:51:17.970   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 06:51:17.992   506   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-12 06:51:17.995   925  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-12 06:51:17.996  3762  3930 W QCNEJ   : |CORE| network available: 102
10-12 06:51:17.996   925  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-12 06:51:17.997  3762  3930 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-12 06:51:17.997   925  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-12 06:51:18.002   925   942 D Tethering: MasterInitialState.processMessage what=3
10-12 06:51:18.004  3762  3930 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-12 06:51:18.004  3762  3930 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.005  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:51:18.007  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.011  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:51:18.011  4959  4959 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-12 06:51:18.012  5067  5090 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-12 06:51:18.012  5067  5090 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-12 06:51:18.012  5067  5090 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-12 06:51:18.012  5067  5090 E SarControlService: no key has been found,reset the power
10-12 06:51:18.012  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-12 06:51:18.012  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-12 06:51:18.012  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-12 06:51:18.013  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-12 06:51:18.013  5092  5092 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-12 06:51:18.014  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.014  5067  5102 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-12 06:51:18.014  5067  5102 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-12 06:51:18.014  5067  5102 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-12 06:51:18.017  3730  3730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-12 06:51:18.020  3730  3730 D SystemUpdateService: onCreate
,10-12 06:51:18.015  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-12 06:51:18.022  5092  5092 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-12 06:51:18.023  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000f003000000000000ffffffff]
10-12 06:51:18.024  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:51:18.024  5092  5106 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-12 06:51:18.024  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 06:51:18.024  5067  5078 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-12 06:51:18.027  3730  3730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-12 06:51:18.028  5092  5106 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@49817f9 HexData = [00000000f103000000000000ffffffff]
10-12 06:51:18.028  5092  5106 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-12 06:51:18.028  5092  5106 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-12 06:51:18.029  5092  5092 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-12 06:51:18.029  5067  5077 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-12 06:51:18.031   925  5968 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-12 06:51:18.038  3730  3730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-12 06:51:18.046  3730  5430 I iu.UploadsManager: num queued entries: 0
,10-12 06:51:18.046  3730  5430 I iu.UploadsManager: num updated entries: 0
10-12 06:51:18.046  3730  5430 I iu.SyncManager: NEXT; no task
,10-12 06:51:18.049  3730  3730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-12 06:51:18.050  3730  3730 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-12 06:51:18.052  5778  5778 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-12 06:51:18.056  5778  5778 D SprintDMHelper: simOperator: 
,10-12 06:51:18.056  5778  5778 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.058  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:51:18.060  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.061  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.061  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f4ca53 removed from the list
10-12 06:51:18.061  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:51:18.061  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.061  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.064  5659  5705 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-12 06:51:18.065  5659  5705 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-12 06:51:18.067  5659  5705 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@de30b6d Bundle[{}]
,10-12 06:51:18.067  5659  5705 I io.jxcore.node.LifeCycleMonitor: start: OK
10-12 06:51:18.067  3730  5982 I SystemUpdateService: active receiver: enabled
10-12 06:51:18.067  5659  5705 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-12 06:51:18.068  5659  5705 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-12 06:51:18.068  5659  5705 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-12 06:51:18.069  5659  5705 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-12 06:51:18.070  5659  5705 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-12 06:51:18.076  5659  5705 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-12 06:51:18.076  5659  5705 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-12 06:51:18.076  5659  5705 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-12 06:51:18.078  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 06:51:18.078  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8119f90 added. We now have 3 listener(s)
,10-12 06:51:18.080  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.080  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.080  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.080  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.080  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77f0089 added. We now have 4 listener(s)
10-12 06:51:18.080  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:51:18.081  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-12 06:51:18.084  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 06:51:18.086   925  5968 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 12 Oct 2016 10:51:18 GMT], X-Android-Received-Millis=[1476269478084], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476269478058]}
10-12 06:51:18.086   925  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-12 06:51:18.086   925  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-12 06:51:18.087   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-12 06:51:18.088   925  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-12 06:51:18.090  3730  5982 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.091  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:51:18.093  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 06:51:18.093  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:51:18.093  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:51:18.093  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f7b8af added. We now have 4 listener(s)
10-12 06:51:18.094  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.095  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.095  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.095  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.095  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1924bc added. We now have 5 listener(s)
10-12 06:51:18.095  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:18.095  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:51:18.095  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-12 06:51:18.095  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:51:18.095  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.095  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.095  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.095  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:51:18.095  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.095  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.095  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8119f90 removed from the list
10-12 06:51:18.095  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.096  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77f0089 removed from the list
,10-12 06:51:18.097  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.097  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:51:18.097  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.098  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.098  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:51:18.098  3730  5982 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-12 06:51:18.098  3730  5982 I SystemUpdateService: now status is 0 (complete)
10-12 06:51:18.098  3730  5982 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-12 06:51:18.098  3730  5982 I SystemUpdateService: file has been verified
10-12 06:51:18.098  3730  5982 I SystemUpdateService: OTA package size = 21989297
10-12 06:51:18.099  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.099  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.099  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.099  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77f0089 not in the list
,10-12 06:51:18.099  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.099  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.100  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.100  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.100  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.100  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1924bc removed from the list
10-12 06:51:18.100  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.100  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.100  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.100  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.100  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.100  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f7b8af removed from the list
10-12 06:51:18.101  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:51:18.101  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e1c45 added. We now have 3 listener(s)
10-12 06:51:18.102  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.102  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.102  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.102  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.102  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d3f9a added. We now have 4 listener(s)
10-12 06:51:18.102  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:18.103  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 06:51:18.105  3730  5982 I SystemUpdateService: showing system update notification
,10-12 06:51:18.106  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.110  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:51:18.112  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.113  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-12 06:51:18.113  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 06:51:18.113  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d0a8 added. We now have 4 listener(s)
10-12 06:51:18.114  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.114  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.114  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.114  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.115  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33937c1 added. We now have 5 listener(s)
,10-12 06:51:18.115  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:51:18.115  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:51:18.115  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 06:51:18.115  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 06:51:18.115  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:51:18.115  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 06:51:18.116  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.118  5659  5705 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 06:51:18.118  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 06:51:18.118  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.120  3730  3730 D SystemUpdateService: onDestroy
10-12 06:51:18.122  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-12 06:51:18.123  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 06:51:18.123  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 06:51:18.130  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 06:51:18.130  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 06:51:18.130  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 06:51:18.130  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 06:51:18.130  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 06:51:18.130  5659  5705 D BluetoothAdapter: STATE_ON
,10-12 06:51:18.133  5911  5939 D BtGatt.GattService: registerClient() - UUID=31a06c05-e8f9-41b7-90fa-fc4b5b94d418
,10-12 06:51:18.133  5911  5927 D BtGatt.GattService: onClientRegistered() - UUID=31a06c05-e8f9-41b7-90fa-fc4b5b94d418, clientIf=5
,10-12 06:51:18.134  5659  5670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-12 06:51:18.135  5911  5922 D BtGatt.GattService: start scan with filters
,10-12 06:51:18.138  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-12 06:51:18.138  5911  5930 D BtGatt.ScanManager: handling starting scan
10-12 06:51:18.139  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 06:51:18.139  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:51:18.139  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-12 06:51:18.139  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 06:51:18.139  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 06:51:18.139  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 06:51:18.140  5911  5930 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4a57c16
,10-12 06:51:18.141  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:51:18.141  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 06:51:18.141  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:51:18.142  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 06:51:18.144  5659  5705 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-12 06:51:18.144  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-12 06:51:18.144  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-12 06:51:18.144  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.144  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 06:51:18.144  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.144  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-12 06:51:18.144  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 06:51:18.144  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 06:51:18.144  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 06:51:18.144  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 06:51:18.144  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 06:51:18.145  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:51:18.146  5911  5927 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 06:51:18.146  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.146  5911  5922 D BtGatt.GattService: stopScan() - queue size =1
10-12 06:51:18.146  5911  5930 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 06:51:18.147  5911  5940 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 06:51:18.147  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 06:51:18.147  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 06:51:18.147  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 06:51:18.147  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:51:18.147  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 06:51:18.147  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 06:51:18.147  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 06:51:18.147  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 06:51:18.149  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 06:51:18.149  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 06:51:18.149  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 06:51:18.149  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 06:51:18.149  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 06:51:18.149  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 06:51:18.151  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 06:51:18.151  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:51:18.151  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 06:51:18.152  5911  5927 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 06:51:18.152  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.152  5911  5930 D BtGatt.ScanManager: Starting BLE batch scan
10-12 06:51:18.152  5911  5930 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 06:51:18.153  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:51:18.153  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:51:18.153  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:51:18.153  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.154  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.154  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:51:18.154  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.154  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-12 06:51:18.154  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84e1c45 removed from the list
10-12 06:51:18.154  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.154  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d3f9a removed from the list
10-12 06:51:18.154  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:51:18.154  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.154  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.154  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.155  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.155  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.155  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:51:18.156  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83d3f9a not in the list
10-12 06:51:18.156  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.156  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.156  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.156  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.156  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.157  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33937c1 removed from the list
10-12 06:51:18.157  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.157  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.157  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.157  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-12 06:51:18.157  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.157  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d0a8 removed from the list
10-12 06:51:18.157  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:51:18.157  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c608efd added. We now have 3 listener(s)
10-12 06:51:18.159  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.159  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.159  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-12 06:51:18.159  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.159  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55c27f2 added. We now have 4 listener(s)
10-12 06:51:18.159  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:18.159  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 06:51:18.161  5911  5927 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 06:51:18.161  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.162  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.166  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:51:18.167  5911  5927 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-12 06:51:18.167  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.168  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.169  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:51:18.169  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:51:18.169  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d40cc0 added. We now have 4 listener(s)
10-12 06:51:18.170  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.170  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.170  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.170  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.170  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fac1df9 added. We now have 5 listener(s)
,10-12 06:51:18.170  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:18.170  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:51:18.171  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.171  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:51:18.171  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 06:51:18.171  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 06:51:18.171  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:51:18.171  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 06:51:18.173  5911  5927 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 06:51:18.173  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.173  5659  5705 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 06:51:18.173  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-12 06:51:18.174  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.174  5911  5930 D BtGatt.ScanManager: stopping BLe Batch
,10-12 06:51:18.176  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 06:51:18.177  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-12 06:51:18.177  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-12 06:51:18.179  5911  5927 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 06:51:18.179  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.179  5911  5930 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 06:51:18.180  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-12 06:51:18.181  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 06:51:18.181  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 06:51:18.181  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 06:51:18.181  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 06:51:18.181  5659  5705 D BluetoothAdapter: STATE_ON
,10-12 06:51:18.183  5911  5939 D BtGatt.GattService: registerClient() - UUID=3a536fa6-ae4f-42fa-91b2-eec1c3dc6649
10-12 06:51:18.184  5911  5927 D BtGatt.GattService: onClientRegistered() - UUID=3a536fa6-ae4f-42fa-91b2-eec1c3dc6649, clientIf=5
,10-12 06:51:18.184  5659  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-12 06:51:18.184  5911  5927 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 06:51:18.184  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.184  5911  5952 D BtGatt.GattService: start scan with filters
,10-12 06:51:18.187  5911  5930 D BtGatt.ScanManager: handling starting scan
,10-12 06:51:18.187  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 06:51:18.187  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 06:51:18.187  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:51:18.187  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 06:51:18.187  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 06:51:18.187  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-12 06:51:18.187  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-12 06:51:18.189  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:51:18.189  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-12 06:51:18.189  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:51:18.190  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-12 06:51:18.191  5041  5987 I Babel   : connection state changed from DISCONNECTED to CONNECTED
10-12 06:51:18.192  5911  5927 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 06:51:18.192  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.192  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:51:18.192  5911  5930 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 06:51:18.192  5659  5705 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-12 06:51:18.192  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-12 06:51:18.192  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:51:18.192  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:51:18.192  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.192  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.192  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 06:51:18.192  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.193  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.193  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c608efd removed from the list
10-12 06:51:18.193  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.193  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55c27f2 removed from the list
10-12 06:51:18.193  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:51:18.193  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:51:18.195  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.195  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-12 06:51:18.195  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.195  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:51:18.196  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.196  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.196  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.196  5911  5927 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-12 ,06:51:18.196  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55c27f2 not in the list
10-12 06:51:18.196  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.196  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 06:51:18.196  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 06:51:18.196  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 06:51:18.196  5911  5930 D BtGatt.ScanManager: Starting BLE batch scan
10-12 06:51:18.196  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-12 06:51:18.196  5911  5930 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-12 06:51:18.197  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 06:51:18.197  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:51:18.198  5911  5940 D BtGatt.GattService: stopScan() - queue size =1
,10-12 06:51:18.201  5911  5921 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-12 06:51:18.201  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 06:51:18.201  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 06:51:18.201  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 06:51:18.202  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:51:18.202  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 06:51:18.202  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 06:51:18.202  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,10-12 06:51:18.202  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-12 06:51:18.203  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:51:18.203  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-12 06:51:18.203  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 06:51:18.203  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 06:51:18.203  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 06:51:18.203  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:51:18.204  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-12 06:51:18.204  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.204  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:51:18.204  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fac1df9 removed from the list
10-12 06:51:18.204  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.204  5911  5927 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 06:51:18.204  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.204  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:51:18.205  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.205  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.205  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.205  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:51:18.205  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d40cc0 removed from the list
10-12 06:51:18.205  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:51:18.205  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-12 06:51:18.205  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:51:18.205  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@587a0b5 added. We now have 3 listener(s)
10-12 06:51:18.206  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.206  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.207  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.207  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.207  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb4c34a added. We now have 4 listener(s)
,10-12 06:51:18.207  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:18.207  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 06:51:18.209  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:51:18.209  5911  5927 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 06:51:18.210  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.212  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-12 06:51:18.214  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.214  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:51:18.214  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:51:18.214  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24eb3d8 added. We now have 4 listener(s)
10-12 06:51:18.215  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.215  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.215  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.215  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-12 06:51:18.215  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75e9331 added. We now have 5 listener(s)
10-12 06:51:18.215  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:18.216  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:51:18.216  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-12 06:51:18.216  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-12 06:51:18.216  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:51:18.216  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-12 06:51:18.216  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.217  5911  5927 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 06:51:18.217  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.217  5911  5930 D BtGatt.ScanManager: stopping BLe Batch
,10-12 06:51:18.219  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.219  5659  5705 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-12 06:51:18.219  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-12 06:51:18.223  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-12 06:51:18.223  5911  5927 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-12 06:51:18.223  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.223  5911  5930 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-12 06:51:18.223  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-12 06:51:18.224  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-12 06:51:18.226  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-12 06:51:18.226  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-12 06:51:18.226  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-12 06:51:18.227  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-12 06:51:18.227  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-12 06:51:18.227  5911  5927 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-12 06:51:18.227  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.227  5659  5705 D BluetoothAdapter: STATE_ON
,10-12 06:51:18.229  5911  5922 D BtGatt.GattService: registerClient() - UUID=97732365-4080-4755-98ab-31b62fe47cb4
10-12 06:51:18.229  5911  5927 D BtGatt.GattService: onClientRegistered() - UUID=97732365-4080-4755-98ab-31b62fe47cb4, clientIf=5
,10-12 06:51:18.230  5659  5670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-12 06:51:18.230  5911  5952 D BtGatt.GattService: start scan with filters
,10-12 06:51:18.232  5911  5930 D BtGatt.ScanManager: handling starting scan
10-12 06:51:18.232  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-12 06:51:18.232  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-12 06:51:18.232  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:51:18.232  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-12 06:51:18.232  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-12 06:51:18.233  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,10-12 06:51:18.233  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-12 06:51:18.235  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-12 06:51:18.235  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-12 06:51:18.236  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-12 06:51:18.236  5911  5927 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-12 06:51:18.236  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:51:18.237  5911  5930 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-12 06:51:18.237  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-12 06:51:18.241  5911  5927 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-12 06:51:18.241  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.241  5911  5930 D BtGatt.ScanManager: Starting BLE batch scan
10-12 06:51:18.241  5911  5930 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-12 06:51:18.242  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:51:18.242  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:51:18.242  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:51:18.242  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.242  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.242  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-12 06:51:18.242  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.242  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.242  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@587a0b5 removed from the list
10-12 06:51:18.242  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-12 06:51:18.242  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb4c34a removed from the list
10-12 06:51:18.242  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:51:18.242  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-12 06:51:18.243  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-12 06:51:18.243  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-12 06:51:18.243  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.243  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:51:18.244  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.244  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.244  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.244  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@eb4c34a not in the list
10-12 06:51:18.244  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-12 06:51:18.244  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-12 06:51:18.244  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-12 06:51:18.244  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-12 06:51:18.244  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-12 06:51:18.245  5659  5705 D BluetoothAdapter: STATE_ON
10-12 06:51:18.245  5911  5922 D BtGatt.GattService: stopScan() - queue size =1
10-12 06:51:18.246  5911  5952 D BtGatt.GattService: unregisterClient() - clientIf=5
10-12 06:51:18.246  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-12 06:51:18.246  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-12 06:51:18.246  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-12 06:51:18.246  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-12 06:51:18.246  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-12 06:51:18.246  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-12 06:51:18.246  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-12 06:51:18.246  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-12 06:51:18.247  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:51:18.247  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-12 06:51:18.247  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-12 06:51:18.247  5659  5705 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-12 06:51:18.247  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-12 06:51:18.247  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.248  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.248  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.248  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.248  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-12 06:51:18.248  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75e9331 removed from the list
10-12 06:51:18.248  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.248  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-12 06:51:18.248  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.249  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-12 06:51:18.249  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.249  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.249  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.249  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24eb3d8 removed from the list
,10-12 06:51:18.249  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-12 06:51:18.249  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8316d added. We now have 3 listener(s)
10-12 06:51:18.250  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.250  5911  5927 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-12 06:51:18.250  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.250  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.250  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.251  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.251  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56a71a2 added. We now have 4 listener(s)
10-12 06:51:18.251  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-12 06:51:18.251  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-12 06:51:18.253  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-12 06:51:18.255  5911  5927 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-12 06:51:18.255  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-12 06:51:18.258  5659  5705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-12 06:51:18.260  5911  5927 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-12 06:51:18.261  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.261  5659  5705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-12 06:51:18.261  5911  5930 D BtGatt.ScanManager: stopping BLe Batch
10-12 06:51:18.261  5659  5705 D io.jxcore.node.ConnectivityMonitor: start: OK
10-12 06:51:18.261  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-12 06:51:18.261  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16425f0 added. We now have 4 listener(s)
,10-12 06:51:18.262  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-12 06:51:18.263  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-12 06:51:18.263  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-12 06:51:18.263  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-12 06:51:18.263  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d37769 added. We now have 5 listener(s)
10-12 06:51:18.263  5659  5705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-12 06:51:18.263  5659  5705 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-12 06:51:18.263  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-12 06:51:18.263  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:51:18.264  5659  5705 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-12 06:51:18.264  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.264  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.264  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-12 06:51:18.264  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.264  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.264  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd8316d removed from the list
10-12 06:51:18.264  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.264  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56a71a2 removed from the list
10-12 06:51:18.265  5911  5927 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-12 06:51:18.265  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.266  5911  5930 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-12 06:51:18.266  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-12 06:51:18.266  5659  5705 D io.jxcore.node.ConnectivityMonitor: stop
10-12 06:51:18.267  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:51:18.267  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.267  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:51:18.268  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.268  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.269  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.269  5659  5705 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56a71a2 not in the list
,10-12 06:51:18.269  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.269  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-12 06:51:18.271  5911  5927 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-12 06:51:18.271  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-12 06:51:18.271  5911  5927 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-12 06:51:18.271  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-12 06:51:18.271  5659  5705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-12 06:51:18.271  5659  5705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d37769 removed from the list
10-12 06:51:18.271  5659  5705 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-12 06:51:18.271  5659  5705 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-12 06:51:18.271  5659  5705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-12 06:51:18.271  5659  5705 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-12 06:51:18.271  5659  5705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-12 06:51:18.271  5659  5705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16425f0 removed from the list
,10-12 06:51:18.272  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-12 06:51:18.272  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-12 06:51:18.273  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-12 06:51:18.273  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-12 06:51:18.273  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-12 06:51:18.273  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-12 06:51:18.652  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 06:51:18.705  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 06:51:18.749  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-12 06:51:20.413  5659  5994 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 06:51:20.413  5659  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:20.747   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 06:51:21.199  5659  5994 W !!      : call onHalfStreamCopied
,10-12 06:51:21.199  5659  5994 I testCopyDataAndClose: closing input stream
,10-12 06:51:21.973  5659  5994 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 06:51:21.973  5659  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-12 06:51:21.974  5659  5994 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 06:51:23.772   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 06:51:25.756  5659  5995 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:25.756  5659  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:25.949   925  2983 D ConnectivityService: handlePromptUnvalidated 102
,10-12 06:51:27.756  5659  5705 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-12 06:51:27.756  5659  5705 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:27.756  5659  5705 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-12 06:51:27.826  5659  5995 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-12 06:51:27.826  5659  5995 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:27.826  5659  5995 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,10-12 06:51:27.900  5659  5996 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 06:51:27.900  5659  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:28.934   925  2968 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-12 06:51:29.518  5659  5996 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-12 06:51:33.264  5659  5997 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:33.264  5659  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-12 06:51:33.265  5659  5997 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:33.265  5659  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 06:51:33.265  5659  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-12 06:51:33.265  5659  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 06:51:33.265  5659  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-12 06:51:33.265  5659  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-12 06:51:33.265  5659  5997 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-12 06:51:33.266  5659  5997 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-12 06:51:33.266  5659  5997 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-12 06:51:33.266  5659  5997 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:33.266  5659  5997 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-12 06:51:33.267  5659  5705 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-12 06:51:33.270  5659  5998 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:33.270  5659  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-12 06:51:33.270  5659  5998 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,10-12 06:51:33.271  5659  5998 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:33.271  5659  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-12 06:51:33.271  5659  5998 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-12 06:51:33.271  5659  5998 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-12 06:51:33.271  5659  5998 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-12 06:51:33.275  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-12 06:51:33.275  5659  5705 I jxcore-log: 
10-12 06:51:33.276  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-12 06:51:33.276  5659  5705 I jxcore-log: 
10-12 06:51:33.276  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-12 06:51:33.276  5659  5705 I jxcore-log: 
10-12 06:51:33.276  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-12 06:51:33.276  5659  5705 I jxcore-log: 
,10-12 06:51:33.276  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'Total duration:  90733'
10-12 06:51:33.276  5659  5705 I jxcore-log: 
10-12 06:51:33.279  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-12 06:51:33.279  5659  5705 I jxcore-log: 
,10-12 06:51:33.283  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.283  5659  5705 I jxcore-log: 
10-12 06:51:33.284  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.284  5659  5705 I jxcore-log: 
10-12 06:51:33.284  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.284  5659  5705 I jxcore-log: 
,10-12 06:51:33.285  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.285  5659  5705 I jxcore-log: 
10-12 06:51:33.285  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-12 06:51:33.285  5659  5705 I jxcore-log: 
10-12 06:51:33.286  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 06:51:33.286  5659  5705 I jxcore-log: 
10-12 06:51:33.286  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.286  5659  5705 I jxcore-log: 
10-12 06:51:33.286  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.286  5659  5705 I jxcore-log: 
10-12 06:51:33.286  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-12 06:51:33.286  5659  5705 I jxcore-log: 
,10-12 06:51:33.287  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 06:51:33.287  5659  5705 I jxcore-log: 
10-12 06:51:33.287  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 06:51:33.287  5659  5705 I jxcore-log: 
10-12 06:51:33.287  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.287  5659  5705 I jxcore-log: 
10-12 06:51:33.287  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.287  5659  5705 I jxcore-log: 
10-12 06:51:33.288  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.288  5659  5705 I jxcore-log: 
10-12 06:51:33.288  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.288  5659  5705 I jxcore-log: 
10-12 06:51:33.288  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.288  5659  5705 I jxcore-log: 
10-12 06:51:33.289  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.289  5659  5705 I jxcore-log: 
10-12 06:51:33.289  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.289  5659  5705 I jxcore-log: 
10-12 06:51:33.289  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.289  5659  5705 I jxcore-log: 
10-12 06:51:33.289  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.289  5659  5705 I jxcore-log: 
10-12 06:51:33.289  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.289  5659  5705 I jxcore-log: 
10-12 06:51:33.290  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.290  5659  5705 I jxcore-log: 
10-12 06:51:33.290  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.290  5659  5705 I jxcore-log: 
10-12 06:51:33.291  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.291  5659  5705 I jxcore-log: 
10-12 06:51:33.292  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.292  5659  5705 I jxcore-lo,g: 
10-12 06:51:33.292  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.292  5659  5705 I jxcore-log: 
10-12 06:51:33.292  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.292  5659  5705 I jxcore-log: 
10-12 06:51:33.293  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.293  5659  5705 I jxcore-log: 
10-12 06:51:33.293  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.293  5659  5705 I jxcore-log: 
10-12 06:51:33.293  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.293  5659  5705 I jxcore-log: 
10-12 06:51:33.293  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.293  5659  5705 I jxcore-log: 
10-12 06:51:33.293  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.293  5659  5705 I jxcore-log: 
10-12 06:51:33.294  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.294  5659  5705 I jxcore-log: 
,10-12 06:51:33.294  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.294  5659  5705 I jxcore-log: 
10-12 06:51:33.294  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.294  5659  5705 I jxcore-log: 
10-12 06:51:33.294  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.294  5659  5705 I jxcore-log: 
10-12 06:51:33.295  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.295  5659  5705 I jxcore-log: 
10-12 06:51:33.295  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.295  5659  5705 I jxcore-log: 
10-12 06:51:33.295  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-12 06:51:33.295  5659  5705 I jxcore-log: 
10-12 06:51:33.295  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.295  5659  5705 I jxcore-log: 
10-12 06:51:33.295  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-12 06:51:33.295  5659  5705 I jxcore-log: 
10-12 06:51:33.296  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.296  5659  5705 I jxcore-log: 
10-12 06:51:33.296  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.296  5659  5705 I jxcore-log: 
10-12 06:51:33.296  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.296  5659  5705 I jxcore-log: 
,10-12 06:51:33.296  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.296  5659  5705 I jxcore-log: 
10-12 06:51:33.297  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.297  5659  5705 I jxcore-log: 
10-12 06:51:33.297  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-12 06:51:33.297  5659  5705 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-12 06:51:33.297  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.297  5659  5705 I jxcore-log: 
10-12 06:51:33.297  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.297  5659  5705 I jxcore-log: 
,10-12 06:51:33.297  5659  5705 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-12 06:51:33.297  5659  5705 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-12 06:51:33.298  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-12 06:51:33.298  5659  5705 I jxcore-log: 
10-12 06:51:33.298  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 06:51:33.298  5659  5705 I jxcore-log: 
10-12 06:51:33.298  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 06:51:33.298  5659  5705 I jxcore-log: 
10-12 06:51:33.298  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-12 06:51:33.298  5659  5705 I jxcore-log: 
,10-12 06:51:33.304  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-12 06:51:33.304  5659  5705 I jxcore-log: 
10-12 06:51:33.304  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - WARN testUtils: 'myNameCallback not set!'
10-12 06:51:33.304  5659  5705 I jxcore-log: 
10-12 06:51:33.304  5659  5659 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-12 06:51:33.305  5659  5705 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-12 06:51:33.305  5659  5705 I jxcore-log: 2016-10-12 10:51:33 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-12 06:51:33.305  5659  5705 I jxcore-log: 
,10-12 06:51:35.284  5659  5705 I jxcore-log: 2016-10-12 10:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-12 06:51:35.284  5659  5705 I jxcore-log: 
,10-12 06:51:35.604  5659  5705 I jxcore-log: 2016-10-12 10:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-12 06:51:35.604  5659  5705 I jxcore-log: 
,10-12 06:51:35.622  5659  5705 I jxcore-log: 2016-10-12 10:51:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-12 06:51:35.622  5659  5705 I jxcore-log: 
,10-12 06:51:36.684  5659  5705 I jxcore-log: 2016-10-12 10:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-12 06:51:36.684  5659  5705 I jxcore-log: 
,10-12 06:51:36.843  5659  5705 I jxcore-log: 2016-10-12 10:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-12 06:51:36.843  5659  5705 I jxcore-log: 
,10-12 06:51:36.849  5659  5705 I jxcore-log: 2016-10-12 10:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-12 06:51:36.849  5659  5705 I jxcore-log: 
,10-12 06:51:36.853  5659  5705 I jxcore-log: 2016-10-12 10:51:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-12 06:51:36.853  5659  5705 I jxcore-log: 
,10-12 06:51:37.323  5659  5705 I jxcore-log: 2016-10-12 10:51:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-12 06:51:37.323  5659  5705 I jxcore-log: 
,10-12 06:51:37.365  5659  5705 I jxcore-log: 2016-10-12 10:51:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-12 06:51:37.365  5659  5705 I jxcore-log: 
,10-12 06:51:37.378  5659  5705 I jxcore-log: 2016-10-12 10:51:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-12 06:51:37.378  5659  5705 I jxcore-log: 
,10-12 06:51:37.382  5659  5705 I jxcore-log: 2016-10-12 10:51:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-12 06:51:37.382  5659  5705 I jxcore-log: 
,10-12 06:51:37.675  5659  5705 I jxcore-log: 2016-10-12 10:51:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-12 06:51:37.675  5659  5705 I jxcore-log: 
,10-12 06:51:37.799  5659  5705 I jxcore-log: 2016-10-12 10:51:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-12 06:51:37.799  5659  5705 I jxcore-log: 
,10-12 06:51:38.028  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-12 06:51:38.028  5659  5705 I jxcore-log: 
,10-12 06:51:38.161  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-12 06:51:38.161  5659  5705 I jxcore-log: 
,10-12 06:51:38.166  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-12 06:51:38.166  5659  5705 I jxcore-log: 
,10-12 06:51:38.171  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-12 06:51:38.171  5659  5705 I jxcore-log: 
,10-12 06:51:38.176  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-12 06:51:38.176  5659  5705 I jxcore-log: 
,10-12 06:51:38.202  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-12 06:51:38.202  5659  5705 I jxcore-log: 
,10-12 06:51:38.235  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-12 06:51:38.235  5659  5705 I jxcore-log: 
,10-12 06:51:38.242  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-12 06:51:38.242  5659  5705 I jxcore-log: 
,10-12 06:51:38.247  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-12 06:51:38.247  5659  5705 I jxcore-log: 
,10-12 06:51:38.260  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-12 06:51:38.260  5659  5705 I jxcore-log: 
,10-12 06:51:38.264  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-12 06:51:38.264  5659  5705 I jxcore-log: 
,10-12 06:51:38.269  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-12 06:51:38.269  5659  5705 I jxcore-log: 
,10-12 06:51:38.274  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-12 06:51:38.274  5659  5705 I jxcore-log: 
,10-12 06:51:38.285  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-12 06:51:38.285  5659  5705 I jxcore-log: 
,10-12 06:51:38.305  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-12 06:51:38.305  5659  5705 I jxcore-log: 
,10-12 06:51:38.315  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-12 06:51:38.315  5659  5705 I jxcore-log: 
,10-12 06:51:38.327  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-12 06:51:38.327  5659  5705 I jxcore-log: 
,10-12 06:51:38.337  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-12 06:51:38.337  5659  5705 I jxcore-log: 
,10-12 06:51:38.350  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-12 06:51:38.350  5659  5705 I jxcore-log: 
,10-12 06:51:38.360  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-12 06:51:38.360  5659  5705 I jxcore-log: 
,10-12 06:51:38.364  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-12 06:51:38.364  5659  5705 I jxcore-log: 
,10-12 06:51:38.385  5659  5705 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-12 06:51:38.386  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - INFO testUtils: 'BLE multiple advertisement supported'
10-12 06:51:38.386  5659  5705 I jxcore-log: 
,10-12 06:51:38.581  5659  5705 I jxcore-log: 2016-10-12 10:51:38 - DEBUG CoordinatedClient: 'connected to the test server'
10-12 06:51:38.581  5659  5705 I jxcore-log: 
,10-12 06:51:39.148  5659  5705 I jxcore-log: TAP version 13
10-12 06:51:39.148  5659  5705 I jxcore-log: 
,10-12 06:51:39.190  5659  5705 I jxcore-log: # setup
10-12 06:51:39.190  5659  5705 I jxcore-log: 
,10-12 06:51:40.292  5659  5705 I jxcore-log: # calling createNativeListener directly rejects
10-12 06:51:40.292  5659  5705 I jxcore-log: 
,10-12 06:51:40.451  5659  5705 I jxcore-log: 2016-10-12 10:51:40 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:40.451  5659  5705 I jxcore-log: 
,10-12 06:51:40.459  5659  5705 I jxcore-log: 2016-10-12 10:51:40 - DEBUG createNativeListener: 'listening 45099'
10-12 06:51:40.459  5659  5705 I jxcore-log: 
,10-12 06:51:40.468  5659  5705 I jxcore-log: ok 1 Should throw
10-12 06:51:40.468  5659  5705 I jxcore-log: 
,10-12 06:51:40.479  5659  5705 I jxcore-log: # teardown
10-12 06:51:40.479  5659  5705 I jxcore-log: 
,10-12 06:51:40.774  5659  5705 I jxcore-log: # setup
10-12 06:51:40.774  5659  5705 I jxcore-log: 
,10-12 06:51:40.923   548   548 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-12 06:51:40.924   548   548 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-12 06:51:41.252  5659  5705 I jxcore-log: # emits incomingConnectionState
10-12 06:51:41.252  5659  5705 I jxcore-log: 
,10-12 06:51:42.100  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:42.100  5659  5705 I jxcore-log: 
,10-12 06:51:42.105  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'listening 48133'
10-12 06:51:42.105  5659  5705 I jxcore-log: 
,10-12 06:51:42.116  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:42.116  5659  5705 I jxcore-log: 
,10-12 06:51:42.120  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:42.120  5659  5705 I jxcore-log: 
,10-12 06:51:42.132  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new mux'
10-12 06:51:42.132  5659  5705 I jxcore-log: 
,10-12 06:51:42.140  5659  5705 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-12 06:51:42.140  5659  5705 I jxcore-log: 
,10-12 06:51:42.159  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:42.159  5659  5705 I jxcore-log: 
,10-12 06:51:42.160  5659  5705 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-12 06:51:42.160  5659  5705 I jxcore-log: 
,10-12 06:51:42.169  5659  5705 I jxcore-log: # teardown
10-12 06:51:42.169  5659  5705 I jxcore-log: 
,10-12 06:51:42.246  5659  5705 I jxcore-log: # setup
10-12 06:51:42.246  5659  5705 I jxcore-log: 
,10-12 06:51:42.285  5659  5705 I jxcore-log: # emits routerPortConnectionFailed
10-12 06:51:42.285  5659  5705 I jxcore-log: 
,10-12 06:51:42.355  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:42.355  5659  5705 I jxcore-log: 
,10-12 06:51:42.358  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'listening 39403'
10-12 06:51:42.358  5659  5705 I jxcore-log: 
,10-12 06:51:42.368  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:42.368  5659  5705 I jxcore-log: 
,10-12 06:51:42.370  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:42.370  5659  5705 I jxcore-log: 
,10-12 06:51:42.371  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new mux'
10-12 06:51:42.371  5659  5705 I jxcore-log: 
,10-12 06:51:42.397  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:42.397  5659  5705 I jxcore-log: 
,10-12 06:51:42.399  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:42.399  5659  5705 I jxcore-log: 
,10-12 06:51:42.403  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: ' $c@net.js:837:7
10-12 06:51:42.403  5659  5705 I jxcore-log: $09@net.js:829:13
10-12 06:51:42.403  5659  5705 I jxcore-log: '
10-12 06:51:42.403  5659  5705 I jxcore-log: 
,10-12 06:51:42.404  5659  5705 I jxcore-log: ok 4 tried to connect to right port
10-12 06:51:42.404  5659  5705 I jxcore-log: 
10-12 06:51:42.405  5659  5705 I jxcore-log: ok 5 failed due to refused connection
10-12 06:51:42.405  5659  5705 I jxcore-log: 
10-12 06:51:42.406  5659  5705 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-12 06:51:42.406  5659  5705 I jxcore-log: 
,10-12 06:51:42.410  5659  5705 I jxcore-log: # teardown
10-12 06:51:42.410  5659  5705 I jxcore-log: 
,10-12 06:51:42.412  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:42.412  5659  5705 I jxcore-log: 
,10-12 06:51:42.460  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'mux close'
10-12 06:51:42.460  5659  5705 I jxcore-log: 
,10-12 06:51:42.465  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:42.465  5659  5705 I jxcore-log: 
,10-12 06:51:42.478  5659  5705 I jxcore-log: # setup
10-12 06:51:42.478  5659  5705 I jxcore-log: 
,10-12 06:51:42.559  5659  5705 I jxcore-log: # native server connections all up
10-12 06:51:42.559  5659  5705 I jxcore-log: 
,10-12 06:51:42.642  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:42.642  5659  5705 I jxcore-log: 
,10-12 06:51:42.646  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'listening 39493'
10-12 06:51:42.646  5659  5705 I jxcore-log: 
,10-12 06:51:42.656  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:42.656  5659  5705 I jxcore-log: 
,10-12 06:51:42.658  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:42.658  5659  5705 I jxcore-log: 
,10-12 06:51:42.660  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new mux'
10-12 06:51:42.660  5659  5705 I jxcore-log: 
,10-12 06:51:42.687  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:42.687  5659  5705 I jxcore-log: 
,10-12 06:51:42.691  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:42.691  5659  5705 I jxcore-log: 
,10-12 06:51:42.694  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:42.694  5659  5705 I jxcore-log: 
,10-12 06:51:42.697  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:42.697  5659  5705 I jxcore-log: 
,10-12 06:51:42.717  5659  5705 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-12 06:51:42.717  5659  5705 I jxcore-log: 
10-12 06:51:42.718  5659  5705 I jxcore-log: ok 8 Send/recvd #1 should be same
10-12 06:51:42.718  5659  5705 I jxcore-log: 
,10-12 06:51:42.720  5659  5705 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-12 06:51:42.720  5659  5705 I jxcore-log: 
,10-12 06:51:42.721  5659  5705 I jxcore-log: ok 10 Send/recvd #2 should be same
10-12 06:51:42.721  5659  5705 I jxcore-log: 
,10-12 06:51:42.724  5659  5705 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-12 06:51:42.724  5659  5705 I jxcore-log: 
,10-12 06:51:42.731  5659  5705 I jxcore-log: # teardown
10-12 06:51:42.731  5659  5705 I jxcore-log: 
,10-12 06:51:42.757  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:42.757  5659  5705 I jxcore-log: 
,10-12 06:51:42.758  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:42.758  5659  5705 I jxcore-log: 
,10-12 06:51:42.760  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'mux close'
10-12 06:51:42.760  5659  5705 I jxcore-log: 
,10-12 06:51:42.764  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:42.764  5659  5705 I jxcore-log: 
,10-12 06:51:42.773  5659  5705 I jxcore-log: # setup
10-12 06:51:42.773  5659  5705 I jxcore-log: 
,10-12 06:51:42.855  5659  5705 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-12 06:51:42.855  5659  5705 I jxcore-log: 
,10-12 06:51:42.968  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:42.968  5659  5705 I jxcore-log: 
,10-12 06:51:42.973  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'listening 44004'
10-12 06:51:42.973  5659  5705 I jxcore-log: 
,10-12 06:51:42.980  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:42.980  5659  5705 I jxcore-log: 
,10-12 06:51:42.983  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:42.983  5659  5705 I jxcore-log: 
,10-12 06:51:42.988  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new mux'
10-12 06:51:42.988  5659  5705 I jxcore-log: 
,10-12 06:51:42.997  5659  5705 I jxcore-log: 2016-10-12 10:51:42 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:42.997  5659  5705 I jxcore-log: 
,10-12 06:51:43.000  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:43.000  5659  5705 I jxcore-log: 
,10-12 06:51:43.012  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:43.012  5659  5705 I jxcore-log: 
,10-12 06:51:43.023  5659  5705 I jxcore-log: ok 12 socket shouldn't close until after stream
10-12 06:51:43.023  5659  5705 I jxcore-log: 
,10-12 06:51:43.024  5659  5705 I jxcore-log: ok 13 incoming remains open
10-12 06:51:43.024  5659  5705 I jxcore-log: 
,10-12 06:51:43.031  5659  5705 I jxcore-log: # teardown
10-12 06:51:43.031  5659  5705 I jxcore-log: 
,10-12 06:51:43.060  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'mux close'
10-12 06:51:43.060  5659  5705 I jxcore-log: 
,10-12 06:51:43.064  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:43.064  5659  5705 I jxcore-log: 
,10-12 06:51:43.071  5659  5705 I jxcore-log: # setup
10-12 06:51:43.071  5659  5705 I jxcore-log: 
,10-12 06:51:43.167  5659  5705 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-12 06:51:43.167  5659  5705 I jxcore-log: 
,10-12 06:51:43.210  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:43.210  5659  5705 I jxcore-log: 
,10-12 06:51:43.215  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'listening 48918'
10-12 06:51:43.215  5659  5705 I jxcore-log: 
,10-12 06:51:43.223  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.223  5659  5705 I jxcore-log: 
,10-12 06:51:43.225  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.225  5659  5705 I jxcore-log: 
,10-12 06:51:43.227  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.227  5659  5705 I jxcore-log: 
,10-12 06:51:43.239  5659  5705 I jxcore-log: ok 14 we should not have gotten an error
10-12 06:51:43.239  5659  5705 I jxcore-log: 
,10-12 06:51:43.244  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:43.244  5659  5705 I jxcore-log: 
,10-12 06:51:43.249  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:43.249  5659  5705 I jxcore-log: 
,10-12 06:51:43.260  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:43.260  5659  5705 I jxcore-log: 
,10-12 06:51:43.263  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:43.263  5659  5705 I jxcore-log: 
,10-12 06:51:43.270  5659  5705 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-12 06:51:43.270  5659  5705 I jxcore-log: 
,10-12 06:51:43.271  5659  5705 I jxcore-log: ok 16 incoming is cleaned up
10-12 06:51:43.271  5659  5705 I jxcore-log: 
,10-12 06:51:43.279  5659  5705 I jxcore-log: # teardown
10-12 06:51:43.279  5659  5705 I jxcore-log: 
,10-12 06:51:43.333  5659  5705 I jxcore-log: # setup
10-12 06:51:43.333  5659  5705 I jxcore-log: 
,10-12 06:51:43.410  5659  5705 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-12 06:51:43.410  5659  5705 I jxcore-log: 
,10-12 06:51:43.446  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:43.446  5659  5705 I jxcore-log: 
,10-12 06:51:43.451  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'listening 39007'
10-12 06:51:43.451  5659  5705 I jxcore-log: 
,10-12 06:51:43.459  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.459  5659  5705 I jxcore-log: 
,10-12 06:51:43.461  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.461  5659  5705 I jxcore-log: 
,10-12 06:51:43.465  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.465  5659  5705 I jxcore-log: 
,10-12 06:51:43.479  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:43.479  5659  5705 I jxcore-log: 
,10-12 06:51:43.482  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:43.482  5659  5705 I jxcore-log: 
,10-12 06:51:43.497  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:43.497  5659  5705 I jxcore-log: 
,10-12 06:51:43.505  5659  5705 I jxcore-log: ok 17 stream was closed
10-12 06:51:43.505  5659  5705 I jxcore-log: 
,10-12 06:51:43.506  5659  5705 I jxcore-log: ok 18 incoming should survive
10-12 06:51:43.506  5659  5705 I jxcore-log: 
10-12 06:51:43.506  5659  5705 I jxcore-log: ok 19 mux should have no streams
10-12 06:51:43.506  5659  5705 I jxcore-log: 
,10-12 06:51:43.511  5659  5705 I jxcore-log: # teardown
10-12 06:51:43.511  5659  5705 I jxcore-log: 
,10-12 06:51:43.553  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'mux close'
10-12 06:51:43.553  5659  5705 I jxcore-log: 
,10-12 06:51:43.575  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:43.575  5659  5705 I jxcore-log: 
,10-12 06:51:43.588  5659  5705 I jxcore-log: # setup
10-12 06:51:43.588  5659  5705 I jxcore-log: 
,10-12 06:51:43.643  5659  5705 I jxcore-log: # native server - closing the whole server cleans everything up
10-12 06:51:43.643  5659  5705 I jxcore-log: 
,10-12 06:51:43.708  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:43.708  5659  5705 I jxcore-log: 
,10-12 06:51:43.712  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'listening 39749'
10-12 06:51:43.712  5659  5705 I jxcore-log: 
,10-12 06:51:43.722  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.722  5659  5705 I jxcore-log: 
,10-12 06:51:43.725  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.725  5659  5705 I jxcore-log: 
10-12 06:51:43.727  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.727  5659  5705 I jxcore-log: 
,10-12 06:51:43.737  5659  5705 I jxcore-log: ok 20 we should not have gotten an error
10-12 06:51:43.737  5659  5705 I jxcore-log: 
,10-12 06:51:43.744  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:43.744  5659  5705 I jxcore-log: 
,10-12 06:51:43.748  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:43.748  5659  5705 I jxcore-log: 
,10-12 06:51:43.759  5659  5705 I jxcore-log: ok 21 Buffers are identical
10-12 06:51:43.759  5659  5705 I jxcore-log: 
,10-12 06:51:43.761  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:43.761  5659  5705 I jxcore-log: 
,10-12 06:51:43.765  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'mux close'
10-12 06:51:43.765  5659  5705 I jxcore-log: 
,10-12 06:51:43.768  5659  5705 I jxcore-log: ok 22 native server is nulled out
10-12 06:51:43.768  5659  5705 I jxcore-log: 
10-12 06:51:43.768  5659  5705 I jxcore-log: ok 23 native server should be closed
10-12 06:51:43.768  5659  5705 I jxcore-log: 
,10-12 06:51:43.769  5659  5705 I jxcore-log: ok 24 incoming has been removed
10-12 06:51:43.769  5659  5705 I jxcore-log: 
10-12 06:51:43.770  5659  5705 I jxcore-log: ok 25 Incoming should be done
10-12 06:51:43.770  5659  5705 I jxcore-log: 
,10-12 06:51:43.770  5659  5705 I jxcore-log: ok 26 The mux object should be closed
10-12 06:51:43.770  5659  5705 I jxcore-log: 
10-12 06:51:43.771  5659  5705 I jxcore-log: ok 27 The mux stream should be closed
10-12 06:51:43.771  5659  5705 I jxcore-log: 
,10-12 06:51:43.773  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:43.773  5659  5705 I jxcore-log: 
,10-12 06:51:43.789  5659  5705 I jxcore-log: # teardown
10-12 06:51:43.789  5659  5705 I jxcore-log: 
,10-12 06:51:43.810  5659  5705 I jxcore-log: # setup
10-12 06:51:43.810  5659  5705 I jxcore-log: 
,10-12 06:51:43.848  5659  5705 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-12 06:51:43.848  5659  5705 I jxcore-log: 
,10-12 06:51:43.913  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:43.913  5659  5705 I jxcore-log: 
,10-12 06:51:43.917  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'listening 46960'
10-12 06:51:43.917  5659  5705 I jxcore-log: 
,10-12 06:51:43.951  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.951  5659  5705 I jxcore-log: 
,10-12 06:51:43.952  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.952  5659  5705 I jxcore-log: 
,10-12 06:51:43.955  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.955  5659  5705 I jxcore-log: 
,10-12 06:51:43.958  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.958  5659  5705 I jxcore-log: 
10-12 06:51:43.959  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.959  5659  5705 I jxcore-log: 
,10-12 06:51:43.960  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.960  5659  5705 I jxcore-log: 
,10-12 06:51:43.963  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.963  5659  5705 I jxcore-log: 
10-12 06:51:43.964  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.964  5659  5705 I jxcore-log: 
10-12 06:51:43.965  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.965  5659  5705 I jxcore-log: 
,10-12 06:51:43.969  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.969  5659  5705 I jxcore-log: 
,10-12 06:51:43.970  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.970  5659  5705 I jxcore-log: 
,10-12 06:51:43.971  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.971  5659  5705 I jxcore-log: 
,10-12 06:51:43.974  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.974  5659  5705 I jxcore-log: 
,10-12 06:51:43.975  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.975  5659  5705 I jxcore-log: 
,10-12 06:51:43.979  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.979  5659  5705 I jxcore-log: 
,10-12 06:51:43.981  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.981  5659  5705 I jxcore-log: 
,10-12 06:51:43.982  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.982  5659  5705 I jxcore-log: 
,10-12 06:51:43.983  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.983  5659  5705 I jxcore-log: 
,10-12 06:51:43.986  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.986  5659  5705 I jxcore-log: 
,10-12 06:51:43.986  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.986  5659  5705 I jxcore-log: 
,10-12 06:51:43.987  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.987  5659  5705 I jxcore-log: 
,10-12 06:51:43.992  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.992  5659  5705 I jxcore-log: 
,10-12 06:51:43.992  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.992  5659  5705 I jxcore-log: 
,10-12 06:51:43.993  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.993  5659  5705 I jxcore-log: 
,10-12 06:51:43.994  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.994  5659  5705 I jxcore-log: 
,10-12 06:51:43.995  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.995  5659  5705 I jxcore-log: 
,10-12 06:51:43.995  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.995  5659  5705 I jxcore-log: 
,10-12 06:51:43.997  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:43.997  5659  5705 I jxcore-log: 
,10-12 06:51:43.997  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:43.997  5659  5705 I jxcore-log: 
,10-12 06:51:43.998  5659  5705 I jxcore-log: 2016-10-12 10:51:43 - DEBUG createNativeListener: 'new mux'
10-12 06:51:43.998  5659  5705 I jxcore-log: 
,10-12 06:51:44.052  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.052  5659  5705 I jxcore-log: 
,10-12 06:51:44.054  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.054  5659  5705 I jxcore-log: 
,10-12 06:51:44.056  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.056  5659  5705 I jxcore-log: 
,10-12 06:51:44.057  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.057  5659  5705 I jxcore-log: 
,10-12 06:51:44.058  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.058  5659  5705 I jxcore-log: 
,10-12 06:51:44.059  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.059  5659  5705 I jxcore-log: 
,10-12 06:51:44.060  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.060  5659  5705 I jxcore-log: 
,10-12 06:51:44.061  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.061  5659  5705 I jxcore-log: 
,10-12 06:51:44.062  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.062  5659  5705 I jxcore-log: 
,10-12 06:51:44.063  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.063  5659  5705 I jxcore-log: 
,10-12 06:51:44.064  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.064  5659  5705 I jxcore-log: 
,10-12 06:51:44.065  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.065  5659  5705 I jxcore-log: 
,10-12 06:51:44.066  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.066  5659  5705 I jxcore-log: 
10-12 06:51:44.067  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.067  5659  5705 I jxcore-log: 
,10-12 06:51:44.067  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.067  5659  5705 I jxcore-log: 
10-12 06:51:44.068  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.068  5659  5705 I jxcore-log: 
,10-12 06:51:44.070  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.070  5659  5705 I jxcore-log: 
,10-12 06:51:44.071  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.071  5659  5705 I jxcore-log: 
10-12 06:51:44.071  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.071  5659  5705 I jxcore-log: 
,10-12 06:51:44.072  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.072  5659  5705 I jxcore-log: 
,10-12 06:51:44.073  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.073  5659  5705 I jxcore-log: 
10-12 06:51:44.074  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.074  5659  5705 I jxcore-log: 
,10-12 06:51:44.074  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.074  5659  5705 I jxcore-log: 
,10-12 06:51:44.075  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.075  5659  5705 I jxcore-log: 
,10-12 06:51:44.076  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.076  5659  5705 I jxcore-log: 
,10-12 06:51:44.077  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.077  5659  5705 I jxcore-log: 
,10-12 06:51:44.078  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.078  5659  5705 I jxcore-log: 
,10-12 06:51:44.079  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.079  5659  5705 I jxcore-log: 
10-12 06:51:44.079  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.079  5659  5705 I jxcore-log: 
,10-12 06:51:44.080  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.080  5659  5705 I jxcore-log: 
10-12 06:51:44.081  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.081  5659  5705 I jxcore-log: 
,10-12 06:51:44.081  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.081  5659  5705 I jxcore-log: 
,10-12 06:51:44.082  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.082  5659  5705 I jxcore-log: 
,10-12 06:51:44.083  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.083  5659  5705 I jxcore-log: 
,10-12 06:51:44.083  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.083  5659  5705 I jxcore-log: 
10-12 06:51:44.084  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.084  5659  5705 I jxcore-log: 
,10-12 06:51:44.085  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.085  5659  5705 I jxcore-log: 
10-12 06:51:44.086  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.086  5659  5705 I jxcore-log: 
,10-12 06:51:44.086  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.086  5659  5705 I jxcore-log: 
,10-12 06:51:44.087  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.087  5659  5705 I jxcore-log: 
,10-12 06:51:44.088  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.088  5659  5705 I jxcore-log: 
,10-12 06:51:44.088  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.088  5659  5705 I jxcore-log: 
10-12 06:51:44.089  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.089  5659  5705 I jxcore-log: 
,10-12 06:51:44.090  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.090  5659  5705 I jxcore-log: 
,10-12 06:51:44.090  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.090  5659  5705 I jxcore-log: 
10-12 06:51:44.091  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.091  5659  5705 I jxcore-log: 
,10-12 06:51:44.091  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.091  5659  5705 I jxcore-log: 
10-12 06:51:44.092  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.092  5659  5705 I jxcore-log: 
,10-12 06:51:44.098  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.098  5659  5705 I jxcore-log: 
,10-12 06:51:44.099  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.099  5659  5705 I jxcore-log: 
,10-12 06:51:44.099  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.099  5659  5705 I jxcore-log: 
,10-12 06:51:44.100  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.100  5659  5705 I jxcore-log: 
10-12 06:51:44.101  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.101  5659  5705 I jxcore-log: 
,10-12 06:51:44.102  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.102  5659  5705 I jxcore-log: 
,10-12 06:51:44.102  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.102  5659  5705 I jxcore-log: 
,10-12 06:51:44.103  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.103  5659  5705 I jxcore-log: 
10-12 06:51:44.104  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.104  5659  5705 I jxcore-log: 
,10-12 06:51:44.105  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.105  5659  5705 I jxcore-log: 
,10-12 06:51:44.105  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.105  5659  5705 I jxcore-log: 
,10-12 06:51:44.106  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.106  5659  5705 I jxcore-log: 
10-12 06:51:44.107  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.107  5659  5705 I jxcore-log: 
,10-12 06:51:44.107  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.107  5659  5705 I jxcore-log: 
,10-12 06:51:44.108  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.108  5659  5705 I jxcore-log: 
,10-12 06:51:44.109  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.109  5659  5705 I jxcore-log: 
,10-12 06:51:44.109  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.109  5659  5705 I jxcore-log: 
,10-12 06:51:44.110  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.110  5659  5705 I jxcore-log: 
,10-12 06:51:44.111  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.111  5659  5705 I jxcore-log: 
,10-12 06:51:44.112  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.112  5659  5705 I jxcore-log: 
,10-12 06:51:44.112  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.112  5659  5705 I jxcore-log: 
10-12 06:51:44.113  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.113  5659  5705 I jxcore-log: 
,10-12 06:51:44.113  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.113  5659  5705 I jxcore-log: 
,10-12 06:51:44.114  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.114  5659  5705 I jxcore-log: 
,10-12 06:51:44.115  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.115  5659  5705 I jxcore-log: 
,10-12 06:51:44.116  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.116  5659  5705 I jxcore-log: 
10-12 06:51:44.116  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.116  5659  5705 I jxcore-log: 
,10-12 06:51:44.117  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.117  5659  5705 I jxcore-log: 
,10-12 06:51:44.120  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.120  5659  5705 I jxcore-log: 
,10-12 06:51:44.121  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.121  5659  5705 I jxcore-log: 
,10-12 06:51:44.122  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:44.122  5659  5705 I jxcore-log: 
,10-12 06:51:44.122  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:44.122  5659  5705 I jxcore-log: 
,10-12 06:51:44.167  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.167  5659  5705 I jxcore-log: 
,10-12 06:51:44.169  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.169  5659  5705 I jxcore-log: 
,10-12 06:51:44.169  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.169  5659  5705 I jxcore-log: 
,10-12 06:51:44.170  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.170  5659  5705 I jxcore-log: 
10-12 06:51:44.171  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.171  5659  5705 I jxcore-log: 
,10-12 06:51:44.171  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.171  5659  5705 I jxcore-log: 
10-12 06:51:44.172  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.172  5659  5705 I jxcore-log: 
,10-12 06:51:44.172  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.172  5659  5705 I jxcore-log: 
10-12 06:51:44.173  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.173  5659  5705 I jxcore-log: 
,10-12 06:51:44.173  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.173  5659  5705 I jxcore-log: 
,10-12 06:51:44.173  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.173  5659  5705 I jxcore-log: 
10-12 06:51:44.174  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.174  5659  5705 I jxcore-log: 
,10-12 06:51:44.174  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.174  5659  5705 I jxcore-log: 
10-12 06:51:44.175  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.175  5659  5705 I jxcore-log: 
,10-12 06:51:44.175  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.175  5659  5705 I jxcore-log: 
10-12 06:51:44.176  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.176  5659  5705 I jxcore-log: 
,10-12 06:51:44.176  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.176  5659  5705 I jxcore-log: 
10-12 06:51:44.177  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.177  5659  5705 I jxcore-log: 
10-12 06:51:44.177  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.177  5659  5705 I jxcore-log: 
,10-12 06:51:44.178  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.178  5659  5705 I jxcore-log: 
,10-12 06:51:44.178  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.178  5659  5705 I jxcore-log: 
10-12 06:51:44.179  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.179  5659  5705 I jxcore-log: 
10-12 06:51:44.179  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.179  5659  5705 I jxcore-log: 
,10-12 06:51:44.179  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.179  5659  5705 I jxcore-log: 
10-12 06:51:44.180  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.180  5659  5705 I jxcore-log: 
,10-12 06:51:44.181  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.181  5659  5705 I jxcore-log: 
10-12 06:51:44.181  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.181  5659  5705 I jxcore-log: 
,10-12 06:51:44.181  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.181  5659  5705 I jxcore-log: 
10-12 06:51:44.182  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.182  5659  5705 I jxcore-log: 
10-12 06:51:44.182  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.182  5659  5705 I jxcore-log: 
10-12 06:51:44.183  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.183  5659  5705 I jxcore-log: 
,10-12 06:51:44.183  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.183  5659  5705 I jxcore-log: 
10-12 06:51:44.184  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.184  5659  5705 I jxcore-log: 
,10-12 06:51:44.184  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.184  5659  5705 I jxcore-log: 
10-12 06:51:44.184  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.184  5659  5705 I jxcore-log: 
,10-12 06:51:44.185  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.185  5659  5705 I jxcore-log: 
10-12 06:51:44.185  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.185  5659  5705 I jxcore-log: 
10-12 06:51:44.186  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.186  5659  5705 I jxcore-log: 
,10-12 06:51:44.186  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.186  5659  5705 I jxcore-log: 
10-12 06:51:44.186  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.186  5659  5705 I jxcore-log: 
,10-12 06:51:44.187  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.187  5659  5705 I jxcore-log: 
10-12 06:51:44.187  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.187  5659  5705 I jxcore-log: 
,10-12 06:51:44.188  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.188  5659  5705 I jxcore-log: 
10-12 06:51:44.188  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.188  5659  5705 I jxcore-log: 
,10-12 06:51:44.190  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.190  5659  5705 I jxcore-log: 
10-12 06:51:44.190  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.190  5659  5705 I jxcore-log: 
10-12 06:51:44.191  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.191  5659  5705 I jxcore-log: 
,10-12 06:51:44.191  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.191  5659  5705 I jxcore-log: 
,10-12 06:51:44.193  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:44.193  5659  5705 I jxcore-log: 
,10-12 06:51:44.194  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'mux close'
10-12 06:51:44.194  5659  5705 I jxcore-log: 
,10-12 06:51:44.196  5659  5705 I jxcore-log: ok 28 native server is nulled out
10-12 06:51:44.196  5659  5705 I jxcore-log: 
,10-12 06:51:44.196  5659  5705 I jxcore-log: ok 29 native server should be closed
10-12 06:51:44.196  5659  5705 I jxcore-log: 
10-12 06:51:44.197  5659  5705 I jxcore-log: ok 30 incoming has been removed
10-12 06:51:44.197  5659  5705 I jxcore-log: 
10-12 06:51:44.197  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.197  5659  5705 I jxcore-log: 
,10-12 06:51:44.198  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.198  5659  5705 I jxcore-log: 
10-12 06:51:44.198  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.198  5659  5705 I jxcore-log: 
10-12 06:51:44.199  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.199  5659  5705 I jxcore-log: 
10-12 06:51:44.199  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.199  5659  5705 I jxcore-log: 
,10-12 06:51:44.199  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.199  5659  5705 I jxcore-log: 
10-12 06:51:44.199  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.199  5659  5705 I jxcore-log: 
10-12 06:51:44.199  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.199  5659  5705 I jxcore-log: 
10-12 06:51:44.200  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.200  5659  5705 I jxcore-log: 
10-12 06:51:44.200  5659  5705 I jxcore-log: 2016-10-12 10:51:44 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:44.200  5659  5705 I jxcore-log: 
,10-12 06:51:44.275  5659  5705 I jxcore-log: # teardown
10-12 06:51:44.275  5659  5705 I jxcore-log: 
,10-12 06:51:44.359  5659  5705 I jxcore-log: # setup
10-12 06:51:44.359  5659  5705 I jxcore-log: 
,10-12 06:51:46.081  5659  5705 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-12 06:51:46.081  5659  5705 I jxcore-log: 
,10-12 06:51:46.121  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:46.121  5659  5705 I jxcore-log: 
,10-12 06:51:46.127  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'listening 47201'
10-12 06:51:46.127  5659  5705 I jxcore-log: 
,10-12 06:51:46.135  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:46.135  5659  5705 I jxcore-log: 
,10-12 06:51:46.137  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:46.137  5659  5705 I jxcore-log: 
,10-12 06:51:46.139  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new mux'
10-12 06:51:46.139  5659  5705 I jxcore-log: 
,10-12 06:51:46.148  5659  5705 I jxcore-log: ok 31 we should not have gotten an error
10-12 06:51:46.148  5659  5705 I jxcore-log: 
,10-12 06:51:46.152  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:46.152  5659  5705 I jxcore-log: 
,10-12 06:51:46.155  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:46.155  5659  5705 I jxcore-log: 
,10-12 06:51:46.164  5659  5705 I jxcore-log: ok 32 Buffers are identical
10-12 06:51:46.164  5659  5705 I jxcore-log: 
,10-12 06:51:46.165  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:46.165  5659  5705 I jxcore-log: 
,10-12 06:51:46.167  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'mux close'
10-12 06:51:46.167  5659  5705 I jxcore-log: 
,10-12 06:51:46.180  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:46.180  5659  5705 I jxcore-log: 
,10-12 06:51:46.181  5659  5705 I jxcore-log: ok 33 server should be fine
10-12 06:51:46.181  5659  5705 I jxcore-log: 
10-12 06:51:46.181  5659  5705 I jxcore-log: ok 34 server should be open
10-12 06:51:46.181  5659  5705 I jxcore-log: 
10-12 06:51:46.181  5659  5705 I jxcore-log: ok 35 incoming has been removed
10-12 06:51:46.181  5659  5705 I jxcore-log: 
10-12 06:51:46.182  5659  5705 I jxcore-log: ok 36 The mux object should be closed
10-12 06:51:46.182  5659  5705 I jxcore-log: 
10-12 06:51:46.182  5659  5705 I jxcore-log: ok 37 The mux stream should be closed
10-12 06:51:46.182  5659  5705 I jxcore-log: 
,10-12 06:51:46.189  5659  5705 I jxcore-log: # teardown
10-12 06:51:46.189  5659  5705 I jxcore-log: 
,10-12 06:51:46.269  5659  5705 I jxcore-log: # setup
10-12 06:51:46.269  5659  5705 I jxcore-log: 
,10-12 06:51:46.328  5659  5705 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-12 06:51:46.328  5659  5705 I jxcore-log: 
,10-12 06:51:46.369  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'creating native server'
10-12 06:51:46.369  5659  5705 I jxcore-log: 
,10-12 06:51:46.373  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'listening 42392'
10-12 06:51:46.373  5659  5705 I jxcore-log: 
,10-12 06:51:46.380  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new incoming socket'
10-12 06:51:46.380  5659  5705 I jxcore-log: 
,10-12 06:51:46.382  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'creating incoming mux'
10-12 06:51:46.382  5659  5705 I jxcore-log: 
,10-12 06:51:46.384  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new mux'
10-12 06:51:46.384  5659  5705 I jxcore-log: 
,10-12 06:51:46.391  5659  5705 I jxcore-log: ok 38 we should not have gotten an error
10-12 06:51:46.391  5659  5705 I jxcore-log: 
,10-12 06:51:46.395  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new stream: '
10-12 06:51:46.395  5659  5705 I jxcore-log: 
,10-12 06:51:46.398  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'new outgoing socket'
10-12 06:51:46.398  5659  5705 I jxcore-log: 
,10-12 06:51:46.405  5659  5705 I jxcore-log: ok 39 Buffers are identical
10-12 06:51:46.405  5659  5705 I jxcore-log: 
,10-12 06:51:46.410  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'incoming socket timeout'
10-12 06:51:46.410  5659  5705 I jxcore-log: 
,10-12 06:51:46.411  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'stream close:'
10-12 06:51:46.411  5659  5705 I jxcore-log: 
,10-12 06:51:46.413  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'mux close'
10-12 06:51:46.413  5659  5705 I jxcore-log: 
,10-12 06:51:46.418  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG createNativeListener: 'incoming socket close'
10-12 06:51:46.418  5659  5705 I jxcore-log: 
10-12 06:51:46.419  5659  5705 I jxcore-log: ok 40 server should be fine
10-12 06:51:46.419  5659  5705 I jxcore-log: 
10-12 06:51:46.419  5659  5705 I jxcore-log: ok 41 server should be open
10-12 06:51:46.419  5659  5705 I jxcore-log: 
10-12 06:51:46.419  5659  5705 I jxcore-log: ok 42 incoming has been removed
10-12 06:51:46.419  5659  5705 I jxcore-log: 
10-12 06:51:46.420  5659  5705 I jxcore-log: ok 43 The mux object should be closed
10-12 06:51:46.420  5659  5705 I jxcore-log: 
10-12 06:51:46.420  5659  5705 I jxcore-log: ok 44 The mux stream should be closed
10-12 06:51:46.420  5659  5705 I jxcore-log: 
,10-12 06:51:46.427  5659  5705 I jxcore-log: # teardown
10-12 06:51:46.427  5659  5705 I jxcore-log: 
,10-12 06:51:46.454  5659  5705 I jxcore-log: # setup
10-12 06:51:46.454  5659  5705 I jxcore-log: 
,10-12 06:51:46.483  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-12 06:51:46.483  5659  5705 I jxcore-log: 
,10-12 06:51:46.672  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-12 06:51:46.672  5659  5705 I jxcore-log: 
,10-12 06:51:46.673  5659  5705 I jxcore-log: ok 45 Got right error
10-12 06:51:46.673  5659  5705 I jxcore-log: 
,10-12 06:51:46.678  5659  5705 I jxcore-log: # teardown
10-12 06:51:46.678  5659  5705 I jxcore-log: 
,10-12 06:51:46.697  5659  5705 I jxcore-log: # setup
10-12 06:51:46.697  5659  5705 I jxcore-log: 
,10-12 06:51:46.733  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-12 06:51:46.733  5659  5705 I jxcore-log: 
,10-12 06:51:46.842  5659  5705 I jxcore-log: 2016-10-12 10:51:46 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-12 06:51:46.842  5659  5705 I jxcore-log: 
,10-12 06:51:46.844  5659  5705 I jxcore-log: ok 46 Got socket hang up
10-12 06:51:46.844  5659  5705 I jxcore-log: 
,10-12 06:51:46.850  5659  5705 I jxcore-log: # teardown
10-12 06:51:46.850  5659  5705 I jxcore-log: 
,10-12 06:51:46.879  5659  5705 I jxcore-log: # setup
10-12 06:51:46.879  5659  5705 I jxcore-log: 
,10-12 06:51:46.923  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-12 06:51:46.923  5659  5705 I jxcore-log: 
,10-12 06:51:47.117  5659  5705 I jxcore-log: 2016-10-12 10:51:47 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-12 06:51:47.117  5659  5705 I jxcore-log: 
,10-12 06:51:47.118  5659  5705 I jxcore-log: ok 47 Got 500 as expected
10-12 06:51:47.118  5659  5705 I jxcore-log: 
,10-12 06:51:47.126  5659  5705 I jxcore-log: # teardown
10-12 06:51:47.126  5659  5705 I jxcore-log: 
,10-12 06:51:47.157  5659  5705 I jxcore-log: # setup
10-12 06:51:47.157  5659  5705 I jxcore-log: 
,10-12 06:51:47.204  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-12 06:51:47.204  5659  5705 I jxcore-log: 
,10-12 06:51:48.598  5659  5705 I jxcore-log: ok 48 should be equal
10-12 06:51:48.598  5659  5705 I jxcore-log: 
,10-12 06:51:48.599  5659  5705 I jxcore-log: ok 49 revs are equal
10-12 06:51:48.599  5659  5705 I jxcore-log: 
,10-12 06:51:48.605  5659  5705 I jxcore-log: # teardown
10-12 06:51:48.605  5659  5705 I jxcore-log: 
,10-12 06:51:48.642  5659  5705 I jxcore-log: # setup
10-12 06:51:48.642  5659  5705 I jxcore-log: 
,10-12 06:51:49.772  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-12 06:51:49.772  5659  5705 I jxcore-log: 
,10-12 06:51:50.613  5659  5705 I jxcore-log: ok 50 should be equal
10-12 06:51:50.613  5659  5705 I jxcore-log: 
,10-12 06:51:50.613  5659  5705 I jxcore-log: ok 51 revs are equal
10-12 06:51:50.613  5659  5705 I jxcore-log: 
,10-12 06:51:50.620  5659  5705 I jxcore-log: # teardown
10-12 06:51:50.620  5659  5705 I jxcore-log: 
,10-12 06:51:50.673  5659  5705 I jxcore-log: # setup
10-12 06:51:50.673  5659  5705 I jxcore-log: 
,10-12 06:51:51.197  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-12 06:51:51.197  5659  5705 I jxcore-log: 
,10-12 06:51:52.474  5659  5705 I jxcore-log: ok 52 should be equal
10-12 06:51:52.474  5659  5705 I jxcore-log: 
,10-12 06:51:52.475  5659  5705 I jxcore-log: ok 53 revs are equal
10-12 06:51:52.475  5659  5705 I jxcore-log: 
,10-12 06:51:52.645  5659  5705 I jxcore-log: ok 54 should be equal
10-12 06:51:52.645  5659  5705 I jxcore-log: 
,10-12 06:51:52.646  5659  5705 I jxcore-log: ok 55 revs are equal
10-12 06:51:52.646  5659  5705 I jxcore-log: 
,10-12 06:51:52.843  5659  5705 I jxcore-log: ok 56 should be equal
10-12 06:51:52.843  5659  5705 I jxcore-log: 
,10-12 06:51:52.844  5659  5705 I jxcore-log: ok 57 revs are equal
10-12 06:51:52.844  5659  5705 I jxcore-log: 
,10-12 06:51:52.853  5659  5705 I jxcore-log: # teardown
10-12 06:51:52.853  5659  5705 I jxcore-log: 
,10-12 06:51:52.910  5659  5705 I jxcore-log: # setup
10-12 06:51:52.910  5659  5705 I jxcore-log: 
,10-12 06:51:52.968  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-12 06:51:52.968  5659  5705 I jxcore-log: 
,10-12 06:51:53.785  5659  5705 I jxcore-log: 2016-10-12 10:51:53 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-12 06:51:53.785  5659  5705 I jxcore-log: 
,10-12 06:51:53.786  5659  5705 I jxcore-log: ok 58 Our rev is old so we should fail
10-12 06:51:53.786  5659  5705 I jxcore-log: 
,10-12 06:51:53.809  5659  5705 I jxcore-log: # teardown
10-12 06:51:53.809  5659  5705 I jxcore-log: 
,10-12 06:51:53.850  5659  5705 I jxcore-log: # setup
10-12 06:51:53.850  5659  5705 I jxcore-log: 
,10-12 06:51:53.890  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-12 06:51:53.890  5659  5705 I jxcore-log: 
,10-12 06:51:53.994  5659  5705 I jxcore-log: ok 59 confirm stop caused failure
10-12 06:51:53.994  5659  5705 I jxcore-log: 
,10-12 06:51:54.003  5659  5705 I jxcore-log: # teardown
10-12 06:51:54.003  5659  5705 I jxcore-log: 
,10-12 06:51:54.034  5659  5705 I jxcore-log: # setup
10-12 06:51:54.034  5659  5705 I jxcore-log: 
,10-12 06:51:54.064  5659  5705 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-12 06:51:54.064  5659  5705 I jxcore-log: 
,10-12 06:51:54.503  5659  5705 I jxcore-log: 2016-10-12 10:51:54 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-12 06:51:54.503  5659  5705 I jxcore-log: 
10-12 06:51:54.504  5659  5705 I jxcore-log: ok 60 stop caused us to fail
10-12 06:51:54.504  5659  5705 I jxcore-log: 
10-12 06:51:54.504  5659  5705 I jxcore-log: ok 61 We specifically failed on a stop before put
10-12 06:51:54.504  5659  5705 I jxcore-log: 
,10-12 06:51:54.519  5659  5705 I jxcore-log: # teardown
10-12 06:51:54.519  5659  5705 I jxcore-log: 
,10-12 06:51:54.601  5659  5705 I jxcore-log: # setup
10-12 06:51:54.601  5659  5705 I jxcore-log: 
,10-12 06:51:54.646  5659  5705 I jxcore-log: # #update - fail if stop is called
10-12 06:51:54.646  5659  5705 I jxcore-log: 
,10-12 06:51:54.758  5659  5705 I jxcore-log: ok 62 failed due to stop
10-12 06:51:54.758  5659  5705 I jxcore-log: 
,10-12 06:51:54.760  5659  5705 I jxcore-log: ok 63 failed due to stop
10-12 06:51:54.760  5659  5705 I jxcore-log: 
,10-12 06:51:54.771  5659  5705 I jxcore-log: # teardown
10-12 06:51:54.771  5659  5705 I jxcore-log: 
,10-12 06:51:54.813  5659  5705 I jxcore-log: # setup
10-12 06:51:54.813  5659  5705 I jxcore-log: 
,10-12 06:51:54.887  5659  5705 I jxcore-log: # #update - set seq for first time
10-12 06:51:54.887  5659  5705 I jxcore-log: 
,10-12 06:51:55.517  5659  5705 I jxcore-log: ok 64 should be equal
10-12 06:51:55.517  5659  5705 I jxcore-log: 
,10-12 06:51:55.540  5659  5705 I jxcore-log: # teardown
10-12 06:51:55.540  5659  5705 I jxcore-log: 
,10-12 06:51:55.603  5659  5705 I jxcore-log: # setup
10-12 06:51:55.603  5659  5705 I jxcore-log: 
,10-12 06:51:55.620  5659  5705 I jxcore-log: # #update - Fail on bad seq value,
10-12 06:51:55.620  5659  5705 I jxcore-log: 
,10-12 06:51:55.924   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:56.180  5659  5705 I jxcore-log: 2016-10-12 10:51:56 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-12 06:51:56.180  5659  5705 I jxcore-log: 
,10-12 06:51:56.182  5659  5705 I jxcore-log: ok 65 Expected bad seq error
10-12 06:51:56.182  5659  5705 I jxcore-log: 
,10-12 06:51:56.202  5659  5705 I jxcore-log: # teardown
10-12 06:51:56.202  5659  5705 I jxcore-log: 
,10-12 06:51:56.266  5659  5705 I jxcore-log: # setup
10-12 06:51:56.266  5659  5705 I jxcore-log: 
,10-12 06:51:56.300  5659  5705 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-12 06:51:56.300  5659  5705 I jxcore-log: 
,10-12 06:51:56.394  5659  5705 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-12 06:51:56.394  5659  5705 E jxcore-log: 
,10-12 06:51:56.396  5659  5705 E jxcore-log: Trace: 
10-12 06:51:56.396  5659  5705 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-12 06:51:56.396  5659  5705 E jxcore-log:     at addListener@events.js:140:1
10-12 06:51:56.396  5659  5705 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
10-12 06:51:56.396  5659  5705 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-12 06:51:56.396  5659  5705 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-12 06:51:56.396  5659  5705 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-12 06:51:56.396  5659  5705 E jxcore-log: 
,10-12 06:51:56.925   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:57.199  5659  5705 I jxcore-log: ok 66 Different promises
10-12 06:51:57.199  5659  5705 I jxcore-log: 
,10-12 06:51:57.200  5659  5705 I jxcore-log: ok 67 Timer was cancelled
10-12 06:51:57.200  5659  5705 I jxcore-log: 
,10-12 06:51:57.385  5659  5705 I jxcore-log: ok 68 should be equal
10-12 06:51:57.385  5659  5705 I jxcore-log: 
,10-12 06:51:57.410  5659  5705 I jxcore-log: # teardown
10-12 06:51:57.410  5659  5705 I jxcore-log: 
,10-12 06:51:57.926   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:57.935   925  2968 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 06:51:58.928   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:51:59.026  5659  5705 I jxcore-log: # setup
10-12 06:51:59.026  5659  5705 I jxcore-log: 
,10-12 06:51:59.929   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:00.324  5659  5705 I jxcore-log: # #update - do we wait for blocked update
10-12 06:52:00.324  5659  5705 I jxcore-log: 
,10-12 06:52:00.930   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-12 06:52:01.211  5659  5705 I jxcore-log: ok 69 One go and one blocked
10-12 06:52:01.211  5659  5705 I jxcore-log: 
,10-12 06:52:01.212  5659  5705 I jxcore-log: ok 70 All blocked
10-12 06:52:01.212  5659  5705 I jxcore-log: 
10-12 06:52:01.212  5659  5705 I jxcore-log: ok 71 Still blocked
10-12 06:52:01.212  5659  5705 I jxcore-log: 
,10-12 06:52:01.226  5659  5705 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-12 06:52:01.226  5659  5705 E jxcore-log: 
,10-12 06:52:01.227  5659  5705 E jxcore-log: Trace: 
10-12 06:52:01.227  5659  5705 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-12 06:52:01.227  5659  5705 E jxcore-log:     at addListener@events.js:140:1
10-12 06:52:01.227  5659  5705 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
10-12 06:52:01.227  5659  5705 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-12 06:52:01.227  5659  5705 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-12 06:52:01.227  5659  5705 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-12 06:52:01.227  5659  5705 E jxcore-log: 
,10-12 06:52:01.913  5659  5705 I jxcore-log: ok 72 should be equal
10-12 06:52:01.913  5659  5705 I jxcore-log: 
,10-12 06:52:01.950  5659  5705 I jxcore-log: # teardown
10-12 06:52:01.950  5659  5705 I jxcore-log: 
,10-12 06:52:02.514  5659  5705 I jxcore-log: # setup
10-12 06:52:02.514  5659  5705 I jxcore-log: 
,10-12 06:52:04.026  5659  5705 I jxcore-log: # #update - test that we wait long enough
10-12 06:52:04.026  5659  5705 I jxcore-log: 
,10-12 06:52:05.599  5659  5705 I jxcore-log: ok 73 We waited long enough
10-12 06:52:05.599  5659  5705 I jxcore-log: 
,10-12 06:52:05.737  5659  5705 I jxcore-log: ok 74 should be equal
10-12 06:52:05.737  5659  5705 I jxcore-log: 
,10-12 06:52:05.761  5659  5705 I jxcore-log: # teardown
10-12 06:52:05.761  5659  5705 I jxcore-log: 
,10-12 06:52:05.933   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:06.281  5659  5705 I jxcore-log: # setup
10-12 06:52:06.281  5659  5705 I jxcore-log: 
,10-12 06:52:06.405  5659  5705 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-12 06:52:06.405  5659  5705 I jxcore-log: 
,10-12 06:52:06.934   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:07.036  5659  5705 I jxcore-log: ok 75 Should have gotten same timer promise
10-12 06:52:07.036  5659  5705 I jxcore-log: 
,10-12 06:52:07.039  5659  5705 I jxcore-log: ok 76 Still same timer promise
10-12 06:52:07.039  5659  5705 I jxcore-log: 
,10-12 06:52:07.614  5659  5705 I jxcore-log: ok 77 We waited long enough
10-12 06:52:07.614  5659  5705 I jxcore-log: 
,10-12 06:52:07.776  5659  5705 I jxcore-log: ok 78 should be equal
10-12 06:52:07.776  5659  5705 I jxcore-log: 
,10-12 06:52:07.829  5659  5705 I jxcore-log: # teardown
10-12 06:52:07.829  5659  5705 I jxcore-log: 
,10-12 06:52:07.935   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:08.936   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:08.947  5659  5705 I jxcore-log: # setup
10-12 06:52:08.947  5659  5705 I jxcore-log: 
,10-12 06:52:09.690  5659  5705 I jxcore-log: # Coordinated seq test
10-12 06:52:09.690  5659  5705 I jxcore-log: 
,10-12 06:52:09.937   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:10.401  5659  5705 I jxcore-log: 2016-10-12 10:52:10 - DEBUG thaliWifiInfrastructure: 'listening 43145'
10-12 06:52:10.401  5659  5705 I jxcore-log: 
,10-12 06:52:10.938   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-12 06:52:13.166  5659  5705 I jxcore-log: ok 79 should be equal
10-12 06:52:13.166  5659  5705 I jxcore-log: 
,10-12 06:52:14.882  5659  5705 I jxcore-log: ok 80 should be equal
10-12 06:52:14.882  5659  5705 I jxcore-log: 
,10-12 06:52:14.925  5659  5705 I jxcore-log: # teardown
10-12 06:52:14.925  5659  5705 I jxcore-log: 
,10-12 06:52:20.940   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:21.941   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:22.943   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:23.944   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:24.946   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:25.947   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-12 06:52:37.939   925  2968 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 06:52:40.948   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:41.949   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:42.951   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:43.952   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:44.953   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:52:45.954   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-12 06:52:57.340   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 06:52:57.940   925  2968 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-12 06:53:00.368   925  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-12 06:53:05.956   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:53:06.957   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:53:07.959   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:53:08.960   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:53:09.961   548   548 I ServiceManager: Waiting for service AtCmdFwd...
,10-12 06:53:10.962   548   548 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-12 06:53:14.944  5659  5705 I jxcore-log: 2016-10-12 10:53:14 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-12 06:53:14.944  5659  5705 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-12 06:53:14.944  5659  5705 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-12 06:53:14.944  5659  5705 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-12 06:53:14.944  5659  5705 I jxcore-log:     at $9@timers.js:120:1
10-12 06:53:14.944  5659  5705 I jxcore-log: ''
10-12 06:53:14.944  5659  5705 I jxcore-log: 
,10-12 06:53:14.947  5659  5705 I jxcore-log: 2016-10-12 10:53:14 - DEBUG CoordinatedClient: 'test client failed'
10-12 06:53:14.947  5659  5705 I jxcore-log: 
,10-12 06:53:14.960  5659  5705 I jxcore-log: 2016-10-12 10:53:14 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-12 06:53:14.960  5659  5705 I jxcore-log: 
,10-12 06:53:14.965  5659  5705 I jxcore-log: 2016-10-12 10:53:14 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-12 06:53:14.965  5659  5705 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-12 06:53:14.965  5659  5705 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-12 06:53:14.965  5659  5705 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-12 06:53:14.965  5659  5705 I jxcore-log:     at $9@timers.js:120:1
10-12 06:53:14.965  5659  5705 I jxcore-log: ''
10-12 06:53:14.965  5659  5705 I jxcore-log: 
,10-12 06:53:14.968  5659  5705 I jxcore-log: 2016-10-12 10:53:14 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-12 06:53:14.968  5659  5705 I jxcore-log: 
,10-12 06:53:15.041   925  2958 W InputDispatcher: channel '3124ecc com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-12 06:53:15.041   925  2958 E InputDispatcher: channel '3124ecc com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-12 06:53:15.056   925  3851 I WindowState: WIN DEATH: Window{3124ecc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-12 06:53:15.056   925  3851 W InputDispatcher: Attempted to unregister already unregistered input channel '3124ecc com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-12 06:53:15.058   925  3173 D GraphicsStats: Buffer count: 2
,10-12 06:53:15.057   925  2978 D WifiService: Client connection lost with reason: 4
,10-12 06:53:15.069   526   526 I Zygote  : Process 5659 exited cleanly (139)
,10-12 06:53:15.073   925   935 I ActivityManager: Process com.test.thalitest (pid 5659) has died
,10-12 06:53:15.095   925   935 I ActivityManager: Start proc 6010:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-12 06:53:15.427   925  3791 I WindowManager: Screenshot max retries 4 of Token{8476abe ActivityRecord{6ef2d79 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{c177f84 u0 Starting com.test.thalitest} drawState=4
,10-12 06:53:15.500  6010  6010 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-12 06:53:15.520  6010  6010 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-12 06:53:15.525  6010  6010 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3107-3110)
,10-12 06:53:15.525  6010  6010 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 06:53:15.533  6010  6010 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fa6433e}
10-12 06:53:15.534  6010  6010 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-12 06:53:15.534  6010  6010 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-12 06:53:15.537  6010  6010 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-12 06:53:15.538  6010  6010 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-12 06:53:15.548  6010  6010 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-12 06:53:15.555  6008  6008 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-12 06:53:15.556  6010  6010 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 06:53:15.556  6010  6010 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-12 06:53:15.556  6010  6010 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-12 06:53:15.556  6010  6010 I Adreno  : Build Date                       : 12/06/15
10-12 06:53:15.556  6010  6010 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-12 06:53:15.556  6010  6010 I Adreno  : Local Branch                     : mybranch17112971
10-12 06:53:15.556  6010  6010 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-12 06:53:15.556  6010  6010 I Adreno  : Remote Branch                    : NONE
10-12 06:53:15.556  6010  6010 I Adreno  : Reconstruct Branch               : NOTHING
,10-12 06:53:15.570  6008  6008 D AndroidRuntime: CheckJNI is OFF
,10-12 06:53:15.588   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fece325:true
,10-12 06:53:15.595  6008  6008 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-12 06:53:15.598   408   408 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31892]" dev="sockfs" ino=31892 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-12 06:53:15.598   408   408 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31892]" dev="sockfs" ino=31892 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-12 06:53:15.611  6010  6010 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-12 06:53:15.619  6010  6010 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-12 06:53:15.621  6008  6008 I Radio-JNI: register_android_hardware_Radio DONE
,10-12 06:53:15.636  6008  6008 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-12 06:53:15.642   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-12 06:53:15.643   925   938 I ActivityManager: Killing 6010:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-12 06:53:15.784   925   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-12 06:53:15.784   925   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,10-12 06:53:15.786   925   938 E ActivityManager: Failure starting process com.test.thalitest
10-12 06:53:15.786   925   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-12 06:53:15.786   925   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:53:15.786   925   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:15.786   925   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 06:53:15.786   925   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-12 06:53:15.788   925   938 I ActivityManager:   Force finishing activity ActivityRecord{6ef2d79 u0 com.test.thalitest/.MainActivity t2}
,10-12 06:53:15.789   925   949 I art     : Starting a blocking GC Explicit
,10-12 06:53:15.800   925   943 W WindowManager: Failed looking up window
10-12 06:53:15.800   925   943 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@22f2197 does not exist
10-12 06:53:15.800   925   943 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-12 06:53:15.800   925   943 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-12 06:53:15.800   925   943 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-12 06:53:15.800   925   943 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-12 06:53:15.800   925   943 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-12 06:53:15.800   925   943 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-12 06:53:15.800   925   943 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-12 06:53:15.800   925   943 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:53:15.800   925   943 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:15.800   925   943 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 06:53:15.800   925   943 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-12 06:53:15.801   925  3791 W ActivityManager: Spurious death for ProcessRecord{eada838 0:com.test.thalitest/u0a77}, curProc for 6010: null
,10-12 06:53:15.886   925   949 I art     : Explicit concurrent mark sweep GC freed 77005(5MB) AllocSpace objects, 33(1184KB) LOS objects, 33% free, 29MB/43MB, paused 1.795ms total 95.890ms
,10-12 06:53:15.906   925   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-12 06:53:15.911  6008  6008 I art     : System.exit called, status: 0
10-12 06:53:15.911  6008  6008 I AndroidRuntime: VM exiting with result code 0.
,10-12 06:53:15.916   925   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-12 06:53:15.924   925   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-12 06:53:15.928  5911  5911 D BluetoothMapAppObserver: onReceive
10-12 06:53:15.928  5911  5911 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-12 06:53:15.932  4069  4176 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-12 06:53:15.933  3676  3676 I Keyboard.Facilitator: resetDictionaries() : en_US
10-12 06:53:15.941   925  2959 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-12 06:53:15.986  3591  3591 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-12 06:53:15.986  3591  3591 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
10-12 06:53:15.986  3793  3793 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-12 06:53:15.988  1430  1430 W kworker/1:3: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 06:53:15.990  3676  6056 I Keyboard.Facilitator.DecoderInitializer: run()
,10-12 06:53:15.991  1430  1430 W kworker/1:3: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 06:53:15.994   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-12 06:53:15.993  3414  6057 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-12 06:53:15.994  1430  1430 W kworker/1:3: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-12 06:53:16.001  3730  6061 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-12 06:53:16.002  3730  6061 D AccountUtils: Clearing selected account for com.test.thalitest
10-12 06:53:16.002  3830  3944 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-12 06:53:16.013   925   937 E PackageManager: Failed to write settings, restoring backup
10-12 06:53:16.013   925   937 E PackageManager: java.io.IOException: write failed: EROFS (Read-only file system)
10-12 06:53:16.013   925   937 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
10-12 06:53:16.013   925   937 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
10-12 06:53:16.013   925   937 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
10-12 06:53:16.013   925   937 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
10-12 06:53:16.013   925   937 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
10-12 06:53:16.013   925   937 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
10-12 06:53:16.013   925   937 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
10-12 06:53:16.013   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
10-12 06:53:16.013   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-12 06:53:16.013   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-12 06:53:16.013   925   937 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:53:16.013   925   937 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:16.013   925   937 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 06:53:16.013   925   937 E PackageManager: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
10-12 06:53:16.013   925   937 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
10-12 06:53:16.013   925   937 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
10-12 06:53:16.013   925   937 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
10-12 06:53:16.013   925   937 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
10-12 06:53:16.013   925   937 E PackageManager: 	... 12 more
,10-12 06:53:16.014  3676  6056 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
10-12 06:53:16.015   925  3791 I ActivityManager: Start proc 6064:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
10-12 06:53:16.016  3830  3944 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-12 06:53:16.016  3830  3944 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3830
10-12 06:53:16.016  3830  3944 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:16.016  3830  3944 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 06:53:16.016   925   938 E DropBoxManagerService: Can't write: system_server_wtf
10-12 06:53:16.016   925   938 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-12 06:53:16.016   925   938 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 06:53:16.016   925   938 E DropBoxManagerService: 	... 13 more
10-12 06:53:16.014  3676  6056 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
10-12 06:53:16.018   925  6072 E DropBoxManagerService: Can't write: system_app_crash
10-12 06:53:16.018   925  6072 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-12 06:5,3:16.018   925  6072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-12 06:53:16.018   925  6072 E DropBoxManagerService: 	... 5 more
10-12 06:53:16.018  3676  6056 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
10-12 06:53:16.018  3676  6056 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
10-12 06:53:16.019   925   936 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-12 06:53:16.027  3830  3944 I Process : Sending signal. PID: 3830 SIG: 9
,10-12 06:53:16.042  3676  6056 I Decoder : createOrResetDecoder
,10-12 06:53:16.064  3414  3435 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjBDD2129D8) - 
,10-12 06:53:16.064  3414  3435 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-12 06:53:16.064  3414  3435 E AndroidRuntime: Process: android.process.acore, PID: 3414
10-12 06:53:16.064  3414  3435 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:16.064  3414  3435 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 06:53:16.079  3730  6061 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-12 06:53:16.101  3730  6061 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:16.101  3730  6061 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-12 06:53:16.101  3730  6061 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-12 06:53:16.102  3730  6061 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-12 06:53:16.113  3591  3591 I ConfigService: onCreate
,10-12 06:53:16.115  3591  6080 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-12 06:53:16.115  3591  6080 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-12 06:53:16.116  3591  6080 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-12 06:53:16.118  3591  6080 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-12 06:53:16.134  3676  6056 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-12 06:53:16.175  3414  3435 I Process : Sending signal. PID: 3414 SIG: 9
,10-12 06:53:16.179   925   935 D GraphicsStats: Buffer count: 1
,10-12 06:53:16.185   925  3623 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3830) has died
,10-12 06:53:16.186   925  3623 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-12 06:53:16.204  3730  6083 I GMPM-SVC: App measurement is starting up
,10-12 06:53:16.212  3730  6083 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-12 06:53:16.213  3730  6083 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-12 06:53:16.376   383   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
