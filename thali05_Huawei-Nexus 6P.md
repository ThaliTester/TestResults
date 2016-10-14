#### Test 89388695d4fcca1_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-14 10:14:22.622   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
10-14 10:14:22.622   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-14 10:14:23.882  5620  5620 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-14 10:14:23.887  5620  5620 D AndroidRuntime: CheckJNI is OFF
10-14 10:14:23.911  5620  5620 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-14 10:14:23.943  5620  5620 I Radio-JNI: register_android_hardware_Radio DONE
10-14 10:14:23.958  5620  5620 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-14 10:14:23.965   929   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-14 10:14:24.010   929   940 I ActivityManager: Start proc 5629:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-14 10:14:24.015  5620  5620 D AndroidRuntime: Shutting down VM
,10-14 10:14:24.358   929  3571 I WindowManager: Screenshot max retries 4 of Token{7855189 ActivityRecord{fea9490 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{21465a8 u0 Starting com.test.thalitest} drawState=2
,10-14 10:14:24.442  5629  5629 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-14 10:14:24.472  5629  5629 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-14 10:14:24.501  5629  5629 I LibraryLoader: Time to load native libraries: 21 ms (timestamps 1379-1400)
,10-14 10:14:24.501  5629  5629 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-14 10:14:24.530  5629  5629 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9254c0d}
,10-14 10:14:24.530  5629  5629 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-14 10:14:24.531  5629  5629 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-14 10:14:24.534  5629  5629 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-14 10:14:24.535  5629  5629 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-14 10:14:24.577  5629  5629 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-14 10:14:24.586  5629  5629 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-14 10:14:24.586  5629  5629 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-14 10:14:24.586  5629  5629 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-14 10:14:24.586  5629  5629 I Adreno  : Build Date                       : 12/06/15
10-14 10:14:24.586  5629  5629 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-14 10:14:24.586  5629  5629 I Adreno  : Local Branch                     : mybranch17112971
10-14 10:14:24.586  5629  5629 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-14 10:14:24.586  5629  5629 I Adreno  : Remote Branch                    : NONE
10-14 10:14:24.586  5629  5629 I Adreno  : Reconstruct Branch               : NOTHING
,10-14 10:14:24.641   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9fa49f:true
,10-14 10:14:24.673   405   405 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34115]" dev="sockfs" ino=34115 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 10:14:24.673   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34115]" dev="sockfs" ino=34115 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 10:14:24.689  5629  5629 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-14 10:14:24.701  5629  5629 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-14 10:14:24.732  5629  5666 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-14 10:14:24.726   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31498]" dev="sockfs" ino=31498 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-14 10:14:24.726   405   405 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31498]" dev="sockfs" ino=31498 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-14 10:14:24.733  3155  3155 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34126]" dev="sockfs" ino=34126 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-14 10:14:24.733  3155  3155 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[34126]" dev="sockfs" ino=34126 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-14 10:14:24.742  5629  5653 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-14 10:14:24.771  5629  5666 I OpenGLRenderer: Initialized EGL, version 1.4
,10-14 10:14:24.870   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +507ms (total +886ms)
,10-14 10:14:24.908  5629  5629 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5629
,10-14 10:14:25.016  5629  5629 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-14 10:14:25.310  5629  5669 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -584316624
,10-14 10:14:25.315  5629  5669 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-14 10:14:25.315  5629  5669 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-14 10:14:25.315  5629  5669 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-14 10:14:25.315  5629  5669 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-14 10:14:25.315  5629  5669 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-14 10:14:25.315  5629  5669 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ed600b added. We now have 1 listener(s)
,10-14 10:14:25.318  5629  5669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-14 10:14:25.319  5629  5669 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 10:14:25.320  5629  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:14:25.321  5629  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-14 10:14:25.324  5629  5669 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc023a6 added. We now have 1 listener(s)
10-14 10:14:25.324  5629  5669 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:14:25.328   929  2972 D WifiService: New client listening to asynchronous messages
10-14 10:14:25.329  5629  5669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 10:14:25.329  5629  5669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-14 10:14:25.329  5629  5669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-14 10:14:25.329  5629  5669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-14 10:14:25.329  5629  5669 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-14 10:14:25.331  5629  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:14:25.331  5629  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-14 10:14:25.336  5629  5669 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:14:25.336  5629  5669 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:14:25.336  5629  5669 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-14 10:14:25.336  5629  5669 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:14:25.337  5629  5669 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-14 10:14:25.484  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:25.488  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:25.491  5629  5629 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-14 10:14:25.516   929  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 10:14:25.868  5629  5638 I art     : Background sticky concurrent mark sweep GC freed 79329(7MB) AllocSpace objects, 17(1096KB) LOS objects, 22% free, 25MB/32MB, paused 4.434ms total 325.146ms
,10-14 10:14:27.225  5629  5638 I art     : Background partial concurrent mark sweep GC freed 49002(5MB) AllocSpace objects, 3(2MB) LOS objects, 38% free, 25MB/41MB, paused 1.131ms total 141.437ms
,10-14 10:14:27.475  5629  5675 W jxcore-log: Initializing JXcore engine
,10-14 10:14:27.475  5629  5675 W jxcore-log: JXcore engine is ready
,10-14 10:14:27.496  5675  5675 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11787 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-14 10:14:27.496  5675  5675 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14514]" dev="sockfs" ino=14514 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-14 10:14:27.496  5675  5675 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-14 10:14:27.496  5675  5675 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31473]" dev="sockfs" ino=31473 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-14 10:14:27.506  5629  5675 W jxcore-log: Starting JXcore engine
,10-14 10:14:27.555  5629  5675 W jxcore-log: Platform android
10-14 10:14:27.555  5629  5675 W jxcore-log: 
,10-14 10:14:27.555  5629  5675 W jxcore-log: Process ARCH arm
10-14 10:14:27.555  5629  5675 W jxcore-log: 
,10-14 10:14:27.732  5629  5675 I jxcore-log: JXcore Cordova bridge is ready!
10-14 10:14:27.732  5629  5675 I jxcore-log: 
,10-14 10:14:27.732  5629  5675 W jxcore-log: JXcore engine is started
,10-14 10:14:27.744  5629  5669 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-14 10:14:27.751  5629  5629 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-14 10:14:32.623   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:33.625   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:34.626   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:35.627   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:36.628   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:37.368  5629  5675 I jxcore-log: 2016-10-14 14:14:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-14 10:14:37.368  5629  5675 I jxcore-log: 
,10-14 10:14:37.370  5629  5675 I jxcore-log: 2016-10-14 14:14:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-14 10:14:37.370  5629  5675 I jxcore-log: 
,10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:14:37.375  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:14:37.377  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:14:37.379  5629  5675 I jxcore-log: 2016-10-14 14:14:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-14 10:14:37.379  5629  5675 I jxcore-log: 
10-14 10:14:37.380  5629  5675 I jxcore-log: 2016-10-14 14:14:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-14 10:14:37.380  5629  5675 I jxcore-log: 
,10-14 10:14:37.629   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-14 10:14:37.631  5629  5675 I jxcore-log: 2016-10-14 14:14:37 - DEBUG UnitTest_app: 'Running unit tests'
10-14 10:14:37.631  5629  5675 I jxcore-log: 
,10-14 10:14:37.632  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 10:14:37.632  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a54a1d added. We now have 2 listener(s)
10-14 10:14:37.633  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 10:14:37.633  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:14:37.633  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:14:37.633  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 10:14:37.633  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3639492 added. We now have 2 listener(s)
10-14 10:14:37.633  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:14:37.633  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 10:14:37.635  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:14:37.638  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:14:37.639  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:37.640  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:14:37.640  5629  5675 D executeNativeTests: Running unit tests
,10-14 10:14:37.646  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:37.651  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:37.676  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 10:14:37.676  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 added. We now have 3 listener(s)
10-14 10:14:37.677  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:14:37.677  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-14 10:14:37.677  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:14:37.677  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:14:37.677  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 added. We now have 3 listener(s)
10-14 10:14:37.677  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:14:37.677  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:14:37.679  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:14:37.681  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:14:37.682  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:37.682  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:14:37.683  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 10:14:37.684  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:14:37.684  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:14:37.684  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:14:37.684  5629  5675 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-14 10:14:37.684  5629  5675 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 10:14:37.684  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 10:14:37.684  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-14 10:14:37.685  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:14:37.685  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:14:37.685  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:37.685  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:14:37.685  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-14 10:14:37.685  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:37.685  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:37.685  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:14:37.686  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:37.686  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:14:37.686  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 removed from the list
10-14 10:14:37.686  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:37.686  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 removed from the list
10-14 10:14:37.691  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:37.697  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:14:37.698  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:37.698  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:37.698  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:37.698  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:37.699  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:37.699  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:37.699  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:37.699  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:14:37.700  5629  5675 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-14 10:14:37.700  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:37.700  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:37.700  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:37.700  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:37.700  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:37.700  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:37.700  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 10:14:37.700  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:37.701  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:37.701  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:37.701  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:37.701  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:37.701  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:37.701  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:37.701  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:37.701  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:37.701  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:37.701  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:37.701  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-14 10:14:37.704  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-14 10:14:37.705  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-14 10:14:37.705  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,10-14 10:14:37.705  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-14 10:14:37.705  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:37.705  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:37.705  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:37.705  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:37.705  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:37.705  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:37.705  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:37.705  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
,10-14 10:14:37.705  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:37.705  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:37.705  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:37.705  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:37.705  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:37.705  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:37.705  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:37.706  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:37.706  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:37.706  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:37.706  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:37.706  5629  5675 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-14 10:14:37.707  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:14:37.709  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:14:37.710  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:37.710  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:14:37.710  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:14:37.710  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 10:14:37.710  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 10:14:37.710  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:14:37.710  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:14:37.712  5629  5675 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:14:37.712  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 10:14:37.714  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:14:37.717  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:37.718  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:14:37.720  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-14 10:14:37.721  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:14:37.724  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,10-14 10:14:37.730  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-14 10:14:37.730  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 10:14:37.730  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-14 10:14:37.730  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 10:14:37.731  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:14:37.731  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:14:37.731  5629  5675 D BluetoothAdapter: STATE_ON
,10-14 10:14:37.733  4594  4818 D BtGatt.GattService: registerClient() - UUID=26895e13-7b08-4cc6-a466-62c22d57347e
,10-14 10:14:37.734  4594  4672 D BtGatt.GattService: onClientRegistered() - UUID=26895e13-7b08-4cc6-a466-62c22d57347e, clientIf=5
10-14 10:14:37.734  5629  5639 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 10:14:37.737  4594  4611 D BtGatt.GattService: start scan with filters
,10-14 10:14:37.740  4594  4676 D BtGatt.ScanManager: handling starting scan
,10-14 10:14:37.741  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 10:14:37.741  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 10:14:37.741  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:14:37.741  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 10:14:37.741  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:14:37.741  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 10:14:37.741  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 10:14:37.742  4594  4676 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:14:37.743  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:14:37.743  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:14:37.743  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:14:37.743  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 10:14:37.744  5629  5675 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 10:14:37.749  4594  4672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-14 10:14:37.749  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:37.749  4594  4676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 10:14:37.755  4594  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 10:14:37.755  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:37.755  4594  4676 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:14:37.756  4594  4676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-14 10:14:37.766  4594  4672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 10:14:37.766  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:37.771  4594  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-14 10:14:37.771  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:38.244  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-14 10:14:38.244  5629  5629 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:14:38.245  5629  5629 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 10:14:39.278   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 10:14:39.286   929  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-14 10:14:42.312   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 10:14:42.320   929  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-14 10:14:42.630   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:42.749  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 10:14:42.749  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:42.749  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 10:14:42.749  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:42.749  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 10:14:42.749  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:42.749  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-14 10:14:42.750  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:14:42.750  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:14:42.750  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:14:42.750  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:14:42.751  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 10:14:42.752  5629  5675 D BluetoothAdapter: STATE_ON
,10-14 10:14:42.752  4594  4818 D BtGatt.GattService: stopScan() - queue size =1
,10-14 10:14:42.754  4594  4611 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:14:42.756  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:14:42.756  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-14 10:14:42.757  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-14 10:14:42.757  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-14 10:14:42.757  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:14:42.757  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 10:14:42.757  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 10:14:42.758  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 10:14:42.761  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:14:42.762  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:14:42.763  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 10:14:42.763  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:14:42.763  4594  4594 D BtGatt.ScanManager: awakened up at time 239663
,10-14 10:14:42.764  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:14:42.767  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 10:14:42.770  4594  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 10:14:42.770  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:42.770  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:42.770  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:42.770  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:14:42.770  4594  4676 D BtGatt.ScanManager: stopping BLe Batch
10-14 10:14:42.770  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:14:42.770  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:14:42.770  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:42.771  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:14:42.771  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:42.771  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:42.771  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:42.771  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:42.771  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:42.781  4594  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 10:14:42.781  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:42.781  4594  4676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 10:14:42.810  4594  4672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,10-14 10:14:42.810  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:42.810  4594  4672 D BtGatt.GattService: current time is 239710630754
,10-14 10:14:42.811  4594  4672 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -97, 11, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -93, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -79, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 50, -35, 86, -77, -92, -11, 1, -128, -97, 8, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 82, -1, 41, 3, 1, -37, 18, -106, -10, 8, -121, 0]
10-14 10:14:42.814  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
10-14 10:14:42.815  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-14 10:14:42.815  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-14 10:14:42.816  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 10:14:42.816  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-14 10:14:42.816  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-14 10:14:42.817  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-14 10:14:42.817  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 82, -1, 41, 3, 1, -37, 18, -106, -10, 8, -121]
,10-14 10:14:43.272  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:14:43.632   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:44.633   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:45.517   929  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 10:14:45.634   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:46.636   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:47.637   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-14 10:14:47.773  5629  5675 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-14 10:14:47.779  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:14:47.791  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:14:47.795  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:14:47.796  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 10:14:47.796  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-14 10:14:47.797  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-14 10:14:47.797  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-14 10:14:47.797  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:14:47.797  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:14:47.802  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:14:47.804  5629  5675 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:14:47.804  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 10:14:47.808  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:47.812  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:14:47.814  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:14:47.815  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:14:47.820  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 10:14:47.820  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 10:14:47.820  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-14 10:14:47.820  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:14:47.820  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:14:47.822  5629  5675 D BluetoothAdapter: STATE_ON
,10-14 10:14:47.826  4594  4611 D BtGatt.GattService: registerClient() - UUID=04111e58-b1da-40ae-ac76-1ec573276ce0
,10-14 10:14:47.827  4594  4672 D BtGatt.GattService: onClientRegistered() - UUID=04111e58-b1da-40ae-ac76-1ec573276ce0, clientIf=5
,10-14 10:14:47.827  5629  5639 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 10:14:47.828  4594  4610 D BtGatt.GattService: start scan with filters
10-14 10:14:47.832  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 10:14:47.832  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 10:14:47.832  4594  4676 D BtGatt.ScanManager: handling starting scan
10-14 10:14:47.833  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:14:47.833  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-14 10:14:47.833  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:14:47.833  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 10:14:47.833  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 10:14:47.837  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:14:47.837  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:14:47.838  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 10:14:47.841  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 10:14:47.845  4594  4672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-14 10:14:47.845  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:47.845  4594  4676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 10:14:47.845  5629  5675 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 10:14:47.851  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 10:14:47.851  5629  5675 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-14 10:14:47.851  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:47.851  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 10:14:47.851  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:47.852  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-14 10:14:47.852  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:47.852  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:14:47.852  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:14:47.852  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:14:47.852  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:14:47.852  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:14:47.852  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 10:14:47.853  5629  5675 D BluetoothAdapter: STATE_ON
10-14 10:14:47.854  4594  4610 D BtGatt.GattService: stopScan() - queue size =1
10-14 10:14:47.855  4594  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-14 10:14:47.856  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:47.856  4594  4817 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:14:47.856  4594  4676 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:14:47.856  4594  4676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 10:14:47.856  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-14 10:14:47.856  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 10:14:47.856  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 10:14:47.856  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:14:47.857  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:14:47.857  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,10-14 10:14:47.857  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 10:14:47.857  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 10:14:47.858  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:14:47.858  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:14:47.859  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,10-14 10:14:47.859  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:14:47.859  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-14 10:14:47.860  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:14:47.861  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:47.861  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:47.862  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:14:47.862  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:47.862  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:47.862  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:14:47.862  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:47.862  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:47.862  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:14:47.862  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:47.862  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:47.862  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:14:47.863  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:47.863  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:47.864  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:47.864  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-14 10:14:47.864  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:47.865  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:47.865  5629  5675 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-14 10:14:47.868  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:14:47.873  4594  4672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 10:14:47.873  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:14:47.874  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:14:47.877  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:14:47.877  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:14:47.878  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:14:47.878  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-14 10:14:47.878  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 10:14:47.878  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:14:47.878  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:14:47.880  4594  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 10:14:47.880  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:47.882  5629  5675 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-14 10:14:47.882  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:14:47.882  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 10:14:47.887  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:14:47.887  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:14:47.889  4594  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 10:14:47.889  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:14:47.889  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 10:14:47.889  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:47.889  4594  4676 D BtGatt.ScanManager: stopping BLe Batch
,10-14 10:14:47.892  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 10:14:47.892  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-14 10:14:47.892  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 10:14:47.892  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:14:47.892  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:14:47.893  5629  5675 D BluetoothAdapter: STATE_ON
,10-14 10:14:47.895  4594  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-14 10:14:47.895  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:47.895  4594  4676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 10:14:47.895  4594  4817 D BtGatt.GattService: registerClient() - UUID=37d13dce-74ad-45c9-9fbb-af3669be669b
10-14 10:14:47.896  4594  4672 D BtGatt.GattService: onClientRegistered() - UUID=37d13dce-74ad-45c9-9fbb-af3669be669b, clientIf=5
,10-14 10:14:47.897  5629  5640 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 10:14:47.897  4594  4611 D BtGatt.GattService: start scan with filters
,10-14 10:14:47.900  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 10:14:47.900  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 10:14:47.901  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-14 10:14:47.901  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 10:14:47.901  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:14:47.901  4594  4672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 10:14:47.901  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 10:14:47.901  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:47.901  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 10:14:47.902  4594  4676 D BtGatt.ScanManager: handling starting scan
10-14 10:14:47.903  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:14:47.903  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:14:47.903  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 10:14:47.905  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 10:14:47.907  5629  5675 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 10:14:47.908  4594  4672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 10:14:47.908  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:47.908  4594  4676 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 10:14:47.913  4594  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 10:14:47.913  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:47.913  4594  4676 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:14:47.913  4594  4676 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-14 10:14:47.923  4594  4672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-14 10:14:47.923  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:47.928  4594  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 10:14:47.928  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:14:48.375   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 10:14:48.379   929  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-14 10:14:48.404  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-14 10:14:48.404  5629  5629 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:14:48.405  5629  5629 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 10:14:51.395   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 10:14:51.402   929  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-14 10:14:52.907  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 10:14:52.908  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:14:52.908  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 10:14:52.908  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:52.908  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 10:14:52.908  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:52.908  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:14:52.909  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-14 10:14:52.909  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:14:52.909  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:14:52.909  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:14:52.909  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-14 10:14:52.911  5629  5675 D BluetoothAdapter: STATE_ON
10-14 10:14:52.912  4594  4611 D BtGatt.GattService: stopScan() - queue size =1
,10-14 10:14:52.914  4594  4817 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:14:52.915  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:14:52.915  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 10:14:52.915  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,10-14 10:14:52.915  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:14:52.916  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:14:52.916  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 10:14:52.916  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 10:14:52.916  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 10:14:52.919  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:14:52.919  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:14:52.919  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 10:14:52.919  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:14:52.919  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:14:52.921  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:14:52.922  4594  4594 D BtGatt.ScanManager: awakened up at time 249822
10-14 10:14:52.923  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:14:52.923  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:14:52.924  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 10:14:52.929  4594  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 10:14:52.929  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:52.929  4594  4676 D BtGatt.ScanManager: stopping BLe Batch
,10-14 10:14:52.936  4594  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-14 10:14:52.936  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:52.936  4594  4676 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 10:14:52.957  4594  4672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-14 10:14:52.957  4594  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:14:52.957  4594  4672 D BtGatt.GattService: current time is 249857531630
10-14 10:14:52.957  4594  4672 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -83, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 85, -113, -37, 31, -33, 8, 0, 4, -85, 27, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -83, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -91, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-14 10:14:52.958  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-14 10:14:52.958  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 10:14:52.958  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
10-14 10:14:52.958  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-14 10:14:52.958  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-14 10:14:52.958  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-14 10:14:52.959  4594  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-14 10:14:53.425  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:14:53.425  5629  5629 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:14:53.425  5629  5629 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 10:14:57.638   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:57.925  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 10:14:57.926  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:57.926  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:57.926  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:57.926  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:57.926  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 10:14:57.927  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.927  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:57.927  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:14:57.927  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.927  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:57.927  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.929  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.929  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.933  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.933  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:57.933  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:14:57.934  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.935  5629  5675 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-14 10:14:57.938  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:57.938  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:57.938  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:57.939  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:14:57.939  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.939  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.939  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.939  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:57.940  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:14:57.940  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.940  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:57.940  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.941  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.941  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:57.941  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.944  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.945  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-14 10:14:57.945  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.945  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:14:57.948  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-14 10:14:57.948  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:57.949  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:14:57.949  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:57.949  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:57.949  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.949  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.950  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.950  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:57.950  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:14:57.950  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.950  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:57.951  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.951  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.951  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.951  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.954  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.954  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:57.954  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.955  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:14:57.957  5629  5675 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-14 10:14:57.957  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:57.957  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:57.958  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:57.958  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:57.958  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:57.958  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.958  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.958  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:57.958  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.959  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.959  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 10:14:57.959  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.959  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.959  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.959  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.961  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.962  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:57.962  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.962  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.964  5629  5675 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-14 10:14:57.964  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:57.964  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:57.965  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-14 10:14:57.965  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:57.965  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.965  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.965  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.965  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:57.966  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.966  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.966  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:57.967  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.967  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.967  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.967  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.969  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.969  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:57.969  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.969  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.970  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-14 10:14:57.971  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:14:57.971  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:14:57.971  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 10:14:57.971  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:14:57.971  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:14:57.971  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 10:14:57.971  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:14:57.971  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 10:14:57.971  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:57.972  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:57.972  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:57.972  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:57.972  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.972  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.972  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.972  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:57.972  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.972  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.972  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:57.972  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.972  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.972  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.972  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:57.974  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.974  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:57.974  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.974  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.975  5629  5675 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 10:14:57.975  5629  5675 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-14 10:14:57.975  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-14 10:14:57.980  5629  5675 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-14 10:14:57.980  5629  5675 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-14 10:14:57.980  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-14 10:14:57.980  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-14 10:14:57.981  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-14 10:14:57.982  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-14 10:14:57.982  5629  5675 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-14 10:14:57.983  5629  5675 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-14 10:14:57.983  5629  5675 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-14 10:14:57.983  5629  5675 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 10:14:57.983  5629  5675 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-14 10:14:57.983  5629  5675 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-14 10:14:57.984  5629  5675 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 10:14:57.984  5629  5675 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-14 10:14:57.984  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-14 10:14:57.988  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-14 10:14:57.989  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-14 10:14:57.989  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-14 10:14:57.990  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,10-14 10:14:57.990  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,10-14 10:14:57.990  5629  5675 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-14 10:14:57.990  5629  5675 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 10:14:57.990  5629  5675 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-14 10:14:57.990  5629  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-14 10:14:57.990  5629  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-14 10:14:57.990  5629  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-14 10:14:57.990  5629  5676 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-14 10:14:57.991  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 10:14:57.991  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:57.991  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:57.991  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:57.991  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.991  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.991  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.991  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-14 10:14:57.993  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:57.993  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.993  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.993  5629  5676 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,10-14 10:14:57.993  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:57.993  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.993  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.993  5629  5676 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:14:57.993  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.993  5629  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
10-14 10:14:57.993  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.993  5629  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
10-14 10:14:57.993  5629  5677 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
10-14 10:14:57.990  4610  4610 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32930]" dev="sockfs" ino=32930 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:14:57.990  4610  4610 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32930]" dev="sockfs" ino=32930 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-14 10:14:57.995  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.995  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:57.995  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:14:57.995  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:14:57.996  5629  5675 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-14 10:14:57.997  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:57.997  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:57.997  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:57.997  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:57.997  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.997  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.997  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:57.997  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
,10-14 10:14:57.998  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.998  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:57.998  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:57.998  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.998  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.998  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:57.998  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:57.999  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:57.999  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:57.999  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:57.999  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:58.000  5629  5675 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-14 10:14:58.000  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:58.000  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:58.000  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:58.000  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:58.000  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:58.001  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:58.001  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:58.001  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:58.001  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:58.001  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:58.001  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:58.001  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:58.001  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:58.001  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:14:58.001  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:58.002  5629  5676 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-14 10:14:58.002  5629  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-14 10:14:58.002  5629  5676 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
10-14 10:14:58.003  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:58.003  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:58.003  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:58.004  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:58.005  5629  5675 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-14 10:14:58.005  5629  5675 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,10-14 10:14:58.005  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 10:14:58.005  5629  5675 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-14 10:14:58.005  5629  5675 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-14 10:14:58.005  5629  5675 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-14 10:14:58.005  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 10:14:58.005  5629  5675 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-14 10:14:58.005  5629  5675 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-14 10:14:58.005  5629  5675 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-14 10:14:58.005  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 10:14:58.005  5629  5675 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-14 10:14:58.006  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:14:58.006  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:14:58.006  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:14:58.006  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:58.006  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:58.006  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:58.006  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 10:14:58.006  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:58.006  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:58.006  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:58.006  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:58.006  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:58.006  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:58.006  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:58.006  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:14:58.008  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:14:58.008  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:14:58.008  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:58.008  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:58.008  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:14:58.008  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:58.008  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:58.008  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:14:58.008  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:14:58.008  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:14:58.008  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:14:58.009  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:14:58.009  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:14:58.009  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:14:58.640   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:14:59.641   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:00.642   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:01.643   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:02.644   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-14 10:15:03.009  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:15:03.010  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:15:03.010  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:15:03.010  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.010  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:03.010  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:03.011  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:15:03.011  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:03.011  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:15:03.011  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:03.012  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:03.012  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.012  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.012  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 10:15:03.012  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:15:03.012  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.013  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:15:03.013  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 10:15:03.013  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.013  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.013  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:15:03.013  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.016  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:03.016  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:03.017  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.017  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:15:03.021  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-14 10:15:03.022  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:15:03.023  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-14 10:15:03.025  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-14 10:15:03.025  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 10:15:03.026  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-14 10:15:03.026  5629  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-14 10:15:03.027  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-14 10:15:03.027  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:15:03.027  5629  5629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 10:15:03.028  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:03.028  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-14 10:15:03.028  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 10:15:03.028  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 10:15:03.028  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.028  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-14 10:15:03.028  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-14 10:15:03.028  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:15:03.028  5629  5678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:15:03.028  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:15:03.028  5629  5629 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-14 10:15:03.028  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:15:03.028  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-14 10:15:03.029  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:15:03.029  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.029  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.030  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:15:03.030  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:15:03.030  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:15:03.030  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:03.031  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:03.031  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:15:03.031  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-14 10:15:03.031  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:15:03.031  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:03.031  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.031  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.031  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-14 10:15:03.031  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:15:03.031  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.031  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:15:03.031  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:03.031  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.031  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.032  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.032  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:03.029  4817  4817 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31528]" dev="sockfs" ino=31528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:15:03.029  4817  4817 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31528]" dev="sockfs" ino=31528 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 10:15:03.032  5629  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-14 10:15:03.032  5629  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 10:15:03.032  5629  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 10:15:03.032  5629  5629 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 10:15:03.032  5629  5629 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:03.033  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:03.033  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:03.033  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.033  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:15:03.034  5629  5675 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-14 10:15:03.034  5629  5675 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 10:15:03.035  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 10:15:03.035  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:15:03.035  5629  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 10:15:03.035  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:03.035  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:03.035  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:03.035  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:15:03.035  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.036  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.036  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:03.036  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:15:03.036  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.036  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:15:03.036  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:03.036  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:15:03.036  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.036  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.036  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.038  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:03.038  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:03.038  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.038  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:15:03.042  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:03.042  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:03.042  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:03.042  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:15:03.042  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.042  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.042  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:03.042  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:15:03.042  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.043  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:15:03.043  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:03.043  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.043  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.043  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.043  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.044  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:03.044  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-14 10:15:03.044  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.044  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:15:03.045  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:03.045  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:03.045  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:03.045  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:15:03.046  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.046  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.046  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:03.046  5629  5675 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae69b90 not in the list
10-14 10:15:03.046  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.046  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
10-14 10:15:03.046  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:03.046  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.046  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:03.046  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:03.047  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:03.048  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:03.048  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:03.048  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:03.048  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f64c89 not in the list
,10-14 10:15:03.049  5629  5675 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-14 10:15:03.049  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 10:15:03.049  5629  5675 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-14 10:15:03.049  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 10:15:03.049  5629  5675 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,10-14 10:15:03.050  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 10:15:03.051  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-14 10:15:03.051  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-14 10:15:03.052  5629  5675 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-14 10:15:03.052  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-14 10:15:03.053  5629  5675 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-14 10:15:03.053  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-14 10:15:03.053  5629  5675 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-14 10:15:03.053  5629  5675 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-14 10:15:03.053  5629  5675 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-14 10:15:03.053  5629  5675 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-14 10:15:03.053  5629  5675 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-14 10:15:03.053  5629  5675 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,10-14 10:15:03.053  5629  5675 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-14 10:15:03.054  5629  5675 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-14 10:15:03.054  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:03.054  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a35a43 added. We now have 3 listener(s)
10-14 10:15:03.054  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:15:03.055  5629  5675 D BluetoothAdapter: enable(): BT is already enabled..!
,10-14 10:15:03.055   929  3847 D WifiService: setWifiEnabled: true pid=5629, uid=10077
10-14 10:15:03.056   929  3847 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:15:03.121  4594  4794 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-14 10:15:03.122  4594  4807 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-14 10:15:03.531  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:15:08.064  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:08.064  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e008c0 added. We now have 4 listener(s)
10-14 10:15:08.064  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:15:08.072  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:08.072  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e008c0 removed from the list
10-14 10:15:08.072  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:08.072  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:08.072  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:08.073  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 10:15:08.073  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38e69f9 added. We now have 4 listener(s)
10-14 10:15:08.073  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:15:08.075  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:08.075  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38e69f9 removed from the list
10-14 10:15:08.075  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:08.075  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:15:08.075  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:08.076  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:08.076  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7832d3e added. We now have 4 listener(s)
10-14 10:15:08.076  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:15:08.078   929  3571 D WifiService: setWifiEnabled: false pid=5629, uid=10077
,10-14 10:15:08.079   929  3571 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:15:08.087   929  2971 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-14 10:15:08.088   929  2971 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-14 10:15:08.088   929  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:15:08.089   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:15:08.095  4594  4667 D BluetoothAdapterState: Current state: ON, message: 23
10-14 10:15:08.096  4594  4667 D BluetoothAdapterProperties: Setting state to 13
,10-14 10:15:08.096  4594  4667 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-14 10:15:08.098  4594  4667 D BluetoothAdapterProperties: onBluetoothDisable()
,10-14 10:15:08.099  4594  4667 I BluetoothAdapterState: Entering PendingCommandState
10-14 10:15:08.101  4594  4594 D BluetoothMapService: onReceive
10-14 10:15:08.101  4594  4594 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 10:15:08.101  4594  4594 D BluetoothMapService: STATE_TURNING_OFF
10-14 10:15:08.102  4594  4594 D BluetoothMapService: MAP Service closeService in
10-14 10:15:08.102  4594  4594 D BluetoothMapMasInstance0: MAP Service shutdown
10-14 10:15:08.102  4594  4594 D ObexServerSockets0: shutdown(block = true)
10-14 10:15:08.103  4594  4594 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:15:08.103  4594  4842 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-14 10:15:08.103  4594  4594 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:15:08.103  4594  4807 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-14 10:15:08.106  4594  4843 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 10:15:08.107  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:08.107  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:08.108  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.109  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:08.112  4594  4594 I BtOppRfcommListener: stopping Accept Thread
,10-14 10:15:08.113   509   923 D CommandListener: Clearing all IP addresses on wlan0
10-14 10:15:08.113  4594  5326 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-14 10:15:08.113  4594  5326 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-14 10:15:08.114   929  5387 D DhcpClient: Clearing IP address
,10-14 10:15:08.120   509   923 D CommandListener: Setting iface cfg
10-14 10:15:08.121  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:08.121  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:08.122   929  5388 D DhcpClient: Receive thread stopped
10-14 10:15:08.122  3556  5443 V NativeCrypto: Read error: ssl=0x7f7e872d00: I/O error during system call, Connection timed out
10-14 10:15:08.123  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.123  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:08.124  3556  5443 V NativeCrypto: SSL shutdown failed: ssl=0x7f7e872d00: I/O error during system call, Broken pipe
,10-14 10:15:08.124   929   942 I ActivityManager: Start proc 5682:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-14 10:15:08.126  4594  4672 D BluetoothAdapterProperties: Scan Mode:20
,10-14 10:15:08.126  4594  4667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-14 10:15:08.129  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:15:08.131   929   940 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-14 10:15:08.132   929  5385 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,10-14 10:15:08.133  4594  4594 D HeadsetService: Received stop request...Stopping profile...
10-14 10:15:08.133  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.134   929  5385 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-14 10:15:08.135   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-14 10:15:08.135   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-14 10:15:08.136  3822  4147 D BluetoothHeadset: Proxy object disconnected
,10-14 10:15:08.137  4594  4594 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:08.137  4594  4594 V BluetoothAdapterState: isTurningOn()=false
,10-14 10:15:08.137  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:08.137  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:08.138  3138  3150 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:08.138   929   929 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:08.138   929   929 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:08.138   929   929 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:08.139   929  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-14 10:15:08.139  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:08.139  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:15:08.140  4594  4594 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-14 10:15:08.140  4594  4594 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-14 10:15:08.140  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.141  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:08.141  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:15:08.141  4594  4794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:08.141  4594  4794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:08.141  4594  4794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-14 10:15:08.141  4594  4594 D A2dpService: Received stop request...Stopping profile...
10-14 10:15:08.141  4594  4672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-14 10:15:08.141  4594  4825 D A2dpStateMachine: Exit Disconnected: -1
10-14 10:15:08.141  4594  4672 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-14 10:15:08.142  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.142  3138  3138 D HeadsetProfile: Bluetooth service disconnected
10-14 10:15:08.143   929   929 D BluetoothA2dp: Proxy object disconnected
10-14 10:15:08.143  3138  3138 D BluetoothA2dp: Proxy object disconnected
10-14 10:15:08.144  4594  4594 D HidService: Received stop request...Stopping profile...
10-14 10:15:08.144  4594  4594 D HidService: Stopping Bluetooth HidService
10-14 10:15:08.144  3138  3138 D BluetoothInputDevice: Proxy object disconnected
10-14 10:15:08.144  3138  3138 D HidProfile: Bluetooth service disconnected
,10-14 10:15:08.146  4594  4594 D HealthService: Received stop request...Stopping profile...
10-14 10:15:08.146  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.147   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-14 10:15:08.148   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-14 10:15:08.149  4594  4594 D PanService: Received stop request...Stopping profile...
10-14 10:15:08.152  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.152   536   536 E Parcel  : Reading a NULL string not supported here.
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:08.152  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:15:08.153  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.153  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:08.154  4594  4594 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:08.154  4594  4594 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:08.154  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:08.154  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:08.155   929   929 D RttService: SCAN_AVAILABLE : 1
10-14 10:15:08.156   929  3080 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-14 10:15:08.156  4594  4672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-14 10:15:08.157  4594  4794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:08.157  4594  4794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:08.158  4594  4594 D BluetoothMapService: Received stop request...Stopping profile...
10-14 10:15:08.157   929  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-14 10:15:08.158  4594  4594 D BluetoothMapService: stop()
10-14 10:15:08.158  4594  4794 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 10:15:08.158  4594  4794 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 10:15:08.158  4594  4794 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 10:15:08.158  4594  4794 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 10:15:08.159  4594  4594 D BluetoothMapAppObserver: deinitObservers()
10-14 10:15:08.159  4594  4594 D BluetoothMapAppObserver: removeReceiver()
10-14 10:15:08.159  3779  3915 W QCNEJ   : |CORE| network lost: 100
,10-14 10:15:08.161  3779  3915 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-14 10:15:08.162  4594  4594 V BluetoothAdapterState: isTurningOff()=true
,10-14 10:15:08.162  4594  4594 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:08.162  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 10:15:08.162  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:08.162  4594  4594 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-14 10:15:08.162  4594  4594 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-14 10:15:08.162  4594  4672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 10:15:08.163  4594  4594 D SapService: Received stop request...Stopping profile...
10-14 10:15:08.163  4594  4594 V SapService: stop()
10-14 10:15:08.164  4594  4594 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:08.164  4594  4594 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:08.164  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:08.164  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:08.164  4594  4594 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-14 10:15:08.164  4594  4672 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-14 10:15:08.165  4594  4594 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 10:15:08.165  4594  4594 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:08.165  4594  4594 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:08.165  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:08.165  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:08.165  4594  4594 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-14 10:15:08.165  4594  4594 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-14 10:15:08.167  3138  3138 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 10:15:08.167  3138  3138 D PanProfile: Bluetooth service disconnected
10-14 10:15:08.167  4594  4594 D BluetoothMapService: MAP Service closeService in
10-14 10:15:08.167  3138  3138 D BluetoothMap: Proxy object disconnected
,10-14 10:15:08.167  3138  3138 D MapProfile: Bluetooth service disconnected
10-14 10:15:08.167  4594  4594 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:08.167  4594  4594 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:08.167  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:08.168  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:08.168  4594  4594 D BluetoothMapService: cleanup()
10-14 10:15:08.168  4594  4594 D BluetoothMapService: MAP Service closeService in
10-14 10:15:08.168  4594  4594 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:08.168  4594  4594 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:08.168  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:08.168  4594  4594 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:08.169  4594  4667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 10:15:08.169  4594  4667 D BluetoothAdapterProperties: Setting state to 15
10-14 10:15:08.169  4594  4667 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 10:15:08.169  4594  4667 I BluetoothAdapterState: Entering BleOnState
10-14 10:15:08.169  3138  3150 D BluetoothPan: onBluetoothStateChange on: false
,10-14 10:15:08.170   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:08.170   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 10:15:08.171  3822  3838 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:08.174   929  2971 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-14 10:15:08.176  3138  3978 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-14 10:15:08.177  3138  3150 D BluetoothMap: onBluetoothStateChange: up=false
10-14 10:15:08.178  3138  3152 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:08.178  3138  3978 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 10:15:08.179   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:08.179  3138  3150 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 10:15:08.180   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:08.180  4594  4667 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-14 10:15:08.180  4594  4667 D BluetoothAdapterProperties: Setting state to 16
10-14 10:15:08.180  4594  4667 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-14 10:15:08.181  4594  4667 D BluetoothAdapterProperties: onBleDisable
10-14 10:15:08.181  4594  4667 I BluetoothAdapterState: Entering PendingCommandState
10-14 10:15:08.182  4594  4669 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 10:15:08.183   929  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 10:15:08.183  4594  4794 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 10:15:08.183  4594  4794 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:08.184  4594  4672 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:15:08.185  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:08.185  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:08.186  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.186  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:15:08.189  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:08.189  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:08.189  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.189  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:08.190   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 10:15:08.191  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:08.192  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:08.193  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:08.194  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.195  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:08.202  5682  5682 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-14 10:15:08.216  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 10:15:08.217   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:15:08.217   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:15:08.218   929  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-14 10:15:08.218   929  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:15:08.218   509   923 D TetherController: Setting IP forward enable = 0
10-14 10:15:08.219   929   946 D Tethering: MasterInitialState.processMessage what=3
10-14 10:15:08.222  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.223  5282  5282 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f1cf9c9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-14 10:15:08.223  3928  3928 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-14 10:15:08.224  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.224   929  2971 D DhcpClient: doQuit
10-14 10:15:08.224   929  2971 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-14 10:15:08.225   929  5387 D DhcpClient: onQuitting
10-14 10:15:08.225  3449  3449 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-14 10:15:08.226  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:15:08.227  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:08.227  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:15:08.228  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.228  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:08.228  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 10:15:08.228  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 10:15:08.228  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-14 10:15:08.228  5046  5070 E SarControlService: no key has been found,reset the power
,10-14 10:15:08.230  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 10:15:08.230  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:08.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:08.230  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 10:15:08.230  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-14 10:15:08.231  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:08.231  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.231  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:08.231  5071  5071 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 10:15:08.232  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-14 10:15:08.232  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 10:15:08.232  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 10:15:08.232  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:08.232  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:08.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:15:08.232  5071  5071 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 10:15:08.233  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:08.233  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:08.234  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.235  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000ea03000000000000ffffffff]
10-14 10:15:08.235  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:08.235  5071  5085 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-14 10:15:08.235  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-14 10:15:08.235  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 10:15:08.239   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d89367:true
10-14 10:15:08.242   929  3570 I ActivityManager: Start proc 5709:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-14 10:15:08.242  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000eb03000000000000ffffffff]
10-14 10:15:08.242  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:08.242  5071  5085 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-14 10:15:08.243  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 10:15:08.243  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-14 10:15:08.247  3449  3449 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-14 10:15:08.257  5682  5682 D LocalBluetoothProfileManager: Adding local MAP profile
,10-14 10:15:08.258  3449  3449 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-14 10:15:08.260   509   916 W SocketClient: write error (Broken pipe)
10-14 10:15:08.260   509   916 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-14 10:15:08.260   509   916 W SocketListener: Error sending broadcast (Broken pipe)
10-14 10:15:08.261  5682  5682 D BluetoothMap: Create BluetoothMap proxy object
,10-14 10:15:08.272   509   923 E Netd    : netlink response contains error (No such file or directory)
,10-14 10:15:08.273   509   923 D TetherController: Setting IP forward enable = 0
,10-14 10:15:08.273   929  2973 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-14 10:15:08.273   929  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-14 10:15:08.274  5682  5682 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-14 10:15:08.282  5709  5709 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-14 10:15:08.291  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:15:08.299   929  3154 I ActivityManager: Killing 4960:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-14 10:15:08.298  3449  3449 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 10:15:08.316  3449  3449 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-14 10:15:08.328  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:15:08.329   929  2971 D wifi    : In wifi stop Hal
10-14 10:15:08.329   929  2971 D wifi    : halHandle = 0x7f6cd67b80, mVM = 0x7f893cd140, mCls = 0x100a02
,10-14 10:15:08.329   929  3448 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-14 10:15:08.329   929  3448 D WifiHAL : Got a signal to exit!!!
10-14 10:15:08.329   929  3448 I WifiHAL : Exit wifi_event_loop
10-14 10:15:08.331  4077  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:15:08.331  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.333  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:08.333   929  2971 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-14 10:15:08.333   929  2971 E WifiHAL : Event processing terminated
,10-14 10:15:08.333   929  2971 D wifi    : In wifi cleaned up handler
10-14 10:15:08.333   929  2971 I WifiHAL : Internal cleanup completed
10-14 10:15:08.334  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:08.351   929  3448 D wifi    : set interface wlan0 flags (DOWN)
,10-14 10:15:08.351   929  2971 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 10:15:08.391  4594  4672 I bt_hci  : shut_down
,10-14 10:15:08.395  4594  4678 D bt_hwcfg: hw_epilog_process
,10-14 10:15:08.395  4594  4678 I bt_vendor: low_power_mode_cb
,10-14 10:15:08.398  4594  4678 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-14 10:15:08.398  4594  4678 I bt_vendor: epilog_cb
10-14 10:15:08.398  4594  4678 I bt_hci  : epilog_finished_callback
,10-14 10:15:08.400  4594  4672 I bt_hci_h4: hal_close
10-14 10:15:08.400  4594  4672 I bt_userial_vendor: device fd = 54 close
,10-14 10:15:08.498  5709  5709 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.498  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 10:15:08.499  5709  5709 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:15:08.499  5709  5709 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:15:08.499  5709  5709 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:15:08.499  5709  5709 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.k.d(PG:583)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:15:08.499  5709  5709 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:15:08.499  5709  5709 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:15:08.499  5709  5709 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:15:08.499  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:15:08.505  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 10:15:08.509  4594  4669 D bt_stack_manager: event_shut_down_stack finished.
10-14 10:15:08.510  4594  4667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-14 10:15:08.511  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:15:08.512  4594  4667 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-14 10:15:08.512  4594  4594 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 10:15:08.512  5682  5682 D DockEventReceiver: finishStartingService: stopping service
10-14 10:15:08.512  4594  4594 D BtGatt.GattService: Received stop request...Stopping profile...
10-14 10:15:08.512  4594  4594 D BtGatt.GattService: stop()
10-14 10:15:08.512  4594  4594 D BtGatt.AdvertiseManager: advertise clients cleared
10-14 10:15:08.514   929  3571 I ActivityManager: Killing 5416:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-14 10:15:08.553  4594  4594 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:08.553  4594  4594 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:08.553  4594  4594 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:08.553  4594  4594 V BluetoothAdapterState: isBleTurningOff()=true
10-14 10:15:08.553  4594  4667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 10:15:08.553  4594  4667 D BluetoothAdapterProperties: Setting state to 10
10-14 10:15:08.553  4594  4667 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-14 10:15:08.554   929   946 D Tethering: InitialState.processMessage what=4
10-14 10:15:08.554  4594  4667 I BluetoothAdapterState: Entering OffState
10-14 10:15:08.557   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
10-14 10:15:08.558  3751  3751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-14 10:15:08.559   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-14 10:15:08.564  4594  4594 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-14 10:15:08.565  4594  4594 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 10:15:08.565  4594  4594 I BluetoothServiceJni: cleanupNative: return from cleanup
10-14 10:15:08.566  4594  4669 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-14 10:15:08.568  3751  3751 D SystemUpdateService: onCreate
10-14 10:15:08.572  3751  3751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-14 10:15:08.577  4594  4594 I art     : System.exit called, status: 0
,10-14 10:15:08.578  4594  4594 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 10:15:08.589  3751  3751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-14 10:15:08.592  3751  5413 I iu.UploadsManager: num queued entries: 0
,10-14 10:15:08.593  3751  5413 I iu.UploadsManager: num updated entries: 0
,10-14 10:15:08.598  3751  3751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 10:15:08.600  3751  3751 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 10:15:08.607  3751  5413 I iu.SyncManager: NEXT; no task
,10-14 10:15:08.608  3751  5746 I SystemUpdateService: active receiver: enabled
,10-14 10:15:08.611   929  3155 I ActivityManager: Start proc 5749:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-14 10:15:08.613   929  3570 I ActivityManager: Process com.android.bluetooth (pid 4594) has died
,10-14 10:15:08.620  3751  5746 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 10:15:08.641  5749  5749 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-14 10:15:08.644  5749  5749 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:15:08.650  5749  5749 D SprintDMHelper: simOperator: 
,10-14 10:15:08.651  5749  5749 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 10:15:08.662  5017  5761 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-14 10:15:08.675  3751  5746 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-14 10:15:08.675  3751  5746 I SystemUpdateService: now status is 0 (complete)
10-14 10:15:08.675  3751  5746 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 10:15:08.675  3751  5746 I SystemUpdateService: file has been verified
,10-14 10:15:08.675  3751  5746 I SystemUpdateService: OTA package size = 21989297
10-14 10:15:08.676   929   939 I ActivityManager: Start proc 5762:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-14 10:15:08.686  3751  5746 I SystemUpdateService: showing system update notification
,10-14 10:15:08.707  5762  5762 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-14 10:15:08.725   929  3155 I ActivityManager: Killing 5282:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-14 10:15:08.758  3751  3751 D SystemUpdateService: onDestroy
,10-14 10:15:08.762   929  3835 I ActivityManager: Killing 4682:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-14 10:15:08.866  5709  5735 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-14 10:15:08.875   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@164ccc8:true
,10-14 10:15:13.143   929  3153 D WifiService: setWifiEnabled: true pid=5629, uid=10077
,10-14 10:15:13.143   929  3153 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:15:13.153   509   923 D SoftapController: Softap fwReload - Ok
,10-14 10:15:13.159   509   923 D CommandListener: Setting iface cfg
10-14 10:15:13.160   509   923 D CommandListener: Trying to bring down wlan0
,10-14 10:15:13.161   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:15:13.165   929  2971 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 10:15:13.738   929  2971 D wifi    : set interface wlan0 flags (UP)
,10-14 10:15:13.741   929  2971 I WifiHAL : Initializing wifi
10-14 10:15:13.741   929  2971 I WifiHAL : Creating socket
10-14 10:15:13.742   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-14 10:15:13.745   929  2971 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-14 10:15:13.746   929  2971 D wifi    : Did set static halHandle = 0x7f6cd67b80
10-14 10:15:13.746   929  2971 D wifi    : halHandle = 0x7f6cd67b80, mVM = 0x7f893cd140, mCls = 0x101a26
10-14 10:15:13.746   929  2971 D wifi    : array field set
10-14 10:15:13.746   929  2971 I WifiNative-HAL: interface[0] = wlan0
10-14 10:15:13.748   929  5779 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547286842240
10-14 10:15:13.748   929  5779 D wifi    : waitForHalEvents called, vm = 0x7f893cd140, obj = 0x101a26, env = 0x7f6a296040
,10-14 10:15:13.815  5780  5780 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 10:15:13.830  5780  5780 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:15:13.849   929  2971 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-14 10:15:13.856  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:13.860  5780  5780 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:15:13.860  5780  5780 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 10:15:13.862  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:13.865  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:13.876   929  2971 D WifiConfigStore: Loading config and enabling all networks 
,10-14 10:15:13.878  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:13.878  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:13.878  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:13.878  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:15:13.879  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:13.879  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:13.879  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:13.879  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:15:13.881  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:13.881  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:13.881  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:13.881  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:13.890   929  2971 D WifiConfigStore: loaded 0 passpoint configs
10-14 10:15:13.890   929  2971 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-14 10:15:13.891   929  2971 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-14 10:15:13.892   929  2971 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-14 10:15:13.893   929  2971 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-14 10:15:13.894   929  2971 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-14 10:15:13.894   929  2971 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 10:15:13.894   929  2971 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-14 10:15:13.896   929  2971 D WifiNative-HAL: Setting external_sim to 1
10-14 10:15:13.897  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:15:13.897   929  2971 D wifi    : setting dfs flag to true, 0x7f6ff5dda0
10-14 10:15:13.897   929  2971 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 10:15:13.897   929  2971 D wifi    : setting scan oui 0x7f6ff5dda0
10-14 10:15:13.897   929  2971 D WifiHAL : Sending mac address OUI
10-14 10:15:13.901   929  2971 E native  : do suspend false
10-14 10:15:13.907   929  2971 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-14 10:15:13.907   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-14 10:15:13.908   929   929 D RttService: SCAN_AVAILABLE : 3
10-14 10:15:13.908   929  3080 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-14 10:15:13.908   509   923 D CommandListener: Setting iface cfg
10-14 10:15:13.911   929  2970 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
10-14 10:15:13.911   929  2970 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 10:15:13.919   929  2970 D WifiNative-HAL: p2pGetDeviceAddress
10-14 10:15:13.924   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=270824 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
10-14 10:15:13.924   929  2970 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 10:15:17.103  5780  5780 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:17.107  5780  5780 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:17.114  5780  5780 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:17.119  5780  5780 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:17.163   929  2971 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-14 10:15:17.164   929  2971 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-14 10:15:17.164   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:15:17.175   929  2971 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-14 10:15:17.209   929  2971 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-14 10:15:17.211  5780  5780 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-14 10:15:17.629  5780  5780 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 10:15:17.645   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:17.667  5780  5780 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 10:15:17.668  5780  5780 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-14 10:15:17.679   929  2971 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 10:15:17.679   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 10:15:17.679   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-14 10:15:17.705   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:15:17.717   509   923 D CommandListener: Setting iface cfg
,10-14 10:15:17.725   929  2971 D WifiStateMachine: Start Dhcp Watchdog 2
,10-14 10:15:17.731   929  5788 D DhcpClient: Receive thread started
,10-14 10:15:17.736   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-14 10:15:17.736   929  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-14 10:15:17.736   929  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-14 10:15:17.817   929  2971 E native  : do suspend false
,10-14 10:15:17.829   929  5787 D DhcpClient: Broadcasting DHCPDISCOVER
,10-14 10:15:17.844   929  5788 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172567, domain null
,10-14 10:15:17.844   929  5787 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172567 seconds
,10-14 10:15:17.846   929  5787 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-14 10:15:17.860   929  5788 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-14 10:15:17.861   929  5787 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-14 10:15:17.863   509   923 D CommandListener: Setting iface cfg
,10-14 10:15:17.867   929  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-14 10:15:17.872   929  5787 D DhcpClient: Scheduling renewal in 86399s
,10-14 10:15:17.880   929  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-14 10:15:17.882   929  2971 D WifiConfigStore: No blacklist allowed without epno enabled
,10-14 10:15:17.883   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-14 10:15:17.884   929  2973 D ConnectivityService: Adding iface wlan0 to network 101
10-14 10:15:17.898   929  2971 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-14 10:15:17.936   929  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-14 10:15:17.936   929  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-14 10:15:17.938   929  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-14 10:15:17.940   929  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-14 10:15:17.942   929  2973 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-14 10:15:17.957   929  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-14 10:15:17.961   929  2973 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-14 10:15:17.962   929  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-14 10:15:17.962   929  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-14 10:15:17.962   929  2973 D ConnectivityService:    accepting network in place of null
10-14 10:15:17.962   929  2971 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,10-14 10:15:17.962   929  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:15:17.963   929  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 10:15:17.975   929  5786 D NetlinkSocketObserver: NeighborEvent{elapsedMs=274875, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-14 10:15:17.986   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:15:18.006   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:15:18.009   929  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-14 10:15:18.009  3779  3915 W QCNEJ   : |CORE| network available: 101
,10-14 10:15:18.009   929  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:15:18.010   929  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-14 10:15:18.011   929   946 D Tethering: MasterInitialState.processMessage what=3
,10-14 10:15:18.015  3779  3915 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-14 10:15:18.016  3779  3915 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-14 10:15:18.017  3779  3915 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-14 10:15:18.017  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:18.017  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:15:18.017  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.017  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:18.020  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:18.020  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:15:18.020  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.020  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:18.023  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:18.023  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:15:18.023  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.023  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:18.027  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-14 10:15:18.027  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 10:15:18.028  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-14 10:15:18.028  5046  5070 E SarControlService: no key has been found,reset the power
10-14 10:15:18.028  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 10:15:18.028  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 10:15:18.028  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 10:15:18.028  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:18.029  5071  5071 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-14 10:15:18.030  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 10:15:18.030  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 10:15:18.030  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 10:15:18.031  3928  3928 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-14 10:15:18.032  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:18.032  5071  5071 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-14 10:15:18.034  3751  3751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-14 10:15:18.035  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000ec03000000000000ffffffff]
10-14 10:15:18.036  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:18.036  5071  5085 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-14 10:15:18.038  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 10:15:18.039  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 10:15:18.039  3751  3751 D SystemUpdateService: onCreate
10-14 10:15:18.040  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000ed03000000000000ffffffff]
10-14 10:15:18.040  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:18.040  5071  5085 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,10-14 10:15:18.041  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-14 10:15:18.042  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-14 10:15:18.045  3751  3751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 10:15:18.048   929  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.101,2a00:1450:400c:c0c::66
,10-14 10:15:18.058  3751  3751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-14 10:15:18.064  3751  5413 I iu.UploadsManager: num queued entries: 0
,10-14 10:15:18.064  3751  5413 I iu.UploadsManager: num updated entries: 0
10-14 10:15:18.064  3751  5413 I iu.SyncManager: NEXT; no task
,10-14 10:15:18.065  3751  5798 I SystemUpdateService: active receiver: enabled
,10-14 10:15:18.068  3751  3751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 10:15:18.069  3751  3751 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 10:15:18.071  5749  5749 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:15:18.074  5749  5749 D SprintDMHelper: simOperator: 
10-14 10:15:18.075  5749  5749 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 10:15:18.091  3751  5798 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 10:15:18.109  3751  5798 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-14 10:15:18.109  3751  5798 I SystemUpdateService: now status is 0 (complete)
10-14 10:15:18.109  3751  5798 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 10:15:18.109  3751  5798 I SystemUpdateService: file has been verified
10-14 10:15:18.109  3751  5798 I SystemUpdateService: OTA package size = 21989297
,10-14 10:15:18.115  3751  5798 I SystemUpdateService: showing system update notification
,10-14 10:15:18.125  3751  3751 D SystemUpdateService: onDestroy
,10-14 10:15:18.135   929  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 14 Oct 2016 14:15:18 GMT], X-Android-Received-Millis=[1476454518134], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476454518086]}
,10-14 10:15:18.135   929  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-14 10:15:18.135   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-14 10:15:18.135   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-14 10:15:18.137   929  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-14 10:15:18.152   929  3155 D WifiService: setWifiEnabled: false pid=5629, uid=10077
10-14 10:15:18.152   929  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:15:18.153   929  2971 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-14 10:15:18.154   929  2971 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-14 10:15:18.154   929  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 10:15:18.154   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:15:18.163   929  5787 D DhcpClient: Clearing IP address
10-14 10:15:18.163   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:15:18.165   509   923 D CommandListener: Setting iface cfg
,10-14 10:15:18.166  3556  5799 V NativeCrypto: SSL handshake aborted: ssl=0x7f6e247e00: I/O error during system call, Connection timed out
,10-14 10:15:18.171   929  3829 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,10-14 10:15:18.171   929  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-14 10:15:18.171   929  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.101,2a00:1450:400c:c0c::66
10-14 10:15:18.174   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-14 10:15:18.174   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-14 10:15:18.179   536   536 E Parcel  : Reading a NULL string not supported here.
,10-14 10:15:18.180   929  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-14 10:15:18.181  3779  3915 W QCNEJ   : |CORE| network lost: 101
10-14 10:15:18.182  3779  3915 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-14 10:15:18.183   929  5788 D DhcpClient: Receive thread stopped
,10-14 10:15:18.184   929   929 D RttService: SCAN_AVAILABLE : 1
10-14 10:15:18.184   929  3080 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-14 10:15:18.185   929  5785 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400c:c0c::66 (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
10-14 10:15:18.186   929  2971 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-14 10:15:18.188  5017  5802 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
10-14 10:15:18.189   929  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: java.net.ConnectException: failed to connect to clients3.google.com/108.177.15.100 (port 80) after 5000ms: connect failed: ENETUNREACH (Network is unreachable)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:124)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at libcore.io.Posix.connect(Native Method)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge,.java:154)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
10-14 10:15:18.198  5017  5802 W Babel_NetworkConnectionCheckingService: 	... 21 more
10-14 10:15:18.198  5017  5802 I Babel   : connection state changed from DISCONNECTED to CONNECTED
10-14 10:15:18.205   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 10:15:18.226   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 10:15:18.226   929  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-14 10:15:18.226   929  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 10:15:18.227   509   923 D CommandListener: Clearing all IP addresses on wlan0
10-14 10:15:18.228   929   946 D Tethering: MasterInitialState.processMessage what=3
10-14 10:15:18.230  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:18.230  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:18.231  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.231  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:18.232  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:18.232  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:15:18.232  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.232  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:18.233  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:18.233  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:18.233  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.233  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:15:18.238  3928  3928 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-14 10:15:18.240  3751  3751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-14 10:15:18.242  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 10:15:18.242  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 10:15:18.242  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-14 10:15:18.242  5046  5070 E SarControlService: no key has been found,reset the power
10-14 10:15:18.242  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 10:15:18.242  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-14 10:15:18.242  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 10:15:18.243  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:18.243  5071  5071 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 10:15:18.244  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 10:15:18.244  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 10:15:18.244  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 10:15:18.245  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:18.245  5071  5071 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-14 10:15:18.248  3751  3751 D SystemUpdateService: onCreate
,10-14 10:15:18.249  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000ee03000000000000ffffffff]
10-14 10:15:18.249  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:18.249  5071  5085 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-14 10:15:18.249  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-14 10:15:18.250  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-14 10:15:18.252  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000ef03000000000000ffffffff]
10-14 10:15:18.252  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:18.253  5071  5085 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-14 10:15:18.253  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 10:15:18.253  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-14 10:15:18.254  3751  3751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 10:15:18.258  3751  5817 I SystemUpdateService: active receiver: enabled
,10-14 10:15:18.262  3751  3751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-14 10:15:18.267  3751  5413 I iu.UploadsManager: num queued entries: 0
,10-14 10:15:18.268  3751  5413 I iu.UploadsManager: num updated entries: 0
10-14 10:15:18.268  3751  5413 I iu.SyncManager: NEXT; no task
,10-14 10:15:18.270  3751  3751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 10:15:18.271  3751  3751 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 10:15:18.273  5749  5749 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:15:18.276   509   923 E Netd    : netlink response contains error (No such file or directory)
10-14 10:15:18.277  5749  5749 D SprintDMHelper: simOperator: 
10-14 10:15:18.277  5749  5749 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-14 10:15:18.278   929  2973 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-14 10:15:18.278   929  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-14 10:15:18.278   929  2971 D DhcpClient: doQuit
10-14 10:15:18.278  3751  5817 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-14 10:15:18.278   929  5787 D DhcpClient: onQuitting
10-14 10:15:18.278   929  2971 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-14 10:15:18.279  5780  5780 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-14 10:15:18.285  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:18.285  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:18.285  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.285  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:18.286  3751  5817 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-14 10:15:18.286  3751  5817 I SystemUpdateService: now status is 0 (complete)
10-14 10:15:18.286  3751  5817 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-14 10:15:18.286  3751  5817 I SystemUpdateService: file has been verified
10-14 10:15:18.286  3751  5817 I SystemUpdateService: OTA package size = 21989297
10-14 10:15:18.287  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:18.287  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:18.287  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.287  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:18.288  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:18.288  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:18.288  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:18.288  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:15:18.289  5017  5820 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-14 10:15:18.294  5780  5780 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-14 10:15:18.298  5780  5780 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-14 10:15:18.304  3751  5817 I SystemUpdateService: showing system update notification
,10-14 10:15:18.315  3751  3751 D SystemUpdateService: onDestroy
,10-14 10:15:18.333  5780  5780 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 10:15:18.337  5780  5780 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-14 10:15:18.440   929  2971 D wifi    : In wifi stop Hal
,10-14 10:15:18.440   929  2971 D wifi    : halHandle = 0x7f6cd67b80, mVM = 0x7f893cd140, mCls = 0x101a26
,10-14 10:15:18.441   929  5779 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-14 10:15:18.441   929  5779 D WifiHAL : Got a signal to exit!!!
10-14 10:15:18.441   929  5779 I WifiHAL : Exit wifi_event_loop
10-14 10:15:18.443   929  2971 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-14 10:15:18.444   929  2971 E WifiHAL : Event processing terminated
10-14 10:15:18.444   929  2971 D wifi    : In wifi cleaned up handler
10-14 10:15:18.444   929  2971 I WifiHAL : Internal cleanup completed
10-14 10:15:18.445  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:18.446  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:15:18.446  4077  4217 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:15:18.447  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:18.450  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:18.469   929  5779 D wifi    : set interface wlan0 flags (DOWN)
10-14 10:15:18.469   929  2971 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 10:15:18.645   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:18.675   929   946 D Tethering: InitialState.processMessage what=4
,10-14 10:15:18.682   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-14 10:15:19.010   929  2973 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-14 10:15:19.646   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:20.647   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:21.648   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:22.649   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-14 10:15:23.188   929   946 I ActivityManager: Start proc 5824:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-14 10:15:23.268  5824  5824 D AdapterServiceConfig: Adding HeadsetService
,10-14 10:15:23.269  5824  5824 D AdapterServiceConfig: Adding A2dpService
10-14 10:15:23.269  5824  5824 D AdapterServiceConfig: Adding HidService
10-14 10:15:23.269  5824  5824 D AdapterServiceConfig: Adding HealthService
10-14 10:15:23.269  5824  5824 D AdapterServiceConfig: Adding PanService
,10-14 10:15:23.269  5824  5824 D AdapterServiceConfig: Adding GattService
,10-14 10:15:23.270  5824  5824 D AdapterServiceConfig: Adding BluetoothMapService
10-14 10:15:23.270  5824  5824 D AdapterServiceConfig: Adding SapService
,10-14 10:15:23.281   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@64525ff:true
,10-14 10:15:23.281  5824  5824 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 10:15:23.284  5824  5824 I bt_bluedroid: init
10-14 10:15:23.284  5824  5836 I BluetoothAdapterState: Entering OffState
,10-14 10:15:23.286  5824  5837 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-14 10:15:23.286  5824  5837 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 10:15:23.286  5824  5837 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-14 10:15:23.286  5824  5837 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-14 10:15:23.287  5824  5824 I bt_bluedroid: get_profile_interface socket
,10-14 10:15:23.289  5824  5824 I bt_bluedroid: get_profile_interface sdp
,10-14 10:15:23.289  5824  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-14 10:15:23.290  5824  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:15:23.294  5824  5835 I bt_bluedroid: config_hci_snoop_log
,10-14 10:15:23.295   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-14 10:15:23.299  5824  5836 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 10:15:23.299  5824  5836 D BluetoothAdapterProperties: Setting state to 14
10-14 10:15:23.299  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-14 10:15:23.301  5824  5836 D BluetoothBondStateMachine: make
,10-14 10:15:23.303  5824  5841 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 10:15:23.306  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:15:23.307  5824  5824 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-14 10:15:23.309  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:23.310  5824  5824 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-14 10:15:23.310  5824  5824 D BtGatt.GattService: Received start request. Starting profile...
,10-14 10:15:23.310  5824  5824 D BtGatt.GattService: start()
10-14 10:15:23.311  5824  5824 I bt_bluedroid: get_profile_interface gatt
10-14 10:15:23.312  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:23.312  5824  5824 D BtGatt.AdvertiseManager: advertise manager created
,10-14 10:15:23.317  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:23.317  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:23.317  5824  5824 V BluetoothAdapterState: isBleTurningOn()=true
10-14 10:15:23.317  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:23.317  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 10:15:23.319  5824  5836 I bt_bluedroid: bt_bluedroid
,10-14 10:15:23.319  5824  5837 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-14 10:15:23.319  5824  5837 I bt_hci  : start_up
,10-14 10:15:23.325  5824  5837 I bt_vendor: alloc value 0xf3e09871
10-14 10:15:23.325  5824  5837 I bt_vendor: init
,10-14 10:15:23.325  5824  5837 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 10:15:23.325  5824  5837 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 10:15:23.436  5824  5837 D bt_hci  : start_up starting async portion
,10-14 10:15:23.436  5824  5844 I bt_hci  : event_finish_startup
10-14 10:15:23.436  5824  5844 I bt_hci_h4: hal_open
10-14 10:15:23.436  5824  5844 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-14 10:15:23.438  5824  5844 I bt_userial_vendor: device fd = 54 open
10-14 10:15:23.433  5845  5845 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:15:23.451  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:15:23.453  5824  5844 D bt_hwcfg: Chipset BCM4358A3
,10-14 10:15:23.454  5824  5844 D bt_hwcfg: Target name = [BCM4358A3]
10-14 10:15:23.454  5824  5844 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 10:15:23.851  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-14 10:15:23.851  5824  5844 D bt_hwcfg: Settlement delay -- 100 ms
10-14 10:15:23.851  5824  5844 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 10:15:23.985  5824  5844 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:15:23.985  5824  5844 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-14 10:15:23.987  5824  5844 I bt_hwcfg: vendor lib fwcfg completed
10-14 10:15:23.987  5824  5844 I bt_vendor: firmware callback
10-14 10:15:23.987  5824  5844 I bt_hci  : firmware_config_callback
,10-14 10:15:23.996  5824  5847 I bt_btu  : btu_task pending for preload complete event
,10-14 10:15:23.996  5824  5847 I bt_btu_task: Bluetooth chip preload is complete
10-14 10:15:23.996  5824  5847 I bt_btu  : btu_task received preload complete event
,10-14 10:15:24.004  5824  5847 I         : BTE_InitTraceLevels -- TRC_HCI
,10-14 10:15:24.004  5824  5847 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-14 10:15:24.004  5824  5847 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,10-14 10:15:24.004  5824  5847 I         : BTE_InitTraceLevels -- TRC_AVDT
10-14 10:15:24.004  5824  5847 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_A2D
10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTM
,10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_PAN
10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_SDP
10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 10:15:24.005  5824  5847 I         : BTE_InitTraceLevels -- TRC_SMP
,10-14 10:15:24.006  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-14 10:15:24.006  5824  5847 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 10:15:24.092  5824  5847 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d87549
,10-14 10:15:24.093  5824  5847 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d87549 
,10-14 10:15:24.112  5824  5840 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 10:15:24.112  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 10:15:24.113  5824  5840 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 10:15:24.115  5824  5840 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:15:24.118  5824  5840 D BluetoothAdapterProperties: Scan Mode:20
,10-14 10:15:24.119  5824  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 10:15:24.119  5824  5840 D bt_hci  : do_postload posting postload work item
10-14 10:15:24.119  5824  5844 I bt_hci  : event_postload
10-14 10:15:24.119  5824  5844 I bt_vendor: sco_config_cb
,10-14 10:15:24.119  5824  5844 I bt_hci  : sco_config_callback postload finished.
,10-14 10:15:24.124  5824  5840 D bt_bte_conf: Device ID record 1 : primary
,10-14 10:15:24.124  5824  5840 D bt_bte_conf:   vendorId            = 000f
10-14 10:15:24.124  5824  5840 D bt_bte_conf:   vendorIdSource      = 0001
10-14 10:15:24.125  5824  5840 D bt_bte_conf:   product             = 1200
10-14 10:15:24.125  5824  5840 D bt_bte_conf:   version             = 1436
10-14 10:15:24.125  5824  5840 D bt_bte_conf:   clientExecutableURL = 
10-14 10:15:24.125  5824  5840 D bt_bte_conf:   serviceDescription  = 
10-14 10:15:24.125  5824  5840 D bt_bte_conf:   documentationURL    = 
10-14 10:15:24.125  5824  5840 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-14 10:15:24.125  5824  5837 D bt_stack_manager: event_start_up_stack finished
,10-14 10:15:24.126  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:24.126  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 10:15:24.126  5824  5836 D BluetoothAdapterProperties: Setting state to 15
10-14 10:15:24.126  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-14 10:15:24.127  5824  5836 I BluetoothAdapterState: Entering BleOnState
10-14 10:15:24.128  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:24.129  5824  5844 I bt_vendor: low_power_mode_cb
,10-14 10:15:24.131  5824  5836 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-14 10:15:24.131  5824  5836 D BluetoothAdapterProperties: Setting state to 11
10-14 10:15:24.131  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-14 10:15:24.133  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:24.135  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:24.136  5824  5824 D HeadsetService: Received start request. Starting profile...
10-14 10:15:24.138  5824  5824 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-14 10:15:24.139  5824  5824 D HeadsetStateMachine: make
,10-14 10:15:24.141  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:24.142  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:24.143  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:24.149  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:15:24.154  5824  5824 D HeadsetStateMachine: max_hf_connections = 1
,10-14 10:15:24.154  5824  5824 I bt_bluedroid: get_profile_interface handsfree
10-14 10:15:24.154  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-14 10:15:24.154  5824  5840 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-14 10:15:24.156  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:24.157  5824  5824 D A2dpService: Received start request. Starting profile...
,10-14 10:15:24.158  5824  5824 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-14 10:15:24.158  5824  5824 I bt_bluedroid: get_profile_interface avrcp
,10-14 10:15:24.162  5824  5824 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-14 10:15:24.163  5824  5824 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-14 10:15:24.163  5824  5824 D A2dpStateMachine: make
,10-14 10:15:24.164  5824  5824 I bt_bluedroid: get_profile_interface a2dp
10-14 10:15:24.164  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-14 10:15:24.165  5824  5856 D A2dpStateMachine: Enter Disconnected: -2
,10-14 10:15:24.167  5824  5824 I BluetoothHidServiceJni: classInitNative: succeeds
10-14 10:15:24.167  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:24.168  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:15:24.169  5824  5824 D HidService: Received start request. Starting profile...
,10-14 10:15:24.169  5824  5824 I bt_bluedroid: get_profile_interface hidhost
10-14 10:15:24.169  5824  5824 D HidService: setHidService(): set to: null
10-14 10:15:24.169  5682  5682 D BluetoothInputDevice: Proxy object connected
10-14 10:15:24.169  5824  5840 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d6856d
10-14 10:15:24.169  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-14 10:15:24.170  5824  5824 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-14 10:15:24.170  5682  5682 D HidProfile: Bluetooth service connected
10-14 10:15:24.170  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:24.171  5824  5824 D HealthService: Received start request. Starting profile...
,10-14 10:15:24.172  5824  5824 I bt_bluedroid: get_profile_interface health
10-14 10:15:24.173  5824  5824 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-14 10:15:24.173  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:24.175  5682  5682 D BluetoothPan: BluetoothPAN Proxy object connected
,10-14 10:15:24.175  5682  5682 D PanProfile: Bluetooth service connected
10-14 10:15:24.176  5824  5824 D PanService: Received start request. Starting profile...
10-14 10:15:24.176  5824  5824 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 10:15:24.176  5824  5824 I bt_bluedroid: get_profile_interface pan
10-14 10:15:24.176  5824  5840 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-14 10:15:24.178  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:24.179  5682  5682 D BluetoothMap: Proxy object connected
,10-14 10:15:24.179  5824  5824 D BluetoothMapService: Received start request. Starting profile...
10-14 10:15:24.179  5824  5824 D BluetoothMapService: start()
10-14 10:15:24.180  5682  5682 D MapProfile: Bluetooth service connected
10-14 10:15:24.180  5682  5682 D BluetoothMap: getConnectedDevices()
10-14 10:15:24.181  5682  5682 D BluetoothMap: Bluetooth is Not enabled
,10-14 10:15:24.182  5824  5824 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-14 10:15:24.182  5824  5824 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 10:15:24.183  5824  5824 D BluetoothMapAppObserver: createReceiver()
,10-14 10:15:24.184  5824  5824 D BluetoothMapAppObserver: initObservers()
,10-14 10:15:24.184  5824  5824 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-14 10:15:24.189  5824  5824 V SapService: SapBinder()
,10-14 10:15:24.189  5824  5824 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:24.190  5824  5824 D SapService: Received start request. Starting profile...
10-14 10:15:24.190  5824  5824 V SapService: start()
,10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:24.193  5824  5854 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:24.193  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:24.194  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:24.195  5824  5824 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:24.195  5824  5824 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:24.195  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:24.195  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:24.195  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-14 10:15:24.195  5824  5836 D BluetoothAdapterProperties: ScanMode =  20
10-14 10:15:24.195  5824  5836 D BluetoothAdapterProperties: State =  11
10-14 10:15:24.196  5824  5836 D BluetoothAdapterProperties: Setting state to 12
10-14 10:15:24.196  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-14 10:15:24.197  5824  5836 I BluetoothAdapterState: Entering OnState
,10-14 10:15:24.198  5824  5840 D BluetoothAdapterProperties: Scan Mode:21
10-14 10:15:24.198  5682  5696 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 10:15:24.198  5824  5840 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 10:15:24.198  5629  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 10:15:24.199  5682  5694 D BluetoothMap: onBluetoothStateChange: up=true
10-14 10:15:24.200  3138  3150 D BluetoothPan: onBluetoothStateChange on: true
10-14 10:15:24.202   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:15:24.202  3138  3138 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 10:15:24.202   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:15:24.202  3138  3138 D PanProfile: Bluetooth service connected
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:24.202  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:24.203  3822  3838 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:15:24.203   929   929 D BluetoothA2dp: Proxy object connected
10-14 10:15:24.203  3138  3152 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:15:24.204  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:24.205  3138  3978 D BluetoothMap: onBluetoothStateChange: up=true
10-14 10:15:24.205  3138  3138 D BluetoothA2dp: Proxy object connected
,10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:24.208  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:15:24.208  3138  3138 D BluetoothMap: Proxy object connected
10-14 10:15:24.208  3138  3150 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:15:24.208  3138  3138 D MapProfile: Bluetooth service connected
10-14 10:15:24.208  3138  3138 D BluetoothMap: getConnectedDevices()
10-14 10:15:24.209  3138  3152 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 10:15:24.209  5824  5824 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 10:15:24.210  5824  5824 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-14 10:15:24.210  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:24.210   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:15:24.211  5682  5696 D BluetoothPan: onBluetoothStateChange on: true
10-14 10:15:24.211  5682  5694 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 10:15:24.211  3138  3978 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 10:15:24.212  5824  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:15:24.213  3138  3138 D BluetoothInputDevice: Proxy object connected
,10-14 10:15:24.213   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:15:24.213  3138  3138 D HidProfile: Bluetooth service connected
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:24.213  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:24.214   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 10:15:24.215  5824  5824 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:15:24.216  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:24.217  5629  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 10:15:24.218  5682  5682 D LocalBluetoothProfileManager: Adding local A2DP profile
10-14 10:15:24.218  5824  5824 D ObexServerSockets: Succeed to create listening sockets 
,10-14 10:15:24.218  5824  5824 D ObexServerSockets0: startAccept()
10-14 10:15:24.219  5824  5824 D ObexServerSockets0: prepareForNewConnect()
10-14 10:15:24.220  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:24.221  5824  5824 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,10-14 10:15:24.221  5824  5824 D BluetoothSdpJni: SDP Create record success - handle: 0
10-14 10:15:24.221  5824  5824 D BluetoothMapService: onReceive
10-14 10:15:24.221  5824  5824 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 10:15:24.221  5824  5824 D BluetoothMapService: STATE_ON
10-14 10:15:24.222  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:24.222  5682  5682 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-14 10:15:24.223  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:24.223  5824  5863 D ObexServerSockets0: Accepting socket connection...
10-14 10:15:24.224  5824  5862 D ObexServerSockets0: Accepting socket connection...
10-14 10:15:24.225  5824  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:15:24.227  5824  5864 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-14 10:15:24.227  5824  5864 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-14 10:15:24.230  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 10:15:24.232  5682  5682 D BluetoothA2dp: Proxy object connected
,10-14 10:15:24.238  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:15:24.238  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:15:24.245  3138  3138 D BluetoothPbap: Proxy object connected
,10-14 10:15:24.245  5682  5682 D BluetoothPbap: Proxy object connected
10-14 10:15:24.245  3138  3138 D PbapServerProfile: Bluetooth service connected
,10-14 10:15:24.245  5682  5682 D PbapServerProfile: Bluetooth service connected
,10-14 10:15:24.246  5824  5824 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 10:15:24.246  5824  5824 D ObexServerSockets0: prepareForNewConnect()
,10-14 10:15:24.254  5824  5868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:15:24.267  5824  5872 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:15:24.268  5824  5872 I BtOppRfcommListener: Accept thread started.
,10-14 10:15:24.304  3822  3841 D BluetoothHeadset: Proxy object connected
,10-14 10:15:24.304  3138  3978 D BluetoothHeadset: Proxy object connected
10-14 10:15:24.304  3138  3138 D HeadsetProfile: Bluetooth service connected
10-14 10:15:24.305   929   929 D BluetoothHeadset: Proxy object connected
10-14 10:15:24.305   929   929 D BluetoothHeadset: Proxy object connected
,10-14 10:15:24.305   929   929 D BluetoothHeadset: Proxy object connected
,10-14 10:15:24.308  3138  3150 D BluetoothHeadset: Proxy object connected
10-14 10:15:24.308  3138  3138 D HeadsetProfile: Bluetooth service connected
,10-14 10:15:24.310   929   946 D BluetoothHeadset: Proxy object connected
,10-14 10:15:24.313   929   946 D BluetoothHeadset: Proxy object connected
,10-14 10:15:24.325  5682  5694 D BluetoothHeadset: Proxy object connected
,10-14 10:15:24.326  5682  5682 D HeadsetProfile: Bluetooth service connected
,10-14 10:15:25.966   929  2973 D ConnectivityService: handlePromptUnvalidated 101
,10-14 10:15:28.168  5824  5836 D BluetoothAdapterState: Current state: ON, message: 23
,10-14 10:15:28.168  5824  5836 D BluetoothAdapterProperties: Setting state to 13
10-14 10:15:28.169  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-14 10:15:28.170  5824  5836 D BluetoothAdapterProperties: onBluetoothDisable()
10-14 10:15:28.175  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:15:28.175  5824  5824 D BluetoothMapService: onReceive
,10-14 10:15:28.175  5824  5824 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 10:15:28.176  5824  5824 D BluetoothMapService: STATE_TURNING_OFF
10-14 10:15:28.177  5824  5824 D BluetoothMapService: MAP Service closeService in
10-14 10:15:28.178  5824  5824 D BluetoothMapMasInstance0: MAP Service shutdown
10-14 10:15:28.178  5824  5824 D ObexServerSockets0: shutdown(block = true)
10-14 10:15:28.179  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:28.179  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:15:28.181  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:28.181  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:28.182  5824  5824 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:15:28.183  5824  5849 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-14 10:15:28.183  5824  5824 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 10:15:28.184  5824  5862 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-14 10:15:28.184  5824  5863 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 10:15:28.184  5824  5840 D BluetoothAdapterProperties: Scan Mode:20
,10-14 10:15:28.186  5824  5824 I BtOppRfcommListener: stopping Accept Thread
10-14 10:15:28.186  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-14 10:15:28.188  5824  5872 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-14 10:15:28.188  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:28.188  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:28.189  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 10:15:28.190  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:28.190  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:28.191  5824  5872 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-14 10:15:28.196  5824  5824 D HeadsetService: Received stop request...Stopping profile...
10-14 10:15:28.196  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:28.196  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:28.197  5629  5629 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 10:15:28.197  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:28.197  5682  5682 D DockEventReceiver: finishStartingService: stopping service
10-14 10:15:28.199  3822  4912 D BluetoothHeadset: Proxy object ,disconnected
10-14 10:15:28.199  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.199  3138  3978 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:28.200   929   929 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:28.200   929   929 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:28.200   929   929 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:28.199  5824  5824 D A2dpService: Received stop request...Stopping profile...
10-14 10:15:28.201  5824  5856 D A2dpStateMachine: Exit Disconnected: -1
10-14 10:15:28.201  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.201  5682  5694 D BluetoothHeadset: Proxy object disconnected
10-14 10:15:28.202   929   929 D BluetoothA2dp: Proxy object disconnected
10-14 10:15:28.203  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.203  5682  5682 D HeadsetProfile: Bluetooth service disconnected
10-14 10:15:28.204  5682  5682 D BluetoothA2dp: Proxy object disconnected
,10-14 10:15:28.207  5824  5824 D HidService: Received stop request...Stopping profile...
,10-14 10:15:28.207  5824  5824 D HidService: Stopping Bluetooth HidService
10-14 10:15:28.208  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 10:15:28.209  5682  5682 D BluetoothInputDevice: Proxy object disconnected
10-14 10:15:28.209  5682  5682 D HidProfile: Bluetooth service disconnected
10-14 10:15:28.210  5824  5824 D HealthService: Received stop request...Stopping profile...
,10-14 10:15:28.212  5824  5824 V BluetoothAdapterState: isTurningOff()=true
,10-14 10:15:28.212  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.212  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.213  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:28.213  3138  3138 D HeadsetProfile: Bluetooth service disconnected
10-14 10:15:28.214  3138  3138 D BluetoothA2dp: Proxy object disconnected
10-14 10:15:28.214  3138  3138 D BluetoothInputDevice: Proxy object disconnected
10-14 10:15:28.214  3138  3138 D HidProfile: Bluetooth service disconnected
10-14 10:15:28.215  5824  5824 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-14 10:15:28.215  5824  5824 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-14 10:15:28.215  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-14 10:15:28.215  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-14 10:15:28.215  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:28.215  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:28.215  5824  5824 D PanService: Received stop request...Stopping profile...
10-14 10:15:28.215  5824  5840 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-14 10:15:28.216  3138  3138 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 10:15:28.216  3138  3138 D PanProfile: Bluetooth service disconnected
,10-14 10:15:28.217  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:28.217  5682  5682 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 10:15:28.217  5682  5682 D PanProfile: Bluetooth service disconnected
10-14 10:15:28.217  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.217  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.217  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:28.218  5824  5824 D BluetoothMapService: Received stop request...Stopping profile...
10-14 10:15:28.218  5824  5824 D BluetoothMapService: stop()
10-14 10:15:28.218  5824  5824 D BluetoothMapAppObserver: deinitObservers()
10-14 10:15:28.218  5824  5824 D BluetoothMapAppObserver: removeReceiver()
10-14 10:15:28.220  3138  3138 D BluetoothMap: Proxy object disconnected
10-14 10:15:28.221  3138  3138 D MapProfile: Bluetooth service disconnected
10-14 10:15:28.221  5682  5682 D BluetoothMap: Proxy object disconnected
10-14 10:15:28.221  5682  5682 D MapProfile: Bluetooth service disconnected
10-14 10:15:28.221  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-14 10:15:28.221  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:28.221  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-14 10:15:28.222  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 10:15:28.222  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-14 10:15:28.222  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 10:15:28.222  5824  5847 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-14 10:15:28.225  5824  5824 D SapService: Received stop request...Stopping profile...
10-14 10:15:28.225  5824  5824 V SapService: stop()
,10-14 10:15:28.227  3138  3138 D BluetoothPbap: Proxy object disconnected
10-14 10:15:28.227  3138  3138 D PbapServerProfile: Bluetooth service disconnected
,10-14 10:15:28.228  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:28.228  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.228  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.228  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:28.228  5824  5824 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-14 10:15:28.228  5824  5824 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-14 10:15:28.229  5824  5840 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 10:15:28.229  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:28.229  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.229  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.229  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:28.229  5824  5824 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,10-14 10:15:28.230  5824  5824 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 10:15:28.230  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:28.230  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.230  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.230  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:28.230  5824  5824 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-14 10:15:28.231  5824  5824 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-14 10:15:28.231  5824  5824 D BluetoothMapService: MAP Service closeService in
10-14 10:15:28.231  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:28.231  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.231  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.231  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:28.231  5682  5682 D BluetoothPbap: Proxy object disconnected
10-14 10:15:28.231  5682  5682 D PbapServerProfile: Bluetooth service disconnected
10-14 10:15:28.232  5824  5824 D BluetoothMapService: cleanup()
10-14 10:15:28.232  5824  5824 D BluetoothMapService: MAP Service closeService in
,10-14 10:15:28.232  5824  5824 V BluetoothAdapterState: isTurningOff()=true
10-14 10:15:28.232  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.232  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.232  5824  5824 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:28.232  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 10:15:28.232  5824  5840 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-14 10:15:28.232  5824  5836 D BluetoothAdapterProperties: Setting state to 15
10-14 10:15:28.232  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 10:15:28.233  5824  5836 I BluetoothAdapterState: Entering BleOnState
10-14 10:15:28.234  5682  5694 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 10:15:28.235  5682  5696 D BluetoothMap: onBluetoothStateChange: up=false
10-14 10:15:28.235  3138  3978 D BluetoothPan: onBluetoothStateChange on: false
10-14 10:15:28.235   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-14 10:15:28.236   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-14 10:15:28.236  3822  4147 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:28.236  3138  3152 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 10:15:28.237  5682  5694 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 10:15:28.237  3138  3150 D BluetoothMap: onBluetoothStateChange: up=false
10-14 10:15:28.238  3138  3978 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:28.238  3138  3152 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 10:15:28.239   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:28.239  5682  5696 D BluetoothPan: onBluetoothStateChange on: false
10-14 10:15:28.240  5682  5694 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 10:15:28.240  5682  5696 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 10:15:28.241  3138  3150 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 10:15:28.241   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-14 10:15:28.241  5824  5836 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-14 10:15:28.242  5824  5836 D BluetoothAdapterProperties: Setting state to 16
10-14 10:15:28.242  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-14 10:15:28.242  5824  5836 D BluetoothAdapterProperties: onBleDisable
10-14 10:15:28.242  5824  5836 I BluetoothAdapterState: Entering PendingCommandState
10-14 10:15:28.242  5824  5837 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 10:15:28.243  5824  5847 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 10:15:28.243  5824  5847 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 10:15:28.245  5824  5840 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:15:28.245  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 10:15:28.247  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.248  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.250  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:28.251  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:15:28.251  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.253  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.256  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:28.257  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:15:28.448  5824  5840 I bt_hci  : shut_down
,10-14 10:15:28.452  5824  5844 D bt_hwcfg: hw_epilog_process
,10-14 10:15:28.452  5824  5844 I bt_vendor: low_power_mode_cb
,10-14 10:15:28.454  5824  5844 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-14 10:15:28.454  5824  5844 I bt_vendor: epilog_cb
10-14 10:15:28.454  5824  5844 I bt_hci  : epilog_finished_callback
,10-14 10:15:28.456  5824  5840 I bt_hci_h4: hal_close
10-14 10:15:28.457  5824  5840 I bt_userial_vendor: device fd = 54 close
,10-14 10:15:28.566  5824  5837 D bt_stack_manager: event_shut_down_stack finished.
10-14 10:15:28.566  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-14 10:15:28.571  5824  5836 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-14 10:15:28.571  5824  5824 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 10:15:28.572  5824  5824 D BtGatt.GattService: Received stop request...Stopping profile...
10-14 10:15:28.572  5824  5824 D BtGatt.GattService: stop()
10-14 10:15:28.572  5824  5824 D BtGatt.AdvertiseManager: advertise clients cleared
,10-14 10:15:28.574  5824  5824 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:15:28.575  5824  5824 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:28.575  5824  5824 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:28.575  5824  5824 V BluetoothAdapterState: isBleTurningOff()=true
,10-14 10:15:28.575  5824  5836 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 10:15:28.575  5824  5836 D BluetoothAdapterProperties: Setting state to 10
10-14 10:15:28.576  5824  5836 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-14 10:15:28.577  5824  5836 I BluetoothAdapterState: Entering OffState
10-14 10:15:28.578   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-14 10:15:28.590  5824  5824 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-14 10:15:28.590  5824  5824 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 10:15:28.590  5824  5824 I BluetoothServiceJni: cleanupNative: return from cleanup
10-14 10:15:28.592  5824  5837 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-14 10:15:28.599  5824  5824 I art     : System.exit called, status: 0
,10-14 10:15:28.599  5824  5824 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 10:15:28.629   929   939 I ActivityManager: Process com.android.bluetooth (pid 5824) has died
,10-14 10:15:33.166  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 10:15:33.167  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:33.172  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:33.172  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7832d3e removed from the list
,10-14 10:15:33.172  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:33.173  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:33.173  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:33.177  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 10:15:33.177  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1cf0ec added. We now have 4 listener(s)
10-14 10:15:33.177  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:15:33.179  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:15:33.179  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1cf0ec removed from the list
10-14 10:15:33.179  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:33.179  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:33.180  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:33.182  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:33.182  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@342acb5 added. We now have 4 listener(s)
10-14 10:15:33.182  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 10:15:38.194  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:38.230   929   946 I ActivityManager: Start proc 5880:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-14 10:15:38.314  5880  5880 D AdapterServiceConfig: Adding HeadsetService
,10-14 10:15:38.314  5880  5880 D AdapterServiceConfig: Adding A2dpService
10-14 10:15:38.314  5880  5880 D AdapterServiceConfig: Adding HidService
10-14 10:15:38.314  5880  5880 D AdapterServiceConfig: Adding HealthService
10-14 10:15:38.314  5880  5880 D AdapterServiceConfig: Adding PanService
10-14 10:15:38.314  5880  5880 D AdapterServiceConfig: Adding GattService
10-14 10:15:38.314  5880  5880 D AdapterServiceConfig: Adding BluetoothMapService
10-14 10:15:38.315  5880  5880 D AdapterServiceConfig: Adding SapService
,10-14 10:15:38.324   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@def688c:true
,10-14 10:15:38.325  5880  5880 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 10:15:38.328  5880  5880 I bt_bluedroid: init
,10-14 10:15:38.328  5880  5892 I BluetoothAdapterState: Entering OffState
,10-14 10:15:38.330  5880  5893 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-14 10:15:38.331  5880  5893 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 10:15:38.331  5880  5893 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-14 10:15:38.331  5880  5893 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-14 10:15:38.332  5880  5880 I bt_bluedroid: get_profile_interface socket
,10-14 10:15:38.333  5880  5896 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-14 10:15:38.334  5880  5880 I bt_bluedroid: get_profile_interface sdp
,10-14 10:15:38.335  5880  5896 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:15:38.339  5880  5891 I bt_bluedroid: config_hci_snoop_log
10-14 10:15:38.340   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
10-14 10:15:38.344  5880  5892 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 10:15:38.344  5880  5892 D BluetoothAdapterProperties: Setting state to 14
10-14 10:15:38.344  5880  5892 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-14 10:15:38.346  5880  5892 D BluetoothBondStateMachine: make
,10-14 10:15:38.348  5880  5897 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 10:15:38.350  5880  5892 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:15:38.352  5880  5880 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-14 10:15:38.354  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:38.354  5880  5880 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 10:15:38.355  5880  5880 D BtGatt.GattService: Received start request. Starting profile...
10-14 10:15:38.355  5880  5880 D BtGatt.GattService: start()
10-14 10:15:38.355  5880  5880 I bt_bluedroid: get_profile_interface gatt
,10-14 10:15:38.356  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:38.356  5880  5880 D BtGatt.AdvertiseManager: advertise manager created
,10-14 10:15:38.363  5880  5880 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:38.363  5880  5880 V BluetoothAdapterState: isTurningOn()=false
10-14 10:15:38.363  5880  5880 V BluetoothAdapterState: isBleTurningOn()=true
,10-14 10:15:38.363  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:38.364  5880  5892 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 10:15:38.365  5880  5892 I bt_bluedroid: bt_bluedroid
,10-14 10:15:38.365  5880  5893 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-14 10:15:38.366  5880  5893 I bt_hci  : start_up
,10-14 10:15:38.371  5880  5893 I bt_vendor: alloc value 0xf3e09871
10-14 10:15:38.371  5880  5893 I bt_vendor: init
,10-14 10:15:38.371  5880  5893 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 10:15:38.371  5880  5893 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 10:15:38.481  5880  5893 D bt_hci  : start_up starting async portion
,10-14 10:15:38.482  5880  5900 I bt_hci  : event_finish_startup
10-14 10:15:38.482  5880  5900 I bt_hci_h4: hal_open
,10-14 10:15:38.482  5880  5900 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-14 10:15:38.480  5901  5901 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-14 10:15:38.485  5880  5900 I bt_userial_vendor: device fd = 54 open
,10-14 10:15:38.499  5880  5900 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:15:38.501  5880  5900 D bt_hwcfg: Chipset BCM4358A3
,10-14 10:15:38.502  5880  5900 D bt_hwcfg: Target name = [BCM4358A3]
10-14 10:15:38.502  5880  5900 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 10:15:38.899  5880  5900 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-14 10:15:38.899  5880  5900 D bt_hwcfg: Settlement delay -- 100 ms
10-14 10:15:38.900  5880  5900 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 10:15:39.033  5880  5900 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 10:15:39.034  5880  5900 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-14 10:15:39.036  5880  5900 I bt_hwcfg: vendor lib fwcfg completed
,10-14 10:15:39.036  5880  5900 I bt_vendor: firmware callback
10-14 10:15:39.036  5880  5900 I bt_hci  : firmware_config_callback
10-14 10:15:39.044  5880  5903 I bt_btu  : btu_task pending for preload complete event
10-14 10:15:39.044  5880  5903 I bt_btu_task: Bluetooth chip preload is complete
,10-14 10:15:39.044  5880  5903 I bt_btu  : btu_task received preload complete event
,10-14 10:15:39.053  5880  5903 I         : BTE_InitTraceLevels -- TRC_HCI
,10-14 10:15:39.053  5880  5903 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-14 10:15:39.053  5880  5903 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_AVDT
10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_AVRC
10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_A2D
10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_BTM
10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_PAN
10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_SDP
,10-14 10:15:39.054  5880  5903 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 10:15:39.055  5880  5903 I         : BTE_InitTraceLevels -- TRC_SMP
10-14 10:15:39.055  5880  5903 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-14 10:15:39.055  5880  5903 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 10:15:39.136  5880  5903 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d87549
10-14 10:15:39.136  5880  5903 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d87549 
,10-14 10:15:39.156  5880  5896 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 10:15:39.158  5880  5896 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 10:15:39.158  5880  5896 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 10:15:39.160  5880  5896 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 10:15:39.163  5880  5896 D BluetoothAdapterProperties: Scan Mode:20
10-14 10:15:39.163  5880  5896 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 10:15:39.163  5880  5896 D bt_hci  : do_postload posting postload work item
10-14 10:15:39.164  5880  5900 I bt_hci  : event_postload
10-14 10:15:39.164  5880  5900 I bt_vendor: sco_config_cb
10-14 10:15:39.164  5880  5900 I bt_hci  : sco_config_callback postload finished.
,10-14 10:15:39.167  5880  5896 D bt_bte_conf: Device ID record 1 : primary
,10-14 10:15:39.167  5880  5896 D bt_bte_conf:   vendorId            = 000f
10-14 10:15:39.167  5880  5896 D bt_bte_conf:   vendorIdSource      = 0001
,10-14 10:15:39.167  5880  5896 D bt_bte_conf:   product             = 1200
10-14 10:15:39.167  5880  5896 D bt_bte_conf:   version             = 1436
10-14 10:15:39.167  5880  5896 D bt_bte_conf:   clientExecutableURL = 
10-14 10:15:39.167  5880  5896 D bt_bte_conf:   serviceDescription  = 
10-14 10:15:39.167  5880  5896 D bt_bte_conf:   documentationURL    = 
10-14 10:15:39.167  5880  5896 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-14 10:15:39.167  5880  5893 D bt_stack_manager: event_start_up_stack finished
10-14 10:15:39.168  5880  5892 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 10:15:39.168  5880  5892 D BluetoothAdapterProperties: Setting state to 15
10-14 10:15:39.168  5880  5892 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,10-14 10:15:39.171  5880  5892 I BluetoothAdapterState: Entering BleOnState
10-14 10:15:39.172  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:39.173  5880  5900 I bt_vendor: low_power_mode_cb
10-14 10:15:39.174  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:39.174  5880  5892 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-14 10:15:39.174  5880  5892 D BluetoothAdapterProperties: Setting state to 11
10-14 10:15:39.174  5880  5892 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-14 10:15:39.179  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:39.181  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:39.181  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:39.182  5880  5880 D HeadsetService: Received start request. Starting profile...
10-14 10:15:39.185  5880  5880 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-14 10:15:39.185  5880  5880 D HeadsetStateMachine: make
,10-14 10:15:39.193  5880  5892 I BluetoothAdapterState: Entering PendingCommandState
,10-14 10:15:39.199  5880  5880 D HeadsetStateMachine: max_hf_connections = 1
,10-14 10:15:39.200  5880  5880 I bt_bluedroid: get_profile_interface handsfree
10-14 10:15:39.200  5880  5896 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-14 10:15:39.200  5880  5896 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-14 10:15:39.204  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:39.204  5880  5880 D A2dpService: Received start request. Starting profile...
,10-14 10:15:39.205  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:15:39.205  5880  5880 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-14 10:15:39.205  5880  5880 I bt_bluedroid: get_profile_interface avrcp
,10-14 10:15:39.211  5880  5880 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-14 10:15:39.211  5880  5880 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-14 10:15:39.211  5880  5880 D A2dpStateMachine: make
10-14 10:15:39.212  5880  5880 I bt_bluedroid: get_profile_interface a2dp
,10-14 10:15:39.212  5880  5896 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-14 10:15:39.214  5880  5912 D A2dpStateMachine: Enter Disconnected: -2
10-14 10:15:39.214  5880  5880 I BluetoothHidServiceJni: classInitNative: succeeds
10-14 10:15:39.215  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:39.216  5880  5880 D HidService: Received start request. Starting profile...
10-14 10:15:39.216  5880  5880 I bt_bluedroid: get_profile_interface hidhost
,10-14 10:15:39.217  5880  5896 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d6856d
10-14 10:15:39.217  5880  5880 D HidService: setHidService(): set to: null
10-14 10:15:39.217  5880  5896 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-14 10:15:39.217  5880  5880 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-14 10:15:39.218  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:39.219  5880  5880 D HealthService: Received start request. Starting profile...
,10-14 10:15:39.220  5880  5880 I bt_bluedroid: get_profile_interface health
,10-14 10:15:39.221  5880  5880 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-14 10:15:39.221  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:39.222  5880  5880 D PanService: Received start request. Starting profile...
10-14 10:15:39.222  5880  5880 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 10:15:39.222  5880  5880 I bt_bluedroid: get_profile_interface pan
10-14 10:15:39.222  5880  5896 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-14 10:15:39.224  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:39.225  5880  5880 D BluetoothMapService: Received start request. Starting profile...
10-14 10:15:39.225  5880  5880 D BluetoothMapService: start()
10-14 10:15:39.228  5880  5880 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-14 10:15:39.228  5880  5880 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 10:15:39.228  5880  5880 D BluetoothMapAppObserver: createReceiver()
,10-14 10:15:39.230  5880  5880 D BluetoothMapAppObserver: initObservers()
,10-14 10:15:39.230  5880  5880 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-14 10:15:39.236  5880  5880 V SapService: SapBinder()
,10-14 10:15:39.236  5880  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
,10-14 10:15:39.237  5880  5880 D SapService: Received start request. Starting profile...
,10-14 10:15:39.237  5880  5880 V SapService: start()
,10-14 10:15:39.241  5880  5880 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:15:39.241  5880  5880 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:39.241  5880  5910 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-14 10:15:39.241  5880  5880 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:39.241  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:39.242  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isTurningOff()=false
,10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 10:15:39.243  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
10-14 10:15:39.244  5880  5880 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:39.244  5880  5880 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:39.244  5880  5880 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:39.244  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:39.245  5880  5880 V BluetoothAdapterState: isTurningOff()=false
10-14 10:15:39.245  5880  5880 V BluetoothAdapterState: isTurningOn()=true
10-14 10:15:39.245  5880  5880 V BluetoothAdapterState: isBleTurningOn()=false
10-14 10:15:39.245  5880  5880 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 10:15:39.246  5880  5892 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-14 10:15:39.246  5880  5892 D BluetoothAdapterProperties: ScanMode =  20
10-14 10:15:39.246  5880  5892 D BluetoothAdapterProperties: State =  11
10-14 10:15:39.246  5880  5892 D BluetoothAdapterProperties: Setting state to 12
10-14 10:15:39.246  5880  5892 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-14 10:15:39.247  5682  5696 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 10:15:39.247  5880  5896 D BluetoothAdapterProperties: Scan Mode:21
10-14 10:15:39.247  5880  5896 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 10:15:39.247  5880  5892 I BluetoothAdapterState: Entering OnState
10-14 10:15:39.247  5629  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-14 10:15:39.249  5682  5694 D BluetoothMap: onBluetoothStateChange: up=true
,10-14 10:15:39.251  3138  3978 D BluetoothPan: onBluetoothStateChange on: true
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:39.252  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:39.253   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:15:39.253   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-14 10:15:39.254  3822  3838 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:15:39.254  3138  3138 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 10:15:39.254  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:39.255  3138  3138 D PanProfile: Bluetooth service connected
10-14 10:15:39.255  3138  3152 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:15:39.255   929   929 D BluetoothA2dp: Proxy object connected
10-14 10:15:39.256  5880  5880 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 10:15:39.256  3138  3138 D BluetoothA2dp: Proxy object connected
10-14 10:15:39.256  5682  5694 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 10:15:39.257  5682  5682 D BluetoothMap: Proxy object connected
10-14 10:15:39.257  5682  5682 D MapProfile: Bluetooth service connected
10-14 10:15:39.257  5880  5880 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-14 10:15:39.257  5682  5682 D BluetoothMap: getConnectedDevices()
,10-14 10:15:39.258  5880  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:15:39.260  5880  5880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:39.260  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:39.260  3138  3150 D BluetoothMap: onBluetoothStateChange: up=true
,10-14 10:15:39.262  3138  3152 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 10:15:39.262  3138  3138 D BluetoothMap: Proxy object connected
,10-14 10:15:39.262  5682  5682 D BluetoothA2dp: Proxy object connected
10-14 10:15:39.262  5880  5880 D ObexServerSockets: Succeed to create listening sockets 
10-14 10:15:39.262  3138  3138 D MapProfile: Bluetooth service connected
10-14 10:15:39.262  3138  3138 D BluetoothMap: getConnectedDevices()
10-14 10:15:39.262  5880  5880 D ObexServerSockets0: startAccept()
10-14 10:15:39.262  5880  5880 D ObexServerSockets0: prepareForNewConnect()
,10-14 10:15:39.264  5880  5880 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-14 10:15:39.265  5880  5880 D BluetoothSdpJni: SDP Create record success - handle: 0
10-14 10:15:39.265  5880  5918 D ObexServerSockets0: Accepting socket connection...
10-14 10:15:39.265  3138  3150 D BluetoothPbap: onBluetoothStateChange: up=true
,10-14 10:15:39.266  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:39.266  5880  5919 D ObexServerSockets0: Accepting socket connection...
,10-14 10:15:39.270   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:15:39.270  5682  5696 D BluetoothPan: onBluetoothStateChange on: true
,10-14 10:15:39.274  5682  5917 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:15:39.275  5682  5694 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 10:15:39.276  3138  3152 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-14 10:15:39.278   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 10:15:39.278  3138  3138 D BluetoothInputDevice: Proxy object connected
,10-14 10:15:39.278  3138  3138 D HidProfile: Bluetooth service connected
10-14 10:15:39.279  5682  5682 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 10:15:39.279  5682  5682 D PanProfile: Bluetooth service connected
10-14 10:15:39.279  5682  5682 D BluetoothInputDevice: Proxy object connected
10-14 10:15:39.279   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 10:15:39.279  5682  5682 D HidProfile: Bluetooth service connected
10-14 10:15:39.280  5880  5880 D BluetoothMapService: onReceive
10-14 10:15:39.280  5880  5880 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-14 10:15:39.280  5880  5880 D BluetoothMapService: STATE_ON
10-14 10:15:39.280  5629  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 10:15:39.283  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:39.284  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:39.284  5880  5921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 10:15:39.286  5880  5921 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-14 10:15:39.286  5880  5921 D BluetoothSdpJni: SDP Create record success - handle: 1
10-14 10:15:39.289  5682  5682 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 10:15:39.294  3556  3556 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 10:15:39.295  5682  5682 D DockEventReceiver: finishStartingService: stopping service
,10-14 10:15:39.301  3138  3138 D BluetoothPbap: Proxy object connected
,10-14 10:15:39.301  3138  3138 D PbapServerProfile: Bluetooth service connected
,10-14 10:15:39.305  5682  5682 D BluetoothPbap: Proxy object connected
,10-14 10:15:39.305  5682  5682 D PbapServerProfile: Bluetooth service connected
,10-14 10:15:39.306  5880  5880 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 10:15:39.306  5880  5880 D ObexServerSockets0: prepareForNewConnect()
,10-14 10:15:39.309  5880  5925 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:15:39.324  5880  5929 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 10:15:39.325  5880  5929 I BtOppRfcommListener: Accept thread started.
,10-14 10:15:39.354  3822  3841 D BluetoothHeadset: Proxy object connected
,10-14 10:15:39.355  3822  4912 D BluetoothHeadset: Proxy object connected
10-14 10:15:39.355  3138  3152 D BluetoothHeadset: Proxy object connected
10-14 10:15:39.355  3138  3138 D HeadsetProfile: Bluetooth service connected
,10-14 10:15:39.355   929   929 D BluetoothHeadset: Proxy object connected
10-14 10:15:39.355   929   929 D BluetoothHeadset: Proxy object connected
10-14 10:15:39.355   929   929 D BluetoothHeadset: Proxy object connected
,10-14 10:15:39.355  5682  5696 D BluetoothHeadset: Proxy object connected
,10-14 10:15:39.357  5682  5682 D HeadsetProfile: Bluetooth service connected
,10-14 10:15:39.364  3138  3150 D BluetoothHeadset: Proxy object connected
,10-14 10:15:39.365  3138  3138 D HeadsetProfile: Bluetooth service connected
,10-14 10:15:39.370   929   946 D BluetoothHeadset: Proxy object connected
,10-14 10:15:39.374  5682  5917 D BluetoothHeadset: Proxy object connected
,10-14 10:15:39.374  5682  5682 D HeadsetProfile: Bluetooth service connected
,10-14 10:15:39.379   929   946 D BluetoothHeadset: Proxy object connected
,10-14 10:15:42.650   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:43.209  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:15:43.215  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:15:43.216  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:15:43.216  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@342acb5 removed from the list
,10-14 10:15:43.218  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:43.218  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:43.218  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:43.220  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:43.220  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d00df4a added. We now have 4 listener(s)
10-14 10:15:43.220  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:43.222   929  3155 D WifiService: setWifiEnabled: false pid=5629, uid=10077
,10-14 10:15:43.222   929  3155 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:15:43.651   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:44.652   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:45.653   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:46.654   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:15:47.655   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-14 10:15:48.230  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:48.231   929  3154 D WifiService: setWifiEnabled: true pid=5629, uid=10077
10-14 10:15:48.231   929  3154 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 10:15:48.240   509   923 D SoftapController: Softap fwReload - Ok
,10-14 10:15:48.245   509   923 D CommandListener: Setting iface cfg
,10-14 10:15:48.246   509   923 D CommandListener: Trying to bring down wlan0
10-14 10:15:48.248   509   923 D CommandListener: Clearing all IP addresses on wlan0
,10-14 10:15:48.252   929  2971 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 10:15:48.912   929  2971 D wifi    : set interface wlan0 flags (UP)
,10-14 10:15:48.918   929  2971 I WifiHAL : Initializing wifi
10-14 10:15:48.918   929  2971 I WifiHAL : Creating socket
10-14 10:15:48.923   929  2971 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-14 10:15:48.923   929  2971 D wifi    : Did set static halHandle = 0x7f6cd67b80
,10-14 10:15:48.923   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-14 10:15:48.924   929  2971 D wifi    : halHandle = 0x7f6cd67b80, mVM = 0x7f893cd140, mCls = 0x201916
,10-14 10:15:48.924   929  2971 D wifi    : array field set
10-14 10:15:48.924   929  2971 I WifiNative-HAL: interface[0] = wlan0
10-14 10:15:48.927   929  5934 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547286842240
10-14 10:15:48.927   929  5934 D wifi    : waitForHalEvents called, vm = 0x7f893cd140, obj = 0x201916, env = 0x7f6a296640
,10-14 10:15:48.976  5935  5935 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 10:15:48.997  5935  5935 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:15:49.010  5935  5935 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 10:15:49.010  5935  5935 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 10:15:49.029   929  2971 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-14 10:15:49.038  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:49.039   929  2971 D WifiConfigStore: Loading config and enabling all networks 
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:49.046  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 10:15:49.048  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 10:15:49.053  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 10:15:49.054   929  2971 D WifiConfigStore: loaded 0 passpoint configs
10-14 10:15:49.054   929  2971 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-14 10:15:49.054   929  2971 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-14 10:15:49.055   929  2971 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-14 10:15:49.056  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 10:15:49.057   929  2971 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-14 10:15:49.057   929  2971 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-14 10:15:49.057   929  2971 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 10:15:49.057   929  2971 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-14 10:15:49.058  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:49.063   929  2971 D WifiNative-HAL: Setting external_sim to 1
,10-14 10:15:49.064  5017  5017 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 10:15:49.064   929  2971 D wifi    : setting dfs flag to true, 0x7f6eab1e40
10-14 10:15:49.064   929  2971 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 10:15:49.064   929  2971 D wifi    : setting scan oui 0x7f6eab1e40
,10-14 10:15:49.064   929  2971 D WifiHAL : Sending mac address OUI
,10-14 10:15:49.069   929  2971 E native  : do suspend false
,10-14 10:15:49.076   929  2971 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-14 10:15:49.077   929   929 D RttService: SCAN_AVAILABLE : 3
10-14 10:15:49.077   929  3080 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-14 10:15:49.081   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-14 10:15:49.083   509   923 D CommandListener: Setting iface cfg
,10-14 10:15:49.085   929  2970 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-14 10:15:49.085   929  2970 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 10:15:49.091   929  2970 D WifiNative-HAL: p2pGetDeviceAddress
,10-14 10:15:49.096   929  2970 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 10:15:49.096   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=305996 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,10-14 10:15:52.255  5935  5935 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:52.259  5935  5935 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:52.263  5935  5935 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:52.268  5935  5935 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 10:15:52.343   929  2971 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-14 10:15:52.344   929  2971 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-14 10:15:52.344   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:15:52.358   929  2971 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-14 10:15:52.390   929  2971 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-14 10:15:52.392  5935  5935 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-14 10:15:52.820  5935  5935 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 10:15:52.855  5935  5935 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 10:15:52.856  5935  5935 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-14 10:15:52.866   929  2971 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 10:15:52.867   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-14 10:15:52.867   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:15:52.881   929  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 10:15:52.891   509   923 D CommandListener: Setting iface cfg
,10-14 10:15:52.895   929  2971 D WifiStateMachine: Start Dhcp Watchdog 3
,10-14 10:15:52.899   929  5940 D DhcpClient: Receive thread started
,10-14 10:15:52.903   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 10:15:52.903   929  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-14 10:15:52.903   929  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-14 10:15:52.983   929  2971 E native  : do suspend false
,10-14 10:15:52.994   929  5939 D DhcpClient: Broadcasting DHCPDISCOVER
,10-14 10:15:53.005   929  5940 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-14 10:15:53.006   929  5939 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-14 10:15:53.008   929  5939 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-14 10:15:53.020   929  5940 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-14 10:15:53.021   929  5939 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-14 10:15:53.025   509   923 D CommandListener: Setting iface cfg
,10-14 10:15:53.030   929  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-14 10:15:53.034   929  5939 D DhcpClient: Scheduling renewal in 86399s
,10-14 10:15:53.042   929  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-14 10:15:53.043   929  2971 D WifiConfigStore: No blacklist allowed without epno enabled
10-14 10:15:53.044   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-14 10:15:53.046   929  2971 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-14 10:15:53.047   929  2973 D ConnectivityService: Adding iface wlan0 to network 102
,10-14 10:15:53.092   929  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-14 10:15:53.092   929  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-14 10:15:53.094   929  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-14 10:15:53.095   929  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-14 10:15:53.097   929  2973 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-14 10:15:53.103   929  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 10:15:53.107   929  2973 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-14 10:15:53.108   929  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-14 10:15:53.108   929  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-14 10:15:53.108   929  2971 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-14 10:15:53.108   929  2973 D ConnectivityService:    accepting network in place of null
10-14 10:15:53.108   929  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 10:15:53.108   929  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 10:15:53.115   929  5938 D NetlinkSocketObserver: NeighborEvent{elapsedMs=310015, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-14 10:15:53.131   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:15:53.151   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 10:15:53.154   929  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-14 10:15:53.154   929  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-14 10:15:53.154  3779  3915 W QCNEJ   : |CORE| network available: 102
10-14 10:15:53.155   929  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-14 10:15:53.156  3779  3915 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-14 10:15:53.157  3779  3915 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-14 10:15:53.157  3779  3915 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-14 10:15:53.157   929   946 D Tethering: MasterInitialState.processMessage what=3
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.165  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:15:53.168  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.169  3928  3928 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.172  5629  5629 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 10:15:53.172  3751  3751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-14 10:15:53.173  5629  5629 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.176  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 10:15:53.176  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,10-14 10:15:53.188  3751  3751 D SystemUpdateService: onCreate
,10-14 10:15:53.193  3751  3751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-14 10:15:53.194   929  5937 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.100,2a00:1450:400c:c0c::65
,10-14 10:15:53.177  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-14 10:15:53.196  5046  5070 E SarControlService: no key has been found,reset the power
10-14 10:15:53.196  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-14 10:15:53.201  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,10-14 10:15:53.201  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 10:15:53.202  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:53.202  5071  5071 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-14 10:15:53.205  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-14 10:15:53.205  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 10:15:53.205  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 10:15:53.206  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 10:15:53.206  5071  5071 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 10:15:53.208  3751  3751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
10-14 10:15:53.209  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000f003000000000000ffffffff]
10-14 10:15:53.209  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:53.209  5071  5085 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-14 10:15:53.210  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,10-14 10:15:53.210  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-14 10:15:53.210  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@38ea137 HexData = [00000000f103000000000000ffffffff]
10-14 10:15:53.210  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 10:15:53.210  5071  5085 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-14 10:15:53.211  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 10:15:53.211  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-14 10:15:53.212  3751  5413 I iu.UploadsManager: num queued entries: 0
10-14 10:15:53.212  3751  5413 I iu.UploadsManager: num updated entries: 0
,10-14 10:15:53.221  3751  3751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-14 10:15:53.223  3751  3751 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 10:15:53.225  5749  5749 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-14 10:15:53.227  5749  5749 D SprintDMHelper: simOperator: 
10-14 10:15:53.228  5749  5749 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 10:15:53.235  3751  5951 I SystemUpdateService: active receiver: enabled
,10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.245  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:53.247  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:53.247  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.247  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d00df4a removed from the list
10-14 10:15:53.247  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:53.247  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.247  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.249  3751  5413 I iu.SyncManager: NEXT; no task
10-14 10:15:53.250  5629  5675 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-14 10:15:53.251  5629  5675 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-14 10:15:53.252  5629  5675 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c28f04b Bundle[{}]
10-14 10:15:53.253  5629  5675 I io.jxcore.node.LifeCycleMonitor: start: OK
10-14 10:15:53.253  5629  5675 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-14 10:15:53.253  5629  5675 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-14 10:15:53.254  5629  5675 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-14 10:15:53.254  5629  5675 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-14 10:15:53.255  5629  5675 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-14 10:15:53.259  3751  5951 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 10:15:53.262  5629  5675 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,10-14 10:15:53.263  5629  5675 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-14 10:15:53.263  5629  5675 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,10-14 10:15:53.265  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 10:15:53.265  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa3cebb added. We now have 3 listener(s)
,10-14 10:15:53.266  3751  5951 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-14 10:15:53.266  3751  5951 I SystemUpdateService: now status is 0 (complete)
10-14 10:15:53.266  3751  5951 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 10:15:53.266  3751  5951 I SystemUpdateService: file has been verified
10-14 10:15:53.266  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.266  3751  5951 I SystemUpdateService: OTA package size = 21989297
10-14 10:15:53.266  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.266  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.267  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.267  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e2fd8 added. We now have 4 listener(s)
,10-14 10:15:53.267  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.267  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:15:53.270  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:15:53.271  3751  5951 I SystemUpdateService: showing system update notification
,10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.273  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:53.276  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:53.276  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:15:53.276  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 10:15:53.276  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f5a616 added. We now have 4 listener(s)
10-14 10:15:53.277  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.277  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.277  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.277  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.278  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1369b97 added. We now have 5 listener(s)
10-14 10:15:53.278  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.278  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:53.278  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:53.278  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:53.278  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 10:15:53.278  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.278  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.278  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.278  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.278   929  5937 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 14 Oct 2016 14:15:53 GMT], X-Android-Received-Millis=[1476454553277], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476454553235]}
10-14 10:15:53.278  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.278  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa3cebb removed from the list
10-14 10:15:53.278  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.278  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e2fd8 removed from the list
,10-14 10:15:53.278   929  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-14 10:15:53.279   929  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-14 10:15:53.279   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-14 10:15:53.280   929  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-14 10:15:53.282  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.282  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:53.282  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:53.283  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:15:53.283  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.284  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.284  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.284  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.284  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e2fd8 not in the list
10-14 10:15:53.284  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.284  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.285  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.285  3751  3751 D SystemUpdateService: onDestroy
10-14 10:15:53.285  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.285  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 10:15:53.285  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1369b97 removed from the list
10-14 10:15:53.285  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.285  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.285  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.285  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.286  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-14 10:15:53.286  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f5a616 removed from the list
10-14 10:15:53.286  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.286  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5727184 added. We now have 3 listener(s)
10-14 10:15:53.287  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.288  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.288  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.288  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.288  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68bd6d added. We now have 4 listener(s)
10-14 10:15:53.288  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.288  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:15:53.291  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.295  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:53.300  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.300  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 10:15:53.300  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.300  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bf5a33 added. We now have 4 listener(s)
10-14 10:15:53.302  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.302  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.302  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.302  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.302  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6721f0 added. We now have 5 listener(s)
10-14 10:15:53.302  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.302  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:15:53.302  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 10:15:53.302  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 10:15:53.302  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:15:53.302  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:15:53.303  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:53.305  5629  5675 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:15:53.305  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 10:15:53.306  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 10:15:53.308  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:15:53.309  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:15:53.309  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:15:53.312  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-14 10:15:53.312  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 10:15:53.312  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 10:15:53.312  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:15:53.312  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:15:53.313  5629  5675 D BluetoothAdapter: STATE_ON
,10-14 10:15:53.316  5880  5920 D BtGatt.GattService: registerClient() - UUID=6c1a0ae7-6715-4e92-bc5d-9ceaeec26410
,10-14 10:15:53.317  5880  5896 D BtGatt.GattService: onClientRegistered() - UUID=6c1a0ae7-6715-4e92-bc5d-9ceaeec26410, clientIf=5
10-14 10:15:53.318  5629  5639 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 10:15:53.318  5880  5907 D BtGatt.GattService: start scan with filters
,10-14 10:15:53.322  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-14 10:15:53.322  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 10:15:53.323  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:15:53.323  5880  5899 D BtGatt.ScanManager: handling starting scan
10-14 10:15:53.323  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 10:15:53.323  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:15:53.323  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 10:15:53.323  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 10:15:53.324  5880  5899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c1163c
10-14 10:15:53.326  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:15:53.326  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:15:53.326  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 10:15:53.328  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 10:15:53.330  5629  5675 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-14 10:15:53.330  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:53.331  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-14 10:15:53.331  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.331  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 10:15:53.331  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.331  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 10:15:53.331  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:15:53.331  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:15:53.331  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:15:53.331  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:15:53.331  5880  5896 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 10:15:53.331  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 10:15:53.331  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:15:53.331  5880  5899 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 10:15:53.331  5629  5675 D BluetoothAdapter: STATE_ON
10-14 10:15:53.332  5880  5907 D BtGatt.GattService: stopScan() - queue size =1
10-14 10:15:53.332  5880  5891 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:15:53.333  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:15:53.333  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 10:15:53.333  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 10:15:53.333  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:15:53.333  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-14 10:15:53.333  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 10:15:53.333  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 10:15:53.333  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 10:15:53.334  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:15:53.334  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:15:53.334  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 10:15:53.334  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:15:53.334  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:15:53.334  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.335  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:15:53.335  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:15:53.335  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 10:15:53.336  5880  5896 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 10:15:53.336  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.336  5880  5899 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:15:53.336  5880  5899 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 10:15:53.337  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:53.337  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:53.337  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:53.337  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.337  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.337  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.337  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.337  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-14 10:15:53.338  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5727184 removed from the list
10-14 10:15:53.338  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.338  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68bd6d removed from the list
10-14 10:15:53.338  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:53.338  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.338  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.338  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.339  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.339  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.339  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.339  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68bd6d not in the list
10-14 10:15:53.339  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:15:53.339  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.340  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.340  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.340  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.341  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6721f0 removed from the list
10-14 10:15:53.341  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.341  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.341  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.341  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.341  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.341  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9bf5a33 removed from the list
10-14 10:15:53.341  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.342  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb46d1c added. We now have 3 listener(s)
10-14 10:15:53.343  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.343  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.343  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.343  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.343  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b92d25 added. We now have 4 listener(s)
10-14 10:15:53.343  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.344  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:15:53.345  5880  5896 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 10:15:53.345  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.345  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:15:53.349  5880  5896 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 10:15:53.349  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.350  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:53.352  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.352  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 10:15:53.352  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.352  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@961dcab added. We now have 4 listener(s)
10-14 10:15:53.354  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.354  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.354  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-14 10:15:53.354  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 10:15:53.354  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7293f08 added. We now have 5 listener(s)
10-14 10:15:53.354  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.354  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:15:53.354  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.355  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:15:53.355  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 10:15:53.355  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 10:15:53.355  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:15:53.355  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 10:15:53.355  5880  5896 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 10:15:53.355  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.355  5880  5899 D BtGatt.ScanManager: stopping BLe Batch
10-14 10:15:53.357  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.358  5629  5675 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 10:15:53.358  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-14 10:15:53.360  5880  5896 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 10:15:53.360  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:15:53.360  5880  5899 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 10:15:53.362  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:15:53.363  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 10:15:53.363  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-14 10:15:53.365  5880  5896 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-14 10:15:53.365  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:15:53.367  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-14 10:15:53.367  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 10:15:53.368  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 10:15:53.368  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:15:53.368  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:15:53.368  5629  5675 D BluetoothAdapter: STATE_ON
,10-14 10:15:53.370  5880  5907 D BtGatt.GattService: registerClient() - UUID=8a9c532f-aa61-4d2f-b119-9d96f3d15db1
10-14 10:15:53.370  5880  5896 D BtGatt.GattService: onClientRegistered() - UUID=8a9c532f-aa61-4d2f-b119-9d96f3d15db1, clientIf=5
,10-14 10:15:53.371  5629  5639 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 10:15:53.371  5880  5908 D BtGatt.GattService: start scan with filters
10-14 10:15:53.373  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 10:15:53.373  5880  5899 D BtGatt.ScanManager: handling starting scan
10-14 10:15:53.373  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 10:15:53.373  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:15:53.373  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 10:15:53.373  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:15:53.373  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 10:15:53.373  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 10:15:53.375  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 10:15:53.375  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:15:53.375  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:15:53.376  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 10:15:53.378  5880  5896 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 10:15:53.378  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.378  5880  5899 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 10:15:53.378  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-14 10:15:53.378  5629  5675 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-14 10:15:53.379  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:53.379  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:15:53.379  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:53.379  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.379  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.379  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 10:15:53.379  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.379  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.379  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb46d1c removed from the list
10-14 10:15:53.379  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.379  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b92d25 removed from the list
,10-14 10:15:53.379  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:53.379  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.380  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.380  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-14 10:15:53.380  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.380  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.381  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.381  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.381  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.381  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b92d25 not in the list
10-14 10:15:53.381  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:15:53.381  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:15:53.381  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:15:53.381  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 10:15:53.381  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 10:15:53.381  5629  5675 D BluetoothAdapter: STATE_ON
10-14 10:15:53.382  5880  5908 D BtGatt.GattService: stopScan() - queue size =1
10-14 10:15:53.382  5880  5896 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 10:15:53.382  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.382  5880  5899 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:15:53.382  5880  5899 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 10:15:53.382  5880  5920 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:15:53.382  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:15:53.382  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 10:15:53.383  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 10:15:53.383  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:15:53.383  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-14 10:15:53.383  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 10:15:53.383  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 10:15:53.383  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 10:15:53.383  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:15:53.384  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:15:53.384  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 10:15:53.384  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:15:53.384  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:15:53.384  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.385  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.385  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.385  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.385  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:15:53.385  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7293f08 removed from the list
10-14 10:15:53.385  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.385  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:15:53.385  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.386  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:53.386  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:15:53.386  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.386  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.386  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@961dcab removed from the list
10-14 10:15:53.386  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.387  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9743b4 added. We now have 3 listener(s)
10-14 10:15:53.388  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.388  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.388  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.388  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.388  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@840dbdd added. We now have 4 listener(s)
10-14 10:15:53.388  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.389  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:15:53.390  5880  5896 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 10:15:53.390  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.391  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 10:15:53.394  5880  5896 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-14 10:15:53.395  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.396  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:53.399  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 10:15:53.399  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 10:15:53.399  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.399  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6933623 added. We now have 4 listener(s)
,10-14 10:15:53.401  5880  5896 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 10:15:53.401  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.401  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.401  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.401  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.401  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-14 10:15:53.401  5880  5899 D BtGatt.ScanManager: stopping BLe Batch
,10-14 10:15:53.401  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.401  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93ee720 added. We now have 5 listener(s)
10-14 10:15:53.401  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.402  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:15:53.402  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 10:15:53.402  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 10:15:53.402  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:15:53.402  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-14 10:15:53.406  5629  5675 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-14 10:15:53.406  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 10:15:53.406  5880  5896 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 10:15:53.406  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.406  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.407  5880  5899 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 10:15:53.409  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 10:15:53.409  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-14 10:15:53.410  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 10:15:53.411  5880  5896 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 10:15:53.411  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:15:53.413  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-14 10:15:53.413  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 10:15:53.413  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 10:15:53.413  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 10:15:53.413  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 10:15:53.413  5629  5675 D BluetoothAdapter: STATE_ON
,10-14 10:15:53.415  5880  5890 D BtGatt.GattService: registerClient() - UUID=391c4f1c-ee61-4ee5-9738-2af1b0813377
,10-14 10:15:53.415  5880  5896 D BtGatt.GattService: onClientRegistered() - UUID=391c4f1c-ee61-4ee5-9738-2af1b0813377, clientIf=5
10-14 10:15:53.415  5629  5639 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-14 10:15:53.416  5880  5908 D BtGatt.GattService: start scan with filters
,10-14 10:15:53.417  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-14 10:15:53.417  5880  5899 D BtGatt.ScanManager: handling starting scan
10-14 10:15:53.418  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 10:15:53.418  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:15:53.418  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 10:15:53.418  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 10:15:53.418  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 10:15:53.418  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 10:15:53.419  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 10:15:53.419  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 10:15:53.420  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 10:15:53.421  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 10:15:53.422  5880  5896 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 10:15:53.422  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.422  5880  5899 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 10:15:53.424  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 10:15:53.425  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:53.425  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:53.425  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.425  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.425  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,10-14 10:15:53.425  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.425  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.425  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9743b4 removed from the list
10-14 10:15:53.425  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.425  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@840dbdd removed from the list
10-14 10:15:53.425  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:53.425  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.425  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:15:53.425  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-14 10:15:53.426  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.426  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.426  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.426  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.427  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.427  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@840dbdd not in the list
10-14 10:15:53.427  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 10:15:53.427  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 10:15:53.427  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 10:15:53.427  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,10-14 10:15:53.427  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 10:15:53.427  5880  5896 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 10:15:53.427  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.427  5880  5899 D BtGatt.ScanManager: Starting BLE batch scan
10-14 10:15:53.427  5880  5899 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 10:15:53.427  5629  5675 D BluetoothAdapter: STATE_ON
10-14 10:15:53.428  5880  5908 D BtGatt.GattService: stopScan() - queue size =1
10-14 10:15:53.429  5880  5891 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 10:15:53.429  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 10:15:53.429  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-14 10:15:53.429  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 10:15:53.429  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 10:15:53.429  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 10:15:53.429  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 10:15:53.429  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 10:15:53.429  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 10:15:53.431  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:15:53.431  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 10:15:53.431  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 10:15:53.431  5629  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 10:15:53.431  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 10:15:53.432  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:53.436  5880  5896 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-14 10:15:53.436  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.436  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.436  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.436  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.437  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93ee720 removed from the list
10-14 10:15:53.437  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 10:15:53.437  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.437  5629  5629 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 10:15:53.437  5629  5629 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 10:15:53.437  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.437  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.437  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.437  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.437  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6933623 removed from the list
10-14 10:15:53.438  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.438  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb554c added. We now have 3 listener(s)
,10-14 10:15:53.439  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 10:15:53.440  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.440  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.440  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.440  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc8a995 added. We now have 4 listener(s)
10-14 10:15:53.440  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.441  5880  5896 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 10:15:53.441  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 10:15:53.442  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 10:15:53.446  5880  5896 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-14 10:15:53.446  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.446  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 10:15:53.447  5880  5899 D BtGatt.ScanManager: stopping BLe Batch
,10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 10:15:53.451  5629  5675 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 10:15:53.451  5880  5896 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 10:15:53.451  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.452  5880  5899 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 10:15:53.452  5629  5675 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 10:15:53.453  5629  5675 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 10:15:53.453  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 10:15:53.453  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b77469b added. We now have 4 listener(s)
10-14 10:15:53.454  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 10:15:53.454  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 10:15:53.454  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 10:15:53.454  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 10:15:53.454  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7a38 added. We now have 5 listener(s)
10-14 10:15:53.454  5629  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 10:15:53.454  5629  5675 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 10:15:53.455  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:15:53.455  5629  5675 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 10:15:53.455  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.455  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.455  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.455  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 10:15:53.455  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.455  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.455  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fb554c removed from the list
10-14 10:15:53.455  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.455  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc8a995 removed from the list
10-14 10:15:53.456  5880  5896 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 10:15:53.456  5880  5896 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 10:15:53.457  5629  5629 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 10:15:53.457  5629  5675 D io.jxcore.node.ConnectivityMonitor: stop
10-14 10:15:53.457  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 10:15:53.457  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 10:15:53.457  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.458  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.458  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.458  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.458  5629  5675 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc8a995 not in the list
10-14 10:15:53.458  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.458  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.459  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 10:15:53.459  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 10:15:53.459  5629  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 10:15:53.459  5629  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7a38 removed from the list
,10-14 10:15:53.459  5629  5675 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 10:15:53.459  5629  5675 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 10:15:53.459  5629  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 10:15:53.459  5629  5675 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 10:15:53.459  5629  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 10:15:53.459  5629  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b77469b removed from the list
10-14 10:15:53.460  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-14 10:15:53.460  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-14 10:15:53.460  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-14 10:15:53.460  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:15:53.460  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-14 10:15:53.460  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-14 10:15:53.464  5017  5955 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-14 10:15:53.836  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:15:53.887  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:15:53.938  5629  5629 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 10:15:55.614  5629  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 10:15:55.614  5629  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:15:55.919   929  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 10:15:56.401  5629  5963 W !!      : call onHalfStreamCopied
,10-14 10:15:56.401  5629  5963 I testCopyDataAndClose: closing input stream
,10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 10:15:57.178  5629  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 10:16:00.957  5629  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:00.957  5629  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:16:01.112   929  2973 D ConnectivityService: handlePromptUnvalidated 102
,10-14 10:16:02.957  5629  5675 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
10-14 10:16:02.957  5629  5675 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:16:02.957  5629  5675 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,10-14 10:16:03.089  5629  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-14 10:16:03.089  5629  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:03.089  5629  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,10-14 10:16:03.112  5629  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 10:16:03.112  5629  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:16:04.099   929  2971 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-14 10:16:04.813  5629  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 10:16:04.813  5629  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:16:04.813  5629  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 10:16:04.813  5629  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:16:04.813  5629  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-14 10:16:04.813  5629  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 10:16:04.814  5629  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 10:16:04.814  5629  5965 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-14 10:16:04.814  5629  5965 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 10:16:04.814  5629  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 10:16:04.814  5629  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 10:16:08.542  5629  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:08.542  5629  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:16:08.542  5629  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:08.542  5629  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:16:08.543  5629  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 10:16:08.543  5629  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 10:16:08.543  5629  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-14 10:16:08.543  5629  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 10:16:08.543  5629  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-14 10:16:08.543  5629  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 10:16:08.543  5629  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 10:16:08.544  5629  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:08.544  5629  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-14 10:16:08.545  5629  5675 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-14 10:16:08.548  5629  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:08.548  5629  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 10:16:08.549  5629  5967 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
10-14 10:16:08.549  5629  5967 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:08.549  5629  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-14 10:16:08.549  5629  5967 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-14 10:16:08.549  5629  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
10-14 10:16:08.549  5629  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-14 10:16:08.555  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-14 10:16:08.555  5629  5675 I jxcore-log: 
10-14 10:16:08.555  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-14 10:16:08.555  5629  5675 I jxcore-log: 
10-14 10:16:08.555  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-14 10:16:08.555  5629  5675 I jxcore-log: 
10-14 10:16:08.555  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-14 10:16:08.555  5629  5675 I jxcore-log: 
,10-14 10:16:08.556  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'Total duration:  90876'
10-14 10:16:08.556  5629  5675 I jxcore-log: 
10-14 10:16:08.558  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-14 10:16:08.558  5629  5675 I jxcore-log: 
,10-14 10:16:08.562  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.562  5629  5675 I jxcore-log: 
10-14 10:16:08.562  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.562  5629  5675 I jxcore-log: 
10-14 10:16:08.563  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.563  5629  5675 I jxcore-log: 
10-14 10:16:08.563  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.563  5629  5675 I jxcore-log: 
,10-14 10:16:08.563  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-14 10:16:08.563  5629  5675 I jxcore-log: 
10-14 10:16:08.564  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:16:08.564  5629  5675 I jxcore-log: 
10-14 10:16:08.564  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.564  5629  5675 I jxcore-log: 
,10-14 10:16:08.564  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.564  5629  5675 I jxcore-log: 
10-14 10:16:08.565  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-14 10:16:08.565  5629  5675 I jxcore-log: 
10-14 10:16:08.565  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:16:08.565  5629  5675 I jxcore-log: 
10-14 10:16:08.565  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:16:08.565  5629  5675 I jxcore-log: 
10-14 10:16:08.565  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.565  5629  5675 I jxcore-log: 
10-14 10:16:08.566  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.566  5629  5675 I jxcore-log: 
10-14 10:16:08.566  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.566  5629  5675 I jxcore-log: 
10-14 10:16:08.566  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.566  5629  5675 I jxcore-log: 
10-14 10:16:08.566  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.566  5629  5675 I jxcore-log: 
10-14 10:16:08.567  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.567  5629  5675 I jxcore-log: 
10-14 10:16:08.567  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.567  5629  5675 I jxcore-log: 
10-14 10:16:08.567  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.567  5629  5675 I jxcore-log: 
10-14 10:16:08.567  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.567  5629  5675 I jxcore-log: 
10-14 10:16:08.568  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.568  5629  5675 I jxcore-log: 
,10-14 10:16:08.568  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.568  5629  5675 I jxcore-log: 
10-14 10:16:08.568  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.568  5629  5675 I jxcore-log: 
10-14 10:16:08.570  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.570  5629  5675 I jxcore-log: 
10-14 10:16:08.570  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.570  5629  5675 I jxcore-log: 
,10-14 10:16:08.570  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.570  5629  5675 I jxcore-log: 
10-14 10:16:08.571  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.571  5629  5675 I jxcore-log: 
10-14 10:16:08.571  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.571  5629  5675 I jxcore-log: 
10-14 10:16:08.571  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.571  5629  5675 I jxcore-log: 
10-14 10:16:08.571  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.571  5629  5675 I jxcore-log: 
10-14 10:16:08.571  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.571  5629  5675 I jxcore-log: 
,10-14 10:16:08.572  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.572  5629  5675 I jxcore-log: 
10-14 10:16:08.572  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.572  5629  5675 I jxcore-log: 
10-14 10:16:08.572  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.572  5629  5675 I jxcore-log: 
10-14 10:16:08.572  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.572  5629  5675 I jxcore-log: 
10-14 10:16:08.573  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.573  5629  5675 I jxcore-log: 
,10-14 10:16:08.573  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.573  5629  5675 I jxcore-log: 
10-14 10:16:08.573  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.573  5629  5675 I jxcore-log: 
10-14 10:16:08.573  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.573  5629  5675 I jxcore-log: 
10-14 10:16:08.574  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.574  5629  5675 I jxcore-log: 
,10-14 10:16:08.574  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 10:16:08.574  5629  5675 I jxcore-log: 
10-14 10:16:08.574  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.574  5629  5675 I jxcore-log: 
10-14 10:16:08.574  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 10:16:08.574  5629  5675 I jxcore-log: 
,10-14 10:16:08.574  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.574  5629  5675 I jxcore-log: 
10-14 10:16:08.575  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.575  5629  5675 I jxcore-log: 
,10-14 10:16:08.575  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.575  5629  5675 I jxcore-log: 
10-14 10:16:08.575  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.575  5629  5675 I jxcore-log: 
10-14 10:16:08.575  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.575  5629  5675 I jxcore-log: 
,10-14 10:16:08.576  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 10:16:08.576  5629  5675 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-14 10:16:08.576  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.576  5629  5675 I jxcore-log: 
,10-14 10:16:08.576  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.576  5629  5675 I jxcore-log: 
10-14 10:16:08.576  5629  5675 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 10:16:08.576  5629  5675 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-14 10:16:08.576  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 10:16:08.576  5629  5675 I jxcore-log: 
,10-14 10:16:08.577  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:16:08.577  5629  5675 I jxcore-log: 
10-14 10:16:08.577  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:16:08.577  5629  5675 I jxcore-log: 
10-14 10:16:08.577  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 10:16:08.577  5629  5675 I jxcore-log: 
10-14 10:16:08.582  5629  5629 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-14 10:16:08.582  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-14 10:16:08.582  5629  5675 I jxcore-log: 
10-14 10:16:08.583  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - WARN testUtils: 'myNameCallback not set!'
10-14 10:16:08.583  5629  5675 I jxcore-log: 
10-14 10:16:08.583  5629  5675 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-14 10:16:08.584  5629  5675 I jxcore-log: 2016-10-14 14:16:08 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-14 10:16:08.584  5629  5675 I jxcore-log: 
,10-14 10:16:10.591  5629  5675 I jxcore-log: 2016-10-14 14:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-14 10:16:10.591  5629  5675 I jxcore-log: 
,10-14 10:16:10.917  5629  5675 I jxcore-log: 2016-10-14 14:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-14 10:16:10.917  5629  5675 I jxcore-log: 
,10-14 10:16:10.929  5629  5675 I jxcore-log: 2016-10-14 14:16:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-14 10:16:10.929  5629  5675 I jxcore-log: 
,10-14 10:16:12.010  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-14 10:16:12.010  5629  5675 I jxcore-log: 
,10-14 10:16:12.172  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-14 10:16:12.172  5629  5675 I jxcore-log: 
,10-14 10:16:12.177  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-14 10:16:12.177  5629  5675 I jxcore-log: 
,10-14 10:16:12.182  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-14 10:16:12.182  5629  5675 I jxcore-log: 
,10-14 10:16:12.651  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-14 10:16:12.651  5629  5675 I jxcore-log: 
,10-14 10:16:12.656   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-14 10:16:12.656   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-14 10:16:12.693  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-14 10:16:12.693  5629  5675 I jxcore-log: 
,10-14 10:16:12.705  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-14 10:16:12.705  5629  5675 I jxcore-log: 
,10-14 10:16:12.710  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-14 10:16:12.710  5629  5675 I jxcore-log: 
,10-14 10:16:12.983  5629  5675 I jxcore-log: 2016-10-14 14:16:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-14 10:16:12.983  5629  5675 I jxcore-log: 
,10-14 10:16:13.105  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-14 10:16:13.105  5629  5675 I jxcore-log: 
,10-14 10:16:13.482  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-14 10:16:13.482  5629  5675 I jxcore-log: 
,10-14 10:16:13.490  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-14 10:16:13.490  5629  5675 I jxcore-log: 
,10-14 10:16:13.493  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-14 10:16:13.493  5629  5675 I jxcore-log: 
,10-14 10:16:13.498  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-14 10:16:13.498  5629  5675 I jxcore-log: 
,10-14 10:16:13.503  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-14 10:16:13.503  5629  5675 I jxcore-log: 
,10-14 10:16:13.528  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-14 10:16:13.528  5629  5675 I jxcore-log: 
,10-14 10:16:13.562  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-14 10:16:13.562  5629  5675 I jxcore-log: 
,10-14 10:16:13.569  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-14 10:16:13.569  5629  5675 I jxcore-log: 
,10-14 10:16:13.576  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-14 10:16:13.576  5629  5675 I jxcore-log: 
,10-14 10:16:13.591  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-14 10:16:13.591  5629  5675 I jxcore-log: 
,10-14 10:16:13.595  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-14 10:16:13.595  5629  5675 I jxcore-log: 
,10-14 10:16:13.601  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-14 10:16:13.601  5629  5675 I jxcore-log: 
,10-14 10:16:13.606  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-14 10:16:13.606  5629  5675 I jxcore-log: 
,10-14 10:16:13.618  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-14 10:16:13.618  5629  5675 I jxcore-log: 
,10-14 10:16:13.640  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-14 10:16:13.640  5629  5675 I jxcore-log: 
,10-14 10:16:13.651  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-14 10:16:13.651  5629  5675 I jxcore-log: 
,10-14 10:16:13.663  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-14 10:16:13.663  5629  5675 I jxcore-log: 
,10-14 10:16:13.673  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-14 10:16:13.673  5629  5675 I jxcore-log: 
,10-14 10:16:13.685  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-14 10:16:13.685  5629  5675 I jxcore-log: 
,10-14 10:16:13.695  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-14 10:16:13.695  5629  5675 I jxcore-log: 
,10-14 10:16:13.700  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-14 10:16:13.700  5629  5675 I jxcore-log: 
,10-14 10:16:13.721  5629  5675 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-14 10:16:13.722  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - INFO testUtils: 'BLE multiple advertisement supported'
10-14 10:16:13.722  5629  5675 I jxcore-log: 
,10-14 10:16:13.931  5629  5675 I jxcore-log: 2016-10-14 14:16:13 - DEBUG CoordinatedClient: 'connected to the test server'
10-14 10:16:13.931  5629  5675 I jxcore-log: 
,10-14 10:16:14.546  5629  5675 I jxcore-log: TAP version 13
10-14 10:16:14.546  5629  5675 I jxcore-log: 
,10-14 10:16:14.588  5629  5675 I jxcore-log: # setup
10-14 10:16:14.588  5629  5675 I jxcore-log: 
,10-14 10:16:15.065  5629  5675 I jxcore-log: # calling createNativeListener directly rejects
10-14 10:16:15.065  5629  5675 I jxcore-log: 
,10-14 10:16:15.201  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:15.201  5629  5675 I jxcore-log: 
,10-14 10:16:15.209  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'listening 43687'
10-14 10:16:15.209  5629  5675 I jxcore-log: 
,10-14 10:16:15.218  5629  5675 I jxcore-log: ok 1 Should throw
10-14 10:16:15.218  5629  5675 I jxcore-log: 
,10-14 10:16:15.231  5629  5675 I jxcore-log: # teardown
10-14 10:16:15.231  5629  5675 I jxcore-log: 
,10-14 10:16:15.378  5629  5675 I jxcore-log: # setup
10-14 10:16:15.378  5629  5675 I jxcore-log: 
,10-14 10:16:15.533  5629  5675 I jxcore-log: # emits incomingConnectionState
10-14 10:16:15.533  5629  5675 I jxcore-log: 
,10-14 10:16:15.696  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:15.696  5629  5675 I jxcore-log: 
,10-14 10:16:15.702  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'listening 38590'
10-14 10:16:15.702  5629  5675 I jxcore-log: 
,10-14 10:16:15.712  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:15.712  5629  5675 I jxcore-log: 
,10-14 10:16:15.715  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:15.715  5629  5675 I jxcore-log: 
,10-14 10:16:15.726  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'new mux'
10-14 10:16:15.726  5629  5675 I jxcore-log: 
,10-14 10:16:15.732  5629  5675 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-14 10:16:15.732  5629  5675 I jxcore-log: 
,10-14 10:16:15.748  5629  5675 I jxcore-log: 2016-10-14 14:16:15 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:15.748  5629  5675 I jxcore-log: 
,10-14 10:16:15.749  5629  5675 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-14 10:16:15.749  5629  5675 I jxcore-log: 
,10-14 10:16:15.755  5629  5675 I jxcore-log: # teardown
10-14 10:16:15.755  5629  5675 I jxcore-log: 
,10-14 10:16:15.829  5629  5675 I jxcore-log: # setup
10-14 10:16:15.829  5629  5675 I jxcore-log: 
,10-14 10:16:15.993  5629  5675 I jxcore-log: # emits routerPortConnectionFailed
10-14 10:16:15.993  5629  5675 I jxcore-log: 
,10-14 10:16:16.067  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:16.067  5629  5675 I jxcore-log: 
,10-14 10:16:16.072  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'listening 38410'
10-14 10:16:16.072  5629  5675 I jxcore-log: 
,10-14 10:16:16.078  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:16.078  5629  5675 I jxcore-log: 
,10-14 10:16:16.080  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:16.080  5629  5675 I jxcore-log: 
,10-14 10:16:16.081  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new mux'
10-14 10:16:16.081  5629  5675 I jxcore-log: 
,10-14 10:16:16.107  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:16.107  5629  5675 I jxcore-log: 
,10-14 10:16:16.110  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:16.110  5629  5675 I jxcore-log: 
,10-14 10:16:16.114  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: ' $c@net.js:837:7
10-14 10:16:16.114  5629  5675 I jxcore-log: $09@net.js:829:13
10-14 10:16:16.114  5629  5675 I jxcore-log: '
10-14 10:16:16.114  5629  5675 I jxcore-log: 
,10-14 10:16:16.115  5629  5675 I jxcore-log: ok 4 tried to connect to right port
10-14 10:16:16.115  5629  5675 I jxcore-log: 
10-14 10:16:16.116  5629  5675 I jxcore-log: ok 5 failed due to refused connection
10-14 10:16:16.116  5629  5675 I jxcore-log: 
10-14 10:16:16.116  5629  5675 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-14 10:16:16.116  5629  5675 I jxcore-log: 
,10-14 10:16:16.120  5629  5675 I jxcore-log: # teardown
10-14 10:16:16.120  5629  5675 I jxcore-log: 
10-14 10:16:16.122  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:16.122  5629  5675 I jxcore-log: 
,10-14 10:16:16.241  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'mux close'
10-14 10:16:16.241  5629  5675 I jxcore-log: 
,10-14 10:16:16.245  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:16.245  5629  5675 I jxcore-log: 
,10-14 10:16:16.256  5629  5675 I jxcore-log: # setup
10-14 10:16:16.256  5629  5675 I jxcore-log: 
,10-14 10:16:16.423  5629  5675 I jxcore-log: # native server connections all up
10-14 10:16:16.423  5629  5675 I jxcore-log: 
,10-14 10:16:16.558  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:16.558  5629  5675 I jxcore-log: 
,10-14 10:16:16.561  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'listening 47758'
10-14 10:16:16.561  5629  5675 I jxcore-log: 
,10-14 10:16:16.569  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:16.569  5629  5675 I jxcore-log: 
,10-14 10:16:16.571  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:16.571  5629  5675 I jxcore-log: 
,10-14 10:16:16.573  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new mux'
10-14 10:16:16.573  5629  5675 I jxcore-log: 
,10-14 10:16:16.607  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:16.607  5629  5675 I jxcore-log: 
,10-14 10:16:16.611  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:16.611  5629  5675 I jxcore-log: 
,10-14 10:16:16.615  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:16.615  5629  5675 I jxcore-log: 
,10-14 10:16:16.618  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:16.618  5629  5675 I jxcore-log: 
,10-14 10:16:16.643  5629  5675 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-14 10:16:16.643  5629  5675 I jxcore-log: 
,10-14 10:16:16.643  5629  5675 I jxcore-log: ok 8 Send/recvd #1 should be same
10-14 10:16:16.643  5629  5675 I jxcore-log: 
10-14 10:16:16.646  5629  5675 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-14 10:16:16.646  5629  5675 I jxcore-log: 
10-14 10:16:16.647  5629  5675 I jxcore-log: ok 10 Send/recvd #2 should be same
10-14 10:16:16.647  5629  5675 I jxcore-log: 
,10-14 10:16:16.650  5629  5675 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-14 10:16:16.650  5629  5675 I jxcore-log: 
,10-14 10:16:16.658  5629  5675 I jxcore-log: # teardown
10-14 10:16:16.658  5629  5675 I jxcore-log: 
,10-14 10:16:16.701  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:16.701  5629  5675 I jxcore-log: 
,10-14 10:16:16.703  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:16.703  5629  5675 I jxcore-log: 
,10-14 10:16:16.705  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'mux close'
10-14 10:16:16.705  5629  5675 I jxcore-log: 
,10-14 10:16:16.709  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:16.709  5629  5675 I jxcore-log: 
,10-14 10:16:16.720  5629  5675 I jxcore-log: # setup
10-14 10:16:16.720  5629  5675 I jxcore-log: 
,10-14 10:16:16.759  5629  5675 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-14 10:16:16.759  5629  5675 I jxcore-log: 
,10-14 10:16:16.803  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:16.803  5629  5675 I jxcore-log: 
,10-14 10:16:16.806  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'listening 44538'
10-14 10:16:16.806  5629  5675 I jxcore-log: 
,10-14 10:16:16.811  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:16.811  5629  5675 I jxcore-log: 
,10-14 10:16:16.812  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:16.812  5629  5675 I jxcore-log: 
,10-14 10:16:16.816  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new mux'
10-14 10:16:16.816  5629  5675 I jxcore-log: 
,10-14 10:16:16.827  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:16.827  5629  5675 I jxcore-log: 
,10-14 10:16:16.830  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:16.830  5629  5675 I jxcore-log: 
,10-14 10:16:16.840  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:16.840  5629  5675 I jxcore-log: 
,10-14 10:16:16.851  5629  5675 I jxcore-log: ok 12 socket shouldn't close until after stream
10-14 10:16:16.851  5629  5675 I jxcore-log: 
,10-14 10:16:16.852  5629  5675 I jxcore-log: ok 13 incoming remains open
10-14 10:16:16.852  5629  5675 I jxcore-log: 
,10-14 10:16:16.859  5629  5675 I jxcore-log: # teardown
10-14 10:16:16.859  5629  5675 I jxcore-log: 
,10-14 10:16:16.929  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'mux close'
10-14 10:16:16.929  5629  5675 I jxcore-log: 
,10-14 10:16:16.935  5629  5675 I jxcore-log: 2016-10-14 14:16:16 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:16.935  5629  5675 I jxcore-log: 
,10-14 10:16:16.943  5629  5675 I jxcore-log: # setup
10-14 10:16:16.943  5629  5675 I jxcore-log: 
,10-14 10:16:16.999  5629  5675 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-14 10:16:16.999  5629  5675 I jxcore-log: 
,10-14 10:16:17.037  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:17.037  5629  5675 I jxcore-log: 
,10-14 10:16:17.041  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'listening 38083'
10-14 10:16:17.041  5629  5675 I jxcore-log: 
,10-14 10:16:17.049  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.049  5629  5675 I jxcore-log: 
,10-14 10:16:17.051  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.051  5629  5675 I jxcore-log: 
,10-14 10:16:17.052  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.052  5629  5675 I jxcore-log: 
,10-14 10:16:17.063  5629  5675 I jxcore-log: ok 14 we should not have gotten an error
10-14 10:16:17.063  5629  5675 I jxcore-log: 
,10-14 10:16:17.068  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.068  5629  5675 I jxcore-log: 
,10-14 10:16:17.073  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.073  5629  5675 I jxcore-log: 
,10-14 10:16:17.082  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.082  5629  5675 I jxcore-log: 
,10-14 10:16:17.084  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:17.084  5629  5675 I jxcore-log: 
,10-14 10:16:17.094  5629  5675 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-14 10:16:17.094  5629  5675 I jxcore-log: 
,10-14 10:16:17.095  5629  5675 I jxcore-log: ok 16 incoming is cleaned up
10-14 10:16:17.095  5629  5675 I jxcore-log: 
,10-14 10:16:17.103  5629  5675 I jxcore-log: # teardown
10-14 10:16:17.103  5629  5675 I jxcore-log: 
,10-14 10:16:17.165  5629  5675 I jxcore-log: # setup
10-14 10:16:17.165  5629  5675 I jxcore-log: 
,10-14 10:16:17.229  5629  5675 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-14 10:16:17.229  5629  5675 I jxcore-log: 
,10-14 10:16:17.268  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:17.268  5629  5675 I jxcore-log: 
,10-14 10:16:17.272  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'listening 48564'
10-14 10:16:17.272  5629  5675 I jxcore-log: 
,10-14 10:16:17.279  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.279  5629  5675 I jxcore-log: 
,10-14 10:16:17.280  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.280  5629  5675 I jxcore-log: 
,10-14 10:16:17.283  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.283  5629  5675 I jxcore-log: 
,10-14 10:16:17.297  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.297  5629  5675 I jxcore-log: 
,10-14 10:16:17.300  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.300  5629  5675 I jxcore-log: 
,10-14 10:16:17.315  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.315  5629  5675 I jxcore-log: 
,10-14 10:16:17.325  5629  5675 I jxcore-log: ok 17 stream was closed
10-14 10:16:17.325  5629  5675 I jxcore-log: 
,10-14 10:16:17.326  5629  5675 I jxcore-log: ok 18 incoming should survive
10-14 10:16:17.326  5629  5675 I jxcore-log: 
10-14 10:16:17.326  5629  5675 I jxcore-log: ok 19 mux should have no streams
10-14 10:16:17.326  5629  5675 I jxcore-log: 
,10-14 10:16:17.331  5629  5675 I jxcore-log: # teardown
10-14 10:16:17.331  5629  5675 I jxcore-log: 
,10-14 10:16:17.353  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.353  5629  5675 I jxcore-log: 
,10-14 10:16:17.364  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:17.364  5629  5675 I jxcore-log: 
,10-14 10:16:17.375  5629  5675 I jxcore-log: # setup
10-14 10:16:17.375  5629  5675 I jxcore-log: 
,10-14 10:16:17.461  5629  5675 I jxcore-log: # native server - closing the whole server cleans everything up
10-14 10:16:17.461  5629  5675 I jxcore-log: 
,10-14 10:16:17.510  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:17.510  5629  5675 I jxcore-log: 
,10-14 10:16:17.520  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'listening 38293'
10-14 10:16:17.520  5629  5675 I jxcore-log: 
,10-14 10:16:17.528  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.528  5629  5675 I jxcore-log: 
,10-14 10:16:17.529  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.529  5629  5675 I jxcore-log: 
,10-14 10:16:17.532  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.532  5629  5675 I jxcore-log: 
,10-14 10:16:17.542  5629  5675 I jxcore-log: ok 20 we should not have gotten an error
10-14 10:16:17.542  5629  5675 I jxcore-log: 
,10-14 10:16:17.548  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.548  5629  5675 I jxcore-log: 
,10-14 10:16:17.551  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.551  5629  5675 I jxcore-log: 
,10-14 10:16:17.561  5629  5675 I jxcore-log: ok 21 Buffers are identical
10-14 10:16:17.561  5629  5675 I jxcore-log: 
,10-14 10:16:17.564  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.564  5629  5675 I jxcore-log: 
,10-14 10:16:17.567  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.567  5629  5675 I jxcore-log: 
,10-14 10:16:17.569  5629  5675 I jxcore-log: ok 22 native server is nulled out
10-14 10:16:17.569  5629  5675 I jxcore-log: 
10-14 10:16:17.570  5629  5675 I jxcore-log: ok 23 native server should be closed
10-14 10:16:17.570  5629  5675 I jxcore-log: 
,10-14 10:16:17.570  5629  5675 I jxcore-log: ok 24 incoming has been removed
10-14 10:16:17.570  5629  5675 I jxcore-log: 
10-14 10:16:17.570  5629  5675 I jxcore-log: ok 25 Incoming should be done
10-14 10:16:17.570  5629  5675 I jxcore-log: 
,10-14 10:16:17.571  5629  5675 I jxcore-log: ok 26 The mux object should be closed
10-14 10:16:17.571  5629  5675 I jxcore-log: 
10-14 10:16:17.572  5629  5675 I jxcore-log: ok 27 The mux stream should be closed
10-14 10:16:17.572  5629  5675 I jxcore-log: 
10-14 10:16:17.573  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:17.573  5629  5675 I jxcore-log: 
,10-14 10:16:17.585  5629  5675 I jxcore-log: # teardown
10-14 10:16:17.585  5629  5675 I jxcore-log: 
,10-14 10:16:17.635  5629  5675 I jxcore-log: # setup
10-14 10:16:17.635  5629  5675 I jxcore-log: 
,10-14 10:16:17.680  5629  5675 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-14 10:16:17.680  5629  5675 I jxcore-log: 
,10-14 10:16:17.722  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:17.722  5629  5675 I jxcore-log: 
,10-14 10:16:17.726  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'listening 49929'
10-14 10:16:17.726  5629  5675 I jxcore-log: 
,10-14 10:16:17.759  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.759  5629  5675 I jxcore-log: 
,10-14 10:16:17.759  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.759  5629  5675 I jxcore-log: 
10-14 10:16:17.761  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.761  5629  5675 I jxcore-log: 
,10-14 10:16:17.763  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.763  5629  5675 I jxcore-log: 
,10-14 10:16:17.764  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.764  5629  5675 I jxcore-log: 
10-14 10:16:17.765  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.765  5629  5675 I jxcore-log: 
,10-14 10:16:17.767  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.767  5629  5675 I jxcore-log: 
10-14 10:16:17.768  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.768  5629  5675 I jxcore-log: 
,10-14 10:16:17.769  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.769  5629  5675 I jxcore-log: 
,10-14 10:16:17.772  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.772  5629  5675 I jxcore-log: 
,10-14 10:16:17.773  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.773  5629  5675 I jxcore-log: 
10-14 10:16:17.774  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.774  5629  5675 I jxcore-log: 
10-14 10:16:17.776  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.776  5629  5675 I jxcore-log: 
10-14 10:16:17.777  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.777  5629  5675 I jxcore-log: 
10-14 10:16:17.779  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.779  5629  5675 I jxcore-log: 
,10-14 10:16:17.782  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.782  5629  5675 I jxcore-log: 
,10-14 10:16:17.783  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.783  5629  5675 I jxcore-log: 
,10-14 10:16:17.784  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.784  5629  5675 I jxcore-log: 
,10-14 10:16:17.786  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.786  5629  5675 I jxcore-log: 
,10-14 10:16:17.787  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.787  5629  5675 I jxcore-log: 
,10-14 10:16:17.788  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.788  5629  5675 I jxcore-log: 
,10-14 10:16:17.797  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.797  5629  5675 I jxcore-log: 
,10-14 10:16:17.797  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.797  5629  5675 I jxcore-log: 
,10-14 10:16:17.798  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.798  5629  5675 I jxcore-log: 
,10-14 10:16:17.801  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.801  5629  5675 I jxcore-log: 
,10-14 10:16:17.801  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.801  5629  5675 I jxcore-log: 
,10-14 10:16:17.801  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.801  5629  5675 I jxcore-log: 
,10-14 10:16:17.803  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:17.803  5629  5675 I jxcore-log: 
10-14 10:16:17.803  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:17.803  5629  5675 I jxcore-log: 
,10-14 10:16:17.804  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new mux'
10-14 10:16:17.804  5629  5675 I jxcore-log: 
,10-14 10:16:17.858  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.858  5629  5675 I jxcore-log: 
,10-14 10:16:17.860  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.860  5629  5675 I jxcore-log: 
,10-14 10:16:17.862  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.862  5629  5675 I jxcore-log: 
,10-14 10:16:17.863  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.863  5629  5675 I jxcore-log: 
,10-14 10:16:17.864  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.864  5629  5675 I jxcore-log: 
,10-14 10:16:17.865  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.865  5629  5675 I jxcore-log: 
,10-14 10:16:17.866  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.866  5629  5675 I jxcore-log: 
10-14 10:16:17.867  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.867  5629  5675 I jxcore-log: 
,10-14 10:16:17.868  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.868  5629  5675 I jxcore-log: 
,10-14 10:16:17.869  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.869  5629  5675 I jxcore-log: 
,10-14 10:16:17.870  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.870  5629  5675 I jxcore-log: 
,10-14 10:16:17.871  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.871  5629  5675 I jxcore-log: 
10-14 10:16:17.872  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.872  5629  5675 I jxcore-log: 
,10-14 10:16:17.873  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.873  5629  5675 I jxcore-log: 
,10-14 10:16:17.873  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.873  5629  5675 I jxcore-log: 
10-14 10:16:17.874  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.874  5629  5675 I jxcore-log: 
,10-14 10:16:17.876  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.876  5629  5675 I jxcore-log: 
,10-14 10:16:17.877  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.877  5629  5675 I jxcore-log: 
10-14 10:16:17.877  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.877  5629  5675 I jxcore-log: 
,10-14 10:16:17.878  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.878  5629  5675 I jxcore-log: 
,10-14 10:16:17.879  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.879  5629  5675 I jxcore-log: 
,10-14 10:16:17.880  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.880  5629  5675 I jxcore-log: 
10-14 10:16:17.880  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.880  5629  5675 I jxcore-log: 
,10-14 10:16:17.881  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.881  5629  5675 I jxcore-log: 
,10-14 10:16:17.882  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.882  5629  5675 I jxcore-log: 
,10-14 10:16:17.883  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.883  5629  5675 I jxcore-log: 
10-14 10:16:17.884  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.884  5629  5675 I jxcore-log: 
,10-14 10:16:17.885  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.885  5629  5675 I jxcore-log: 
,10-14 10:16:17.885  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.885  5629  5675 I jxcore-log: 
10-14 10:16:17.886  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.886  5629  5675 I jxcore-log: 
,10-14 10:16:17.887  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.887  5629  5675 I jxcore-log: 
10-14 10:16:17.887  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.887  5629  5675 I jxcore-log: 
,10-14 10:16:17.888  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.888  5629  5675 I jxcore-log: 
10-14 10:16:17.889  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.889  5629  5675 I jxcore-log: 
,10-14 10:16:17.890  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.890  5629  5675 I jxcore-log: 
10-14 10:16:17.890  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.890  5629  5675 I jxcore-log: 
,10-14 10:16:17.891  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.891  5629  5675 I jxcore-log: 
10-14 10:16:17.892  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.892  5629  5675 I jxcore-log: 
,10-14 10:16:17.892  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.892  5629  5675 I jxcore-log: 
,10-14 10:16:17.893  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.893  5629  5675 I jxcore-log: 
10-14 10:16:17.894  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.894  5629  5675 I jxcore-log: 
,10-14 10:16:17.894  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.894  5629  5675 I jxcore-log: 
10-14 10:16:17.895  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.895  5629  5675 I jxcore-log: 
,10-14 10:16:17.896  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.896  5629  5675 I jxcore-log: 
10-14 10:16:17.896  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.896  5629  5675 I jxcore-log: 
,10-14 10:16:17.897  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.897  5629  5675 I jxcore-log: 
10-14 10:16:17.898  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.898  5629  5675 I jxcore-log: 
,10-14 10:16:17.898  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.898  5629  5675 I jxcore-log: 
,10-14 10:16:17.904  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.904  5629  5675 I jxcore-log: 
,10-14 10:16:17.905  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.905  5629  5675 I jxcore-log: 
,10-14 10:16:17.906  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.906  5629  5675 I jxcore-log: 
,10-14 10:16:17.907  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.907  5629  5675 I jxcore-log: 
10-14 10:16:17.907  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.907  5629  5675 I jxcore-log: 
,10-14 10:16:17.908  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.908  5629  5675 I jxcore-log: 
10-14 10:16:17.908  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.908  5629  5675 I jxcore-log: 
,10-14 10:16:17.909  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.909  5629  5675 I jxcore-log: 
,10-14 10:16:17.910  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.910  5629  5675 I jxcore-log: 
10-14 10:16:17.911  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.911  5629  5675 I jxcore-log: 
,10-14 10:16:17.912  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.912  5629  5675 I jxcore-log: 
10-14 10:16:17.912  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.912  5629  5675 I jxcore-log: 
,10-14 10:16:17.913  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.913  5629  5675 I jxcore-log: 
10-14 10:16:17.914  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.914  5629  5675 I jxcore-log: 
,10-14 10:16:17.914  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.914  5629  5675 I jxcore-log: 
10-14 10:16:17.915  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.915  5629  5675 I jxcore-log: 
,10-14 10:16:17.916  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.916  5629  5675 I jxcore-log: 
,10-14 10:16:17.917  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.917  5629  5675 I jxcore-log: 
10-14 10:16:17.917  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.917  5629  5675 I jxcore-log: 
,10-14 10:16:17.918  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.918  5629  5675 I jxcore-log: 
10-14 10:16:17.918  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.918  5629  5675 I jxcore-log: 
,10-14 10:16:17.919  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.919  5629  5675 I jxcore-log: 
10-14 10:16:17.919  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.919  5629  5675 I jxcore-log: 
,10-14 10:16:17.920  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.920  5629  5675 I jxcore-log: 
10-14 10:16:17.921  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.921  5629  5675 I jxcore-log: 
,10-14 10:16:17.922  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.922  5629  5675 I jxcore-log: 
,10-14 10:16:17.922  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.922  5629  5675 I jxcore-log: 
,10-14 10:16:17.923  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.923  5629  5675 I jxcore-log: 
10-14 10:16:17.924  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.924  5629  5675 I jxcore-log: 
,10-14 10:16:17.924  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.924  5629  5675 I jxcore-log: 
10-14 10:16:17.925  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:17.925  5629  5675 I jxcore-log: 
,10-14 10:16:17.926  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:17.926  5629  5675 I jxcore-log: 
,10-14 10:16:17.970  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.970  5629  5675 I jxcore-log: 
,10-14 10:16:17.971  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.971  5629  5675 I jxcore-log: 
,10-14 10:16:17.972  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.972  5629  5675 I jxcore-log: 
10-14 10:16:17.972  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.972  5629  5675 I jxcore-log: 
10-14 10:16:17.973  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.973  5629  5675 I jxcore-log: 
,10-14 10:16:17.974  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.974  5629  5675 I jxcore-log: 
10-14 10:16:17.974  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.974  5629  5675 I jxcore-log: 
,10-14 10:16:17.974  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.974  5629  5675 I jxcore-log: 
10-14 10:16:17.975  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.975  5629  5675 I jxcore-log: 
10-14 10:16:17.975  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.975  5629  5675 I jxcore-log: 
10-14 10:16:17.976  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.976  5629  5675 I jxcore-log: 
,10-14 10:16:17.976  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.976  5629  5675 I jxcore-log: 
10-14 10:16:17.977  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.977  5629  5675 I jxcore-log: 
10-14 10:16:17.977  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.977  5629  5675 I jxcore-log: 
,10-14 10:16:17.978  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.978  5629  5675 I jxcore-log: 
10-14 10:16:17.978  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.978  5629  5675 I jxcore-log: 
,10-14 10:16:17.979  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.979  5629  5675 I jxcore-log: 
10-14 10:16:17.979  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.979  5629  5675 I jxcore-log: 
,10-14 10:16:17.979  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.979  5629  5675 I jxcore-log: 
10-14 10:16:17.980  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.980  5629  5675 I jxcore-log: 
10-14 10:16:17.980  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.980  5629  5675 I jxcore-log: 
10-14 10:16:17.981  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.981  5629  5675 I jxcore-log: 
10-14 10:16:17.981  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.981  5629  5675 I jxcore-log: 
,10-14 10:16:17.982  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.982  5629  5675 I jxcore-log: 
10-14 10:16:17.982  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.982  5629  5675 I jxcore-log: 
,10-14 10:16:17.983  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.983  5629  5675 I jxcore-log: 
10-14 10:16:17.983  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.983  5629  5675 I jxcore-log: 
10-14 10:16:17.984  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.984  5629  5675 I jxcore-log: 
,10-14 10:16:17.984  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.984  5629  5675 I jxcore-log: 
10-14 10:16:17.984  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.984  5629  5675 I jxcore-log: 
10-14 10:16:17.985  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.985  5629  5675 I jxcore-log: 
,10-14 10:16:17.985  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.985  5629  5675 I jxcore-log: 
10-14 10:16:17.986  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.986  5629  5675 I jxcore-log: 
10-14 10:16:17.986  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.986  5629  5675 I jxcore-log: 
,10-14 10:16:17.987  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.987  5629  5675 I jxcore-log: 
10-14 10:16:17.987  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.987  5629  5675 I jxcore-log: 
10-14 10:16:17.987  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.987  5629  5675 I jxcore-log: 
,10-14 10:16:17.988  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.988  5629  5675 I jxcore-log: 
10-14 10:16:17.988  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.988  5629  5675 I jxcore-log: 
10-14 10:16:17.989  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.989  5629  5675 I jxcore-log: 
10-14 10:16:17.989  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.989  5629  5675 I jxcore-log: 
,10-14 10:16:17.989  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.989  5629  5675 I jxcore-log: 
10-14 10:16:17.990  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.990  5629  5675 I jxcore-log: 
10-14 10:16:17.990  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.990  5629  5675 I jxcore-log: 
,10-14 10:16:17.992  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.992  5629  5675 I jxcore-log: 
,10-14 10:16:17.992  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.992  5629  5675 I jxcore-log: 
,10-14 10:16:17.995  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.995  5629  5675 I jxcore-log: 
,10-14 10:16:17.995  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.995  5629  5675 I jxcore-log: 
,10-14 10:16:17.996  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:17.996  5629  5675 I jxcore-log: 
10-14 10:16:17.996  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'mux close'
10-14 10:16:17.996  5629  5675 I jxcore-log: 
,10-14 10:16:17.998  5629  5675 I jxcore-log: ok 28 native server is nulled out
10-14 10:16:17.998  5629  5675 I jxcore-log: 
,10-14 10:16:17.999  5629  5675 I jxcore-log: ok 29 native server should be closed
10-14 10:16:17.999  5629  5675 I jxcore-log: 
10-14 10:16:17.999  5629  5675 I jxcore-log: ok 30 incoming has been removed
10-14 10:16:17.999  5629  5675 I jxcore-log: 
,10-14 10:16:18.000  5629  5675 I jxcore-log: 2016-10-14 14:16:17 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.000  5629  5675 I jxcore-log: 
10-14 10:16:18.000  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.000  5629  5675 I jxcore-log: 
10-14 10:16:18.000  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.000  5629  5675 I jxcore-log: 
,10-14 10:16:18.001  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.001  5629  5675 I jxcore-log: 
10-14 10:16:18.001  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.001  5629  5675 I jxcore-log: 
10-14 10:16:18.001  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.001  5629  5675 I jxcore-log: 
10-14 10:16:18.001  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.001  5629  5675 I jxcore-log: 
,10-14 10:16:18.002  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.002  5629  5675 I jxcore-log: 
10-14 10:16:18.002  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.002  5629  5675 I jxcore-log: 
10-14 10:16:18.002  5629  5675 I jxcore-log: 2016-10-14 14:16:18 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:18.002  5629  5675 I jxcore-log: 
,10-14 10:16:18.074  5629  5675 I jxcore-log: # teardown
10-14 10:16:18.074  5629  5675 I jxcore-log: 
,10-14 10:16:18.172  5629  5675 I jxcore-log: # setup
10-14 10:16:18.172  5629  5675 I jxcore-log: 
,10-14 10:16:19.915  5629  5675 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-14 10:16:19.915  5629  5675 I jxcore-log: 
,10-14 10:16:20.823  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:20.823  5629  5675 I jxcore-log: 
,10-14 10:16:20.828  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'listening 45625'
10-14 10:16:20.828  5629  5675 I jxcore-log: 
,10-14 10:16:20.836  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:20.836  5629  5675 I jxcore-log: 
,10-14 10:16:20.838  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:20.838  5629  5675 I jxcore-log: 
,10-14 10:16:20.841  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'new mux'
10-14 10:16:20.841  5629  5675 I jxcore-log: 
,10-14 10:16:20.847  5629  5675 I jxcore-log: ok 31 we should not have gotten an error
10-14 10:16:20.847  5629  5675 I jxcore-log: 
,10-14 10:16:20.850  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:20.850  5629  5675 I jxcore-log: 
,10-14 10:16:20.853  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:20.853  5629  5675 I jxcore-log: 
,10-14 10:16:20.860  5629  5675 I jxcore-log: ok 32 Buffers are identical
10-14 10:16:20.860  5629  5675 I jxcore-log: 
,10-14 10:16:20.861  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:20.861  5629  5675 I jxcore-log: 
,10-14 10:16:20.862  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'mux close'
10-14 10:16:20.862  5629  5675 I jxcore-log: 
,10-14 10:16:20.872  5629  5675 I jxcore-log: 2016-10-14 14:16:20 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:20.872  5629  5675 I jxcore-log: 
,10-14 10:16:20.873  5629  5675 I jxcore-log: ok 33 server should be fine
10-14 10:16:20.873  5629  5675 I jxcore-log: 
10-14 10:16:20.873  5629  5675 I jxcore-log: ok 34 server should be open
10-14 10:16:20.873  5629  5675 I jxcore-log: 
,10-14 10:16:20.874  5629  5675 I jxcore-log: ok 35 incoming has been removed
10-14 10:16:20.874  5629  5675 I jxcore-log: 
10-14 10:16:20.874  5629  5675 I jxcore-log: ok 36 The mux object should be closed
10-14 10:16:20.874  5629  5675 I jxcore-log: 
10-14 10:16:20.875  5629  5675 I jxcore-log: ok 37 The mux stream should be closed
10-14 10:16:20.875  5629  5675 I jxcore-log: 
,10-14 10:16:20.880  5629  5675 I jxcore-log: # teardown
10-14 10:16:20.880  5629  5675 I jxcore-log: 
,10-14 10:16:21.232  5629  5675 I jxcore-log: # setup
10-14 10:16:21.232  5629  5675 I jxcore-log: 
,10-14 10:16:21.756  5629  5675 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-14 10:16:21.756  5629  5675 I jxcore-log: 
,10-14 10:16:22.355  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'creating native server'
10-14 10:16:22.355  5629  5675 I jxcore-log: 
,10-14 10:16:22.363  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'listening 42752'
10-14 10:16:22.363  5629  5675 I jxcore-log: 
,10-14 10:16:22.371  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'new incoming socket'
10-14 10:16:22.371  5629  5675 I jxcore-log: 
,10-14 10:16:22.372  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'creating incoming mux'
10-14 10:16:22.372  5629  5675 I jxcore-log: 
,10-14 10:16:22.374  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'new mux'
10-14 10:16:22.374  5629  5675 I jxcore-log: 
,10-14 10:16:22.382  5629  5675 I jxcore-log: ok 38 we should not have gotten an error
10-14 10:16:22.382  5629  5675 I jxcore-log: 
,10-14 10:16:22.385  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'new stream: '
10-14 10:16:22.385  5629  5675 I jxcore-log: 
,10-14 10:16:22.387  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'new outgoing socket'
10-14 10:16:22.387  5629  5675 I jxcore-log: 
,10-14 10:16:22.394  5629  5675 I jxcore-log: ok 39 Buffers are identical
10-14 10:16:22.394  5629  5675 I jxcore-log: 
,10-14 10:16:22.398  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'incoming socket timeout'
10-14 10:16:22.398  5629  5675 I jxcore-log: 
,10-14 10:16:22.399  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'stream close:'
10-14 10:16:22.399  5629  5675 I jxcore-log: 
,10-14 10:16:22.401  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'mux close'
10-14 10:16:22.401  5629  5675 I jxcore-log: 
,10-14 10:16:22.405  5629  5675 I jxcore-log: 2016-10-14 14:16:22 - DEBUG createNativeListener: 'incoming socket close'
10-14 10:16:22.405  5629  5675 I jxcore-log: 
10-14 10:16:22.405  5629  5675 I jxcore-log: ok 40 server should be fine
10-14 10:16:22.405  5629  5675 I jxcore-log: 
10-14 10:16:22.405  5629  5675 I jxcore-log: ok 41 server should be open
10-14 10:16:22.405  5629  5675 I jxcore-log: 
10-14 10:16:22.406  5629  5675 I jxcore-log: ok 42 incoming has been removed
10-14 10:16:22.406  5629  5675 I jxcore-log: 
10-14 10:16:22.406  5629  5675 I jxcore-log: ok 43 The mux object should be closed
10-14 10:16:22.406  5629  5675 I jxcore-log: 
10-14 10:16:22.406  5629  5675 I jxcore-log: ok 44 The mux stream should be closed
10-14 10:16:22.406  5629  5675 I jxcore-log: 
,10-14 10:16:22.413  5629  5675 I jxcore-log: # teardown
10-14 10:16:22.413  5629  5675 I jxcore-log: 
,10-14 10:16:22.982  5629  5675 I jxcore-log: # setup
10-14 10:16:22.982  5629  5675 I jxcore-log: 
,10-14 10:16:23.690  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-14 10:16:23.690  5629  5675 I jxcore-log: 
,10-14 10:16:23.872  5629  5675 I jxcore-log: 2016-10-14 14:16:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-14 10:16:23.872  5629  5675 I jxcore-log: 
,10-14 10:16:23.872  5629  5675 I jxcore-log: ok 45 Got right error
10-14 10:16:23.872  5629  5675 I jxcore-log: 
,10-14 10:16:23.878  5629  5675 I jxcore-log: # teardown
10-14 10:16:23.878  5629  5675 I jxcore-log: 
,10-14 10:16:23.897  5629  5675 I jxcore-log: # setup
10-14 10:16:23.897  5629  5675 I jxcore-log: 
,10-14 10:16:23.923  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-14 10:16:23.923  5629  5675 I jxcore-log: 
,10-14 10:16:24.047  5629  5675 I jxcore-log: 2016-10-14 14:16:24 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-14 10:16:24.047  5629  5675 I jxcore-log: 
,10-14 10:16:24.048  5629  5675 I jxcore-log: ok 46 Got socket hang up
10-14 10:16:24.048  5629  5675 I jxcore-log: 
,10-14 10:16:24.054  5629  5675 I jxcore-log: # teardown
10-14 10:16:24.054  5629  5675 I jxcore-log: 
,10-14 10:16:24.083  5629  5675 I jxcore-log: # setup
10-14 10:16:24.083  5629  5675 I jxcore-log: 
,10-14 10:16:24.123  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-14 10:16:24.123  5629  5675 I jxcore-log: 
,10-14 10:16:24.290  5629  5675 I jxcore-log: 2016-10-14 14:16:24 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-14 10:16:24.290  5629  5675 I jxcore-log: 
,10-14 10:16:24.291  5629  5675 I jxcore-log: ok 47 Got 500 as expected
10-14 10:16:24.291  5629  5675 I jxcore-log: 
,10-14 10:16:24.295  5629  5675 I jxcore-log: # teardown
10-14 10:16:24.295  5629  5675 I jxcore-log: 
,10-14 10:16:24.376  5629  5675 I jxcore-log: # setup
10-14 10:16:24.376  5629  5675 I jxcore-log: 
,10-14 10:16:24.399  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-14 10:16:24.399  5629  5675 I jxcore-log: 
,10-14 10:16:25.924  5629  5675 I jxcore-log: ok 48 should be equal
10-14 10:16:25.924  5629  5675 I jxcore-log: 
,10-14 10:16:25.924  5629  5675 I jxcore-log: ok 49 revs are equal
10-14 10:16:25.924  5629  5675 I jxcore-log: 
,10-14 10:16:25.933  5629  5675 I jxcore-log: # teardown
10-14 10:16:25.933  5629  5675 I jxcore-log: 
,10-14 10:16:25.982  5629  5675 I jxcore-log: # setup
10-14 10:16:25.982  5629  5675 I jxcore-log: 
,10-14 10:16:27.179  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-14 10:16:27.179  5629  5675 I jxcore-log: 
,10-14 10:16:27.656   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:28.041  5629  5675 I jxcore-log: ok 50 should be equal
10-14 10:16:28.041  5629  5675 I jxcore-log: 
,10-14 10:16:28.042  5629  5675 I jxcore-log: ok 51 revs are equal
10-14 10:16:28.042  5629  5675 I jxcore-log: 
,10-14 10:16:28.050  5629  5675 I jxcore-log: # teardown
10-14 10:16:28.050  5629  5675 I jxcore-log: 
,10-14 10:16:28.657   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:28.736  5629  5675 I jxcore-log: # setup
10-14 10:16:28.736  5629  5675 I jxcore-log: 
,10-14 10:16:28.753  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times,
10-14 10:16:28.753  5629  5675 I jxcore-log: 
,10-14 10:16:29.388  5629  5675 I jxcore-log: ok 52 should be equal
10-14 10:16:29.388  5629  5675 I jxcore-log: 
,10-14 10:16:29.388  5629  5675 I jxcore-log: ok 53 revs are equal
10-14 10:16:29.388  5629  5675 I jxcore-log: 
,10-14 10:16:29.564  5629  5675 I jxcore-log: ok 54 should be equal
10-14 10:16:29.564  5629  5675 I jxcore-log: 
,10-14 10:16:29.565  5629  5675 I jxcore-log: ok 55 revs are equal
10-14 10:16:29.565  5629  5675 I jxcore-log: 
,10-14 10:16:29.658   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:29.752  5629  5675 I jxcore-log: ok 56 should be equal
10-14 10:16:29.752  5629  5675 I jxcore-log: 
10-14 10:16:29.752  5629  5675 I jxcore-log: ok 57 revs are equal
10-14 10:16:29.752  5629  5675 I jxcore-log: 
,10-14 10:16:29.761  5629  5675 I jxcore-log: # teardown
10-14 10:16:29.761  5629  5675 I jxcore-log: 
,10-14 10:16:29.826  5629  5675 I jxcore-log: # setup
10-14 10:16:29.826  5629  5675 I jxcore-log: 
,10-14 10:16:29.882  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-14 10:16:29.882  5629  5675 I jxcore-log: 
,10-14 10:16:30.659   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:30.660  5629  5675 I jxcore-log: 2016-10-14 14:16:30 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-14 10:16:30.660  5629  5675 I jxcore-log: 
,10-14 10:16:30.662  5629  5675 I jxcore-log: ok 58 Our rev is old so we should fail
10-14 10:16:30.662  5629  5675 I jxcore-log: 
,10-14 10:16:30.680  5629  5675 I jxcore-log: # teardown
10-14 10:16:30.680  5629  5675 I jxcore-log: 
,10-14 10:16:30.726  5629  5675 I jxcore-log: # setup
10-14 10:16:30.726  5629  5675 I jxcore-log: 
,10-14 10:16:30.775  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-14 10:16:30.775  5629  5675 I jxcore-log: 
,10-14 10:16:30.903  5629  5675 I jxcore-log: ok 59 confirm stop caused failure
10-14 10:16:30.903  5629  5675 I jxcore-log: 
,10-14 10:16:30.915  5629  5675 I jxcore-log: # teardown
10-14 10:16:30.915  5629  5675 I jxcore-log: 
,10-14 10:16:30.944  5629  5675 I jxcore-log: # setup
10-14 10:16:30.944  5629  5675 I jxcore-log: 
,10-14 10:16:31.006  5629  5675 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-14 10:16:31.006  5629  5675 I jxcore-log: 
,10-14 10:16:31.420  5629  5675 I jxcore-log: 2016-10-14 14:16:31 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-14 10:16:31.420  5629  5675 I jxcore-log: 
,10-14 10:16:31.421  5629  5675 I jxcore-log: ok 60 stop caused us to fail
10-14 10:16:31.421  5629  5675 I jxcore-log: 
10-14 10:16:31.422  5629  5675 I jxcore-log: ok 61 We specifically failed on a stop before put
10-14 10:16:31.422  5629  5675 I jxcore-log: 
,10-14 10:16:31.437  5629  5675 I jxcore-log: # teardown
10-14 10:16:31.437  5629  5675 I jxcore-log: 
,10-14 10:16:31.498  5629  5675 I jxcore-log: # setup
10-14 10:16:31.498  5629  5675 I jxcore-log: 
,10-14 10:16:31.561  5629  5675 I jxcore-log: # #update - fail if stop is called
10-14 10:16:31.561  5629  5675 I jxcore-log: 
,10-14 10:16:31.645  5629  5675 I jxcore-log: ok 62 failed due to stop
10-14 10:16:31.645  5629  5675 I jxcore-log: 
,10-14 10:16:31.647  5629  5675 I jxcore-log: ok 63 failed due to stop
10-14 10:16:31.647  5629  5675 I jxcore-log: 
,10-14 10:16:31.656  5629  5675 I jxcore-log: # teardown
10-14 10:16:31.656  5629  5675 I jxcore-log: 
,10-14 10:16:31.660   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:31.740  5629  5675 I jxcore-log: # setup
10-14 10:16:31.740  5629  5675 I jxcore-log: 
,10-14 10:16:31.771  5629  5675 I jxcore-log: # #update - set seq for first time
10-14 10:16:31.771  5629  5675 I jxcore-log: 
,10-14 10:16:32.457  5629  5675 I jxcore-log: ok 64 should be equal
10-14 10:16:32.457  5629  5675 I jxcore-log: 
,10-14 10:16:32.483  5629  5675 I jxcore-log: # teardown
10-14 10:16:32.483  5629  5675 I jxcore-log: 
,10-14 10:16:32.660   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-14 10:16:33.051   929  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 10:16:33.658  5629  5675 I jxcore-log: # setup
10-14 10:16:33.658  5629  5675 I jxcore-log: 
,10-14 10:16:33.675  5629  5675 I jxcore-log: # #update - Fail on bad seq value
10-14 10:16:33.675  5629  5675 I jxcore-log: 
,10-14 10:16:34.659  5629  5675 I jxcore-log: 2016-10-14 14:16:34 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-14 10:16:34.659  5629  5675 I jxcore-log: 
,10-14 10:16:34.661  5629  5675 I jxcore-log: ok 65 Expected bad seq error
10-14 10:16:34.661  5629  5675 I jxcore-log: 
,10-14 10:16:34.680  5629  5675 I jxcore-log: # teardown
10-14 10:16:34.680  5629  5675 I jxcore-log: 
,10-14 10:16:34.733  5629  5675 I jxcore-log: # setup
10-14 10:16:34.733  5629  5675 I jxcore-log: 
,10-14 10:16:34.778  5629  5675 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-14 10:16:34.778  5629  5675 I jxcore-log: 
,10-14 10:16:36.277  5629  5675 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-14 10:16:36.277  5629  5675 E jxcore-log: 
,10-14 10:16:36.278  5629  5675 E jxcore-log: Trace: 
10-14 10:16:36.278  5629  5675 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-14 10:16:36.278  5629  5675 E jxcore-log:     at addListener@events.js:140:1
10-14 10:16:36.278  5629  5675 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
10-14 10:16:36.278  5629  5675 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-14 10:16:36.278  5629  5675 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-14 10:16:36.278  5629  5675 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-14 10:16:36.278  5629  5675 E jxcore-log: 
,10-14 10:16:36.791  5629  5675 I jxcore-log: ok 66 Different promises
10-14 10:16:36.791  5629  5675 I jxcore-log: 
,10-14 10:16:36.793  5629  5675 I jxcore-log: ok 67 Timer was cancelled
10-14 10:16:36.793  5629  5675 I jxcore-log: 
,10-14 10:16:37.019  5629  5675 I jxcore-log: ok 68 should be equal
10-14 10:16:37.019  5629  5675 I jxcore-log: 
,10-14 10:16:37.049  5629  5675 I jxcore-log: # teardown
10-14 10:16:37.049  5629  5675 I jxcore-log: 
,10-14 10:16:37.127  5629  5675 I jxcore-log: # setup
10-14 10:16:37.127  5629  5675 I jxcore-log: 
,10-14 10:16:37.662   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:38.229  5629  5675 I jxcore-log: # #update - do we wait for blocked update
10-14 10:16:38.229  5629  5675 I jxcore-log: 
,10-14 10:16:38.339  5629  5675 I jxcore-log: ok 69 One go and one blocked
10-14 10:16:38.339  5629  5675 I jxcore-log: 
10-14 10:16:38.339  5629  5675 I jxcore-log: ok 70 All blocked
10-14 10:16:38.339  5629  5675 I jxcore-log: 
10-14 10:16:38.341  5629  5675 I jxcore-log: ok 71 Still blocked
10-14 10:16:38.341  5629  5675 I jxcore-log: 
,10-14 10:16:38.357  5629  5675 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-14 10:16:38.357  5629  5675 E jxcore-log: 
,10-14 10:16:38.358  5629  5675 E jxcore-log: Trace: 
10-14 10:16:38.358  5629  5675 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-14 10:16:38.358  5629  5675 E jxcore-log:     at addListener@events.js:140:1
10-14 10:16:38.358  5629  5675 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
10-14 10:16:38.358  5629  5675 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-14 10:16:38.358  5629  5675 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-14 10:16:38.358  5629  5675 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-14 10:16:38.358  5629  5675 E jxcore-log: 
,10-14 10:16:38.663   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:39.012  5629  5675 I jxcore-log: ok 72 should be equal
10-14 10:16:39.012  5629  5675 I jxcore-log: 
,10-14 10:16:39.042  5629  5675 I jxcore-log: # teardown
10-14 10:16:39.042  5629  5675 I jxcore-log: 
,10-14 10:16:39.098  5629  5675 I jxcore-log: # setup
10-14 10:16:39.098  5629  5675 I jxcore-log: 
,10-14 10:16:39.164  5629  5675 I jxcore-log: # #update - test that we wait long enough
10-14 10:16:39.164  5629  5675 I jxcore-log: 
,10-14 10:16:39.664   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:40.534  5629  5675 I jxcore-log: ok 73 We waited long enough
10-14 10:16:40.534  5629  5675 I jxcore-log: 
,10-14 10:16:40.665   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:40.721  5629  5675 I jxcore-log: ok 74 should be equal
10-14 10:16:40.721  5629  5675 I jxcore-log: 
,10-14 10:16:40.743  5629  5675 I jxcore-log: # teardown
10-14 10:16:40.743  5629  5675 I jxcore-log: 
,10-14 10:16:40.867  5629  5675 I jxcore-log: # setup
10-14 10:16:40.867  5629  5675 I jxcore-log: 
,10-14 10:16:41.666   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:42.532  5629  5675 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-14 10:16:42.532  5629  5675 I jxcore-log: 
,10-14 10:16:42.667   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-14 10:16:43.817  5629  5675 I jxcore-log: ok 75 Should have gotten same timer promise
10-14 10:16:43.817  5629  5675 I jxcore-log: 
,10-14 10:16:43.818  5629  5675 I jxcore-log: ok 76 Still same timer promise
10-14 10:16:43.818  5629  5675 I jxcore-log: 
,10-14 10:16:44.406  5629  5675 I jxcore-log: ok 77 We waited long enough
10-14 10:16:44.406  5629  5675 I jxcore-log: 
,10-14 10:16:44.531  5629  5675 I jxcore-log: ok 78 should be equal
10-14 10:16:44.531  5629  5675 I jxcore-log: 
,10-14 10:16:44.599  5629  5675 I jxcore-log: # teardown
10-14 10:16:44.599  5629  5675 I jxcore-log: 
,10-14 10:16:45.148  5629  5675 I jxcore-log: # setup
10-14 10:16:45.148  5629  5675 I jxcore-log: 
,10-14 10:16:45.407  5629  5675 I jxcore-log: # Coordinated seq test
10-14 10:16:45.407  5629  5675 I jxcore-log: 
,10-14 10:16:45.578  5629  5675 I jxcore-log: 2016-10-14 14:16:45 - DEBUG thaliWifiInfrastructure: 'listening 48051'
10-14 10:16:45.578  5629  5675 I jxcore-log: 
,10-14 10:16:47.922  5629  5675 I jxcore-log: ok 79 should be equal
10-14 10:16:47.922  5629  5675 I jxcore-log: 
,10-14 10:16:48.454  5629  5675 I jxcore-log: ok 80 should be equal
10-14 10:16:48.454  5629  5675 I jxcore-log: 
,10-14 10:16:48.480  5629  5675 I jxcore-log: # teardown
10-14 10:16:48.480  5629  5675 I jxcore-log: 
,10-14 10:16:52.668   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:53.671   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:54.672   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:55.673   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:56.675   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:16:57.675   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-14 10:17:12.677   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:13.053   929  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 10:17:13.678   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:14.680   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:15.682   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:16.683   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:17.683   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-14 10:17:33.055   929  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 10:17:37.685   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:38.686   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:39.687   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:40.688   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:41.690   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 10:17:42.690   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-14 10:17:48.497  5629  5675 I jxcore-log: 2016-10-14 14:17:48 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-14 10:17:48.497  5629  5675 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-14 10:17:48.497  5629  5675 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-14 10:17:48.497  5629  5675 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-14 10:17:48.497  5629  5675 I jxcore-log:     at $9@timers.js:120:1
10-14 10:17:48.497  5629  5675 I jxcore-log: ''
10-14 10:17:48.497  5629  5675 I jxcore-log: 
10-14 10:17:48.499  5629  5675 I jxcore-log: 2016-10-14 14:17:48 - DEBUG CoordinatedClient: 'test client failed'
10-14 10:17:48.499  5629  5675 I jxcore-log: 
,10-14 10:17:48.510  5629  5675 I jxcore-log: 2016-10-14 14:17:48 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-14 10:17:48.510  5629  5675 I jxcore-log: 
,10-14 10:17:48.515  5629  5675 I jxcore-log: 2016-10-14 14:17:48 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-14 10:17:48.515  5629  5675 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-14 10:17:48.515  5629  5675 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-14 10:17:48.515  5629  5675 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-14 10:17:48.515  5629  5675 I jxcore-log:     at $9@timers.js:120:1
10-14 10:17:48.515  5629  5675 I jxcore-log: ''
10-14 10:17:48.515  5629  5675 I jxcore-log: 
,10-14 10:17:48.516  5629  5675 I jxcore-log: 2016-10-14 14:17:48 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-14 10:17:48.516  5629  5675 I jxcore-log: 
,10-14 10:17:48.590   929  2948 W InputDispatcher: channel '540f38f com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-14 10:17:48.590   929  2948 E InputDispatcher: channel '540f38f com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-14 10:17:48.605   929  3847 D GraphicsStats: Buffer count: 2
10-14 10:17:48.605   929  2972 D WifiService: Client connection lost with reason: 4
10-14 10:17:48.606   929  3571 I WindowState: WIN DEATH: Window{540f38f u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-14 10:17:48.606   929  3571 W InputDispatcher: Attempted to unregister already unregistered input channel '540f38f com.test.thalitest/com.test.thalitest.MainActivity (server)'
,10-14 10:17:48.613   529   529 I Zygote  : Process 5629 exited cleanly (139)
,10-14 10:17:48.617   929  3847 I ActivityManager: Process com.test.thalitest (pid 5629) has died
,10-14 10:17:48.638   929  3847 I ActivityManager: Start proc 5980:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-14 10:17:48.961   929  3829 I WindowManager: Screenshot max retries 4 of Token{7855189 ActivityRecord{fea9490 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{7e928e6 u0 Starting com.test.thalitest} drawState=4
,10-14 10:17:49.032  5978  5978 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-14 10:17:49.043  5980  5980 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-14 10:17:49.050  5978  5978 D AndroidRuntime: CheckJNI is OFF
,10-14 10:17:49.061  5980  5980 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-14 10:17:49.066  5980  5980 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5964-5966)
,10-14 10:17:49.066  5980  5980 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-14 10:17:49.075  5980  5980 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6396a4}
,10-14 10:17:49.075  5980  5980 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-14 10:17:49.075  5980  5980 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
10-14 10:17:49.076  5978  5978 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-14 10:17:49.078  5980  5980 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-14 10:17:49.079  5980  5980 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-14 10:17:49.090  5980  5980 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-14 10:17:49.098  5980  5980 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-14 10:17:49.098  5980  5980 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 10:17:49.098  5980  5980 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-14 10:17:49.098  5980  5980 I Adreno  : Build Date                       : 12/06/15
10-14 10:17:49.098  5980  5980 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-14 10:17:49.098  5980  5980 I Adreno  : Local Branch                     : mybranch17112971
10-14 10:17:49.098  5980  5980 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-14 10:17:49.098  5980  5980 I Adreno  : Remote Branch                    : NONE
10-14 10:17:49.098  5980  5980 I Adreno  : Reconstruct Branch               : NOTHING
,10-14 10:17:49.099  5978  5978 I Radio-JNI: register_android_hardware_Radio DONE
,10-14 10:17:49.114  5978  5978 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-14 10:17:49.121   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-14 10:17:49.122   929   942 I ActivityManager: Killing 5980:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-14 10:17:49.175   929   942 I ActivityManager: Start proc 6007:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-14 10:17:49.175   929   942 I ActivityManager:   Force finishing activity ActivityRecord{fea9490 u0 com.test.thalitest/.MainActivity t2}
,10-14 10:17:49.195   929   947 W WindowManager: Failed looking up window
10-14 10:17:49.195   929   947 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@635eb41 does not exist
10-14 10:17:49.195   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-14 10:17:49.195   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-14 10:17:49.195   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-14 10:17:49.195   929   947 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-14 10:17:49.195   929   947 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-14 10:17:49.195   929   947 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-14 10:17:49.195   929   947 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-14 10:17:49.195   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.195   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.195   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 10:17:49.195   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-14 10:17:49.298   929  3153 I ActivityManager: Killing 5495:com.android.defcontainer/u0a7 (adj 15): empty #17
10-14 10:17:49.296   929   952 I art     : Starting a blocking GC Explicit
,10-14 10:17:49.327   929   939 W ActivityManager: Spurious death for ProcessRecord{134fa7d 0:com.test.thalitest/u0a77}, curProc for 5980: null
,10-14 10:17:49.351  6007  6007 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,10-14 10:17:49.351  6007  6007 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
10-14 10:17:49.351  6007  6007 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
10-14 10:17:49.351  6007  6007 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,10-14 10:17:49.370  6007  6007 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
10-14 10:17:49.371  6007  6007 E AndroidRuntime: FATAL EXCEPTION: main
10-14 10:17:49.371  6007  6007 E AndroidRuntime: Process: com.test.thalitest, PID: 6007
10-14 10:17:49.371  6007  6007 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:578)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4685)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:424)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:570)
10-14 10:17:49.371  6007  6007 E AndroidRuntime: 	... 9 more
,10-14 10:17:49.376  6007  6007 I Process : Sending signal. PID: 6007 SIG: 9
,10-14 10:17:49.398   929   952 I art     : Explicit concurrent mark sweep GC freed 77684(5MB) AllocSpace objects, 35(1380KB) LOS objects, 33% free, 29MB/43MB, paused 2.246ms total 99.648ms
,10-14 10:17:49.404   929  3835 I ActivityManager: Process com.test.thalitest (pid 6007) has died
,10-14 10:17:49.415   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-14 10:17:49.418  5978  5978 I art     : System.exit called, status: 0
,10-14 10:17:49.418  5978  5978 I AndroidRuntime: VM exiting with result code 0.
,10-14 10:17:49.429   929   952 I ActivityManager: Start proc 6021:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-14 10:17:49.429   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-14 10:17:49.442  5880  5880 D BluetoothMapAppObserver: onReceive
,10-14 10:17:49.442  5880  5880 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-14 10:17:49.443  4077  4187 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-14 10:17:49.446  3681  3681 I Keyboard.Facilitator: resetDictionaries() : en_US
10-14 10:17:49.453   929  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-14 10:17:49.469  3681  6033 I Keyboard.Facilitator.DecoderInitializer: run()
,10-14 10:17:49.471  3390  6034 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-14 10:17:49.488  3822  3822 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-14 10:17:49.495  3681  6033 I Decoder : createOrResetDecoder
,10-14 10:17:49.504  3556  3556 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-14 10:17:49.504  3556  3556 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-14 10:17:49.508   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-14 10:17:49.503    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:17:49.506    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:17:49.517  3844  3971 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-14 10:17:49.516    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 10:17:49.530   929  3571 I ActivityManager: Start proc 6041:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
10-14 10:17:49.531  3844  3971 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-14 10:17:49.531  3844  3971 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3844
10-14 10:17:49.531  3844  3971 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.531  3844  3971 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 10:17:49.534   929  3829 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 10:17:49.539   929  6049 E DropBoxManagerService: Can't write: system_app_crash
10-14 10:17:49.539   929  6049 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 10:17:49.539   929  6049 E DropBoxManagerService: 	... 5 more
,10-14 10:17:49.539  3844  3971 I Process : Sending signal. PID: 3844 SIG: 9
,10-14 10:17:49.560  3390  3413 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj7A8D559E8) - 
,10-14 10:17:49.566  3556  3556 I ConfigService: onCreate
,10-14 10:17:49.568  3556  6055 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-14 10:17:49.568  3556  6055 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-14 10:17:49.569  3556  6055 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,10-14 10:17:49.571  3556  6055 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-14 10:17:49.582  3751  6054 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-14 10:17:49.582  3751  6054 D AccountUtils: Clearing selected account for com.test.thalitest
,10-14 10:17:49.603  3681  6033 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-14 10:17:49.632   929  2948 W InputDispatcher: channel '9480852 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-14 10:17:49.632   929  2948 E InputDispatcher: channel '9480852 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-14 10:17:49.633   929   939 D GraphicsStats: Buffer count: 1
10-14 10:17:49.633  3390  3413 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-14 10:17:49.633  3390  3413 E AndroidRuntime: Process: android.process.acore, PID: 3390
10-14 10:17:49.633  3390  3413 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.633  3390  3413 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 10:17:49.633   929  3571 I WindowState: WIN DEATH: Window{9480852 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-14 10:17:49.634   929  3571 W InputDispatcher: Attempted to unregister already unregistered input channel '9480852 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-14 10:17:49.644   929  3155 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3844) has died
,10-14 10:17:49.644   929  3155 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-14 10:17:49.646   929  3155 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 10:17:49.662   929   942 I ActivityManager: Start proc 6060:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 10:17:49.664  3390  3413 I Process : Sending signal. PID: 3390 SIG: 9
,10-14 10:17:49.702  6060  6060 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:17:49.702  6060  6060 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 10:17:49.703  6060  6060 D AndroidRuntime: Shutting down VM
,10-14 10:17:49.709  6060  6060 E AndroidRuntime: FATAL EXCEPTION: main
10-14 10:17:49.709  6060  6060 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6060
10-14 10:17:49.709  6060  6060 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 10:17:49.709  6060  6060 E AndroidRuntime: 	... 10 more
10-14 10:17:49.712   929  3835 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-14 10:17:49.713  6060  6060 I Process : Sending signal. PID: 6060 SIG: 9
10-14 10:17:49.735   929   940 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6060) has died
10-14 10:17:49.736   929   940 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 10:17:49.750   929   942 I ActivityManager: Start proc 6075:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 10:17:49.801  6075  6075 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:17:49.801  6075  6075 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:17:49.801  6075  6075 D AndroidRuntime: Shutting down VM
,10-14 10:17:49.811  6075  6075 E AndroidRuntime: FATAL EXCEPTION: main
10-14 10:17:49.811  6075  6075 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6075
10-14 10:17:49.811  6075  6075 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 10:17:49.811  6075  6075 E AndroidRuntime: 	... 10 more
10-14 10:17:49.814   929  3570 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-14 10:17:49.816  6075  6075 I Process : Sending signal. PID: 6075 SIG: 9
10-14 10:17:49.827   929   940 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6075) has died
10-14 10:17:49.829   929   940 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 10:17:49.844   929   942 I ActivityManager: Start proc 6088:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 10:17:49.895  6088  6088 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 10:17:49.895  6088  6088 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 10:17:49.895  6088  6088 D AndroidRuntime: Shutting down VM
,10-14 10:17:49.903   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
