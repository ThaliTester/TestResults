#### Test 869203704658a9f_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-27 10:29:49.785   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-27 10:29:49.785   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 10:29:50.261  5635  5635 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-27 10:29:50.266  5635  5635 D AndroidRuntime: CheckJNI is OFF
09-27 10:29:50.289  5635  5635 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-27 10:29:50.318  5635  5635 I Radio-JNI: register_android_hardware_Radio DONE
09-27 10:29:50.333  5635  5635 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-27 10:29:50.338   929  3719 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-27 10:29:50.389   929  3719 I ActivityManager: Start proc 5644:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-27 10:29:50.392  5635  5635 D AndroidRuntime: Shutting down VM
,09-27 10:29:50.719   929  3597 I WindowManager: Screenshot max retries 4 of Token{3878bad ActivityRecord{42e90c4 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{c6d345c u0 Starting com.test.thalitest} drawState=2
,09-27 10:29:50.785  5644  5644 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-27 10:29:50.821  5644  5644 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-27 10:29:50.849  5644  5644 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 9453-9473)
09-27 10:29:50.850  5644  5644 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-27 10:29:50.869  5644  5644 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e50ee2d}
,09-27 10:29:50.870  5644  5644 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-27 10:29:50.870  5644  5644 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-27 10:29:50.875  5644  5644 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-27 10:29:50.876  5644  5644 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-27 10:29:50.912  5644  5644 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-27 10:29:50.926  5644  5644 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-27 10:29:50.926  5644  5644 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-27 10:29:50.926  5644  5644 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-27 10:29:50.926  5644  5644 I Adreno  : Build Date                       : 12/06/15
09-27 10:29:50.926  5644  5644 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-27 10:29:50.926  5644  5644 I Adreno  : Local Branch                     : mybranch17112971
09-27 10:29:50.926  5644  5644 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-27 10:29:50.926  5644  5644 I Adreno  : Remote Branch                    : NONE
09-27 10:29:50.926  5644  5644 I Adreno  : Reconstruct Branch               : NOTHING
,09-27 10:29:50.985   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b5ede63:true
,09-27 10:29:51.020   738   738 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13197]" dev="sockfs" ino=13197 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 10:29:51.023   738   738 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[13197]" dev="sockfs" ino=13197 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 10:29:51.037  5644  5644 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-27 10:29:51.047  5644  5644 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-27 10:29:51.137  5644  5681 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-27 10:29:51.133   738   738 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32942]" dev="sockfs" ino=32942 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-27 10:29:51.133   738   738 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32942]" dev="sockfs" ino=32942 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-27 10:29:51.137   940   940 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[13208]" dev="sockfs" ino=13208 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-27 10:29:51.140   940   940 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[13208]" dev="sockfs" ino=13208 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-27 10:29:51.150  5644  5668 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-27 10:29:51.178  5644  5681 I OpenGLRenderer: Initialized EGL, version 1.4
,09-27 10:29:51.263   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +539ms (total +901ms)
,09-27 10:29:51.299  5644  5644 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5644
,09-27 10:29:51.394  5644  5644 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-27 10:29:51.608  5644  5684 D jxcore_app_log: JniHelper::setJavaVM(0xf523c000), pthread_self() = -584578768
,09-27 10:29:51.616  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-27 10:29:51.616  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-27 10:29:51.616  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-27 10:29:51.616  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-27 10:29:51.616  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-27 10:29:51.616  5644  5684 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7875f7a added. We now have 1 listener(s)
,09-27 10:29:51.619  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-27 10:29:51.620  5644  5684 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 10:29:51.620  5644  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 10:29:51.620  5644  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-27 10:29:51.623  5644  5684 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a4121 added. We now have 1 listener(s)
09-27 10:29:51.623  5644  5684 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:29:51.634   929  2977 D WifiService: New client listening to asynchronous messages
,09-27 10:29:51.635  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 10:29:51.636  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-27 10:29:51.636  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-27 10:29:51.636  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-27 10:29:51.636  5644  5684 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-27 10:29:51.640  5644  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:29:51.640  5644  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-27 10:29:51.649  5644  5684 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:29:51.649  5644  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:29:51.649  5644  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-27 10:29:51.649  5644  5684 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:29:51.650  5644  5684 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 10:29:51.655  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:29:51.659  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:29:51.674  5644  5644 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-27 10:29:52.292  5644  5653 I art     : Background sticky concurrent mark sweep GC freed 76283(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.488ms total 206.290ms
,09-27 10:29:52.395  5644  5690 W jxcore-log: Initializing JXcore engine
,09-27 10:29:52.395  5644  5690 W jxcore-log: JXcore engine is ready
,09-27 10:29:52.423  5690  5690 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11872 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-27 10:29:52.423  5690  5690 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14396]" dev="sockfs" ino=14396 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-27 10:29:52.423  5690  5690 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-27 10:29:52.423  5690  5690 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32918]" dev="sockfs" ino=32918 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-27 10:29:52.434  5644  5690 W jxcore-log: Starting JXcore engine
,09-27 10:29:52.485  5644  5690 W jxcore-log: Platform android
09-27 10:29:52.485  5644  5690 W jxcore-log: 
,09-27 10:29:52.485  5644  5690 W jxcore-log: Process ARCH arm
09-27 10:29:52.485  5644  5690 W jxcore-log: 
,09-27 10:29:52.585  5644  5690 I jxcore-log: JXcore Cordova bridge is ready!
09-27 10:29:52.585  5644  5690 I jxcore-log: 
,09-27 10:29:52.585  5644  5690 W jxcore-log: JXcore engine is started
,09-27 10:29:52.600  5644  5684 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-27 10:29:52.607  5644  5644 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-27 10:29:52.622   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:29:59.787   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:00.257   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 10:30:00.788   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:01.789   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:02.235  5644  5690 I jxcore-log: 2016-09-27 14:30:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native',
09-27 10:30:02.235  5644  5690 I jxcore-log: 
,09-27 10:30:02.237  5644  5690 I jxcore-log: 2016-09-27 14:30:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-27 10:30:02.237  5644  5690 I jxcore-log: 
,09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:02.242  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:30:02.244  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:30:02.245  5644  5690 I jxcore-log: 2016-09-27 14:30:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-27 10:30:02.245  5644  5690 I jxcore-log: 
,09-27 10:30:02.247  5644  5690 I jxcore-log: 2016-09-27 14:30:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-27 10:30:02.247  5644  5690 I jxcore-log: 
,09-27 10:30:02.499  5644  5690 I jxcore-log: 2016-09-27 14:30:02 - DEBUG UnitTest_app: 'Running unit tests'
09-27 10:30:02.499  5644  5690 I jxcore-log: 
,09-27 10:30:02.499  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 10:30:02.499  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fedc7e5 added. We now have 2 listener(s)
09-27 10:30:02.500  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 10:30:02.500  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 10:30:02.500  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 10:30:02.500  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:30:02.501  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4412ba added. We now have 2 listener(s)
09-27 10:30:02.501  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 10:30:02.501  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 10:30:02.503  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:02.506  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:02.507  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:30:02.507  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:30:02.508  5644  5690 D executeNativeTests: Running unit tests
,09-27 10:30:02.513  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:02.519  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:02.544  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 10:30:02.544  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 added. We now have 3 listener(s)
,09-27 10:30:02.544  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 10:30:02.545  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 10:30:02.545  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 10:30:02.545  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:30:02.545  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 added. We now have 3 listener(s)
09-27 10:30:02.545  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:30:02.545  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 10:30:02.547  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:02.549  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:30:02.550  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:30:02.550  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 10:30:02.552  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-27 10:30:02.552  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 10:30:02.552  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-27 10:30:02.552  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 10:30:02.552  5644  5690 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-27 10:30:02.553  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 10:30:02.553  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 10:30:02.553  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 10:30:02.553  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-27 10:30:02.553  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 10:30:02.553  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:02.553  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:02.553  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:02.554  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:02.554  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.554  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:02.554  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 10:30:02.554  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 removed from the list
09-27 10:30:02.554  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:02.554  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 removed from the list
09-27 10:30:02.555  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:02.560  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:02.561  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:02.561  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:02.561  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.562  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:02.562  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:02.562  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:02.562  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:02.562  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:02.563  5644  5690 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-27 10:30:02.563  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:02.563  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:02.563  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:02.563  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:02.564  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.564  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,2 listener(s) left
09-27 10:30:02.564  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:02.564  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:02.564  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:02.564  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:02.564  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.564  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:02.564  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.564  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:02.564  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:02.564  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:02.564  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:02.564  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 10:30:02.567  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 10:30:02.568  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:02.568  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:02.568  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:02.568  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:02.568  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.568  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:02.568  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:02.568  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:02.568  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:02.568  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:02.568  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.568  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:02.568  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:02.568  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:02.568  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:02.568  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:02.568  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:02.569  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:02.569  5644  5690 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-27 10:30:02.570  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:02.572  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:02.573  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:02.573  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:30:02.573  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 10:30:02.573  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 10:30:02.573  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 10:30:02.573  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:02.573  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:02.575  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:02.576  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:02.577  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:30:02.577  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 10:30:02.579  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 10:30:02.580  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:30:02.580  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 10:30:02.581  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-27 10:30:02.582  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-27 10:30:02.582  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 10:30:02.582  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 10:30:02.582  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 10:30:02.583  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:02.585  4597  4613 D BtGatt.GattService: registerClient() - UUID=34349f9f-3063-415d-9029-5f180d5ac8d7
09-27 10:30:02.587  4597  4675 D BtGatt.GattService: onClientRegistered() - UUID=34349f9f-3063-415d-9029-5f180d5ac8d7, clientIf=5
09-27 10:30:02.588  5644  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 10:30:02.589  4597  4823 D BtGatt.GattService: start scan with filters
09-27 10:30:02.593  4597  4678 D BtGatt.ScanManager: handling starting scan
09-27 10:30:02.594  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 10:30:02.594  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 10:30:02.594  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 10:30:02.594  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-27 10:30:02.594  4597  4678 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:30:02.596  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:30:02.596  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 10:30:02.596  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:30:02.596  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 10:30:02.597  5644  5690 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 10:30:02.601  4597  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 10:30:02.602  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:02.602  4597  4678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-27 10:30:02.609  4597  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 10:30:02.609  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:02.609  4597  4678 D BtGatt.ScanManager: Starting BLE batch scan
09-27 10:30:02.610  4597  4678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-27 10:30:02.621  4597  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 10:30:02.621  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:02.628  4597  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 10:30:02.628  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:30:02.791   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:03.098  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 10:30:03.098  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 10:30:03.099  5644  5644 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 10:30:03.792   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:04.793   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 10:30:06.315   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 10:30:06.324   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-27 10:30:07.601  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:30:07.602  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:07.602  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 10:30:07.602  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:07.602  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 10:30:07.602  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 10:30:07.602  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 10:30:07.602  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 10:30:07.603  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-27 10:30:07.603  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 10:30:07.603  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 10:30:07.604  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:07.605  4597  4613 D BtGatt.GattService: stopScan() - queue size =1
09-27 10:30:07.606  4597  4823 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 10:30:07.607  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:07.607  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 10:30:07.607  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-27 10:30:07.607  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-27 10:30:07.607  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 10:30:07.608  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:30:07.609  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:07.609  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 10:30:07.609  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:07.610  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 10:30:07.611  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:07.611  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:07.612  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:07.612  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:07.612  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:07.612  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:07.612  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:07.612  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:07.613  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 10:30:07.613  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:07.613  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:07.616  4597  4597 D BtGatt.ScanManager: awakened up at time 236239
09-27 10:30:07.623  4597  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 10:30:07.623  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:07.623  4597  4678 D BtGatt.ScanManager: stopping BLe Batch
09-27 10:30:07.624  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 10:30:07.624  5644  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:30:07.633  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 10:30:07.635  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 10:30:07.635  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 10:30:07.635  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 10:30:07.636  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:07.637  4597  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 10:30:07.637  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:07.638  4597  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 10:30:07.640  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 10:30:07.640  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:07.641  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:07.645  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 10:30:07.645  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:07.646  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:07.650  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 10:30:07.663  4597  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-27 10:30:07.664  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:07.664  4597  4675 D BtGatt.GattService: current time is 236288181005
09-27 10:30:07.665  4597  4675 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -70, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -76, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -72, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 10:30:07.666  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 10:30:07.667  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-27 10:30:07.668  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-27 10:30:07.668  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 10:30:07.668  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-27 10:30:07.669  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-27 10:30:08.151  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 10:30:09.349   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-27 10:30:09.357   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-27 10:30:09.794   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:10.795   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:11.797   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:12.614  5644  5690 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-27 10:30:12.616  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:12.626  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:30:12.631  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:30:12.631  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:30:12.632  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 10:30:12.632  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-27 10:30:12.632  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 10:30:12.632  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:12.632  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:12.638  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:12.639  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 10:30:12.641  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:12.643  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 10:30:12.643  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-27 10:30:12.643  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 10:30:12.644  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:12.646  4597  4613 D BtGatt.GattService: registerClient() - UUID=9945d5d3-c1d2-45b2-a99d-ae8fccff9319
09-27 10:30:12.647  4597  4675 D BtGatt.GattService: onClientRegistered() - UUID=9945d5d3-c1d2-45b2-a99d-ae8fccff9319, clientIf=5
,09-27 10:30:12.647  5644  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 10:30:12.648  4597  4844 D BtGatt.GattService: start scan with filters
,09-27 10:30:12.651  4597  4678 D BtGatt.ScanManager: handling starting scan
,09-27 10:30:12.651  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 10:30:12.651  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 10:30:12.652  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 10:30:12.652  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 10:30:12.655  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-27 10:30:12.655  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 10:30:12.655  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:30:12.657  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 10:30:12.658  4597  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 10:30:12.658  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:12.659  4597  4678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-27 10:30:12.660  5644  5690 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 10:30:12.664  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:30:12.664  5644  5690 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-27 10:30:12.664  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:12.664  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 10:30:12.664  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:12.664  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 10:30:12.664  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 10:30:12.664  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 10:30:12.664  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 10:30:12.664  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 10:30:12.664  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 10:30:12.664  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 10:30:12.665  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:12.666  4597  4613 D BtGatt.GattService: stopScan() - queue size =1
09-27 10:30:12.666  4597  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-27 10:30:12.666  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:12.666  4597  4678 D BtGatt.ScanManager: Starting BLE batch scan
09-27 10:30:12.666  4597  4678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 10:30:12.667  4597  4844 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 10:30:12.667  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:12.667  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 10:30:12.667  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-27 10:30:12.668  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 10:30:12.668  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-27 10:30:12.669  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:30:12.669  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:12.669  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 10:30:12.669  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:12.670  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:12.671  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:12.671  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:12.671  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:12.671  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:12.671  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:12.671  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:12.671  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:12.671  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:30:12.672  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:12.673  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:12.673  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:12.676  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:30:12.676  5644  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:30:12.682  4597  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 10:30:12.682  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:30:12.684  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 10:30:12.685  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:30:12.685  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 10:30:12.685  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:12.686  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:12.689  4597  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 10:30:12.689  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:12.690  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 10:30:12.690  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:12.690  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:12.694  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:30:12.694  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 10:30:12.694  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:12.697  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:30:12.698  4597  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 10:30:12.698  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:12.698  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:12.698  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:12.698  4597  4678 D BtGatt.ScanManager: stopping BLe Batch
,09-27 10:30:12.699  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:12.699  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:12.699  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:12.699  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:30:12.700  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:12.700  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:12.700  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:12.700  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:12.700  5644  5690 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-27 10:30:12.703  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:30:12.704  4597  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 10:30:12.704  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:12.704  4597  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:12.708  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:30:12.709  4597  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-27 10:30:12.710  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:30:12.710  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:30:12.711  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:30:12.711  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 10:30:12.711  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 10:30:12.711  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 10:30:12.711  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:12.711  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 10:30:12.713  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:12.715  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 10:30:12.717  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:12.719  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 10:30:12.719  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 10:30:12.719  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-27 10:30:12.720  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:12.722  4597  4844 D BtGatt.GattService: registerClient() - UUID=98522e3a-fe3e-451d-a1fd-9f3af22524e6
09-27 10:30:12.722  4597  4675 D BtGatt.GattService: onClientRegistered() - UUID=98522e3a-fe3e-451d-a1fd-9f3af22524e6, clientIf=5
,09-27 10:30:12.723  5644  5654 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 10:30:12.723  4597  4614 D BtGatt.GattService: start scan with filters
,09-27 10:30:12.725  4597  4678 D BtGatt.ScanManager: handling starting scan
,09-27 10:30:12.726  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 10:30:12.726  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 10:30:12.726  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 10:30:12.726  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 10:30:12.728  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:30:12.729  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 10:30:12.729  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:30:12.730  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 10:30:12.731  4597  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 10:30:12.731  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:12.731  4597  4678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 10:30:12.732  5644  5690 I io.jxcore.node.ConnectionHelper: start: OK
,09-27 10:30:12.737  4597  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 10:30:12.737  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:12.738  4597  4678 D BtGatt.ScanManager: Starting BLE batch scan
09-27 10:30:12.738  4597  4678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 10:30:12.747  4597  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 10:30:12.747  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:30:12.753  4597  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-27 10:30:12.753  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:30:12.798   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:13.229  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 10:30:13.230  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 10:30:13.230  5644  5644 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 10:30:13.799   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:14.799   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 10:30:17.734  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:30:17.734  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-27 10:30:17.734  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 10:30:17.735  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:17.735  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 10:30:17.735  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 10:30:17.735  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 10:30:17.735  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-27 10:30:17.735  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 10:30:17.736  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 10:30:17.736  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-27 10:30:17.738  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:17.739  4597  4614 D BtGatt.GattService: stopScan() - queue size =1
09-27 10:30:17.743  4597  4823 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 10:30:17.743  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:17.744  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 10:30:17.744  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-27 10:30:17.745  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 10:30:17.745  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 10:30:17.750  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:30:17.750  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:17.750  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-27 10:30:17.750  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:17.752  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:17.752  4597  4597 D BtGatt.ScanManager: awakened up at time 246376
09-27 10:30:17.755  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:30:17.755  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:30:17.755  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 10:30:17.758  4597  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 10:30:17.758  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:30:17.758  4597  4678 D BtGatt.ScanManager: stopping BLe Batch
09-27 10:30:17.761  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:30:17.761  5644  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:30:17.767  4597  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 10:30:17.767  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:17.767  4597  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 10:30:17.768  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 10:30:17.770  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:30:17.770  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 10:30:17.771  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:17.772  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 10:30:17.775  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 10:30:17.775  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:17.775  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:17.778  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:30:17.778  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:17.779  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 10:30:17.783  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 10:30:17.789  4597  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-27 10:30:17.789  4597  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:30:17.789  4597  4675 D BtGatt.GattService: current time is 246413285166
09-27 10:30:17.789  4597  4675 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -70, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -76, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -76, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -72, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -75, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 10:30:17.790  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-27 10:30:17.790  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-27 10:30:17.790  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 10:30:17.790  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 10:30:17.791  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-27 10:30:17.791  4597  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-27 10:30:18.284  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 10:30:18.284  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:18.284  5644  5644 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 10:30:18.436   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 10:30:21.471   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-27 10:30:22.756  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:30:22.757  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.757  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.757  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.757  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.757  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:22.758  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.758  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:22.758  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.758  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.758  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:22.760  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:22.760  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.763  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.763  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.763  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:22.766  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:22.766  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:22.766  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.766  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.767  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.769  5644  5690 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-27 10:30:22.771  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.772  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.772  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-27 10:30:22.772  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.773  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:22.773  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.773  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.773  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.774  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:22.774  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.774  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.775  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.775  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:22.779  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 10:30:22.779  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.779  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:22.781  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:30:22.781  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:22.781  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.781  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.782  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:22.784  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-27 10:30:22.785  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.785  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.785  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.785  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 10:30:22.785  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.785  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.785  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
,09-27 10:30:22.785  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:22.785  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:22.786  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.786  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.786  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:22.787  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.787  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.790  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.790  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.790  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:22.791  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:22.791  5644  5690 D BluetoothLeScanner: could not find callback wrapper
,09-27 10:30:22.791  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.791  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.792  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.793  5644  5690 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-27 10:30:22.793  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.793  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.794  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.794  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 10:30:22.794  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.794  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.794  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.794  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:22.794  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.794  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.794  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.794  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:22.795  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.795  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.797  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.797  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.797  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:22.798  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:22.798  5644  5690 D BluetoothLeScanner: could not find callback wrapper
,09-27 10:30:22.798  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.798  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.798  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.800  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-27 10:30:22.800  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.800  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 10:30:22.800  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.800  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.800  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.801  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.801  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.801  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.801  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.801  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.801  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.801  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.801  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:22.801  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.803  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.803  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.803  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:22.804  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:22.804  5644  5690 D BluetoothLeScanner: could not find callback wrapper
,09-27 10:30:22.804  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.804  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.805  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.805  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 10:30:22.806  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 10:30:22.806  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 10:30:22.806  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 10:30:22.806  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 10:30:22.806  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 10:30:22.806  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-27 10:30:22.806  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 10:30:22.807  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-27 10:30:22.807  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.807  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.807  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.807  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 10:30:22.807  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.807  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.807  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.807  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.807  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.808  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 10:30:22.808  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.808  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.808  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.808  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:22.810  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.810  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.810  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:22.812  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:30:22.812  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:22.812  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.812  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.812  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.813  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 10:30:22.813  5644  5690 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 10:30:22.814  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-27 10:30:22.818  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 10:30:22.818  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-27 10:30:22.818  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-27 10:30:22.818  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-27 10:30:22.818  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-27 10:30:22.818  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-27 10:30:22.818  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-27 10:30:22.819  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-27 10:30:22.820  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-27 10:30:22.821  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-27 10:30:22.821  5644  5690 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-27 10:30:22.821  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-27 10:30:22.821  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 10:30:22.821  5644  5690 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 10:30:22.821  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-27 10:30:22.821  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 10:30:22.822  5644  5690 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-27 10:30:22.822  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-27 10:30:22.826  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-27 10:30:22.827  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-27 10:30:22.827  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-27 10:30:22.828  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-27 10:30:22.828  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-27 10:30:22.828  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-27 10:30:22.828  5644  5690 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-27 10:30:22.828  5644  5690 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-27 10:30:22.829  5644  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-27 10:30:22.830  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.830  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.830  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.830  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.830  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.830  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.830  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-27 10:30:22.832  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.832  5644  5692 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 10:30:22.832  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.832  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.832  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.832  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.832  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.832  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.832  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.833  5644  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-27 10:30:22.833  5644  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
09-27 10:30:22.833  5644  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
09-27 10:30:22.834  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.834  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.834  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:22.830  4823  4823 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32967]" dev="sockfs" ino=32967 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 10:30:22.835  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:22.835  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:22.835  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.835  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.835  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.835  5644  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
09-27 10:30:22.836  5644  5690 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-27 10:30:22.830  4823  4823 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32967]" dev="sockfs" ino=32967 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 10:30:22.837  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.837  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.837  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.837  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.837  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.837  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.837  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.837  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.837  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.838  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.838  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.838  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.838  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.838  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.839  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.839  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.839  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:22.840  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:22.840  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:22.840  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.840  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.840  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.841  5644  5690 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-27 10:30:22.842  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:30:22.842  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:22.842  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.842  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.842  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.842  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.842  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.842  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.842  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.843  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.843  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.843  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.843  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:22.843  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.844  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.844  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 10:30:22.844  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:22.845  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:30:22.845  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:22.845  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.845  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.845  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:22.846  5644  5690 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-27 10:30:22.846  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-27 10:30:22.846  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 10:30:22.846  5644  5690 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-27 10:30:22.846  5644  5690 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 10:30:22.846  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-27 10:30:22.847  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 10:30:22.847  5644  5690 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-27 10:30:22.847  5644  5690 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-27 10:30:22.847  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-27 10:30:22.847  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-27 10:30:22.847  5644  5690 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-27 10:30:22.847  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:22.847  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 10:30:22.847  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:22.847  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.848  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.848  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.848  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.848  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.848  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.848  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.848  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.848  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.848  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:22.848  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.850  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:22.850  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:22.850  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:22.850  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:30:22.850  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:22.851  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:22.851  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:22.851  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.851  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:22.851  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.851  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:22.851  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:22.851  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:22.851  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:22.851  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:22.852  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:22.852  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:24.801   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:25.802   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:26.803   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:27.804   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:27.852  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:27.853  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:27.853  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:27.853  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.853  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.853  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
,09-27 10:30:27.853  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:27.854  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:27.854  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:27.854  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:27.854  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:27.854  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.855  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:27.855  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.855  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.855  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 10:30:27.855  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.855  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.855  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:27.856  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-27 10:30:27.858  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:27.859  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:27.859  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:27.860  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:27.860  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:27.861  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:27.861  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:27.861  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.865  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 10:30:27.865  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:27.867  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-27 10:30:27.869  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-27 10:30:27.869  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-27 10:30:27.870  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 10:30:27.870  5644  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 10:30:27.870  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-27 10:30:27.870  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 10:30:27.871  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-27 10:30:27.871  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 10:30:27.871  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 10:30:27.871  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.871  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 10:30:27.871  5644  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 10:30:27.871  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:27.871  5644  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-27 10:30:27.871  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.871  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 10:30:27.872  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 10:30:27.872  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 10:30:27.872  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 10:30:27.870  4613  4613 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30480]" dev="sockfs" ino=30480 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 10:30:27.870  4613  4613 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30480]" dev="sockfs" ino=30480 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 10:30:27.873  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:27.873  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:27.873  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:27.873  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:27.873  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 10:30:27.874  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.874  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.875  5644  5694 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-27 10:30:27.875  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:30:27.875  5644  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 10:30:27.875  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.875  5644  5694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 10:30:27.876  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:27.876  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:30:27.876  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:27.876  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:27.876  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:27.876  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:30:27.876  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:27.876  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.876  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:27.876  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:27.876  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.877  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:27.877  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:27.877  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.877  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:27.882  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:30:27.882  5644  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:30:27.889  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 10:30:27.890  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-27 10:30:27.890  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 10:30:27.891  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:27.891  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.894  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.895  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:27.896  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:27.896  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 10:30:27.897  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:27.898  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:27.898  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:27.898  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:27.898  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:27.898  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:30:27.898  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.898  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:30:27.898  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 10:30:27.900  5644  5690 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-27 10:30:27.900  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-27 10:30:27.900  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-27 10:30:27.901  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 10:30:27.901  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-27 10:30:27.901  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:27.901  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:27.901  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:27.901  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:27.901  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.901  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:27.901  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:27.902  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.902  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.902  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:27.902  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.902  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:30:27.905  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:30:27.905  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:30:27.906  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:27.910  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:30:27.910  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.910  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.910  5644  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-27 10:30:27.912  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:27.913  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:27.913  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:30:27.914  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:27.914  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:27.914  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:27.914  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.914  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:27.920  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:30:27.920  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:30:27.920  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:27.920  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:27.920  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:30:27.920  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.921  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:27.921  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.921  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.921  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 10:30:27.921  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.921  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.921  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.921  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:27.922  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:30:27.922  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:27.922  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:27.923  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:30:27.923  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:27.924  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:27.924  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.924  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.925  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:30:27.925  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-27 10:30:27.925  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:30:27.925  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:30:27.925  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.925  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.925  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f12d3f8 not in the list
09-27 10:30:27.925  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:27.926  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
09-27 10:30:27.926  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:27.926  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.926  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.926  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:27.926  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:27.927  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 10:30:27.927  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:30:27.927  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:30:27.929  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:30:27.929  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:30:27.929  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:30:27.929  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:27.929  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a00d1 not in the list
,09-27 10:30:27.931  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-27 10:30:27.931  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 10:30:27.931  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-27 10:30:27.931  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-27 10:30:27.931  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-27 10:30:27.932  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-27 10:30:27.934  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-27 10:30:27.934  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-27 10:30:27.935  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-27 10:30:27.935  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 10:30:27.935  5644  5690 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-27 10:30:27.935  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-27 10:30:27.935  5644  5690 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-27 10:30:27.935  5644  5690 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-27 10:30:27.936  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-27 10:30:27.936  5644  5690 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-27 10:30:27.937  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-27 10:30:27.937  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-27 10:30:27.937  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-27 10:30:27.937  5644  5690 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-27 10:30:27.939  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:30:27.939  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@168381f added. We now have 3 listener(s)
09-27 10:30:27.939  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:30:27.941  5644  5690 D BluetoothAdapter: enable(): BT is already enabled..!
,09-27 10:30:27.942   929  3158 D WifiService: setWifiEnabled: true pid=5644, uid=10077
09-27 10:30:27.942   929  3158 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 10:30:27.964  4597  4792 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-27 10:30:27.964  4597  4819 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-27 10:30:28.411  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 10:30:28.805   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:29.805   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 10:30:32.625   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:30:32.947  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-27 10:30:32.948  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@173876c added. We now have 4 listener(s)
09-27 10:30:32.948  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:30:32.962  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:32.962  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@173876c removed from the list
09-27 10:30:32.962  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 10:30:32.962  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:32.962  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:30:32.964  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:30:32.964  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afbc135 added. We now have 4 listener(s)
09-27 10:30:32.965  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:30:32.968  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:32.968  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afbc135 removed from the list
09-27 10:30:32.968  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 10:30:32.968  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:32.968  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:32.970  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:30:32.970  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60d99ca added. We now have 4 listener(s)
09-27 10:30:32.970  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:30:32.976   929  2936 D WifiService: setWifiEnabled: false pid=5644, uid=10077
,09-27 10:30:32.976   929  2936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 10:30:32.983   929  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-27 10:30:32.984   929  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-27 10:30:32.984   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 10:30:32.984   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 10:30:32.989  4597  4671 D BluetoothAdapterState: Current state: ON, message: 23
09-27 10:30:32.989  4597  4671 D BluetoothAdapterProperties: Setting state to 13
09-27 10:30:32.989  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:30:32.989  4597  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-27 10:30:32.991  4597  4671 D BluetoothAdapterProperties: onBluetoothDisable()
,09-27 10:30:32.992  4597  4671 I BluetoothAdapterState: Entering PendingCommandState
,09-27 10:30:33.000  4597  4597 D BluetoothMapService: onReceive
,09-27 10:30:33.002  4597  4597 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-27 10:30:33.002  4597  4597 D BluetoothMapService: STATE_TURNING_OFF
,09-27 10:30:33.003  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:33.003  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:33.002  4597  4597 D BluetoothMapService: MAP Service closeService in
09-27 10:30:33.004  4597  4597 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 10:30:33.004  4597  4597 D ObexServerSockets0: shutdown(block = true)
,09-27 10:30:33.005  4597  4597 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 10:30:33.005  4597  4597 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 10:30:33.005  4597  4846 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-27 10:30:33.005  4597  4847 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-27 10:30:33.006  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.006  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:33.006  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:30:33.006  4597  4819 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-27 10:30:33.008  4597  4597 I BtOppRfcommListener: stopping Accept Thread
09-27 10:30:33.009  4597  5319 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 10:30:33.009  4597  5319 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-27 10:30:33.011  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:33.012   929  5378 D DhcpClient: Clearing IP address
,09-27 10:30:33.012   509   920 D CommandListener: Clearing all IP addresses on wlan0
09-27 10:30:33.013  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:33.014   509   920 D CommandListener: Setting iface cfg
,09-27 10:30:33.016  3581  5434 V NativeCrypto: Read error: ssl=0x7f9c0cba00: I/O error during system call, Connection timed out
09-27 10:30:33.018  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:33.018  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:33.018  3581  5434 V NativeCrypto: SSL shutdown failed: ssl=0x7f9c0cba00: I/O error during system call, Broken pipe
09-27 10:30:33.019  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.019  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:33.024   929  3876 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-27 10:30:33.024  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.025   929  5376 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:33.025  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:33.026  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.026  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:33.027   929  5376 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-27 10:30:33.027   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-27 10:30:33.028   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-27 10:30:33.028   929   942 I ActivityManager: Start proc 5698:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-27 10:30:33.028  4597  4675 D BluetoothAdapterProperties: Scan Mode:20
,09-27 10:30:33.029  4597  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 10:30:33.029  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:33.030   929  5379 D DhcpClient: Receive thread stopped
09-27 10:30:33.030   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-27 10:30:33.036  4597  4597 D HeadsetService: Received stop request...Stopping profile...
,09-27 10:30:33.038   535   535 E Parcel  : Reading a NULL string not supported here.
,09-27 10:30:33.039  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:33.039  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:33.040   929   929 D RttService: SCAN_AVAILABLE : 1
09-27 10:30:33.041   929  3084 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-27 10:30:33.041  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.041  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:33.043   929   929 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:33.043  4597  4597 D A2dpService: Received stop request...Stopping profile...
09-27 10:30:33.043  3131  3142 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:33.043   929   929 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:33.043  4597  4827 D A2dpStateMachine: Exit Disconnected: -1
,09-27 10:30:33.043  3131  3131 D HeadsetProfile: Bluetooth service disconnected
09-27 10:30:33.043  3810  3832 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:33.044   929   929 D BluetoothHeadset: Proxy object disconnected
,09-27 10:30:33.044   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-27 10:30:33.045   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-27 10:30:33.045  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:33.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:30:33.045  4597  4597 D HidService: Received stop request...Stopping profile...
09-27 10:30:33.046  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.045   929   929 D BluetoothA2dp: Proxy object disconnected
09-27 10:30:33.047  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 10:30:33.047  4597  4597 D HidService: Stopping Bluetooth HidService
09-27 10:30:33.049  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:33.049  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:30:33.049  3131  3131 D BluetoothA2dp: Proxy object disconnected
09-27 10:30:33.050  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.050  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:33.050  4597  4597 D HealthService: Received stop request...Stopping profile...
09-27 10:30:33.050  3131  3131 D BluetoothInputDevice: Proxy object disconnected
09-27 10:30:33.050  3131  3131 D HidProfile: Bluetooth service disconnected
09-27 10:30:33.051  4597  4597 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:33.051  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.051  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.051  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:33.051   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 10:30:33.052   929  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-27 10:30:33.052  4597  4597 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 10:30:33.053  4597  4597 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 10:30:33.053  4597  4792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:33.053  4597  4792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:33.053  4597  4792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:33.053  4597  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 10:30:33.053  4597  4675 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-27 10:30:33.053  4597  4597 D PanService: Received stop request...Stopping profile...
09-27 10:30:33.054  3779  3913 W QCNEJ   : |CORE| network lost: 100
09-27 10:30:33.055  4597  4597 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:33.055  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.055  3779  3913 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-27 10:30:33.055  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.055  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:33.057  4597  4792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-27 10:30:33.058  4597  4792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:33.058  4597  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 10:30:33.058  4597  4597 D BluetoothMapService: Received stop request...Stopping profile...
09-27 10:30:33.058  4597  4597 D BluetoothMapService: stop()
09-27 10:30:33.058  4597  4792 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-27 10:30:33.058  4597  4792 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-27 10:30:33.058  4597  4792 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 10:30:33.058  4597  4792 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 10:30:33.058  4597  4597 D BluetoothMapAppObserver: deinitObservers()
09-27 10:30:33.058  4597  4597 D BluetoothMapAppObserver: removeReceiver()
,09-27 10:30:33.062  4597  4597 D SapService: Received stop request...Stopping profile...
,09-27 10:30:33.063  4597  4597 V SapService: stop()
09-27 10:30:33.063  4597  4597 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:33.063  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.063  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.063  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:33.064  4597  4597 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 10:30:33.064  4597  4597 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-27 10:30:33.064  4597  4597 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:33.064  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.064  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.064  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:33.064  4597  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 10:30:33.064  4597  4597 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 10:30:33.064  4597  4675 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 10:30:33.065  4597  4597 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 10:30:33.065  4597  4597 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:33.065  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.065  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.065  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:33.065  4597  4597 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 10:30:33.065  4597  4597 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-27 10:30:33.069  3131  3131 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-27 10:30:33.069  3131  3131 D PanProfile: Bluetooth service disconnected
09-27 10:30:33.070  4597  4597 D BluetoothMapService: MAP Service closeService in
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:33.070  3131  3131 D BluetoothMap: Proxy object disconnected
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.070  3131  3131 D MapProfile: Bluetooth service disconnected
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:33.070  4597  4597 D BluetoothMapService: cleanup()
09-27 10:30:33.070  4597  4597 D BluetoothMapService: MAP Service closeService in
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.070  4597  4597 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:33.071  4597  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 10:30:33.071  4597  4671 D BluetoothAdapterProperties: Setting state to 15
09-27 10:30:33.071  4597  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-27 10:30:33.072  4597  4671 I BluetoothAdapterState: Entering BleOnState
,09-27 10:30:33.073  3131  3148 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 10:30:33.074  3131  3981 D BluetoothMap: onBluetoothStateChange: up=false
09-27 10:30:33.075   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 10:30:33.075   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 10:30:33.075   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 10:30:33.075  3131  3918 D BluetoothPan: onBluetoothStateChange on: false
09-27 10:30:33.076  3131  3142 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 10:30:33.077  3810  3833 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 10:30:33.077  3131  3148 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 10:30:33.078   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 10:30:33.078  3131  3981 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 10:30:33.079  4597  4671 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 10:30:33.079  4597  4671 D BluetoothAdapterProperties: Setting state to 16
09-27 10:30:33.079  4597  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-27 10:30:33.080  4597  4671 D BluetoothAdapterProperties: onBleDisable
09-27 10:30:33.080  4597  4671 I BluetoothAdapterState: Entering PendingCommandState
09-27 10:30:33.081  4597  4672 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 10:30:33.081  4597  4675 D BluetoothAdapterProperties: Scan Mode:20
09-27 10:30:33.082  4597  4792 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-27 10:30:33.083  4597  4792 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-27 10:30:33.083  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:33.083  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:33.086  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:33.086  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 10:30:33.087  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:33.088  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:33.088  5698  5698 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-27 10:30:33.089  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:33.091   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-27 10:30:33.091  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:33.092  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:33.105  5698  5698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 10:30:33.111   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1d9a49:true
,09-27 10:30:33.112  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 10:30:33.113   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 10:30:33.114   509   920 D CommandListener: Clearing all IP addresses on wlan0
09-27 10:30:33.115   929  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-27 10:30:33.115   509   920 D TetherController: Setting IP forward enable = 0
,09-27 10:30:33.116   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 10:30:33.126   929  3407 I ActivityManager: Start proc 5720:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-27 10:30:33.127   929  2976 D DhcpClient: doQuit
,09-27 10:30:33.127   929  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 10:30:33.128   929  5378 D DhcpClient: onQuitting
09-27 10:30:33.130   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-27 10:30:33.131  3443  3443 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 10:30:33.131  5289  5289 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@781bde9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-27 10:30:33.133   929  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-27 10:30:33.135  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:33.135  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:33.136  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 10:30:33.136  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:33.138  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 10:30:33.138  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 10:30:33.138  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 10:30:33.138  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:33.138  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:33.138  5046  5070 E SarControlService: no key has been found,reset the power
09-27 10:30:33.139  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-27 10:30:33.139  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 10:30:33.139  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 10:30:33.139  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.139  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 10:30:33.139  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:33.139  5071  5071 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 10:30:33.141  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 10:30:33.141  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 10:30:33.141  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 10:30:33.141  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:33.142  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:33.142  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 10:30:33.142  5071  5071 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 10:30:33.142  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:33.143  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:33.144  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:33.144  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000ea03000000000000ffffffff]
,09-27 10:30:33.144  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 10:30:33.144  5071  5085 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-27 10:30:33.145  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:30:33.145  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:33.145  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 10:30:33.147  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:33.151  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000eb03000000000000ffffffff]
09-27 10:30:33.151  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-27 10:30:33.151  5071  5085 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-27 10:30:33.152  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:30:33.152  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-27 10:30:33.153  5698  5698 D LocalBluetoothProfileManager: Adding local MAP profile
,09-27 10:30:33.155  5698  5698 D BluetoothMap: Create BluetoothMap proxy object
,09-27 10:30:33.159  3443  3443 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-27 10:30:33.165  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-27 10:30:33.165  5698  5698 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-27 10:30:33.186  5698  5698 D DockEventReceiver: finishStartingService: stopping service
,09-27 10:30:33.189  5720  5720 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-27 10:30:33.189   509   920 E Netd    : netlink response contains error (No such file or directory)
,09-27 10:30:33.190   509   920 D TetherController: Setting IP forward enable = 0
09-27 10:30:33.191   929  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 10:30:33.192   929  3719 I ActivityManager: Killing 4986:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-27 10:30:33.197  3443  3443 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 10:30:33.217  3443  3443 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 10:30:33.287  4597  4675 I bt_hci  : shut_down
,09-27 10:30:33.291  4597  4679 D bt_hwcfg: hw_epilog_process
,09-27 10:30:33.291  4597  4679 I bt_vendor: low_power_mode_cb
,09-27 10:30:33.294  4597  4679 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-27 10:30:33.294  4597  4679 I bt_vendor: epilog_cb
09-27 10:30:33.294  4597  4679 I bt_hci  : epilog_finished_callback
,09-27 10:30:33.296  4597  4675 I bt_hci_h4: hal_close
,09-27 10:30:33.297  4597  4675 I bt_userial_vendor: device fd = 54 close
,09-27 10:30:33.319   929  2976 D wifi    : In wifi stop Hal
09-27 10:30:33.319   929  2976 D wifi    : halHandle = 0x7f8ab25f80, mVM = 0x7fa5f8d140, mCls = 0x100a02
09-27 10:30:33.319   929  3441 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 10:30:33.319   929  3441 D WifiHAL : Got a signal to exit!!!
,09-27 10:30:33.319   929  3441 I WifiHAL : Exit wifi_event_loop
09-27 10:30:33.320   929  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-27 10:30:33.320  5021  5021 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 10:30:33.320   929  2976 E WifiHAL : Event processing terminated
,09-27 10:30:33.320   929  2976 D wifi    : In wifi cleaned up handler
09-27 10:30:33.320   929  2976 I WifiHAL : Internal cleanup completed
,09-27 10:30:33.322  4067  4222 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 10:30:33.323  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:33.325  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:33.327  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:33.343   929  3441 D wifi    : set interface wlan0 flags (DOWN)
,09-27 10:30:33.344   929  2976 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 10:30:33.379  5720  5720 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-27 10:30:33.379  5720  5720 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 10:30:33.379  5720  5720 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 10:30:33.379  5720  5720 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 10:30:33.379  5720  5720 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.k.d(PG:583)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:170)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 10:30:33.379  5720  5720 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 10:30:33.379  5720  5720 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.io.File.exists(File.java:361)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.379  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 10:30:33.380  5720  5720 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-27 10:30:33.380  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-27 10:30:33.384  5698  5698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 10:30:33.390  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-27 10:30:33.391  5698  5698 D DockEventReceiver: finishStartingService: stopping service
09-27 10:30:33.393   929  2936 I ActivityManager: Killing 5454:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-27 10:30:33.427  4597  4672 D bt_stack_manager: event_shut_down_stack finished.
09-27 10:30:33.427  4597  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-27 10:30:33.428  4597  4671 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-27 10:30:33.430  4597  4597 D BtGatt.DebugUtils: handleDebugAction() action=null
09-27 10:30:33.430  4597  4597 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 10:30:33.430  4597  4597 D BtGatt.GattService: stop()
09-27 10:30:33.430  4597  4597 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 10:30:33.431  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 10:30:33.432  4597  4597 V BluetoothAdapterState: isTurningOff()=false
09-27 10:30:33.432  4597  4597 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:33.432  4597  4597 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:33.432  4597  4597 V BluetoothAdapterState: isBleTurningOff()=true
09-27 10:30:33.433  4597  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-27 10:30:33.433  4597  4671 D BluetoothAdapterProperties: Setting state to 10
09-27 10:30:33.433  4597  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 10:30:33.434   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-27 10:30:33.434  4597  4671 I BluetoothAdapterState: Entering OffState
09-27 10:30:33.440  4597  4597 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-27 10:30:33.440  4597  4597 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 10:30:33.440  4597  4597 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 10:30:33.441  4597  4672 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-27 10:30:33.444  3732  3732 D SystemUpdateService: onCreate
09-27 10:30:33.448  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-27 10:30:33.455  4597  4672 D bt_stack_manager: event_clean_up_stack finished.
,09-27 10:30:33.458  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-27 10:30:33.463  3732  5404 I iu.UploadsManager: num queued entries: 0
,09-27 10:30:33.463  3732  5404 I iu.UploadsManager: num updated entries: 0
09-27 10:30:33.464  3732  5404 I iu.SyncManager: NEXT; no task
,09-27 10:30:33.467  4597  4597 I art     : System.exit called, status: 0
,09-27 10:30:33.467  4597  4597 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 10:30:33.478  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 10:30:33.479  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 10:30:33.481  3732  5762 I SystemUpdateService: active receiver: enabled
,09-27 10:30:33.492   929   939 I ActivityManager: Start proc 5764:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-27 10:30:33.497   929   940 I ActivityManager: Process com.android.bluetooth (pid 4597) has died
,09-27 10:30:33.522  5764  5764 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-27 10:30:33.525  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 10:30:33.531  5764  5764 D SprintDMHelper: simOperator: 
,09-27 10:30:33.531  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 10:30:33.537  3732  5762 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 10:30:33.539  3732  5762 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 10:30:33.539  3732  5762 I SystemUpdateService: now status is 0 (complete)
09-27 10:30:33.539  3732  5762 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 10:30:33.539  3732  5762 I SystemUpdateService: file has been verified
,09-27 10:30:33.539  3732  5762 I SystemUpdateService: OTA package size = 21989297
,09-27 10:30:33.543   929  3407 I ActivityManager: Start proc 5776:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-27 10:30:33.547   929   946 D Tethering: InitialState.processMessage what=4
,09-27 10:30:33.551   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 10:30:33.553  3732  5762 I SystemUpdateService: showing system update notification
,09-27 10:30:33.641  3732  3732 D SystemUpdateService: onDestroy
,09-27 10:30:33.648  5021  5791 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-27 10:30:33.652   929  2936 I ActivityManager: Start proc 5792:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-27 10:30:33.655   929   939 I ActivityManager: Killing 5289:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-27 10:30:33.697   929   939 I ActivityManager: Killing 4685:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-27 10:30:33.753  5792  5792 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-27 10:30:33.762   929  3876 I ActivityManager: Killing 5507:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-27 10:30:33.853  5720  5749 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-27 10:30:33.862   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@730dc62:true
,09-27 10:30:38.010   929  3407 D WifiService: setWifiEnabled: true pid=5644, uid=10077
,09-27 10:30:38.010   929  3407 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 10:30:38.018   509   920 D SoftapController: Softap fwReload - Ok
,09-27 10:30:38.023   509   920 D CommandListener: Setting iface cfg
,09-27 10:30:38.024   509   920 D CommandListener: Trying to bring down wlan0
,09-27 10:30:38.025   509   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 10:30:38.031   929  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 10:30:38.599   929  2976 D wifi    : set interface wlan0 flags (UP)
,09-27 10:30:38.600   929  2976 I WifiHAL : Initializing wifi
09-27 10:30:38.600   929  2976 I WifiHAL : Creating socket
09-27 10:30:38.601   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-27 10:30:38.604   929  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-27 10:30:38.604   929  2976 D wifi    : Did set static halHandle = 0x7f8ab25f80
09-27 10:30:38.604   929  2976 D wifi    : halHandle = 0x7f8ab25f80, mVM = 0x7fa5f8d140, mCls = 0x101912
09-27 10:30:38.604   929  2976 D wifi    : array field set
09-27 10:30:38.604   929  2976 I WifiNative-HAL: interface[0] = wlan0
09-27 10:30:38.605   929  5811 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547787792256
09-27 10:30:38.605   929  5811 D wifi    : waitForHalEvents called, vm = 0x7fa5f8d140, obj = 0x101912, env = 0x7f8a8c7300
,09-27 10:30:38.664  5812  5812 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 10:30:38.683  5812  5812 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 10:30:38.706   929  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-27 10:30:38.708  5812  5812 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-27 10:30:38.708  5812  5812 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 10:30:38.715  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:38.718  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:38.721  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:38.730  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:38.731  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:38.731  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:38.731  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:38.732  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:38.732  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:38.732  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:38.732  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 10:30:38.733   929  2976 D WifiConfigStore: Loading config and enabling all networks 
,09-27 10:30:38.733  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:38.734  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:38.734  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:38.734  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 10:30:38.746   929  2976 D WifiConfigStore: loaded 0 passpoint configs
,09-27 10:30:38.746   929  2976 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 10:30:38.747   929  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-27 10:30:38.748   929  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-27 10:30:38.749   929  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 10:30:38.750   929  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 10:30:38.750   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 10:30:38.750   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 10:30:38.753   929  2976 D WifiNative-HAL: Setting external_sim to 1
,09-27 10:30:38.753  5021  5021 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 10:30:38.754   929  2976 D wifi    : setting dfs flag to true, 0x7f8aea69e0
,09-27 10:30:38.754   929  2976 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 10:30:38.754   929  2976 D wifi    : setting scan oui 0x7f8aea69e0
09-27 10:30:38.754   929  2976 D WifiHAL : Sending mac address OUI
09-27 10:30:38.758   929  2976 E native  : do suspend false
,09-27 10:30:38.766   929  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-27 10:30:38.766   929   929 D RttService: SCAN_AVAILABLE : 3
,09-27 10:30:38.766   929  3084 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-27 10:30:38.766   509   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 10:30:38.767   509   920 D CommandListener: Setting iface cfg
,09-27 10:30:38.774   929  2975 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-27 10:30:38.774   929  2975 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 10:30:38.782   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267405 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=11 mControllerEnergyUsed=41 }
,09-27 10:30:38.783   929  2975 D WifiNative-HAL: p2pGetDeviceAddress
,09-27 10:30:38.783   929  2975 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 10:30:41.950  5812  5812 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:30:41.957  5812  5812 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:30:41.962  5812  5812 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:30:41.966  5812  5812 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:30:42.026   929  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-27 10:30:42.027   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-27 10:30:42.027   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 10:30:42.039   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 10:30:42.073   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 10:30:42.075  5812  5812 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 10:30:42.561  5812  5812 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 10:30:42.641  5812  5812 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 10:30:42.642  5812  5812 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 10:30:42.657   929  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 10:30:42.658   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-27 10:30:42.658   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 10:30:42.672   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 10:30:42.682   509   920 D CommandListener: Setting iface cfg
,09-27 10:30:42.686   929  2976 D WifiStateMachine: Start Dhcp Watchdog 2
,09-27 10:30:42.694   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 10:30:42.695   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-27 10:30:42.695   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-27 10:30:42.697   929  5818 D DhcpClient: Receive thread started
,09-27 10:30:42.776   929  2976 E native  : do suspend false
,09-27 10:30:42.790   929  5817 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 10:30:42.807   929  5818 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-27 10:30:42.808   929  5817 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-27 10:30:42.810   929  5817 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 10:30:42.825   929  5818 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 10:30:42.827   929  5817 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 10:30:42.829   509   920 D CommandListener: Setting iface cfg
09-27 10:30:42.834   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 10:30:42.839   929  5817 D DhcpClient: Scheduling renewal in 86399s
,09-27 10:30:42.855   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-27 10:30:42.857   929  2976 D WifiConfigStore: No blacklist allowed without epno enabled
,09-27 10:30:42.858   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-27 10:30:42.859   929  2978 D ConnectivityService: Adding iface wlan0 to network 101
09-27 10:30:42.870   929  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 10:30:42.910   929  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 10:30:42.913   929  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-27 10:30:42.917   929  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-27 10:30:42.920   929  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-27 10:30:42.922   929  2978 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-27 10:30:42.928   929  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-27 10:30:42.933   929  2978 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-27 10:30:42.933   929  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-27 10:30:42.933   929  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-27 10:30:42.933   929  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 10:30:42.933   929  2978 D ConnectivityService:    accepting network in place of null
09-27 10:30:42.933   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 10:30:42.934   929  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 10:30:42.947   929  5816 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 10:30:42.955   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 10:30:42.977   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 10:30:42.981   929  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-27 10:30:42.981   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 10:30:42.981  3779  3913 W QCNEJ   : |CORE| network available: 101
,09-27 10:30:42.982   929  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-27 10:30:42.984   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-27 10:30:42.988  3779  3913 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-27 10:30:42.989  3779  3913 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 10:30:42.990  3779  3913 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-27 10:30:42.991  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:42.991  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:42.991  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:42.992  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:30:42.994  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:42.994  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:42.994  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:42.994  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:42.994  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 10:30:42.994  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 10:30:42.995  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 10:30:42.995  5046  5070 E SarControlService: no key has been found,reset the power
09-27 10:30:42.995  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 10:30:42.995  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-27 10:30:42.996  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:42.996  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:30:42.996  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:30:42.996  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:42.996  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:30:42.997  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-27 10:30:42.997  5071  5071 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-27 10:30:43.000  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 10:30:43.000  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-27 10:30:43.004  3732  3732 D SystemUpdateService: onCreate
09-27 10:30:43.005  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000ec03000000000000ffffffff]
,09-27 10:30:43.005  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 10:30:43.005  5071  5085 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-27 10:30:43.006  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:30:43.006  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 10:30:43.006  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 10:30:43.006  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 10:30:43.007  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 10:30:43.007  5071  5071 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-27 10:30:43.012  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000ed03000000000000ffffffff]
09-27 10:30:43.012  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 10:30:43.012  5071  5085 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,09-27 10:30:43.013  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:30:43.013  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 10:30:43.014  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-27 10:30:43.016   929  3873 D WifiService: setWifiEnabled: false pid=5644, uid=10077
09-27 10:30:43.016   929  3873 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 10:30:43.018   929  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-27 10:30:43.018   929  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-27 10:30:43.018   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-27 10:30:43.018   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 10:30:43.023   929  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-27 10:30:43.026  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 10:30:43.027   929  5817 D DhcpClient: Clearing IP address
09-27 10:30:43.027   509   920 D CommandListener: Clearing all IP addresses on wlan0
09-27 10:30:43.028   509   920 D CommandListener: Setting iface cfg
,09-27 10:30:43.031  3732  5404 I iu.UploadsManager: num queued entries: 0
,09-27 10:30:43.031  3732  5404 I iu.UploadsManager: num updated entries: 0
,09-27 10:30:43.032   929  5818 D DhcpClient: Receive thread stopped
,09-27 10:30:43.034  3732  5828 I SystemUpdateService: active receiver: enabled
,09-27 10:30:43.034   929  5815 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-27 10:30:43.035   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
09-27 10:30:43.037  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-27 10:30:43.038   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-27 10:30:43.038  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-27 10:30:43.038   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-27 10:30:43.041   535   535 E Parcel  : Reading a NULL string not supported here.
09-27 10:30:43.042  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-27 10:30:43.048   929   929 D RttService: SCAN_AVAILABLE : 1
09-27 10:30:43.048   929  3084 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-27 10:30:43.050   929  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-27 10:30:43.050   929  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-27 10:30:43.051  3779  3913 W QCNEJ   : |CORE| network lost: 101
09-27 10:30:43.052  5764  5764 D SprintDMHelper: simOperator: 
09-27 10:30:43.052  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-27 10:30:43.052  3779  3913 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-27 10:30:43.056   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 10:30:43.074  3732  5828 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 10:30:43.078  3732  5404 I iu.SyncManager: NEXT; no task
,09-27 10:30:43.078   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 10:30:43.084  3732  5828 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 10:30:43.084  3732  5828 I SystemUpdateService: now status is 0 (complete)
09-27 10:30:43.084  3732  5828 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 10:30:43.084  3732  5828 I SystemUpdateService: file has been verified
09-27 10:30:43.084  3732  5828 I SystemUpdateService: OTA package size = 21989297
,09-27 10:30:43.092  3732  5828 I SystemUpdateService: showing system update notification
,09-27 10:30:43.099   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 10:30:43.099   509   920 D CommandListener: Clearing all IP addresses on wlan0
09-27 10:30:43.100   929  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-27 10:30:43.100   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-27 10:30:43.104   929  2976 D DhcpClient: doQuit
,09-27 10:30:43.104   929  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-27 10:30:43.104  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:43.104  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:43.104  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.104   929  5817 D DhcpClient: onQuitting
09-27 10:30:43.104  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:43.104  5812  5812 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-27 10:30:43.105  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:43.106  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 10:30:43.106   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-27 10:30:43.109  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.109  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:43.110  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 10:30:43.110  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 10:30:43.110  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-27 10:30:43.110  5046  5070 E SarControlService: no key has been found,reset the power
09-27 10:30:43.110  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 10:30:43.111  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 10:30:43.111  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 10:30:43.111  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 10:30:43.111  5071  5071 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-27 10:30:43.111  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:43.111  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:43.112  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.112  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:43.112  3732  3732 D SystemUpdateService: onDestroy
09-27 10:30:43.112  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:43.113  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:43.113  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:43.113  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 10:30:43.113  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 10:30:43.113  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 10:30:43.113  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 10:30:43.113  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:43.114  5071  5071 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 10:30:43.114  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:43.115  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 10:30:43.118  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000ee03000000000000ffffffff]
09-27 10:30:43.118  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 10:30:43.118  5071  5085 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-27 10:30:43.118  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000ef03000000000000ffffffff]
09-27 10:30:43.118  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 10:30:43.118  5071  5085 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-27 10:30:43.119  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:30:43.119  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 10:30:43.120  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:30:43.120  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 10:30:43.121  3732  3732 D SystemUpdateService: onCreate
,09-27 10:30:43.124  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 10:30:43.127  3732  5841 I SystemUpdateService: active receiver: enabled
,09-27 10:30:43.132  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-27 10:30:43.134  5812  5812 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-27 10:30:43.135  3732  5841 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 10:30:43.138  5812  5812 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-27 10:30:43.139  3732  5404 I iu.UploadsManager: num queued entries: 0
,09-27 10:30:43.141  3732  5841 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-27 10:30:43.141  3732  5841 I SystemUpdateService: now status is 0 (complete)
09-27 10:30:43.141  3732  5841 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 10:30:43.141  3732  5841 I SystemUpdateService: file has been verified
09-27 10:30:43.141  3732  5841 I SystemUpdateService: OTA package size = 21989297
,09-27 10:30:43.146  3732  5404 I iu.UploadsManager: num updated entries: 0
,09-27 10:30:43.149  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 10:30:43.150  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 10:30:43.152  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 10:30:43.155  5764  5764 D SprintDMHelper: simOperator: 
,09-27 10:30:43.155  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-27 10:30:43.161  3732  5404 I iu.SyncManager: NEXT; no task
,09-27 10:30:43.166  3732  5841 I SystemUpdateService: showing system update notification
,09-27 10:30:43.172   509   920 E Netd    : netlink response contains error (No such file or directory)
,09-27 10:30:43.173   929  2978 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-27 10:30:43.173   929  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-27 10:30:43.178  5812  5812 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-27 10:30:43.180  3732  3732 D SystemUpdateService: onDestroy
,09-27 10:30:43.189  5812  5812 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-27 10:30:43.294   929  2976 D wifi    : In wifi stop Hal
09-27 10:30:43.295   929  2976 D wifi    : halHandle = 0x7f8ab25f80, mVM = 0x7fa5f8d140, mCls = 0x101912
09-27 10:30:43.297   929  5811 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-27 10:30:43.297   929  5811 D WifiHAL : Got a signal to exit!!!
09-27 10:30:43.297   929  5811 I WifiHAL : Exit wifi_event_loop
,09-27 10:30:43.299  4067  4222 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 10:30:43.300  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:43.302  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:43.303  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:43.303   929  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-27 10:30:43.303   929  2976 E WifiHAL : Event processing terminated
09-27 10:30:43.304   929  2976 D wifi    : In wifi cleaned up handler
,09-27 10:30:43.304   929  2976 I WifiHAL : Internal cleanup completed
09-27 10:30:43.304  5021  5021 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-27 10:30:43.329   929  5811 D wifi    : set interface wlan0 flags (DOWN)
,09-27 10:30:43.329   929  2976 D WifiNative-HAL: HAL event thread stopped successfully
,09-27 10:30:43.536   929   946 D Tethering: InitialState.processMessage what=4
,09-27 10:30:43.542   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-27 10:30:43.982   929  2978 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-27 10:30:44.806   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:45.807   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:46.808   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:47.810   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:48.059   929   946 I ActivityManager: Start proc 5849:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 10:30:48.152  5849  5849 D AdapterServiceConfig: Adding HeadsetService
,09-27 10:30:48.152  5849  5849 D AdapterServiceConfig: Adding A2dpService
09-27 10:30:48.152  5849  5849 D AdapterServiceConfig: Adding HidService
09-27 10:30:48.152  5849  5849 D AdapterServiceConfig: Adding HealthService
09-27 10:30:48.153  5849  5849 D AdapterServiceConfig: Adding PanService
09-27 10:30:48.153  5849  5849 D AdapterServiceConfig: Adding GattService
09-27 10:30:48.153  5849  5849 D AdapterServiceConfig: Adding BluetoothMapService
09-27 10:30:48.153  5849  5849 D AdapterServiceConfig: Adding SapService
,09-27 10:30:48.166   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d12c2b:true
,09-27 10:30:48.166  5849  5849 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 10:30:48.169  5849  5849 I bt_bluedroid: init
,09-27 10:30:48.169  5849  5861 I BluetoothAdapterState: Entering OffState
,09-27 10:30:48.172  5849  5862 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-27 10:30:48.172  5849  5862 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 10:30:48.172  5849  5862 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 10:30:48.172  5849  5862 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 10:30:48.173  5849  5849 I bt_bluedroid: get_profile_interface socket
,09-27 10:30:48.175  5849  5865 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 10:30:48.175  5849  5849 I bt_bluedroid: get_profile_interface sdp
09-27 10:30:48.176  5849  5865 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 10:30:48.180  5849  5860 I bt_bluedroid: config_hci_snoop_log
09-27 10:30:48.181   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-27 10:30:48.185  5849  5861 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 10:30:48.185  5849  5861 D BluetoothAdapterProperties: Setting state to 14
09-27 10:30:48.185  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 10:30:48.187  5849  5861 D BluetoothBondStateMachine: make
,09-27 10:30:48.190  5849  5866 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 10:30:48.192  5849  5861 I BluetoothAdapterState: Entering PendingCommandState
,09-27 10:30:48.193  5849  5849 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 10:30:48.195  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:30:48.196  5849  5849 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 10:30:48.196  5849  5849 D BtGatt.GattService: Received start request. Starting profile...
09-27 10:30:48.196  5849  5849 D BtGatt.GattService: start()
09-27 10:30:48.197  5849  5849 I bt_bluedroid: get_profile_interface gatt
,09-27 10:30:48.197  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:30:48.198  5849  5849 D BtGatt.AdvertiseManager: advertise manager created
,09-27 10:30:48.203  5849  5849 V BluetoothAdapterState: isTurningOff()=false
,09-27 10:30:48.203  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:48.203  5849  5849 V BluetoothAdapterState: isBleTurningOn()=true
09-27 10:30:48.203  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:48.203  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-27 10:30:48.204  5849  5861 I bt_bluedroid: bt_bluedroid
09-27 10:30:48.204  5849  5862 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-27 10:30:48.205  5849  5862 I bt_hci  : start_up
,09-27 10:30:48.210  5849  5862 I bt_vendor: alloc value 0xf3f19871
09-27 10:30:48.210  5849  5862 I bt_vendor: init
09-27 10:30:48.211  5849  5862 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 10:30:48.211  5849  5862 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 10:30:48.322  5849  5862 D bt_hci  : start_up starting async portion
,09-27 10:30:48.323  5849  5869 I bt_hci  : event_finish_startup
09-27 10:30:48.323  5849  5869 I bt_hci_h4: hal_open
09-27 10:30:48.323  5849  5869 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-27 10:30:48.325  5849  5869 I bt_userial_vendor: device fd = 54 open
,09-27 10:30:48.320  5870  5870 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-27 10:30:48.338  5849  5869 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 10:30:48.341  5849  5869 D bt_hwcfg: Chipset BCM4358A3
,09-27 10:30:48.341  5849  5869 D bt_hwcfg: Target name = [BCM4358A3]
09-27 10:30:48.341  5849  5869 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 10:30:48.734  5849  5869 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-27 10:30:48.734  5849  5869 D bt_hwcfg: Settlement delay -- 100 ms
09-27 10:30:48.734  5849  5869 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 10:30:48.810   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:30:48.869  5849  5869 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 10:30:48.869  5849  5869 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-27 10:30:48.871  5849  5869 I bt_hwcfg: vendor lib fwcfg completed
09-27 10:30:48.871  5849  5869 I bt_vendor: firmware callback
09-27 10:30:48.871  5849  5869 I bt_hci  : firmware_config_callback
,09-27 10:30:48.881  5849  5872 I bt_btu  : btu_task pending for preload complete event
,09-27 10:30:48.882  5849  5872 I bt_btu_task: Bluetooth chip preload is complete
09-27 10:30:48.882  5849  5872 I bt_btu  : btu_task received preload complete event
,09-27 10:30:48.890  5849  5872 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 10:30:48.890  5849  5872 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-27 10:30:48.890  5849  5872 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-27 10:30:48.890  5849  5872 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 10:30:48.890  5849  5872 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 10:30:48.891  5849  5872 I         : BTE_InitTraceLevels -- TRC_A2D
09-27 10:30:48.891  5849  5872 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-27 10:30:48.891  5849  5872 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 10:30:48.891  5849  5872 I         : BTE_InitTraceLevels -- TRC_GAP
09-27 10:30:48.891  5849  5872 I         : BTE_InitTraceLevels -- TRC_PAN
,09-27 10:30:48.891  5849  5872 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 10:30:48.891  5849  5872 I         : BTE_InitTraceLevels -- TRC_GATT
,09-27 10:30:48.892  5849  5872 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 10:30:48.892  5849  5872 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-27 10:30:48.892  5849  5872 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 10:30:48.978  5849  5872 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e97549
09-27 10:30:48.978  5849  5872 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e97549 
,09-27 10:30:48.996  5849  5865 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 10:30:48.998  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 10:30:48.998  5849  5865 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 10:30:49.001  5849  5865 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 10:30:49.004  5849  5865 D BluetoothAdapterProperties: Scan Mode:20
09-27 10:30:49.004  5849  5865 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 10:30:49.005  5849  5865 D bt_hci  : do_postload posting postload work item
09-27 10:30:49.005  5849  5869 I bt_hci  : event_postload
09-27 10:30:49.005  5849  5869 I bt_vendor: sco_config_cb
09-27 10:30:49.005  5849  5869 I bt_hci  : sco_config_callback postload finished.
,09-27 10:30:49.008  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:49.010  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:49.010  5849  5865 D bt_bte_conf: Device ID record 1 : primary
09-27 10:30:49.010  5849  5865 D bt_bte_conf:   vendorId            = 000f
09-27 10:30:49.010  5849  5865 D bt_bte_conf:   vendorIdSource      = 0001
,09-27 10:30:49.010  5849  5865 D bt_bte_conf:   product             = 1200
09-27 10:30:49.010  5849  5865 D bt_bte_conf:   version             = 1436
09-27 10:30:49.010  5849  5865 D bt_bte_conf:   clientExecutableURL = 
09-27 10:30:49.010  5849  5865 D bt_bte_conf:   serviceDescription  = 
09-27 10:30:49.010  5849  5865 D bt_bte_conf:   documentationURL    = 
09-27 10:30:49.010  5849  5865 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-27 10:30:49.010  5849  5862 D bt_stack_manager: event_start_up_stack finished
09-27 10:30:49.011  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 10:30:49.011  5849  5861 D BluetoothAdapterProperties: Setting state to 15
09-27 10:30:49.011  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 10:30:49.011  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:49.012  5849  5869 I bt_vendor: low_power_mode_cb
,09-27 10:30:49.013  5849  5861 I BluetoothAdapterState: Entering BleOnState
,09-27 10:30:49.017  5849  5861 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-27 10:30:49.017  5849  5861 D BluetoothAdapterProperties: Setting state to 11
,09-27 10:30:49.017  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 10:30:49.022  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:30:49.022  5849  5849 D HeadsetService: Received start request. Starting profile...
09-27 10:30:49.025  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:49.025  5849  5849 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 10:30:49.025  5849  5849 D HeadsetStateMachine: make
09-27 10:30:49.028  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:49.031  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:49.038  5849  5849 D HeadsetStateMachine: max_hf_connections = 1
,09-27 10:30:49.038  5849  5849 I bt_bluedroid: get_profile_interface handsfree
09-27 10:30:49.038  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 10:30:49.039  5849  5865 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-27 10:30:49.042  5849  5861 I BluetoothAdapterState: Entering PendingCommandState
,09-27 10:30:49.044  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:30:49.044  5849  5849 D A2dpService: Received start request. Starting profile...
09-27 10:30:49.045  5849  5849 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-27 10:30:49.045  5849  5849 I bt_bluedroid: get_profile_interface avrcp
,09-27 10:30:49.050  5849  5849 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 10:30:49.051  5849  5849 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 10:30:49.051  5849  5849 D A2dpStateMachine: make
,09-27 10:30:49.052  5849  5849 I bt_bluedroid: get_profile_interface a2dp
09-27 10:30:49.052  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-27 10:30:49.054  5849  5881 D A2dpStateMachine: Enter Disconnected: -2
,09-27 10:30:49.056  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 10:30:49.057  5849  5849 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 10:30:49.058  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:30:49.059  5849  5849 D HidService: Received start request. Starting profile...
,09-27 10:30:49.059  5849  5849 I bt_bluedroid: get_profile_interface hidhost
09-27 10:30:49.060  5849  5849 D HidService: setHidService(): set to: null
09-27 10:30:49.060  5698  5698 D BluetoothInputDevice: Proxy object connected
09-27 10:30:49.060  5849  5849 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 10:30:49.060  5698  5698 D HidProfile: Bluetooth service connected
09-27 10:30:49.061  5849  5865 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e7856d
,09-27 10:30:49.061  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 10:30:49.061  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:30:49.061  5849  5849 D HealthService: Received start request. Starting profile...
09-27 10:30:49.063  5849  5849 I bt_bluedroid: get_profile_interface health
,09-27 10:30:49.064  5849  5849 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-27 10:30:49.065  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:30:49.066  5698  5698 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 10:30:49.066  5849  5849 D PanService: Received start request. Starting profile...
09-27 10:30:49.066  5849  5849 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 10:30:49.066  5849  5849 I bt_bluedroid: get_profile_interface pan
,09-27 10:30:49.066  5698  5698 D PanProfile: Bluetooth service connected
09-27 10:30:49.067  5849  5865 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-27 10:30:49.069  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:30:49.070  5698  5698 D BluetoothMap: Proxy object connected
09-27 10:30:49.070  5849  5849 D BluetoothMapService: Received start request. Starting profile...
09-27 10:30:49.070  5849  5849 D BluetoothMapService: start()
09-27 10:30:49.071  5698  5698 D MapProfile: Bluetooth service connected
09-27 10:30:49.071  5698  5698 D BluetoothMap: getConnectedDevices()
09-27 10:30:49.072  5698  5698 D BluetoothMap: Bluetooth is Not enabled
,09-27 10:30:49.073  5849  5849 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-27 10:30:49.074  5849  5849 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-27 10:30:49.074  5849  5849 D BluetoothMapAppObserver: createReceiver()
,09-27 10:30:49.076  5849  5849 D BluetoothMapAppObserver: initObservers()
,09-27 10:30:49.076  5849  5849 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-27 10:30:49.082  5849  5849 V SapService: SapBinder()
,09-27 10:30:49.083  5849  5849 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:30:49.083  5849  5849 D SapService: Received start request. Starting profile...
09-27 10:30:49.083  5849  5849 V SapService: start()
,09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isTurningOff()=false
09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isTurningOn()=true
09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isTurningOff()=false
,09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isTurningOn()=true
09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
,09-27 10:30:49.085  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:49.085  5849  5878 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isTurningOff()=false
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isTurningOn()=true
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isTurningOff()=false
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isTurningOn()=true
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isTurningOff()=false
09-27 10:30:49.086  5849  5849 V BluetoothAdapterState: isTurningOn()=true
09-27 10:30:49.087  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:49.087  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:49.087  5849  5849 V BluetoothAdapterState: isTurningOff()=false
09-27 10:30:49.087  5849  5849 V BluetoothAdapterState: isTurningOn()=true
09-27 10:30:49.087  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:49.087  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:49.088  5849  5849 V BluetoothAdapterState: isTurningOff()=false
09-27 10:30:49.088  5849  5849 V BluetoothAdapterState: isTurningOn()=true
,09-27 10:30:49.088  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:49.088  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:49.088  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 10:30:49.088  5849  5861 D BluetoothAdapterProperties: ScanMode =  20
09-27 10:30:49.089  5849  5861 D BluetoothAdapterProperties: State =  11
09-27 10:30:49.089  5849  5865 D BluetoothAdapterProperties: Scan Mode:21
09-27 10:30:49.090  5849  5861 D BluetoothAdapterProperties: Setting state to 12
09-27 10:30:49.090  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 10:30:49.090  5849  5865 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 10:30:49.090  3131  3142 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 10:30:49.091  5849  5861 I BluetoothAdapterState: Entering OnState
,09-27 10:30:49.091  3131  3981 D BluetoothMap: onBluetoothStateChange: up=true
,09-27 10:30:49.094   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 10:30:49.094  3131  3131 D BluetoothMap: Proxy object connected
09-27 10:30:49.094  3131  3131 D MapProfile: Bluetooth service connected
09-27 10:30:49.094  3131  3131 D BluetoothMap: getConnectedDevices()
09-27 10:30:49.094  5698  5711 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 10:30:49.095   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:49.096  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 10:30:49.096   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 10:30:49.096  3131  3918 D BluetoothPan: onBluetoothStateChange on: true
09-27 10:30:49.097   929   929 D BluetoothA2dp: Proxy object connected
09-27 10:30:49.098  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:49.098  3131  3131 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 10:30:49.098  3131  3131 D PanProfile: Bluetooth service connected
09-27 10:30:49.098  3131  3981 D BluetoothPbap: onBluetoothStateChange: up=true
,09-27 10:30:49.100  3810  3832 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 10:30:49.101  3131  3148 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:49.102  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:49.102  5849  5849 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 10:30:49.102   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 10:30:49.102  3131  3131 D BluetoothInputDevice: Proxy object connected
09-27 10:30:49.102  3131  3131 D HidProfile: Bluetooth service connected
,09-27 10:30:49.103  3131  3142 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-27 10:30:49.103  5849  5849 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 10:30:49.104  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:49.105  3131  3131 D BluetoothA2dp: Proxy object connected
09-27 10:30:49.105  5698  5709 D BluetoothMap: onBluetoothStateChange: up=true
09-27 10:30:49.106  5698  5711 D BluetoothPan: onBluetoothStateChange on: true
09-27 10:30:49.107  5698  5709 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 10:30:49.107  5849  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 10:30:49.108   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:49.108  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 10:30:49.110  5849  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 10:30:49.110  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:49.111  5698  5698 D LocalBluetoothProfileManager: Adding local A2DP profile
09-27 10:30:49.111  5849  5849 D ObexServerSockets: Succeed to create listening sockets 
09-27 10:30:49.111  5849  5849 D ObexServerSockets0: startAccept()
09-27 10:30:49.111  5849  5849 D ObexServerSockets0: prepareForNewConnect()
09-27 10:30:49.113  5849  5849 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-27 10:30:49.113  5849  5849 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 10:30:49.113  5849  5888 D ObexServerSockets0: Accepting socket connection...
,09-27 10:30:49.114  5849  5849 D BluetoothMapService: onReceive
09-27 10:30:49.114  5849  5849 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 10:30:49.114  5849  5849 D BluetoothMapService: STATE_ON
09-27 10:30:49.114  5849  5889 D ObexServerSockets0: Accepting socket connection...
09-27 10:30:49.114  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:49.115  5698  5698 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-27 10:30:49.115  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:49.116  5849  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 10:30:49.117  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:49.117  5849  5890 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 10:30:49.118  5849  5890 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 10:30:49.123  5698  5698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 10:30:49.125  5698  5698 D BluetoothA2dp: Proxy object connected
,09-27 10:30:49.129  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 10:30:49.132  5698  5698 D DockEventReceiver: finishStartingService: stopping service
,09-27 10:30:49.136  3131  3131 D BluetoothPbap: Proxy object connected
,09-27 10:30:49.137  3131  3131 D PbapServerProfile: Bluetooth service connected
,09-27 10:30:49.139  5698  5698 D BluetoothPbap: Proxy object connected
,09-27 10:30:49.140  5698  5698 D PbapServerProfile: Bluetooth service connected
,09-27 10:30:49.141  5849  5849 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 10:30:49.142  5849  5849 D ObexServerSockets0: prepareForNewConnect()
,09-27 10:30:49.143  5849  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 10:30:49.159  5849  5898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 10:30:49.161  5849  5898 I BtOppRfcommListener: Accept thread started.
,09-27 10:30:49.191   929   929 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.191  3131  3918 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.192  3131  3131 D HeadsetProfile: Bluetooth service connected
,09-27 10:30:49.192   929   929 D BluetoothHeadset: Proxy object connected
09-27 10:30:49.192  3810  4039 D BluetoothHeadset: Proxy object connected
09-27 10:30:49.192   929   929 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.194   929   946 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.197   929   946 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.200  3810  4034 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.202   929   946 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.220  5698  5709 D BluetoothHeadset: Proxy object connected
,09-27 10:30:49.221  5698  5698 D HeadsetProfile: Bluetooth service connected
,09-27 10:30:49.811   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 10:30:50.941   929  2978 D ConnectivityService: handlePromptUnvalidated 101
,09-27 10:30:53.033  5849  5861 D BluetoothAdapterState: Current state: ON, message: 23
09-27 10:30:53.033  5849  5861 D BluetoothAdapterProperties: Setting state to 13
09-27 10:30:53.034  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-27 10:30:53.035  5849  5861 D BluetoothAdapterProperties: onBluetoothDisable()
,09-27 10:30:53.037  5849  5861 I BluetoothAdapterState: Entering PendingCommandState
09-27 10:30:53.041  5849  5849 D BluetoothMapService: onReceive
,09-27 10:30:53.042  5849  5849 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 10:30:53.042  5849  5849 D BluetoothMapService: STATE_TURNING_OFF
09-27 10:30:53.042  5849  5849 D BluetoothMapService: MAP Service closeService in
09-27 10:30:53.043  5849  5849 D BluetoothMapMasInstance0: MAP Service shutdown
09-27 10:30:53.043  5849  5849 D ObexServerSockets0: shutdown(block = true)
09-27 10:30:53.045  5849  5849 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 10:30:53.045  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:53.045  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:53.045  5849  5849 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-27 10:30:53.045  5849  5888 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-27 10:30:53.045  5849  5874 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-27 10:30:53.046  5849  5889 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-27 10:30:53.046  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:53.046  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:53.050  5849  5849 I BtOppRfcommListener: stopping Accept Thread
09-27 10:30:53.051  5849  5898 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-27 10:30:53.051  5849  5898 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-27 10:30:53.052  5849  5865 D BluetoothAdapterProperties: Scan Mode:20
09-27 10:30:53.053  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-27 10:30:53.054  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:53.054  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:53.056  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-27 10:30:53.056  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:53.059  5849  5849 D HeadsetService: Received stop request...Stopping profile...
09-27 10:30:53.061   929   929 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:53.061  3131  3918 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:53.062  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:30:53.062  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:30:53.062  5698  5711 D BluetoothHeadset: Proxy object disconnected
,09-27 10:30:53.063  5849  5849 D A2dpService: Received stop request...Stopping profile...
09-27 10:30:53.063   929   929 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:53.063  5849  5881 D A2dpStateMachine: Exit Disconnected: -1
09-27 10:30:53.063  3810  3833 D BluetoothHeadset: Proxy object disconnected
09-27 10:30:53.064   929   929 D BluetoothHeadset: Proxy object disconnected
,09-27 10:30:53.064  5644  5644 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-27 10:30:53.064  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:30:53.066  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:53.067   929   929 D BluetoothA2dp: Proxy object disconnected
09-27 10:30:53.068  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:53.070  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:53.070  5849  5849 D HidService: Received stop request...Stopping profile...
09-27 10:30:53.070  5849  5849 D HidService: Stopping Bluetooth HidService
09-27 10:30:53.072  5849  5849 D HealthService: Received stop request...Stopping profile...
09-27 10:30:53.073  5698  5698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 10:30:53.073  5849  5849 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:53.073  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.073  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.074  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 10:30:53.075  5698  5698 D HeadsetProfile: Bluetooth service disconnected
09-27 10:30:53.076  5698  5698 D BluetoothA2dp: Proxy object disconnected
09-27 10:30:53.076  5849  5849 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-27 10:30:53.076  5849  5849 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-27 10:30:53.076  5698  5698 D BluetoothInputDevice: Proxy object disconnected
09-27 10:30:53.076  5698  5698 D HidProfile: Bluetooth service disconnected
09-27 10:30:53.077  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-27 10:30:53.077  5849  5849 D PanService: Received stop request...Stopping profile...
09-27 10:30:53.077  5849  5872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:53.077  5849  5872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-27 10:30:53.077  5849  5872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:53.078  5849  5865 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-27 10:30:53.079  5849  5849 D BluetoothMapService: Received stop request...Stopping profile...
09-27 10:30:53.079  5849  5849 D BluetoothMapService: stop()
09-27 10:30:53.080  5849  5849 D BluetoothMapAppObserver: deinitObservers()
09-27 10:30:53.080  5849  5849 D BluetoothMapAppObserver: removeReceiver()
09-27 10:30:53.082  5849  5849 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:53.082  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.082  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.082  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:53.084  5849  5872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:53.084  5849  5872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:53.084  5849  5872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 10:30:53.084  3131  3131 D HeadsetProfile: Bluetooth service disconnected
09-27 10:30:53.084  5849  5872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 10:30:53.084  5849  5872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-27 10:30:53.084  5849  5872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-27 10:30:53.084  3131  3131 D BluetoothA2dp: Proxy object disconnected
09-27 10:30:53.084  3131  3131 D BluetoothInputDevice: Proxy object disconnected
09-27 10:30:53.084  3131  3131 D HidProfile: Bluetooth service disconnected
,09-27 10:30:53.084  5698  5698 D DockEventReceiver: finishStartingService: stopping service
09-27 10:30:53.084  3131  3131 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 10:30:53.085  3131  3131 D PanProfile: Bluetooth service disconnected
09-27 10:30:53.085  3131  3131 D BluetoothMap: Proxy object disconnected
09-27 10:30:53.085  3131  3131 D MapProfile: Bluetooth service disconnected
09-27 10:30:53.085  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-27 10:30:53.085  5849  5849 D SapService: Received stop request...Stopping profile...
09-27 10:30:53.085  5849  5849 V SapService: stop()
09-27 10:30:53.086  5698  5698 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-27 10:30:53.086  5698  5698 D PanProfile: Bluetooth service disconnected
09-27 10:30:53.086  5698  5698 D BluetoothMap: Proxy object disconnected
09-27 10:30:53.086  5698  5698 D MapProfile: Bluetooth service disconnected
09-27 10:30:53.087  5849  5849 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:53.087  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.087  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.087  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:53.087  5849  5849 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-27 10:30:53.087  5849  5849 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-27 10:30:53.088  5849  5865 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-27 10:30:53.088  5849  5849 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:53.088  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.088  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.088  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:53.088  5849  5849 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-27 10:30:53.088  5849  5865 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-27 10:30:53.089  5849  5849 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-27 10:30:53.090  5849  5849 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:53.091  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.091  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.091  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:53.091  5849  5849 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-27 10:30:53.091  5849  5849 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-27 10:30:53.092  5849  5849 D BluetoothMapService: MAP Service closeService in
09-27 10:30:53.092  5849  5849 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:53.092  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.092  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.092  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:53.093  5849  5849 D BluetoothMapService: cleanup()
09-27 10:30:53.093  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 10:30:53.093  5849  5849 D BluetoothMapService: MAP Service closeService in
09-27 10:30:53.093  5849  5849 V BluetoothAdapterState: isTurningOff()=true
09-27 10:30:53.093  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.093  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.093  5849  5849 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:30:53.093  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-27 10:30:53.093  5849  5861 D BluetoothAdapterProperties: Setting state to 15
09-27 10:30:53.093  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-27 10:30:53.094  5849  5861 I BluetoothAdapterState: Entering BleOnState
09-27 10:30:53.096  3131  3131 D BluetoothPbap: Proxy object disconnected
09-27 10:30:53.096  3131  3131 D PbapServerProfile: Bluetooth service disconnected
09-27 10:30:53.097  3131  3148 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 10:30:53.097  5698  5698 D BluetoothPbap: Proxy object disconnected
09-27 10:30:53.097  5698  5698 D PbapServerProfile: Bluetooth service disconnected
09-27 10:30:53.097  3131  3981 D BluetoothMap: onBluetoothStateChange: up=false
09-27 10:30:53.098   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 10:30:53.098  5698  5711 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 10:30:53.100  5698  5709 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-27 10:30:53.100  5698  5711 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 10:30:53.101   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 10:30:53.101   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 10:30:53.102  3131  3148 D BluetoothPan: onBluetoothStateChange on: false
09-27 10:30:53.104  3131  3918 D BluetoothPbap: onBluetoothStateChange: up=false
09-27 10:30:53.104  3810  3832 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 10:30:53.105  3131  3981 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-27 10:30:53.105   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-27 10:30:53.105  3131  3142 D BluetoothA2dp: onBluetoothStateChange: up=false
09-27 10:30:53.106  5698  5709 D BluetoothMap: onBluetoothStateChange: up=false
,09-27 10:30:53.106  5698  5711 D BluetoothPan: onBluetoothStateChange on: false
09-27 10:30:53.107  5698  5709 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-27 10:30:53.108  5849  5861 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-27 10:30:53.108  5849  5861 D BluetoothAdapterProperties: Setting state to 16
09-27 10:30:53.108  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-27 10:30:53.109  5849  5861 D BluetoothAdapterProperties: onBleDisable
09-27 10:30:53.109  5849  5861 I BluetoothAdapterState: Entering PendingCommandState
09-27 10:30:53.109  5849  5862 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-27 10:30:53.111  5849  5872 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-27 10:30:53.111  5849  5872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-27 10:30:53.112  5849  5865 D BluetoothAdapterProperties: Scan Mode:20
09-27 10:30:53.112  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:53.114  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:53.116  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:53.118  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:53.121  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:30:53.122  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:30:53.123  5698  5698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-27 10:30:53.127  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 10:30:53.128  5698  5698 D DockEventReceiver: finishStartingService: stopping service
,09-27 10:30:53.326  5849  5865 I bt_hci  : shut_down
,09-27 10:30:53.336  5849  5869 D bt_hwcfg: hw_epilog_process
,09-27 10:30:53.337  5849  5869 I bt_vendor: low_power_mode_cb
,09-27 10:30:53.339  5849  5869 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-27 10:30:53.339  5849  5869 I bt_vendor: epilog_cb
09-27 10:30:53.339  5849  5869 I bt_hci  : epilog_finished_callback
,09-27 10:30:53.342  5849  5865 I bt_hci_h4: hal_close
,09-27 10:30:53.343  5849  5865 I bt_userial_vendor: device fd = 54 close
,09-27 10:30:53.465  5849  5862 D bt_stack_manager: event_shut_down_stack finished.
,09-27 10:30:53.466  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-27 10:30:53.469  5849  5861 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-27 10:30:53.470  5849  5849 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 10:30:53.471  5849  5849 D BtGatt.GattService: Received stop request...Stopping profile...
09-27 10:30:53.471  5849  5849 D BtGatt.GattService: stop()
09-27 10:30:53.471  5849  5849 D BtGatt.AdvertiseManager: advertise clients cleared
09-27 10:30:53.474  5849  5849 V BluetoothAdapterState: isTurningOff()=false
,09-27 10:30:53.474  5849  5849 V BluetoothAdapterState: isTurningOn()=false
09-27 10:30:53.474  5849  5849 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:30:53.475  5849  5849 V BluetoothAdapterState: isBleTurningOff()=true
09-27 10:30:53.475  5849  5861 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-27 10:30:53.475  5849  5861 D BluetoothAdapterProperties: Setting state to 10
09-27 10:30:53.476  5849  5861 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-27 10:30:53.477  5849  5861 I BluetoothAdapterState: Entering OffState
,09-27 10:30:53.478   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-27 10:30:53.491  5849  5849 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-27 10:30:53.491  5849  5849 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-27 10:30:53.491  5849  5849 I BluetoothServiceJni: cleanupNative: return from cleanup
09-27 10:30:53.494  5849  5862 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-27 10:30:53.500  5849  5849 I art     : System.exit called, status: 0
,09-27 10:30:53.501  5849  5849 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-27 10:30:53.535   929  3597 I ActivityManager: Process com.android.bluetooth (pid 5849) has died
,09-27 10:30:58.031  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 10:30:58.031  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:58.036  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:30:58.036  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60d99ca removed from the list
09-27 10:30:58.036  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
,09-27 10:30:58.036  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:58.036  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:58.039  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:30:58.039  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c7ae58 added. We now have 4 listener(s)
09-27 10:30:58.039  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 10:30:58.040  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:30:58.041  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c7ae58 removed from the list
09-27 10:30:58.041  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:30:58.041  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:30:58.041  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:30:58.044  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:30:58.044  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3343bb1 added. We now have 4 listener(s)
,09-27 10:30:58.045  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:31:03.056  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:03.094   929   946 I ActivityManager: Start proc 5906:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-27 10:31:03.195  5906  5906 D AdapterServiceConfig: Adding HeadsetService
,09-27 10:31:03.195  5906  5906 D AdapterServiceConfig: Adding A2dpService
09-27 10:31:03.195  5906  5906 D AdapterServiceConfig: Adding HidService
09-27 10:31:03.195  5906  5906 D AdapterServiceConfig: Adding HealthService
09-27 10:31:03.196  5906  5906 D AdapterServiceConfig: Adding PanService
09-27 10:31:03.196  5906  5906 D AdapterServiceConfig: Adding GattService
,09-27 10:31:03.196  5906  5906 D AdapterServiceConfig: Adding BluetoothMapService
09-27 10:31:03.196  5906  5906 D AdapterServiceConfig: Adding SapService
,09-27 10:31:03.211   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0c8d48:true
,09-27 10:31:03.211  5906  5906 D BluetoothAdapterState: make() - Creating AdapterState
,09-27 10:31:03.214  5906  5906 I bt_bluedroid: init
09-27 10:31:03.215  5906  5918 I BluetoothAdapterState: Entering OffState
,09-27 10:31:03.217  5906  5919 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-27 10:31:03.217  5906  5919 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-27 10:31:03.217  5906  5919 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-27 10:31:03.217  5906  5919 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-27 10:31:03.218  5906  5906 I bt_bluedroid: get_profile_interface socket
,09-27 10:31:03.219  5906  5922 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 10:31:03.220  5906  5906 I bt_bluedroid: get_profile_interface sdp
09-27 10:31:03.221  5906  5922 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 10:31:03.225  5906  5917 I bt_bluedroid: config_hci_snoop_log
09-27 10:31:03.226   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-27 10:31:03.230  5906  5918 D BluetoothAdapterState: Current state: OFF, message: 0
,09-27 10:31:03.230  5906  5918 D BluetoothAdapterProperties: Setting state to 14
09-27 10:31:03.230  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-27 10:31:03.231  5906  5918 D BluetoothBondStateMachine: make
,09-27 10:31:03.234  5906  5923 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-27 10:31:03.237  5906  5918 I BluetoothAdapterState: Entering PendingCommandState
,09-27 10:31:03.239  5906  5906 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-27 10:31:03.241  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:31:03.241  5906  5906 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-27 10:31:03.242  5906  5906 D BtGatt.GattService: Received start request. Starting profile...
,09-27 10:31:03.252  5906  5906 D BtGatt.GattService: start()
09-27 10:31:03.252  5906  5906 I bt_bluedroid: get_profile_interface gatt
09-27 10:31:03.253  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:31:03.253  5906  5906 D BtGatt.AdvertiseManager: advertise manager created
,09-27 10:31:03.260  5906  5906 V BluetoothAdapterState: isTurningOff()=false
09-27 10:31:03.260  5906  5906 V BluetoothAdapterState: isTurningOn()=false
,09-27 10:31:03.260  5906  5906 V BluetoothAdapterState: isBleTurningOn()=true
09-27 10:31:03.260  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 10:31:03.260  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-27 10:31:03.261  5906  5918 I bt_bluedroid: bt_bluedroid
09-27 10:31:03.262  5906  5919 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-27 10:31:03.262  5906  5919 I bt_hci  : start_up
,09-27 10:31:03.267  5906  5919 I bt_vendor: alloc value 0xf3f19871
,09-27 10:31:03.267  5906  5919 I bt_vendor: init
09-27 10:31:03.267  5906  5919 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-27 10:31:03.267  5906  5919 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-27 10:31:03.376  5906  5919 D bt_hci  : start_up starting async portion
09-27 10:31:03.377  5906  5926 I bt_hci  : event_finish_startup
09-27 10:31:03.377  5906  5926 I bt_hci_h4: hal_open
09-27 10:31:03.377  5906  5926 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-27 10:31:03.373  5927  5927 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-27 10:31:03.382  5906  5926 I bt_userial_vendor: device fd = 54 open
,09-27 10:31:03.399  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 10:31:03.403  5906  5926 D bt_hwcfg: Chipset BCM4358A3
,09-27 10:31:03.403  5906  5926 D bt_hwcfg: Target name = [BCM4358A3]
09-27 10:31:03.403  5906  5926 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-27 10:31:03.803  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-27 10:31:03.804  5906  5926 D bt_hwcfg: Settlement delay -- 100 ms
09-27 10:31:03.804  5906  5926 I bt_hwcfg: Setting fw settlement delay to 100 
,09-27 10:31:03.938  5906  5926 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-27 10:31:03.938  5906  5926 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-27 10:31:03.940  5906  5926 I bt_hwcfg: vendor lib fwcfg completed
09-27 10:31:03.940  5906  5926 I bt_vendor: firmware callback
,09-27 10:31:03.940  5906  5926 I bt_hci  : firmware_config_callback
,09-27 10:31:03.948  5906  5929 I bt_btu  : btu_task pending for preload complete event
,09-27 10:31:03.948  5906  5929 I bt_btu_task: Bluetooth chip preload is complete
09-27 10:31:03.948  5906  5929 I bt_btu  : btu_task received preload complete event
,09-27 10:31:03.955  5906  5929 I         : BTE_InitTraceLevels -- TRC_HCI
,09-27 10:31:03.956  5906  5929 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-27 10:31:03.956  5906  5929 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-27 10:31:03.956  5906  5929 I         : BTE_InitTraceLevels -- TRC_AVDT
09-27 10:31:03.956  5906  5929 I         : BTE_InitTraceLevels -- TRC_AVRC
09-27 10:31:03.956  5906  5929 I         : BTE_InitTraceLevels -- TRC_A2D
,09-27 10:31:03.956  5906  5929 I         : BTE_InitTraceLevels -- TRC_BNEP
09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTM
09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_GAP
,09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_PAN
09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_SDP
09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_GATT
09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_SMP
09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-27 10:31:03.957  5906  5929 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-27 10:31:04.040  5906  5929 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e97549
09-27 10:31:04.041  5906  5929 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e97549 
,09-27 10:31:04.061  5906  5922 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-27 10:31:04.063  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-27 10:31:04.064  5906  5922 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-27 10:31:04.066  5906  5922 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-27 10:31:04.069  5906  5922 D BluetoothAdapterProperties: Scan Mode:20
,09-27 10:31:04.069  5906  5922 D BluetoothAdapterProperties: Discoverable Timeout:120
09-27 10:31:04.070  5906  5922 D bt_hci  : do_postload posting postload work item
,09-27 10:31:04.070  5906  5926 I bt_hci  : event_postload
,09-27 10:31:04.070  5906  5926 I bt_vendor: sco_config_cb
09-27 10:31:04.070  5906  5926 I bt_hci  : sco_config_callback postload finished.
09-27 10:31:04.072  5906  5922 D bt_bte_conf: Device ID record 1 : primary
09-27 10:31:04.073  5906  5922 D bt_bte_conf:   vendorId            = 000f
09-27 10:31:04.073  5906  5922 D bt_bte_conf:   vendorIdSource      = 0001
09-27 10:31:04.073  5906  5922 D bt_bte_conf:   product             = 1200
,09-27 10:31:04.073  5906  5922 D bt_bte_conf:   version             = 1436
09-27 10:31:04.073  5906  5922 D bt_bte_conf:   clientExecutableURL = 
09-27 10:31:04.073  5906  5922 D bt_bte_conf:   serviceDescription  = 
09-27 10:31:04.073  5906  5922 D bt_bte_conf:   documentationURL    = 
09-27 10:31:04.073  5906  5922 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-27 10:31:04.074  5906  5919 D bt_stack_manager: event_start_up_stack finished
09-27 10:31:04.074  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-27 10:31:04.075  5906  5918 D BluetoothAdapterProperties: Setting state to 15
09-27 10:31:04.075  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-27 10:31:04.076  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:04.076  5906  5918 I BluetoothAdapterState: Entering BleOnState
,09-27 10:31:04.079  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:04.082  5906  5918 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-27 10:31:04.082  5906  5918 D BluetoothAdapterProperties: Setting state to 11
,09-27 10:31:04.082  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-27 10:31:04.082  5906  5926 I bt_vendor: low_power_mode_cb
,09-27 10:31:04.093  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:31:04.094  5906  5906 D HeadsetService: Received start request. Starting profile...
09-27 10:31:04.098  5906  5906 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-27 10:31:04.098  5906  5906 D HeadsetStateMachine: make
,09-27 10:31:04.099  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:04.103  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:04.108  5906  5918 I BluetoothAdapterState: Entering PendingCommandState
,09-27 10:31:04.110  5906  5906 D HeadsetStateMachine: max_hf_connections = 1
,09-27 10:31:04.110  5906  5906 I bt_bluedroid: get_profile_interface handsfree
09-27 10:31:04.111  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-27 10:31:04.111  5906  5922 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-27 10:31:04.114  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:31:04.115  5906  5906 D A2dpService: Received start request. Starting profile...
,09-27 10:31:04.115  5906  5906 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-27 10:31:04.116  5906  5906 I bt_bluedroid: get_profile_interface avrcp
,09-27 10:31:04.122  5906  5906 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-27 10:31:04.122  5906  5906 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-27 10:31:04.122  5906  5906 D A2dpStateMachine: make
09-27 10:31:04.123  5906  5906 I bt_bluedroid: get_profile_interface a2dp
,09-27 10:31:04.124  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-27 10:31:04.125  5906  5937 D A2dpStateMachine: Enter Disconnected: -2
,09-27 10:31:04.125  5906  5906 I BluetoothHidServiceJni: classInitNative: succeeds
,09-27 10:31:04.126  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:31:04.127  5906  5906 D HidService: Received start request. Starting profile...
09-27 10:31:04.127  5906  5906 I bt_bluedroid: get_profile_interface hidhost
09-27 10:31:04.127  5906  5906 D HidService: setHidService(): set to: null
09-27 10:31:04.127  5906  5922 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e7856d
09-27 10:31:04.128  5906  5922 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-27 10:31:04.129  5906  5906 I BluetoothHealthServiceJni: classInitNative: succeeds
09-27 10:31:04.130  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:31:04.131  5906  5906 D HealthService: Received start request. Starting profile...
,09-27 10:31:04.131  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 10:31:04.136  5906  5906 I bt_bluedroid: get_profile_interface health
,09-27 10:31:04.137  5906  5906 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-27 10:31:04.138  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:31:04.138  5906  5906 D PanService: Received start request. Starting profile...
09-27 10:31:04.139  5906  5906 D BluetoothPanServiceJni: initializeNative(L110): pan
09-27 10:31:04.139  5906  5906 I bt_bluedroid: get_profile_interface pan
09-27 10:31:04.139  5906  5922 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-27 10:31:04.141  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:31:04.142  5906  5906 D BluetoothMapService: Received start request. Starting profile...
,09-27 10:31:04.142  5906  5906 D BluetoothMapService: start()
09-27 10:31:04.145  5906  5906 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-27 10:31:04.146  5906  5906 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-27 10:31:04.146  5906  5906 D BluetoothMapAppObserver: createReceiver()
09-27 10:31:04.147  5906  5906 D BluetoothMapAppObserver: initObservers()
09-27 10:31:04.147  5906  5906 D BluetoothMapAppObserver: getEnabledAccountItems()
09-27 10:31:04.155  5906  5906 V SapService: SapBinder()
09-27 10:31:04.155  5906  5906 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
09-27 10:31:04.156  5906  5906 D SapService: Received start request. Starting profile...
09-27 10:31:04.156  5906  5906 V SapService: start()
,09-27 10:31:04.157  5906  5906 V BluetoothAdapterState: isTurningOff()=false
,09-27 10:31:04.157  5906  5906 V BluetoothAdapterState: isTurningOn()=true
09-27 10:31:04.157  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:31:04.157  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:31:04.157  5906  5906 V BluetoothAdapterState: isTurningOff()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isTurningOn()=true
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isTurningOff()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isTurningOn()=true
09-27 10:31:04.158  5906  5935 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isTurningOff()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isTurningOn()=true
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:31:04.158  5906  5906 V BluetoothAdapterState: isTurningOff()=false
09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isTurningOn()=true
09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isTurningOff()=false
09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isTurningOn()=true
09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
,09-27 10:31:04.159  5906  5906 V BluetoothAdapterState: isTurningOff()=false
,09-27 10:31:04.160  5906  5906 V BluetoothAdapterState: isTurningOn()=true
09-27 10:31:04.160  5906  5906 V BluetoothAdapterState: isBleTurningOn()=false
09-27 10:31:04.160  5906  5906 V BluetoothAdapterState: isBleTurningOff()=false
09-27 10:31:04.160  5906  5918 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-27 10:31:04.160  5906  5918 D BluetoothAdapterProperties: ScanMode =  20
09-27 10:31:04.160  5906  5918 D BluetoothAdapterProperties: State =  11
09-27 10:31:04.162  5906  5922 D BluetoothAdapterProperties: Scan Mode:21
09-27 10:31:04.162  5906  5922 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-27 10:31:04.162  5906  5918 D BluetoothAdapterProperties: Setting state to 12
09-27 10:31:04.162  5906  5918 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-27 10:31:04.163  3131  3918 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 10:31:04.163  3131  3142 D BluetoothMap: onBluetoothStateChange: up=true
,09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:31:04.165  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:31:04.165  5906  5918 I BluetoothAdapterState: Entering OnState
09-27 10:31:04.165  3131  3131 D BluetoothMap: Proxy object connected
09-27 10:31:04.165  3131  3131 D MapProfile: Bluetooth service connected
09-27 10:31:04.166   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 10:31:04.166  3131  3131 D BluetoothMap: getConnectedDevices()
09-27 10:31:04.166  5698  5711 D BluetoothPbap: onBluetoothStateChange: up=true
,09-27 10:31:04.167  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 10:31:04.168  5698  5709 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-27 10:31:04.169  5698  5711 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:31:04.169  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:31:04.170   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 10:31:04.171   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 10:31:04.171  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-27 10:31:04.171   929   929 D BluetoothA2dp: Proxy object connected
09-27 10:31:04.171  3131  3918 D BluetoothPan: onBluetoothStateChange on: true
09-27 10:31:04.172  3131  3142 D BluetoothPbap: onBluetoothStateChange: up=true
09-27 10:31:04.173  5698  5698 D BluetoothA2dp: Proxy object connected
09-27 10:31:04.173  5906  5906 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-27 10:31:04.173  5906  5906 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-27 10:31:04.174  3810  3832 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 10:31:04.174  3131  3148 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-27 10:31:04.174  5906  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 10:31:04.175   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-27 10:31:04.176  3131  3981 D BluetoothA2dp: onBluetoothStateChange: up=true
09-27 10:31:04.176  5906  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 10:31:04.177  5906  5906 D ObexServerSockets: Succeed to create listening sockets 
09-27 10:31:04.177  5698  5711 D BluetoothMap: onBluetoothStateChange: up=true
09-27 10:31:04.177  3131  3131 D BluetoothA2dp: Proxy object connected
,09-27 10:31:04.177  5906  5906 D ObexServerSockets0: startAccept()
,09-27 10:31:04.178  5906  5906 D ObexServerSockets0: prepareForNewConnect()
,09-27 10:31:04.181  5906  5906 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-27 10:31:04.181  5698  5943 D BluetoothPan: onBluetoothStateChange on: true
09-27 10:31:04.181  5906  5906 D BluetoothSdpJni: SDP Create record success - handle: 0
09-27 10:31:04.181  5906  5944 D ObexServerSockets0: Accepting socket connection...
09-27 10:31:04.181  5906  5945 D ObexServerSockets0: Accepting socket connection...
09-27 10:31:04.182  3131  3131 D BluetoothPan: BluetoothPAN Proxy object connected
09-27 10:31:04.182  3131  3131 D PanProfile: Bluetooth service connected
,09-27 10:31:04.183  5698  5711 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-27 10:31:04.183  3131  3131 D BluetoothInputDevice: Proxy object connected
,09-27 10:31:04.183  3131  3131 D HidProfile: Bluetooth service connected
09-27 10:31:04.185  5698  5698 D BluetoothMap: Proxy object connected
09-27 10:31:04.185  5698  5698 D MapProfile: Bluetooth service connected
09-27 10:31:04.185  5698  5698 D BluetoothMap: getConnectedDevices()
09-27 10:31:04.185   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-27 10:31:04.187  5906  5906 D BluetoothMapService: onReceive
09-27 10:31:04.187  5906  5906 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-27 10:31:04.187  5906  5906 D BluetoothMapService: STATE_ON
,09-27 10:31:04.188  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:04.190  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:04.190  5698  5698 D BluetoothPan: BluetoothPAN Proxy object connected
,09-27 10:31:04.190  5698  5698 D PanProfile: Bluetooth service connected
09-27 10:31:04.190  5698  5698 D BluetoothInputDevice: Proxy object connected
09-27 10:31:04.190  5698  5698 D HidProfile: Bluetooth service connected
,09-27 10:31:04.191  5906  5946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 10:31:04.193  5906  5946 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-27 10:31:04.193  5906  5946 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-27 10:31:04.195  5698  5698 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-27 10:31:04.198  5698  5698 D DockEventReceiver: finishStartingService: stopping service
,09-27 10:31:04.204  3581  3581 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-27 10:31:04.209  3131  3131 D BluetoothPbap: Proxy object connected
,09-27 10:31:04.210  3131  3131 D PbapServerProfile: Bluetooth service connected
,09-27 10:31:04.211  5698  5698 D BluetoothPbap: Proxy object connected
,09-27 10:31:04.211  5698  5698 D PbapServerProfile: Bluetooth service connected
,09-27 10:31:04.216  5906  5906 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-27 10:31:04.216  5906  5906 D ObexServerSockets0: prepareForNewConnect()
,09-27 10:31:04.217  5906  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 10:31:04.229  5906  5955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-27 10:31:04.230  5906  5955 I BtOppRfcommListener: Accept thread started.
,09-27 10:31:04.265   929   929 D BluetoothHeadset: Proxy object connected
,09-27 10:31:04.265  3131  3981 D BluetoothHeadset: Proxy object connected
09-27 10:31:04.265   929   946 D BluetoothHeadset: Proxy object connected
09-27 10:31:04.265  3131  3131 D HeadsetProfile: Bluetooth service connected
,09-27 10:31:04.266  5698  5943 D BluetoothHeadset: Proxy object connected
,09-27 10:31:04.266   929   929 D BluetoothHeadset: Proxy object connected
09-27 10:31:04.266  3810  4039 D BluetoothHeadset: Proxy object connected
09-27 10:31:04.267   929   929 D BluetoothHeadset: Proxy object connected
09-27 10:31:04.269  5698  5709 D BluetoothHeadset: Proxy object connected
09-27 10:31:04.269  5698  5698 D HeadsetProfile: Bluetooth service connected
09-27 10:31:04.270  5698  5698 D HeadsetProfile: Bluetooth service connected
09-27 10:31:04.271   929   946 D BluetoothHeadset: Proxy object connected
,09-27 10:31:04.274  3810  4034 D BluetoothHeadset: Proxy object connected
,09-27 10:31:04.276   929   946 D BluetoothHeadset: Proxy object connected
,09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:31:08.072  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 10:31:08.078  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:31:08.078  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:31:08.079  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3343bb1 removed from the list
09-27 10:31:08.079  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:31:08.079  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:08.079  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:08.081  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:31:08.081  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3538896 added. We now have 4 listener(s)
,09-27 10:31:08.081  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:31:08.085   929   939 D WifiService: setWifiEnabled: false pid=5644, uid=10077
,09-27 10:31:08.085   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 10:31:09.812   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:10.813   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:11.814   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:12.815   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:13.093  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:13.094   929  3876 D WifiService: setWifiEnabled: true pid=5644, uid=10077
,09-27 10:31:13.095   929  3876 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-27 10:31:13.103   509   920 D SoftapController: Softap fwReload - Ok
,09-27 10:31:13.109   509   920 D CommandListener: Setting iface cfg
09-27 10:31:13.109   509   920 D CommandListener: Trying to bring down wlan0
,09-27 10:31:13.111   509   920 D CommandListener: Clearing all IP addresses on wlan0
,09-27 10:31:13.116   929  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-27 10:31:13.772   929  2976 D wifi    : set interface wlan0 flags (UP)
,09-27 10:31:13.774   929  2976 I WifiHAL : Initializing wifi
09-27 10:31:13.775   929  2976 I WifiHAL : Creating socket
,09-27 10:31:13.782   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-27 10:31:13.785   929  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-27 10:31:13.785   929  2976 D wifi    : Did set static halHandle = 0x7f8ab25f80
09-27 10:31:13.785   929  2976 D wifi    : halHandle = 0x7f8ab25f80, mVM = 0x7fa5f8d140, mCls = 0x15aa
09-27 10:31:13.785   929  2976 D wifi    : array field set
09-27 10:31:13.785   929  2976 I WifiNative-HAL: interface[0] = wlan0
09-27 10:31:13.788   929  5960 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547787792256
09-27 10:31:13.788   929  5960 D wifi    : waitForHalEvents called, vm = 0x7fa5f8d140, obj = 0x15aa, env = 0x7f9c172f00
,09-27 10:31:13.816   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:13.843  5961  5961 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-27 10:31:13.864  5961  5961 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 10:31:13.889   929  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-27 10:31:13.902  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:13.904  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:13.912  5961  5961 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-27 10:31:13.912  5961  5961 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-27 10:31:13.927   929  2976 D WifiConfigStore: Loading config and enabling all networks 
,09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:31:13.933  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-27 10:31:13.935  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-27 10:31:13.939  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-27 10:31:13.940   929  2976 D WifiConfigStore: loaded 0 passpoint configs
09-27 10:31:13.941   929  2976 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-27 10:31:13.941   929  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-27 10:31:13.942   929  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-27 10:31:13.942  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-27 10:31:13.943   929  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-27 10:31:13.944   929  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-27 10:31:13.944   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-27 10:31:13.944   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-27 10:31:13.948   929  2976 D WifiNative-HAL: Setting external_sim to 1
,09-27 10:31:13.948  5021  5021 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-27 10:31:13.948   929  2976 D wifi    : setting dfs flag to true, 0x7f8aea68e0
09-27 10:31:13.949   929  2976 D WifiStateMachine: Setting OUI to DA-A1-19
09-27 10:31:13.949   929  2976 D wifi    : setting scan oui 0x7f8aea68e0
,09-27 10:31:13.949   929  2976 D WifiHAL : Sending mac address OUI
,09-27 10:31:13.953   929  2976 E native  : do suspend false
,09-27 10:31:13.962   929  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-27 10:31:13.962   929   929 D RttService: SCAN_AVAILABLE : 3
09-27 10:31:13.962   509   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-27 10:31:13.962   929  3084 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-27 10:31:13.963   509   920 D CommandListener: Setting iface cfg
,09-27 10:31:13.967   929  2975 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-27 10:31:13.967   929  2975 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-27 10:31:13.972   929  2975 D WifiNative-HAL: p2pGetDeviceAddress
09-27 10:31:13.973   929  2975 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-27 10:31:14.002   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302626 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=34 mControllerEnergyUsed=129 }
,09-27 10:31:14.817   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-27 10:31:17.151  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:31:17.155  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:31:17.160  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:31:17.166  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:31:17.228   929  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-27 10:31:17.228   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-27 10:31:17.229   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 10:31:17.240   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-27 10:31:17.273   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-27 10:31:17.275  5961  5961 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-27 10:31:17.699  5961  5961 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-27 10:31:17.733  5961  5961 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-27 10:31:17.734  5961  5961 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-27 10:31:17.746   929  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 10:31:17.747   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 10:31:17.747   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-27 10:31:17.762   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-27 10:31:17.775   509   920 D CommandListener: Setting iface cfg
,09-27 10:31:17.781   929  2976 D WifiStateMachine: Start Dhcp Watchdog 3
,09-27 10:31:17.788   929  5966 D DhcpClient: Receive thread started
,09-27 10:31:17.791   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:31:17.792   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-27 10:31:17.792   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-27 10:31:17.873   929  2976 E native  : do suspend false
,09-27 10:31:17.884   929  5965 D DhcpClient: Broadcasting DHCPDISCOVER
,09-27 10:31:17.904   929  5966 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-27 10:31:17.905   929  5965 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
09-27 10:31:17.907   929  5965 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-27 10:31:17.918   929  5966 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-27 10:31:17.919   929  5965 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-27 10:31:17.923   509   920 D CommandListener: Setting iface cfg
,09-27 10:31:17.928   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-27 10:31:17.934   929  5965 D DhcpClient: Scheduling renewal in 86399s
,09-27 10:31:17.947   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-27 10:31:17.947   929  2976 D WifiConfigStore: No blacklist allowed without epno enabled
09-27 10:31:17.948   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-27 10:31:17.950   929  2978 D ConnectivityService: Adding iface wlan0 to network 102
09-27 10:31:17.955   929  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-27 10:31:18.002   929  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-27 10:31:18.002   929  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-27 10:31:18.004   929  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-27 10:31:18.006   929  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-27 10:31:18.008   929  2978 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-27 10:31:18.019   929  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:31:18.024   929  2978 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-27 10:31:18.024   929  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-27 10:31:18.024   929  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-27 10:31:18.024   929  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-27 10:31:18.024   929  2978 D ConnectivityService:    accepting network in place of null
09-27 10:31:18.024   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-27 10:31:18.025   929  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-27 10:31:18.032   929  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306655, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-27 10:31:18.049   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 10:31:18.070   509   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-27 10:31:18.073   929  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-27 10:31:18.073  3779  3913 W QCNEJ   : |CORE| network available: 102
09-27 10:31:18.073   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-27 10:31:18.074   929  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-27 10:31:18.075   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-27 10:31:18.079  3779  3913 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-27 10:31:18.080  3779  3913 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-27 10:31:18.080  3779  3913 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:18.085  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:31:18.087  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:31:18.089  5046  5070 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-27 10:31:18.089  5046  5070 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-27 10:31:18.089  5046  5070 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-27 10:31:18.091  5046  5070 E SarControlService: no key has been found,reset the power
09-27 10:31:18.091  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-27 10:31:18.092  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:18.092  5644  5644 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:31:18.092  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-27 10:31:18.092  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 10:31:18.092  5071  5071 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-27 10:31:18.094  5644  5644 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:31:18.095  5046  5082 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-27 10:31:18.095  5046  5082 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-27 10:31:18.095  5046  5082 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-27 10:31:18.096  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-27 10:31:18.096  5071  5071 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-27 10:31:18.098  3732  3732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-27 10:31:18.101   929  5963 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-27 10:31:18.101  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000f003000000000000ffffffff]
09-27 10:31:18.101  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 10:31:18.101  5071  5085 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-27 10:31:18.101  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@67ae57 HexData = [00000000f103000000000000ffffffff]
09-27 10:31:18.102  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-27 10:31:18.102  5071  5085 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-27 10:31:18.102  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:31:18.103  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-27 10:31:18.104  3732  3732 D SystemUpdateService: onCreate
09-27 10:31:18.105  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-27 10:31:18.105  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:18.107  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:31:18.108  3732  3732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-27 10:31:18.109  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:31:18.110  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:18.110  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3538896 removed from the list
09-27 10:31:18.110  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:31:18.110  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:18.110  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:18.113  5644  5977 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-27 10:31:18.113  5644  5977 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 10:31:18.119  3732  3732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-27 10:31:18.124  3732  5404 I iu.UploadsManager: num queued entries: 0
,09-27 10:31:18.124  3732  5404 I iu.UploadsManager: num updated entries: 0
09-27 10:31:18.125  3732  5404 I iu.SyncManager: NEXT; no task
,09-27 10:31:18.129  3732  3732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-27 10:31:18.130  3732  3732 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-27 10:31:18.132  5764  5764 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-27 10:31:18.135  5764  5764 D SprintDMHelper: simOperator: 
09-27 10:31:18.135  5764  5764 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-27 10:31:18.136  3732  5976 I SystemUpdateService: active receiver: enabled
,09-27 10:31:18.153   929  5963 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 27 Sep 2016 14:31:18 GMT], X-Android-Received-Millis=[1474986678152], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474986678127]}
,09-27 10:31:18.154   929  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-27 10:31:18.154   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-27 10:31:18.154   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:31:18.155   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-27 10:31:18.156  3732  5976 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-27 10:31:18.171  3732  5976 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-27 10:31:18.171  3732  5976 I SystemUpdateService: now status is 0 (complete)
09-27 10:31:18.171  3732  5976 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-27 10:31:18.171  3732  5976 I SystemUpdateService: file has been verified
09-27 10:31:18.171  3732  5976 I SystemUpdateService: OTA package size = 21989297
,09-27 10:31:18.177  3732  5976 I SystemUpdateService: showing system update notification
,09-27 10:31:18.187  3732  3732 D SystemUpdateService: onDestroy
,09-27 10:31:18.256  5021  5982 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-27 10:31:20.815   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:31:21.124  5644  5977 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-27 10:31:21.125  5644  5977 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 10:31:21.126  5644  5977 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 10:31:21.127  5644  5977 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 10:31:21.127  5644  5989 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-27 10:31:21.127  5644  5989 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 10:31:21.127  5644  5977 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 10:31:21.128  5644  5989 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 10:31:21.131  5644  5991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender)
,09-27 10:31:21.131  5644  5989 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 10:31:21.133  5644  5989 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-27 10:31:21.133  5644  5992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Receiver)
,09-27 10:31:21.136  5644  5992 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 158, thread name: OutgoingSocketThread/Receiver)
09-27 10:31:21.136  5644  5992 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 10:31:21.136  5644  5992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-27 10:31:21.137  5644  5993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Sender)
,09-27 10:31:21.139  5644  5994 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: IncomingSocketThread/Receiver)
,09-27 10:31:21.140  5644  5994 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: IncomingSocketThread/Receiver)
09-27 10:31:21.141  5644  5994 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 10:31:21.141  5644  5994 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-27 10:31:23.842   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:31:24.121  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-27 10:31:24.122  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-27 10:31:24.128  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@18a736b Bundle[{}]
,09-27 10:31:24.130  5644  5690 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-27 10:31:24.131  5644  5690 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-27 10:31:24.133  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-27 10:31:24.134  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-27 10:31:24.135  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-27 10:31:24.136  5644  5690 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-27 10:31:24.142  5644  5690 I System.out: Running OutgoingSocketThread
,09-27 10:31:24.144  5644  5996 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-27 10:31:24.144  5644  5996 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-27 10:31:26.026   929  2978 D ConnectivityService: handlePromptUnvalidated 102
,09-27 10:31:27.156  5644  5996 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-27 10:31:27.156  5644  5996 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-27 10:31:27.157  5644  5997 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-27 10:31:27.157  5644  5996 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 10:31:27.157  5644  5997 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-27 10:31:27.157  5644  5997 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 10:31:27.158  5644  5997 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 10:31:27.158  5644  5996 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-27 10:31:27.161  5644  5999 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender)
,09-27 10:31:27.163  5644  5997 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-27 10:31:27.163  5644  5996 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-27 10:31:27.165  5644  6000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender)
,09-27 10:31:27.169  5644  6002 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Receiver)
,09-27 10:31:27.170  5644  6001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver)
09-27 10:31:27.170  5644  6002 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: OutgoingSocketThread/Receiver)
09-27 10:31:27.170  5644  6002 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-27 10:31:27.170  5644  6002 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-27 10:31:27.172  5644  6001 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver)
09-27 10:31:27.172  5644  6001 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-27 10:31:27.172  5644  6001 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-27 10:31:29.003   929  2976 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-27 10:31:30.153  5644  5690 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-27 10:31:30.155  5644  5690 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-27 10:31:30.155  5644  5690 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-27 10:31:30.162  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-27 10:31:30.162  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8330c17 added. We now have 3 listener(s)
,09-27 10:31:30.165  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 10:31:30.166  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 10:31:30.166  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 10:31:30.168  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:31:30.169  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c355804 added. We now have 4 listener(s)
,09-27 10:31:30.169  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 10:31:30.170  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 10:31:30.175  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:30.182  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:31:30.184  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:31:30.185  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:31:30.185  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:31:30.185  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:31:30.185  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:31:30.185  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:30.185  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:30.186  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:30.186  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 10:31:30.186  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8330c17 removed from the list
09-27 10:31:30.186  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:31:30.186  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c355804 removed from the list
09-27 10:31:30.188  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:30.190  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:30.190  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:31:30.190  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:30.191  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:31:30.191  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:30.193  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:30.193  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:30.193  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:30.193  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c355804 not in the list
09-27 10:31:30.193  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:30.193  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:30.194  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:30.194  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:30.194  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:30.195  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c355804 not in the list
09-27 10:31:30.195  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:30.195  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:30.195  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:30.195  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8330c17 not in the list
09-27 10:31:30.196  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 10:31:30.196  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7379822 added. We now have 3 listener(s)
,09-27 10:31:30.197  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 10:31:30.198  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-27 10:31:30.198  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 10:31:30.198  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:31:30.198  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5252b3 added. We now have 4 listener(s)
09-27 10:31:30.198  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:31:30.199  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 10:31:30.202  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:30.207  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-27 10:31:30.208  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:30.208  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 10:31:30.209  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 10:31:30.209  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 10:31:30.209  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 10:31:30.209  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:30.209  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 10:31:30.212  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:30.213  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:31:30.213  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:31:30.215  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:30.218  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 10:31:30.218  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:31:30.218  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 10:31:30.221  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-27 10:31:30.221  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-27 10:31:30.221  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 10:31:30.222  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:31:30.224  5906  5947 D BtGatt.GattService: registerClient() - UUID=c10b3f11-d6ea-449f-817b-a9fbfe88ad97
09-27 10:31:30.225  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=c10b3f11-d6ea-449f-817b-a9fbfe88ad97, clientIf=5
,09-27 10:31:30.226  5644  5743 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-27 10:31:30.227  5906  5916 D BtGatt.GattService: start scan with filters
,09-27 10:31:30.231  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-27 10:31:30.231  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-27 10:31:30.231  5906  5925 D BtGatt.ScanManager: handling starting scan
09-27 10:31:30.231  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 10:31:30.231  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 10:31:30.233  5906  5925 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1cba0dc
,09-27 10:31:30.233  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:31:30.234  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 10:31:30.234  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:31:30.235  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 10:31:30.237  5644  5690 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-27 10:31:30.238  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 10:31:30.238  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-27 10:31:30.238  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:30.238  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 10:31:30.238  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 10:31:30.238  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 10:31:30.238  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 10:31:30.238  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 10:31:30.238  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 10:31:30.238  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-27 10:31:30.239  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:31:30.240  5906  5947 D BtGatt.GattService: stopScan() - queue size =1
09-27 10:31:30.241  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 10:31:30.241  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:30.241  5906  5916 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 10:31:30.241  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:30.241  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-27 10:31:30.241  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-27 10:31:30.241  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-27 10:31:30.241  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 10:31:30.241  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 10:31:30.243  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:31:30.243  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:31:30.243  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 10:31:30.243  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:30.243  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 10:31:30.246  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:31:30.246  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:30.246  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 10:31:30.249  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 10:31:30.249  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:31:30.250  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
09-27 10:31:30.250  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-27 10:31:30.250  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:31:30.250  5644  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:31:30.254  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 10:31:30.254  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:31:30.255  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 10:31:30.255  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:30.255  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:30.257  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:31:30.257  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:30.257  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:31:30.260  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:31:30.260  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:30.260  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:30.260  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-27 10:31:30.260  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:30.262  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-27 10:31:30.265  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-27 10:31:30.265  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:31:30.272  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-27 10:31:30.272  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:30.272  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
,09-27 10:31:30.278  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-27 10:31:30.278  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:30.279  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-27 10:31:30.284  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-27 10:31:30.284  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:31:30.763  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 10:31:30.764  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:31:30.764  5644  5644 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 10:31:33.246  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:31:33.247  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:31:33.247  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:31:33.247  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 10:31:33.247  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:33.247  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:33.248  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 10:31:33.248  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7379822 removed from the list
09-27 10:31:33.248  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:31:33.248  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5252b3 removed from the list
09-27 10:31:33.248  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:31:33.249  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:33.250  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:33.251  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:33.255  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:33.255  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 10:31:33.256  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:33.257  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:31:33.258  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:31:33.258  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:33.258  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:31:33.258  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5252b3 not in the list
09-27 10:31:33.258  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:33.258  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:33.261  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:31:33.263  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:31:33.263  5644  5690 D BluetoothLeScanner: could not find callback wrapper
,09-27 10:31:33.263  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:33.263  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:33.263  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:31:33.263  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:31:33.264  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5252b3 not in the list
09-27 10:31:33.264  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:33.264  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:33.264  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:33.264  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7379822 not in the list
09-27 10:31:33.266  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 10:31:33.266  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92f5d88 added. We now have 3 listener(s)
,09-27 10:31:33.270  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 10:31:33.270  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 10:31:33.270  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 10:31:33.271  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:31:33.271  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6da7321 added. We now have 4 listener(s)
09-27 10:31:33.271  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-27 10:31:33.272  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 10:31:33.276  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:33.283  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:31:33.286  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-27 10:31:33.286  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:31:33.287  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 10:31:33.288  5644  5690 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-27 10:31:33.288  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-27 10:31:33.288  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 10:31:33.288  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-27 10:31:33.288  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-27 10:31:33.289  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:31:33.290  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-27 10:31:33.292  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:33.291  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-27 10:31:33.292  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-27 10:31:33.293  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-27 10:31:33.293  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-27 10:31:33.294  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:33.294  5644  6003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-27 10:31:33.294  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 10:31:33.293  5916  5916 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34181]" dev="sockfs" ino=34181 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 10:31:33.297  5644  6003 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-27 10:31:33.293  5916  5916 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34181]" dev="sockfs" ino=34181 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-27 10:31:33.299  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:33.299  5644  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-27 10:31:33.301  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:31:33.301  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:31:33.307  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 10:31:33.308  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:31:33.308  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 10:31:33.311  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-27 10:31:33.311  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 10:31:33.312  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-27 10:31:33.313  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-27 10:31:33.313  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-27 10:31:33.313  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-27 10:31:33.315  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:31:33.320  5906  5942 D BtGatt.GattService: registerClient() - UUID=ee673897-504b-4f98-9bbf-07cc2d962d31
09-27 10:31:33.320  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=ee673897-504b-4f98-9bbf-07cc2d962d31, clientIf=5
,09-27 10:31:33.321  5644  5655 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-27 10:31:33.323  5906  5924 D BtGatt.AdvertiseManager: message : 0
,09-27 10:31:33.326  5906  5924 D BtGatt.AdvertiseManager: starting multi advertising
,09-27 10:31:33.339  5906  5922 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-27 10:31:33.346  5906  5922 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-27 10:31:33.347  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-27 10:31:33.348  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-27 10:31:33.349  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-27 10:31:33.351  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-27 10:31:33.351  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-27 10:31:33.351  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-27 10:31:33.351  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-27 10:31:33.351  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-27 10:31:33.352  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-27 10:31:33.353  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-27 10:31:33.355  5644  5644 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 10:31:33.355  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-27 10:31:33.857  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-27 10:31:33.857  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 10:31:33.857  5644  5644 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 10:31:36.355  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-27 10:31:36.355  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-27 10:31:36.355  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 10:31:36.355  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-27 10:31:36.356  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-27 10:31:36.356  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-27 10:31:36.357  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-27 10:31:36.357  5644  6003 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-27 10:31:36.357  5644  5690 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-27 10:31:36.357  5644  6003 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-27 10:31:36.357  5644  6003 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-27 10:31:36.357  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 10:31:36.357  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 10:31:36.357  5644  5644 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-27 10:31:36.357  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 10:31:36.357  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 10:31:36.358  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-27 10:31:36.360  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:31:36.360  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:31:36.360  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:36.361  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-27 10:31:36.363  5906  5924 D BtGatt.AdvertiseManager: message : 1
,09-27 10:31:36.364  5906  5924 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-27 10:31:36.378  5906  5922 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-27 10:31:36.378  5906  5922 D BtGatt.GattService: Client app is not null!
09-27 10:31:36.379  5906  5917 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-27 10:31:36.380  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:31:36.380  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-27 10:31:36.380  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-27 10:31:36.380  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-27 10:31:36.380  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-27 10:31:36.382  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:31:36.382  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 10:31:36.382  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-27 10:31:36.386  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 10:31:36.388  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-27 10:31:36.389  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:36.389  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:36.389  5644  5644 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-27 10:31:36.389  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 10:31:36.389  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:31:36.389  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:36.389  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92f5d88 removed from the list
09-27 10:31:36.389  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:31:36.389  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:36.389  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6da7321 removed from the list
09-27 10:31:36.390  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:31:36.390  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-27 10:31:36.394  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 10:31:36.394  5644  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:31:36.400  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 10:31:36.401  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:31:36.401  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 10:31:36.402  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:36.402  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:36.405  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:31:36.405  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:36.406  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 10:31:36.407  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:31:36.407  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:36.407  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:31:36.408  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:31:36.408  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:36.408  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:36.408  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:31:36.408  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6da7321 not in the list
,09-27 10:31:36.408  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:36.408  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-27 10:31:36.412  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 10:31:36.412  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:36.413  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:36.415  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:31:36.415  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:36.415  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:36.417  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:36.418  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:31:36.418  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:31:36.418  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:36.418  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-27 10:31:36.418  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:31:36.418  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:36.418  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6da7321 not in the list
09-27 10:31:36.418  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:36.418  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:36.419  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:36.419  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92f5d88 not in the list
,09-27 10:31:36.420  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 10:31:36.420  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b751e added. We now have 3 listener(s)
,09-27 10:31:36.422  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-27 10:31:36.422  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 10:31:36.422  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 10:31:36.423  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:31:36.423  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a431ff added. We now have 4 listener(s)
09-27 10:31:36.423  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:31:36.424  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-27 10:31:36.427  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:36.433  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:31:36.435  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:36.435  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-27 10:31:36.436  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 10:31:36.436  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-27 10:31:36.436  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-27 10:31:36.436  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:36.436  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:31:36.439  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:36.442  5644  5690 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:31:36.442  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-27 10:31:36.444  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-27 10:31:36.448  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-27 10:31:36.449  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:31:36.449  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-27 10:31:36.454  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-27 10:31:36.455  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-27 10:31:36.455  5644  5690 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-27 10:31:36.456  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:31:36.458  5906  5916 D BtGatt.GattService: registerClient() - UUID=36ac6425-bc8a-4d06-bb31-6c3c208dcedd
09-27 10:31:36.459  5906  5922 D BtGatt.GattService: onClientRegistered() - UUID=36ac6425-bc8a-4d06-bb31-6c3c208dcedd, clientIf=5
,09-27 10:31:36.459  5644  5743 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-27 10:31:36.460  5906  5947 D BtGatt.GattService: start scan with filters
09-27 10:31:36.463  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-27 10:31:36.463  5906  5925 D BtGatt.ScanManager: handling starting scan
,09-27 10:31:36.463  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-27 10:31:36.463  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-27 10:31:36.463  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-27 10:31:36.466  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:31:36.466  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-27 10:31:36.466  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-27 10:31:36.468  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-27 10:31:36.470  5906  5922 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-27 10:31:36.470  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:36.471  5906  5925 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-27 10:31:36.478  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-27 10:31:36.478  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:36.478  5906  5925 D BtGatt.ScanManager: Starting BLE batch scan
09-27 10:31:36.478  5906  5925 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-27 10:31:36.490  5906  5922 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-27 10:31:36.491  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:31:36.497  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-27 10:31:36.498  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:31:36.916  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 10:31:36.966  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-27 10:31:36.967  5644  5644 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-27 10:31:36.967  5644  5644 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-27 10:31:39.478  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-27 10:31:39.479  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-27 10:31:39.479  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-27 10:31:39.479  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.479  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-27 10:31:39.479  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-27 10:31:39.480  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-27 10:31:39.480  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-27 10:31:39.480  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-27 10:31:39.480  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-27 10:31:39.480  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-27 10:31:39.483  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:31:39.485  5906  5917 D BtGatt.GattService: stopScan() - queue size =1
09-27 10:31:39.488  5906  5942 D BtGatt.GattService: unregisterClient() - clientIf=5
09-27 10:31:39.489  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:39.490  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-27 10:31:39.490  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-27 10:31:39.490  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-27 10:31:39.490  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-27 10:31:39.494  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:31:39.494  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:31:39.494  5644  5690 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-27 10:31:39.495  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:39.496  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:39.500  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:39.498  5906  5906 D BtGatt.ScanManager: awakened up at time 328122
09-27 10:31:39.500  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-27 10:31:39.501  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.501  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:39.501  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-27 10:31:39.501  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b751e removed from the list
09-27 10:31:39.503  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:31:39.503  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a431ff removed from the list
09-27 10:31:39.503  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:31:39.501  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:39.505  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:31:39.505  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:39.507  5906  5922 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-27 10:31:39.508  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:39.508  5906  5925 D BtGatt.ScanManager: stopping BLe Batch
,09-27 10:31:39.511  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-27 10:31:39.511  5644  5644 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-27 10:31:39.517  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-27 10:31:39.518  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-27 10:31:39.518  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-27 10:31:39.518  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:39.519  5906  5922 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-27 10:31:39.519  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:39.519  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-27 10:31:39.519  5906  5925 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-27 10:31:39.521  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.522  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:39.523  5644  5644 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-27 10:31:39.523  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:39.524  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-27 10:31:39.527  5644  5644 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-27 10:31:39.527  5644  5644 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-27 10:31:39.528  5644  5644 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:39.530  5644  5644 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-27 10:31:39.531  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:39.531  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-27 10:31:39.531  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-27 10:31:39.532  5644  5690 D BluetoothAdapter: STATE_ON
,09-27 10:31:39.532  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:31:39.532  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:39.532  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:39.532  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a431ff not in the list
09-27 10:31:39.532  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.532  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:39.534  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:39.535  5644  5690 D BluetoothAdapter: STATE_ON
09-27 10:31:39.535  5644  5690 D BluetoothLeScanner: could not find callback wrapper
09-27 10:31:39.535  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-27 10:31:39.535  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:39.535  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-27 10:31:39.535  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:39.536  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a431ff not in the list
09-27 10:31:39.536  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:39.536  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.536  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:39.536  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26b751e not in the list
09-27 10:31:39.537  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-27 10:31:39.537  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a52864 added. We now have 3 listener(s)
09-27 10:31:39.538  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-27 10:31:39.539  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-27 10:31:39.539  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-27 10:31:39.539  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-27 10:31:39.539  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f8dacd added. We now have 4 listener(s)
09-27 10:31:39.540  5644  5690 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-27 10:31:39.540  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-27 10:31:39.543  5906  5922 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-27 10:31:39.543  5906  5922 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-27 10:31:39.543  5906  5922 D BtGatt.GattService: current time is 328167507917
09-27 10:31:39.544  5906  5922 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -73, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -79, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -89, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-27 10:31:39.545  5906  5922 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-27 10:31:39.545  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-27 10:31:39.547  5906  5922 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-27 10:31:39.547  5906  5922 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-27 10:31:39.547  5906  5922 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-27 10:31:39.547  5906  5922 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-27 10:31:39.547  5906  5922 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-27 10:31:39.550  5644  5690 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-27 10:31:39.552  5644  5690 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-27 10:31:39.552  5644  5690 D io.jxcore.node.ConnectivityMonitor: start: OK
09-27 10:31:39.552  5644  5690 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-27 10:31:39.552  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-27 10:31:39.552  5644  5690 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-27 10:31:39.552  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:39.552  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.552  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-27 10:31:39.552  5644  5690 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-27 10:31:39.553  5644  5690 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a52864 removed from the list
09-27 10:31:39.553  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-27 10:31:39.553  5644  5690 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f8dacd removed from the list
09-27 10:31:39.554  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:39.554  5644  5690 D io.jxcore.node.ConnectivityMonitor: stop
09-27 10:31:39.554  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-27 10:31:39.555  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-27 10:31:39.555  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:39.556  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:39.556  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:39.556  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:39.556  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f8dacd not in the list
,09-27 10:31:39.556  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.556  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:39.557  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-27 10:31:39.557  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-27 10:31:39.558  5644  5690 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-27 10:31:39.558  5644  5690 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f8dacd not in the list
09-27 10:31:39.558  5644  5690 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-27 10:31:39.558  5644  5690 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-27 10:31:39.558  5644  5690 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-27 10:31:39.558  5644  5644 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-27 10:31:39.558  5644  5690 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a52864 not in the list
09-27 10:31:39.559  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-27 10:31:39.559  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-27 10:31:39.559  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-27 10:31:39.559  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-27 10:31:39.559  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-27 10:31:39.559  5644  5690 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-27 10:31:39.817   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-27 10:31:39.817   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 10:31:40.031  5644  5644 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-27 10:31:41.571  5644  6004 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-27 10:31:43.570  5644  5690 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 191
,09-27 10:31:43.570  5644  5690 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 191, name: My test thread name)
09-27 10:31:43.575  5644  6005 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 192, name: My test thread name)
09-27 10:31:43.575  5644  6005 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 192, thread name: My test thread name)
,09-27 10:31:43.575  5644  6005 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 192, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-27 10:31:43.580  5644  5690 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-27 10:31:43.586  5644  6006 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name)
09-27 10:31:43.587  5644  6006 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 196, thread name: My test thread name): Test exception.
09-27 10:31:43.587  5644  6006 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-27 10:31:43.597  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
09-27 10:31:43.597  5644  5690 I jxcore-log: 
,09-27 10:31:43.599  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-27 10:31:43.599  5644  5690 I jxcore-log: 
09-27 10:31:43.600  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'Number of failed tests:  0'
09-27 10:31:43.600  5644  5690 I jxcore-log: 
09-27 10:31:43.601  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-27 10:31:43.601  5644  5690 I jxcore-log: 
,09-27 10:31:43.604  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'Total duration:  101046'
09-27 10:31:43.604  5644  5690 I jxcore-log: 
,09-27 10:31:43.614  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-27 10:31:43.614  5644  5690 I jxcore-log: 
,09-27 10:31:43.624  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.624  5644  5690 I jxcore-log: 
,09-27 10:31:43.628  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.628  5644  5690 I jxcore-log: 
,09-27 10:31:43.629  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.629  5644  5690 I jxcore-log: 
09-27 10:31:43.630  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.630  5644  5690 I jxcore-log: 
09-27 10:31:43.632  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 10:31:43.632  5644  5690 I jxcore-log: 
09-27 10:31:43.632  5644  5644 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-27 10:31:43.634  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 10:31:43.634  5644  5690 I jxcore-log: 
09-27 10:31:43.635  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.635  5644  5690 I jxcore-log: 
09-27 10:31:43.635  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.635  5644  5690 I jxcore-log: 
,09-27 10:31:43.636  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 10:31:43.636  5644  5690 I jxcore-log: 
,09-27 10:31:43.637  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 10:31:43.637  5644  5690 I jxcore-log: 
09-27 10:31:43.638  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 10:31:43.638  5644  5690 I jxcore-log: 
09-27 10:31:43.639  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.639  5644  5690 I jxcore-log: 
,09-27 10:31:43.641  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.641  5644  5690 I jxcore-log: 
09-27 10:31:43.642  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.642  5644  5690 I jxcore-log: 
,09-27 10:31:43.643  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.643  5644  5690 I jxcore-log: 
,09-27 10:31:43.644  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.644  5644  5690 I jxcore-log: 
09-27 10:31:43.646  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.646  5644  5690 I jxcore-log: 
,09-27 10:31:43.647  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.647  5644  5690 I jxcore-log: 
09-27 10:31:43.648  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.648  5644  5690 I jxcore-log: 
09-27 10:31:43.649  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.649  5644  5690 I jxcore-log: 
,09-27 10:31:43.650  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.650  5644  5690 I jxcore-log: 
09-27 10:31:43.651  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.651  5644  5690 I jxcore-log: 
09-27 10:31:43.652  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.652  5644  5690 I jxcore-log: 
,09-27 10:31:43.656  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.656  5644  5690 I jxcore-log: 
,09-27 10:31:43.658  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.658  5644  5690 I jxcore-log: 
09-27 10:31:43.659  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.659  5644  5690 I jxcore-log: 
,09-27 10:31:43.660  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.660  5644  5690 I jxcore-log: 
,09-27 10:31:43.661  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.661  5644  5690 I jxcore-log: 
09-27 10:31:43.661  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.661  5644  5690 I jxcore-log: 
09-27 10:31:43.662  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.662  5644  5690 I jxcore-log: 
,09-27 10:31:43.663  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.663  5644  5690 I jxcore-log: 
09-27 10:31:43.664  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.664  5644  5690 I jxcore-log: 
,09-27 10:31:43.665  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.665  5644  5690 I jxcore-log: 
,09-27 10:31:43.666  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.666  5644  5690 I jxcore-log: 
,09-27 10:31:43.667  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.667  5644  5690 I jxcore-log: 
09-27 10:31:43.668  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.668  5644  5690 I jxcore-log: 
,09-27 10:31:43.669  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.669  5644  5690 I jxcore-log: 
09-27 10:31:43.670  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.670  5644  5690 I jxcore-log: 
,09-27 10:31:43.670  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-27 10:31:43.670  5644  5690 I jxcore-log: 
09-27 10:31:43.671  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.671  5644  5690 I jxcore-log: 
,09-27 10:31:43.672  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-27 10:31:43.672  5644  5690 I jxcore-log: 
09-27 10:31:43.673  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.673  5644  5690 I jxcore-log: 
09-27 10:31:43.673  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.673  5644  5690 I jxcore-log: 
,09-27 10:31:43.674  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.674  5644  5690 I jxcore-log: 
,09-27 10:31:43.675  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.675  5644  5690 I jxcore-log: 
09-27 10:31:43.675  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.675  5644  5690 I jxcore-log: 
09-27 10:31:43.676  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 10:31:43.676  5644  5690 I jxcore-log: 
,09-27 10:31:43.677  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.677  5644  5690 I jxcore-log: 
09-27 10:31:43.678  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
09-27 10:31:43.678  5644  5690 I jxcore-log: 
,09-27 10:31:43.678  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.678  5644  5690 I jxcore-log: 
09-27 10:31:43.679  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 10:31:43.679  5644  5690 I jxcore-log: 
,09-27 10:31:43.680  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-27 10:31:43.680  5644  5690 I jxcore-log: 
09-27 10:31:43.680  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-27 10:31:43.680  5644  5690 I jxcore-log: 
,09-27 10:31:43.681  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-27 10:31:43.681  5644  5690 I jxcore-log: 
,09-27 10:31:43.684  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-27 10:31:43.684  5644  5690 I jxcore-log: 
,09-27 10:31:43.685  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - WARN testUtils: 'myNameCallback not set!'
09-27 10:31:43.685  5644  5690 I jxcore-log: 
,09-27 10:31:43.686  5644  5690 I jxcore-log: 2016-09-27 14:31:43 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-27 10:31:43.686  5644  5690 I jxcore-log: 
,09-27 10:31:43.697  5644  6004 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-27 10:31:45.722  5644  5690 I jxcore-log: 2016-09-27 14:31:45 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-27 10:31:45.722  5644  5690 I jxcore-log: 
,09-27 10:31:46.042  5644  5690 I jxcore-log: 2016-09-27 14:31:46 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-27 10:31:46.042  5644  5690 I jxcore-log: 
,09-27 10:31:46.057  5644  5690 I jxcore-log: 2016-09-27 14:31:46 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-27 10:31:46.057  5644  5690 I jxcore-log: 
,09-27 10:31:47.159  5644  5690 I jxcore-log: 2016-09-27 14:31:47 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-27 10:31:47.159  5644  5690 I jxcore-log: 
,09-27 10:31:47.307  5644  5690 I jxcore-log: 2016-09-27 14:31:47 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-27 10:31:47.307  5644  5690 I jxcore-log: 
,09-27 10:31:47.312  5644  5690 I jxcore-log: 2016-09-27 14:31:47 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-27 10:31:47.312  5644  5690 I jxcore-log: 
,09-27 10:31:47.316  5644  5690 I jxcore-log: 2016-09-27 14:31:47 - DEBUG runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-27 10:31:47.316  5644  5690 I jxcore-log: 
,09-27 10:31:47.326  5644  5690 I jxcore-log: 2016-09-27 14:31:47 - ERROR runTests: ''
09-27 10:31:47.326  5644  5690 I jxcore-log: 
,09-27 10:31:47.327  5644  5690 I jxcore-log: 2016-09-27 14:31:47 - ERROR UnitTest_app: ''
09-27 10:31:47.327  5644  5690 I jxcore-log: 
,09-27 10:31:52.194   929  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=340817, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-27 10:31:54.819   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:55.820   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:56.822   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:57.824   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:58.007   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:31:58.826   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:31:59.826   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 10:32:00.135   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:32:03.167   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:32:04.827   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:05.829   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:06.830   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:07.832   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:08.833   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:09.834   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 10:32:16.388   929  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=365011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-27 10:32:19.837   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:20.838   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:21.840   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:22.841   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:23.842   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:24.844   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 10:32:38.012   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:32:39.845   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:40.847   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:41.848   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:42.850   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:43.851   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:32:44.852   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 10:32:50.041   929  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=398664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-27 10:32:56.734   929  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=405357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-27 10:32:58.013   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:33:04.854   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:05.855   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:06.756   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:06.857   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:07.858   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:08.860   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:09.797   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:09.861   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-27 10:33:21.655  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-27 10:33:30.362   929  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=438985, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-27 10:33:30.995   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:34.021   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:34.862   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-27 10:33:34.862   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-27 10:33:37.056   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:38.017   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:33:40.093   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:43.125   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:46.165   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:33:54.864   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:55.865   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:56.866   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:57.868   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:58.019   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:33:58.869   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:33:59.870   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-27 10:34:04.872   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:05.873   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:06.875   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:07.876   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:08.878   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:09.879   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-27 10:34:13.451   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:34:16.486   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:34:18.021   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:34:19.881   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:20.883   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:21.884   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:22.886   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:23.888   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:24.889   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-27 10:34:39.890   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:40.892   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:41.893   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:42.895   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:43.896   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-27 10:34:44.897   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-27 10:34:55.866   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-27 10:34:58.027   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-27 10:34:58.898   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]

```
