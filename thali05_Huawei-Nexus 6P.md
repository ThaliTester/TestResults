#### Test 8727714588eb016_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-29 07:14:45.315   600   600 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-29 07:14:45.316   600   600 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 07:14:45.625   929  5442 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
09-29 07:14:45.790  5686  5686 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-29 07:14:45.795  5686  5686 D AndroidRuntime: CheckJNI is OFF
09-29 07:14:45.818  5686  5686 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-29 07:14:45.851  5686  5686 I Radio-JNI: register_android_hardware_Radio DONE
09-29 07:14:45.866  5686  5686 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-29 07:14:45.871   929  3933 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-29 07:14:45.915   929  3933 I ActivityManager: Start proc 5695:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-29 07:14:45.938  5686  5686 D AndroidRuntime: Shutting down VM
,09-29 07:14:46.251   929   940 I WindowManager: Screenshot max retries 4 of Token{2b0b020 ActivityRecord{4fa8323 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{bdb339b u0 Starting com.test.thalitest} drawState=2
,09-29 07:14:46.314  5695  5695 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-29 07:14:46.349  5695  5695 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-29 07:14:46.375  5695  5695 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 9527-9547)
,09-29 07:14:46.375  5695  5695 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-29 07:14:46.395  5695  5695 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a547934}
,09-29 07:14:46.395  5695  5695 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-29 07:14:46.396  5695  5695 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-29 07:14:46.400  5695  5695 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-29 07:14:46.402  5695  5695 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-29 07:14:46.436  5695  5695 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-29 07:14:46.452  5695  5695 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-29 07:14:46.453  5695  5695 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-29 07:14:46.453  5695  5695 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-29 07:14:46.453  5695  5695 I Adreno  : Build Date                       : 12/06/15
09-29 07:14:46.453  5695  5695 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-29 07:14:46.453  5695  5695 I Adreno  : Local Branch                     : mybranch17112971
09-29 07:14:46.453  5695  5695 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-29 07:14:46.453  5695  5695 I Adreno  : Remote Branch                    : NONE
09-29 07:14:46.453  5695  5695 I Adreno  : Reconstruct Branch               : NOTHING
,09-29 07:14:46.514   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20e204e:true
,09-29 07:14:46.548   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32069]" dev="sockfs" ino=32069 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 07:14:46.548   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32069]" dev="sockfs" ino=32069 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 07:14:46.565  5695  5695 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-29 07:14:46.575  5695  5695 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-29 07:14:46.601   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34377]" dev="sockfs" ino=34377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-29 07:14:46.601   406   406 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34377]" dev="sockfs" ino=34377 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-29 07:14:46.605  5695  5732 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-29 07:14:46.608  3683  3683 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[29768]" dev="sockfs" ino=29768 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 07:14:46.608  3683  3683 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[29768]" dev="sockfs" ino=29768 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-29 07:14:46.615  5695  5719 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-29 07:14:46.637  5695  5732 I OpenGLRenderer: Initialized EGL, version 1.4
,09-29 07:14:46.721   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +467ms (total +837ms)
,09-29 07:14:46.750  5695  5695 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5695
,09-29 07:14:46.844  5695  5695 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-29 07:14:47.027  5695  5735 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -582743760
,09-29 07:14:47.034  5695  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-29 07:14:47.034  5695  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-29 07:14:47.034  5695  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-29 07:14:47.034  5695  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-29 07:14:47.034  5695  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-29 07:14:47.034  5695  5735 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0e2ad5 added. We now have 1 listener(s)
,09-29 07:14:47.037  5695  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-29 07:14:47.037  5695  5735 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 07:14:47.038  5695  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:14:47.038  5695  5735 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-29 07:14:47.041  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-29 07:14:47.042  5695  5735 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97ddc78 added. We now have 1 listener(s)
09-29 07:14:47.042  5695  5735 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:14:47.054   929  3055 D WifiService: New client listening to asynchronous messages
09-29 07:14:47.055  5695  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 07:14:47.055  5695  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-29 07:14:47.055  5695  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-29 07:14:47.055  5695  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-29 07:14:47.055  5695  5735 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-29 07:14:47.058  5695  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:14:47.058  5695  5735 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-29 07:14:47.064  5695  5735 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:14:47.064  5695  5735 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:14:47.064  5695  5735 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-29 07:14:47.064  5695  5735 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:14:47.065  5695  5735 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-29 07:14:47.067  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:14:47.070  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:14:47.081  5695  5695 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-29 07:14:47.461  5695  5741 W jxcore-log: Initializing JXcore engine
09-29 07:14:47.461  5695  5741 W jxcore-log: JXcore engine is ready
,09-29 07:14:47.481  5741  5741 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12514 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-29 07:14:47.481  5741  5741 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12858]" dev="sockfs" ino=12858 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-29 07:14:47.481  5741  5741 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-29 07:14:47.481  5741  5741 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31587]" dev="sockfs" ino=31587 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-29 07:14:47.493  5695  5741 W jxcore-log: Starting JXcore engine
,09-29 07:14:47.497  5695  5704 I art     : Background sticky concurrent mark sweep GC freed 86250(8MB) AllocSpace objects, 18(1892KB) LOS objects, 24% free, 24MB/32MB, paused 2.419ms total 115.921ms
,09-29 07:14:47.542  5695  5741 W jxcore-log: Platform android
09-29 07:14:47.542  5695  5741 W jxcore-log: 
,09-29 07:14:47.542  5695  5741 W jxcore-log: Process ARCH arm
09-29 07:14:47.542  5695  5741 W jxcore-log: 
,09-29 07:14:47.648  5695  5741 I jxcore-log: JXcore Cordova bridge is ready!
09-29 07:14:47.648  5695  5741 I jxcore-log: 
,09-29 07:14:47.648  5695  5741 W jxcore-log: JXcore engine is started
,09-29 07:14:47.654  5695  5735 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-29 07:14:47.658  5695  5695 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-29 07:14:48.249   929  3054 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 07:14:55.317   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:14:56.318   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:14:57.319   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:14:57.511  5695  5741 I jxcore-log: 2016-09-29 11:14:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 07:14:57.511  5695  5741 I jxcore-log: 
,09-29 07:14:57.513  5695  5741 I jxcore-log: 2016-09-29 11:14:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 07:14:57.513  5695  5741 I jxcore-log: 
,09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:14:57.517  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:14:57.518  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:14:57.520  5695  5741 I jxcore-log: 2016-09-29 11:14:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 07:14:57.520  5695  5741 I jxcore-log: 
,09-29 07:14:57.521  5695  5741 I jxcore-log: 2016-09-29 11:14:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 07:14:57.521  5695  5741 I jxcore-log: 
,09-29 07:14:57.774  5695  5741 I jxcore-log: 2016-09-29 11:14:57 - DEBUG UnitTest_app: 'Running unit tests'
09-29 07:14:57.774  5695  5741 I jxcore-log: 
,09-29 07:14:57.774  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:14:57.774  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@802361e added. We now have 2 listener(s)
,09-29 07:14:57.775  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:14:57.775  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:14:57.775  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-29 07:14:57.775  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:14:57.775  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea25eff added. We now have 2 listener(s)
09-29 07:14:57.775  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:14:57.776  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 07:14:57.778  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:14:57.780  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:14:57.781  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:57.781  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:14:57.782  5695  5741 D executeNativeTests: Running unit tests
,09-29 07:14:57.789  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:14:57.795  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:14:57.818  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 07:14:57.818  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 added. We now have 3 listener(s)
09-29 07:14:57.819  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:14:57.819  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:14:57.819  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:14:57.819  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:14:57.819  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda added. We now have 3 listener(s)
09-29 07:14:57.819  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:14:57.819  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 07:14:57.821  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:14:57.823  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:14:57.824  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:57.824  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 07:14:57.825  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 07:14:57.825  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 07:14:57.825  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-29 07:14:57.825  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-29 07:14:57.826  5695  5741 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-29 07:14:57.826  5695  5741 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-29 07:14:57.826  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 07:14:57.826  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 07:14:57.826  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 07:14:57.826  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 07:14:57.827  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:14:57.827  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:14:57.827  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:14:57.828  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:14:57.828  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.828  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:14:57.828  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:14:57.828  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:14:57.828  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 removed from the list
09-29 07:14:57.828  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:14:57.828  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda removed from the list
,09-29 07:14:57.829  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:14:57.838  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:14:57.839  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:14:57.839  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:14:57.839  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.839  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:14:57.840  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:14:57.840  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:14:57.840  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:14:57.840  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:14:57.841  5695  5741 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-29 07:14:57.841  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:14:57.841  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:14:57.841  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:14:57.841  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:14:57.841  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.841  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:14:57.842  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:14:57.842  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:14:57.842  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:14:57.842  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:14:57.842  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:14:57.842  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.842  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:14:57.842  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.842  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:14:57.842  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:14:57.842  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:14:57.842  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:14:57.842  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 07:14:57.845  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 07:14:57.846  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:14:57.846  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:14:57.846  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:14:57.846  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:14:57.846  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.846  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:14:57.846  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:14:57.846  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:14:57.846  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:14:57.846  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:14:57.846  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:14:57.846  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.846  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:14:57.846  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:14:57.847  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:14:57.847  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:14:57.847  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:14:57.847  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:14:57.847  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:14:57.847  5695  5741 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-29 07:14:57.848  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:14:57.851  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:14:57.852  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:14:57.852  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:14:57.852  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:14:57.852  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 07:14:57.852  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 07:14:57.852  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:14:57.852  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 07:14:57.855  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:14:57.856  5695  5741 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 07:14:57.856  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 07:14:57.857  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:14:57.859  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 07:14:57.860  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 07:14:57.860  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-29 07:14:57.862  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-29 07:14:57.865  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-29 07:14:57.865  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 07:14:57.865  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 07:14:57.865  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 07:14:57.866  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 07:14:57.866  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 07:14:57.867  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:14:57.869  4686  4700 D BtGatt.GattService: registerClient() - UUID=f97ae380-3fb9-4fa9-906d-843f1e080cff
09-29 07:14:57.870  4686  4761 D BtGatt.GattService: onClientRegistered() - UUID=f97ae380-3fb9-4fa9-906d-843f1e080cff, clientIf=5
09-29 07:14:57.871  5695  5706 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 07:14:57.872  4686  4701 D BtGatt.GattService: start scan with filters
09-29 07:14:57.876  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 07:14:57.876  4686  4764 D BtGatt.ScanManager: handling starting scan
09-29 07:14:57.876  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 07:14:57.876  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:14:57.877  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 07:14:57.877  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 07:14:57.877  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 07:14:57.877  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 07:14:57.878  4686  4764 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:14:57.878  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:14:57.878  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 07:14:57.878  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:14:57.878  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 07:14:57.880  5695  5741 I io.jxcore.node.ConnectionHelper: start: OK
09-29 07:14:57.885  4686  4761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-29 07:14:57.885  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:14:57.886  4686  4764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 07:14:57.891  4686  4761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 07:14:57.891  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:14:57.892  4686  4764 D BtGatt.ScanManager: Starting BLE batch scan
09-29 07:14:57.892  4686  4764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 07:14:57.901  4686  4761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 07:14:57.901  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:14:57.907  4686  4761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 07:14:57.907  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:14:58.320   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:14:58.380  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-29 07:14:58.380  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:14:58.380  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 07:14:59.321   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:00.322   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-29 07:15:02.884  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:02.884  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:02.884  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 07:15:02.884  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:02.884  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 07:15:02.884  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:02.884  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 07:15:02.885  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 07:15:02.885  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 07:15:02.885  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 07:15:02.885  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 07:15:02.886  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 07:15:02.886  5695  5741 D BluetoothAdapter: STATE_ON
,09-29 07:15:02.887  4686  4910 D BtGatt.GattService: stopScan() - queue size =1
,09-29 07:15:02.889  4686  4700 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 07:15:02.892  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 07:15:02.893  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 07:15:02.893  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 07:15:02.894  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:15:02.894  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 07:15:02.895  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 07:15:02.895  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 07:15:02.895  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 07:15:02.896  4686  4686 D BtGatt.ScanManager: awakened up at time 236068
09-29 07:15:02.898  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:02.899  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 07:15:02.900  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-29 07:15:02.900  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 07:15:02.900  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 07:15:02.902  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:15:02.903  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:02.903  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:02.903  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:02.903  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:02.903  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:15:02.904  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:02.904  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:02.904  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
,09-29 07:15:02.904  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:02.904  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:02.904  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:02.904  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:02.904  4686  4761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 07:15:02.904  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:02.904  4686  4764 D BtGatt.ScanManager: stopping BLe Batch
,09-29 07:15:02.913  4686  4761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 07:15:02.913  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:02.913  4686  4764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 07:15:02.936  4686  4761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-29 07:15:02.936  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:02.936  4686  4761 D BtGatt.GattService: current time is 236108809412
09-29 07:15:02.937  4686  4761 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -76, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -79, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -71, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -73, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -9, -41, -38, 3, -84, 69, 1, -128, -87, 31, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0, 0, -43, -54, -6, -55, 22, -20, 1, -128, -95, 78, 0, 31, 2, 1, 4, 17, 6, -70, 86, -119, -90, -6, -65, -94, -67, 1, 70, 125, 110, 0, -5, -85, -83, 9, 22, 10, 24, 8, 4, 85, 14, 0, 0, 0]
09-29 07:15:02.938  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-29 07:15:02.939  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-29 07:15:02.939  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-29 07:15:02.939  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-29 07:15:02.939  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-29 07:15:02.940  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-29 07:15:02.940  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0]
09-29 07:15:02.940  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 4, 17, 6, -70, 86, -119, -90, -6, -65, -94, -67, 1, 70, 125, 110, 0, -5, -85, -83, 9, 22, 10, 24, 8, 4, 85, 14, 0, 0]
,09-29 07:15:03.405  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 07:15:05.323   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:06.325   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:07.326   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:07.906  5695  5741 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-29 07:15:07.911  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:07.923  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:15:07.928  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:15:07.929  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:15:07.929  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:15:07.929  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 07:15:07.929  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-29 07:15:07.930  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:15:07.930  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 07:15:07.936  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:07.938  5695  5741 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 07:15:07.939  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 07:15:07.944  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:07.948  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 07:15:07.949  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 07:15:07.949  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 07:15:07.955  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 07:15:07.955  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 07:15:07.955  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 07:15:07.955  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 07:15:07.955  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 07:15:07.956  5695  5741 D BluetoothAdapter: STATE_ON
,09-29 07:15:07.960  4686  4700 D BtGatt.GattService: registerClient() - UUID=feba0e47-9fd3-4d64-aa14-232addc527b4
09-29 07:15:07.961  4686  4761 D BtGatt.GattService: onClientRegistered() - UUID=feba0e47-9fd3-4d64-aa14-232addc527b4, clientIf=5
09-29 07:15:07.962  5695  5705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-29 07:15:07.962  4686  4910 D BtGatt.GattService: start scan with filters
,09-29 07:15:07.968  4686  4764 D BtGatt.ScanManager: handling starting scan
,09-29 07:15:07.968  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 07:15:07.968  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 07:15:07.968  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:15:07.968  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 07:15:07.968  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-29 07:15:07.968  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-29 07:15:07.969  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 07:15:07.973  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 07:15:07.973  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 07:15:07.974  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 07:15:07.976  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 07:15:07.979  4686  4761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-29 07:15:07.979  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:07.980  4686  4764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 07:15:07.981  5695  5741 I io.jxcore.node.ConnectionHelper: start: OK
09-29 07:15:07.985  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:15:07.985  5695  5741 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-29 07:15:07.985  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:07.985  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 07:15:07.985  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:07.985  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 07:15:07.985  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:07.985  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 07:15:07.985  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 07:15:07.985  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-29 07:15:07.985  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 07:15:07.986  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 07:15:07.986  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 07:15:07.986  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:15:07.987  4686  4701 D BtGatt.GattService: stopScan() - queue size =1
09-29 07:15:07.988  4686  4910 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 07:15:07.989  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-29 07:15:07.989  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 07:15:07.989  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 07:15:07.989  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:15:07.989  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 07:15:07.989  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 07:15:07.989  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 07:15:07.989  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 07:15:07.990  4686  4761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 07:15:07.990  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:07.990  4686  4764 D BtGatt.ScanManager: Starting BLE batch scan
09-29 07:15:07.990  4686  4764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-29 07:15:07.991  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:07.991  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-29 07:15:07.991  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 07:15:07.991  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 07:15:07.991  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 07:15:07.992  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:15:07.995  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:07.995  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:07.995  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:07.995  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:07.995  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:15:07.995  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:07.995  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:07.995  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:07.995  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:07.995  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:07.996  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:07.996  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:07.996  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:07.996  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:07.999  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:07.999  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:07.999  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:07.999  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:08.000  5695  5741 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-29 07:15:08.002  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:15:08.004  4686  4761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 07:15:08.004  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:08.009  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:15:08.011  4686  4761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-29 07:15:08.011  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:15:08.011  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:08.011  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:15:08.012  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:15:08.012  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 07:15:08.012  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 07:15:08.012  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:15:08.012  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-29 07:15:08.014  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:08.017  5695  5741 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-29 07:15:08.017  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 07:15:08.017  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:08.020  4686  4761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 07:15:08.020  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:08.020  4686  4764 D BtGatt.ScanManager: stopping BLe Batch
09-29 07:15:08.021  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-29 07:15:08.022  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 07:15:08.022  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 07:15:08.025  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 07:15:08.025  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 07:15:08.025  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 07:15:08.025  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 07:15:08.025  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 07:15:08.026  4686  4761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 07:15:08.026  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:08.026  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:15:08.026  4686  4764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 07:15:08.028  4686  4700 D BtGatt.GattService: registerClient() - UUID=32441cd3-4eb5-4dbf-a869-28c8afb477cc
,09-29 07:15:08.029  4686  4761 D BtGatt.GattService: onClientRegistered() - UUID=32441cd3-4eb5-4dbf-a869-28c8afb477cc, clientIf=5
09-29 07:15:08.029  5695  5706 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 07:15:08.030  4686  4701 D BtGatt.GattService: start scan with filters
,09-29 07:15:08.032  4686  4761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-29 07:15:08.032  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:15:08.034  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 07:15:08.034  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 07:15:08.034  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:15:08.034  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-29 07:15:08.034  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 07:15:08.034  4686  4764 D BtGatt.ScanManager: handling starting scan
,09-29 07:15:08.034  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 07:15:08.034  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 07:15:08.036  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:15:08.037  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 07:15:08.037  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:15:08.038  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 07:15:08.040  5695  5741 I io.jxcore.node.ConnectionHelper: start: OK
09-29 07:15:08.041  4686  4761 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 07:15:08.041  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:08.041  4686  4764 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-29 07:15:08.046  4686  4761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-29 07:15:08.046  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:08.046  4686  4764 D BtGatt.ScanManager: Starting BLE batch scan
09-29 07:15:08.046  4686  4764 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-29 07:15:08.055  4686  4761 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-29 07:15:08.056  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:15:08.061  4686  4761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 07:15:08.061  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:15:08.328   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:08.538  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-29 07:15:08.538  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:15:08.539  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 07:15:09.329   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:10.329   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 07:15:13.041  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:15:13.041  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:13.041  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-29 07:15:13.041  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:15:13.041  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 07:15:13.041  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:13.042  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 07:15:13.042  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 07:15:13.042  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 07:15:13.042  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 07:15:13.042  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 07:15:13.042  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 07:15:13.044  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:15:13.045  4686  4701 D BtGatt.GattService: stopScan() - queue size =1
09-29 07:15:13.047  4686  4700 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 07:15:13.047  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 07:15:13.047  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 07:15:13.048  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 07:15:13.048  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:15:13.048  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 07:15:13.048  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 07:15:13.048  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 07:15:13.048  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-29 07:15:13.051  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:13.051  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 07:15:13.051  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 07:15:13.052  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 07:15:13.052  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 07:15:13.053  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:15:13.053  4686  4686 D BtGatt.ScanManager: awakened up at time 246225
09-29 07:15:13.056  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:13.056  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:13.056  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:13.060  4686  4761 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 07:15:13.060  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:13.060  4686  4764 D BtGatt.ScanManager: stopping BLe Batch
,09-29 07:15:13.069  4686  4761 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 07:15:13.070  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:13.070  4686  4764 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 07:15:13.096  4686  4761 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-29 07:15:13.096  4686  4761 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:15:13.096  4686  4761 D BtGatt.GattService: current time is 246269273927
09-29 07:15:13.097  4686  4761 D BtGatt.GattService: Batch record : [-43, -54, -6, -55, 22, -20, 1, -6, -96, 99, 0, 31, 2, 1, 4, 17, 6, -70, 86, -119, -90, -6, -65, -94, -67, 1, 70, 125, 110, 0, -5, -85, -83, 9, 22, 10, 24, 8, 4, 85, 14, 0, 0, 11, 7, 9, 67, 104, 97, 114, 103, 101, 2, 10, -6, 81, 34, 97, 112, -14, -5, 1, -128, -76, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -9, -41, -38, 3, -84, 69, 1, -128, -93, 38, 0, 11, 2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0, 0, 37, -47, 14, -113, 116, -46, 1, -128, -73, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -79, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -77, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -77, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-29 07:15:13.097  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 4, 17, 6, -70, 86, -119, -90, -6, -65, -94, -67, 1, 70, 125, 110, 0, -5, -85, -83, 9, 22, 10, 24, 8, 4, 85, 14, 0, 0, 7, 9, 67, 104, 97, 114, 103, 101, 2, 10, -6]
09-29 07:15:13.097  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-29 07:15:13.098  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 26, 7, -1, 76, 0, 16, 2, 10, 0]
09-29 07:15:13.098  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-29 07:15:13.098  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-29 07:15:13.098  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-29 07:15:13.098  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-29 07:15:13.099  4686  4761 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-29 07:15:13.557  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 07:15:13.558  5695  5695 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:13.558  5695  5695 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-29 07:15:18.057  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:15:18.057  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 07:15:18.057  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.057  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.058  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:15:18.058  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:15:18.058  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.058  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
,09-29 07:15:18.058  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.058  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:18.058  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.059  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:18.060  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.060  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.062  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 07:15:18.062  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.062  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.063  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:18.064  5695  5741 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-29 07:15:18.066  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.066  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 07:15:18.066  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.066  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 07:15:18.066  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.067  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.067  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.067  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
,09-29 07:15:18.067  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.067  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.067  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.068  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.068  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.068  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.068  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.070  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 07:15:18.071  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.071  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.071  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.073  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-29 07:15:18.073  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.074  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.074  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.075  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.075  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.075  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.075  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.075  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.075  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:18.075  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.075  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.075  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.076  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.076  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.076  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.077  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:18.077  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 07:15:18.077  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.077  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.078  5695  5741 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-29 07:15:18.078  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.079  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.079  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.079  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.079  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.079  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:18.079  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.079  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.079  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.079  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.079  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.079  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.080  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:18.080  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.080  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.082  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 07:15:18.082  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.082  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.083  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:18.085  5695  5741 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-29 07:15:18.085  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.085  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.085  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.085  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.085  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.085  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.085  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.086  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.086  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:18.086  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.086  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.086  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.086  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.086  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.086  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:18.087  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:18.088  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.088  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.088  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.089  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 07:15:18.089  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 07:15:18.089  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-29 07:15:18.089  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 07:15:18.089  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 07:15:18.089  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 07:15:18.089  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-29 07:15:18.090  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 07:15:18.090  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-29 07:15:18.090  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:15:18.090  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.090  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.090  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.090  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.090  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.090  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.090  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.090  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:18.090  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.091  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.091  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.091  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.091  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.091  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.092  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:18.095  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.096  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:18.098  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:18.101  5695  5741 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-29 07:15:18.101  5695  5741 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 07:15:18.101  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-29 07:15:18.106  5695  5741 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-29 07:15:18.107  5695  5741 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-29 07:15:18.107  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-29 07:15:18.108  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-29 07:15:18.109  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-29 07:15:18.109  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-29 07:15:18.109  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-29 07:15:18.109  5695  5741 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-29 07:15:18.110  5695  5741 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 07:15:18.110  5695  5741 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,09-29 07:15:18.110  5695  5741 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 07:15:18.110  5695  5741 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 07:15:18.110  5695  5741 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-29 07:15:18.110  5695  5741 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 07:15:18.110  5695  5741 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-29 07:15:18.110  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-29 07:15:18.115  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-29 07:15:18.116  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-29 07:15:18.116  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-29 07:15:18.116  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-29 07:15:18.116  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-29 07:15:18.116  5695  5741 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-29 07:15:18.117  5695  5741 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-29 07:15:18.117  5695  5741 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-29 07:15:18.117  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-29 07:15:18.117  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,09-29 07:15:18.118  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.118  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.118  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.118  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.118  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.118  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.118  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.118  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-29 07:15:18.118  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-29 07:15:18.118  5695  5742 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-29 07:15:18.119  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.119  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.119  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.119  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 07:15:18.119  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.119  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.119  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.119  5695  5743 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-29 07:15:18.119  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:18.120  5695  5742 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-29 07:15:18.121  5695  5742 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 07:15:18.121  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:18.121  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.121  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.121  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.122  5695  5741 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-29 07:15:18.123  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.123  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.123  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 07:15:18.123  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 07:15:18.123  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.118  4700  4700 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34413]" dev="sockfs" ino=34413 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 07:15:18.123  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.123  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.123  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.123  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.124  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.124  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.124  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.124  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:18.124  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.124  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.121  4700  4700 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34413]" dev="sockfs" ino=34413 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-29 07:15:18.125  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:18.125  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.125  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:18.125  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.126  5695  5741 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-29 07:15:18.126  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.126  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.126  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.126  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.126  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.126  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.127  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.127  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.127  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.127  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:18.127  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.127  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.127  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.127  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.127  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:18.128  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:18.128  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.128  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.128  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.129  5695  5741 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-29 07:15:18.129  5695  5741 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-29 07:15:18.129  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 07:15:18.129  5695  5741 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-29 07:15:18.129  5695  5741 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 07:15:18.129  5695  5741 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-29 07:15:18.129  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 07:15:18.129  5695  5741 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-29 07:15:18.129  5695  5741 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-29 07:15:18.129  5695  5741 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-29 07:15:18.129  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-29 07:15:18.129  5695  5741 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-29 07:15:18.130  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:18.130  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:18.130  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:18.130  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.130  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:15:18.130  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.130  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.130  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.130  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.130  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.130  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.130  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.130  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.130  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.130  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.131  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 07:15:18.131  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:18.131  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.131  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:18.132  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:18.132  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.132  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:18.133  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:18.133  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:18.133  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:18.133  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:18.133  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:18.133  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:18.133  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:20.196   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 07:15:20.331   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:21.332   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:22.333   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:22.664   929  5442 D NetlinkSocketObserver: NeighborEvent{elapsedMs=255837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-29 07:15:23.134  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:23.134  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:23.134  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:23.135  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.135  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.135  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:23.135  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
,09-29 07:15:23.135  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:15:23.136  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 07:15:23.136  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:23.136  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:23.136  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.136  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.136  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:23.137  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
,09-29 07:15:23.137  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.137  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.137  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:23.137  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.137  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.138  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.138  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.141  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:23.141  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:23.141  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.141  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.145  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-29 07:15:23.146  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:15:23.148  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-29 07:15:23.150  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-29 07:15:23.151  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-29 07:15:23.151  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-29 07:15:23.151  5695  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-29 07:15:23.152  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-29 07:15:23.152  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-29 07:15:23.152  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 07:15:23.153  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-29 07:15:23.153  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-29 07:15:23.153  5695  5744 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 07:15:23.153  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-29 07:15:23.154  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-29 07:15:23.154  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.154  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-29 07:15:23.154  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-29 07:15:23.154  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:23.154  5695  5695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-29 07:15:23.155  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.155  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 07:15:23.155  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 07:15:23.155  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 07:15:23.155  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:15:23.155  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.155  4700  4700 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34416]" dev="sockfs" ino=34416 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 07:15:23.158  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:23.159  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.159  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:23.159  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:23.159  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:15:23.159  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-29 07:15:23.159  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:15:23.159  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:23.159  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:23.159  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.160  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.160  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-29 07:15:23.160  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:23.160  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.160  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.160  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:23.160  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.161  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.161  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.161  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.165  4700  4700 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34416]" dev="sockfs" ino=34416 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-29 07:15:23.163  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:23.164  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:23.164  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:23.164  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.167  5695  5741 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-29 07:15:23.167  5695  5744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-29 07:15:23.167  5695  5741 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-29 07:15:23.167  5695  5744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-29 07:15:23.167  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-29 07:15:23.168  5695  5744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-29 07:15:23.168  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 07:15:23.168  5695  5741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-29 07:15:23.168  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:23.168  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-29 07:15:23.168  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:23.168  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 07:15:23.168  5695  5695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:23.168  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:23.168  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.169  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.169  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:23.169  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
,09-29 07:15:23.169  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.169  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.169  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:23.169  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.169  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.169  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.169  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.174  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:23.175  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:23.175  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.175  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
,09-29 07:15:23.182  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:15:23.182  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:23.182  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:15:23.182  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:23.182  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.182  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.182  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 07:15:23.182  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:23.183  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.183  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.183  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:23.183  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.183  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.183  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.183  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.184  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 07:15:23.185  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:15:23.185  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.185  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.186  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:15:23.186  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:15:23.186  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 07:15:23.186  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:15:23.186  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.186  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.187  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:15:23.187  5695  5741 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1d4b85 not in the list
09-29 07:15:23.187  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:23.187  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.187  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:23.187  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.187  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:23.187  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:23.187  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:23.189  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:15:23.190  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 07:15:23.190  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:23.190  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@659ddda not in the list
09-29 07:15:23.191  5695  5741 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-29 07:15:23.191  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 07:15:23.192  5695  5741 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-29 07:15:23.192  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-29 07:15:23.192  5695  5741 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-29 07:15:23.192  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-29 07:15:23.195  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-29 07:15:23.195  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-29 07:15:23.196  5695  5741 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-29 07:15:23.197  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 07:15:23.197  5695  5741 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-29 07:15:23.197  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-29 07:15:23.197  5695  5741 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-29 07:15:23.198  5695  5741 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-29 07:15:23.198  5695  5741 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-29 07:15:23.199  5695  5741 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-29 07:15:23.199  5695  5741 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-29 07:15:23.199  5695  5741 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-29 07:15:23.199  5695  5741 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-29 07:15:23.199  5695  5741 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-29 07:15:23.200  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:15:23.201  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ec292c added. We now have 3 listener(s)
09-29 07:15:23.201  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:15:23.203  5695  5741 D BluetoothAdapter: enable(): BT is already enabled..!
09-29 07:15:23.204   929  3902 D WifiService: setWifiEnabled: true pid=5695, uid=10077
09-29 07:15:23.204   929  3902 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 07:15:23.213   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-29 07:15:23.250  4686  4890 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-29 07:15:23.251  4686  4906 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-29 07:15:23.251  5695  5742 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
09-29 07:15:23.251  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-29 07:15:23.251  5695  5742 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,09-29 07:15:23.334   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:23.660  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 07:15:24.335   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:25.335   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 07:15:28.210  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 07:15:28.210  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b211ff5 added. We now have 4 listener(s)
,09-29 07:15:28.210  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:15:28.223  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:28.223  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b211ff5 removed from the list
09-29 07:15:28.223  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:28.224  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:28.224  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:28.226  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:15:28.226  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@155718a added. We now have 4 listener(s)
09-29 07:15:28.226  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:15:28.229  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:28.229  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@155718a removed from the list
09-29 07:15:28.229  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:28.230  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:28.230  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:28.231  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:15:28.231  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b593fb added. We now have 4 listener(s)
09-29 07:15:28.231  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:15:28.235   929  3683 D WifiService: setWifiEnabled: false pid=5695, uid=10077
09-29 07:15:28.236   929  3683 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 07:15:28.242   929  3054 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-29 07:15:28.243   929  3054 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-29 07:15:28.243   929  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 07:15:28.243   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-29 07:15:28.251  4686  4757 D BluetoothAdapterState: Current state: ON, message: 23
,09-29 07:15:28.251  4686  4757 D BluetoothAdapterProperties: Setting state to 13
,09-29 07:15:28.251  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:15:28.251  4686  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-29 07:15:28.253  4686  4757 D BluetoothAdapterProperties: onBluetoothDisable()
09-29 07:15:28.255  4686  4757 I BluetoothAdapterState: Entering PendingCommandState
09-29 07:15:28.256  4686  4761 D BluetoothAdapterProperties: Scan Mode:20
09-29 07:15:28.257  4686  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-29 07:15:28.258  4686  4686 D BluetoothMapService: onReceive
09-29 07:15:28.258  4686  4686 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-29 07:15:28.258   508   928 D CommandListener: Clearing all IP addresses on wlan0
,09-29 07:15:28.258  4686  4686 D BluetoothMapService: STATE_TURNING_OFF
09-29 07:15:28.258  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:28.259  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:28.259  4686  4686 D BluetoothMapService: MAP Service closeService in
09-29 07:15:28.259  4686  4686 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 07:15:28.259   929  5443 D DhcpClient: Clearing IP address
09-29 07:15:28.259  4686  4686 D ObexServerSockets0: shutdown(block = true)
09-29 07:15:28.259  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.259  4686  4686 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 07:15:28.259  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:15:28.259  4686  4686 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 07:15:28.260  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:15:28.261  4686  4921 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-29 07:15:28.261  4686  4922 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-29 07:15:28.261  4686  4906 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-29 07:15:28.263  4686  4686 I BtOppRfcommListener: stopping Accept Thread
09-29 07:15:28.264  4686  5374 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-29 07:15:28.265  4686  5374 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-29 07:15:28.265  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.267   508   928 D CommandListener: Setting iface cfg
09-29 07:15:28.268  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:28.271  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:28.271  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:28.272  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.272  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:28.273  3690  5497 V NativeCrypto: Read error: ssl=0x7f93fbc800: I/O error during system call, Connection timed out
,09-29 07:15:28.274  3690  5497 V NativeCrypto: SSL shutdown failed: ssl=0x7f93fbc800: I/O error during system call, Broken pipe
,09-29 07:15:28.276  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:28.276  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:28.276   929  3683 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-29 07:15:28.277   929  5441 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-29 07:15:28.277  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.277  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:28.278   929  5441 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-29 07:15:28.279   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-29 07:15:28.279   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-29 07:15:28.280  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.280   929  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-29 07:15:28.283  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:28.283  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:28.283  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.283  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:28.286  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:28.286  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:28.287  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.287  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:15:28.288   929   942 I ActivityManager: Start proc 5749:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-29 07:15:28.290  4686  4686 D HeadsetService: Received stop request...Stopping profile...
09-29 07:15:28.291   929  5444 D DhcpClient: Receive thread stopped
09-29 07:15:28.293   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-29 07:15:28.293   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-29 07:15:28.293  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:28.293  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:28.293   598   598 E Parcel  : Reading a NULL string not supported here.
09-29 07:15:28.294   929   929 D BluetoothHeadset: Proxy object disconnected
,09-29 07:15:28.294   929   929 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:28.295  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.295  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:28.295  3221  3236 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:28.295   929   929 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:28.296  3891  3911 D BluetoothHeadset: Proxy object disconnected
,09-29 07:15:28.298   929  3056 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-29 07:15:28.300  3840  3975 W QCNEJ   : |CORE| network lost: 100
09-29 07:15:28.300   929   929 D RttService: SCAN_AVAILABLE : 1
,09-29 07:15:28.300  3840  3975 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-29 07:15:28.300   929  3162 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 07:15:28.301  4686  4686 D A2dpService: Received stop request...Stopping profile...
09-29 07:15:28.303  4686  4914 D A2dpStateMachine: Exit Disconnected: -1
,09-29 07:15:28.304   929   929 D BluetoothA2dp: Proxy object disconnected
09-29 07:15:28.304  4686  4686 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:28.306  4686  4686 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:28.306  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:28.306  4686  4686 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:28.306  4686  4686 D HidService: Received stop request...Stopping profile...
09-29 07:15:28.306  4686  4686 D HidService: Stopping Bluetooth HidService
09-29 07:15:28.307   929  3054 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-29 07:15:28.309  3221  3221 D HeadsetProfile: Bluetooth service disconnected
09-29 07:15:28.309  4686  4686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-29 07:15:28.309  4686  4686 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 07:15:28.309  4686  4890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:28.309  4686  4890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:28.309  4686  4890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:28.309  4686  4686 D HealthService: Received stop request...Stopping profile...
09-29 07:15:28.310  4686  4686 D PanService: Received stop request...Stopping profile...
09-29 07:15:28.311  4686  4761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 07:15:28.311  4686  4761 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-29 07:15:28.312  4686  4686 D BluetoothMapService: Received stop request...Stopping profile...
09-29 07:15:28.312  4686  4686 D BluetoothMapService: stop()
09-29 07:15:28.312  4686  4686 D BluetoothMapAppObserver: deinitObservers()
09-29 07:15:28.312  4686  4686 D BluetoothMapAppObserver: removeReceiver()
09-29 07:15:28.314  4686  4686 D SapService: Received stop request...Stopping profile...
09-29 07:15:28.314  4686  4686 V SapService: stop()
,09-29 07:15:28.315  4686  4686 V BluetoothAdapterState: isTurningOff()=true
,09-29 07:15:28.315  4686  4686 V BluetoothAdapterState: isTurningOn()=false
,09-29 07:15:28.315  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:28.315  4686  4686 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:28.317  4686  4686 V BluetoothAdapterState: isTurningOff()=true
,09-29 07:15:28.317  4686  4686 V BluetoothAdapterState: isTurningOn()=false
,09-29 07:15:28.317  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 07:15:28.317  4686  4686 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:28.316  3221  3221 D BluetoothA2dp: Proxy object disconnected
,09-29 07:15:28.317   929  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 07:15:28.317  4686  4686 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 07:15:28.317  3221  3221 D BluetoothInputDevice: Proxy object disconnected
09-29 07:15:28.317  4686  4686 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 07:15:28.317  3221  3221 D HidProfile: Bluetooth service disconnected
09-29 07:15:28.317  4686  4761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 07:15:28.317  4686  4890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-29 07:15:28.317  4686  4761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 07:15:28.317  4686  4890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:28.318  4686  4890 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 07:15:28.318  4686  4890 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 07:15:28.318  4686  4890 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-29 07:15:28.318  4686  4890 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 07:15:28.318  4686  4686 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:28.318  4686  4686 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:28.318  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:28.318  4686  4686 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:28.318  3221  3221 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 07:15:28.318  3221  3221 D PanProfile: Bluetooth service disconnected
09-29 07:15:28.318  4686  4686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 07:15:28.318  3221  3221 D BluetoothMap: Proxy object disconnected
09-29 07:15:28.318  3221  3221 D MapProfile: Bluetooth service disconnected
09-29 07:15:28.319  4686  4686 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:28.319  4686  4686 D BluetoothMapService: MAP Service closeService in
09-29 07:15:28.319  4686  4761 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:28.319  4686  4686 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:28.320  4686  4686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 07:15:28.320  4686  4686 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-29 07:15:28.321  4686  4686 D BluetoothMapService: cleanup()
09-29 07:15:28.321  4686  4686 D BluetoothMapService: MAP Service closeService in
,09-29 07:15:28.321  4686  4686 V BluetoothAdapterState: isTurningOff()=true
,09-29 07:15:28.321  4686  4686 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:28.321  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:28.321  4686  4686 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:28.322  4686  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 07:15:28.322  4686  4757 D BluetoothAdapterProperties: Setting state to 15
09-29 07:15:28.322  4686  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 07:15:28.323   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 07:15:28.323  4686  4757 I BluetoothAdapterState: Entering BleOnState
09-29 07:15:28.323  3221  3234 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:28.323   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:28.324  3221  3236 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 07:15:28.324  3221  3447 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 07:15:28.325   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:28.325  3221  3234 D BluetoothMap: onBluetoothStateChange: up=false
09-29 07:15:28.326  3221  3236 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 07:15:28.326  3891  4107 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:28.326   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-29 07:15:28.327   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:28.327  3221  3447 D BluetoothPan: onBluetoothStateChange on: false
09-29 07:15:28.328  4686  4757 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 07:15:28.328  4686  4757 D BluetoothAdapterProperties: Setting state to 16
09-29 07:15:28.328  4686  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 07:15:28.329  4686  4757 D BluetoothAdapterProperties: onBleDisable
09-29 07:15:28.329  4686  4757 I BluetoothAdapterState: Entering PendingCommandState
09-29 07:15:28.329  4686  4758 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-29 07:15:28.330  4686  4890 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 07:15:28.330  4686  4890 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:28.332  4686  4761 D BluetoothAdapterProperties: Scan Mode:20
,09-29 07:15:28.334  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:28.334  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:15:28.337  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:28.338  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:28.340  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:28.340  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:28.341  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.343  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:28.344  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:28.351   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 07:15:28.351   508   928 D CommandListener: Clearing all IP addresses on wlan0
09-29 07:15:28.351   508   928 D TetherController: Setting IP forward enable = 0
09-29 07:15:28.352   929  3056 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-29 07:15:28.352   929  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-29 07:15:28.354   929  3054 D DhcpClient: doQuit
,09-29 07:15:28.355   929  3054 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 07:15:28.355   929  5443 D DhcpClient: onQuitting
,09-29 07:15:28.355  3557  3557 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-29 07:15:28.356   929   946 D Tethering: MasterInitialState.processMessage what=3
09-29 07:15:28.358  5359  5359 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@be54160 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-29 07:15:28.359  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:28.360  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:28.360  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.360  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:28.364  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:28.364  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:15:28.366  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:28.366  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:15:28.369  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:28.369  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:28.369  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:28.369  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:28.371  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.372  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.373  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.376  5112  5129 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 07:15:28.376  5112  5129 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 07:15:28.376  5112  5129 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-29 07:15:28.376  5112  5129 E SarControlService: no key has been found,reset the power
09-29 07:15:28.376  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 07:15:28.376  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 07:15:28.376  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 07:15:28.377  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:15:28.377  5139  5139 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 07:15:28.379  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 07:15:28.379  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 07:15:28.379  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 07:15:28.379  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:15:28.379  5139  5139 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 07:15:28.380  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000ea03000000000000ffffffff]
09-29 07:15:28.380  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 07:15:28.380  5139  5153 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-29 07:15:28.381  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 07:15:28.381  5112  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 07:15:28.385  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000eb03000000000000ffffffff]
09-29 07:15:28.385  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 07:15:28.385  5139  5153 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-29 07:15:28.385  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 07:15:28.386  5112  5123 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 07:15:28.386  5749  5749 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-29 07:15:28.387  3557  3557 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-29 07:15:28.392  3557  3557 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-29 07:15:28.399  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 07:15:28.404   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8328b36:true
09-29 07:15:28.405  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 07:15:28.412   508   928 E Netd    : netlink response contains error (No such file or directory)
09-29 07:15:28.413   508   928 D TetherController: Setting IP forward enable = 0
09-29 07:15:28.413   929  3056 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-29 07:15:28.413   929  3056 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 07:15:28.422  3557  3557 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-29 07:15:28.426   929  3254 I ActivityManager: Start proc 5780:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-29 07:15:28.431  3557  3557 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 07:15:28.447  5749  5749 D LocalBluetoothProfileManager: Adding local MAP profile
09-29 07:15:28.450  5749  5749 D BluetoothMap: Create BluetoothMap proxy object
,09-29 07:15:28.466  5780  5780 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-29 07:15:28.467  5749  5749 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-29 07:15:28.478  5749  5749 D DockEventReceiver: finishStartingService: stopping service
,09-29 07:15:28.489   929  3902 I ActivityManager: Killing 5076:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-29 07:15:28.533   929  3054 D wifi    : In wifi stop Hal
,09-29 07:15:28.533  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 07:15:28.533   929  3054 D wifi    : halHandle = 0x7f7db27400, mVM = 0x7f9a10d140, mCls = 0x100a02
,09-29 07:15:28.534   929  3556 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 07:15:28.534   929  3556 D WifiHAL : Got a signal to exit!!!
09-29 07:15:28.534   929  3556 I WifiHAL : Exit wifi_event_loop
09-29 07:15:28.534   929  3054 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-29 07:15:28.534   929  3054 E WifiHAL : Event processing terminated
,09-29 07:15:28.534   929  3054 D wifi    : In wifi cleaned up handler
,09-29 07:15:28.534   929  3054 I WifiHAL : Internal cleanup completed
09-29 07:15:28.536  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.536  3979  4293 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 07:15:28.538  4686  4761 I bt_hci  : shut_down
09-29 07:15:28.538  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:28.540  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:28.541  4686  4765 I bt_vendor: low_power_mode_cb
,09-29 07:15:28.544  4686  4765 D bt_hwcfg: hw_epilog_process
,09-29 07:15:28.547  4686  4765 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-29 07:15:28.547  4686  4765 I bt_vendor: epilog_cb
,09-29 07:15:28.547  4686  4765 I bt_hci  : epilog_finished_callback
,09-29 07:15:28.549  4686  4761 I bt_hci_h4: hal_close
,09-29 07:15:28.549  4686  4761 I bt_userial_vendor: device fd = 54 close
,09-29 07:15:28.552   929  3556 D wifi    : set interface wlan0 flags (DOWN)
,09-29 07:15:28.553   929  3054 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 07:15:28.652  4686  4758 D bt_stack_manager: event_shut_down_stack finished.
,09-29 07:15:28.652  4686  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-29 07:15:28.654  4686  4757 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-29 07:15:28.654  4686  4686 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 07:15:28.655  4686  4686 D BtGatt.GattService: Received stop request...Stopping profile...
,09-29 07:15:28.655  4686  4686 D BtGatt.GattService: stop()
09-29 07:15:28.655  4686  4686 D BtGatt.AdvertiseManager: advertise clients cleared
09-29 07:15:28.656  5780  5780 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.656  5780  5780 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 07:15:28.656  5780  5780 D ,StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.656  5780  5780 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.656  5780 , 5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.656  4686  4686 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:28.656  4686  4686 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:28.656  5780  5780 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.656  4686  4686 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:28.656  4686  4686 V BluetoothAdapterState: isBleTurningOff()=true
09-29 07:15:28.656  5780  5780 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.k.d(PG:583)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.e.b(PG:170)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.656  5780  5780 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.656  4686  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 07:15:28.656  5780  5780 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.io.File.exists(File.java:361)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.656  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.657  4686  4757 D BluetoothAdapterProperties: Setting state to 10
09-29 07:15:28.657  5780  5780 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-29 07:15:28.657  5780  5780 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-29 07:15:28.657  4686  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 07:15:28.658   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-29 07:15:28.658  4686  4757 I BluetoothAdapterState: Entering OffState
09-29 07:15:28.663  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 07:15:28.668  4686  4686 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-29 07:15:28.668  4686  4686 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 07:15:28.668  4686  4686 I BluetoothServiceJni: cleanupNative: return from cleanup
09-29 07:15:28.669  4686  4758 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-29 07:15:28.679  4686  4686 I art     : System.exit called, status: 0
09-29 07:15:28.679  4686  4686 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-29 07:15:28.692  5749  5749 D DockEventReceiver: finishStartingService: stopping service
09-29 07:15:28.694   929  3902 I ActivityManager: Killing 5471:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-29 07:15:28.732   929  3683 I ActivityManager: Process com.android.bluetooth (pid 4686) has died
09-29 07:15:28.734  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 07:15:28.746   929  3723 I ActivityManager: Start proc 5814:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-29 07:15:28.756   929   946 D Tethering: InitialState.processMessage what=4
,09-29 07:15:28.760   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 07:15:28.828  5814  5814 D AdapterServiceConfig: Adding HeadsetService
,09-29 07:15:28.829  5814  5814 D AdapterServiceConfig: Adding A2dpService
09-29 07:15:28.829  5814  5814 D AdapterServiceConfig: Adding HidService
09-29 07:15:28.829  5814  5814 D AdapterServiceConfig: Adding HealthService
09-29 07:15:28.829  5814  5814 D AdapterServiceConfig: Adding PanService
09-29 07:15:28.829  5814  5814 D AdapterServiceConfig: Adding GattService
09-29 07:15:28.829  5814  5814 D AdapterServiceConfig: Adding BluetoothMapService
,09-29 07:15:28.829  5814  5814 D AdapterServiceConfig: Adding SapService
,09-29 07:15:28.833   929  3254 I ActivityManager: Killing 5483:com.android.chrome/u0a39 (adj 15): empty #17
,09-29 07:15:28.853  4144  4144 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-29 07:15:28.857  4144  4144 D SystemUpdateService: onCreate
,09-29 07:15:28.860  4144  4144 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-29 07:15:28.868  4144  4144 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-29 07:15:28.874  4144  5469 I iu.UploadsManager: num queued entries: 0
,09-29 07:15:28.879  4144  5826 I SystemUpdateService: active receiver: enabled
,09-29 07:15:28.885  4144  4144 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 07:15:28.887  4144  4144 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 07:15:28.889  4144  5469 I iu.UploadsManager: num updated entries: 0
,09-29 07:15:28.890  4144  5469 I iu.SyncManager: NEXT; no task
,09-29 07:15:28.897  4144  5826 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 07:15:28.898   929  3933 I ActivityManager: Start proc 5828:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-29 07:15:28.908  4144  5826 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-29 07:15:28.910  4144  5826 I SystemUpdateService: now status is 0 (complete)
09-29 07:15:28.910  4144  5826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 07:15:28.910  4144  5826 I SystemUpdateService: file has been verified
09-29 07:15:28.910  4144  5826 I SystemUpdateService: OTA package size = 21989297
,09-29 07:15:28.938  5828  5828 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-29 07:15:28.941  5828  5828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 07:15:28.942  4144  5826 I SystemUpdateService: showing system update notification
,09-29 07:15:28.949  5828  5828 D SprintDMHelper: simOperator: 
,09-29 07:15:28.949  5828  5828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 07:15:28.961   929  3901 I ActivityManager: Start proc 5840:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-29 07:15:28.987  4144  4144 D SystemUpdateService: onDestroy
,09-29 07:15:28.988   929  3254 I ActivityManager: Killing 5501:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-29 07:15:29.065  4508  5854 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-29 07:15:29.071   929  3254 I ActivityManager: Start proc 5855:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-29 07:15:29.072   929  3723 I ActivityManager: Killing 5359:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-29 07:15:29.135  5855  5855 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-29 07:15:29.215  5780  5805 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-29 07:15:29.311   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e0d2c22:true
,09-29 07:15:29.333   929  3254 I ActivityManager: Killing 4783:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-29 07:15:29.374   929  3902 I ActivityManager: Start proc 5869:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-29 07:15:29.404  5869  5869 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-29 07:15:29.412   929   939 I ActivityManager: Killing 5559:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-29 07:15:33.262   929  3683 D WifiService: setWifiEnabled: true pid=5695, uid=10077
09-29 07:15:33.262   929  3683 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 07:15:33.270   508   928 D SoftapController: Softap fwReload - Ok
,09-29 07:15:33.276   508   928 D CommandListener: Setting iface cfg
,09-29 07:15:33.276   508   928 D CommandListener: Trying to bring down wlan0
09-29 07:15:33.277   508   928 D CommandListener: Clearing all IP addresses on wlan0
,09-29 07:15:33.281   929  3054 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 07:15:33.850   929  3054 D wifi    : set interface wlan0 flags (UP)
09-29 07:15:33.850   929  3054 I WifiHAL : Initializing wifi
,09-29 07:15:33.850   929  3054 I WifiHAL : Creating socket
,09-29 07:15:33.853   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-29 07:15:33.855   929  3054 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-29 07:15:33.856   929  3054 D wifi    : Did set static halHandle = 0x7f7db27400
,09-29 07:15:33.856   929  3054 D wifi    : halHandle = 0x7f7db27400, mVM = 0x7f9a10d140, mCls = 0x1018d2
,09-29 07:15:33.856   929  3054 D wifi    : array field set
09-29 07:15:33.856   929  3054 I WifiNative-HAL: interface[0] = wlan0
09-29 07:15:33.858   929  5889 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547569693696
09-29 07:15:33.858   929  5889 D wifi    : waitForHalEvents called, vm = 0x7f9a10d140, obj = 0x1018d2, env = 0x7f7adbe200
,09-29 07:15:33.922  5890  5890 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 07:15:33.937  5890  5890 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 07:15:33.959   929  3054 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 07:15:33.963  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:33.964  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:33.964  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:33.990  5890  5890 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 07:15:33.990  5890  5890 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 07:15:34.006   929  3054 D WifiConfigStore: Loading config and enabling all networks 
,09-29 07:15:34.007  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:34.007  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:34.007  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:34.007  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:34.008  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:34.008  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:15:34.008  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:34.008  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:34.010  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:34.010  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:34.010  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:34.010  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:15:34.021   929  3054 D WifiConfigStore: loaded 0 passpoint configs
,09-29 07:15:34.021   929  3054 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 07:15:34.022   929  3054 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-29 07:15:34.023   929  3054 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-29 07:15:34.024   929  3054 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-29 07:15:34.024   929  3054 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 07:15:34.025   929  3054 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 07:15:34.025   929  3054 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 07:15:34.027   929  3054 D WifiNative-HAL: Setting external_sim to 1
,09-29 07:15:34.027  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 07:15:34.027   929  3054 D wifi    : setting dfs flag to true, 0x7f7fb98da0
09-29 07:15:34.027   929  3054 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 07:15:34.027   929  3054 D wifi    : setting scan oui 0x7f7fb98da0
09-29 07:15:34.027   929  3054 D WifiHAL : Sending mac address OUI
,09-29 07:15:34.030   929  3054 E native  : do suspend false
,09-29 07:15:34.037   929  3054 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-29 07:15:34.037   929   929 D RttService: SCAN_AVAILABLE : 3
09-29 07:15:34.037   929  3162 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 07:15:34.038   508   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-29 07:15:34.038   508   928 D CommandListener: Setting iface cfg
,09-29 07:15:34.042   929  3053 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-29 07:15:34.042   929  3053 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 07:15:34.050   929  3053 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 07:15:34.050   929  3053 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-29 07:15:34.068   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=267241 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=26 mControllerEnergyUsed=98 }
,09-29 07:15:37.217  5890  5890 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:15:37.222  5890  5890 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:15:37.227  5890  5890 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:15:37.232  5890  5890 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:15:37.280   929  3054 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 07:15:37.282   929  3054 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 07:15:37.282   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 07:15:37.293   929  3054 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 07:15:37.326   929  3054 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 07:15:37.328  5890  5890 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 07:15:37.787  5890  5890 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-29 07:15:37.819  5890  5890 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-29 07:15:37.820  5890  5890 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-29 07:15:37.830   929  3054 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-29 07:15:37.830   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-29 07:15:37.831   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-29 07:15:37.846   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 07:15:37.858   508   928 D CommandListener: Setting iface cfg
,09-29 07:15:37.864   929  3054 D WifiStateMachine: Start Dhcp Watchdog 2
,09-29 07:15:37.871   929  5896 D DhcpClient: Receive thread started
,09-29 07:15:37.875   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 07:15:37.875   929  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-29 07:15:37.875   929  3056 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-29 07:15:37.956   929  3054 E native  : do suspend false
,09-29 07:15:37.972   929  5895 D DhcpClient: Broadcasting DHCPDISCOVER
,09-29 07:15:37.984   929  5896 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-29 07:15:37.985   929  5895 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
,09-29 07:15:37.987   929  5895 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-29 07:15:38.001   929  5896 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-29 07:15:38.001   929  5895 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-29 07:15:38.004   508   928 D CommandListener: Setting iface cfg
,09-29 07:15:38.009   929  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-29 07:15:38.017   929  5895 D DhcpClient: Scheduling renewal in 86399s
,09-29 07:15:38.026   929  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-29 07:15:38.028   929  3054 D WifiConfigStore: No blacklist allowed without epno enabled
09-29 07:15:38.029   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-29 07:15:38.031   929  3056 D ConnectivityService: Adding iface wlan0 to network 101
,09-29 07:15:38.047   929  3054 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-29 07:15:38.085   929  3056 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-29 07:15:38.085   929  3056 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-29 07:15:38.087   929  3056 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-29 07:15:38.090   929  3056 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-29 07:15:38.094   929  3056 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-29 07:15:38.102   929  3056 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-29 07:15:38.106   929  3056 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-29 07:15:38.106   929  3056 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-29 07:15:38.106   929  3056 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-29 07:15:38.106   929  3054 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-29 07:15:38.106   929  3056 D ConnectivityService:    accepting network in place of null
09-29 07:15:38.106   929  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 07:15:38.115   929  5894 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271288, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 07:15:38.138   929  3056 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 07:15:38.158   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 07:15:38.181   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 07:15:38.185   929  3056 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-29 07:15:38.185  3840  3975 W QCNEJ   : |CORE| network available: 101
09-29 07:15:38.185   929  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-29 07:15:38.186   929  3056 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-29 07:15:38.188   929  5893 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-29 07:15:38.189   929   946 D Tethering: MasterInitialState.processMessage what=3
09-29 07:15:38.192  3840  3975 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-29 07:15:38.193  3840  3975 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-29 07:15:38.193  3840  3975 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-29 07:15:38.196  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:38.196  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:15:38.196  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.196  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:38.198  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:38.198  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:38.198  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.198  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:38.200  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:15:38.200  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:15:38.200  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.200  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:15:38.201  4144  4144 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-29 07:15:38.202  5112  5129 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-29 07:15:38.203  5112  5129 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 07:15:38.203  5112  5129 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-29 07:15:38.203  5112  5129 E SarControlService: no key has been found,reset the power
09-29 07:15:38.203  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 07:15:38.203  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 07:15:38.203  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 07:15:38.204  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:15:38.204  5139  5139 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-29 07:15:38.205  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-29 07:15:38.205  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 07:15:38.205  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 07:15:38.206  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:15:38.206  5139  5139 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 07:15:38.209  4144  4144 D SystemUpdateService: onCreate
,09-29 07:15:38.214  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000ec03000000000000ffffffff]
,09-29 07:15:38.214  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 07:15:38.214  5139  5153 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-29 07:15:38.214  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 07:15:38.214  5112  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 07:15:38.215  4144  4144 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-29 07:15:38.216  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000ed03000000000000ffffffff]
09-29 07:15:38.216  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 07:15:38.216  5139  5153 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-29 07:15:38.217  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 07:15:38.217  5112  5123 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-29 07:15:38.228  4144  4144 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-29 07:15:38.236  4144  5906 I SystemUpdateService: active receiver: enabled
,09-29 07:15:38.238  4144  4144 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 07:15:38.240  4144  4144 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 07:15:38.242  5828  5828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 07:15:38.244   929  5893 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 29 Sep 2016 11:15:38 GMT], X-Android-Received-Millis=[1475147738243], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475147738221]}
,09-29 07:15:38.245   929  3056 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-29 07:15:38.245   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-29 07:15:38.245   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-29 07:15:38.246   929  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-29 07:15:38.246  5828  5828 D SprintDMHelper: simOperator: 
09-29 07:15:38.246  5828  5828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 07:15:38.234  4144  5469 I iu.UploadsManager: num queued entries: 0
,09-29 07:15:38.257  4144  5469 I iu.UploadsManager: num updated entries: 0
,09-29 07:15:38.267   929  3901 D WifiService: setWifiEnabled: false pid=5695, uid=10077
,09-29 07:15:38.267   929  3901 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 07:15:38.270   929  3054 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-29 07:15:38.270   929  3054 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-29 07:15:38.270   929  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 07:15:38.270   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 07:15:38.279   929  5895 D DhcpClient: Clearing IP address
09-29 07:15:38.279   508   928 D CommandListener: Clearing all IP addresses on wlan0
,09-29 07:15:38.281   508   928 D CommandListener: Setting iface cfg
,09-29 07:15:38.284   929  5896 D DhcpClient: Receive thread stopped
,09-29 07:15:38.291   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-29 07:15:38.291   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-29 07:15:38.293  4144  5906 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-29 07:15:38.294   598   598 E Parcel  : Reading a NULL string not supported here.
09-29 07:15:38.297   929  3056 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-29 07:15:38.299  3840  3975 W QCNEJ   : |CORE| network lost: 101
09-29 07:15:38.299  3840  3975 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-29 07:15:38.299   929   929 D RttService: SCAN_AVAILABLE : 1
09-29 07:15:38.300   929  3162 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-29 07:15:38.302   929  3054 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-29 07:15:38.306  4144  5469 I iu.SyncManager: NEXT; no task
,09-29 07:15:38.307   929  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-29 07:15:38.311  4144  5906 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-29 07:15:38.311  4144  5906 I SystemUpdateService: now status is 0 (complete)
09-29 07:15:38.311  4144  5906 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 07:15:38.311  4144  5906 I SystemUpdateService: file has been verified
09-29 07:15:38.311  4144  5906 I SystemUpdateService: OTA package size = 21989297
,09-29 07:15:38.320  4144  5906 I SystemUpdateService: showing system update notification
,09-29 07:15:38.323   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 07:15:38.332  4144  4144 D SystemUpdateService: onDestroy
,09-29 07:15:38.343   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 07:15:38.343   508   928 D CommandListener: Clearing all IP addresses on wlan0
09-29 07:15:38.344   929  3056 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-29 07:15:38.344   929  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-29 07:15:38.347   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-29 07:15:38.350  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:38.350  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:15:38.350  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:38.350  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:15:38.350   929  3054 D DhcpClient: doQuit
09-29 07:15:38.350   929  3054 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-29 07:15:38.350   929  5895 D DhcpClient: onQuitting
09-29 07:15:38.352  5890  5890 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-29 07:15:38.353  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:38.353  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:38.353  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.353  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:38.354  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:38.354  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:38.354  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.354  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:15:38.356  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:38.356  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:38.357  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.357  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:38.359  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:38.359  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:38.359  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:38.359  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:38.361  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:38.362  4144  4144 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 07:15:38.364  5112  5129 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 07:15:38.364  5112  5129 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 07:15:38.364  5112  5129 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-29 07:15:38.364  5112  5129 E SarControlService: no key has been found,reset the power
,09-29 07:15:38.365  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-29 07:15:38.365  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 07:15:38.365  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 07:15:38.365  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:15:38.365  5139  5139 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 07:15:38.366  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 07:15:38.366  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 07:15:38.366  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-29 07:15:38.367  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:15:38.367  5139  5139 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-29 07:15:38.369  5890  5890 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-29 07:15:38.370  4144  4144 D SystemUpdateService: onCreate
09-29 07:15:38.371  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000ee03000000000000ffffffff]
09-29 07:15:38.371  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 07:15:38.371  5139  5153 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-29 07:15:38.371  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-29 07:15:38.372  5112  5123 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-29 07:15:38.373  5890  5890 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-29 07:15:38.375  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000ef03000000000000ffffffff]
09-29 07:15:38.375  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 07:15:38.375  5139  5153 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-29 07:15:38.376  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 07:15:38.376  5112  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-29 07:15:38.377  4144  4144 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-29 07:15:38.383  4144  5925 I SystemUpdateService: active receiver: enabled
,09-29 07:15:38.385  4144  4144 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-29 07:15:38.391  4144  5469 I iu.UploadsManager: num queued entries: 0
,09-29 07:15:38.391  4144  5469 I iu.UploadsManager: num updated entries: 0
,09-29 07:15:38.392  4144  4144 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-29 07:15:38.394  4144  4144 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 07:15:38.395  5828  5828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-29 07:15:38.397   508   928 E Netd    : netlink response contains error (No such file or directory)
,09-29 07:15:38.398   929  3056 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-29 07:15:38.400  5828  5828 D SprintDMHelper: simOperator: 
09-29 07:15:38.400  5828  5828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 07:15:38.403  5890  5890 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-29 07:15:38.408  4144  5925 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 07:15:38.410  4144  5469 I iu.SyncManager: NEXT; no task
,09-29 07:15:38.412  4144  5925 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-29 07:15:38.413  4144  5925 I SystemUpdateService: now status is 0 (complete)
09-29 07:15:38.413  4144  5925 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 07:15:38.413  4144  5925 I SystemUpdateService: file has been verified
09-29 07:15:38.413  4144  5925 I SystemUpdateService: OTA package size = 21989297
,09-29 07:15:38.414  5890  5890 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-29 07:15:38.419   929  3054 D wifi    : In wifi stop Hal
,09-29 07:15:38.419   929  3054 D wifi    : halHandle = 0x7f7db27400, mVM = 0x7f9a10d140, mCls = 0x1018d2
09-29 07:15:38.419   929  5889 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-29 07:15:38.419   929  5889 D WifiHAL : Got a signal to exit!!!
09-29 07:15:38.419   929  5889 I WifiHAL : Exit wifi_event_loop
09-29 07:15:38.419  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 07:15:38.421   929  3054 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-29 07:15:38.421   929  3054 E WifiHAL : Event processing terminated
09-29 07:15:38.421   929  3054 D wifi    : In wifi cleaned up handler
09-29 07:15:38.421   929  3054 I WifiHAL : Internal cleanup completed
09-29 07:15:38.421  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:38.422  3979  4293 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-29 07:15:38.422  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:38.423  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:38.433  4144  5925 I SystemUpdateService: showing system update notification
,09-29 07:15:38.440  4144  4144 D SystemUpdateService: onDestroy
,09-29 07:15:38.443   929  5889 D wifi    : set interface wlan0 flags (DOWN)
,09-29 07:15:38.443   929  3054 D WifiNative-HAL: HAL event thread stopped successfully
,09-29 07:15:38.647   929   946 D Tethering: InitialState.processMessage what=4
,09-29 07:15:38.650   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-29 07:15:39.186   929  3056 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-29 07:15:40.336   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:41.338   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:42.339   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:43.279  4508  5912 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-29 07:15:43.279  4508  5912 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-29 07:15:43.287  4508  5912 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-29 07:15:43.304   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae8d43a:true
,09-29 07:15:43.305  5814  5814 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 07:15:43.309  5814  5814 I bt_bluedroid: init
,09-29 07:15:43.309  5814  5929 I BluetoothAdapterState: Entering OffState
,09-29 07:15:43.313  5814  5930 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-29 07:15:43.313  5814  5930 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 07:15:43.313  5814  5930 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 07:15:43.313  5814  5930 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-29 07:15:43.313  5814  5814 I bt_bluedroid: get_profile_interface socket
,09-29 07:15:43.315  5814  5814 I bt_bluedroid: get_profile_interface sdp
09-29 07:15:43.316  5814  5933 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 07:15:43.317  5814  5933 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 07:15:43.322  5814  5825 I bt_bluedroid: config_hci_snoop_log
09-29 07:15:43.323   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 07:15:43.328  5814  5929 D BluetoothAdapterState: Current state: OFF, message: 0
,09-29 07:15:43.328  5814  5929 D BluetoothAdapterProperties: Setting state to 14
09-29 07:15:43.328  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-29 07:15:43.330  5814  5929 D BluetoothBondStateMachine: make
,09-29 07:15:43.332  5814  5934 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 07:15:43.335  5814  5929 I BluetoothAdapterState: Entering PendingCommandState
,09-29 07:15:43.336  5814  5814 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 07:15:43.338  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:43.339  5814  5814 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 07:15:43.339   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:43.340  5814  5814 D BtGatt.GattService: Received start request. Starting profile...
09-29 07:15:43.340  5814  5814 D BtGatt.GattService: start()
09-29 07:15:43.340  5814  5814 I bt_bluedroid: get_profile_interface gatt
,09-29 07:15:43.341  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:43.342  5814  5814 D BtGatt.AdvertiseManager: advertise manager created
,09-29 07:15:43.348  5814  5814 V BluetoothAdapterState: isTurningOff()=false
,09-29 07:15:43.348  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:43.348  5814  5814 V BluetoothAdapterState: isBleTurningOn()=true
09-29 07:15:43.348  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:43.348  5814  5929 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-29 07:15:43.349  5814  5929 I bt_bluedroid: bt_bluedroid
,09-29 07:15:43.350  5814  5930 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-29 07:15:43.350  5814  5930 I bt_hci  : start_up
,09-29 07:15:43.355  5814  5930 I bt_vendor: alloc value 0xf3fb8871
,09-29 07:15:43.355  5814  5930 I bt_vendor: init
09-29 07:15:43.356  5814  5930 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 07:15:43.356  5814  5930 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 07:15:43.466  5814  5930 D bt_hci  : start_up starting async portion
09-29 07:15:43.467  5814  5937 I bt_hci  : event_finish_startup
09-29 07:15:43.467  5814  5937 I bt_hci_h4: hal_open
09-29 07:15:43.467  5814  5937 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 07:15:43.469  5814  5937 I bt_userial_vendor: device fd = 54 open
,09-29 07:15:43.465  5938  5938 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 07:15:43.482  5814  5937 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 07:15:43.485  5814  5937 D bt_hwcfg: Chipset BCM4358A3
,09-29 07:15:43.485  5814  5937 D bt_hwcfg: Target name = [BCM4358A3]
09-29 07:15:43.485  5814  5937 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 07:15:43.875  5814  5937 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 07:15:43.875  5814  5937 D bt_hwcfg: Settlement delay -- 100 ms
09-29 07:15:43.875  5814  5937 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 07:15:44.009  5814  5937 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 07:15:44.010  5814  5937 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 07:15:44.011  5814  5937 I bt_hwcfg: vendor lib fwcfg completed
,09-29 07:15:44.011  5814  5937 I bt_vendor: firmware callback
09-29 07:15:44.012  5814  5937 I bt_hci  : firmware_config_callback
,09-29 07:15:44.020  5814  5940 I bt_btu  : btu_task pending for preload complete event
,09-29 07:15:44.021  5814  5940 I bt_btu_task: Bluetooth chip preload is complete
09-29 07:15:44.021  5814  5940 I bt_btu  : btu_task received preload complete event
,09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_HCI
,09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_AVDT
09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_A2D
,09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_BNEP
09-29 07:15:44.028  5814  5940 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 07:15:44.029  5814  5940 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 07:15:44.029  5814  5940 I         : BTE_InitTraceLevels -- TRC_PAN
09-29 07:15:44.029  5814  5940 I         : BTE_InitTraceLevels -- TRC_SDP
,09-29 07:15:44.029  5814  5940 I         : BTE_InitTraceLevels -- TRC_GATT
09-29 07:15:44.029  5814  5940 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 07:15:44.029  5814  5940 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 07:15:44.029  5814  5940 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 07:15:44.110  5814  5940 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f36549
09-29 07:15:44.112  5814  5940 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f36549 
,09-29 07:15:44.130  5814  5933 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 07:15:44.132  5814  5933 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-29 07:15:44.133  5814  5933 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 07:15:44.135  5814  5933 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 07:15:44.139  5814  5933 D BluetoothAdapterProperties: Scan Mode:20
09-29 07:15:44.140  5814  5933 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 07:15:44.140  5814  5933 D bt_hci  : do_postload posting postload work item
,09-29 07:15:44.140  5814  5937 I bt_hci  : event_postload
09-29 07:15:44.141  5814  5937 I bt_vendor: sco_config_cb
09-29 07:15:44.141  5814  5937 I bt_hci  : sco_config_callback postload finished.
,09-29 07:15:44.145  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:44.147  5814  5937 I bt_vendor: low_power_mode_cb
09-29 07:15:44.148  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:44.149  5814  5933 D bt_bte_conf: Device ID record 1 : primary
09-29 07:15:44.149  5814  5933 D bt_bte_conf:   vendorId            = 000f
09-29 07:15:44.149  5814  5933 D bt_bte_conf:   vendorIdSource      = 0001
09-29 07:15:44.149  5814  5933 D bt_bte_conf:   product             = 1200
09-29 07:15:44.149  5814  5933 D bt_bte_conf:   version             = 1436
09-29 07:15:44.150  5814  5933 D bt_bte_conf:   clientExecutableURL = 
09-29 07:15:44.150  5814  5933 D bt_bte_conf:   serviceDescription  = 
09-29 07:15:44.150  5814  5933 D bt_bte_conf:   documentationURL    = 
09-29 07:15:44.150  5814  5933 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 07:15:44.150  5814  5930 D bt_stack_manager: event_start_up_stack finished
09-29 07:15:44.152  5814  5929 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 07:15:44.152  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:44.152  5814  5929 D BluetoothAdapterProperties: Setting state to 15
09-29 07:15:44.152  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-29 07:15:44.153  5814  5929 I BluetoothAdapterState: Entering BleOnState
,09-29 07:15:44.156  5814  5929 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 07:15:44.156  5814  5929 D BluetoothAdapterProperties: Setting state to 11
,09-29 07:15:44.156  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-29 07:15:44.161  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:44.162  5814  5814 D HeadsetService: Received start request. Starting profile...
09-29 07:15:44.164  5814  5814 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 07:15:44.164  5814  5814 D HeadsetStateMachine: make
09-29 07:15:44.166  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:44.168  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:44.169  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:44.174  5814  5814 D HeadsetStateMachine: max_hf_connections = 1
,09-29 07:15:44.174  5814  5814 I bt_bluedroid: get_profile_interface handsfree
09-29 07:15:44.174  5814  5933 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 07:15:44.174  5814  5933 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-29 07:15:44.176  5814  5929 I BluetoothAdapterState: Entering PendingCommandState
,09-29 07:15:44.177  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:44.178  5814  5814 D A2dpService: Received start request. Starting profile...
,09-29 07:15:44.178  5814  5814 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-29 07:15:44.178  5814  5814 I bt_bluedroid: get_profile_interface avrcp
,09-29 07:15:44.183  5814  5814 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 07:15:44.183  5814  5814 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 07:15:44.184  5814  5814 D A2dpStateMachine: make
09-29 07:15:44.184  5814  5814 I bt_bluedroid: get_profile_interface a2dp
,09-29 07:15:44.185  5814  5933 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-29 07:15:44.186  5814  5948 D A2dpStateMachine: Enter Disconnected: -2
09-29 07:15:44.187  5814  5814 I BluetoothHidServiceJni: classInitNative: succeeds
09-29 07:15:44.187  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:44.188  5749  5749 D BluetoothInputDevice: Proxy object connected
,09-29 07:15:44.189  5749  5749 D HidProfile: Bluetooth service connected
09-29 07:15:44.190  5814  5814 D HidService: Received start request. Starting profile...
09-29 07:15:44.190  5814  5814 I bt_bluedroid: get_profile_interface hidhost
09-29 07:15:44.190  5814  5814 D HidService: setHidService(): set to: null
09-29 07:15:44.190  5814  5933 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f1756d
09-29 07:15:44.190  5814  5933 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 07:15:44.192  5814  5814 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 07:15:44.193  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:44.193  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 07:15:44.193  5814  5814 D HealthService: Received start request. Starting profile...
,09-29 07:15:44.195  5814  5814 I bt_bluedroid: get_profile_interface health
,09-29 07:15:44.196  5814  5814 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-29 07:15:44.197  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:44.198  5814  5814 D PanService: Received start request. Starting profile...
09-29 07:15:44.198  5749  5749 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 07:15:44.198  5814  5814 D BluetoothPanServiceJni: initializeNative(L110): pan
09-29 07:15:44.198  5814  5814 I bt_bluedroid: get_profile_interface pan
09-29 07:15:44.199  5749  5749 D PanProfile: Bluetooth service connected
,09-29 07:15:44.199  5814  5933 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-29 07:15:44.203  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:44.204  5749  5749 D BluetoothMap: Proxy object connected
,09-29 07:15:44.204  5814  5814 D BluetoothMapService: Received start request. Starting profile...
09-29 07:15:44.204  5814  5814 D BluetoothMapService: start()
09-29 07:15:44.204  5749  5749 D MapProfile: Bluetooth service connected
09-29 07:15:44.205  5749  5749 D BluetoothMap: getConnectedDevices()
09-29 07:15:44.205  5749  5749 D BluetoothMap: Bluetooth is Not enabled
,09-29 07:15:44.207  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-29 07:15:44.207  5814  5814 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-29 07:15:44.208  5814  5814 D BluetoothMapAppObserver: createReceiver()
,09-29 07:15:44.209  5814  5814 D BluetoothMapAppObserver: initObservers()
,09-29 07:15:44.209  5814  5814 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-29 07:15:44.215  5814  5814 V SapService: SapBinder()
,09-29 07:15:44.215  5814  5814 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:44.215  5814  5814 D SapService: Received start request. Starting profile...
09-29 07:15:44.215  5814  5814 V SapService: start()
,09-29 07:15:44.216  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:44.216  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:44.217  5814  5945 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isTurningOn()=true
,09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:44.217  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:44.218  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:44.219  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:44.219  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:44.219  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:44.219  5814  5814 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:44.220  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:44.220  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:44.220  5814  5929 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-29 07:15:44.220  5814  5929 D BluetoothAdapterProperties: ScanMode =  20
09-29 07:15:44.220  5814  5929 D BluetoothAdapterProperties: State =  11
09-29 07:15:44.220  5814  5929 D BluetoothAdapterProperties: Setting state to 12
09-29 07:15:44.220  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-29 07:15:44.221  5814  5929 I BluetoothAdapterState: Entering OnState
,09-29 07:15:44.221  5749  5763 D BluetoothPbap: onBluetoothStateChange: up=true
,09-29 07:15:44.223   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 07:15:44.224  5814  5933 D BluetoothAdapterProperties: Scan Mode:21
09-29 07:15:44.224  5814  5933 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 07:15:44.224  3221  3447 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:44.225   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:44.225   929   929 D BluetoothA2dp: Proxy object connected
09-29 07:15:44.225  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 07:15:44.225  3221  3236 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 07:15:44.226  3221  3221 D BluetoothInputDevice: Proxy object connected
09-29 07:15:44.226  3221  3447 D BluetoothPbap: onBluetoothStateChange: up=true
,09-29 07:15:44.227  3221  3221 D HidProfile: Bluetooth service connected
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:44.228  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:44.228  5749  5761 D BluetoothMap: onBluetoothStateChange: up=true
09-29 07:15:44.228   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:44.229  3221  3236 D BluetoothMap: onBluetoothStateChange: up=true
09-29 07:15:44.230  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:44.230  3221  3221 D BluetoothMap: Proxy object connected
09-29 07:15:44.230  3221  3221 D MapProfile: Bluetooth service connected
09-29 07:15:44.230  3221  3447 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-29 07:15:44.230  3221  3221 D BluetoothMap: getConnectedDevices()
,09-29 07:15:44.232  5749  5763 D BluetoothPan: onBluetoothStateChange on: true
09-29 07:15:44.232  3221  3221 D BluetoothA2dp: Proxy object connected
09-29 07:15:44.232  3891  3911 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:44.233  5749  5761 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 07:15:44.233   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:44.233  3221  3234 D BluetoothPan: onBluetoothStateChange on: true
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:44.233  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:44.235  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 07:15:44.235  3221  3221 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 07:15:44.235  3221  3221 D PanProfile: Bluetooth service connected
09-29 07:15:44.235  5814  5814 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 07:15:44.236  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:44.237   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-29 07:15:44.238  5749  5749 D LocalBluetoothProfileManager: Adding local A2DP profile
09-29 07:15:44.238  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:44.240  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:44.241  5814  5814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 07:15:44.241  5749  5749 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-29 07:15:44.242  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:44.242  5814  5814 D ObexServerSockets: Succeed to create listening sockets 
09-29 07:15:44.243  5814  5814 D ObexServerSockets0: startAccept()
09-29 07:15:44.243  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 07:15:44.243  5814  5814 D ObexServerSockets0: prepareForNewConnect()
09-29 07:15:44.245  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:44.245  5814  5814 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-29 07:15:44.245  5814  5814 D BluetoothSdpJni: SDP Create record success - handle: 0
09-29 07:15:44.246  5814  5814 D BluetoothMapService: onReceive
09-29 07:15:44.246  5814  5814 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 07:15:44.246  5814  5814 D BluetoothMapService: STATE_ON
,09-29 07:15:44.246  5814  5956 D ObexServerSockets0: Accepting socket connection...
09-29 07:15:44.246  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:44.247  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:44.248  5814  5958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 07:15:44.248  5814  5957 D ObexServerSockets0: Accepting socket connection...
09-29 07:15:44.248  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 07:15:44.250  5814  5958 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-29 07:15:44.250  5814  5958 D BluetoothSdpJni: SDP Create record success - handle: 1
09-29 07:15:44.251  5749  5749 D BluetoothA2dp: Proxy object connected
,09-29 07:15:44.256  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 07:15:44.261  5749  5749 D DockEventReceiver: finishStartingService: stopping service
,09-29 07:15:44.265  5749  5749 D BluetoothPbap: Proxy object connected
,09-29 07:15:44.265  5749  5749 D PbapServerProfile: Bluetooth service connected
09-29 07:15:44.266  3221  3221 D BluetoothPbap: Proxy object connected
09-29 07:15:44.266  3221  3221 D PbapServerProfile: Bluetooth service connected
,09-29 07:15:44.270  5814  5814 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-29 07:15:44.271  5814  5814 D ObexServerSockets0: prepareForNewConnect()
09-29 07:15:44.272  5814  5962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 07:15:44.285  5814  5966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 07:15:44.286  5814  5966 I BtOppRfcommListener: Accept thread started.
,09-29 07:15:44.328   929   929 D BluetoothHeadset: Proxy object connected
09-29 07:15:44.328   929   929 D BluetoothHeadset: Proxy object connected
,09-29 07:15:44.328  3221  3234 D BluetoothHeadset: Proxy object connected
,09-29 07:15:44.328  3221  3221 D HeadsetProfile: Bluetooth service connected
09-29 07:15:44.329   929   946 D BluetoothHeadset: Proxy object connected
09-29 07:15:44.329   929   929 D BluetoothHeadset: Proxy object connected
09-29 07:15:44.329  3891  4107 D BluetoothHeadset: Proxy object connected
,09-29 07:15:44.333  3891  3908 D BluetoothHeadset: Proxy object connected
,09-29 07:15:44.334   929   946 D BluetoothHeadset: Proxy object connected
,09-29 07:15:44.339   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:15:44.345  5749  5763 D BluetoothHeadset: Proxy object connected
,09-29 07:15:44.346  5749  5749 D HeadsetProfile: Bluetooth service connected
,09-29 07:15:45.340   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-29 07:15:46.112   929  3056 D ConnectivityService: handlePromptUnvalidated 101
,09-29 07:15:48.282  5814  5929 D BluetoothAdapterState: Current state: ON, message: 23
,09-29 07:15:48.282  5814  5929 D BluetoothAdapterProperties: Setting state to 13
,09-29 07:15:48.282  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-29 07:15:48.283  5814  5929 D BluetoothAdapterProperties: onBluetoothDisable()
,09-29 07:15:48.285  5814  5929 I BluetoothAdapterState: Entering PendingCommandState
09-29 07:15:48.291  5814  5933 D BluetoothAdapterProperties: Scan Mode:20
09-29 07:15:48.291  5814  5929 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-29 07:15:48.292  5814  5814 D BluetoothMapService: onReceive
09-29 07:15:48.292  5814  5814 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 07:15:48.292  5814  5814 D BluetoothMapService: STATE_TURNING_OFF
,09-29 07:15:48.293  5814  5814 D BluetoothMapService: MAP Service closeService in
09-29 07:15:48.293  5814  5814 D BluetoothMapMasInstance0: MAP Service shutdown
09-29 07:15:48.293  5814  5814 D ObexServerSockets0: shutdown(block = true)
09-29 07:15:48.294  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 07:15:48.294  5814  5814 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-29 07:15:48.294  5814  5956 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-29 07:15:48.295  5814  5814 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-29 07:15:48.295  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:48.295  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:48.295  5814  5957 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-29 07:15:48.295  5814  5942 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-29 07:15:48.296  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:48.296  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:48.301  5814  5814 I BtOppRfcommListener: stopping Accept Thread
09-29 07:15:48.301  5814  5966 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-29 07:15:48.301  5814  5966 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-29 07:15:48.309  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:48.309  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:48.310  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:48.310  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:48.311  5814  5814 D HeadsetService: Received stop request...Stopping profile...
09-29 07:15:48.313   929   929 D BluetoothHeadset: Proxy object disconnected
,09-29 07:15:48.313   929   929 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:48.313  5749  5763 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:48.314  5814  5814 D A2dpService: Received stop request...Stopping profile...
09-29 07:15:48.314  5814  5948 D A2dpStateMachine: Exit Disconnected: -1
09-29 07:15:48.315  3221  3447 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:48.315  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:48.315  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:48.315   929   929 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:48.316  3891  3911 D BluetoothHeadset: Proxy object disconnected
09-29 07:15:48.316  5695  5695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-29 07:15:48.316  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:48.316   929   929 D BluetoothA2dp: Proxy object disconnected
,09-29 07:15:48.318  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:48.319  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 07:15:48.320  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:48.320  5749  5749 D DockEventReceiver: finishStartingService: stopping service
09-29 07:15:48.321  5749  5749 D HeadsetProfile: Bluetooth service disconnected
09-29 07:15:48.321  5814  5814 D HidService: Received stop request...Stopping profile...
09-29 07:15:48.322  5814  5814 D HidService: Stopping Bluetooth HidService
09-29 07:15:48.322  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:48.322  5749  5749 D BluetoothA2dp: Proxy object disconnected
09-29 07:15:48.323  5749  5749 D BluetoothInputDevice: Proxy object disconnected
09-29 07:15:48.323  5749  5749 D HidProfile: Bluetooth service disconnected
09-29 07:15:48.323  3221  3221 D HeadsetProfile: Bluetooth service disconnected
,09-29 07:15:48.323  3221  3221 D BluetoothA2dp: Proxy object disconnected
09-29 07:15:48.323  3221  3221 D BluetoothInputDevice: Proxy object disconnected
09-29 07:15:48.323  3221  3221 D HidProfile: Bluetooth service disconnected
09-29 07:15:48.325  5814  5814 D HealthService: Received stop request...Stopping profile...
09-29 07:15:48.327  5814  5814 D PanService: Received stop request...Stopping profile...
09-29 07:15:48.328  3221  3221 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 07:15:48.328  3221  3221 D PanProfile: Bluetooth service disconnected
,09-29 07:15:48.329  5749  5749 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-29 07:15:48.329  5749  5749 D PanProfile: Bluetooth service disconnected
,09-29 07:15:48.330  5814  5814 D BluetoothMapService: Received stop request...Stopping profile...
09-29 07:15:48.330  5814  5814 D BluetoothMapService: stop()
,09-29 07:15:48.332  5814  5814 D BluetoothMapAppObserver: deinitObservers()
,09-29 07:15:48.332  5814  5814 D BluetoothMapAppObserver: removeReceiver()
09-29 07:15:48.333  3221  3221 D BluetoothMap: Proxy object disconnected
09-29 07:15:48.333  3221  3221 D MapProfile: Bluetooth service disconnected
09-29 07:15:48.334  5814  5814 D SapService: Received stop request...Stopping profile...
09-29 07:15:48.334  5749  5749 D BluetoothMap: Proxy object disconnected
09-29 07:15:48.334  5814  5814 V SapService: stop()
09-29 07:15:48.334  5749  5749 D MapProfile: Bluetooth service disconnected
,09-29 07:15:48.335  5814  5814 V BluetoothAdapterState: isTurningOff()=true
,09-29 07:15:48.336  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.336  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:48.336  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:48.337  5814  5814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-29 07:15:48.337  5814  5814 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-29 07:15:48.338  5814  5940 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:48.338  5814  5940 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:48.338  5814  5940 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:48.338  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:48.338  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.338  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:48.338  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:48.338  5814  5933 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-29 07:15:48.339  5814  5933 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-29 07:15:48.339  5814  5940 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:48.339  5814  5940 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-29 07:15:48.339  5814  5933 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-29 07:15:48.340  5814  5940 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-29 07:15:48.340  5814  5940 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-29 07:15:48.340  5814  5940 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-29 07:15:48.340  5814  5940 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-29 07:15:48.341  3221  3221 D BluetoothPbap: Proxy object disconnected
09-29 07:15:48.341  3221  3221 D PbapServerProfile: Bluetooth service disconnected
09-29 07:15:48.341  5749  5749 D BluetoothPbap: Proxy object disconnected
,09-29 07:15:48.341  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:48.341  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.341  5749  5749 D PbapServerProfile: Bluetooth service disconnected
09-29 07:15:48.341  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:48.341  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:48.342  5814  5814 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-29 07:15:48.342  5814  5814 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-29 07:15:48.342  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:48.342  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.342  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:48.342  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:48.342  5814  5814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-29 07:15:48.342  5814  5814 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-29 07:15:48.343  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:48.343  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.343  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:48.343  5814  5933 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 07:15:48.343  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:48.343  5814  5933 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-29 07:15:48.343  5814  5814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-29 07:15:48.343  5814  5814 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-29 07:15:48.345  5814  5814 D BluetoothMapService: MAP Service closeService in
09-29 07:15:48.345  5814  5814 V BluetoothAdapterState: isTurningOff()=true
09-29 07:15:48.345  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.345  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:48.345  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:48.346  5814  5814 D BluetoothMapService: cleanup()
09-29 07:15:48.346  5814  5814 D BluetoothMapService: MAP Service closeService in
09-29 07:15:48.346  5814  5814 V BluetoothAdapterState: isTurningOff()=true
,09-29 07:15:48.346  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.356  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:48.356  5814  5814 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:48.356  5814  5929 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-29 07:15:48.356  5814  5929 D BluetoothAdapterProperties: Setting state to 15
09-29 07:15:48.356  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-29 07:15:48.357  5814  5929 I BluetoothAdapterState: Entering BleOnState
09-29 07:15:48.357  5749  5761 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 07:15:48.361  5749  5763 D BluetoothPbap: onBluetoothStateChange: up=false
,09-29 07:15:48.362   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 07:15:48.362  3221  3447 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:48.362   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:48.362  3221  3234 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 07:15:48.363  3221  3236 D BluetoothPbap: onBluetoothStateChange: up=false
09-29 07:15:48.363  5749  5761 D BluetoothMap: onBluetoothStateChange: up=false
09-29 07:15:48.364   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 07:15:48.365  3221  3447 D BluetoothMap: onBluetoothStateChange: up=false
09-29 07:15:48.366  3221  3234 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 07:15:48.366  5749  5763 D BluetoothPan: onBluetoothStateChange on: false
,09-29 07:15:48.367  3891  4107 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-29 07:15:48.368  5749  5761 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-29 07:15:48.368   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-29 07:15:48.368  5749  5763 D BluetoothA2dp: onBluetoothStateChange: up=false
09-29 07:15:48.369  3221  3236 D BluetoothPan: onBluetoothStateChange on: false
09-29 07:15:48.370  5814  5929 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-29 07:15:48.370  5814  5929 D BluetoothAdapterProperties: Setting state to 16
09-29 07:15:48.370  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-29 07:15:48.371  5814  5929 D BluetoothAdapterProperties: onBleDisable
09-29 07:15:48.371  5814  5929 I BluetoothAdapterState: Entering PendingCommandState
09-29 07:15:48.371  5814  5930 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-29 07:15:48.372  5814  5940 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-29 07:15:48.372  5814  5940 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-29 07:15:48.375  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:48.375  5814  5933 D BluetoothAdapterProperties: Scan Mode:20
,09-29 07:15:48.377  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:48.377  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-29 07:15:48.378  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:48.379  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:48.380  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:48.382  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:48.383  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 07:15:48.385  5749  5749 D DockEventReceiver: finishStartingService: stopping service
,09-29 07:15:48.585  5814  5933 I bt_hci  : shut_down
,09-29 07:15:48.588  5814  5937 D bt_hwcfg: hw_epilog_process
,09-29 07:15:48.589  5814  5937 I bt_vendor: low_power_mode_cb
,09-29 07:15:48.591  5814  5937 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-29 07:15:48.591  5814  5937 I bt_vendor: epilog_cb
09-29 07:15:48.591  5814  5937 I bt_hci  : epilog_finished_callback
,09-29 07:15:48.593  5814  5933 I bt_hci_h4: hal_close
,09-29 07:15:48.594  5814  5933 I bt_userial_vendor: device fd = 54 close
,09-29 07:15:48.709  5814  5930 D bt_stack_manager: event_shut_down_stack finished.
,09-29 07:15:48.710  5814  5929 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-29 07:15:48.716  5814  5814 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-29 07:15:48.716  5814  5929 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-29 07:15:48.718  5814  5814 D BtGatt.GattService: Received stop request...Stopping profile...
09-29 07:15:48.718  5814  5814 D BtGatt.GattService: stop()
09-29 07:15:48.718  5814  5814 D BtGatt.AdvertiseManager: advertise clients cleared
,09-29 07:15:48.721  5814  5814 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:48.721  5814  5814 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:48.721  5814  5814 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 07:15:48.721  5814  5814 V BluetoothAdapterState: isBleTurningOff()=true
09-29 07:15:48.722  5814  5929 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-29 07:15:48.722  5814  5929 D BluetoothAdapterProperties: Setting state to 10
09-29 07:15:48.722  5814  5929 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-29 07:15:48.723  5814  5929 I BluetoothAdapterState: Entering OffState
,09-29 07:15:48.725   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-29 07:15:48.737  5814  5814 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-29 07:15:48.737  5814  5814 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-29 07:15:48.739  5814  5814 I BluetoothServiceJni: cleanupNative: return from cleanup
09-29 07:15:48.740  5814  5930 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-29 07:15:48.746  5814  5814 I art     : System.exit called, status: 0
09-29 07:15:48.746  5814  5814 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-29 07:15:48.776   929   940 I ActivityManager: Process com.android.bluetooth (pid 5814) has died
,09-29 07:15:53.279  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 07:15:53.280  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:53.284  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:15:53.284  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4b593fb removed from the list
,09-29 07:15:53.285  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 07:15:53.285  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:15:53.285  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:15:53.287  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:15:53.287  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@830c671 added. We now have 4 listener(s)
09-29 07:15:53.288  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:15:53.290  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:15:53.290  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@830c671 removed from the list
09-29 07:15:53.290  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:15:53.290  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:15:53.290  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:15:53.292  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:15:53.292  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a11c56 added. We now have 4 listener(s)
09-29 07:15:53.292  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:15:58.303  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:58.334   929   946 I ActivityManager: Start proc 5974:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-29 07:15:58.417  5974  5974 D AdapterServiceConfig: Adding HeadsetService
,09-29 07:15:58.418  5974  5974 D AdapterServiceConfig: Adding A2dpService
,09-29 07:15:58.418  5974  5974 D AdapterServiceConfig: Adding HidService
,09-29 07:15:58.418  5974  5974 D AdapterServiceConfig: Adding HealthService
09-29 07:15:58.418  5974  5974 D AdapterServiceConfig: Adding PanService
09-29 07:15:58.418  5974  5974 D AdapterServiceConfig: Adding GattService
09-29 07:15:58.419  5974  5974 D AdapterServiceConfig: Adding BluetoothMapService
09-29 07:15:58.419  5974  5974 D AdapterServiceConfig: Adding SapService
,09-29 07:15:58.431   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3833b08:true
,09-29 07:15:58.432  5974  5974 D BluetoothAdapterState: make() - Creating AdapterState
,09-29 07:15:58.435  5974  5974 I bt_bluedroid: init
,09-29 07:15:58.435  5974  5986 I BluetoothAdapterState: Entering OffState
,09-29 07:15:58.437  5974  5987 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-29 07:15:58.437  5974  5987 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-29 07:15:58.437  5974  5987 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-29 07:15:58.437  5974  5987 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-29 07:15:58.439  5974  5974 I bt_bluedroid: get_profile_interface socket
,09-29 07:15:58.440  5974  5990 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 07:15:58.441  5974  5974 I bt_bluedroid: get_profile_interface sdp
09-29 07:15:58.442  5974  5990 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 07:15:58.446  5974  5985 I bt_bluedroid: config_hci_snoop_log
09-29 07:15:58.447   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-29 07:15:58.452  5974  5986 D BluetoothAdapterState: Current state: OFF, message: 0
,09-29 07:15:58.453  5974  5986 D BluetoothAdapterProperties: Setting state to 14
09-29 07:15:58.453  5974  5986 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-29 07:15:58.454  5974  5986 D BluetoothBondStateMachine: make
,09-29 07:15:58.457  5974  5991 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-29 07:15:58.459  5974  5986 I BluetoothAdapterState: Entering PendingCommandState
,09-29 07:15:58.461  5974  5974 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-29 07:15:58.463  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:58.464  5974  5974 D BtGatt.DebugUtils: handleDebugAction() action=null
09-29 07:15:58.464  5974  5974 D BtGatt.GattService: Received start request. Starting profile...
09-29 07:15:58.465  5974  5974 D BtGatt.GattService: start()
09-29 07:15:58.465  5974  5974 I bt_bluedroid: get_profile_interface gatt
,09-29 07:15:58.466  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:58.466  5974  5974 D BtGatt.AdvertiseManager: advertise manager created
,09-29 07:15:58.472  5974  5974 V BluetoothAdapterState: isTurningOff()=false
,09-29 07:15:58.472  5974  5974 V BluetoothAdapterState: isTurningOn()=false
09-29 07:15:58.472  5974  5974 V BluetoothAdapterState: isBleTurningOn()=true
,09-29 07:15:58.472  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:58.473  5974  5986 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-29 07:15:58.474  5974  5986 I bt_bluedroid: bt_bluedroid
09-29 07:15:58.474  5974  5987 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-29 07:15:58.475  5974  5987 I bt_hci  : start_up
,09-29 07:15:58.481  5974  5987 I bt_vendor: alloc value 0xf402f871
09-29 07:15:58.481  5974  5987 I bt_vendor: init
,09-29 07:15:58.481  5974  5987 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-29 07:15:58.481  5974  5987 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-29 07:15:58.594  5974  5987 D bt_hci  : start_up starting async portion
,09-29 07:15:58.595  5974  5994 I bt_hci  : event_finish_startup
,09-29 07:15:58.595  5974  5994 I bt_hci_h4: hal_open
,09-29 07:15:58.595  5974  5994 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-29 07:15:58.591  5995  5995 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 07:15:58.597  5974  5994 I bt_userial_vendor: device fd = 54 open
,09-29 07:15:58.613  5974  5994 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 07:15:58.616  5974  5994 D bt_hwcfg: Chipset BCM4358A3
,09-29 07:15:58.617  5974  5994 D bt_hwcfg: Target name = [BCM4358A3]
09-29 07:15:58.618  5974  5994 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-29 07:15:59.124  5974  5994 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-29 07:15:59.125  5974  5994 D bt_hwcfg: Settlement delay -- 100 ms
,09-29 07:15:59.125  5974  5994 I bt_hwcfg: Setting fw settlement delay to 100 
,09-29 07:15:59.259  5974  5994 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-29 07:15:59.259  5974  5994 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-29 07:15:59.261  5974  5994 I bt_hwcfg: vendor lib fwcfg completed
,09-29 07:15:59.262  5974  5994 I bt_vendor: firmware callback
,09-29 07:15:59.262  5974  5994 I bt_hci  : firmware_config_callback
,09-29 07:15:59.271  5974  5997 I bt_btu  : btu_task pending for preload complete event
,09-29 07:15:59.272  5974  5997 I bt_btu_task: Bluetooth chip preload is complete
09-29 07:15:59.272  5974  5997 I bt_btu  : btu_task received preload complete event
,09-29 07:15:59.278  5974  5997 I         : BTE_InitTraceLevels -- TRC_HCI
09-29 07:15:59.278  5974  5997 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-29 07:15:59.278  5974  5997 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-29 07:15:59.278  5974  5997 I         : BTE_InitTraceLevels -- TRC_AVDT
09-29 07:15:59.278  5974  5997 I         : BTE_InitTraceLevels -- TRC_AVRC
09-29 07:15:59.278  5974  5997 I         : BTE_InitTraceLevels -- TRC_A2D
09-29 07:15:59.278  5974  5997 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_BTM
09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_GAP
09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_PAN
09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_SDP
09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_GATT
,09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_SMP
09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-29 07:15:59.279  5974  5997 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-29 07:15:59.372  5974  5997 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fad549
09-29 07:15:59.373  5974  5997 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fad549 
,09-29 07:15:59.392  5974  5990 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-29 07:15:59.395  5974  5990 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-29 07:15:59.396  5974  5990 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-29 07:15:59.399  5974  5990 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-29 07:15:59.402  5974  5990 D BluetoothAdapterProperties: Scan Mode:20
,09-29 07:15:59.403  5974  5990 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 07:15:59.403  5974  5990 D bt_hci  : do_postload posting postload work item
09-29 07:15:59.403  5974  5994 I bt_hci  : event_postload
09-29 07:15:59.403  5974  5994 I bt_vendor: sco_config_cb
09-29 07:15:59.403  5974  5994 I bt_hci  : sco_config_callback postload finished.
09-29 07:15:59.406  5974  5990 D bt_bte_conf: Device ID record 1 : primary
,09-29 07:15:59.406  5974  5990 D bt_bte_conf:   vendorId            = 000f
09-29 07:15:59.406  5974  5990 D bt_bte_conf:   vendorIdSource      = 0001
09-29 07:15:59.406  5974  5990 D bt_bte_conf:   product             = 1200
09-29 07:15:59.406  5974  5990 D bt_bte_conf:   version             = 1436
,09-29 07:15:59.406  5974  5990 D bt_bte_conf:   clientExecutableURL = 
09-29 07:15:59.406  5974  5990 D bt_bte_conf:   serviceDescription  = 
09-29 07:15:59.407  5974  5990 D bt_bte_conf:   documentationURL    = 
09-29 07:15:59.407  5974  5990 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-29 07:15:59.407  5974  5987 D bt_stack_manager: event_start_up_stack finished
09-29 07:15:59.408  5974  5986 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-29 07:15:59.408  5974  5986 D BluetoothAdapterProperties: Setting state to 15
09-29 07:15:59.408  5974  5986 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-29 07:15:59.409  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:59.412  5974  5986 I BluetoothAdapterState: Entering BleOnState
09-29 07:15:59.413  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:59.415  5974  5986 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-29 07:15:59.415  5974  5986 D BluetoothAdapterProperties: Setting state to 11
09-29 07:15:59.415  5974  5986 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-29 07:15:59.417  5974  5994 I bt_vendor: low_power_mode_cb
,09-29 07:15:59.422  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:59.424  5974  5974 D HeadsetService: Received start request. Starting profile...
09-29 07:15:59.426  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:59.428  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:59.429  5974  5974 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-29 07:15:59.429  5974  5974 D HeadsetStateMachine: make
,09-29 07:15:59.439  5974  5974 D HeadsetStateMachine: max_hf_connections = 1
,09-29 07:15:59.439  5974  5974 I bt_bluedroid: get_profile_interface handsfree
09-29 07:15:59.440  5974  5990 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-29 07:15:59.440  5974  5990 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-29 07:15:59.443  5974  5986 I BluetoothAdapterState: Entering PendingCommandState
09-29 07:15:59.444  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:59.444  5974  5974 D A2dpService: Received start request. Starting profile...
09-29 07:15:59.445  5974  5974 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-29 07:15:59.445  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-29 07:15:59.446  5974  5974 I bt_bluedroid: get_profile_interface avrcp
,09-29 07:15:59.451  5974  5974 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-29 07:15:59.452  5974  5974 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-29 07:15:59.452  5974  5974 D A2dpStateMachine: make
09-29 07:15:59.453  5974  5974 I bt_bluedroid: get_profile_interface a2dp
09-29 07:15:59.453  5974  5990 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-29 07:15:59.458  5974  6005 D A2dpStateMachine: Enter Disconnected: -2
,09-29 07:15:59.458  5974  5974 I BluetoothHidServiceJni: classInitNative: succeeds
,09-29 07:15:59.459  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:59.460  5974  5974 D HidService: Received start request. Starting profile...
09-29 07:15:59.460  5974  5974 I bt_bluedroid: get_profile_interface hidhost
09-29 07:15:59.460  5974  5990 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f8e56d
09-29 07:15:59.460  5974  5974 D HidService: setHidService(): set to: null
09-29 07:15:59.460  5974  5990 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-29 07:15:59.461  5974  5974 I BluetoothHealthServiceJni: classInitNative: succeeds
09-29 07:15:59.462  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:59.462  5974  5974 D HealthService: Received start request. Starting profile...
,09-29 07:15:59.464  5974  5974 I bt_bluedroid: get_profile_interface health
,09-29 07:15:59.466  5974  5974 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-29 07:15:59.467  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:59.467  5974  5974 D PanService: Received start request. Starting profile...
09-29 07:15:59.467  5974  5974 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-29 07:15:59.467  5974  5974 I bt_bluedroid: get_profile_interface pan
09-29 07:15:59.470  5974  5990 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-29 07:15:59.470  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
,09-29 07:15:59.471  5974  5974 D BluetoothMapService: Received start request. Starting profile...
09-29 07:15:59.471  5974  5974 D BluetoothMapService: start()
09-29 07:15:59.474  5974  5974 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-29 07:15:59.475  5974  5974 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-29 07:15:59.475  5974  5974 D BluetoothMapAppObserver: createReceiver()
,09-29 07:15:59.476  5974  5974 D BluetoothMapAppObserver: initObservers()
09-29 07:15:59.476  5974  5974 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-29 07:15:59.483  5974  5974 V BluetoothAdapterState: isTurningOff()=false
,09-29 07:15:59.483  5974  5974 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:59.483  5974  5974 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:59.483  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 07:15:59.484  5974  6003 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-29 07:15:59.485  5974  5974 V SapService: SapBinder()
09-29 07:15:59.485  5974  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:15:59.486  5974  5974 D SapService: Received start request. Starting profile...
09-29 07:15:59.486  5974  5974 V SapService: start()
,09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOff()=false
,09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
,09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOff()=false
,09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOn()=true
,09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:59.488  5974  5974 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:59.489  5974  5974 V BluetoothAdapterState: isBleTurningOn()=false
,09-29 07:15:59.489  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:59.489  5974  5974 V BluetoothAdapterState: isTurningOff()=false
09-29 07:15:59.489  5974  5974 V BluetoothAdapterState: isTurningOn()=true
09-29 07:15:59.489  5974  5974 V BluetoothAdapterState: isBleTurningOn()=false
09-29 07:15:59.490  5974  5974 V BluetoothAdapterState: isBleTurningOff()=false
09-29 07:15:59.490  5974  5986 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-29 07:15:59.490  5974  5986 D BluetoothAdapterProperties: ScanMode =  20
,09-29 07:15:59.490  5974  5986 D BluetoothAdapterProperties: State =  11
09-29 07:15:59.490  5974  5986 D BluetoothAdapterProperties: Setting state to 12
09-29 07:15:59.490  5974  5986 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-29 07:15:59.491  5974  5986 I BluetoothAdapterState: Entering OnState
09-29 07:15:59.491  5749  5761 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:59.492  5749  5763 D BluetoothPbap: onBluetoothStateChange: up=true
,09-29 07:15:59.493  5974  5990 D BluetoothAdapterProperties: Scan Mode:21
09-29 07:15:59.493  5974  5990 D BluetoothAdapterProperties: Discoverable Timeout:120
09-29 07:15:59.493  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 07:15:59.494   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 07:15:59.495  3221  3236 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:59.495   929   929 D BluetoothA2dp: Proxy object connected
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:59.498  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:59.498   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:59.498  3221  3447 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 07:15:59.500  3221  3234 D BluetoothPbap: onBluetoothStateChange: up=true
09-29 07:15:59.501  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:15:59.501  3221  3221 D BluetoothInputDevice: Proxy object connected
09-29 07:15:59.501  3221  3221 D HidProfile: Bluetooth service connected
09-29 07:15:59.502  5749  5761 D BluetoothMap: onBluetoothStateChange: up=true
09-29 07:15:59.504  5974  5974 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-29 07:15:59.504   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:59.504  3221  3447 D BluetoothMap: onBluetoothStateChange: up=true
09-29 07:15:59.504  5974  5974 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:15:59.505  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-29 07:15:59.506  5974  5974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 07:15:59.507  3221  3236 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 07:15:59.508  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:15:59.508  5974  5974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-29 07:15:59.509  3221  3221 D BluetoothA2dp: Proxy object connected
09-29 07:15:59.509  5749  5763 D BluetoothPan: onBluetoothStateChange on: true
09-29 07:15:59.510  5974  5974 D ObexServerSockets: Succeed to create listening sockets 
09-29 07:15:59.511  5974  5974 D ObexServerSockets0: startAccept()
09-29 07:15:59.511  5974  5974 D ObexServerSockets0: prepareForNewConnect()
09-29 07:15:59.512  3891  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:59.513  5974  5974 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-29 07:15:59.513  5974  5974 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-29 07:15:59.513  5749  5761 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-29 07:15:59.514  5974  6012 D ObexServerSockets0: Accepting socket connection...
,09-29 07:15:59.514  3221  3221 D BluetoothMap: Proxy object connected
09-29 07:15:59.514  3221  3221 D MapProfile: Bluetooth service connected
09-29 07:15:59.514  3221  3221 D BluetoothMap: getConnectedDevices()
09-29 07:15:59.515  5974  6013 D ObexServerSockets0: Accepting socket connection...
09-29 07:15:59.516   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-29 07:15:59.516  5749  5763 D BluetoothA2dp: onBluetoothStateChange: up=true
09-29 07:15:59.518  3221  3234 D BluetoothPan: onBluetoothStateChange on: true
,09-29 07:15:59.520  3221  3221 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 07:15:59.520  3221  3221 D PanProfile: Bluetooth service connected
,09-29 07:15:59.521  5749  5749 D BluetoothMap: Proxy object connected
,09-29 07:15:59.521  5749  5749 D MapProfile: Bluetooth service connected
09-29 07:15:59.521  5749  5749 D BluetoothMap: getConnectedDevices()
09-29 07:15:59.521   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-29 07:15:59.522  5695  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-29 07:15:59.522  5974  5974 D BluetoothMapService: onReceive
09-29 07:15:59.522  5974  5974 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-29 07:15:59.522  5974  5974 D BluetoothMapService: STATE_ON
09-29 07:15:59.523  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:15:59.525  5974  6015 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 07:15:59.526  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:15:59.526  5974  6015 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-29 07:15:59.527  5974  6015 D BluetoothSdpJni: SDP Create record success - handle: 1
09-29 07:15:59.527  5749  5749 D BluetoothPan: BluetoothPAN Proxy object connected
09-29 07:15:59.527  5749  5749 D PanProfile: Bluetooth service connected
09-29 07:15:59.527  5749  5749 D BluetoothInputDevice: Proxy object connected
09-29 07:15:59.527  5749  5749 D HidProfile: Bluetooth service connected
,09-29 07:15:59.528  5749  5749 D BluetoothA2dp: Proxy object connected
,09-29 07:15:59.534  5749  5749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-29 07:15:59.540  3690  3690 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-29 07:15:59.541  5749  5749 D DockEventReceiver: finishStartingService: stopping service
,09-29 07:15:59.547  5974  5974 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-29 07:15:59.547  5974  5974 D ObexServerSockets0: prepareForNewConnect()
09-29 07:15:59.548  5749  5749 D BluetoothPbap: Proxy object connected
09-29 07:15:59.548  5749  5749 D PbapServerProfile: Bluetooth service connected
,09-29 07:15:59.549  3221  3221 D BluetoothPbap: Proxy object connected
,09-29 07:15:59.550  3221  3221 D PbapServerProfile: Bluetooth service connected
,09-29 07:15:59.559  5974  6019 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 07:15:59.571  5974  6023 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-29 07:15:59.572  5974  6023 I BtOppRfcommListener: Accept thread started.
,09-29 07:15:59.593   929   929 D BluetoothHeadset: Proxy object connected
,09-29 07:15:59.593   929   929 D BluetoothHeadset: Proxy object connected
,09-29 07:15:59.594  5749  6014 D BluetoothHeadset: Proxy object connected
09-29 07:15:59.594  3221  3234 D BluetoothHeadset: Proxy object connected
09-29 07:15:59.594   929   929 D BluetoothHeadset: Proxy object connected
09-29 07:15:59.594  3221  3221 D HeadsetProfile: Bluetooth service connected
09-29 07:15:59.595  3891  3911 D BluetoothHeadset: Proxy object connected
09-29 07:15:59.597  5749  5749 D HeadsetProfile: Bluetooth service connected
09-29 07:15:59.598  3221  3236 D BluetoothHeadset: Proxy object connected
09-29 07:15:59.598  3221  3221 D HeadsetProfile: Bluetooth service connected
,09-29 07:15:59.599   929   946 D BluetoothHeadset: Proxy object connected
,09-29 07:15:59.605   929   946 D BluetoothHeadset: Proxy object connected
,09-29 07:15:59.613  3891  4107 D BluetoothHeadset: Proxy object connected
,09-29 07:15:59.616   929   946 D BluetoothHeadset: Proxy object connected
,09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:16:03.320  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:16:03.326  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:16:03.326  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:03.327  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a11c56 removed from the list
09-29 07:16:03.327  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
,09-29 07:16:03.327  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:03.327  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:16:03.329  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:03.329  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cbf74d7 added. We now have 4 listener(s)
,09-29 07:16:03.329  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:16:03.333   929   939 D WifiService: setWifiEnabled: false pid=5695, uid=10077
09-29 07:16:03.333   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 07:16:05.341   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:06.342   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:07.343   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:08.344  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:08.344   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:08.345   929  3901 D WifiService: setWifiEnabled: true pid=5695, uid=10077
,09-29 07:16:08.345   929  3901 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-29 07:16:08.352   508   928 D SoftapController: Softap fwReload - Ok
,09-29 07:16:08.358   508   928 D CommandListener: Setting iface cfg
09-29 07:16:08.358   508   928 D CommandListener: Trying to bring down wlan0
,09-29 07:16:08.359   508   928 D CommandListener: Clearing all IP addresses on wlan0
,09-29 07:16:08.363   929  3054 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-29 07:16:09.031   929  3054 D wifi    : set interface wlan0 flags (UP)
,09-29 07:16:09.032   929  3054 I WifiHAL : Initializing wifi
09-29 07:16:09.032   929  3054 I WifiHAL : Creating socket
,09-29 07:16:09.040   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-29 07:16:09.041   929  3054 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-29 07:16:09.041   929  3054 D wifi    : Did set static halHandle = 0x7f7db27400
,09-29 07:16:09.041   929  3054 D wifi    : halHandle = 0x7f7db27400, mVM = 0x7f9a10d140, mCls = 0x20152e
09-29 07:16:09.041   929  3054 D wifi    : array field set
09-29 07:16:09.042   929  3054 I WifiNative-HAL: interface[0] = wlan0
,09-29 07:16:09.045   929  6028 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547569693696
09-29 07:16:09.046   929  6028 D wifi    : waitForHalEvents called, vm = 0x7f9a10d140, obj = 0x20152e, env = 0x7f7adbfb80
,09-29 07:16:09.104  6029  6029 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-29 07:16:09.126  6029  6029 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-29 07:16:09.146   929  3054 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-29 07:16:09.155  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:16:09.161  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:16:09.166  6029  6029 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-29 07:16:09.166  6029  6029 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-29 07:16:09.180   929  3054 D WifiConfigStore: Loading config and enabling all networks 
,09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:16:09.183  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:16:09.185  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:16:09.190  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:16:09.192  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-29 07:16:09.195   929  3054 D WifiConfigStore: loaded 0 passpoint configs
,09-29 07:16:09.195   929  3054 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-29 07:16:09.196   929  3054 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-29 07:16:09.197   929  3054 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-29 07:16:09.198   929  3054 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-29 07:16:09.198   929  3054 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-29 07:16:09.199   929  3054 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-29 07:16:09.199   929  3054 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-29 07:16:09.203   929  3054 D WifiNative-HAL: Setting external_sim to 1
09-29 07:16:09.203  4508  4508 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-29 07:16:09.203   929  3054 D wifi    : setting dfs flag to true, 0x7f7fb98aa0
09-29 07:16:09.203   929  3054 D WifiStateMachine: Setting OUI to DA-A1-19
09-29 07:16:09.204   929  3054 D wifi    : setting scan oui 0x7f7fb98aa0
09-29 07:16:09.204   929  3054 D WifiHAL : Sending mac address OUI
,09-29 07:16:09.209   929  3054 E native  : do suspend false
,09-29 07:16:09.217   929  3054 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-29 07:16:09.217   929   929 D RttService: SCAN_AVAILABLE : 3
09-29 07:16:09.218   508   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-29 07:16:09.218   929  3162 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-29 07:16:09.219   508   928 D CommandListener: Setting iface cfg
,09-29 07:16:09.224   929  3053 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
09-29 07:16:09.224   929  3053 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-29 07:16:09.234   929  3053 D WifiNative-HAL: p2pGetDeviceAddress
,09-29 07:16:09.239   929  3053 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-29 07:16:09.239   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=302411 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,09-29 07:16:09.345   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:10.345   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-29 07:16:12.382  6029  6029 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:16:12.387  6029  6029 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:16:12.392  6029  6029 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:16:12.448   929  3054 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-29 07:16:12.449   929  3054 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-29 07:16:12.449   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 07:16:12.462   929  3054 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-29 07:16:12.493   929  3054 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-29 07:16:12.495  6029  6029 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-29 07:16:13.067  6029  6029 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-29 07:16:13.185  6029  6029 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-29 07:16:13.186  6029  6029 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-29 07:16:13.200   929  3054 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-29 07:16:13.201   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 07:16:13.201   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-29 07:16:13.217   929  3054 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-29 07:16:13.232   508   928 D CommandListener: Setting iface cfg
,09-29 07:16:13.238   929  3054 D WifiStateMachine: Start Dhcp Watchdog 3
,09-29 07:16:13.245   929  6034 D DhcpClient: Receive thread started
,09-29 07:16:13.249   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:13.249   929  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-29 07:16:13.249   929  3056 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-29 07:16:13.330   929  3054 E native  : do suspend false
,09-29 07:16:13.343   929  6033 D DhcpClient: Broadcasting DHCPDISCOVER
,09-29 07:16:13.357   929  6034 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,09-29 07:16:13.357   929  6033 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,09-29 07:16:13.359   929  6033 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-29 07:16:13.361  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-29 07:16:13.366  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-29 07:16:13.366  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:13.367  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cbf74d7 removed from the list
09-29 07:16:13.367  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:16:13.367  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:13.367  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:16:13.373  5695  6035 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-29 07:16:13.373  5695  6035 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 07:16:13.379   929  6034 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-29 07:16:13.379   929  6033 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-29 07:16:13.382   508   928 D CommandListener: Setting iface cfg
,09-29 07:16:13.385   929  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-29 07:16:13.389   929  6033 D DhcpClient: Scheduling renewal in 86399s
,09-29 07:16:13.395   929  3054 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-29 07:16:13.396   929  3054 D WifiConfigStore: No blacklist allowed without epno enabled
09-29 07:16:13.396   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-29 07:16:13.402   929  3056 D ConnectivityService: Adding iface wlan0 to network 102
09-29 07:16:13.405   929  3054 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-29 07:16:13.445   929  3056 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-29 07:16:13.446   929  3056 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-29 07:16:13.451   929  3056 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-29 07:16:13.454   929  3056 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-29 07:16:13.456   929  3056 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-29 07:16:13.462   929  3056 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:13.467   929  3056 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-29 07:16:13.467   929  3056 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-29 07:16:13.467   929  3056 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:13.467   929  3054 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-29 07:16:13.467   929  3056 D ConnectivityService:    accepting network in place of null
09-29 07:16:13.467   929  3054 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-29 07:16:13.468   929  3056 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-29 07:16:13.492   929  6032 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-29 07:16:13.498   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 07:16:13.527   508   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-29 07:16:13.531   929  3056 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-29 07:16:13.531   929  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-29 07:16:13.531  3840  3975 W QCNEJ   : |CORE| network available: 102
09-29 07:16:13.532   929  3056 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-29 07:16:13.533  3840  3975 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-29 07:16:13.533   929   946 D Tethering: MasterInitialState.processMessage what=3
09-29 07:16:13.535  3840  3975 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-29 07:16:13.535  3840  3975 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:16:13.546  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:16:13.546  5112  5129 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-29 07:16:13.546  5112  5129 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-29 07:16:13.546  5112  5129 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-29 07:16:13.546  5112  5129 E SarControlService: no key has been found,reset the power
,09-29 07:16:13.547  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-29 07:16:13.547  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-29 07:16:13.548  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-29 07:16:13.549  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:16:13.549  5139  5139 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-29 07:16:13.549  5112  5151 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-29 07:16:13.549  5112  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-29 07:16:13.549  5112  5151 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-29 07:16:13.549  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:13.550  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-29 07:16:13.550  5139  5139 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-29 07:16:13.553  4144  4144 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:16:13.554  5695  5695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:16:13.556  5695  5695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:13.556  4144  4144 D SystemUpdateService: onCreate
09-29 07:16:13.557  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000f003000000000000ffffffff]
09-29 07:16:13.557  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-29 07:16:13.557  5139  5153 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-29 07:16:13.558  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-29 07:16:13.558  5112  5123 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-29 07:16:13.560  4144  4144 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-29 07:16:13.563  5139  5153 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a479a46 HexData = [00000000f103000000000000ffffffff]
,09-29 07:16:13.563  5139  5153 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-29 07:16:13.563  5139  5153 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,09-29 07:16:13.564  5139  5139 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-29 07:16:13.564  5112  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-29 07:16:13.570  4144  4144 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-29 07:16:13.579  4144  5469 I iu.UploadsManager: num queued entries: 0
,09-29 07:16:13.580  4144  5469 I iu.UploadsManager: num updated entries: 0
09-29 07:16:13.580  4144  5469 I iu.SyncManager: NEXT; no task
,09-29 07:16:13.582  4144  4144 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-29 07:16:13.583  4144  4144 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-29 07:16:13.585  5828  5828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-29 07:16:13.588  5828  5828 D SprintDMHelper: simOperator: 
09-29 07:16:13.588  5828  5828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-29 07:16:13.588  4144  6045 I SystemUpdateService: active receiver: enabled
,09-29 07:16:13.615  4144  6045 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-29 07:16:13.623  4144  6045 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-29 07:16:13.623  4144  6045 I SystemUpdateService: now status is 0 (complete)
09-29 07:16:13.623  4144  6045 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-29 07:16:13.623  4144  6045 I SystemUpdateService: file has been verified
09-29 07:16:13.623  4144  6045 I SystemUpdateService: OTA package size = 21989297
,09-29 07:16:13.629  4144  6045 I SystemUpdateService: showing system update notification
,09-29 07:16:13.638  4144  4144 D SystemUpdateService: onDestroy
,09-29 07:16:16.266   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:16.383  5695  6054 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-29 07:16:16.383  5695  6035 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-29 07:16:16.384  5695  6054 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-29 07:16:16.384  5695  6035 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-29 07:16:16.385  5695  6054 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:16.386  5695  6035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:16.386  5695  6054 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:16.389  5695  6035 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:16.389  5695  6054 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-29 07:16:16.393  5695  6056 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:16.393  5695  6056 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 07:16:16.394  5695  6058 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:16.394  5695  6058 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 07:16:16.395  5695  6035 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 07:16:16.396  5695  6058 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:16.396  5695  6058 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 07:16:16.397  5695  6058 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:16.397  5695  6058 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 07:16:16.397  5695  6058 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-29 07:16:16.397  5695  6058 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 07:16:16.397  5695  6057 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:16.397  5695  6057 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:16.398  5695  6058 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 07:16:16.398  5695  6058 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 07:16:16.398  5695  6057 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 153, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:16.398  5695  6057 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:16.398  5695  6057 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:16.398  5695  6057 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:16.398  5695  6058 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 07:16:16.399  5695  6057 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 07:16:16.399  5695  6057 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-29 07:16:16.399  5695  6057 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 07:16:16.399  5695  6057 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 07:16:16.399  5695  6057 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 07:16:16.399  5695  6057 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-29 07:16:16.399  5695  6058 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-29 07:16:16.399  5695  6056 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 154, thread name: IncomingSocketThread/Sender): Socket closed
09-29 07:16:16.400  5695  6057 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:16.400  5695  6057 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 07:16:16.400  5695  6058 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:16.400  5695  6058 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-29 07:16:16.400  5695  6056 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:16.400  5695  6056 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-29 07:16:16.400  5695  6056 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-29 07:16:16.400  5695  6059 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:16.400  5695  6059 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:16.400  5695  6056 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-29 07:16:16.400  5695  6056 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:16.400  5695  6056 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-29 07:16:16.402  5695  6059 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 07:16:16.403  5695  6059 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 07:16:16.403  5695  6059 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 07:16:16.403  5695  6059 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-29 07:16:16.403  5695  6059 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:16.403  5695  6059 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 07:16:18.561   929  6031 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-29 07:16:18.625   929  6031 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 29 Sep 2016 11:16:18 GMT], X-Android-Received-Millis=[1475147778623], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475147778596]}
09-29 07:16:18.626   929  3056 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-29 07:16:18.627   929  3056 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-29 07:16:18.627   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:18.632   929  3056 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-29 07:16:18.700  4508  6050 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-29 07:16:19.383  5695  5741 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-29 07:16:19.385  5695  5741 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-29 07:16:19.392  5695  5741 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a406c2a Bundle[{}]
,09-29 07:16:19.392  5695  5741 I io.jxcore.node.LifeCycleMonitor: start: OK
09-29 07:16:19.393  5695  5741 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-29 07:16:19.395  5695  5741 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-29 07:16:19.395  5695  5741 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-29 07:16:19.396  5695  5741 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-29 07:16:19.398  5695  5741 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-29 07:16:19.404  5695  5741 I System.out: Running OutgoingSocketThread
,09-29 07:16:19.406  5695  6063 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-29 07:16:19.406  5695  6063 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-29 07:16:21.470   929  3056 D ConnectivityService: handlePromptUnvalidated 102
,09-29 07:16:22.418  5695  6063 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-29 07:16:22.418  5695  6064 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-29 07:16:22.418  5695  6064 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-29 07:16:22.418  5695  6063 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-29 07:16:22.419  5695  6063 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:22.419  5695  6064 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:22.420  5695  6063 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:22.420  5695  6064 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-29 07:16:22.421  5695  6063 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-29 07:16:22.422  5695  6064 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-29 07:16:22.423  5695  6066 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:22.423  5695  6066 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:22.425  5695  6067 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:22.425  5695  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 07:16:22.427  5695  6068 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:22.427  5695  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:22.428  5695  6069 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:22.428  5695  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-29 07:16:22.429  5695  6069 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:22.429  5695  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 07:16:22.429  5695  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:22.429  5695  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-29 07:16:22.429  5695  6068 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:22.429  5695  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:22.429  5695  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 07:16:22.429  5695  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 07:16:22.429  5695  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:22.429  5695  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:22.430  5695  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 07:16:22.430  5695  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 07:16:22.430  5695  6068 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 07:16:22.430  5695  6068 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 07:16:22.430  5695  6068 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-29 07:16:22.430  5695  6067 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 166, thread name: IncomingSocketThread/Sender): Socket closed
09-29 07:16:22.430  5695  6069 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 07:16:22.430  5695  6068 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-29 07:16:22.430  5695  6069 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 07:16:22.430  5695  6067 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 166, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:22.430  5695  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 07:16:22.430  5695  6068 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:22.430  5695  6068 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 07:16:22.430  5695  6069 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 07:16:22.430  5695  6067 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-29 07:16:22.431  5695  6069 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-29 07:16:22.431  5695  6067 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-29 07:16:22.431  5695  6069 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-29 07:16:22.431  5695  6069 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 07:16:22.431  5695  6067 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:22.431  5695  6067 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-29 07:16:22.431  5695  6066 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 165, thread name: OutgoingSocketThread/Sender): Socket closed
09-29 07:16:22.431  5695  6066 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:22.431  5695  6066 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-29 07:16:22.431  5695  6066 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-29 07:16:22.431  5695  6066 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-29 07:16:22.431  5695  6066 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-29 07:16:22.431  5695  6066 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-29 07:16:24.236   929  3054 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,09-29 07:16:25.416  5695  5741 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-29 07:16:25.418  5695  5741 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-29 07:16:25.418  5695  5741 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,09-29 07:16:25.426  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 07:16:25.426  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86871c4 added. We now have 3 listener(s)
,09-29 07:16:25.429  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 07:16:25.430  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 07:16:25.430  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.430  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.430  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ba58ad added. We now have 4 listener(s)
09-29 07:16:25.430  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:16:25.431  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 07:16:25.438  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:16:25.445  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-29 07:16:25.447  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.447  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:16:25.447  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.447  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91c8773 added. We now have 4 listener(s)
09-29 07:16:25.449  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.449  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:16:25.449  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.450  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.450  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85ce630 added. We now have 5 listener(s)
09-29 07:16:25.450  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:16:25.450  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:16:25.450  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:25.450  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:25.450  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:16:25.450  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.450  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.450  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.450  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.450  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.451  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86871c4 removed from the list
09-29 07:16:25.451  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.451  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ba58ad removed from the list
09-29 07:16:25.454  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:25.454  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:16:25.454  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.455  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.455  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.457  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.457  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:16:25.457  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.457  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8ba58ad not in the list
09-29 07:16:25.457  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.457  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:16:25.458  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 07:16:25.458  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.458  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.458  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85ce630 removed from the list
09-29 07:16:25.458  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.459  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.459  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.459  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 07:16:25.459  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.459  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@91c8773 removed from the list
09-29 07:16:25.459  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.459  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d2a9 added. We now have 3 listener(s)
09-29 07:16:25.461  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.462  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:16:25.462  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.462  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.462  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf602e added. We now have 4 listener(s)
09-29 07:16:25.462  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:16:25.462  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 07:16:25.465  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:16:25.470  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:16:25.472  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:16:25.473  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:16:25.473  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.473  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2355c added. We now have 4 listener(s)
09-29 07:16:25.474  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.475  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:16:25.475  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.475  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.475  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@baf065 added. We now have 5 listener(s)
09-29 07:16:25.475  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:16:25.475  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:16:25.475  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 07:16:25.475  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 07:16:25.475  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:16:25.475  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 07:16:25.476  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:16:25.478  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:25.479  5695  5741 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 07:16:25.479  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 07:16:25.482  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 07:16:25.483  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 07:16:25.483  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 07:16:25.486  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 07:16:25.487  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 07:16:25.487  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 07:16:25.487  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 07:16:25.487  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 07:16:25.487  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:16:25.490  5974  6010 D BtGatt.GattService: registerClient() - UUID=c5bd7564-82ad-4793-a3c9-2a0424354235
,09-29 07:16:25.491  5974  5990 D BtGatt.GattService: onClientRegistered() - UUID=c5bd7564-82ad-4793-a3c9-2a0424354235, clientIf=5
09-29 07:16:25.492  5695  5705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-29 07:16:25.493  5974  6011 D BtGatt.GattService: start scan with filters
,09-29 07:16:25.497  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-29 07:16:25.497  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 07:16:25.497  5974  5993 D BtGatt.ScanManager: handling starting scan
09-29 07:16:25.497  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:16:25.497  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 07:16:25.497  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 07:16:25.497  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-29 07:16:25.497  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 07:16:25.500  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 07:16:25.500  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 07:16:25.500  5974  5993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9639cff
09-29 07:16:25.500  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:16:25.501  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 07:16:25.503  5695  5741 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-29 07:16:25.503  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:25.503  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-29 07:16:25.504  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.504  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 07:16:25.504  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.504  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-29 07:16:25.504  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 07:16:25.504  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 07:16:25.504  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 07:16:25.504  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 07:16:25.504  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 07:16:25.505  5695  5741 D BluetoothAdapter: STATE_ON
,09-29 07:16:25.506  5974  5984 D BtGatt.GattService: stopScan() - queue size =1
09-29 07:16:25.506  5974  5985 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 07:16:25.507  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 07:16:25.507  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 07:16:25.507  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 07:16:25.507  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:16:25.507  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 07:16:25.507  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 07:16:25.507  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-29 07:16:25.507  5974  5990 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 07:16:25.507  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-29 07:16:25.507  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.508  5974  5993 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 07:16:25.508  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:16:25.509  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 07:16:25.509  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 07:16:25.509  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 07:16:25.509  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 07:16:25.509  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.510  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-29 07:16:25.510  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:16:25.510  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-29 07:16:25.513  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-29 07:16:25.513  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:25.513  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:16:25.513  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.513  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.513  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.513  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-29 07:16:25.514  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.514  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6d0d2a9 removed from the list
09-29 07:16:25.514  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.514  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf602e removed from the list
09-29 07:16:25.514  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:16:25.514  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.514  5974  5990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 07:16:25.514  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.514  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.514  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.515  5974  5993 D BtGatt.ScanManager: Starting BLE batch scan
09-29 07:16:25.516  5974  5993 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 07:16:25.516  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.516  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:16:25.516  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.516  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf602e not in the list
09-29 07:16:25.516  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.516  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:16:25.518  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 07:16:25.518  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.518  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.518  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@baf065 removed from the list
09-29 07:16:25.518  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.518  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.518  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.518  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.518  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-29 07:16:25.518  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2355c removed from the list
09-29 07:16:25.519  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.519  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86f2de1 added. We now have 3 listener(s)
09-29 07:16:25.520  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.521  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:16:25.521  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.521  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.521  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4574706 added. We now have 4 listener(s)
,09-29 07:16:25.521  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-29 07:16:25.522  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 07:16:25.525  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:16:25.527  5974  5990 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 07:16:25.527  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:16:25.529  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:16:25.531  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.532  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:16:25.532  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.532  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2dd3f4 added. We now have 4 listener(s)
09-29 07:16:25.532  5974  5990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 07:16:25.532  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.533  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.533  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:16:25.533  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.533  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.533  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecfc71d added. We now have 5 listener(s)
09-29 07:16:25.534  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:16:25.534  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:25.534  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-29 07:16:25.534  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:16:25.534  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 07:16:25.535  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 07:16:25.535  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-29 07:16:25.535  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 07:16:25.536  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:16:25.538  5695  5741 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 07:16:25.538  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-29 07:16:25.540  5974  5990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 07:16:25.541  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.541  5974  5993 D BtGatt.ScanManager: stopping BLe Batch
,09-29 07:16:25.542  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 07:16:25.543  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 07:16:25.543  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 07:16:25.545  5974  5990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-29 07:16:25.545  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.546  5974  5993 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 07:16:25.546  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-29 07:16:25.547  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 07:16:25.547  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 07:16:25.547  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-29 07:16:25.547  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 07:16:25.548  5695  5741 D BluetoothAdapter: STATE_ON
,09-29 07:16:25.550  5974  6002 D BtGatt.GattService: registerClient() - UUID=e8d42603-07d7-410d-afb6-180448a64f95
,09-29 07:16:25.550  5974  5990 D BtGatt.GattService: onClientRegistered() - UUID=e8d42603-07d7-410d-afb6-180448a64f95, clientIf=5
,09-29 07:16:25.551  5974  5990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 07:16:25.551  5695  5706 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-29 07:16:25.551  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.551  5974  6011 D BtGatt.GattService: start scan with filters
,09-29 07:16:25.553  5974  5993 D BtGatt.ScanManager: handling starting scan
,09-29 07:16:25.553  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-29 07:16:25.553  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 07:16:25.553  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:16:25.553  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-29 07:16:25.554  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 07:16:25.554  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 07:16:25.554  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-29 07:16:25.555  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:16:25.556  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 07:16:25.556  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:16:25.557  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-29 07:16:25.558  5974  5990 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 07:16:25.558  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.558  5974  5993 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 07:16:25.559  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:16:25.559  5695  5741 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-29 07:16:25.559  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:16:25.559  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:25.559  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:16:25.559  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.559  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:16:25.559  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-29 07:16:25.559  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.559  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.559  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86f2de1 removed from the list
09-29 07:16:25.559  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.559  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4574706 removed from the list
09-29 07:16:25.559  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:16:25.559  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.560  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.560  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-29 07:16:25.560  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.560  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.561  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.561  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:16:25.561  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.561  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4574706 not in the list
09-29 07:16:25.561  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 07:16:25.561  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-29 07:16:25.561  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 07:16:25.561  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-29 07:16:25.561  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-29 07:16:25.562  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:16:25.562  5974  6011 D BtGatt.GattService: stopScan() - queue size =1
09-29 07:16:25.563  5974  6010 D BtGatt.GattService: unregisterClient() - clientIf=5
09-29 07:16:25.563  5974  5990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 07:16:25.563  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 07:16:25.563  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.563  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 07:16:25.563  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 07:16:25.563  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:16:25.563  5974  5993 D BtGatt.ScanManager: Starting BLE batch scan
09-29 07:16:25.563  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 07:16:25.563  5974  5993 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 07:16:25.563  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 07:16:25.563  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-29 07:16:25.563  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 07:16:25.565  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:16:25.565  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 07:16:25.565  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 07:16:25.565  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 07:16:25.565  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 07:16:25.566  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.566  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:16:25.567  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-29 07:16:25.567  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:16:25.567  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:16:25.567  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecfc71d removed from the list
09-29 07:16:25.567  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:16:25.567  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.567  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:16:25.567  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.567  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:16:25.567  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.567  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.568  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2dd3f4 removed from the list
09-29 07:16:25.568  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.568  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a6b819 added. We now have 3 listener(s)
09-29 07:16:25.570  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.570  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 07:16:25.570  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.570  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.570  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6a30de added. We now have 4 listener(s)
09-29 07:16:25.570  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:16:25.571  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 07:16:25.572  5974  5990 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 07:16:25.572  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:16:25.574  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:16:25.577  5974  5990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 07:16:25.577  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:16:25.578  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:16:25.580  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.580  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-29 07:16:25.580  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.580  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4bad8c added. We now have 4 listener(s)
09-29 07:16:25.582  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.582  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:16:25.582  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.582  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-29 07:16:25.582  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b61bcd5 added. We now have 5 listener(s)
09-29 07:16:25.582  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:16:25.582  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:16:25.582  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-29 07:16:25.582  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-29 07:16:25.582  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:25.582  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:16:25.582  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-29 07:16:25.582  5974  5990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-29 07:16:25.582  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.583  5974  5993 D BtGatt.ScanManager: stopping BLe Batch
09-29 07:16:25.584  5695  5741 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-29 07:16:25.584  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-29 07:16:25.586  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:16:25.587  5974  5990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 07:16:25.587  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.587  5974  5993 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 07:16:25.588  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-29 07:16:25.588  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-29 07:16:25.588  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-29 07:16:25.591  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-29 07:16:25.591  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-29 07:16:25.592  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-29 07:16:25.592  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-29 07:16:25.592  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-29 07:16:25.592  5974  5990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-29 07:16:25.592  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.592  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:16:25.594  5974  5984 D BtGatt.GattService: registerClient() - UUID=40e5524d-2822-4724-8f1b-8a136f98efba
09-29 07:16:25.594  5974  5990 D BtGatt.GattService: onClientRegistered() - UUID=40e5524d-2822-4724-8f1b-8a136f98efba, clientIf=5
,09-29 07:16:25.594  5695  5796 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-29 07:16:25.594  5974  5985 D BtGatt.GattService: start scan with filters
09-29 07:16:25.596  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-29 07:16:25.596  5974  5993 D BtGatt.ScanManager: handling starting scan
09-29 07:16:25.596  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-29 07:16:25.596  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:16:25.596  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-29 07:16:25.596  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-29 07:16:25.596  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-29 07:16:25.596  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-29 07:16:25.598  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-29 07:16:25.598  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-29 07:16:25.598  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-29 07:16:25.599  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-29 07:16:25.601  5974  5990 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-29 07:16:25.601  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.601  5974  5993 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-29 07:16:25.603  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:16:25.603  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:25.603  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:16:25.603  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.603  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.603  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-29 07:16:25.603  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.603  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.603  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a6b819 removed from the list
09-29 07:16:25.603  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.603  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6a30de removed from the list
09-29 07:16:25.603  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:16:25.603  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.604  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:16:25.604  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-29 07:16:25.604  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.604  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.605  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.605  5974  5990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-29 07:16:25.605  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 07:16:25.605  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.605  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.606  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6a30de not in the list
09-29 07:16:25.606  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-29 07:16:25.606  5974  5993 D BtGatt.ScanManager: Starting BLE batch scan
09-29 07:16:25.606  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-29 07:16:25.606  5974  5993 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-29 07:16:25.606  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-29 07:16:25.606  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-29 07:16:25.606  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-29 07:16:25.607  5695  5741 D BluetoothAdapter: STATE_ON
09-29 07:16:25.607  5974  5984 D BtGatt.GattService: stopScan() - queue size =1
09-29 07:16:25.608  5974  5985 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-29 07:16:25.608  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-29 07:16:25.608  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-29 07:16:25.608  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-29 07:16:25.608  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-29 07:16:25.608  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-29 07:16:25.608  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-29 07:16:25.608  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-29 07:16:25.608  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-29 07:16:25.609  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:16:25.609  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-29 07:16:25.609  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-29 07:16:25.609  5695  5741 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-29 07:16:25.609  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-29 07:16:25.610  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.611  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-29 07:16:25.611  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.611  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.611  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:16:25.611  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b61bcd5 removed from the list
09-29 07:16:25.611  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.611  5695  5695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-29 07:16:25.611  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:16:25.611  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.611  5695  5695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-29 07:16:25.611  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.611  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.611  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4bad8c removed from the list
09-29 07:16:25.612  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.612  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78e5151 added. We now have 3 listener(s)
09-29 07:16:25.613  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.613  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-29 07:16:25.613  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.613  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.613  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a057db6 added. We now have 4 listener(s)
09-29 07:16:25.613  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:16:25.613  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-29 07:16:25.614  5974  5990 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-29 07:16:25.615  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.615  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:16:25.619  5974  5990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-29 07:16:25.619  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:16:25.620  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:16:25.622  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:16:25.622  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:16:25.622  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-29 07:16:25.622  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6e82224 added. We now have 4 listener(s)
09-29 07:16:25.623  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:16:25.624  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:16:25.624  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:16:25.624  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:16:25.624  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@715b18d added. We now have 5 listener(s)
09-29 07:16:25.624  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:16:25.624  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:25.624  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:16:25.624  5974  5990 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-29 07:16:25.624  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:16:25.624  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:25.624  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-29 07:16:25.625  5974  5993 D BtGatt.ScanManager: stopping BLe Batch
09-29 07:16:25.625  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.625  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:16:25.625  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-29 07:16:25.625  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.625  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.625  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78e5151 removed from the list
09-29 07:16:25.625  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.625  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a057db6 removed from the list
09-29 07:16:25.627  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:16:25.628  5695  5741 D io.jxcore.node.ConnectivityMonitor: stop
09-29 07:16:25.628  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-29 07:16:25.629  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-29 07:16:25.629  5974  5990 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-29 07:16:25.629  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-29 07:16:25.629  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.629  5974  5993 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-29 07:16:25.630  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.630  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:16:25.630  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-29 07:16:25.630  5695  5741 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a057db6 not in the list
09-29 07:16:25.630  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.630  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.631  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-29 07:16:25.631  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-29 07:16:25.631  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-29 07:16:25.631  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@715b18d removed from the list
09-29 07:16:25.631  5695  5741 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-29 07:16:25.631  5695  5741 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-29 07:16:25.631  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-29 07:16:25.631  5695  5741 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-29 07:16:25.631  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-29 07:16:25.631  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6e82224 removed from the list
09-29 07:16:25.632  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-29 07:16:25.632  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-29 07:16:25.632  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-29 07:16:25.632  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:16:25.632  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-29 07:16:25.632  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:25.633  5974  5990 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-29 07:16:25.633  5974  5990 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-29 07:16:26.011  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 07:16:26.067  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 07:16:26.111  5695  5695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-29 07:16:27.772  5695  6070 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 07:16:27.772  5695  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:28.574  5695  6070 W !!      : call onHalfStreamCopied
,09-29 07:16:28.574  5695  6070 I testCopyDataAndClose: closing input stream
,09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 186, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-29 07:16:29.349  5695  6070 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-29 07:16:31.381   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:33.102  5695  6071 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:33.102  5695  6071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:34.407   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:35.101  5695  5741 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 189. Connection data: Peer properties: [null null].
09-29 07:16:35.101  5695  5741 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:35.102  5695  5741 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 189, name: My test thread name)
,09-29 07:16:35.119  5695  6071 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-29 07:16:35.119  5695  6071 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:35.119  5695  6071 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-29 07:16:35.210  5695  6072 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 07:16:35.210  5695  6072 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:35.346   600   600 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-29 07:16:35.346   600   600 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-29 07:16:36.842  5695  6072 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 07:16:36.842  5695  6072 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:36.842  5695  6072 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:36.842  5695  6072 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:36.842  5695  6072 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 07:16:36.842  5695  6072 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 07:16:36.843  5695  6072 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 07:16:36.843  5695  6072 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-29 07:16:36.843  5695  6072 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 07:16:36.843  5695  6072 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-29 07:16:36.843  5695  6072 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-29 07:16:37.195  6029  6029 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-29 07:16:40.562  5695  6073 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:40.562  5695  6073 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-29 07:16:40.562  5695  6073 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 193, thread name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:40.562  5695  6073 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:40.563  5695  6073 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-29 07:16:40.565  5695  5741 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-29 07:16:40.568  5695  6074 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:40.568  5695  6074 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-29 07:16:40.568  5695  6074 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 197, thread name: My test thread name): Test exception.
09-29 07:16:40.569  5695  6074 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:40.569  5695  6074 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-29 07:16:40.569  5695  6074 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,09-29 07:16:40.569  5695  6074 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-29 07:16:40.569  5695  6074 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-29 07:16:40.574  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-29 07:16:40.574  5695  5741 I jxcore-log: 
09-29 07:16:40.575  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Number of passed tests:  83'
09-29 07:16:40.575  5695  5741 I jxcore-log: 
09-29 07:16:40.575  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Number of failed tests:  1'
09-29 07:16:40.575  5695  5741 I jxcore-log: 
,09-29 07:16:40.575  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-29 07:16:40.575  5695  5741 I jxcore-log: 
09-29 07:16:40.575  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Total duration:  102754'
09-29 07:16:40.575  5695  5741 I jxcore-log: 
09-29 07:16:40.576  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Failures: 
09-29 07:16:40.576  5695  5741 I jxcore-log:  IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-29 07:16:40.576  5695  5741 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-29 07:16:40.576  5695  5741 I jxcore-log:      but: was ""
09-29 07:16:40.576  5695  5741 I jxcore-log: '
09-29 07:16:40.576  5695  5741 I jxcore-log: 
09-29 07:16:40.577  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-29 07:16:40.577  5695  5741 I jxcore-log: 
,09-29 07:16:40.578  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-29 07:16:40.578  5695  5741 I jxcore-log: 
,09-29 07:16:40.581  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.581  5695  5741 I jxcore-log: 
09-29 07:16:40.582  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.582  5695  5741 I jxcore-log: 
,09-29 07:16:40.582  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.582  5695  5741 I jxcore-log: 
09-29 07:16:40.582  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.582  5695  5741 I jxcore-log: 
09-29 07:16:40.583  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-29 07:16:40.583  5695  5741 I jxcore-log: 
09-29 07:16:40.583  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 07:16:40.583  5695  5741 I jxcore-log: 
09-29 07:16:40.584  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.584  5695  5741 I jxcore-log: 
09-29 07:16:40.584  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.584  5695  5741 I jxcore-log: 
09-29 07:16:40.584  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-29 07:16:40.584  5695  5741 I jxcore-log: 
09-29 07:16:40.584  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 07:16:40.584  5695  5741 I jxcore-log: 
,09-29 07:16:40.585  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 07:16:40.585  5695  5741 I jxcore-log: 
09-29 07:16:40.585  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.585  5695  5741 I jxcore-log: 
09-29 07:16:40.585  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.585  5695  5741 I jxcore-log: 
09-29 07:16:40.585  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.585  5695  5741 I jxcore-log: 
09-29 07:16:40.585  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.585  5695  5741 I jxcore-log: 
,09-29 07:16:40.586  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.586  5695  5741 I jxcore-log: 
09-29 07:16:40.586  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.586  5695  5741 I jxcore-log: 
09-29 07:16:40.586  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.586  5695  5741 I jxcore-log: 
09-29 07:16:40.587  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.587  5695  5741 I jxcore-log: 
09-29 07:16:40.587  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.587  5695  5741 I jxcore-log: 
09-29 07:16:40.587  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.587  5695  5741 I jxcore-log: 
09-29 07:16:40.587  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.587  5695  5741 I jxcore-log: 
,09-29 07:16:40.589  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.589  5695  5741 I jxcore-log: 
09-29 07:16:40.589  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.589  5695  5741 I jxcore-log: 
09-29 07:16:40.589  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.589  5695  5741 I jxcore-log: 
09-29 07:16:40.590  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.590  5695  5741 I jxcore-log: 
09-29 07:16:40.590  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.590  5695  5741 I jxcore-log: 
09-29 07:16:40.590  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.590  5695  5741 I jxcore-log: 
09-29 07:16:40.590  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.590  5695  5741 I jxcore-log: 
09-29 07:16:40.591  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.591  5695  5741 I jxcore-log: 
,09-29 07:16:40.591  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.591  5695  5741 I jxcore-log: 
09-29 07:16:40.591  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.591  5695  5741 I jxcore-log: 
09-29 07:16:40.591  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.591  5695  5741 I jxcore-log: 
,09-29 07:16:40.592  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.592  5695  5741 I jxcore-log: 
09-29 07:16:40.592  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.592  5695  5741 I jxcore-log: 
09-29 07:16:40.592  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.592  5695  5741 I jxcore-log: 
09-29 07:16:40.592  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.592  5695  5741 I jxcore-log: 
09-29 07:16:40.592  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.592  5695  5741 I jxcore-log: 
09-29 07:16:40.593  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.593  5695  5741 I jxcore-log: 
09-29 07:16:40.593  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-29 07:16:40.593  5695  5741 I jxcore-log: 
09-29 07:16:40.593  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.593  5695  5741 I jxcore-log: 
09-29 07:16:40.593  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.593  5695  5741 I jxcore-log: 
09-29 07:16:40.593  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-29 07:16:40.593  5695  5741 I jxcore-log: 
09-29 07:16:40.594  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.594  5695  5741 I jxcore-log: 
09-29 07:16:40.594  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.594  5695  5741 I jxcore-log: 
09-29 07:16:40.594  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.594  5695  5741 I jxcore-log: 
09-29 07:16:40.594  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.594  5695  5741 I jxcore-log: 
09-29 07:16:40.595  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:16:40.595  5695  5741 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-29 07:16:40.595  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"d,oNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.595  5695  5741 I jxcore-log: 
09-29 07:16:40.595  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.595  5695  5741 I jxcore-log: 
09-29 07:16:40.595  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-29 07:16:40.595  5695  5741 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-29 07:16:40.595  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:16:40.595  5695  5741 I jxcore-log: 
09-29 07:16:40.596  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 07:16:40.596  5695  5741 I jxcore-log: 
09-29 07:16:40.596  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 07:16:40.596  5695  5741 I jxcore-log: 
09-29 07:16:40.596  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-29 07:16:40.596  5695  5741 I jxcore-log: 
09-29 07:16:40.598  5695  5695 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-29 07:16:40.601  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-29 07:16:40.601  5695  5741 I jxcore-log: 
09-29 07:16:40.602  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - WARN testUtils: 'myNameCallback not set!'
09-29 07:16:40.602  5695  5741 I jxcore-log: 
,09-29 07:16:40.603  5695  5741 I jxcore-log: 2016-09-29 11:16:40 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-29 07:16:40.603  5695  5741 I jxcore-log: 
,09-29 07:16:42.637  5695  5741 I jxcore-log: 2016-09-29 11:16:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-29 07:16:42.637  5695  5741 I jxcore-log: 
,09-29 07:16:42.977  5695  5741 I jxcore-log: 2016-09-29 11:16:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-29 07:16:42.977  5695  5741 I jxcore-log: 
,09-29 07:16:42.992  5695  5741 I jxcore-log: 2016-09-29 11:16:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-29 07:16:42.992  5695  5741 I jxcore-log: 
,09-29 07:16:43.487   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:44.084  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-29 07:16:44.084  5695  5741 I jxcore-log: 
,09-29 07:16:44.246  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-29 07:16:44.246  5695  5741 I jxcore-log: 
,09-29 07:16:44.251  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-29 07:16:44.251  5695  5741 I jxcore-log: 
,09-29 07:16:44.255  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-29 07:16:44.255  5695  5741 I jxcore-log: 
,09-29 07:16:44.802  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-29 07:16:44.802  5695  5741 I jxcore-log: 
,09-29 07:16:44.854  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-29 07:16:44.854  5695  5741 I jxcore-log: 
,09-29 07:16:44.867  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-29 07:16:44.867  5695  5741 I jxcore-log: 
,09-29 07:16:44.871  5695  5741 I jxcore-log: 2016-09-29 11:16:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-29 07:16:44.871  5695  5741 I jxcore-log: 
,09-29 07:16:45.151  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-29 07:16:45.151  5695  5741 I jxcore-log: 
,09-29 07:16:45.276  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-29 07:16:45.276  5695  5741 I jxcore-log: 
,09-29 07:16:45.510  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-29 07:16:45.510  5695  5741 I jxcore-log: 
,09-29 07:16:45.521  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-29 07:16:45.521  5695  5741 I jxcore-log: 
,09-29 07:16:45.525  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-29 07:16:45.525  5695  5741 I jxcore-log: 
,09-29 07:16:45.659  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-29 07:16:45.659  5695  5741 I jxcore-log: 
,09-29 07:16:45.666  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-29 07:16:45.666  5695  5741 I jxcore-log: 
,09-29 07:16:45.693  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-29 07:16:45.693  5695  5741 I jxcore-log: 
,09-29 07:16:45.727  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-29 07:16:45.727  5695  5741 I jxcore-log: 
,09-29 07:16:45.734  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-29 07:16:45.734  5695  5741 I jxcore-log: 
,09-29 07:16:45.741  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-29 07:16:45.741  5695  5741 I jxcore-log: 
,09-29 07:16:45.756  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-29 07:16:45.756  5695  5741 I jxcore-log: 
,09-29 07:16:45.760  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-29 07:16:45.760  5695  5741 I jxcore-log: 
,09-29 07:16:45.766  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-29 07:16:45.766  5695  5741 I jxcore-log: 
,09-29 07:16:45.771  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-29 07:16:45.771  5695  5741 I jxcore-log: 
,09-29 07:16:45.784  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-29 07:16:45.784  5695  5741 I jxcore-log: 
,09-29 07:16:45.805  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-29 07:16:45.805  5695  5741 I jxcore-log: 
,09-29 07:16:45.815  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-29 07:16:45.815  5695  5741 I jxcore-log: 
,09-29 07:16:45.825  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-29 07:16:45.825  5695  5741 I jxcore-log: 
,09-29 07:16:45.835  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-29 07:16:45.835  5695  5741 I jxcore-log: 
,09-29 07:16:45.847  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-29 07:16:45.847  5695  5741 I jxcore-log: 
,09-29 07:16:45.856  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-29 07:16:45.856  5695  5741 I jxcore-log: 
,09-29 07:16:45.861  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-29 07:16:45.861  5695  5741 I jxcore-log: 
,09-29 07:16:45.882  5695  5741 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-29 07:16:45.883  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - INFO testUtils: 'BLE multiple advertisement supported'
09-29 07:16:45.883  5695  5741 I jxcore-log: 
,09-29 07:16:45.990  5695  5741 I jxcore-log: 2016-09-29 11:16:45 - DEBUG CoordinatedClient: 'connected to the test server'
09-29 07:16:45.990  5695  5741 I jxcore-log: 
,09-29 07:16:46.485  5695  5741 I jxcore-log: TAP version 13
09-29 07:16:46.485  5695  5741 I jxcore-log: 
,09-29 07:16:46.526  5695  5741 I jxcore-log: # setup
09-29 07:16:46.526  5695  5741 I jxcore-log: 
,09-29 07:16:46.529   929  3056 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-29 07:16:47.455  5695  5741 I jxcore-log: # calling createNativeListener directly rejects
09-29 07:16:47.455  5695  5741 I jxcore-log: 
,09-29 07:16:47.485  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:47.485  5695  5741 I jxcore-log: 
,09-29 07:16:47.489  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'listening 49610'
09-29 07:16:47.489  5695  5741 I jxcore-log: 
,09-29 07:16:47.496  5695  5741 I jxcore-log: ok 1 Should throw
09-29 07:16:47.496  5695  5741 I jxcore-log: 
,09-29 07:16:47.506  5695  5741 I jxcore-log: # teardown
09-29 07:16:47.506  5695  5741 I jxcore-log: 
,09-29 07:16:47.574  5695  5741 I jxcore-log: # setup
09-29 07:16:47.574  5695  5741 I jxcore-log: 
,09-29 07:16:47.604  5695  5741 I jxcore-log: # emits incomingConnectionState
09-29 07:16:47.604  5695  5741 I jxcore-log: 
,09-29 07:16:47.649  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:47.649  5695  5741 I jxcore-log: 
,09-29 07:16:47.652  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'listening 48202'
09-29 07:16:47.652  5695  5741 I jxcore-log: 
,09-29 07:16:47.661  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:47.661  5695  5741 I jxcore-log: 
,09-29 07:16:47.663  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:47.663  5695  5741 I jxcore-log: 
,09-29 07:16:47.675  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'new mux'
09-29 07:16:47.675  5695  5741 I jxcore-log: 
,09-29 07:16:47.681  5695  5741 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-29 07:16:47.681  5695  5741 I jxcore-log: 
,09-29 07:16:47.699  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:47.699  5695  5741 I jxcore-log: 
,09-29 07:16:47.700  5695  5741 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-29 07:16:47.700  5695  5741 I jxcore-log: 
,09-29 07:16:47.709  5695  5741 I jxcore-log: # teardown
09-29 07:16:47.709  5695  5741 I jxcore-log: 
,09-29 07:16:47.751  5695  5741 I jxcore-log: # setup
09-29 07:16:47.751  5695  5741 I jxcore-log: 
,09-29 07:16:47.817  5695  5741 I jxcore-log: # emits routerPortConnectionFailed
09-29 07:16:47.817  5695  5741 I jxcore-log: 
,09-29 07:16:47.910  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:47.910  5695  5741 I jxcore-log: 
,09-29 07:16:47.913  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'listening 42930'
09-29 07:16:47.913  5695  5741 I jxcore-log: 
,09-29 07:16:47.920  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:47.920  5695  5741 I jxcore-log: 
,09-29 07:16:47.922  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:47.922  5695  5741 I jxcore-log: 
,09-29 07:16:47.924  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'new mux'
09-29 07:16:47.924  5695  5741 I jxcore-log: 
,09-29 07:16:47.954  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:47.954  5695  5741 I jxcore-log: 
,09-29 07:16:47.956  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:47.956  5695  5741 I jxcore-log: 
,09-29 07:16:47.960  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: ' $c@net.js:837:7
09-29 07:16:47.960  5695  5741 I jxcore-log: $09@net.js:829:13
09-29 07:16:47.960  5695  5741 I jxcore-log: '
09-29 07:16:47.960  5695  5741 I jxcore-log: 
,09-29 07:16:47.961  5695  5741 I jxcore-log: ok 4 tried to connect to right port
09-29 07:16:47.961  5695  5741 I jxcore-log: 
,09-29 07:16:47.962  5695  5741 I jxcore-log: ok 5 failed due to refused connection
09-29 07:16:47.962  5695  5741 I jxcore-log: 
09-29 07:16:47.963  5695  5741 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-29 07:16:47.963  5695  5741 I jxcore-log: 
09-29 07:16:47.966  5695  5741 I jxcore-log: # teardown
09-29 07:16:47.966  5695  5741 I jxcore-log: 
,09-29 07:16:47.968  5695  5741 I jxcore-log: 2016-09-29 11:16:47 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:47.968  5695  5741 I jxcore-log: 
,09-29 07:16:48.009  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'mux close'
09-29 07:16:48.009  5695  5741 I jxcore-log: 
,09-29 07:16:48.013  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:48.013  5695  5741 I jxcore-log: 
,09-29 07:16:48.022  5695  5741 I jxcore-log: # setup
09-29 07:16:48.022  5695  5741 I jxcore-log: 
,09-29 07:16:48.065  5695  5741 I jxcore-log: # native server connections all up
09-29 07:16:48.065  5695  5741 I jxcore-log: 
,09-29 07:16:48.133  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:48.133  5695  5741 I jxcore-log: 
,09-29 07:16:48.139  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'listening 40149'
09-29 07:16:48.139  5695  5741 I jxcore-log: 
,09-29 07:16:48.148  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:48.148  5695  5741 I jxcore-log: 
,09-29 07:16:48.149  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:48.149  5695  5741 I jxcore-log: 
,09-29 07:16:48.151  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new mux'
09-29 07:16:48.151  5695  5741 I jxcore-log: 
,09-29 07:16:48.179  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:48.179  5695  5741 I jxcore-log: 
,09-29 07:16:48.182  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:48.182  5695  5741 I jxcore-log: 
,09-29 07:16:48.186  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:48.186  5695  5741 I jxcore-log: 
,09-29 07:16:48.189  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:48.189  5695  5741 I jxcore-log: 
,09-29 07:16:48.213  5695  5741 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-29 07:16:48.213  5695  5741 I jxcore-log: 
,09-29 07:16:48.214  5695  5741 I jxcore-log: ok 8 Send/recvd #1 should be same
09-29 07:16:48.214  5695  5741 I jxcore-log: 
09-29 07:16:48.217  5695  5741 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-29 07:16:48.217  5695  5741 I jxcore-log: 
09-29 07:16:48.217  5695  5741 I jxcore-log: ok 10 Send/recvd #2 should be same
09-29 07:16:48.217  5695  5741 I jxcore-log: 
09-29 07:16:48.220  5695  5741 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-29 07:16:48.220  5695  5741 I jxcore-log: 
,09-29 07:16:48.228  5695  5741 I jxcore-log: # teardown
09-29 07:16:48.228  5695  5741 I jxcore-log: 
,09-29 07:16:48.263  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:48.263  5695  5741 I jxcore-log: 
,09-29 07:16:48.265  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:48.265  5695  5741 I jxcore-log: 
,09-29 07:16:48.266  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'mux close'
09-29 07:16:48.266  5695  5741 I jxcore-log: 
,09-29 07:16:48.270  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:48.270  5695  5741 I jxcore-log: 
,09-29 07:16:48.281  5695  5741 I jxcore-log: # setup
09-29 07:16:48.281  5695  5741 I jxcore-log: 
,09-29 07:16:48.323  5695  5741 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-29 07:16:48.323  5695  5741 I jxcore-log: 
,09-29 07:16:48.393  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:48.393  5695  5741 I jxcore-log: 
,09-29 07:16:48.397  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'listening 37199'
09-29 07:16:48.397  5695  5741 I jxcore-log: 
,09-29 07:16:48.405  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:48.405  5695  5741 I jxcore-log: 
,09-29 07:16:48.406  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:48.406  5695  5741 I jxcore-log: 
,09-29 07:16:48.409  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new mux'
09-29 07:16:48.409  5695  5741 I jxcore-log: 
,09-29 07:16:48.419  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:48.419  5695  5741 I jxcore-log: 
,09-29 07:16:48.422  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:48.422  5695  5741 I jxcore-log: 
,09-29 07:16:48.433  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:48.433  5695  5741 I jxcore-log: 
,09-29 07:16:48.444  5695  5741 I jxcore-log: ok 12 socket shouldn't close until after stream
09-29 07:16:48.444  5695  5741 I jxcore-log: 
,09-29 07:16:48.444  5695  5741 I jxcore-log: ok 13 incoming remains open
09-29 07:16:48.444  5695  5741 I jxcore-log: 
,09-29 07:16:48.451  5695  5741 I jxcore-log: # teardown
09-29 07:16:48.451  5695  5741 I jxcore-log: 
,09-29 07:16:48.476  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'mux close'
09-29 07:16:48.476  5695  5741 I jxcore-log: 
,09-29 07:16:48.480  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:48.480  5695  5741 I jxcore-log: 
,09-29 07:16:48.485  5695  5741 I jxcore-log: # setup
09-29 07:16:48.485  5695  5741 I jxcore-log: 
,09-29 07:16:48.561  5695  5741 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-29 07:16:48.561  5695  5741 I jxcore-log: 
,09-29 07:16:48.593  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:48.593  5695  5741 I jxcore-log: 
,09-29 07:16:48.598  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'listening 41552'
09-29 07:16:48.598  5695  5741 I jxcore-log: 
,09-29 07:16:48.605  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:48.605  5695  5741 I jxcore-log: 
,09-29 07:16:48.606  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:48.606  5695  5741 I jxcore-log: 
09-29 07:16:48.607  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new mux'
09-29 07:16:48.607  5695  5741 I jxcore-log: 
,09-29 07:16:48.617  5695  5741 I jxcore-log: ok 14 we should not have gotten an error
09-29 07:16:48.617  5695  5741 I jxcore-log: 
,09-29 07:16:48.622  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:48.622  5695  5741 I jxcore-log: 
,09-29 07:16:48.628  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:48.628  5695  5741 I jxcore-log: 
,09-29 07:16:48.637  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:48.637  5695  5741 I jxcore-log: 
,09-29 07:16:48.639  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:48.639  5695  5741 I jxcore-log: 
,09-29 07:16:48.646  5695  5741 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-29 07:16:48.646  5695  5741 I jxcore-log: 
,09-29 07:16:48.647  5695  5741 I jxcore-log: ok 16 incoming is cleaned up
09-29 07:16:48.647  5695  5741 I jxcore-log: 
,09-29 07:16:48.655  5695  5741 I jxcore-log: # teardown
09-29 07:16:48.655  5695  5741 I jxcore-log: 
,09-29 07:16:48.719  5695  5741 I jxcore-log: # setup
09-29 07:16:48.719  5695  5741 I jxcore-log: 
,09-29 07:16:48.769  5695  5741 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-29 07:16:48.769  5695  5741 I jxcore-log: 
,09-29 07:16:48.833  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:48.833  5695  5741 I jxcore-log: 
,09-29 07:16:48.837  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'listening 46844'
09-29 07:16:48.837  5695  5741 I jxcore-log: 
,09-29 07:16:48.845  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:48.845  5695  5741 I jxcore-log: 
,09-29 07:16:48.846  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:48.846  5695  5741 I jxcore-log: 
,09-29 07:16:48.850  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new mux'
09-29 07:16:48.850  5695  5741 I jxcore-log: 
,09-29 07:16:48.862  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:48.862  5695  5741 I jxcore-log: 
,09-29 07:16:48.864  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:48.864  5695  5741 I jxcore-log: 
,09-29 07:16:48.880  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:48.880  5695  5741 I jxcore-log: 
,09-29 07:16:48.889  5695  5741 I jxcore-log: ok 17 stream was closed
09-29 07:16:48.889  5695  5741 I jxcore-log: 
,09-29 07:16:48.889  5695  5741 I jxcore-log: ok 18 incoming should survive
09-29 07:16:48.889  5695  5741 I jxcore-log: 
09-29 07:16:48.889  5695  5741 I jxcore-log: ok 19 mux should have no streams
09-29 07:16:48.889  5695  5741 I jxcore-log: 
,09-29 07:16:48.895  5695  5741 I jxcore-log: # teardown
09-29 07:16:48.895  5695  5741 I jxcore-log: 
,09-29 07:16:48.917  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'mux close'
09-29 07:16:48.917  5695  5741 I jxcore-log: 
,09-29 07:16:48.927  5695  5741 I jxcore-log: 2016-09-29 11:16:48 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:48.927  5695  5741 I jxcore-log: 
,09-29 07:16:48.938  5695  5741 I jxcore-log: # setup
09-29 07:16:48.938  5695  5741 I jxcore-log: 
,09-29 07:16:49.021  5695  5741 I jxcore-log: # native server - closing the whole server cleans everything up
09-29 07:16:49.021  5695  5741 I jxcore-log: 
,09-29 07:16:49.064  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:49.064  5695  5741 I jxcore-log: 
,09-29 07:16:49.069  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'listening 38732'
09-29 07:16:49.069  5695  5741 I jxcore-log: 
,09-29 07:16:49.076  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.076  5695  5741 I jxcore-log: 
,09-29 07:16:49.077  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.077  5695  5741 I jxcore-log: 
,09-29 07:16:49.079  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.079  5695  5741 I jxcore-log: 
,09-29 07:16:49.090  5695  5741 I jxcore-log: ok 20 we should not have gotten an error
09-29 07:16:49.090  5695  5741 I jxcore-log: 
,09-29 07:16:49.095  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.095  5695  5741 I jxcore-log: 
,09-29 07:16:49.097  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.097  5695  5741 I jxcore-log: 
,09-29 07:16:49.105  5695  5741 I jxcore-log: ok 21 Buffers are identical
09-29 07:16:49.105  5695  5741 I jxcore-log: 
,09-29 07:16:49.107  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.107  5695  5741 I jxcore-log: 
,09-29 07:16:49.109  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.109  5695  5741 I jxcore-log: 
,09-29 07:16:49.112  5695  5741 I jxcore-log: ok 22 native server is nulled out
09-29 07:16:49.112  5695  5741 I jxcore-log: 
,09-29 07:16:49.112  5695  5741 I jxcore-log: ok 23 native server should be closed
09-29 07:16:49.112  5695  5741 I jxcore-log: 
09-29 07:16:49.112  5695  5741 I jxcore-log: ok 24 incoming has been removed
09-29 07:16:49.112  5695  5741 I jxcore-log: 
09-29 07:16:49.112  5695  5741 I jxcore-log: ok 25 Incoming should be done
09-29 07:16:49.112  5695  5741 I jxcore-log: 
09-29 07:16:49.113  5695  5741 I jxcore-log: ok 26 The mux object should be closed
09-29 07:16:49.113  5695  5741 I jxcore-log: 
09-29 07:16:49.113  5695  5741 I jxcore-log: ok 27 The mux stream should be closed
09-29 07:16:49.113  5695  5741 I jxcore-log: 
09-29 07:16:49.113  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.113  5695  5741 I jxcore-log: 
,09-29 07:16:49.126  5695  5741 I jxcore-log: # teardown
09-29 07:16:49.126  5695  5741 I jxcore-log: 
,09-29 07:16:49.163  5695  5741 I jxcore-log: # setup
09-29 07:16:49.163  5695  5741 I jxcore-log: 
,09-29 07:16:49.197  5695  5741 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-29 07:16:49.197  5695  5741 I jxcore-log: 
,09-29 07:16:49.249  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:49.249  5695  5741 I jxcore-log: 
,09-29 07:16:49.253  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'listening 37399'
09-29 07:16:49.253  5695  5741 I jxcore-log: 
,09-29 07:16:49.281  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.281  5695  5741 I jxcore-log: 
,09-29 07:16:49.282  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.282  5695  5741 I jxcore-log: 
,09-29 07:16:49.283  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.283  5695  5741 I jxcore-log: 
,09-29 07:16:49.286  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.286  5695  5741 I jxcore-log: 
,09-29 07:16:49.287  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.287  5695  5741 I jxcore-log: 
,09-29 07:16:49.288  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.288  5695  5741 I jxcore-log: 
,09-29 07:16:49.291  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.291  5695  5741 I jxcore-log: 
,09-29 07:16:49.292  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.292  5695  5741 I jxcore-log: 
,09-29 07:16:49.293  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.293  5695  5741 I jxcore-log: 
,09-29 07:16:49.296  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.296  5695  5741 I jxcore-log: 
,09-29 07:16:49.297  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.297  5695  5741 I jxcore-log: 
,09-29 07:16:49.298  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.298  5695  5741 I jxcore-log: 
,09-29 07:16:49.300  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.300  5695  5741 I jxcore-log: 
,09-29 07:16:49.300  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.300  5695  5741 I jxcore-log: 
,09-29 07:16:49.302  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.302  5695  5741 I jxcore-log: 
,09-29 07:16:49.308  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.308  5695  5741 I jxcore-log: 
,09-29 07:16:49.308  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.308  5695  5741 I jxcore-log: 
,09-29 07:16:49.309  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.309  5695  5741 I jxcore-log: 
,09-29 07:16:49.310  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.310  5695  5741 I jxcore-log: 
,09-29 07:16:49.311  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.311  5695  5741 I jxcore-log: 
,09-29 07:16:49.311  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.311  5695  5741 I jxcore-log: 
,09-29 07:16:49.313  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.313  5695  5741 I jxcore-log: 
,09-29 07:16:49.313  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.313  5695  5741 I jxcore-log: 
,09-29 07:16:49.313  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.313  5695  5741 I jxcore-log: 
,09-29 07:16:49.315  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.315  5695  5741 I jxcore-log: 
,09-29 07:16:49.315  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.315  5695  5741 I jxcore-log: 
09-29 07:16:49.316  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.316  5695  5741 I jxcore-log: 
,09-29 07:16:49.317  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:49.317  5695  5741 I jxcore-log: 
,09-29 07:16:49.317  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:49.317  5695  5741 I jxcore-log: 
,09-29 07:16:49.318  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new mux'
09-29 07:16:49.318  5695  5741 I jxcore-log: 
,09-29 07:16:49.371  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.371  5695  5741 I jxcore-log: 
,09-29 07:16:49.373  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.373  5695  5741 I jxcore-log: 
,09-29 07:16:49.374  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.374  5695  5741 I jxcore-log: 
,09-29 07:16:49.376  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.376  5695  5741 I jxcore-log: 
,09-29 07:16:49.376  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.376  5695  5741 I jxcore-log: 
,09-29 07:16:49.377  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.377  5695  5741 I jxcore-log: 
,09-29 07:16:49.378  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.378  5695  5741 I jxcore-log: 
,09-29 07:16:49.379  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.379  5695  5741 I jxcore-log: 
,09-29 07:16:49.381  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.381  5695  5741 I jxcore-log: 
,09-29 07:16:49.382  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.382  5695  5741 I jxcore-log: 
,09-29 07:16:49.383  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.383  5695  5741 I jxcore-log: 
,09-29 07:16:49.384  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.384  5695  5741 I jxcore-log: 
,09-29 07:16:49.384  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.384  5695  5741 I jxcore-log: 
,09-29 07:16:49.385  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.385  5695  5741 I jxcore-log: 
,09-29 07:16:49.386  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.386  5695  5741 I jxcore-log: 
,09-29 07:16:49.387  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.387  5695  5741 I jxcore-log: 
,09-29 07:16:49.388  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.388  5695  5741 I jxcore-log: 
,09-29 07:16:49.389  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.389  5695  5741 I jxcore-log: 
,09-29 07:16:49.390  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.390  5695  5741 I jxcore-log: 
,09-29 07:16:49.391  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.391  5695  5741 I jxcore-log: 
,09-29 07:16:49.391  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.391  5695  5741 I jxcore-log: 
09-29 07:16:49.392  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.392  5695  5741 I jxcore-log: 
,09-29 07:16:49.393  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.393  5695  5741 I jxcore-log: 
,09-29 07:16:49.393  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.393  5695  5741 I jxcore-log: 
,09-29 07:16:49.395  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.395  5695  5741 I jxcore-log: 
,09-29 07:16:49.396  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.396  5695  5741 I jxcore-log: 
,09-29 07:16:49.396  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.396  5695  5741 I jxcore-log: 
,09-29 07:16:49.397  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.397  5695  5741 I jxcore-log: 
09-29 07:16:49.398  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.398  5695  5741 I jxcore-log: 
,09-29 07:16:49.398  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.398  5695  5741 I jxcore-log: 
,09-29 07:16:49.399  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.399  5695  5741 I jxcore-log: 
09-29 07:16:49.400  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.400  5695  5741 I jxcore-log: 
,09-29 07:16:49.400  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.400  5695  5741 I jxcore-log: 
,09-29 07:16:49.401  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.401  5695  5741 I jxcore-log: 
,09-29 07:16:49.402  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.402  5695  5741 I jxcore-log: 
09-29 07:16:49.403  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.403  5695  5741 I jxcore-log: 
,09-29 07:16:49.403  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.403  5695  5741 I jxcore-log: 
,09-29 07:16:49.404  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.404  5695  5741 I jxcore-log: 
09-29 07:16:49.404  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.404  5695  5741 I jxcore-log: 
,09-29 07:16:49.405  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.405  5695  5741 I jxcore-log: 
,09-29 07:16:49.406  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.406  5695  5741 I jxcore-log: 
09-29 07:16:49.407  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.407  5695  5741 I jxcore-log: 
,09-29 07:16:49.407  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.407  5695  5741 I jxcore-log: 
,09-29 07:16:49.408  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.408  5695  5741 I jxcore-log: 
09-29 07:16:49.408  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.408  5695  5741 I jxcore-log: 
,09-29 07:16:49.409  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.409  5695  5741 I jxcore-log: 
09-29 07:16:49.410  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.410  5695  5741 I jxcore-log: 
,09-29 07:16:49.410  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.410  5695  5741 I jxcore-log: 
,09-29 07:16:49.416  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.416  5695  5741 I jxcore-log: 
,09-29 07:16:49.417  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.417  5695  5741 I jxcore-log: 
,09-29 07:16:49.418  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.418  5695  5741 I jxcore-log: 
,09-29 07:16:49.419  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.419  5695  5741 I jxcore-log: 
09-29 07:16:49.419  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.419  5695  5741 I jxcore-log: 
,09-29 07:16:49.420  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.420  5695  5741 I jxcore-log: 
09-29 07:16:49.420  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.420  5695  5741 I jxcore-log: 
09-29 07:16:49.421  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.421  5695  5741 I jxcore-log: 
,09-29 07:16:49.422  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.422  5695  5741 I jxcore-log: 
,09-29 07:16:49.423  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.423  5695  5741 I jxcore-log: 
09-29 07:16:49.423  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.423  5695  5741 I jxcore-log: 
,09-29 07:16:49.424  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.424  5695  5741 I jxcore-log: 
09-29 07:16:49.425  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.425  5695  5741 I jxcore-log: 
,09-29 07:16:49.425  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.425  5695  5741 I jxcore-log: 
09-29 07:16:49.426  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.426  5695  5741 I jxcore-log: 
09-29 07:16:49.426  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.426  5695  5741 I jxcore-log: 
,09-29 07:16:49.427  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.427  5695  5741 I jxcore-log: 
,09-29 07:16:49.428  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.428  5695  5741 I jxcore-log: 
09-29 07:16:49.429  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.429  5695  5741 I jxcore-log: 
,09-29 07:16:49.429  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.429  5695  5741 I jxcore-log: 
09-29 07:16:49.430  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.430  5695  5741 I jxcore-log: 
,09-29 07:16:49.431  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.431  5695  5741 I jxcore-log: 
09-29 07:16:49.431  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.431  5695  5741 I jxcore-log: 
,09-29 07:16:49.432  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.432  5695  5741 I jxcore-log: 
,09-29 07:16:49.433  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.433  5695  5741 I jxcore-log: 
09-29 07:16:49.433  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.433  5695  5741 I jxcore-log: 
,09-29 07:16:49.434  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.434  5695  5741 I jxcore-log: 
09-29 07:16:49.435  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.435  5695  5741 I jxcore-log: 
,09-29 07:16:49.435  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.435  5695  5741 I jxcore-log: 
09-29 07:16:49.436  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.436  5695  5741 I jxcore-log: 
,09-29 07:16:49.436  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:49.436  5695  5741 I jxcore-log: 
09-29 07:16:49.437  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:49.437  5695  5741 I jxcore-log: 
,09-29 07:16:49.482  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.482  5695  5741 I jxcore-log: 
,09-29 07:16:49.483  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.483  5695  5741 I jxcore-log: 
,09-29 07:16:49.483  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.483  5695  5741 I jxcore-log: 
09-29 07:16:49.484  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.484  5695  5741 I jxcore-log: 
,09-29 07:16:49.485  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.485  5695  5741 I jxcore-log: 
09-29 07:16:49.486  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.486  5695  5741 I jxcore-log: 
,09-29 07:16:49.486  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.486  5695  5741 I jxcore-log: 
09-29 07:16:49.486  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.486  5695  5741 I jxcore-log: 
,09-29 07:16:49.487  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.487  5695  5741 I jxcore-log: 
,09-29 07:16:49.487  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.487  5695  5741 I jxcore-log: 
,09-29 07:16:49.488  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.488  5695  5741 I jxcore-log: 
,09-29 07:16:49.488  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.488  5695  5741 I jxcore-log: 
09-29 07:16:49.489  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.489  5695  5741 I jxcore-log: 
,09-29 07:16:49.489  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.489  5695  5741 I jxcore-log: 
09-29 07:16:49.490  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.490  5695  5741 I jxcore-log: 
,09-29 07:16:49.490  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.490  5695  5741 I jxcore-log: 
09-29 07:16:49.491  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.491  5695  5741 I jxcore-log: 
,09-29 07:16:49.491  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.491  5695  5741 I jxcore-log: 
09-29 07:16:49.492  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.492  5695  5741 I jxcore-log: 
,09-29 07:16:49.492  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.492  5695  5741 I jxcore-log: 
09-29 07:16:49.493  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.493  5695  5741 I jxcore-log: 
09-29 07:16:49.493  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.493  5695  5741 I jxcore-log: 
,09-29 07:16:49.493  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.493  5695  5741 I jxcore-log: 
09-29 07:16:49.494  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.494  5695  5741 I jxcore-log: 
,09-29 07:16:49.494  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.494  5695  5741 I jxcore-log: 
09-29 07:16:49.495  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.495  5695  5741 I jxcore-log: 
09-29 07:16:49.495  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.495  5695  5741 I jxcore-log: 
09-29 07:16:49.496  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.496  5695  5741 I jxcore-log: 
09-29 07:16:49.496  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.496  5695  5741 I jxcore-log: 
,09-29 07:16:49.497  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.497  5695  5741 I jxcore-log: 
09-29 07:16:49.497  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.497  5695  5741 I jxcore-log: 
09-29 07:16:49.498  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.498  5695  5741 I jxcore-log: 
,09-29 07:16:49.498  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.498  5695  5741 I jxcore-log: 
09-29 07:16:49.499  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.499  5695  5741 I jxcore-log: 
09-29 07:16:49.499  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.499  5695  5741 I jxcore-log: 
09-29 07:16:49.499  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.499  5695  5741 I jxcore-log: 
,09-29 07:16:49.500  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.500  5695  5741 I jxcore-log: 
09-29 07:16:49.500  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.500  5695  5741 I jxcore-log: 
09-29 07:16:49.501  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.501  5695  5741 I jxcore-log: 
09-29 07:16:49.501  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.501  5695  5741 I jxcore-log: 
,09-29 07:16:49.501  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.501  5695  5741 I jxcore-log: 
09-29 07:16:49.502  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.502  5695  5741 I jxcore-log: 
09-29 07:16:49.502  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.502  5695  5741 I jxcore-log: 
09-29 07:16:49.503  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.503  5695  5741 I jxcore-log: 
09-29 07:16:49.504  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.504  5695  5741 I jxcore-log: 
09-29 07:16:49.506  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.506  5695  5741 I jxcore-log: 
09-29 07:16:49.507  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.507  5695  5741 I jxcore-log: 
09-29 07:16:49.508  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.508  5695  5741 I jxcore-log: 
09-29 07:16:49.508  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:49.508  5695  5741 I jxcore-log: 
09-29 07:16:49.509  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'mux close'
09-29 07:16:49.509  5695  5741 I jxcore-log: 
09-29 07:16:49.511  5695  5741 I jxcore-log: ok 28 native server is nulled out
09-29 07:16:49.511  5695  5741 I jxcore-log: 
09-29 07:16:49.511  5695  5741 I jxcore-log: ok 29 native server should be closed
09-29 07:16:49.511  5695  5741 I jxcore-log: 
09-29 07:16:49.511  5695  5741 I jxcore-log: ok 30 incoming has been removed
09-29 07:16:49.511  5695  5741 I jxcore-log: 
09-29 07:16:49.512  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.512  5695  5741 I jxcore-log: 
09-29 07:16:49.512  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.512  5695  5741 I jxcore-log: 
09-29 07:16:49.513  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.513  5695  5741 I jxcore-log: 
09-29 07:16:49.513  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.513  5695  5741 I jxcore-log: 
09-29 07:16:49.513  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.513  5695  5741 I jxcore-log: 
09-29 07:16:49.514  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.514  5695  5741 I jxcore-log: 
09-29 07:16:49.514  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.514  5695  5741 I jxcore-log: 
09-29 07:16:49.514  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.514  5695  5741 I jxcore-log: 
09-29 07:16:49.514  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.514  5695  5741 I jxcore-log: 
09-29 07:16:49.514  5695  5741 I jxcore-log: 2016-09-29 11:16:49 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:49.514  5695  5741 I jxcore-log: 
,09-29 07:16:49.586  5695  5741 I jxcore-log: # teardown
09-29 07:16:49.586  5695  5741 I jxcore-log: 
,09-29 07:16:49.696  5695  5741 I jxcore-log: # setup
09-29 07:16:49.696  5695  5741 I jxcore-log: 
,09-29 07:16:50.347   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:51.313  5695  5741 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-29 07:16:51.313  5695  5741 I jxcore-log: 
,09-29 07:16:51.349   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:51.383  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:51.383  5695  5741 I jxcore-log: 
,09-29 07:16:51.389  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'listening 40118'
09-29 07:16:51.389  5695  5741 I jxcore-log: 
,09-29 07:16:51.398  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:51.398  5695  5741 I jxcore-log: 
,09-29 07:16:51.399  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:51.399  5695  5741 I jxcore-log: 
09-29 07:16:51.401  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new mux'
09-29 07:16:51.401  5695  5741 I jxcore-log: 
,09-29 07:16:51.409  5695  5741 I jxcore-log: ok 31 we should not have gotten an error
09-29 07:16:51.409  5695  5741 I jxcore-log: 
,09-29 07:16:51.413  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:51.413  5695  5741 I jxcore-log: 
,09-29 07:16:51.416  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:51.416  5695  5741 I jxcore-log: 
,09-29 07:16:51.424  5695  5741 I jxcore-log: ok 32 Buffers are identical
09-29 07:16:51.424  5695  5741 I jxcore-log: 
,09-29 07:16:51.425  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:51.425  5695  5741 I jxcore-log: 
09-29 07:16:51.427  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'mux close'
09-29 07:16:51.427  5695  5741 I jxcore-log: 
,09-29 07:16:51.436  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:51.436  5695  5741 I jxcore-log: 
,09-29 07:16:51.437  5695  5741 I jxcore-log: ok 33 server should be fine
09-29 07:16:51.437  5695  5741 I jxcore-log: 
,09-29 07:16:51.438  5695  5741 I jxcore-log: ok 34 server should be open
09-29 07:16:51.438  5695  5741 I jxcore-log: 
09-29 07:16:51.438  5695  5741 I jxcore-log: ok 35 incoming has been removed
09-29 07:16:51.438  5695  5741 I jxcore-log: 
09-29 07:16:51.439  5695  5741 I jxcore-log: ok 36 The mux object should be closed
09-29 07:16:51.439  5695  5741 I jxcore-log: 
09-29 07:16:51.439  5695  5741 I jxcore-log: ok 37 The mux stream should be closed
09-29 07:16:51.439  5695  5741 I jxcore-log: 
,09-29 07:16:51.444  5695  5741 I jxcore-log: # teardown
09-29 07:16:51.444  5695  5741 I jxcore-log: 
,09-29 07:16:51.510  5695  5741 I jxcore-log: # setup
09-29 07:16:51.510  5695  5741 I jxcore-log: 
,09-29 07:16:51.582  5695  5741 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-29 07:16:51.582  5695  5741 I jxcore-log: 
,09-29 07:16:51.630  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'creating native server'
09-29 07:16:51.630  5695  5741 I jxcore-log: 
,09-29 07:16:51.635  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'listening 43506'
09-29 07:16:51.635  5695  5741 I jxcore-log: 
,09-29 07:16:51.642  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new incoming socket'
09-29 07:16:51.642  5695  5741 I jxcore-log: 
,09-29 07:16:51.644  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'creating incoming mux'
09-29 07:16:51.644  5695  5741 I jxcore-log: 
,09-29 07:16:51.647  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new mux'
09-29 07:16:51.647  5695  5741 I jxcore-log: 
,09-29 07:16:51.653  5695  5741 I jxcore-log: ok 38 we should not have gotten an error
09-29 07:16:51.653  5695  5741 I jxcore-log: 
,09-29 07:16:51.657  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new stream: '
09-29 07:16:51.657  5695  5741 I jxcore-log: 
,09-29 07:16:51.660  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'new outgoing socket'
09-29 07:16:51.660  5695  5741 I jxcore-log: 
,09-29 07:16:51.667  5695  5741 I jxcore-log: ok 39 Buffers are identical
09-29 07:16:51.667  5695  5741 I jxcore-log: 
,09-29 07:16:51.672  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'incoming socket timeout'
09-29 07:16:51.672  5695  5741 I jxcore-log: 
,09-29 07:16:51.674  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'stream close:'
09-29 07:16:51.674  5695  5741 I jxcore-log: 
,09-29 07:16:51.676  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'mux close'
09-29 07:16:51.676  5695  5741 I jxcore-log: 
,09-29 07:16:51.681  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG createNativeListener: 'incoming socket close'
09-29 07:16:51.681  5695  5741 I jxcore-log: 
,09-29 07:16:51.682  5695  5741 I jxcore-log: ok 40 server should be fine
09-29 07:16:51.682  5695  5741 I jxcore-log: 
09-29 07:16:51.682  5695  5741 I jxcore-log: ok 41 server should be open
09-29 07:16:51.682  5695  5741 I jxcore-log: 
09-29 07:16:51.682  5695  5741 I jxcore-log: ok 42 incoming has been removed
09-29 07:16:51.682  5695  5741 I jxcore-log: 
09-29 07:16:51.683  5695  5741 I jxcore-log: ok 43 The mux object should be closed
09-29 07:16:51.683  5695  5741 I jxcore-log: 
09-29 07:16:51.683  5695  5741 I jxcore-log: ok 44 The mux stream should be closed
09-29 07:16:51.683  5695  5741 I jxcore-log: 
,09-29 07:16:51.689  5695  5741 I jxcore-log: # teardown
09-29 07:16:51.689  5695  5741 I jxcore-log: 
,09-29 07:16:51.730  5695  5741 I jxcore-log: # setup
09-29 07:16:51.730  5695  5741 I jxcore-log: 
,09-29 07:16:51.773  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-29 07:16:51.773  5695  5741 I jxcore-log: 
,09-29 07:16:51.931  5695  5741 I jxcore-log: 2016-09-29 11:16:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-29 07:16:51.931  5695  5741 I jxcore-log: 
,09-29 07:16:51.932  5695  5741 I jxcore-log: ok 45 Got right error
09-29 07:16:51.932  5695  5741 I jxcore-log: 
,09-29 07:16:51.937  5695  5741 I jxcore-log: # teardown
09-29 07:16:51.937  5695  5741 I jxcore-log: 
,09-29 07:16:51.992  5695  5741 I jxcore-log: # setup
09-29 07:16:51.992  5695  5741 I jxcore-log: 
,09-29 07:16:52.038  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-29 07:16:52.038  5695  5741 I jxcore-log: 
,09-29 07:16:52.128  5695  5741 I jxcore-log: 2016-09-29 11:16:52 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-29 07:16:52.128  5695  5741 I jxcore-log: 
,09-29 07:16:52.129  5695  5741 I jxcore-log: ok 46 Got socket hang up
09-29 07:16:52.129  5695  5741 I jxcore-log: 
,09-29 07:16:52.134  5695  5741 I jxcore-log: # teardown
09-29 07:16:52.134  5695  5741 I jxcore-log: 
,09-29 07:16:52.178  5695  5741 I jxcore-log: # setup
09-29 07:16:52.178  5695  5741 I jxcore-log: 
,09-29 07:16:52.251  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-29 07:16:52.251  5695  5741 I jxcore-log: 
,09-29 07:16:52.350   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:52.467  5695  5741 I jxcore-log: 2016-09-29 11:16:52 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-29 07:16:52.467  5695  5741 I jxcore-log: 
,09-29 07:16:52.468  5695  5741 I jxcore-log: ok 47 Got 500 as expected
09-29 07:16:52.468  5695  5741 I jxcore-log: 
,09-29 07:16:52.472  5695  5741 I jxcore-log: # teardown
09-29 07:16:52.472  5695  5741 I jxcore-log: 
,09-29 07:16:52.512  5695  5741 I jxcore-log: # setup
09-29 07:16:52.512  5695  5741 I jxcore-log: 
,09-29 07:16:52.576  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-29 07:16:52.576  5695  5741 I jxcore-log: 
,09-29 07:16:53.351   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:53.446   929  3054 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 07:16:53.930  5695  5741 I jxcore-log: ok 48 should be equal
09-29 07:16:53.930  5695  5741 I jxcore-log: 
,09-29 07:16:53.930  5695  5741 I jxcore-log: ok 49 revs are equal
09-29 07:16:53.930  5695  5741 I jxcore-log: 
,09-29 07:16:53.935  5695  5741 I jxcore-log: # teardown
09-29 07:16:53.935  5695  5741 I jxcore-log: 
,09-29 07:16:53.982  5695  5741 I jxcore-log: # setup
09-29 07:16:53.982  5695  5741 I jxcore-log: 
,09-29 07:16:54.352   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:16:54.795  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-29 07:16:54.795  5695  5741 I jxcore-log: 
,09-29 07:16:55.352   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-29 07:16:55.566  5695  5741 I jxcore-log: ok 50 should be equal
09-29 07:16:55.566  5695  5741 I jxcore-log: 
,09-29 07:16:55.566  5695  5741 I jxcore-log: ok 51 revs are equal
09-29 07:16:55.566  5695  5741 I jxcore-log: 
,09-29 07:16:55.572  5695  5741 I jxcore-log: # teardown
09-29 07:16:55.572  5695  5741 I jxcore-log: 
,09-29 07:16:55.606  5695  5741 I jxcore-log: # setup
09-29 07:16:55.606  5695  5741 I jxcore-log: 
,09-29 07:16:55.682  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-29 07:16:55.682  5695  5741 I jxcore-log: 
,09-29 07:16:56.197  5695  5741 I jxcore-log: ok 52 should be equal
09-29 07:16:56.197  5695  5741 I jxcore-log: 
,09-29 07:16:56.197  5695  5741 I jxcore-log: ok 53 revs are equal
09-29 07:16:56.197  5695  5741 I jxcore-log: 
,09-29 07:16:56.330  5695  5741 I jxcore-log: ok 54 should be equal
09-29 07:16:56.330  5695  5741 I jxcore-log: 
,09-29 07:16:56.330  5695  5741 I jxcore-log: ok 55 revs are equal
09-29 07:16:56.330  5695  5741 I jxcore-log: 
,09-29 07:16:56.459  5695  5741 I jxcore-log: ok 56 should be equal
09-29 07:16:56.459  5695  5741 I jxcore-log: 
,09-29 07:16:56.460  5695  5741 I jxcore-log: ok 57 revs are equal
09-29 07:16:56.460  5695  5741 I jxcore-log: 
,09-29 07:16:56.465  5695  5741 I jxcore-log: # teardown
09-29 07:16:56.465  5695  5741 I jxcore-log: 
,09-29 07:16:56.539  5695  5741 I jxcore-log: # setup
09-29 07:16:56.539  5695  5741 I jxcore-log: 
,09-29 07:16:56.564  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-29 07:16:56.564  5695  5741 I jxcore-log: 
,09-29 07:16:57.117  5695  5741 I jxcore-log: 2016-09-29 11:16:57 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-29 07:16:57.117  5695  5741 I jxcore-log: 
,09-29 07:16:57.118  5695  5741 I jxcore-log: ok 58 Our rev is old so we should fail
09-29 07:16:57.118  5695  5741 I jxcore-log: 
,09-29 07:16:57.122  5695  5741 I jxcore-log: # teardown
09-29 07:16:57.122  5695  5741 I jxcore-log: 
,09-29 07:16:57.221  5695  5741 I jxcore-log: # setup
09-29 07:16:57.221  5695  5741 I jxcore-log: 
,09-29 07:16:57.246  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-29 07:16:57.246  5695  5741 I jxcore-log: 
,09-29 07:16:57.358  5695  5741 I jxcore-log: ok 59 confirm stop caused failure
09-29 07:16:57.358  5695  5741 I jxcore-log: 
,09-29 07:16:57.370  5695  5741 I jxcore-log: # teardown
09-29 07:16:57.370  5695  5741 I jxcore-log: 
,09-29 07:16:57.399  5695  5741 I jxcore-log: # setup
09-29 07:16:57.399  5695  5741 I jxcore-log: 
,09-29 07:16:57.429  5695  5741 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-29 07:16:57.429  5695  5741 I jxcore-log: 
,09-29 07:16:57.707  5695  5741 I jxcore-log: 2016-09-29 11:16:57 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-29 07:16:57.707  5695  5741 I jxcore-log: 
,09-29 07:16:57.708  5695  5741 I jxcore-log: ok 60 stop caused us to fail
09-29 07:16:57.708  5695  5741 I jxcore-log: 
,09-29 07:16:57.709  5695  5741 I jxcore-log: ok 61 We specifically failed on a stop before put
09-29 07:16:57.709  5695  5741 I jxcore-log: 
,09-29 07:16:57.714  5695  5741 I jxcore-log: # teardown
09-29 07:16:57.714  5695  5741 I jxcore-log: 
,09-29 07:16:57.893  5695  5741 I jxcore-log: # setup
09-29 07:16:57.893  5695  5741 I jxcore-log: 
,09-29 07:16:57.957  5695  5741 I jxcore-log: # #update - fail if stop is called
09-29 07:16:57.957  5695  5741 I jxcore-log: 
,09-29 07:16:58.043  5695  5741 I jxcore-log: ok 62 failed due to stop
09-29 07:16:58.043  5695  5741 I jxcore-log: 
,09-29 07:16:58.046  5695  5741 I jxcore-log: ok 63 failed due to stop
09-29 07:16:58.046  5695  5741 I jxcore-log: 
,09-29 07:16:58.059  5695  5741 I jxcore-log: # teardown
09-29 07:16:58.059  5695  5741 I jxcore-log: 
,09-29 07:16:58.100  5695  5741 I jxcore-log: # setup
09-29 07:16:58.100  5695  5741 I jxcore-log: 
,09-29 07:16:58.168  5695  5741 I jxcore-log: # #update - set seq for first time
09-29 07:16:58.168  5695  5741 I jxcore-log: 
,09-29 07:16:58.655  5695  5741 I jxcore-log: ok 64 should be equal
09-29 07:16:58.655  5695  5741 I jxcore-log: 
,09-29 07:16:58.661  5695  5741 I jxcore-log: # teardown
09-29 07:16:58.661  5695  5741 I jxcore-log: 
,09-29 07:16:58.799  5695  5741 I jxcore-log: # setup
09-29 07:16:58.799  5695  5741 I jxcore-log: 
,09-29 07:16:58.823  5695  5741 I jxcore-log: # #update - Fail on bad seq value
09-29 07:16:58.823  5695  5741 I jxcore-log: 
,09-29 07:16:59.223  5695  5741 I jxcore-log: 2016-09-29 11:16:59 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-29 07:16:59.223  5695  5741 I jxcore-log: 
,09-29 07:16:59.225  5695  5741 I jxcore-log: ok 65 Expected bad seq error
09-29 07:16:59.225  5695  5741 I jxcore-log: 
,09-29 07:16:59.229  5695  5741 I jxcore-log: # teardown
09-29 07:16:59.229  5695  5741 I jxcore-log: 
,09-29 07:16:59.341  5695  5741 I jxcore-log: # setup
09-29 07:16:59.341  5695  5741 I jxcore-log: 
,09-29 07:16:59.372  5695  5741 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-29 07:16:59.372  5695  5741 I jxcore-log: 
,09-29 07:16:59.790  5695  5741 I jxcore-log: ok 66 Different promises
09-29 07:16:59.790  5695  5741 I jxcore-log: 
09-29 07:16:59.792  5695  5741 I jxcore-log: ok 67 Timer was cancelled
09-29 07:16:59.792  5695  5741 I jxcore-log: 
,09-29 07:16:59.931  5695  5741 I jxcore-log: ok 68 should be equal
09-29 07:16:59.931  5695  5741 I jxcore-log: 
,09-29 07:16:59.938  5695  5741 I jxcore-log: # teardown
09-29 07:16:59.938  5695  5741 I jxcore-log: 
,09-29 07:17:00.353   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:01.355   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:01.370  5695  5741 I jxcore-log: # setup
09-29 07:17:01.370  5695  5741 I jxcore-log: 
,09-29 07:17:01.756  5695  5741 I jxcore-log: # #update - do we wait for blocked update
09-29 07:17:01.756  5695  5741 I jxcore-log: 
,09-29 07:17:01.973  5695  5741 I jxcore-log: ok 69 One go and one blocked
09-29 07:17:01.973  5695  5741 I jxcore-log: 
,09-29 07:17:01.974  5695  5741 I jxcore-log: ok 70 All blocked
09-29 07:17:01.974  5695  5741 I jxcore-log: 
09-29 07:17:01.975  5695  5741 I jxcore-log: ok 71 Still blocked
09-29 07:17:01.975  5695  5741 I jxcore-log: 
,09-29 07:17:02.356   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:02.390  5695  5741 I jxcore-log: ok 72 should be equal
09-29 07:17:02.390  5695  5741 I jxcore-log: 
,09-29 07:17:02.398  5695  5741 I jxcore-log: # teardown
09-29 07:17:02.398  5695  5741 I jxcore-log: 
,09-29 07:17:02.463  5695  5741 I jxcore-log: # setup
09-29 07:17:02.463  5695  5741 I jxcore-log: 
,09-29 07:17:02.515  5695  5741 I jxcore-log: # #update - test that we wait long enough
09-29 07:17:02.515  5695  5741 I jxcore-log: 
,09-29 07:17:03.357   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:04.273  5695  5741 I jxcore-log: ok 73 We waited long enough
09-29 07:17:04.273  5695  5741 I jxcore-log: 
,09-29 07:17:04.331  5695  5741 I jxcore-log: ok 74 should be equal
09-29 07:17:04.331  5695  5741 I jxcore-log: 
,09-29 07:17:04.338  5695  5741 I jxcore-log: # teardown
09-29 07:17:04.338  5695  5741 I jxcore-log: 
,09-29 07:17:04.358   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:04.387  5695  5741 I jxcore-log: # setup
09-29 07:17:04.387  5695  5741 I jxcore-log: 
,09-29 07:17:04.422  5695  5741 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-29 07:17:04.422  5695  5741 I jxcore-log: 
,09-29 07:17:04.942  5695  5741 I jxcore-log: ok 75 Should have gotten same timer promise
09-29 07:17:04.942  5695  5741 I jxcore-log: 
,09-29 07:17:04.943  5695  5741 I jxcore-log: ok 76 Still same timer promise
09-29 07:17:04.943  5695  5741 I jxcore-log: 
,09-29 07:17:05.358   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-29 07:17:05.687  5695  5741 I jxcore-log: ok 77 We waited long enough
09-29 07:17:05.687  5695  5741 I jxcore-log: 
,09-29 07:17:05.776  5695  5741 I jxcore-log: ok 78 should be equal
09-29 07:17:05.776  5695  5741 I jxcore-log: 
,09-29 07:17:05.786  5695  5741 I jxcore-log: # teardown
09-29 07:17:05.786  5695  5741 I jxcore-log: 
,09-29 07:17:05.866  5695  5741 I jxcore-log: # setup
09-29 07:17:05.866  5695  5741 I jxcore-log: 
,09-29 07:17:05.991  5695  5741 I jxcore-log: # Coordinated seq test
09-29 07:17:05.991  5695  5741 I jxcore-log: 
,09-29 07:17:05.996  5695  5741 I jxcore-log: 2016-09-29 11:17:05 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-29 07:17:05.996  5695  5741 I jxcore-log: 
,09-29 07:17:06.045  5695  5741 I jxcore-log: # teardown
09-29 07:17:06.045  5695  5741 I jxcore-log: 
,09-29 07:17:06.103  5695  5741 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-29 07:17:06.104  5695  5741 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-29 07:17:06.104  5695  5741 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-29 07:17:06.105  5695  5741 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-29 07:17:06.120  5695  5741 I jxcore-log: # setup
09-29 07:17:06.120  5695  5741 I jxcore-log: 
,09-29 07:17:06.157  5695  5741 I jxcore-log: # closeAll can close even when connections open
09-29 07:17:06.157  5695  5741 I jxcore-log: 
,09-29 07:17:06.319  5695  5741 I jxcore-log: ok 79 not possible to connect to the server anymore
09-29 07:17:06.319  5695  5741 I jxcore-log: 
,09-29 07:17:06.332  5695  5741 I jxcore-log: # teardown
09-29 07:17:06.332  5695  5741 I jxcore-log: 
,09-29 07:17:06.369  5695  5741 I jxcore-log: # setup
09-29 07:17:06.369  5695  5741 I jxcore-log: 
,09-29 07:17:06.418  5695  5741 I jxcore-log: # closeAll with promise
09-29 07:17:06.418  5695  5741 I jxcore-log: 
,09-29 07:17:06.572  5695  5741 I jxcore-log: ok 80 not possible to connect to the server anymore
09-29 07:17:06.572  5695  5741 I jxcore-log: 
,09-29 07:17:06.581  5695  5741 I jxcore-log: # teardown
09-29 07:17:06.581  5695  5741 I jxcore-log: 
,09-29 07:17:06.628  5695  5741 I jxcore-log: # setup
09-29 07:17:06.628  5695  5741 I jxcore-log: 
,09-29 07:17:06.685  5695  5741 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-29 07:17:06.685  5695  5741 I jxcore-log: 
,09-29 07:17:06.830  5695  5741 I jxcore-log: ok 81 Got the right error
09-29 07:17:06.830  5695  5741 I jxcore-log: 
,09-29 07:17:06.845  5695  5741 I jxcore-log: # teardown
09-29 07:17:06.845  5695  5741 I jxcore-log: 
,09-29 07:17:06.872  5695  5741 I jxcore-log: # setup
09-29 07:17:06.872  5695  5741 I jxcore-log: 
,09-29 07:17:06.923  5695  5741 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-29 07:17:06.923  5695  5741 I jxcore-log: 
,09-29 07:17:07.072  5695  5741 I jxcore-log: # teardown
09-29 07:17:07.072  5695  5741 I jxcore-log: 
,09-29 07:17:07.111  5695  5741 I jxcore-log: # setup
09-29 07:17:07.111  5695  5741 I jxcore-log: 
,09-29 07:17:07.151  5695  5741 I jxcore-log: # onPeerLost calls jxcore
09-29 07:17:07.151  5695  5741 I jxcore-log: 
,09-29 07:17:07.210  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 07:17:07.211  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63bf42 added. We now have 3 listener(s)
09-29 07:17:07.213  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-29 07:17:07.213  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:17:07.213  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:17:07.214  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:17:07.214  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcabb53 added. We now have 4 listener(s)
,09-29 07:17:07.214  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:17:07.215  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 07:17:07.222  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:17:07.229  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:17:07.232  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:17:07.232  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:17:07.233  5695  5741 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-29 07:17:07.233  5695  5741 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-29 07:17:07.237  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:17:07.242  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:17:09.235  5695  5741 I jxcore-log: onPeerLost
09-29 07:17:09.235  5695  5741 I jxcore-log: 
,09-29 07:17:09.240  5695  5741 I jxcore-log: 2016-09-29 11:17:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:17:09.240  5695  5741 I jxcore-log: 
,09-29 07:17:09.252  5695  5741 I jxcore-log: # teardown
09-29 07:17:09.252  5695  5741 I jxcore-log: 
,09-29 07:17:09.256  5695  5741 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-29 07:17:09.256  5695  5741 I jxcore-log: 
,09-29 07:17:09.261  5695  5741 I jxcore-log: ok 83 check if peerAvailable is false
09-29 07:17:09.261  5695  5741 I jxcore-log: 
,09-29 07:17:09.310  5695  5741 I jxcore-log: 2016-09-29 11:17:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 07:17:09.310  5695  5741 I jxcore-log: 
,09-29 07:17:09.315  5695  5741 I jxcore-log: 2016-09-29 11:17:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 07:17:09.315  5695  5741 I jxcore-log: 
,09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:17:09.324  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:17:09.327  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:17:09.329  5695  5741 I jxcore-log: 2016-09-29 11:17:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 07:17:09.329  5695  5741 I jxcore-log: 
,09-29 07:17:09.333  5695  5741 I jxcore-log: 2016-09-29 11:17:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 07:17:09.333  5695  5741 I jxcore-log: 
,09-29 07:17:09.337  5695  5741 I jxcore-log: 2016-09-29 11:17:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:17:09.337  5695  5741 I jxcore-log: 
,09-29 07:17:09.342  5695  5741 I jxcore-log: # setup
09-29 07:17:09.342  5695  5741 I jxcore-log: 
,09-29 07:17:11.179  5695  5741 I jxcore-log: # onPeerDiscovered calls jxcore
09-29 07:17:11.179  5695  5741 I jxcore-log: 
,09-29 07:17:11.584  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-29 07:17:11.584  5695  5741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138d989 added. We now have 4 listener(s)
,09-29 07:17:11.588  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-29 07:17:11.588  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-29 07:17:11.589  5695  5741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-29 07:17:11.589  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-29 07:17:11.589  5695  5741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@728d8e added. We now have 5 listener(s)
09-29 07:17:11.589  5695  5741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-29 07:17:11.591  5695  5741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-29 07:17:11.599  5695  5741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:17:11.607  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:17:11.610  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-29 07:17:11.611  5695  5741 D io.jxcore.node.ConnectivityMonitor: start: OK
09-29 07:17:11.611  5695  5741 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
09-29 07:17:11.615  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-29 07:17:11.618  5695  5695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-29 07:17:13.449   929  3054 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 07:17:13.614  5695  5741 I jxcore-log: onPeerDiscovered
09-29 07:17:13.614  5695  5741 I jxcore-log: 
,09-29 07:17:13.618  5695  5741 I jxcore-log: 2016-09-29 11:17:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:17:13.618  5695  5741 I jxcore-log: 
,09-29 07:17:13.635  5695  5741 I jxcore-log: # teardown
09-29 07:17:13.635  5695  5741 I jxcore-log: 
,09-29 07:17:13.641  5695  5741 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-29 07:17:13.641  5695  5741 I jxcore-log: 
09-29 07:17:13.642  5695  5741 I jxcore-log: ok 85 check if peerAvailable is true
09-29 07:17:13.642  5695  5741 I jxcore-log: 
,09-29 07:17:14.438  5695  5741 I jxcore-log: 2016-09-29 11:17:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-29 07:17:14.438  5695  5741 I jxcore-log: 
,09-29 07:17:14.445  5695  5741 I jxcore-log: 2016-09-29 11:17:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-29 07:17:14.445  5695  5741 I jxcore-log: 
,09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-29 07:17:14.455  5695  5741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-29 07:17:14.458  5695  5741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-29 07:17:14.463  5695  5741 I jxcore-log: 2016-09-29 11:17:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-29 07:17:14.463  5695  5741 I jxcore-log: 
,09-29 07:17:14.468  5695  5741 I jxcore-log: 2016-09-29 11:17:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-29 07:17:14.468  5695  5741 I jxcore-log: 
,09-29 07:17:14.473  5695  5741 I jxcore-log: 2016-09-29 11:17:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-29 07:17:14.473  5695  5741 I jxcore-log: 
,09-29 07:17:14.477  5695  5741 I jxcore-log: # setup
09-29 07:17:14.477  5695  5741 I jxcore-log: 
,09-29 07:17:15.359   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:15.494  5695  5741 I jxcore-log: # Call of onCheckpointReached handler on a single db change
09-29 07:17:15.494  5695  5741 I jxcore-log: 
,09-29 07:17:16.309  5695  5741 I jxcore-log: # teardown
09-29 07:17:16.309  5695  5741 I jxcore-log: 
,09-29 07:17:16.362   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:16.652  5695  5741 I jxcore-log: # setup
09-29 07:17:16.652  5695  5741 I jxcore-log: 
,09-29 07:17:17.331  5695  5741 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-29 07:17:17.331  5695  5741 I jxcore-log: 
,09-29 07:17:17.362   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:18.364   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:18.447  5695  5741 I jxcore-log: # teardown
09-29 07:17:18.447  5695  5741 I jxcore-log: 
,09-29 07:17:18.791  5695  5741 I jxcore-log: # setup
09-29 07:17:18.791  5695  5741 I jxcore-log: 
,09-29 07:17:19.366   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:19.385  5695  5741 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-29 07:17:19.385  5695  5741 I jxcore-log: 
,09-29 07:17:20.366   600   600 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-29 07:17:21.788  5695  5741 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-29 07:17:21.788  5695  5741 I jxcore-log: 
,09-29 07:17:21.804  5695  5741 I jxcore-log: # teardown
09-29 07:17:21.804  5695  5741 I jxcore-log: 
,09-29 07:17:21.866  5695  5741 I jxcore-log: # setup
09-29 07:17:21.866  5695  5741 I jxcore-log: 
,09-29 07:17:22.116  5695  5741 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-29 07:17:22.116  5695  5741 I jxcore-log: 
,09-29 07:17:22.722  5695  5741 I jxcore-log: # teardown
09-29 07:17:22.722  5695  5741 I jxcore-log: 
,09-29 07:17:23.521  5695  5741 I jxcore-log: # setup
09-29 07:17:23.521  5695  5741 I jxcore-log: 
,09-29 07:17:24.486  5695  5741 I jxcore-log: # test defaultDirectory
09-29 07:17:24.486  5695  5741 I jxcore-log: 
,09-29 07:17:25.514  5695  5741 I jxcore-log: ok 87 should be equal
09-29 07:17:25.514  5695  5741 I jxcore-log: 
,09-29 07:17:25.520  5695  5741 I jxcore-log: ok 88 should be equal
09-29 07:17:25.520  5695  5741 I jxcore-log: 
,09-29 07:17:25.531  5695  5741 I jxcore-log: ok 89 should be equal
09-29 07:17:25.531  5695  5741 I jxcore-log: 
,09-29 07:17:25.544  5695  5741 I jxcore-log: # teardown
09-29 07:17:25.544  5695  5741 I jxcore-log: 
,09-29 07:17:25.574  5695  5741 I jxcore-log: # setup
09-29 07:17:25.574  5695  5741 I jxcore-log: 
,09-29 07:17:26.331  5695  5741 I jxcore-log: # test defaultAdapter
09-29 07:17:26.331  5695  5741 I jxcore-log: 
,09-29 07:17:27.265  5695  5741 I jxcore-log: ok 90 should be equal
09-29 07:17:27.265  5695  5741 I jxcore-log: 
09-29 07:17:27.266  5695  5741 I jxcore-log: ok 91 should be equal
09-29 07:17:27.266  5695  5741 I jxcore-log: 
,09-29 07:17:27.270  5695  5741 I jxcore-log: ok 92 should be equal
09-29 07:17:27.270  5695  5741 I jxcore-log: 
,09-29 07:17:27.271  5695  5741 I jxcore-log: ok 93 should be equal
09-29 07:17:27.271  5695  5741 I jxcore-log: 
,09-29 07:17:27.276  5695  5741 I jxcore-log: ok 94 should be equal
09-29 07:17:27.276  5695  5741 I jxcore-log: 
09-29 07:17:27.277  5695  5741 I jxcore-log: ok 95 should be equal
09-29 07:17:27.277  5695  5741 I jxcore-log: 
,09-29 07:17:27.450  5695  5741 I jxcore-log: ok 96 should be equal
09-29 07:17:27.450  5695  5741 I jxcore-log: 
,09-29 07:17:27.451  5695  5741 I jxcore-log: ok 97 should be equal
09-29 07:17:27.451  5695  5741 I jxcore-log: 
,09-29 07:17:27.458  5695  5741 I jxcore-log: # teardown
09-29 07:17:27.458  5695  5741 I jxcore-log: 
,09-29 07:17:27.880  5695  5741 I jxcore-log: # setup
09-29 07:17:27.880  5695  5741 I jxcore-log: 
,09-29 07:17:28.581  5695  5741 I jxcore-log: # enqueue and run in order
09-29 07:17:28.581  5695  5741 I jxcore-log: 
,09-29 07:17:29.192  5695  5741 I jxcore-log: ok 98 firstPromise setTimeout
09-29 07:17:29.192  5695  5741 I jxcore-log: 
,09-29 07:17:29.195  5695  5741 I jxcore-log: ok 99 firstPromise result
09-29 07:17:29.195  5695  5741 I jxcore-log: 
09-29 07:17:29.196  5695  5741 I jxcore-log: ok 100 firstPromise testValue
09-29 07:17:29.196  5695  5741 I jxcore-log: 
,09-29 07:17:29.299  5695  5741 I jxcore-log: ok 101 secondPromise setTimeout
09-29 07:17:29.299  5695  5741 I jxcore-log: 
,09-29 07:17:29.301  5695  5741 I jxcore-log: ok 102 secondPromise result
09-29 07:17:29.301  5695  5741 I jxcore-log: 
09-29 07:17:29.302  5695  5741 I jxcore-log: ok 103 secondPromise testValue
09-29 07:17:29.302  5695  5741 I jxcore-log: 
09-29 07:17:29.304  5695  5741 I jxcore-log: ok 104 thirdPromise in promise
09-29 07:17:29.304  5695  5741 I jxcore-log: 
09-29 07:17:29.307  5695  5741 I jxcore-log: ok 105 thirdPromise result
09-29 07:17:29.307  5695  5741 I jxcore-log: 
09-29 07:17:29.309  5695  5741 I jxcore-log: ok 106 thirdPromise testValue
09-29 07:17:29.309  5695  5741 I jxcore-log: 
,09-29 07:17:29.319  5695  5741 I jxcore-log: # teardown
09-29 07:17:29.319  5695  5741 I jxcore-log: 
,09-29 07:17:29.914  5695  5741 I jxcore-log: # setup
09-29 07:17:29.914  5695  5741 I jxcore-log: 
,09-29 07:17:30.170  5695  5741 I jxcore-log: # enqueueAtTop and run backwards
09-29 07:17:30.170  5695  5741 I jxcore-log: 
,09-29 07:17:31.248  5695  5741 I jxcore-log: ok 107 thirdPromise - first to run
09-29 07:17:31.248  5695  5741 I jxcore-log: 
,09-29 07:17:31.252  5695  5741 I jxcore-log: ok 108 thirdPromise - in resolve
09-29 07:17:31.252  5695  5741 I jxcore-log: 
,09-29 07:17:31.254  5695  5741 I jxcore-log: ok 109 secondPromise - second to run
09-29 07:17:31.254  5695  5741 I jxcore-log: 
,09-29 07:17:31.256  5695  5741 I jxcore-log: ok 110 secondPromise - in catch
09-29 07:17:31.256  5695  5741 I jxcore-log: 
09-29 07:17:31.258  5695  5741 I jxcore-log: ok 111 firstPromise - third to run
09-29 07:17:31.258  5695  5741 I jxcore-log: 
09-29 07:17:31.260  5695  5741 I jxcore-log: ok 112 firstPromise - in then
09-29 07:17:31.260  5695  5741 I jxcore-log: 
,09-29 07:17:31.274  5695  5741 I jxcore-log: ok 113 testing promises
09-29 07:17:31.274  5695  5741 I jxcore-log: 
,09-29 07:17:31.284  5695  5741 I jxcore-log: # teardown
09-29 07:17:31.284  5695  5741 I jxcore-log: 
,09-29 07:17:32.165  5695  5741 I jxcore-log: # setup
09-29 07:17:32.165  5695  5741 I jxcore-log: 
,09-29 07:17:33.450   929  3054 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-29 07:17:33.755  5695  5741 I jxcore-log: # mix enqueue and enqueueAtTop
09-29 07:17:33.755  5695  5741 I jxcore-log: 
,09-29 07:17:33.799  5695  5741 I jxcore-log: ok 114 fourth
09-29 07:17:33.799  5695  5741 I jxcore-log: 
09-29 07:17:33.800  5695  5741 I jxcore-log: ok 115 fourth
09-29 07:17:33.800  5695  5741 I jxcore-log: 
,09-29 07:17:33.801  5695  5741 I jxcore-log: ok 116 second
09-29 07:17:33.801  5695  5741 I jxcore-log: 
,09-29 07:17:33.804  5695  5741 I jxcore-log: ok 117 secondPromise - in then
09-29 07:17:33.804  5695  5741 I jxcore-log: 
,09-29 07:17:33.909  5695  5741 I jxcore-log: ok 118 first
09-29 07:17:33.909  5695  5741 I jxcore-log: 
,09-29 07:17:33.912  5695  5741 I jxcore-log: ok 119 firstPromise - in catch
09-29 07:17:33.912  5695  5741 I jxcore-log: 
,09-29 07:17:33.916  5695  5741 I jxcore-log: ok 120 third
09-29 07:17:33.916  5695  5741 I jxcore-log: 
,09-29 07:17:33.919  5695  5741 I jxcore-log: ok 121 thirdPromise - in then
09-29 07:17:33.919  5695  5741 I jxcore-log: 
,09-29 07:17:33.921  5695  5741 I jxcore-log: ok 122 testingPromises
09-29 07:17:33.921  5695  5741 I jxcore-log: 
,09-29 07:17:33.934  5695  5741 I jxcore-log: # teardown
09-29 07:17:33.934  5695  5741 I jxcore-log: 
,09-29 07:17:34.423  5695  5741 I jxcore-log: # setup
09-29 07:17:34.423  5695  5741 I jxcore-log: 
,09-29 07:17:34.572  5695  5741 I jxcore-log: # queues handled independently
09-29 07:17:34.572  5695  5741 I jxcore-log: 
,09-29 07:17:34.639  5695  5741 I jxcore-log: ok 123 all short operations completed before the long resolves
09-29 07:17:34.639  5695  5741 I jxcore-log: 
,09-29 07:17:34.646  5695  5741 I jxcore-log: # teardown
09-29 07:17:34.646  5695  5741 I jxcore-log: 
,09-29 07:17:34.715  5695  5741 I jxcore-log: # setup
09-29 07:17:34.715  5695  5741 I jxcore-log: 
,09-29 07:17:34.796  5695  5741 I jxcore-log: # basic
09-29 07:17:34.796  5695  5741 I jxcore-log: 
,09-29 07:17:34.821  5695  5741 I jxcore-log: ok 124 sane
09-29 07:17:34.821  5695  5741 I jxcore-log: 
,09-29 07:17:34.826  5695  5741 I jxcore-log: # teardown
09-29 07:17:34.826  5695  5741 I jxcore-log: 
,09-29 07:17:34.881  5695  5741 I jxcore-log: # setup
09-29 07:17:34.881  5695  5741 I jxcore-log: 
,09-29 07:17:34.909  5695  5741 I jxcore-log: # another
09-29 07:17:34.909  5695  5741 I jxcore-log: 
,09-29 07:17:34.942  5695  5741 I jxcore-log: ok 125 sane
09-29 07:17:34.942  5695  5741 I jxcore-log: 
,09-29 07:17:34.948  5695  5741 I jxcore-log: # teardown
09-29 07:17:34.948  5695  5741 I jxcore-log: 
,09-29 07:17:34.978  5695  5741 I jxcore-log: # setup
09-29 07:17:34.978  5695  5741 I jxcore-log: 
,09-29 07:17:35.018  5695  5741 I jxcore-log: # can pass data in setup
09-29 07:17:35.018  5695  5741 I jxcore-log: 
,09-29 07:17:35.050  5695  5741 I jxcore-log: ok 126 test participant has uuid
09-29 07:17:35.050  5695  5741 I jxcore-log: 
,09-29 07:17:35.051  5695  5741 I jxcore-log: ok 127 participant data matches
09-29 07:17:35.051  5695  5741 I jxcore-log: 
09-29 07:17:35.052  5695  5741 I jxcore-log: ok 128 test participant has uuid
09-29 07:17:35.052  5695  5741 I jxcore-log: 
09-29 07:17:35.052  5695  5741 I jxcore-log: ok 129 participant data matches
09-29 07:17:35.052  5695  5741 I jxcore-log: 
09-29 07:17:35.052  5695  5741 I jxcore-log: ok 130 test participant has uuid
09-29 07:17:35.052  5695  5741 I jxcore-log: 
09-29 07:17:35.053  5695  5741 I jxcore-log: ok 131 participant data matches
09-29 07:17:35.053  5695  5741 I jxcore-log: 
09-29 07:17:35.053  5695  5741 I jxcore-log: ok 132 own UUID is found from the participants list
09-29 07:17:35.053  5695  5741 I jxcore-log: 
,09-29 07:17:35.059  5695  5741 I jxcore-log: # teardown
09-29 07:17:35.059  5695  5741 I jxcore-log: 
,09-29 07:17:35.092  5695  5741 I jxcore-log: # setup
09-29 07:17:35.092  5695  5741 I jxcore-log: 
,09-29 07:17:35.130  5695  5741 I jxcore-log: # test thali manager spies
09-29 07:17:35.130  5695  5741 I jxcore-log: 
,09-29 07:17:35.257  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 07:17:35.257  5695  5741 I jxcore-log: 
,09-29 07:17:35.262  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 07:17:35.262  5695  5741 I jxcore-log: 
,09-29 07:17:35.264  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 07:17:35.264  5695  5741 I jxcore-log: 
,09-29 07:17:35.282  5695  5741 I jxcore-log: ok 133 expressPouchDB was called once
09-29 07:17:35.282  5695  5741 I jxcore-log: 
,09-29 07:17:35.283  5695  5741 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-29 07:17:35.283  5695  5741 I jxcore-log: 
09-29 07:17:35.283  5695  5741 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-29 07:17:35.283  5695  5741 I jxcore-log: 
09-29 07:17:35.283  5695  5741 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-29 07:17:35.283  5695  5741 I jxcore-log: 
09-29 07:17:35.284  5695  5741 I jxcore-log: ok 137 PouchDB was called once
09-29 07:17:35.284  5695  5741 I jxcore-log: 
,09-29 07:17:35.284  5695  5741 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-29 07:17:35.284  5695  5741 I jxcore-log: 
09-29 07:17:35.284  5695  5741 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-29 07:17:35.284  5695  5741 I jxcore-log: 
09-29 07:17:35.284  5695  5741 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-29 07:17:35.284  5695  5741 I jxcore-log: 
,09-29 07:17:35.285  5695  5741 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-29 07:17:35.285  5695  5741 I jxcore-log: 
09-29 07:17:35.285  5695  5741 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-29 07:17:35.285  5695  5741 I jxcore-log: 
09-29 07:17:35.285  5695  5741 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-29 07:17:35.285  5695  5741 I jxcore-log: 
,09-29 07:17:35.286  5695  5741 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-29 07:17:35.286  5695  5741 I jxcore-log: 
09-29 07:17:35.286  5695  5741 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-29 07:17:35.286  5695  5741 I jxcore-log: 
09-29 07:17:35.286  5695  5741 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-29 07:17:35.286  5695  5741 I jxcore-log: 
,09-29 07:17:35.286  5695  5741 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-29 07:17:35.286  5695  5741 I jxcore-log: 
09-29 07:17:35.286  5695  5741 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-29 07:17:35.286  5695  5741 I jxcore-log: 
,09-29 07:17:35.287  5695  5741 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-29 07:17:35.287  5695  5741 I jxcore-log: 
09-29 07:17:35.287  5695  5741 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-29 07:17:35.287  5695  5741 I jxcore-log: 
09-29 07:17:35.287  5695  5741 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-29 07:17:35.287  5695  5741 I jxcore-log: 
09-29 07:17:35.287  5695  5741 I jxcore-log: ok 152 Salti was called once
09-29 07:17:35.287  5695  5741 I jxcore-log: 
09-29 07:17:35.288  5695  5741 I jxcore-log: ok 153 Salti was called with 4 arguments
09-29 07:17:35.288  5695  5741 I jxcore-log: 
,09-29 07:17:35.288  5695  5741 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-29 07:17:35.288  5695  5741 I jxcore-log: 
09-29 07:17:35.288  5695  5741 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-29 07:17:35.288  5695  5741 I jxcore-log: 
09-29 07:17:35.288  5695  5741 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-29 07:17:35.288  5695  5741 I jxcore-log: 
09-29 07:17:35.289  5695  5741 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-29 07:17:35.289  5695  5741 I jxcore-log: 
,09-29 07:17:35.289  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 07:17:35.289  5695  5741 I jxcore-log: 
09-29 07:17:35.290  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 07:17:35.290  5695  5741 I jxcore-log: 
,09-29 07:17:35.291  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 07:17:35.291  5695  5741 I jxcore-log: 
,09-29 07:17:35.293  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start listening for advertisements'
09-29 07:17:35.293  5695  5741 I jxcore-log: 
,09-29 07:17:35.297  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start update advertising and listening'
09-29 07:17:35.297  5695  5741 I jxcore-log: 
,09-29 07:17:35.324  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliWifiInfrastructure: 'listening 42711'
09-29 07:17:35.324  5695  5741 I jxcore-log: 
,09-29 07:17:35.326  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 07:17:35.326  5695  5741 I jxcore-log: 
,09-29 07:17:35.344  5695  5741 I jxcore-log: ok 158 ThaliMobile.start was called once
09-29 07:17:35.344  5695  5741 I jxcore-log: 
09-29 07:17:35.344  5695  5741 I jxcore-log: ok 159 ThaliMobile.start was called with 2 arguments
09-29 07:17:35.344  5695  5741 I jxcore-log: 
,09-29 07:17:35.344  5695  5741 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 07:17:35.344  5695  5741 I jxcore-log: 
09-29 07:17:35.344  5695  5741 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 07:17:35.344  5695  5741 I jxcore-log: 
,09-29 07:17:35.345  5695  5741 I jxcore-log: ok 162 ThaliMobile.startListeningForAdvertisements was called once
09-29 07:17:35.345  5695  5741 I jxcore-log: 
09-29 07:17:35.345  5695  5741 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 07:17:35.345  5695  5741 I jxcore-log: 
09-29 07:17:35.345  5695  5741 I jxcore-log: ok 164 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 07:17:35.345  5695  5741 I jxcore-log: 
,09-29 07:17:35.345  5695  5741 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 07:17:35.345  5695  5741 I jxcore-log: 
09-29 07:17:35.345  5695  5741 I jxcore-log: ok 166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 07:17:35.345  5695  5741 I jxcore-log: 
09-29 07:17:35.345  5695  5741 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 07:17:35.345  5695  5741 I jxcore-log: 
,09-29 07:17:35.346  5695  5741 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 07:17:35.346  5695  5741 I jxcore-log: 
09-29 07:17:35.346  5695  5741 I jxcore-log: ok 169 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 07:17:35.346  5695  5741 I jxcore-log: 
,09-29 07:17:35.346  5695  5741 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 07:17:35.346  5695  5741 I jxcore-log: 
09-29 07:17:35.346  5695  5741 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 07:17:35.346  5695  5741 I jxcore-log: 
,09-29 07:17:35.347  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 07:17:35.347  5695  5741 I jxcore-log: 
,09-29 07:17:35.348  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 07:17:35.348  5695  5741 I jxcore-log: 
,09-29 07:17:35.349  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 07:17:35.349  5695  5741 I jxcore-log: 
09-29 07:17:35.351  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 07:17:35.351  5695  5741 I jxcore-log: 
,09-29 07:17:35.355  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 07:17:35.355  5695  5741 I jxcore-log: 
,09-29 07:17:35.357  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 07:17:35.357  5695  5741 I jxcore-log: 
,09-29 07:17:35.359  5695  5741 I jxcore-log: ok 172 ThaliMobile.stop was called once
09-29 07:17:35.359  5695  5741 I jxcore-log: 
,09-29 07:17:35.360  5695  5741 I jxcore-log: ok 173 ThaliMobile.stop was called with 0 arguments
09-29 07:17:35.360  5695  5741 I jxcore-log: 
,09-29 07:17:35.360  5695  5741 I jxcore-log: ok 174 ThaliMobile.stopListeningForAdvertisements was called once
09-29 07:17:35.360  5695  5741 I jxcore-log: 
09-29 07:17:35.361  5695  5741 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-29 07:17:35.361  5695  5741 I jxcore-log: 
09-29 07:17:35.361  5695  5741 I jxcore-log: ok 176 ThaliMobile.stopAdvertisingAndListening was called once
09-29 07:17:35.361  5695  5741 I jxcore-log: 
,09-29 07:17:35.361  5695  5741 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-29 07:17:35.361  5695  5741 I jxcore-log: 
09-29 07:17:35.361  5695  5741 I jxcore-log: ok 178 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-29 07:17:35.361  5695  5741 I jxcore-log: 
09-29 07:17:35.361  5695  5741 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-29 07:17:35.361  5695  5741 I jxcore-log: 
09-29 07:17:35.361  5695  5741 I jxcore-log: ok 180 ThaliPullReplicationFromNotification.prototype.stop was called once
09-29 07:17:35.361  5695  5741 I jxcore-log: 
09-29 07:17:35.362  5695  5741 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-29 07:17:35.362  5695  5741 I jxcore-log: 
09-29 07:17:35.367   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:35.371  5695  5741 I jxcore-log: # teardown
09-29 07:17:35.371  5695  5741 I jxcore-log: 
,09-29 07:17:35.463  5695  5741 I jxcore-log: # setup
09-29 07:17:35.463  5695  5741 I jxcore-log: 
,09-29 07:17:35.560  5695  5741 I jxcore-log: # test thali manager multiple starts and stops
09-29 07:17:35.560  5695  5741 I jxcore-log: 
,09-29 07:17:35.663  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 07:17:35.663  5695  5741 I jxcore-log: 
,09-29 07:17:35.668  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 07:17:35.668  5695  5741 I jxcore-log: 
,09-29 07:17:35.670  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 07:17:35.670  5695  5741 I jxcore-log: 
,09-29 07:17:35.687  5695  5741 I jxcore-log: ok 182 expressPouchDB was called once
09-29 07:17:35.687  5695  5741 I jxcore-log: 
,09-29 07:17:35.687  5695  5741 I jxcore-log: ok 183 expressPouchDB was called with 2 arguments
09-29 07:17:35.687  5695  5741 I jxcore-log: 
09-29 07:17:35.687  5695  5741 I jxcore-log: ok 184 expressPouchDB was called with 'PouchDB' as 1-st argument
09-29 07:17:35.687  5695  5741 I jxcore-log: 
,09-29 07:17:35.687  5695  5741 I jxcore-log: ok 185 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-29 07:17:35.687  5695  5741 I jxcore-log: 
09-29 07:17:35.688  5695  5741 I jxcore-log: ok 186 PouchDB was called once
09-29 07:17:35.688  5695  5741 I jxcore-log: 
09-29 07:17:35.688  5695  5741 I jxcore-log: ok 187 PouchDB was called with 1 arguments
09-29 07:17:35.688  5695  5741 I jxcore-log: 
09-29 07:17:35.688  5695  5741 I jxcore-log: ok 188 PouchDB was called with 'dbName' as 1-st argument
09-29 07:17:35.688  5695  5741 I jxcore-log: 
09-29 07:17:35.688  5695  5741 I jxcore-log: ok 189 ThaliSendNotificationBasedOnReplication was called once
09-29 07:17:35.688  5695  5741 I jxcore-log: 
09-29 07:17:35.688  5695  5741 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-29 07:17:35.688  5695  5741 I jxcore-log: 
09-29 07:17:35.689  5695  5741 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-29 07:17:35.689  5695  5741 I jxcore-log: 
09-29 07:17:35.689  5695  5741 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-29 07:17:35.689  5695  5741 I jxcore-log: 
09-29 07:17:35.689  5695  5741 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-29 07:17:35.689  5695  5741 I jxcore-log: 
09-29 07:17:35.689  5695  5741 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-29 07:17:35.689  5695  5741 I jxcore-log: 
09-29 07:17:35.689  5695  5741 I jxcore-log: ok 195 ThaliPullReplicationFromNotification was called once
09-29 07:17:35.689  5695  5741 I jxcore-log: 
09-29 07:17:35.690  5695  5741 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called with 4 arguments
09-29 07:17:35.690  5695  5741 I jxcore-log: 
09-29 07:17:35.690  5695  5741 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-29 07:17:35.690  5695  5741 I jxcore-log: 
09-29 07:17:35.690  5695  5741 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-29 07:17:35.690  5695  5741 I jxcore-log: 
09-29 07:17:35.690  5695  5741 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-29 07:17:35.690  5695  5741 I jxcore-log: 
09-29 07:17:35.690  5695  5741 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-29 07:17:35.690  5695  5741 I jxcore-log: 
09-29 07:17:35.690  5695  5741 I jxcore-log: ok 201 Salti was called once
09-29 07:17:35.690  5695  5741 I jxcore-log: 
09-29 07:17:35.690  5695  5741 I jxcore-log: ok 202 Salti was called with 4 arguments
09-29 07:17:35.690  5695  5741 I jxcore-log: 
09-29 07:17:35.691  5695  5741 I jxcore-log: ok 203 Salti was called with 'dbName' as 1-st argument
09-29 07:17:35.691  5695  5741 I jxcore-log: 
09-29 07:17:35.691  5695  5741 I jxcore-log: ok 204 Salti was called with 'acl' as 2-st argument
09-29 07:17:35.691  5695  5741 I jxcore-log: 
09-29 07:17:35.691  5695  5741 I jxcore-log: ok 205 Salti was called with 'thaliIdCallback' as 3-st argument
09-29 07:17:35.691  5695  5741 I jxcore-log: 
09-29 07:17:35.691  5695  5741 I jxcore-log: ok 206 Salti was called with 'options' as 4-st argument
09-29 07:17:35.691  5695  5741 I jxcore-log: 
09-29 07:17:35.692  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 07:17:35.692  5695  5741 I jxcore-log: 
,09-29 07:17:35.692  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 07:17:35.692  5695  5741 I jxcore-log: 
09-29 07:17:35.693  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 07:17:35.693  5695  5741 I jxcore-log: 
09-29 07:17:35.695  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start listening for advertisements'
09-29 07:17:35.695  5695  5741 I jxcore-log: 
09-29 07:17:35.699  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start update advertising and listening'
09-29 07:17:35.699  5695  5741 I jxcore-log: 
09-29 07:17:35.703  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliWifiInfrastructure: 'listening 38068'
09-29 07:17:35.703  5695  5741 I jxcore-log: 
09-29 07:17:35.705  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 07:17:35.705  5695  5741 I jxcore-log: 
,09-29 07:17:35.740  5695  5741 I jxcore-log: ok 207 ThaliMobile.start was called once
09-29 07:17:35.740  5695  5741 I jxcore-log: 
,09-29 07:17:35.741  5695  5741 I jxcore-log: ok 208 ThaliMobile.start was called with 2 arguments
09-29 07:17:35.741  5695  5741 I jxcore-log: 
,09-29 07:17:35.741  5695  5741 I jxcore-log: ok 209 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 07:17:35.741  5695  5741 I jxcore-log: 
09-29 07:17:35.741  5695  5741 I jxcore-log: ok 210 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 07:17:35.741  5695  5741 I jxcore-log: 
,09-29 07:17:35.741  5695  5741 I jxcore-log: ok 211 ThaliMobile.startListeningForAdvertisements was called once
09-29 07:17:35.741  5695  5741 I jxcore-log: 
09-29 07:17:35.741  5695  5741 I jxcore-log: ok 212 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 07:17:35.741  5695  5741 I jxcore-log: 
09-29 07:17:35.741  5695  5741 I jxcore-log: ok 213 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 07:17:35.741  5695  5741 I jxcore-log: 
09-29 07:17:35.742  5695  5741 I jxcore-log: ok 214 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 07:17:35.742  5695  5741 I jxcore-log: 
,09-29 07:17:35.742  5695  5741 I jxcore-log: ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 07:17:35.742  5695  5741 I jxcore-log: 
09-29 07:17:35.742  5695  5741 I jxcore-log: ok 216 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 07:17:35.742  5695  5741 I jxcore-log: 
09-29 07:17:35.742  5695  5741 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 07:17:35.742  5695  5741 I jxcore-log: 
09-29 07:17:35.742  5695  5741 I jxcore-log: ok 218 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 07:17:35.742  5695  5741 I jxcore-log: 
09-29 07:17:35.742  5695  5741 I jxcore-log: ok 219 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 07:17:35.742  5695  5741 I jxcore-log: 
,09-29 07:17:35.743  5695  5741 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 07:17:35.743  5695  5741 I jxcore-log: 
09-29 07:17:35.743  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 07:17:35.743  5695  5741 I jxcore-log: 
09-29 07:17:35.744  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 07:17:35.744  5695  5741 I jxcore-log: 
09-29 07:17:35.746  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 07:17:35.746  5695  5741 I jxcore-log: 
09-29 07:17:35.747  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 07:17:35.747  5695  5741 I jxcore-log: 
,09-29 07:17:35.751  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 07:17:35.751  5695  5741 I jxcore-log: 
,09-29 07:17:35.753  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 07:17:35.753  5695  5741 I jxcore-log: 
,09-29 07:17:35.759  5695  5741 I jxcore-log: ok 221 ThaliMobile.stop was called once
09-29 07:17:35.759  5695  5741 I jxcore-log: 
,09-29 07:17:35.759  5695  5741 I jxcore-log: ok 222 ThaliMobile.stop was called with 0 arguments
09-29 07:17:35.759  5695  5741 I jxcore-log: 
09-29 07:17:35.759  5695  5741 I jxcore-log: ok 223 ThaliMobile.stopListeningForAdvertisements was called once
09-29 07:17:35.759  5695  5741 I jxcore-log: 
09-29 07:17:35.759  5695  5741 I jxcore-log: ok 224 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-29 07:17:35.759  5695  5741 I jxcore-log: 
09-29 07:17:35.760  5695  5741 I jxcore-log: ok 225 ThaliMobile.stopAdvertisingAndListening was called once
09-29 07:17:35.760  5695  5741 I jxcore-log: 
09-29 07:17:35.760  5695  5741 I jxcore-log: ok 226 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-29 07:17:35.760  5695  5741 I jxcore-log: 
,09-29 07:17:35.760  5695  5741 I jxcore-log: ok 227 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-29 07:17:35.760  5695  5741 I jxcore-log: 
09-29 07:17:35.760  5695  5741 I jxcore-log: ok 228 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-29 07:17:35.760  5695  5741 I jxcore-log: 
09-29 07:17:35.760  5695  5741 I jxcore-log: ok 229 ThaliPullReplicationFromNotification.prototype.stop was called once
09-29 07:17:35.760  5695  5741 I jxcore-log: 
09-29 07:17:35.760  5695  5741 I jxcore-log: ok 230 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-29 07:17:35.760  5695  5741 I jxcore-log: 
,09-29 07:17:35.761  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 07:17:35.761  5695  5741 I jxcore-log: 
,09-29 07:17:35.761  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 07:17:35.761  5695  5741 I jxcore-log: 
09-29 07:17:35.762  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 07:17:35.762  5695  5741 I jxcore-log: 
,09-29 07:17:35.765  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start listening for advertisements'
09-29 07:17:35.765  5695  5741 I jxcore-log: 
,09-29 07:17:35.767  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start update advertising and listening'
09-29 07:17:35.767  5695  5741 I jxcore-log: 
,09-29 07:17:35.771  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliWifiInfrastructure: 'listening 44873'
09-29 07:17:35.771  5695  5741 I jxcore-log: 
,09-29 07:17:35.773  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 07:17:35.773  5695  5741 I jxcore-log: 
,09-29 07:17:35.775  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 07:17:35.775  5695  5741 I jxcore-log: 
,09-29 07:17:35.776  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 07:17:35.776  5695  5741 I jxcore-log: 
,09-29 07:17:35.778  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 07:17:35.778  5695  5741 I jxcore-log: 
,09-29 07:17:35.779  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 07:17:35.779  5695  5741 I jxcore-log: 
,09-29 07:17:35.783  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 07:17:35.783  5695  5741 I jxcore-log: 
,09-29 07:17:35.785  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 07:17:35.785  5695  5741 I jxcore-log: 
,09-29 07:17:35.787  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 07:17:35.787  5695  5741 I jxcore-log: 
,09-29 07:17:35.788  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 07:17:35.788  5695  5741 I jxcore-log: 
09-29 07:17:35.788  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 07:17:35.788  5695  5741 I jxcore-log: 
,09-29 07:17:35.791  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start listening for advertisements'
09-29 07:17:35.791  5695  5741 I jxcore-log: 
,09-29 07:17:35.793  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start update advertising and listening'
09-29 07:17:35.793  5695  5741 I jxcore-log: 
,09-29 07:17:35.798  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliWifiInfrastructure: 'listening 38639'
09-29 07:17:35.798  5695  5741 I jxcore-log: 
,09-29 07:17:35.801  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 07:17:35.801  5695  5741 I jxcore-log: 
,09-29 07:17:35.803  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 07:17:35.803  5695  5741 I jxcore-log: 
,09-29 07:17:35.804  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 07:17:35.804  5695  5741 I jxcore-log: 
,09-29 07:17:35.806  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 07:17:35.806  5695  5741 I jxcore-log: 
,09-29 07:17:35.807  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 07:17:35.807  5695  5741 I jxcore-log: 
,09-29 07:17:35.811  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 07:17:35.811  5695  5741 I jxcore-log: 
,09-29 07:17:35.812  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 07:17:35.812  5695  5741 I jxcore-log: 
,09-29 07:17:35.815  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 07:17:35.815  5695  5741 I jxcore-log: 
,09-29 07:17:35.816  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 07:17:35.816  5695  5741 I jxcore-log: 
,09-29 07:17:35.816  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 07:17:35.816  5695  5741 I jxcore-log: 
,09-29 07:17:35.818  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start listening for advertisements'
09-29 07:17:35.818  5695  5741 I jxcore-log: 
,09-29 07:17:35.820  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'start update advertising and listening'
09-29 07:17:35.820  5695  5741 I jxcore-log: 
,09-29 07:17:35.824  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliWifiInfrastructure: 'listening 38201'
09-29 07:17:35.824  5695  5741 I jxcore-log: 
,09-29 07:17:35.826  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 07:17:35.826  5695  5741 I jxcore-log: 
,09-29 07:17:35.846  5695  5741 I jxcore-log: ok 231 ThaliMobile.start was called once
09-29 07:17:35.846  5695  5741 I jxcore-log: 
,09-29 07:17:35.846  5695  5741 I jxcore-log: ok 232 ThaliMobile.start was called with 2 arguments
09-29 07:17:35.846  5695  5741 I jxcore-log: 
09-29 07:17:35.846  5695  5741 I jxcore-log: ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-29 07:17:35.846  5695  5741 I jxcore-log: 
09-29 07:17:35.846  5695  5741 I jxcore-log: ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-29 07:17:35.846  5695  5741 I jxcore-log: 
09-29 07:17:35.846  5695  5741 I jxcore-log: ok 235 ThaliMobile.startListeningForAdvertisements was called once
09-29 07:17:35.846  5695  5741 I jxcore-log: 
09-29 07:17:35.847  5695  5741 I jxcore-log: ok 236 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-29 07:17:35.847  5695  5741 I jxcore-log: 
09-29 07:17:35.847  5695  5741 I jxcore-log: ok 237 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-29 07:17:35.847  5695  5741 I jxcore-log: 
09-29 07:17:35.847  5695  5741 I jxcore-log: ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-29 07:17:35.847  5695  5741 I jxcore-log: 
,09-29 07:17:35.847  5695  5741 I jxcore-log: ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-29 07:17:35.847  5695  5741 I jxcore-log: 
09-29 07:17:35.847  5695  5741 I jxcore-log: ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-29 07:17:35.847  5695  5741 I jxcore-log: 
09-29 07:17:35.847  5695  5741 I jxcore-log: ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 07:17:35.847  5695  5741 I jxcore-log: 
09-29 07:17:35.848  5695  5741 I jxcore-log: ok 242 ThaliPullReplicationFromNotification.prototype.start was called once
09-29 07:17:35.848  5695  5741 I jxcore-log: 
09-29 07:17:35.848  5695  5741 I jxcore-log: ok 243 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-29 07:17:35.848  5695  5741 I jxcore-log: 
09-29 07:17:35.848  5695  5741 I jxcore-log: ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-29 07:17:35.848  5695  5741 I jxcore-log: 
,09-29 07:17:35.848  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-29 07:17:35.848  5695  5741 I jxcore-log: 
09-29 07:17:35.850  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-29 07:17:35.850  5695  5741 I jxcore-log: 
,09-29 07:17:35.853  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-29 07:17:35.853  5695  5741 I jxcore-log: 
,09-29 07:17:35.855  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-29 07:17:35.855  5695  5741 I jxcore-log: 
,09-29 07:17:35.862  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-29 07:17:35.862  5695  5741 I jxcore-log: 
,09-29 07:17:35.864  5695  5741 I jxcore-log: 2016-09-29 11:17:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-29 07:17:35.864  5695  5741 I jxcore-log: 
,09-29 07:17:35.870  5695  5741 I jxcore-log: # teardown
09-29 07:17:35.870  5695  5741 I jxcore-log: 
,09-29 07:17:36.000  5695  5741 I jxcore-log: # setup
09-29 07:17:36.000  5695  5741 I jxcore-log: 
,09-29 07:17:36.052  5695  5741 I jxcore-log: # test write
09-29 07:17:36.052  5695  5741 I jxcore-log: 
,09-29 07:17:36.243  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-29 07:17:36.243  5695  5741 I jxcore-log: 
,09-29 07:17:36.248  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-29 07:17:36.248  5695  5741 I jxcore-log: 
,09-29 07:17:36.249  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'creating express pouchdb instance'
09-29 07:17:36.249  5695  5741 I jxcore-log: 
,09-29 07:17:36.272  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-29 07:17:36.272  5695  5741 I jxcore-log: 
,09-29 07:17:36.273  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-29 07:17:36.273  5695  5741 I jxcore-log: 
,09-29 07:17:36.273  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'starting ThaliMobile'
09-29 07:17:36.273  5695  5741 I jxcore-log: 
,09-29 07:17:36.276  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'start listening for advertisements'
09-29 07:17:36.276  5695  5741 I jxcore-log: 
,09-29 07:17:36.281  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'start update advertising and listening'
09-29 07:17:36.281  5695  5741 I jxcore-log: 
,09-29 07:17:36.287  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliWifiInfrastructure: 'listening 40764'
09-29 07:17:36.287  5695  5741 I jxcore-log: 
,09-29 07:17:36.291  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-29 07:17:36.291  5695  5741 I jxcore-log: 
,09-29 07:17:36.368   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:36.999  5695  5741 I jxcore-log: 2016-09-29 11:17:36 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-29 07:17:36.999  5695  5741 I jxcore-log: 
,09-29 07:17:37.030  5695  5741 I jxcore-log: 2016-09-29 11:17:37 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-29 07:17:37.030  5695  5741 I jxcore-log: 
,09-29 07:17:37.369   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:37.518  5695  5741 I jxcore-log: 2016-09-29 11:17:37 - ERROR thaliSendNotificationBasedOnReplication: 'Got an error on the replication change listener - {"name":"AssertionError","actual":null,"expected":true,"operator":"==","message":"If beacons werepreviously updated then there has to be a refresh timer for them.","stack":"ok@assert.js:126:1\nThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9\nPouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9"}'
09-29 07:17:37.518  5695  5741 I jxcore-log: 
,09-29 07:17:37.520  5695  5741 I jxcore-log: 2016-09-29 11:17:37 - ERROR TestsProcess: 'uncaught promise rejection, error: 'AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.', stack: 'ok@assert.js:126:1
09-29 07:17:37.520  5695  5741 I jxcore-log: ThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:359:9
09-29 07:17:37.520  5695  5741 I jxcore-log: PouchDBGenerator/PouchAlt.prototype.addListener/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/utils/pouchDBGenerator.js:101:9''
09-29 07:17:37.520  5695  5741 I jxcore-log: 
09-29 07:17:37.521  5695  5741 I jxcore-log: 2016-09-29 11:17:37 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-29 07:17:37.521  5695  5741 I jxcore-log: 
,09-29 07:17:38.028  6085  6085 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-29 07:17:38.048  6085  6085 D AndroidRuntime: CheckJNI is OFF
,09-29 07:17:38.076  6085  6085 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-29 07:17:38.104  6085  6085 I Radio-JNI: register_android_hardware_Radio DONE
,09-29 07:17:38.119  6085  6085 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-29 07:17:38.127   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-29 07:17:38.128   929   942 I ActivityManager: Killing 5695:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-29 07:17:38.242   929  3901 I WindowState: WIN DEATH: Window{c6938fe u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-29 07:17:38.242   929  3055 D WifiService: Client connection lost with reason: 4
09-29 07:17:38.246   929  3255 D GraphicsStats: Buffer count: 2
,09-29 07:17:38.280   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-29 07:17:38.284   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-29 07:17:38.285   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-29 07:17:38.285   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-29 07:17:38.285   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:17:38.285   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:17:38.285   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 07:17:38.285   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-29 07:17:38.285   929   942 I ActivityManager:   Force finishing activity ActivityRecord{4fa8323 u0 com.test.thalitest/.MainActivity t2}
,09-29 07:17:38.286   929   952 I art     : Starting a blocking GC Explicit
,09-29 07:17:38.296   929  3683 W ActivityManager: Spurious death for ProcessRecord{da6b6fc 0:com.test.thalitest/u0a77}, curProc for 5695: null
,09-29 07:17:38.296   929   947 W WindowManager: Attempted to add application window with unknown token Token{2b0b020 ActivityRecord{4fa8323 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-29 07:17:38.297   929   947 W WindowManager: Token{2b0b020 ActivityRecord{4fa8323 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{2b0b020 ActivityRecord{4fa8323 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
,09-29 07:17:38.297   929   947 W WindowManager: view not successfully added to wm, removing view
09-29 07:17:38.297   929   947 W WindowManager: Exception when adding starting window
09-29 07:17:38.297   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{ea4e185 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-29 07:17:38.297   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-29 07:17:38.297   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-29 07:17:38.297   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-29 07:17:38.297   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-29 07:17:38.297   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-29 07:17:38.297   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:17:38.297   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:17:38.297   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-29 07:17:38.297   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-29 07:17:38.370   600   600 I ServiceManager: Waiting for service AtCmdFwd...
,09-29 07:17:38.376   929   952 I art     : Explicit concurrent mark sweep GC freed 75554(5MB) AllocSpace objects, 34(1252KB) LOS objects, 33% free, 29MB/43MB, paused 1.515ms total 89.390ms
,09-29 07:17:38.396   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-29 07:17:38.398  6085  6085 I art     : System.exit called, status: 0
,09-29 07:17:38.398  6085  6085 I AndroidRuntime: VM exiting with result code 0.
,09-29 07:17:38.413   929   952 I ActivityManager: Start proc 6095:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-29 07:17:38.414   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-29 07:17:38.420   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-29 07:17:38.424  5974  5974 D BluetoothMapAppObserver: onReceive
09-29 07:17:38.424  5974  5974 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-29 07:17:38.429  3979  4202 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-29 07:17:38.428  3761  3761 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-29 07:17:38.439   929  3046 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-29 07:17:38.456  3761  6107 I Keyboard.Facilitator.DecoderInitializer: run()
,09-29 07:17:38.461  3503  6109 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-29 07:17:38.478  3761  6107 I Decoder : createOrResetDecoder
,09-29 07:17:38.482  3891  3891 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-29 07:17:38.502   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-29 07:17:38.520  3690  3690 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-29 07:17:38.521  3690  3690 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-29 07:17:38.528    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 07:17:38.535    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 07:17:38.545    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-29 07:17:38.553  3690  3690 I ConfigService: onCreate
,09-29 07:17:38.555  3690  6115 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-29 07:17:38.555  3690  6115 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFi,le:49)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-29 07:17:38.555  3690  6115 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-29 07:17:38.557  3690  6115 W SQLiteOpenHelper: Opened config.db in read-only mode
09-29 07:17:38.557  3503  3525 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj3061E39E4) - 
09-29 07:17:38.570  4144  6114 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-29 07:17:38.581  3761  6107 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-29 07:17:38.583  4144  6114 D AccountUtils: Clearing selected account for com.test.thalitest
,09-29 07:17:38.607  4144  6114 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,--------- beginning of crash
09-29 07:17:38.638  3503  3525 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-29 07:17:38.638  3503  3525 E AndroidRuntime: Process: android.process.acore, PID: 3503
09-29 07:17:38.638  3503  3525 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-29 07:17:38.638  3503  3525 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-29 07:17:38.667  3503  3525 I Process : Sending signal. PID: 3503 SIG: 9
,09-29 07:17:38.916   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
