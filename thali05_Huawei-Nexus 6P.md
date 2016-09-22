#### Test 85046911906f2db_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-22 03:00:52.783   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-22 03:00:53.286  5457  5457 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-22 03:00:53.292  5457  5457 D AndroidRuntime: CheckJNI is OFF
09-22 03:00:53.318  5457  5457 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-22 03:00:53.358  5457  5457 I Radio-JNI: register_android_hardware_Radio DONE
09-22 03:00:53.374  5457  5457 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-22 03:00:53.392   931   942 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-22 03:00:53.432   931   942 I ActivityManager: Start proc 5466:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-22 03:00:53.444  5457  5457 D AndroidRuntime: Shutting down VM
,09-22 03:00:53.771   931  3592 I WindowManager: Screenshot max retries 4 of Token{e69e02 ActivityRecord{5f1d34d u0 com.test.thalitest/.MainActivity t2}} appWin=Window{4d31f05 u0 Starting com.test.thalitest} drawState=2
09-22 03:00:53.844  5466  5466 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-22 03:00:53.878  5466  5466 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-22 03:00:53.953  5466  5466 I LibraryLoader: Time to load native libraries: 69 ms (timestamps 1183-1252)
09-22 03:00:53.953  5466  5466 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 03:00:53.989  5466  5466 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8faeba5}
09-22 03:00:53.990  5466  5466 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-22 03:00:53.991  5466  5466 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-22 03:00:53.998  5466  5466 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-22 03:00:53.999  5466  5466 E SysUtils: ApplicationContext is null in ApplicationStatus
09-22 03:00:54.054  5466  5466 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-22 03:00:54.071  5466  5466 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 03:00:54.071  5466  5466 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-22 03:00:54.071  5466  5466 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-22 03:00:54.071  5466  5466 I Adreno  : Build Date                       : 12/06/15
09-22 03:00:54.071  5466  5466 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-22 03:00:54.071  5466  5466 I Adreno  : Local Branch                     : mybranch17112971
09-22 03:00:54.071  5466  5466 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-22 03:00:54.071  5466  5466 I Adreno  : Remote Branch                    : NONE
09-22 03:00:54.071  5466  5466 I Adreno  : Reconstruct Branch               : NOTHING
09-22 03:00:54.128   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ab29bd:true
09-22 03:00:54.166   728   728 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22207]" dev="sockfs" ino=22207 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 03:00:54.166   728   728 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22207]" dev="sockfs" ino=22207 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 03:00:54.180  5466  5466 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-22 03:00:54.189  5466  5466 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
09-22 03:00:54.216   408   408 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31270]" dev="sockfs" ino=31270 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 03:00:54.216   408   408 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31270]" dev="sockfs" ino=31270 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-22 03:00:54.219  5466  5503 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-22 03:00:54.223  3145  3145 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15349]" dev="sockfs" ino=15349 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-22 03:00:54.223  3145  3145 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[15349]" dev="sockfs" ino=15349 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-22 03:00:54.228  5466  5490 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-22 03:00:54.250  5466  5503 I OpenGLRenderer: Initialized EGL, version 1.4
09-22 03:00:54.322   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +549ms (total +917ms)
09-22 03:00:54.353  5466  5466 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5466
09-22 03:00:54.462  5466  5466 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-22 03:00:54.682  5466  5506 D jxcore_app_log: JniHelper::setJavaVM(0xf4f3c000), pthread_self() = -604243664
09-22 03:00:54.689  5466  5506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-22 03:00:54.689  5466  5506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-22 03:00:54.689  5466  5506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-22 03:00:54.689  5466  5506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-22 03:00:54.689  5466  5506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-22 03:00:54.689  5466  5506 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fc1e92 added. We now have 1 listener(s)
09-22 03:00:54.692  5466  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-22 03:00:54.693  5466  5506 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:00:54.694  5466  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:00:54.694  5466  5506 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-22 03:00:54.697  5466  5506 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@502fd19 added. We now have 1 listener(s)
09-22 03:00:54.697  5466  5506 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:00:54.705   931  2937 D WifiService: New client listening to asynchronous messages
09-22 03:00:54.706  5466  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 03:00:54.706  5466  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-22 03:00:54.706  5466  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-22 03:00:54.706  5466  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-22 03:00:54.706  5466  5506 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-22 03:00:54.708  5466  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:00:54.708  5466  5506 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-22 03:00:54.714  5466  5506 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:00:54.714  5466  5506 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:00:54.714  5466  5506 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-22 03:00:54.714  5466  5506 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:00:54.716  5466  5506 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 03:00:54.717  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:00:54.720  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:00:54.977  5466  5466 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-22 03:00:55.114  5466  5512 W jxcore-log: Initializing JXcore engine
09-22 03:00:55.115  5466  5512 W jxcore-log: JXcore engine is ready
09-22 03:00:55.136  5512  5512 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10701 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-22 03:00:55.136  5512  5512 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13350]" dev="sockfs" ino=13350 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-22 03:00:55.136  5512  5512 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5200 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-22 03:00:55.136  5512  5512 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31245]" dev="sockfs" ino=31245 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
09-22 03:00:55.148  5466  5512 W jxcore-log: Starting JXcore engine
09-22 03:00:55.165  5466  5475 I art     : Background sticky concurrent mark sweep GC freed 81569(8MB) AllocSpace objects, 19(2MB) LOS objects, 24% free, 24MB/32MB, paused 1.195ms total 101.363ms
09-22 03:00:55.202  5466  5512 W jxcore-log: Platform android
09-22 03:00:55.202  5466  5512 W jxcore-log: 
09-22 03:00:55.202  5466  5512 W jxcore-log: Process ARCH arm
09-22 03:00:55.202  5466  5512 W jxcore-log: 
09-22 03:00:55.301  5466  5512 I jxcore-log: JXcore Cordova bridge is ready!
09-22 03:00:55.301  5466  5512 I jxcore-log: 
09-22 03:00:55.301  5466  5512 W jxcore-log: JXcore engine is started
09-22 03:00:55.308  5466  5506 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-22 03:00:55.311  5466  5466 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-22 03:00:58.217   931  5204 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-22 03:01:01.864  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-22 03:01:01.864  5466  5512 I jxcore-log: 
,09-22 03:01:01.865  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-22 03:01:01.865  5466  5512 I jxcore-log: 
,09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:01.869  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 03:01:01.871  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-22 03:01:01.873  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-22 03:01:01.873  5466  5512 I jxcore-log: 
,09-22 03:01:01.874  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-22 03:01:01.874  5466  5512 I jxcore-log: 
,09-22 03:01:02.224  5466  5512 D executeNativeTests: Running unit tests
,09-22 03:01:02.261  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 03:01:02.261  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c added. We now have 2 listener(s)
09-22 03:01:02.261  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:02.261  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:02.261  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 03:01:02.261  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:02.262  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 added. We now have 2 listener(s)
,09-22 03:01:02.262  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:02.262  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 03:01:02.263  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:02.266  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-22 03:01:02.266  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.267  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-22 03:01:02.268  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-22 03:01:02.268  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 03:01:02.268  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 03:01:02.269  5466  5512 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-22 03:01:02.269  5466  5512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 03:01:02.269  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 03:01:02.269  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 03:01:02.269  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 03:01:02.269  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 03:01:02.269  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.269  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.269  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 03:01:02.269  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.269  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:02.270  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:02.270  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c removed from the list
09-22 03:01:02.270  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.270  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 removed from the list
09-22 03:01:02.272  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.278  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.278  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.278  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.279  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.279  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.279  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.279  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.279  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.279  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.280  5466  5512 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-22 03:01:02.281  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 03:01:02.281  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.281  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.281  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.281  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.281  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 03:01:02.281  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.281  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.281  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
,09-22 03:01:02.281  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.281  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.281  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.281  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.281  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.281  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.282  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.282  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.282  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 03:01:02.284  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 03:01:02.285  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 03:01:02.285  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 03:01:02.285  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 03:01:02.285  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 03:01:02.285  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 03:01:02.285  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 03:01:02.285  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.285  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.285  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.285  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 03:01:02.285  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.285  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.285  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.285  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.285  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.285  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.285  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 03:01:02.285  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.285  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.286  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.286  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.286  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.286  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.286  5466  5512 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 03:01:02.287  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:02.289  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:01:02.290  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.290  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:02.290  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 03:01:02.290  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 03:01:02.290  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 03:01:02.290  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.290  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 03:01:02.292  5466  5512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 03:01:02.292  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 03:01:02.294  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.295  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 03:01:02.296  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 03:01:02.296  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, sc,an result type: 0
09-22 03:01:02.298  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.299  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-22 03:01:02.300  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-22 03:01:02.300  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 03:01:02.301  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 03:01:02.301  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 03:01:02.301  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:02.303  4389  4402 D BtGatt.GattService: registerClient() - UUID=4a2a58bd-a692-4e72-8029-fdc20536eaab
09-22 03:01:02.304  4389  4451 D BtGatt.GattService: onClientRegistered() - UUID=4a2a58bd-a692-4e72-8029-fdc20536eaab, clientIf=5
09-22 03:01:02.305  5466  5476 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 03:01:02.306  4389  4404 D BtGatt.GattService: start scan with filters
09-22 03:01:02.311  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 03:01:02.311  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 03:01:02.311  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 03:01:02.311  4389  4454 D BtGatt.ScanManager: handling starting scan
09-22 03:01:02.311  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 03:01:02.312  4389  4454 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
09-22 03:01:02.313  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:02.313  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 03:01:02.314  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:02.314  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 03:01:02.315  5466  5512 I io.jxcore.node.ConnectionHelper: start: OK
09-22 03:01:02.316  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.316  5466  5512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 03:01:02.317  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.317  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 03:01:02.317  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.317  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 03:01:02.317  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 03:01:02.317  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 03:01:02.317  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 03:01:02.317  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 03:01:02.317  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 03:01:02.317  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 03:01:02.317  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:02.318  4389  4402 D BtGatt.GattService: stopScan() - queue size =1
09-22 03:01:02.318  4389  4404 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 03:01:02.318  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 03:01:02.318  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 03:01:02.318  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 03:01:02.318  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 03:01:02.318  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 03:01:02.319  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.319  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 03:01:02.319  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 03:01:02.319  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 03:01:02.319  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:02.320  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.320  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.320  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:02.320  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.320  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.320  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.320  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.320  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.320  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.321  5466  5512 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 03:01:02.321  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.321  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.321  4389  4451 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 03:01:02.321  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.321  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.321  4389  4454 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:02.324  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:01:02.325  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.325  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:02.325  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 03:01:02.325  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 03:01:02.325  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 03:01:02.325  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.326  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 03:01:02.328  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.329  5466  5512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 03:01:02.329  4389  4451 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 03:01:02.329  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 03:01:02.329  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.330  4389  4454 D BtGatt.ScanManager: Starting BLE batch scan
09-22 03:01:02.330  4389  4454 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 03:01:02.331  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.333  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 03:01:02.333  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 03:01:02.333  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 03:,01:02.334  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 03:01:02.335  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 03:01:02.335  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 03:01:02.335  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:02.336  4389  4404 D BtGatt.GattService: registerClient() - UUID=daf3d0b9-896a-4919-bf89-c80c14c6b113
09-22 03:01:02.336  4389  4451 D BtGatt.GattService: onClientRegistered() - UUID=daf3d0b9-896a-4919-bf89-c80c14c6b113, clientIf=5
09-22 03:01:02.337  5466  5476 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 03:01:02.337  4389  4601 D BtGatt.GattService: start scan with filters
09-22 03:01:02.342  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 03:01:02.342  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 03:01:02.342  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 03:01:02.342  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 03:01:02.342  4389  4451 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 03:01:02.343  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.343  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:02.343  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 03:01:02.343  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:02.343  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 03:01:02.344  5466  5512 I io.jxcore.node.ConnectionHelper: start: OK
09-22 03:01:02.346  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.347  5466  5512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 03:01:02.347  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.347  4389  4451 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 03:01:02.347  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 03:01:02.347  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.347  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.347  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 03:01:02.347  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 03:01:02.347  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 03:01:02.347  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 03:01:02.347  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 03:01:02.347  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 03:01:02.347  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 03:01:02.348  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:02.348  4389  4404 D BtGatt.GattService: stopScan() - queue size =0
09-22 03:01:02.349  4389  4609 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 03:01:02.349  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 03:01:02.349  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 03:01:02.349  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 03:01:02.349  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 03:01:02.349  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 03:01:02.350  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.350  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 03:01:02.350  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 03:01:02.350  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 03:01:02.351  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:02.351  4389  4451 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 03:01:02.351  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.351  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.351  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.351  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.351  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:02.351  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.351  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.351  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.351  4389  4454 D BtGatt.ScanManager: stopping BLe Batch
09-22 03:01:02.351  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.351  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.351  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.352  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.352  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.352  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.353  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.353  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.354  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.354  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.354  5466  5512 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-22 03:01:02.355  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.355  4389  4451 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 03:01:02.355  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.355  4389  4454 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:02.357  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:01:02.358  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.358  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:02.358  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 03:01:02.358  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 03:01:02.358  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 03:01:02.358  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.358  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 03:01:02.358  4389  4451 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 03:01:02.358  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.360  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.360  4389  4454 D BtGatt.ScanManager: handling starting scan
09-22 03:01:02.361  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.361  5466  5512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 03:01:02.361  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 03:01:02.363  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 03:01:02.363  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 03:01:02.363  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 03:01:02.365  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 03:01:02.365  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 03:01:02.365  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 03:01:02.365  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:02.366  4389  4451 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 03:01:02.366  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.366  4389  4609 D BtGatt.GattService: registerClient() - UUID=ff4550ce-cf69-4d02-bbae-452071c3034b
09-22 03:01:02.366  4389  4454 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 03:01:02.366  4389  4451 D BtGatt.GattService: onClientRegistered() - UUID=ff4550ce-cf69-4d02-bbae-452071c3034b, clientIf=5
09-22 03:01:02.367  5466  5476 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 03:01:02.367  4389  4402 D BtGatt.GattService: start scan with filters
09-22 03:01:02.370  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-22 03:01:02.370  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 03:01:02.370  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 03:01:02.370  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-22 03:01:02.371  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:02.371  4389  4451 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 03:01:02.371  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 03:01:02.371  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.371  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:02.371  4389  4454 D BtGatt.ScanManager: Starting BLE batch scan
09-22 03:01:02.371  4389  4454 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 03:01:02.371  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 03:01:02.372  5466  5512 I io.jxcore.node.ConnectionHelper: start: OK
09-22 03:01:02.372  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.372  5466  5512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 03:01:02.372  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.372  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 03:01:02.372  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.372  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 03:01:02.372  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 03:01:02.372  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 03:01:02.372  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 03:01:02.372  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 03:01:02.372  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 03:01:02.373  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 03:01:02.380  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:02.380  4389  4451 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 03:01:02.380  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.380  4389  4402 D BtGatt.GattService: stopScan() - queue size =1
09-22 03:01:02.385  4389  4601 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 03:01:02.385  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 03:01:02.385  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 03:01:02.385  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 03:01:02.385  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 03:01:02.385  4389  4451 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 03:01:02.385  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 03:01:02.385  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.386  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.386  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 03:01:02.386  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 03:01:02.386  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 03:01:02.387  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:02.388  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.388  5466  5512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-22 03:01:02.388  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.388  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.388  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.388  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.388  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.388  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:02.388  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.388  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.388  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.388  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.388  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.388  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.388  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.388  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.388  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.389  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.389  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.389  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.389  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.389  5466  5512 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-22 03:01:02.389  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.389  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.389  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.390  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.390  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.390  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.390  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.390  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.390  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.390  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.390  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.390  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.390  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.390  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.391  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.391  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.391  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.391  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.391  4389  4451 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 03:01:02.391  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.391  4389  4454 D BtGatt.ScanManager: stopping BLe Batch
09-22 03:01:02.391  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 03:01:02.391  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.391  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.392  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.392  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.392  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.392  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.392  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.392  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.392  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.392  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.392  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.392  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.392  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.392  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.392  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.392  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.392  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.392  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.393  5466  5512 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-22 03:01:02.393  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.393  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.393  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.393  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.393  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.393  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.393  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.393  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.393  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.393  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.393  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.393  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.393  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.393  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.393  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.394  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.394  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.394  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.394  5466  5512 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-22 03:01:02.394  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.394  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.394  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.394  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.394  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.394  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.394  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.394  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.394  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.394  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.394  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.394  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.394  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.394  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.395  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.395  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.395  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.395  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.396  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 03:01:02.396  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 03:01:02.396  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 03:01:02.396  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 03:01:02.396  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-22 03:01:02.396  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-22 03:01:02.396  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.396  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.396  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.396  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.396  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.396  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.396  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.396  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.396  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.396  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.396  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.396  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.396  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.397  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.397  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.397  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.397  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.397  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.397  5466  5512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 03:01:02.397  5466  5512 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 03:01:02.397  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-22 03:01:02.398  4389  4451 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 03:01:02.398  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.398  4389  4454 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 03:01:02.398  5466  5512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 03:01:02.398  5466  5512 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-22 03:01:02.398  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-22 03:01:02.399  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-22 03:01:02.399  5466  5512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-22 03:01:02.400  5466  5512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 03:01:02.400  5466  5512 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-22 03:01:02.400  5466  5512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 03:01:02.400  5466  5512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 03:01:02.400  5466  5512 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-22 03:01:02.400  5466  5512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 03:01:02.400  5466  5512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-22 03:01:02.400  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-22 03:01:02.403  4389  4451 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 03:01:02.403  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.403  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-22 03:01:02.403  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-22 03:01:02.403  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-22 03:01:02.404  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-22 03:01:02.404  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-22 03:01:02.404  5466  5512 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-22 03:01:02.404  5466  5512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-22 03:01:02.404  5466  5512 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-22 03:01:02.404  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.404  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.404  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.404  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.404  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.404  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.404  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-22 03:01:02.405  4389  4454 D BtGatt.ScanManager: handling starting scan
09-22 03:01:02.405  5466  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-22 03:01:02.405  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.405  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.405  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.405  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.405  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.405  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.405  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.405  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.406  5466  5514 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-22 03:01:02.406  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.406  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.406  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.406  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.406  5466  5512 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-22 03:01:02.407  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.407  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.407  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.407  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.407  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.407  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.407  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.407  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.407  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
,09-22 03:01:02.407  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.407  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.407  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.407  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.407  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.408  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.408  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.408  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.408  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.409  5466  5512 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-22 03:01:02.409  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.409  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.409  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.409  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.409  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.409  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.409  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.409  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.409  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.409  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.409  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.409  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.409  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.409  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.410  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.410  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.410  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.410  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.410  5466  5512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-22 03:01:02.410  5466  5512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-22 03:01:02.410  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 03:01:02.410  5466  5512 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-22 03:01:02.410  5466  5512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 03:01:02.410  5466  5512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-22 03:01:02.410  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 03:01:02.410  5466  5512 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-22 03:01:02.410  4389  4451 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 03:01:02.410  5466  5512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-22 03:01:02.410  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.410  5466  5512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-22 03:01:02.410  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 03:01:02.410  5466  5512 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-22 03:01:02.410  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.410  4389  4454 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 03:01:02.410  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.410  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.410  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.411  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.411  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.411  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.411  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.411  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.411  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.411  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.411  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.411  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.411  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.411  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.411  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.411  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.411  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.411  5466  5513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 03:01:02.412  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.412  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.412  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.412  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.412  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.412  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.412  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.412  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.412  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.412  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.412  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.412  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.412  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.412  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.412  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.412  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.412  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.412  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.412  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.412  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.412  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.412  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.412  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.412  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.412  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.412  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.412  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.412  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.412  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.413  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.413  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.413  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.413  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.413  5466  5512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-22 03:01:02.414  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.414  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-22 03:01:02.415  5466  5512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-22 03:01:02.415  5466  5512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-22 03:01:02.415  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-22 03:01:02.415  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 03:01:02.415  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.415  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-22 03:01:02.415  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-22 03:01:02.415  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-22 03:01:02.415  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.415  5466  5512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-22 03:01:02.415  5466  5466 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-22 03:01:02.416  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.416  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.416  5466  5466 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-22 03:01:02.416  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 03:01:02.416  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 03:01:02.416  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 03:01:02.416  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.416  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.413  4404  4404 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[31979]" dev="sockfs" ino=31979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 03:01:02.417  5466  5515 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 03:01:02.413  4404  4404 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[31979]" dev="sockfs" ino=31979 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 03:01:02.416  4609  4609 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31981]" dev="sockfs" ino=31981 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 03:01:02.416  4609  4609 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31981]" dev="sockfs" ino=31981 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-22 03:01:02.417  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.417  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.417  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.417  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.417  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:02.417  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.417  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.417  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:02.417  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.417  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.417  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.417  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.417  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.418  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.418  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.418  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.418  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.418  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.418  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.418  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.419  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.419  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.419  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.419  4389  4451 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 03:01:02.419  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.419  4389  4454 D BtGatt.ScanManager: Starting BLE batch scan
09-22 03:01:02.419  4389  4454 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 03:01:02.419  5466  5512 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-22 03:01:02.419  5466  5512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-22 03:01:02.419  5466  5515 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-22 03:01:02.420  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-22 03:01:02.420  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-22 03:01:02.420  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.420  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.420  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.420  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.420  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.420  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.420  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.420  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.420  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.420  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.420  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.420  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.420  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.420  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.420  5466  5515 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-22 03:01:02.421  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.421  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.421  5466  5515 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-22 03:01:02.421  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.421  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.422  5466  5466 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-22 03:01:02.428  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.428  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.428  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.428  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.429  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.429  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.429  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.429  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.429  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.429  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.429  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.429  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.429  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.429  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.429  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.429  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.429  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.429  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.429  4389  4451 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 03:01:02.430  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.430  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:02.430  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:02.430  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:02.430  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:02.430  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.430  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.430  5466  5512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@79a925c not in the list
09-22 03:01:02.430  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.430  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.430  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:02.430  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.430  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.430  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:02.430  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:02.430  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:02.431  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:02.431  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:02.431  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4908965 not in the list
09-22 03:01:02.431  5466  5512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-22 03:01:02.431  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 03:01:02.431  5466  5512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-22 03:01:02.431  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-22 03:01:02.431  5466  5512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-22 03:01:02.431  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-22 03:01:02.432  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-22 03:01:02.432  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-22 03:01:02.432  5466  5512 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-22 03:01:02.432  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 03:01:02.432  5466  5512 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-22 03:01:02.432  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-22 03:01:02.432  5466  5512 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-22 03:01:02.432  5466  5512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-22 03:01:02.432  5466  5512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-22 03:01:02.432  5466  5512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-22 03:01:02.433  5466  5512 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-22 03:01:02.433  5466  5512 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-22 03:01:02.433  5466  5512 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-22 03:01:02.433  5466  5512 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-22 03:01:02.433  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:02.433  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b893bf added. We now have 2 listener(s)
09-22 03:01:02.433  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:02.434  4389  4451 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 03:01:02.434  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.435  5466  5512 D BluetoothAdapter: enable(): BT is already enabled..!
09-22 03:01:02.436   931   942 D WifiService: setWifiEnabled: true pid=5466, uid=10077
09-22 03:01:02.436   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 03:01:02.437  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:02.437  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7554a8c added. We now have 3 listener(s)
09-22 03:01:02.437  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:02.439  4389  4451 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 03:01:02.439  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.439  4389  4454 D BtGatt.ScanManager: stopping BLe Batch
09-22 03:01:02.440  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:02.440  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4f95d5 added. We now have 4 listener(s)
09-22 03:01:02.440  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:02.440  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:02.441  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@947e1ea added. We now have 5 listener(s)
09-22 03:01:02.441  5466 , 5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:02.441   931  3526 D WifiService: setWifiEnabled: false pid=5466, uid=10077
09-22 03:01:02.441   931  3526 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-22 03:01:02.443   931  2936 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-22 03:01:02.443   931  2936 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-22 03:01:02.443   931  2936 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 03:01:02.443   931  2936 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-22 03:01:02.444  4389  4451 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 03:01:02.444  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.444  4389  4454 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 03:01:02.448  4389  4447 D BluetoothAdapterState: Current state: ON, message: 23
09-22 03:01:02.448  4389  4451 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 03:01:02.448  4389  4447 D BluetoothAdapterProperties: Setting state to 13
09-22 03:01:02.448  4389  4451 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:02.448  4389  4447 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 03:01:02.448  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:02.449  4389  4447 D BluetoothAdapterProperties: onBluetoothDisable()
09-22 03:01:02.450  4389  4447 I BluetoothAdapterState: Entering PendingCommandState
09-22 03:01:02.452  4389  4389 D BluetoothMapService: onReceive
09-22 03:01:02.452  4389  4389 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 03:01:02.452  4389  4389 D BluetoothMapService: STATE_TURNING_OFF
09-22 03:01:02.452  4389  4389 D BluetoothMapService: MAP Service closeService in
09-22 03:01:02.452  4389  4389 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 03:01:02.452  4389  4389 D ObexServerSockets0: shutdown(block = true)
09-22 03:01:02.452   931  5205 D DhcpClient: Clearing IP address
09-22 03:01:02.452  4389  4389 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 03:01:02.453  4389  4389 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 03:01:02.453  4389  4599 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 03:01:02.453  4389  4612 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 03:01:02.453  4389  4611 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-22 03:01:02.454  4389  4389 I BtOppRfcommListener: stopping Accept Thread
09-22 03:01:02.454  4389  5133 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-22 03:01:02.454  4389  5133 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 03:01:02.454  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:02.454  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:01:02.454   509   925 D CommandListener: Clearing all IP addresses on wlan0
09-22 03:01:02.455  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.455  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.455  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:02.458  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.458   509   925 D CommandListener: Setting iface cfg
09-22 03:01:02.464  3594  5264 V NativeCrypto: Read error: ssl=0x7f95565380: I/O error during system call, Connection timed out
09-22 03:01:02.464  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.467  3594  5264 V NativeCrypto: SSL shutdown failed: ssl=0x7f95565380: I/O error during system call, Broken pipe
09-22 03:01:02.468   931  5206 D DhcpClient: Receive thread stopped
09-22 03:01:02.470  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.470   931  3148 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:02.470  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:01:02.471   931  5203 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-22 03:01:02.471  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.471  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-22 03:01:02.473   931  5203 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-22 03:01:02.474   931  2938 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-22 03:01:02.474   931   944 I ActivityManager: Start proc 5518:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-22 03:01:02.474   931  2938 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-22 03:01:02.475  4389  4451 D BluetoothAdapterProperties: Scan Mode:20
09-22 03:01:02.475  4389  4447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 03:01:02.476   931  2938 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-22 03:01:02.478  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-22 03:01:02.478  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:01:02.479   931  2938 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-22 03:01:02.479   535   535 E Parcel  : Reading a NULL string not supported here.
09-22 03:01:02.479   931  2938 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-22 03:01:02.480  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.480  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:02.482  4389  4389 D HeadsetService: Received stop request...Stopping profile...
09-22 03:01:02.483   931  2938 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-22 03:01:02.484  3479  3682 W QCNEJ   : |CORE| network lost: 100
09-22 03:01:02.484  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:02.484  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-22 03:01:02.485  3479  3682 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-22 03:01:02.485  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.485  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:02.486   931   931 D RttService: SCAN_AVAILABLE : 1
09-22 03:01:02.486   931   931 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:02.486   931   931 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:02.487  3118  3130 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:02.487   931  3045 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-22 03:01:02.487  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.488  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:02.487   931   931 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:02.488  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:02.488  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.488  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.488  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:02.488  3516  3869 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:02.489  4389  4389 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 03:01:02.490  4389  4389 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 03:01:02.490  4389  4451 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 03:01:02.490  4389  4585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:02.490  4389  4585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:02.490  4389  4585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:02.490  4389  4451 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-22 03:01:02.491  4389  4389 D A2dpService: Received stop request...Stopping profile...
09-22 03:01:02.492  4389  4604 D A2dpStateMachine: Exit Disconnected: -1
09-22 03:01:02.493   931   931 D BluetoothA2dp: Proxy object disconnected
09-22 03:01:02.495  4389  4389 D HidService: Received stop request...Stopping profile...
,09-22 03:01:02.495  3118  3118 D HeadsetProfile: Bluetooth service disconnected
,09-22 03:01:02.495  4389  4389 D HidService: Stopping Bluetooth HidService
09-22 03:01:02.496  3118  3118 D BluetoothA2dp: Proxy object disconnected
09-22 03:01:02.498  4389  4389 D HealthService: Received stop request...Stopping profile...
09-22 03:01:02.499  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:02.499  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.499  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.499  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:02.500  4389  4389 D PanService: Received stop request...Stopping profile...
09-22 03:01:02.502  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:02.502  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.502  4389  4585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:02.502  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.502  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:02.502  4389  4585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:02.502  4389  4451 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-22 03:01:02.502  4389  4585 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 03:01:02.502  4389  4585 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 03:01:02.502  4389  4389 D BluetoothMapService: Received stop request...Stopping profile...
09-22 03:01:02.502  4389  4585 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 03:01:02.502  4389  4389 D BluetoothMapService: stop()
09-22 03:01:02.502  4389  4585 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 03:01:02.502  4389  4389 D BluetoothMapAppObserver: deinitObservers()
09-22 03:01:02.502  4389  4389 D BluetoothMapAppObserver: removeReceiver()
09-22 03:01:02.503  4389  4389 D SapService: Received stop request...Stopping profile...
09-22 03:01:02.503  4389  4389 V SapService: stop()
09-22 03:01:02.504   931  2936 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-22 03:01:02.507  4389  4389 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-22 03:01:02.507  4389  4389 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 03:01:02.507  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:02.507  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.507  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.507  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:02.507  4389  4389 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 03:01:02.507  4389  4389 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-22 03:01:02.507  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:02.507  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.508  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.508  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:02.508  4389  4451 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 03:01:02.508  4389  4389 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-22 03:01:02.508  4389  4389 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-22 03:01:02.508  4389  4451 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 03:01:02.508  4389  4389 D BluetoothMapService: MAP Service closeService in
09-22 03:01:02.508  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:02.508  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.508  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.509  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:02.509  4389  4389 D BluetoothMapService: cleanup()
09-22 03:01:02.509  4389  4389 D BluetoothMapService: MAP Service closeService in
09-22 03:01:02.509  4389  4389 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:02.509  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.509  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.509  4389  4389 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:02.509  4389  4447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 03:01:02.509  4389  4447 D BluetoothAdapterProperties: Setting state to 15
09-22 03:01:02.509  4389  4447 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 03:01:02.509  4389  4447 I BluetoothAdapterState: Entering BleOnState
09-22 03:01:02.510   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 03:01:02.511  3118  3130 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 03:01:02.511  3118  3118 D BluetoothInputDevice: Proxy object disconnected
09-22 03:01:02.511  3118  3118 D HidProfile: Bluetooth service disconnected
09-22 03:01:02.511  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 03:01:02.511  3118  3118 D PanProfile: Bluetooth service disconnected
09-22 03:01:02.511  3118  3118 D BluetoothMap: Proxy object disconnected
09-22 03:01:02.511  3118  3118 D MapProfile: Bluetooth service disconnected
09-22 03:01:02.512  3118  3132 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 03:01:02.512   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 03:01:02.512   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 03:01:02.513  3118  3730 D BluetoothPan: onBluetoothStateChange on: false
09-22 03:01:02.514   931  2936 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-22 03:01:02.515  3118  3130 D BluetoothMap: onBluetoothStateChange: up=false
09-22 03:01:02.516   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 03:01:02.517  3118  3727 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-22 03:01:02.520  3516  3535 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 03:01:02.521  3118  3132 D BluetoothPbap: onBluetoothStateChange: up=false
,09-22 03:01:02.521   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-22 03:01:02.522  4389  4447 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 03:01:02.522  4389  4447 D BluetoothAdapterProperties: Setting state to 16
09-22 03:01:02.522  4389  4447 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 03:01:02.523  4389  4447 D BluetoothAdapterProperties: onBleDisable
09-22 03:01:02.523  4389  4447 I BluetoothAdapterState: Entering PendingCommandState
09-22 03:01:02.523  4389  4448 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 03:01:02.524  4389  4585 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 03:01:02.524  4389  4451 D BluetoothAdapterProperties: Scan Mode:20
09-22 03:01:02.524  4389  4585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:02.524  5466  5513 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-22 03:01:02.525  5518  5518 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-22 03:01:02.526  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:02.526  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:02.527  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:02.529  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.531  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:02.543  5518  5518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 03:01:02.548   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c1d8c5:true
,09-22 03:01:02.549   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-22 03:01:02.549  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 03:01:02.550   931  2938 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-22 03:01:02.551   931  2938 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-22 03:01:02.551   509   925 D CommandListener: Clearing all IP addresses on wlan0
09-22 03:01:02.552   509   925 D TetherController: Setting IP forward enable = 0
,09-22 03:01:02.563   931   942 I ActivityManager: Start proc 5541:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-22 03:01:02.564   931  2936 D DhcpClient: doQuit
,09-22 03:01:02.564   931  2936 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-22 03:01:02.565   931  5205 D DhcpClient: onQuitting
,09-22 03:01:02.565  3611  3611 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-22 03:01:02.569   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-22 03:01:02.576  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:02.576  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:02.577  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.577  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:02.579  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:02.579  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:02.579  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:02.579  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:02.581  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:02.581  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:02.582  4820  4833 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-22 03:01:02.582  4820  4833 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-22 03:01:02.582  4820  4833 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-22 03:01:02.582  4820  4833 E SarControlService: no key has been found,reset the power
09-22 03:01:02.582  4820  4858 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-22 03:01:02.582  4820  4858 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-22 03:01:02.582  4820  4858 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-22 03:01:02.583  4846  4846 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-22 03:01:02.583  4846  4846 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-22 03:01:02.584  4820  4858 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-22 03:01:02.584  4820  4858 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-22 03:01:02.584  4820  4858 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-22 03:01:02.586  4846  4846 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-22 03:01:02.586  4846  4846 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-22 03:01:02.589  4846  4860 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a4098f6 HexData = [00000000ea03000000000000ffffffff]
09-22 03:01:02.589  4846  4860 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 03:01:02.589  4846  4860 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-22 03:01:02.589  4846  4846 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 03:01:02.589  4820  4832 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-22 03:01:02.598  4846  4860 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@a4098f6 HexData = [00000000eb03000000000000ffffffff]
09-22 03:01:02.598  4846  4860 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-22 03:01:02.598  4846  4860 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-22 03:01:02.599  4846  4846 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-22 03:01:02.599  4820  4831 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-22 03:01:02.600  3611  3611 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 03:01:02.598  5518  5518 D LocalBluetoothProfileManager: Adding local MAP profile
,09-22 03:01:02.605  3611  3611 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-22 03:01:02.606  5518  5518 D BluetoothMap: Create BluetoothMap proxy object
,09-22 03:01:02.620  5541  5541 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-22 03:01:02.621  5518  5518 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-22 03:01:02.629   509   925 E Netd    : netlink response contains error (No such file or directory)
,09-22 03:01:02.630   931  2938 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-22 03:01:02.632   509   925 D TetherController: Setting IP forward enable = 0
09-22 03:01:02.632  3611  3611 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 03:01:02.641  5518  5518 D DockEventReceiver: finishStartingService: stopping service
,09-22 03:01:02.644   931  3565 I ActivityManager: Killing 5251:com.android.chrome/u0a39 (adj 15): empty #17
,09-22 03:01:02.646  3611  3611 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 03:01:02.731  4389  4451 I bt_hci  : shut_down
,09-22 03:01:02.733  4389  4455 D bt_hwcfg: hw_epilog_process
,09-22 03:01:02.734  4389  4455 I bt_vendor: low_power_mode_cb
,09-22 03:01:02.737  4389  4455 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-22 03:01:02.737  4389  4455 I bt_vendor: epilog_cb
09-22 03:01:02.737  4389  4455 I bt_hci  : epilog_finished_callback
,09-22 03:01:02.739  4389  4451 I bt_hci_h4: hal_close
,09-22 03:01:02.740  4389  4451 I bt_userial_vendor: device fd = 54 close
,09-22 03:01:02.750  4264  4264 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 03:01:02.750   931  2936 D wifi    : In wifi stop Hal
09-22 03:01:02.750   931  2936 D wifi    : halHandle = 0x7f94fbc2c0, mVM = 0x7fb070d140, mCls = 0x100b0e
09-22 03:01:02.750   931  3606 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-22 03:01:02.750   931  3606 D WifiHAL : Got a signal to exit!!!
09-22 03:01:02.750   931  3606 I WifiHAL : Exit wifi_event_loop
09-22 03:01:02.751   931  2936 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-22 03:01:02.751   931  2936 E WifiHAL : Event processing terminated
,09-22 03:01:02.751   931  2936 D wifi    : In wifi cleaned up handler
09-22 03:01:02.751   931  2936 I WifiHAL : Internal cleanup completed
09-22 03:01:02.752  3450  4013 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 03:01:02.754  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:02.755  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:02.775   931  3606 D wifi    : set interface wlan0 flags (DOWN)
,09-22 03:01:02.776   931  2936 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.k.d(PG:583)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.e.b(PG:170)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.File.exists(File.java:361)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.825  5541  5541 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:02.825  5541  5541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:02.830  5518  5518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 03:01:02.835  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 03:01:02.837  5518  5518 D DockEventReceiver: finishStartingService: stopping service
09-22 03:01:02.840   931  3560 I ActivityManager: Killing 4758:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-22 03:01:02.884   931  3560 I ActivityManager: Start proc 5581:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-22 03:01:02.892  4389  4448 D bt_stack_manager: event_shut_down_stack finished.
09-22 03:01:02.893  4389  4447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-22 03:01:02.895  4389  4447 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-22 03:01:02.895  4389  4389 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 03:01:02.896  4389  4389 D BtGatt.GattService: Received stop request...Stopping profile...
09-22 03:01:02.896  4389  4389 D BtGatt.GattService: stop()
09-22 03:01:02.896  4389  4389 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 03:01:02.898  4389  4389 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:02.898  4389  4389 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:02.898  4389  4389 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:02.898  4389  4389 V BluetoothAdapterState: isBleTurningOff()=true
09-22 03:01:02.898  4389  4447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 03:01:02.898  4389  4447 D BluetoothAdapterProperties: Setting state to 10
09-22 03:01:02.898  4389  4447 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-22 03:01:02.898  4389  4447 I BluetoothAdapterState: Entering OffState
09-22 03:01:02.900   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-22 03:01:02.908  4389  4389 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-22 03:01:02.908  4389  4389 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-22 03:01:02.908  4389  4389 I BluetoothServiceJni: cleanupNative: return from cleanup
09-22 03:01:02.908  4389  4448 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 03:01:02.918  5466  5466 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 03:01:02.921  4389  4448 D bt_stack_manager: event_clean_up_stack finished.
,09-22 03:01:02.928  5581  5581 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-22 03:01:02.930  4389  4389 I art     : System.exit called, status: 0
,09-22 03:01:02.930  4389  4389 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 03:01:02.953   931  3409 I ActivityManager: Killing 5286:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-22 03:01:02.978   931   948 D Tethering: InitialState.processMessage what=4
,09-22 03:01:02.981   931  3148 I ActivityManager: Process com.android.bluetooth (pid 4389) has died
,09-22 03:01:02.982   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 03:01:02.986  3915  3915 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-22 03:01:02.989  3915  3915 D SystemUpdateService: onCreate
,09-22 03:01:02.992  3915  3915 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-22 03:01:02.998  3915  5596 I SystemUpdateService: active receiver: enabled
,09-22 03:01:02.999  3915  3915 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-22 03:01:03.001  3915  5236 I iu.UploadsManager: num queued entries: 0
09-22 03:01:03.001  3915  5236 I iu.UploadsManager: num updated entries: 0
09-22 03:01:03.002  3915  5236 I iu.SyncManager: NEXT; no task
,09-22 03:01:03.005  3915  3915 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-22 03:01:03.007  3915  3915 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-22 03:01:03.018  3915  5596 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-22 03:01:03.018   931  3592 I ActivityManager: Start proc 5598:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-22 03:01:03.027  3915  5596 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-22 03:01:03.037  3915  5596 I SystemUpdateService: now status is 0 (complete)
09-22 03:01:03.037  3915  5596 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-22 03:01:03.037  3915  5596 I SystemUpdateService: file has been verified
,09-22 03:01:03.037  3915  5596 I SystemUpdateService: OTA package size = 21989297
,09-22 03:01:03.050  5598  5598 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-22 03:01:03.055  5598  5598 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-22 03:01:03.067  5598  5598 D SprintDMHelper: simOperator: 
,09-22 03:01:03.067  5598  5598 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-22 03:01:03.068  3915  5596 I SystemUpdateService: showing system update notification
,09-22 03:01:03.079   931  3409 I ActivityManager: Start proc 5610:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-22 03:01:03.138  3915  3915 D SystemUpdateService: onDestroy
,09-22 03:01:03.139   931  3537 I ActivityManager: Killing 5270:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-22 03:01:03.184   931  3392 I ActivityManager: Start proc 5625:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-22 03:01:03.184  4264  5624 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-22 03:01:03.186   931  3537 I ActivityManager: Killing 4461:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-22 03:01:03.229  5625  5625 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-22 03:01:03.388  5541  5571 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-22 03:01:03.415   931  3148 I ActivityManager: Killing 5328:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-22 03:01:03.434   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@981cf9c:true
,09-22 03:01:05.457   931   942 D WifiService: setWifiEnabled: true pid=5466, uid=10077
,09-22 03:01:05.457   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 03:01:05.465   509   925 D SoftapController: Softap fwReload - Ok
,09-22 03:01:05.469   509   925 D CommandListener: Setting iface cfg
,09-22 03:01:05.469   509   925 D CommandListener: Trying to bring down wlan0
,09-22 03:01:05.471   509   925 D CommandListener: Clearing all IP addresses on wlan0
,09-22 03:01:05.476   931  2936 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 03:01:06.079   931  2936 D wifi    : set interface wlan0 flags (UP)
,09-22 03:01:06.082   931  2936 I WifiHAL : Initializing wifi
09-22 03:01:06.082   931  2936 I WifiHAL : Creating socket
,09-22 03:01:06.086   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-22 03:01:06.095   931  2936 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 03:01:06.095   931  2936 D wifi    : Did set static halHandle = 0x7f94fbc2c0
09-22 03:01:06.095   931  2936 D wifi    : halHandle = 0x7f94fbc2c0, mVM = 0x7fb070d140, mCls = 0x101702
09-22 03:01:06.095   931  2936 D wifi    : array field set
09-22 03:01:06.096   931  2936 I WifiNative-HAL: interface[0] = wlan0
09-22 03:01:06.099   931  5646 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547960373952
09-22 03:01:06.099   931  5646 D wifi    : waitForHalEvents called, vm = 0x7fb070d140, obj = 0x101702, env = 0x7f99b7ac80
,09-22 03:01:06.179  5647  5647 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 03:01:06.203  5647  5647 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 03:01:06.204   931  2936 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-22 03:01:06.208  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:06.211  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:06.233  5647  5647 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 03:01:06.233  5647  5647 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 03:01:06.248  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:06.248  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:06.248  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:06.248   931  2936 D WifiConfigStore: Loading config and enabling all networks 
09-22 03:01:06.248  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:06.250  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:06.250  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:06.250  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:06.250  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:06.260   931  2936 D WifiConfigStore: loaded 0 passpoint configs
,09-22 03:01:06.260   931  2936 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 03:01:06.260   931  2936 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-22 03:01:06.261   931  2936 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-22 03:01:06.262   931  2936 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-22 03:01:06.262   931  2936 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 03:01:06.262   931  2936 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 03:01:06.262   931  2936 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 03:01:06.266   931  2936 D WifiNative-HAL: Setting external_sim to 1
,09-22 03:01:06.266  4264  4264 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 03:01:06.266   931  2936 D wifi    : setting dfs flag to true, 0x7f959fe4a0
09-22 03:01:06.267   931  2936 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 03:01:06.267   931  2936 D wifi    : setting scan oui 0x7f959fe4a0
09-22 03:01:06.267   931  2936 D WifiHAL : Sending mac address OUI
,09-22 03:01:06.271   931  2936 E native  : do suspend false
,09-22 03:01:06.278   931  2936 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-22 03:01:06.278   931   931 D RttService: SCAN_AVAILABLE : 3
09-22 03:01:06.278   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 03:01:06.279   931  3045 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-22 03:01:06.279   509   925 D CommandListener: Setting iface cfg
,09-22 03:01:06.284   931  2935 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-22 03:01:06.284   931  2935 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 03:01:06.296   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=183595 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-22 03:01:06.297   931  2935 D WifiNative-HAL: p2pGetDeviceAddress
09-22 03:01:06.297   931  2935 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 03:01:08.463   931  3526 D WifiService: setWifiEnabled: false pid=5466, uid=10077
,09-22 03:01:08.464   931  3526 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 03:01:08.469   931   931 D RttService: SCAN_AVAILABLE : 1
,09-22 03:01:08.470   931  3045 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 03:01:08.486   931  2936 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-22 03:01:08.489   509   925 D CommandListener: Clearing all IP addresses on wlan0
,09-22 03:01:08.498   931  2936 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 03:01:08.499  5647  5647 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-22 03:01:08.507  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:08.507  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:08.507  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:08.507  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:08.509  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:08.510  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:08.510  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:08.510  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:08.511  5647  5647 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-22 03:01:08.519  5647  5647 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-22 03:01:08.521  5647  5647 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-22 03:01:08.626   931  2936 D wifi    : In wifi stop Hal
,09-22 03:01:08.629   931  2936 D wifi    : halHandle = 0x7f94fbc2c0, mVM = 0x7fb070d140, mCls = 0x101702
,09-22 03:01:08.629   931  5646 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-22 03:01:08.629   931  5646 D WifiHAL : Got a signal to exit!!!
09-22 03:01:08.630   931  5646 I WifiHAL : Exit wifi_event_loop
,09-22 03:01:08.632   931  2936 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-22 03:01:08.633   931  2936 E WifiHAL : Event processing terminated
09-22 03:01:08.633  3450  4013 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 03:01:08.634  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:08.626  4264  4264 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-22 03:01:08.633   931  2936 D wifi    : In wifi cleaned up handler
09-22 03:01:08.638   931  2936 I WifiHAL : Internal cleanup completed
09-22 03:01:08.638  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:08.653   931  5646 D wifi    : set interface wlan0 flags (DOWN)
,09-22 03:01:08.654   931  2936 D WifiNative-HAL: HAL event thread stopped successfully
,09-22 03:01:08.856   931   948 D Tethering: InitialState.processMessage what=4
,09-22 03:01:08.859   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-22 03:01:11.508   931   948 I ActivityManager: Start proc 5651:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 03:01:11.602  5651  5651 D AdapterServiceConfig: Adding HeadsetService
,09-22 03:01:11.603  5651  5651 D AdapterServiceConfig: Adding A2dpService
09-22 03:01:11.603  5651  5651 D AdapterServiceConfig: Adding HidService
09-22 03:01:11.603  5651  5651 D AdapterServiceConfig: Adding HealthService
09-22 03:01:11.603  5651  5651 D AdapterServiceConfig: Adding PanService
,09-22 03:01:11.604  5651  5651 D AdapterServiceConfig: Adding GattService
,09-22 03:01:11.604  5651  5651 D AdapterServiceConfig: Adding BluetoothMapService
09-22 03:01:11.604  5651  5651 D AdapterServiceConfig: Adding SapService
,09-22 03:01:11.617   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@47ed12a:true
,09-22 03:01:11.618  5651  5651 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 03:01:11.620  5651  5651 I bt_bluedroid: init
,09-22 03:01:11.620  5651  5663 I BluetoothAdapterState: Entering OffState
,09-22 03:01:11.622  5651  5664 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-22 03:01:11.622  5651  5664 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 03:01:11.622  5651  5664 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 03:01:11.623  5651  5664 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 03:01:11.623  5651  5651 I bt_bluedroid: get_profile_interface socket
,09-22 03:01:11.625  5651  5651 I bt_bluedroid: get_profile_interface sdp
09-22 03:01:11.625  5651  5667 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 03:01:11.627  5651  5667 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 03:01:11.630  5651  5662 I bt_bluedroid: config_hci_snoop_log
,09-22 03:01:11.631   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-22 03:01:11.635  5651  5663 D BluetoothAdapterState: Current state: OFF, message: 0
09-22 03:01:11.635  5651  5663 D BluetoothAdapterProperties: Setting state to 14
09-22 03:01:11.635  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-22 03:01:11.637  5651  5663 D BluetoothBondStateMachine: make
,09-22 03:01:11.639  5651  5668 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 03:01:11.642  5651  5663 I BluetoothAdapterState: Entering PendingCommandState
,09-22 03:01:11.642  5651  5651 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-22 03:01:11.645  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:11.645  5651  5651 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 03:01:11.646  5651  5651 D BtGatt.GattService: Received start request. Starting profile...
09-22 03:01:11.646  5651  5651 D BtGatt.GattService: start()
09-22 03:01:11.646  5651  5651 I bt_bluedroid: get_profile_interface gatt
09-22 03:01:11.647  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
09-22 03:01:11.647  5651  5651 D BtGatt.AdvertiseManager: advertise manager created
,09-22 03:01:11.652  5651  5651 V BluetoothAdapterState: isTurningOff()=false
,09-22 03:01:11.652  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:11.652  5651  5651 V BluetoothAdapterState: isBleTurningOn()=true
09-22 03:01:11.652  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:11.652  5651  5663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 03:01:11.653  5651  5663 I bt_bluedroid: bt_bluedroid
09-22 03:01:11.653  5651  5664 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-22 03:01:11.654  5651  5664 I bt_hci  : start_up
,09-22 03:01:11.659  5651  5664 I bt_vendor: alloc value 0xf3bef871
09-22 03:01:11.659  5651  5664 I bt_vendor: init
09-22 03:01:11.659  5651  5664 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 03:01:11.659  5651  5664 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 03:01:11.769  5651  5664 D bt_hci  : start_up starting async portion
,09-22 03:01:11.769  5651  5671 I bt_hci  : event_finish_startup
09-22 03:01:11.770  5651  5671 I bt_hci_h4: hal_open
09-22 03:01:11.770  5651  5671 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 03:01:11.772  5651  5671 I bt_userial_vendor: device fd = 54 open
,09-22 03:01:11.770  5672  5672 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 03:01:11.784  5651  5671 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 03:01:11.786  5651  5671 D bt_hwcfg: Chipset BCM4358A3
,09-22 03:01:11.787  5651  5671 D bt_hwcfg: Target name = [BCM4358A3]
09-22 03:01:11.787  5651  5671 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 03:01:12.189  5651  5671 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-22 03:01:12.189  5651  5671 D bt_hwcfg: Settlement delay -- 100 ms
09-22 03:01:12.190  5651  5671 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 03:01:12.324  5651  5671 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-22 03:01:12.324  5651  5671 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-22 03:01:12.326  5651  5671 I bt_hwcfg: vendor lib fwcfg completed
09-22 03:01:12.326  5651  5671 I bt_vendor: firmware callback
09-22 03:01:12.326  5651  5671 I bt_hci  : firmware_config_callback
,09-22 03:01:12.335  5651  5674 I bt_btu  : btu_task pending for preload complete event
,09-22 03:01:12.335  5651  5674 I bt_btu_task: Bluetooth chip preload is complete
09-22 03:01:12.335  5651  5674 I bt_btu  : btu_task received preload complete event
,09-22 03:01:12.343  5651  5674 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 03:01:12.343  5651  5674 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 03:01:12.343  5651  5674 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 03:01:12.343  5651  5674 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-22 03:01:12.343  5651  5674 I         : BTE_InitTraceLevels -- TRC_AVRC
09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_BTM
09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_PAN
09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_SDP
,09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 03:01:12.344  5651  5674 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-22 03:01:12.345  5651  5674 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 03:01:12.431  5651  5674 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b6d549
,09-22 03:01:12.432  5651  5674 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b6d549 
,09-22 03:01:12.449  5651  5667 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 03:01:12.451  5651  5667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 03:01:12.451  5651  5667 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-22 03:01:12.453  5651  5667 D BluetoothAdapterProperties: Name is: Nexus 6P
09-22 03:01:12.456  5651  5667 D BluetoothAdapterProperties: Scan Mode:20
09-22 03:01:12.456  5651  5667 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 03:01:12.457  5651  5667 D bt_hci  : do_postload posting postload work item
09-22 03:01:12.457  5651  5671 I bt_hci  : event_postload
,09-22 03:01:12.457  5651  5671 I bt_vendor: sco_config_cb
09-22 03:01:12.457  5651  5671 I bt_hci  : sco_config_callback postload finished.
,09-22 03:01:12.460  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:12.464  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:12.466  5651  5667 D bt_bte_conf: Device ID record 1 : primary
,09-22 03:01:12.466  5651  5667 D bt_bte_conf:   vendorId            = 000f
09-22 03:01:12.467  5651  5667 D bt_bte_conf:   vendorIdSource      = 0001
09-22 03:01:12.467  5651  5667 D bt_bte_conf:   product             = 1200
09-22 03:01:12.467  5651  5667 D bt_bte_conf:   version             = 1436
09-22 03:01:12.467  5651  5667 D bt_bte_conf:   clientExecutableURL = 
,09-22 03:01:12.467  5651  5667 D bt_bte_conf:   serviceDescription  = 
09-22 03:01:12.467  5651  5667 D bt_bte_conf:   documentationURL    = 
09-22 03:01:12.467  5651  5667 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 03:01:12.467  5651  5664 D bt_stack_manager: event_start_up_stack finished
09-22 03:01:12.468  5651  5671 I bt_vendor: low_power_mode_cb
09-22 03:01:12.468  5651  5663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 03:01:12.468  5651  5663 D BluetoothAdapterProperties: Setting state to 15
09-22 03:01:12.468  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 03:01:12.469  5651  5663 I BluetoothAdapterState: Entering BleOnState
,09-22 03:01:12.473  5651  5663 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-22 03:01:12.473  5651  5663 D BluetoothAdapterProperties: Setting state to 11
09-22 03:01:12.473  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-22 03:01:12.480  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:12.482  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:12.483  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:12.484  5651  5651 D HeadsetService: Received start request. Starting profile...
,09-22 03:01:12.486  5651  5651 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-22 03:01:12.487  5651  5651 D HeadsetStateMachine: make
,09-22 03:01:12.494  5651  5663 I BluetoothAdapterState: Entering PendingCommandState
,09-22 03:01:12.497  5651  5651 D HeadsetStateMachine: max_hf_connections = 1
,09-22 03:01:12.498  5651  5651 I bt_bluedroid: get_profile_interface handsfree
09-22 03:01:12.498  5651  5667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-22 03:01:12.498  5651  5667 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-22 03:01:12.502  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:12.503  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 03:01:12.503  5651  5651 D A2dpService: Received start request. Starting profile...
,09-22 03:01:12.503  5651  5651 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-22 03:01:12.504  5651  5651 I bt_bluedroid: get_profile_interface avrcp
,09-22 03:01:12.509  5651  5651 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 03:01:12.509  5651  5651 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 03:01:12.509  5651  5651 D A2dpStateMachine: make
,09-22 03:01:12.511  5651  5651 I bt_bluedroid: get_profile_interface a2dp
,09-22 03:01:12.512  5651  5667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-22 03:01:12.513  5651  5682 D A2dpStateMachine: Enter Disconnected: -2
09-22 03:01:12.513  5651  5651 I BluetoothHidServiceJni: classInitNative: succeeds
,09-22 03:01:12.514  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:12.515  5518  5518 D BluetoothInputDevice: Proxy object connected
,09-22 03:01:12.516  5651  5651 D HidService: Received start request. Starting profile...
09-22 03:01:12.516  5518  5518 D HidProfile: Bluetooth service connected
09-22 03:01:12.516  5651  5651 I bt_bluedroid: get_profile_interface hidhost
09-22 03:01:12.516  5651  5667 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b4e56d
09-22 03:01:12.516  5651  5651 D HidService: setHidService(): set to: null
09-22 03:01:12.516  5651  5667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 03:01:12.517  5651  5651 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-22 03:01:12.518  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:12.519  5651  5651 D HealthService: Received start request. Starting profile...
,09-22 03:01:12.520  5651  5651 I bt_bluedroid: get_profile_interface health
09-22 03:01:12.521  5651  5651 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-22 03:01:12.522  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
09-22 03:01:12.523  5518  5518 D BluetoothPan: BluetoothPAN Proxy object connected
,09-22 03:01:12.523  5651  5651 D PanService: Received start request. Starting profile...
09-22 03:01:12.523  5651  5651 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 03:01:12.523  5651  5651 I bt_bluedroid: get_profile_interface pan
09-22 03:01:12.524  5518  5518 D PanProfile: Bluetooth service connected
09-22 03:01:12.524  5651  5667 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-22 03:01:12.526  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:12.527  5651  5651 D BluetoothMapService: Received start request. Starting profile...
,09-22 03:01:12.527  5518  5518 D BluetoothMap: Proxy object connected
09-22 03:01:12.527  5651  5651 D BluetoothMapService: start()
09-22 03:01:12.528  5518  5518 D MapProfile: Bluetooth service connected
09-22 03:01:12.528  5518  5518 D BluetoothMap: getConnectedDevices()
09-22 03:01:12.528  5518  5518 D BluetoothMap: Bluetooth is Not enabled
,09-22 03:01:12.530  5651  5651 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 03:01:12.531  5651  5651 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 03:01:12.531  5651  5651 D BluetoothMapAppObserver: createReceiver()
09-22 03:01:12.532  5651  5651 D BluetoothMapAppObserver: initObservers()
09-22 03:01:12.532  5651  5651 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-22 03:01:12.538  5651  5651 V SapService: SapBinder()
09-22 03:01:12.538  5651  5651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:12.538  5651  5651 D SapService: Received start request. Starting profile...
,09-22 03:01:12.538  5651  5651 V SapService: start()
09-22 03:01:12.541  5651  5651 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:12.541  5651  5651 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:12.541  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:12.541  5651  5680 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 03:01:12.541  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isTurningOff()=false
,09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:12.542  5651  5651 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:12.543  5651  5651 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:12.544  5651  5651 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:12.544  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:12.544  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:12.544  5651  5663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 03:01:12.544  5651  5663 D BluetoothAdapterProperties: ScanMode =  20
09-22 03:01:12.544  5651  5663 D BluetoothAdapterProperties: State =  11
09-22 03:01:12.544  5651  5663 D BluetoothAdapterProperties: Setting state to 12
09-22 03:01:12.544  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-22 03:01:12.545   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:12.545  3118  3132 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 03:01:12.546  5651  5663 I BluetoothAdapterState: Entering OnState
09-22 03:01:12.546  5518  5530 D BluetoothPan: onBluetoothStateChange on: true
09-22 03:01:12.546  5518  5534 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 03:01:12.546  5651  5667 D BluetoothAdapterProperties: Scan Mode:21
09-22 03:01:12.547  5651  5667 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-22 03:01:12.548  3118  3130 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-22 03:01:12.549  3118  3118 D BluetoothInputDevice: Proxy object connected
09-22 03:01:12.549  3118  3118 D HidProfile: Bluetooth service connected
09-22 03:01:12.549  5518  5530 D BluetoothMap: onBluetoothStateChange: up=true
09-22 03:01:12.550   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:12.550   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:12.550  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:12.550  3118  3730 D BluetoothPan: onBluetoothStateChange on: true
09-22 03:01:12.552  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 03:01:12.552  3118  3118 D PanProfile: Bluetooth service connected
,09-22 03:01:12.552  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:12.552  3118  3130 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 03:01:12.554   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 03:01:12.555  3118  3118 D BluetoothMap: Proxy object connected
09-22 03:01:12.555  3118  3118 D MapProfile: Bluetooth service connected
09-22 03:01:12.555  3118  3118 D BluetoothMap: getConnectedDevices()
09-22 03:01:12.555  3118  3132 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 03:01:12.556   931   931 D BluetoothA2dp: Proxy object connected
,09-22 03:01:12.557  5651  5651 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:12.558  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:12.558  5651  5651 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-22 03:01:12.558  3118  3118 D BluetoothA2dp: Proxy object connected
09-22 03:01:12.558  5518  5534 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 03:01:12.559  5651  5651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:12.560  3516  3869 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:12.561  3118  3130 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 03:01:12.561  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:12.561  5651  5651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 03:01:12.563  5651  5651 D ObexServerSockets: Succeed to create listening sockets 
09-22 03:01:12.563  5651  5651 D ObexServerSockets0: startAccept()
,09-22 03:01:12.563  5651  5651 D ObexServerSockets0: prepareForNewConnect()
,09-22 03:01:12.564   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,09-22 03:01:12.565  5651  5651 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 03:01:12.565  5651  5651 D BluetoothSdpJni: SDP Create record success - handle: 0
09-22 03:01:12.566  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:12.566  5651  5688 D ObexServerSockets0: Accepting socket connection...
,09-22 03:01:12.566  5651  5651 D BluetoothMapService: onReceive
09-22 03:01:12.566  5651  5651 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 03:01:12.566  5651  5689 D ObexServerSockets0: Accepting socket connection...
09-22 03:01:12.566  5651  5651 D BluetoothMapService: STATE_ON
09-22 03:01:12.568  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:12.568  5518  5518 D LocalBluetoothProfileManager: Adding local A2DP profile
09-22 03:01:12.569  5651  5690 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-22 03:01:12.571  5651  5690 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-22 03:01:12.571  5651  5690 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 03:01:12.571  5518  5518 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-22 03:01:12.579  5518  5518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 03:01:12.580  5518  5518 D BluetoothA2dp: Proxy object connected
,09-22 03:01:12.585  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 03:01:12.586  5518  5518 D DockEventReceiver: finishStartingService: stopping service
,09-22 03:01:12.591  3118  3118 D BluetoothPbap: Proxy object connected
,09-22 03:01:12.591  3118  3118 D PbapServerProfile: Bluetooth service connected
09-22 03:01:12.591  5518  5518 D BluetoothPbap: Proxy object connected
09-22 03:01:12.592  5651  5651 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-22 03:01:12.592  5651  5651 D ObexServerSockets0: prepareForNewConnect()
09-22 03:01:12.592  5518  5518 D PbapServerProfile: Bluetooth service connected
,09-22 03:01:12.598  5651  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:12.611  5651  5698 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:12.612  5651  5698 I BtOppRfcommListener: Accept thread started.
,09-22 03:01:12.645   931   931 D BluetoothHeadset: Proxy object connected
,09-22 03:01:12.645   931   931 D BluetoothHeadset: Proxy object connected
09-22 03:01:12.646  3118  3727 D BluetoothHeadset: Proxy object connected
09-22 03:01:12.646  3118  3132 D BluetoothHeadset: Proxy object connected
09-22 03:01:12.646  3118  3118 D HeadsetProfile: Bluetooth service connected
09-22 03:01:12.646   931   931 D BluetoothHeadset: Proxy object connected
,09-22 03:01:12.646  3516  3535 D BluetoothHeadset: Proxy object connected
,09-22 03:01:12.648  3118  3118 D HeadsetProfile: Bluetooth service connected
,09-22 03:01:12.650   931   948 D BluetoothHeadset: Proxy object connected
09-22 03:01:12.650   931   948 D BluetoothHeadset: Proxy object connected
,09-22 03:01:12.661  3516  3542 D BluetoothHeadset: Proxy object connected
,09-22 03:01:12.676  5518  5530 D BluetoothHeadset: Proxy object connected
,09-22 03:01:12.679  5518  5518 D HeadsetProfile: Bluetooth service connected
,09-22 03:01:12.783   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 03:01:13.784   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 03:01:14.479  5651  5663 D BluetoothAdapterState: Current state: ON, message: 23
09-22 03:01:14.480  5651  5663 D BluetoothAdapterProperties: Setting state to 13
,09-22 03:01:14.480  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-22 03:01:14.481  5651  5663 D BluetoothAdapterProperties: onBluetoothDisable()
,09-22 03:01:14.483  5651  5663 I BluetoothAdapterState: Entering PendingCommandState
,09-22 03:01:14.486  5651  5651 D BluetoothMapService: onReceive
,09-22 03:01:14.487  5651  5651 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 03:01:14.487  5651  5651 D BluetoothMapService: STATE_TURNING_OFF
09-22 03:01:14.488  5651  5651 D BluetoothMapService: MAP Service closeService in
09-22 03:01:14.488  5651  5651 D BluetoothMapMasInstance0: MAP Service shutdown
09-22 03:01:14.488  5651  5651 D ObexServerSockets0: shutdown(block = true)
09-22 03:01:14.491  5651  5688 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-22 03:01:14.492  5651  5667 D BluetoothAdapterProperties: Scan Mode:20
09-22 03:01:14.492  5651  5663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-22 03:01:14.496  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:14.496  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:14.500  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:14.501  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:14.506  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:14.506  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:14.507  5466  5466 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-22 03:01:14.508  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:14.508  5518  5518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 03:01:14.492  5651  5651 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 03:01:14.511  5651  5651 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-22 03:01:14.511  5651  5676 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-22 03:01:14.512  5651  5689 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-22 03:01:14.512  5651  5651 I BtOppRfcommListener: stopping Accept Thread
09-22 03:01:14.513  5651  5698 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-22 03:01:14.513  5651  5698 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-22 03:01:14.515  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:14.515  5518  5518 D DockEventReceiver: finishStartingService: stopping service
09-22 03:01:14.516  5651  5651 D HeadsetService: Received stop request...Stopping profile...
09-22 03:01:14.517  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:14.521   931   931 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:14.521   931   931 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:14.521  3118  3730 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:14.522  3118  3118 D HeadsetProfile: Bluetooth service disconnected
09-22 03:01:14.522   931   931 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:14.522  5651  5651 D A2dpService: Received stop request...Stopping profile...
09-22 03:01:14.523  5651  5682 D A2dpStateMachine: Exit Disconnected: -1
09-22 03:01:14.523  5518  5530 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:14.524  3516  3535 D BluetoothHeadset: Proxy object disconnected
09-22 03:01:14.524   931   931 D BluetoothA2dp: Proxy object disconnected
09-22 03:01:14.524  5518  5518 D HeadsetProfile: Bluetooth service disconnected
09-22 03:01:14.525  3118  3118 D BluetoothA2dp: Proxy object disconnected
09-22 03:01:14.525  5518  5518 D BluetoothA2dp: Proxy object disconnected
09-22 03:01:14.525  5651  5651 D HidService: Received stop request...Stopping profile...
09-22 03:01:14.526  5651  5651 D HidService: Stopping Bluetooth HidService
,09-22 03:01:14.526  3118  3118 D BluetoothInputDevice: Proxy object disconnected
09-22 03:01:14.526  3118  3118 D HidProfile: Bluetooth service disconnected
09-22 03:01:14.527  5518  5518 D BluetoothInputDevice: Proxy object disconnected
09-22 03:01:14.527  5518  5518 D HidProfile: Bluetooth service disconnected
,09-22 03:01:14.528  5651  5651 D HealthService: Received stop request...Stopping profile...
09-22 03:01:14.529  5651  5651 D PanService: Received stop request...Stopping profile...
,09-22 03:01:14.530  3118  3118 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-22 03:01:14.530  3118  3118 D PanProfile: Bluetooth service disconnected
09-22 03:01:14.531  5651  5651 D BluetoothMapService: Received stop request...Stopping profile...
09-22 03:01:14.531  5651  5651 D BluetoothMapService: stop()
09-22 03:01:14.531  5518  5518 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-22 03:01:14.531  5518  5518 D PanProfile: Bluetooth service disconnected
09-22 03:01:14.531  5651  5651 D BluetoothMapAppObserver: deinitObservers()
09-22 03:01:14.532  5651  5651 D BluetoothMapAppObserver: removeReceiver()
09-22 03:01:14.533  3118  3118 D BluetoothMap: Proxy object disconnected
09-22 03:01:14.533  3118  3118 D MapProfile: Bluetooth service disconnected
,09-22 03:01:14.533  5651  5651 D SapService: Received stop request...Stopping profile...
09-22 03:01:14.534  5651  5651 V SapService: stop()
,09-22 03:01:14.534  5518  5518 D BluetoothMap: Proxy object disconnected
09-22 03:01:14.534  5518  5518 D MapProfile: Bluetooth service disconnected
,09-22 03:01:14.537  5651  5651 V BluetoothAdapterState: isTurningOff()=true
,09-22 03:01:14.537  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.537  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:14.537  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:14.538  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 03:01:14.540  5651  5651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-22 03:01:14.540  5651  5651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-22 03:01:14.540  5651  5674 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:14.540  5651  5674 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:14.540  5651  5667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-22 03:01:14.540  5651  5674 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:14.540  5651  5667 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-22 03:01:14.540  5651  5651 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:14.540  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.540  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:14.540  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:14.541  5651  5651 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:14.542  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.542  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:14.542  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:14.542  5651  5651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-22 03:01:14.542  5651  5651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-22 03:01:14.542  5651  5651 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:14.542  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.542  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:14.542  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:14.542  5651  5651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-22 03:01:14.543  5651  5667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 03:01:14.543  5651  5667 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-22 03:01:14.543  5651  5667 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-22 03:01:14.543  5651  5651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-22 03:01:14.543  5651  5674 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-22 03:01:14.543  5651  5674 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:14.544  5651  5674 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 03:01:14.544  5651  5674 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 03:01:14.544  5651  5651 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:14.544  5651  5674 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-22 03:01:14.544  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.544  5651  5674 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-22 03:01:14.544  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:14.544  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
,09-22 03:01:14.547  5651  5651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-22 03:01:14.547  5651  5651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-22 03:01:14.547  5651  5651 D BluetoothMapService: MAP Service closeService in
09-22 03:01:14.547  5651  5651 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:14.547  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.547  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:14.547  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:14.548  5651  5651 D BluetoothMapService: cleanup()
09-22 03:01:14.548  5651  5651 D BluetoothMapService: MAP Service closeService in
09-22 03:01:14.548  5651  5651 V BluetoothAdapterState: isTurningOff()=true
09-22 03:01:14.548  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.548  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:14.548  5651  5651 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:14.549  5651  5663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-22 03:01:14.549  5651  5663 D BluetoothAdapterProperties: Setting state to 15
09-22 03:01:14.549  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-22 03:01:14.549  3118  3118 D BluetoothPbap: Proxy object disconnected
09-22 03:01:14.549  3118  3118 D PbapServerProfile: Bluetooth service disconnected
09-22 03:01:14.549  5651  5663 I BluetoothAdapterState: Entering BleOnState
09-22 03:01:14.550   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 03:01:14.550  3118  3730 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 03:01:14.551  5518  5530 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-22 03:01:14.552  5518  5534 D BluetoothPan: onBluetoothStateChange on: false
09-22 03:01:14.552  5518  5530 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 03:01:14.555  3118  3130 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 03:01:14.555  5518  5534 D BluetoothMap: onBluetoothStateChange: up=false
09-22 03:01:14.555   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 03:01:14.556   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 03:01:14.556  5518  5530 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-22 03:01:14.556  5518  5518 D BluetoothPbap: Proxy object disconnected
09-22 03:01:14.556  5518  5518 D PbapServerProfile: Bluetooth service disconnected
,09-22 03:01:14.557  3118  3132 D BluetoothPan: onBluetoothStateChange on: false
09-22 03:01:14.557  3118  3727 D BluetoothMap: onBluetoothStateChange: up=false
09-22 03:01:14.558   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 03:01:14.558  3118  3730 D BluetoothA2dp: onBluetoothStateChange: up=false
09-22 03:01:14.558  5518  5534 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-22 03:01:14.559  3516  3542 D BluetoothHeadset: onBluetoothStateChange: up=false
09-22 03:01:14.559  3118  3130 D BluetoothPbap: onBluetoothStateChange: up=false
09-22 03:01:14.560  5651  5663 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-22 03:01:14.560  5651  5663 D BluetoothAdapterProperties: Setting state to 16
09-22 03:01:14.560  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-22 03:01:14.560  5651  5663 D BluetoothAdapterProperties: onBleDisable
,09-22 03:01:14.560  5651  5663 I BluetoothAdapterState: Entering PendingCommandState
09-22 03:01:14.560  5651  5664 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-22 03:01:14.562  5651  5667 D BluetoothAdapterProperties: Scan Mode:20
09-22 03:01:14.563  5518  5518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-22 03:01:14.564  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:14.565  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:14.566  5651  5674 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-22 03:01:14.566  5651  5674 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-22 03:01:14.567  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:14.569  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-22 03:01:14.569  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:14.569  5518  5518 D DockEventReceiver: finishStartingService: stopping service
,09-22 03:01:14.775  5651  5667 I bt_hci  : shut_down
,09-22 03:01:14.779  5651  5671 D bt_hwcfg: hw_epilog_process
,09-22 03:01:14.779  5651  5671 I bt_vendor: low_power_mode_cb
,09-22 03:01:14.781  5651  5671 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-22 03:01:14.781  5651  5671 I bt_vendor: epilog_cb
09-22 03:01:14.781  5651  5671 I bt_hci  : epilog_finished_callback
,09-22 03:01:14.783  5651  5667 I bt_hci_h4: hal_close
,09-22 03:01:14.784  5651  5667 I bt_userial_vendor: device fd = 54 close
,09-22 03:01:14.785   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 03:01:14.895  5651  5664 D bt_stack_manager: event_shut_down_stack finished.
,09-22 03:01:14.896  5651  5663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-22 03:01:14.900  5651  5663 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-22 03:01:14.901  5651  5651 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-22 03:01:14.902  5651  5651 D BtGatt.GattService: Received stop request...Stopping profile...
,09-22 03:01:14.902  5651  5651 D BtGatt.GattService: stop()
09-22 03:01:14.902  5651  5651 D BtGatt.AdvertiseManager: advertise clients cleared
09-22 03:01:14.906  5651  5651 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:14.906  5651  5651 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:14.906  5651  5651 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 03:01:14.906  5651  5651 V BluetoothAdapterState: isBleTurningOff()=true
09-22 03:01:14.906  5651  5663 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-22 03:01:14.907  5651  5663 D BluetoothAdapterProperties: Setting state to 10
09-22 03:01:14.907  5651  5663 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-22 03:01:14.908  5651  5663 I BluetoothAdapterState: Entering OffState
,09-22 03:01:14.910   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-22 03:01:14.925  5651  5651 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-22 03:01:14.925  5651  5651 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-22 03:01:14.926  5651  5651 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-22 03:01:14.929  5651  5664 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-22 03:01:14.937  5651  5651 I art     : System.exit called, status: 0
,09-22 03:01:14.938  5651  5651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-22 03:01:14.963   931  3409 I ActivityManager: Process com.android.bluetooth (pid 5651) has died
,09-22 03:01:15.786   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 03:01:16.786   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-22 03:01:17.482  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
,09-22 03:01:17.482  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 03:01:17.787   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-22 03:01:20.489  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 03:01:20.489  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a528378 added. We now have 6 listener(s)
,09-22 03:01:20.489  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 03:01:20.492  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:20.493  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba51 added. We now have 7 listener(s)
09-22 03:01:20.493  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 03:01:20.495  5466  5512 I System.out: IsBluetoothEnabled
,09-22 03:01:20.503  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:20.525   931   948 I ActivityManager: Start proc 5707:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-22 03:01:20.588  5707  5707 D AdapterServiceConfig: Adding HeadsetService
,09-22 03:01:20.588  5707  5707 D AdapterServiceConfig: Adding A2dpService
09-22 03:01:20.588  5707  5707 D AdapterServiceConfig: Adding HidService
09-22 03:01:20.588  5707  5707 D AdapterServiceConfig: Adding HealthService
09-22 03:01:20.589  5707  5707 D AdapterServiceConfig: Adding PanService
09-22 03:01:20.589  5707  5707 D AdapterServiceConfig: Adding GattService
09-22 03:01:20.589  5707  5707 D AdapterServiceConfig: Adding BluetoothMapService
09-22 03:01:20.589  5707  5707 D AdapterServiceConfig: Adding SapService
,09-22 03:01:20.598   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f9cadb:true
,09-22 03:01:20.599  5707  5707 D BluetoothAdapterState: make() - Creating AdapterState
,09-22 03:01:20.602  5707  5707 I bt_bluedroid: init
,09-22 03:01:20.602  5707  5719 I BluetoothAdapterState: Entering OffState
,09-22 03:01:20.604  5707  5720 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-22 03:01:20.604  5707  5720 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-22 03:01:20.604  5707  5720 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-22 03:01:20.604  5707  5720 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-22 03:01:20.604  5707  5707 I bt_bluedroid: get_profile_interface socket
,09-22 03:01:20.606  5707  5723 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-22 03:01:20.606  5707  5707 I bt_bluedroid: get_profile_interface sdp
,09-22 03:01:20.607  5707  5723 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 03:01:20.611  5707  5718 I bt_bluedroid: config_hci_snoop_log
,09-22 03:01:20.612   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-22 03:01:20.616  5707  5719 D BluetoothAdapterState: Current state: OFF, message: 0
,09-22 03:01:20.616  5707  5719 D BluetoothAdapterProperties: Setting state to 14
09-22 03:01:20.616  5707  5719 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-22 03:01:20.617  5707  5719 D BluetoothBondStateMachine: make
,09-22 03:01:20.619  5707  5724 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-22 03:01:20.621  5707  5719 I BluetoothAdapterState: Entering PendingCommandState
,09-22 03:01:20.622  5707  5707 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-22 03:01:20.624  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
09-22 03:01:20.624  5707  5707 D BtGatt.DebugUtils: handleDebugAction() action=null
09-22 03:01:20.625  5707  5707 D BtGatt.GattService: Received start request. Starting profile...
09-22 03:01:20.625  5707  5707 D BtGatt.GattService: start()
09-22 03:01:20.625  5707  5707 I bt_bluedroid: get_profile_interface gatt
,09-22 03:01:20.626  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:20.626  5707  5707 D BtGatt.AdvertiseManager: advertise manager created
,09-22 03:01:20.631  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:20.631  5707  5707 V BluetoothAdapterState: isTurningOn()=false
09-22 03:01:20.631  5707  5707 V BluetoothAdapterState: isBleTurningOn()=true
09-22 03:01:20.631  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:20.631  5707  5719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-22 03:01:20.632  5707  5719 I bt_bluedroid: bt_bluedroid
,09-22 03:01:20.632  5707  5720 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-22 03:01:20.633  5707  5720 I bt_hci  : start_up
,09-22 03:01:20.637  5707  5720 I bt_vendor: alloc value 0xf3bef871
,09-22 03:01:20.637  5707  5720 I bt_vendor: init
09-22 03:01:20.637  5707  5720 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-22 03:01:20.638  5707  5720 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-22 03:01:20.750  5707  5720 D bt_hci  : start_up starting async portion
,09-22 03:01:20.751  5707  5727 I bt_hci  : event_finish_startup
09-22 03:01:20.751  5707  5727 I bt_hci_h4: hal_open
,09-22 03:01:20.751  5707  5727 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-22 03:01:20.750  5728  5728 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-22 03:01:20.753  5707  5727 I bt_userial_vendor: device fd = 54 open
,09-22 03:01:20.767  5707  5727 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 03:01:20.770  5707  5727 D bt_hwcfg: Chipset BCM4358A3
,09-22 03:01:20.770  5707  5727 D bt_hwcfg: Target name = [BCM4358A3]
09-22 03:01:20.771  5707  5727 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-22 03:01:21.175  5707  5727 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-22 03:01:21.175  5707  5727 D bt_hwcfg: Settlement delay -- 100 ms
09-22 03:01:21.176  5707  5727 I bt_hwcfg: Setting fw settlement delay to 100 
,09-22 03:01:21.309  5707  5727 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-22 03:01:21.310  5707  5727 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-22 03:01:21.312  5707  5727 I bt_hwcfg: vendor lib fwcfg completed
,09-22 03:01:21.312  5707  5727 I bt_vendor: firmware callback
09-22 03:01:21.312  5707  5727 I bt_hci  : firmware_config_callback
,09-22 03:01:21.321  5707  5730 I bt_btu  : btu_task pending for preload complete event
,09-22 03:01:21.322  5707  5730 I bt_btu_task: Bluetooth chip preload is complete
09-22 03:01:21.322  5707  5730 I bt_btu  : btu_task received preload complete event
,09-22 03:01:21.329  5707  5730 I         : BTE_InitTraceLevels -- TRC_HCI
,09-22 03:01:21.329  5707  5730 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-22 03:01:21.329  5707  5730 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-22 03:01:21.329  5707  5730 I         : BTE_InitTraceLevels -- TRC_AVDT
09-22 03:01:21.330  5707  5730 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-22 03:01:21.330  5707  5730 I         : BTE_InitTraceLevels -- TRC_A2D
09-22 03:01:21.330  5707  5730 I         : BTE_InitTraceLevels -- TRC_BNEP
09-22 03:01:21.330  5707  5730 I         : BTE_InitTraceLevels -- TRC_BTM
,09-22 03:01:21.330  5707  5730 I         : BTE_InitTraceLevels -- TRC_GAP
09-22 03:01:21.330  5707  5730 I         : BTE_InitTraceLevels -- TRC_PAN
,09-22 03:01:21.331  5707  5730 I         : BTE_InitTraceLevels -- TRC_SDP
,09-22 03:01:21.331  5707  5730 I         : BTE_InitTraceLevels -- TRC_GATT
09-22 03:01:21.331  5707  5730 I         : BTE_InitTraceLevels -- TRC_SMP
09-22 03:01:21.331  5707  5730 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-22 03:01:21.331  5707  5730 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-22 03:01:21.413  5707  5730 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b6d549
,09-22 03:01:21.413  5707  5730 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b6d549 
,09-22 03:01:21.425  5707  5723 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-22 03:01:21.427  5707  5723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-22 03:01:21.427  5707  5723 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-22 03:01:21.429  5707  5723 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-22 03:01:21.432  5707  5723 D BluetoothAdapterProperties: Scan Mode:20
09-22 03:01:21.432  5707  5723 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 03:01:21.432  5707  5723 D bt_hci  : do_postload posting postload work item
09-22 03:01:21.433  5707  5727 I bt_hci  : event_postload
09-22 03:01:21.433  5707  5727 I bt_vendor: sco_config_cb
,09-22 03:01:21.433  5707  5727 I bt_hci  : sco_config_callback postload finished.
09-22 03:01:21.437  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:21.439  5707  5723 D bt_bte_conf: Device ID record 1 : primary
,09-22 03:01:21.439  5707  5723 D bt_bte_conf:   vendorId            = 000f
09-22 03:01:21.439  5707  5723 D bt_bte_conf:   vendorIdSource      = 0001
09-22 03:01:21.439  5707  5723 D bt_bte_conf:   product             = 1200
09-22 03:01:21.439  5707  5723 D bt_bte_conf:   version             = 1436
09-22 03:01:21.440  5707  5723 D bt_bte_conf:   clientExecutableURL = 
09-22 03:01:21.440  5707  5723 D bt_bte_conf:   serviceDescription  = 
09-22 03:01:21.440  5707  5723 D bt_bte_conf:   documentationURL    = 
09-22 03:01:21.440  5707  5723 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-22 03:01:21.440  5707  5720 D bt_stack_manager: event_start_up_stack finished
09-22 03:01:21.441  5707  5719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-22 03:01:21.441  5707  5719 D BluetoothAdapterProperties: Setting state to 15
09-22 03:01:21.441  5707  5719 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-22 03:01:21.442  5707  5727 I bt_vendor: low_power_mode_cb
09-22 03:01:21.443  5707  5719 I BluetoothAdapterState: Entering BleOnState
,09-22 03:01:21.449  5707  5719 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-22 03:01:21.449  5707  5719 D BluetoothAdapterProperties: Setting state to 11
,09-22 03:01:21.449  5707  5719 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-22 03:01:21.455  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:21.459  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:21.459  5707  5707 D HeadsetService: Received start request. Starting profile...
09-22 03:01:21.462  5707  5707 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-22 03:01:21.462  5707  5707 D HeadsetStateMachine: make
,09-22 03:01:21.468  5707  5719 I BluetoothAdapterState: Entering PendingCommandState
,09-22 03:01:21.472  5707  5707 D HeadsetStateMachine: max_hf_connections = 1
,09-22 03:01:21.473  5707  5707 I bt_bluedroid: get_profile_interface handsfree
09-22 03:01:21.473  5707  5723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-22 03:01:21.473  5707  5723 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-22 03:01:21.477  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:21.477  5707  5707 D A2dpService: Received start request. Starting profile...
09-22 03:01:21.478  5707  5707 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-22 03:01:21.478  5707  5707 I bt_bluedroid: get_profile_interface avrcp
,09-22 03:01:21.484  5707  5707 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-22 03:01:21.484  5707  5707 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-22 03:01:21.484  5707  5707 D A2dpStateMachine: make
09-22 03:01:21.485  5707  5707 I bt_bluedroid: get_profile_interface a2dp
,09-22 03:01:21.486  5707  5723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-22 03:01:21.487  5707  5738 D A2dpStateMachine: Enter Disconnected: -2
,09-22 03:01:21.488  5707  5707 I BluetoothHidServiceJni: classInitNative: succeeds
09-22 03:01:21.489  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
09-22 03:01:21.490  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 03:01:21.490  5707  5707 D HidService: Received start request. Starting profile...
,09-22 03:01:21.490  5707  5707 I bt_bluedroid: get_profile_interface hidhost
09-22 03:01:21.490  5707  5723 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b4e56d
09-22 03:01:21.491  5707  5707 D HidService: setHidService(): set to: null
09-22 03:01:21.491  5707  5723 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-22 03:01:21.491  5707  5707 I BluetoothHealthServiceJni: classInitNative: succeeds
09-22 03:01:21.492  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
09-22 03:01:21.492  5707  5707 D HealthService: Received start request. Starting profile...
,09-22 03:01:21.494  5707  5707 I bt_bluedroid: get_profile_interface health
,09-22 03:01:21.495  5707  5707 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-22 03:01:21.495  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:21.496  5707  5707 D PanService: Received start request. Starting profile...
,09-22 03:01:21.496  5707  5707 D BluetoothPanServiceJni: initializeNative(L110): pan
09-22 03:01:21.496  5707  5707 I bt_bluedroid: get_profile_interface pan
09-22 03:01:21.497  5707  5723 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-22 03:01:21.499  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:21.499  5707  5707 D BluetoothMapService: Received start request. Starting profile...
09-22 03:01:21.499  5707  5707 D BluetoothMapService: start()
,09-22 03:01:21.502  5707  5707 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-22 03:01:21.503  5707  5707 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-22 03:01:21.503  5707  5707 D BluetoothMapAppObserver: createReceiver()
09-22 03:01:21.505  5707  5707 D BluetoothMapAppObserver: initObservers()
09-22 03:01:21.505  5707  5707 D BluetoothMapAppObserver: getEnabledAccountItems()
09-22 03:01:21.510  5707  5707 V SapService: SapBinder()
09-22 03:01:21.511  5707  5707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
09-22 03:01:21.511  5707  5707 D SapService: Received start request. Starting profile...
09-22 03:01:21.511  5707  5707 V SapService: start()
,09-22 03:01:21.514  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:21.514  5707  5707 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:21.514  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 03:01:21.514  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:21.515  5707  5736 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:21.515  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isTurningOn()=true
,09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
09-22 03:01:21.516  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:21.517  5707  5707 V BluetoothAdapterState: isTurningOff()=false
09-22 03:01:21.517  5707  5707 V BluetoothAdapterState: isTurningOn()=true
09-22 03:01:21.517  5707  5707 V BluetoothAdapterState: isBleTurningOn()=false
,09-22 03:01:21.517  5707  5707 V BluetoothAdapterState: isBleTurningOff()=false
09-22 03:01:21.517  5707  5719 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-22 03:01:21.517  5707  5719 D BluetoothAdapterProperties: ScanMode =  20
09-22 03:01:21.517  5707  5719 D BluetoothAdapterProperties: State =  11
,09-22 03:01:21.518  5707  5719 D BluetoothAdapterProperties: Setting state to 12
09-22 03:01:21.518  5707  5719 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-22 03:01:21.518   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:21.519  3118  3730 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:21.519  5518  5702 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:21.520  5707  5719 I BluetoothAdapterState: Entering OnState
09-22 03:01:21.520  5518  5530 D BluetoothPan: onBluetoothStateChange on: true
09-22 03:01:21.520  5707  5723 D BluetoothAdapterProperties: Scan Mode:21
09-22 03:01:21.521  5707  5723 D BluetoothAdapterProperties: Discoverable Timeout:120
09-22 03:01:21.522  5518  5534 D BluetoothPbap: onBluetoothStateChange: up=true
,09-22 03:01:21.524  3118  3727 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-22 03:01:21.524  5518  5518 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 03:01:21.524  5518  5518 D PanProfile: Bluetooth service connected
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:21.524  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-22 03:01:21.526  3118  3118 D BluetoothInputDevice: Proxy object connected
09-22 03:01:21.526  3118  3118 D HidProfile: Bluetooth service connected
,09-22 03:01:21.529  5518  5702 D BluetoothMap: onBluetoothStateChange: up=true
,09-22 03:01:21.530  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:21.530  5707  5707 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-22 03:01:21.531  5707  5707 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-22 03:01:21.532  5707  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:21.534  5707  5707 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:21.535  5707  5707 D ObexServerSockets: Succeed to create listening sockets 
09-22 03:01:21.535  5707  5707 D ObexServerSockets0: startAccept()
09-22 03:01:21.535  5707  5707 D ObexServerSockets0: prepareForNewConnect()
09-22 03:01:21.535   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:21.535   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-22 03:01:21.536  5518  5530 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 03:01:21.537  5707  5707 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-22 03:01:21.537  5707  5707 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-22 03:01:21.538  3118  3132 D BluetoothPan: onBluetoothStateChange on: true
,09-22 03:01:21.538  5707  5743 D ObexServerSockets0: Accepting socket connection...
,09-22 03:01:21.538  5707  5744 D ObexServerSockets0: Accepting socket connection...
09-22 03:01:21.540  5518  5518 D BluetoothMap: Proxy object connected
09-22 03:01:21.540  5518  5518 D MapProfile: Bluetooth service connected
09-22 03:01:21.540  5518  5518 D BluetoothMap: getConnectedDevices()
09-22 03:01:21.540  3118  3118 D BluetoothPan: BluetoothPAN Proxy object connected
09-22 03:01:21.540  3118  3130 D BluetoothMap: onBluetoothStateChange: up=true
09-22 03:01:21.540  3118  3118 D PanProfile: Bluetooth service connected
09-22 03:01:21.541  5518  5518 D BluetoothA2dp: Proxy object connected
09-22 03:01:21.541   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-22 03:01:21.542  3118  3118 D BluetoothMap: Proxy object connected
09-22 03:01:21.542  3118  3118 D MapProfile: Bluetooth service connected
09-22 03:01:21.542  3118  3118 D BluetoothMap: getConnectedDevices()
09-22 03:01:21.542   931   931 D BluetoothA2dp: Proxy object connected
09-22 03:01:21.542  3118  3132 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-22 03:01:21.544  5518  5530 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-22 03:01:21.545  3118  3118 D BluetoothA2dp: Proxy object connected
,09-22 03:01:21.548  5518  5518 D BluetoothInputDevice: Proxy object connected
,09-22 03:01:21.548  5518  5518 D HidProfile: Bluetooth service connected
09-22 03:01:21.548  3516  3869 D BluetoothHeadset: onBluetoothStateChange: up=true
09-22 03:01:21.549  3118  3130 D BluetoothPbap: onBluetoothStateChange: up=true
09-22 03:01:21.551   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,09-22 03:01:21.552  5707  5707 D BluetoothMapService: onReceive
,09-22 03:01:21.552  5707  5707 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-22 03:01:21.552  5707  5707 D BluetoothMapService: STATE_ON
09-22 03:01:21.553  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:21.556  5707  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:21.558  5707  5748 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-22 03:01:21.558  5707  5748 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-22 03:01:21.559  5518  5518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-22 03:01:21.564  5518  5518 D DockEventReceiver: finishStartingService: stopping service
,09-22 03:01:21.565  3594  3594 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-22 03:01:21.573  3118  3118 D BluetoothPbap: Proxy object connected
,09-22 03:01:21.573  3118  3118 D PbapServerProfile: Bluetooth service connected
09-22 03:01:21.574  5518  5518 D BluetoothPbap: Proxy object connected
09-22 03:01:21.574  5518  5518 D PbapServerProfile: Bluetooth service connected
,09-22 03:01:21.578  5707  5707 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-22 03:01:21.579  5707  5707 D ObexServerSockets0: prepareForNewConnect()
09-22 03:01:21.583  5707  5752 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:21.594  5707  5756 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-22 03:01:21.595  5707  5756 I BtOppRfcommListener: Accept thread started.
,09-22 03:01:21.620   931   931 D BluetoothHeadset: Proxy object connected
,09-22 03:01:21.620   931   931 D BluetoothHeadset: Proxy object connected
09-22 03:01:21.620  3118  3130 D BluetoothHeadset: Proxy object connected
09-22 03:01:21.620  3118  3118 D HeadsetProfile: Bluetooth service connected
09-22 03:01:21.620   931   931 D BluetoothHeadset: Proxy object connected
,09-22 03:01:21.621  5518  5530 D BluetoothHeadset: Proxy object connected
,09-22 03:01:21.623  3516  3535 D BluetoothHeadset: Proxy object connected
09-22 03:01:21.624  5518  5518 D HeadsetProfile: Bluetooth service connected
,09-22 03:01:21.635   931   948 D BluetoothHeadset: Proxy object connected
,09-22 03:01:21.635   931   948 D BluetoothHeadset: Proxy object connected
,09-22 03:01:21.649  3516  3542 D BluetoothHeadset: Proxy object connected
,09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:22.521  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:22.526  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:22.528  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-22 03:01:22.529  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ba32b6 added. We now have 8 listener(s)
09-22 03:01:22.529  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 03:01:22.533   931  3148 D WifiService: setWifiEnabled: false pid=5466, uid=10077
,09-22 03:01:22.533   931  3148 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 03:01:22.540  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:22.541   931  3145 D WifiService: setWifiEnabled: true pid=5466, uid=10077
09-22 03:01:22.541   931  3145 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-22 03:01:22.546   509   925 D SoftapController: Softap fwReload - Ok
,09-22 03:01:22.552   509   925 D CommandListener: Setting iface cfg
,09-22 03:01:22.552   509   925 D CommandListener: Trying to bring down wlan0
,09-22 03:01:22.554   509   925 D CommandListener: Clearing all IP addresses on wlan0
,09-22 03:01:22.558   931  2936 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-22 03:01:23.166   931  2936 D wifi    : set interface wlan0 flags (UP)
,09-22 03:01:23.170   931  2936 I WifiHAL : Initializing wifi
09-22 03:01:23.170   931  2936 I WifiHAL : Creating socket
,09-22 03:01:23.176   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-22 03:01:23.176   931  2936 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-22 03:01:23.176   931  2936 D wifi    : Did set static halHandle = 0x7f94fbc2c0
09-22 03:01:23.176   931  2936 D wifi    : halHandle = 0x7f94fbc2c0, mVM = 0x7fb070d140, mCls = 0x20175e
,09-22 03:01:23.176   931  2936 D wifi    : array field set
,09-22 03:01:23.178   931  2936 I WifiNative-HAL: interface[0] = wlan0
09-22 03:01:23.180   931  5761 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547960373952
09-22 03:01:23.180   931  5761 D wifi    : waitForHalEvents called, vm = 0x7fb070d140, obj = 0x20175e, env = 0x7fa5ca3d80
09-22 03:01:23.185   931  2936 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-22 03:01:23.191  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:23.227  5762  5762 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-22 03:01:23.247  5762  5762 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 03:01:23.255  5762  5762 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-22 03:01:23.255  5762  5762 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-22 03:01:23.272   931  2936 D WifiConfigStore: Loading config and enabling all networks 
,09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:23.279  5466  5466 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:23.282  5466  5466 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:23.287   931  2936 D WifiConfigStore: loaded 0 passpoint configs
,09-22 03:01:23.287   931  2936 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-22 03:01:23.287   931  2936 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-22 03:01:23.288   931  2936 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-22 03:01:23.290   931  2936 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-22 03:01:23.290   931  2936 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-22 03:01:23.290   931  2936 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-22 03:01:23.290   931  2936 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-22 03:01:23.294   931  2936 D WifiNative-HAL: Setting external_sim to 1
,09-22 03:01:23.294  4264  4264 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-22 03:01:23.295   931  2936 D wifi    : setting dfs flag to true, 0x7f95315b60
09-22 03:01:23.295   931  2936 D WifiStateMachine: Setting OUI to DA-A1-19
09-22 03:01:23.295   931  2936 D wifi    : setting scan oui 0x7f95315b60
09-22 03:01:23.295   931  2936 D WifiHAL : Sending mac address OUI
,09-22 03:01:23.299   931  2936 E native  : do suspend false
,09-22 03:01:23.306   931  2936 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-22 03:01:23.306   931   931 D RttService: SCAN_AVAILABLE : 3
09-22 03:01:23.306   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-22 03:01:23.306   931  3045 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-22 03:01:23.308   509   925 D CommandListener: Setting iface cfg
,09-22 03:01:23.311   931  2935 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-22 03:01:23.312   931  2935 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-22 03:01:23.322   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=200622 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
09-22 03:01:23.324   931  2935 D WifiNative-HAL: p2pGetDeviceAddress
,09-22 03:01:23.325   931  2935 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:23.558  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:23.564  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:23.574  5466  5512 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-22 03:01:23.576  5466  5512 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-22 03:01:23.581  5466  5512 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2b528a3 Bundle[{}]
,09-22 03:01:23.583  5466  5512 I io.jxcore.node.LifeCycleMonitor: start: OK
09-22 03:01:23.583  5466  5512 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-22 03:01:23.585  5466  5512 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-22 03:01:23.586  5466  5512 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-22 03:01:23.587  5466  5512 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-22 03:01:23.589  5466  5512 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-22 03:01:23.596  5466  5512 I System.out: Running OutgoingSocketThread
,09-22 03:01:23.599  5466  5764 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 152)
,09-22 03:01:23.601  5466  5764 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49685
,09-22 03:01:23.601  5466  5764 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-22 03:01:24.600  5466  5512 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 153)
,09-22 03:01:24.600  5466  5512 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 153)
,09-22 03:01:24.607  5466  5512 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-22 03:01:24.609  5466  5512 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-22 03:01:24.609  5466  5512 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 159)
,09-22 03:01:24.615  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-22 03:01:24.616  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7f3bb7 added. We now have 2 listener(s)
09-22 03:01:24.619  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.619  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 03:01:24.620  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 03:01:24.620  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.620  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e85f24 added. We now have 9 listener(s)
09-22 03:01:24.620  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 03:01:24.622  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-22 03:01:24.627  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:24.632  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:24.635  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:24.635  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:24.635  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.635  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2ec442 added. We now have 3 listener(s)
09-22 03:01:24.638  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.638  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.638  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 03:01:24.638  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.638  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.639  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1dc53 added. We now have 10 listener(s)
09-22 03:01:24.640  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.640  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.641  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:24.641  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-22 03:01:24.641  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:24.641  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.641  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.641  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:24.641  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.642  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7f3bb7 removed from the list
09-22 03:01:24.642  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.642  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e85f24 removed from the list
,09-22 03:01:24.642  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:24.642  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 03:01:24.643  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 03:01:24.643  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.645  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.645  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.645  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.645  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e85f24 not in the list
09-22 03:01:24.645  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.645  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.646  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.646  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.646  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.646  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1dc53 removed from the list
,09-22 03:01:24.646  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.647  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.647  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.647  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.647  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2ec442 removed from the list
09-22 03:01:24.648  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.648  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8de4990 added. We now have 2 listener(s)
09-22 03:01:24.649  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.649  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-22 03:01:24.649  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.650  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.650  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66f6289 added. We now have 9 listener(s)
09-22 03:01:24.650  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.650  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 03:01:24.654  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:24.659  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:24.662  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-22 03:01:24.662  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:24.662  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.662  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@583eaaf added. We now have 3 listener(s)
09-22 03:01:24.664  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.664  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.664  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:24.664  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.664  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.664  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d066ebc added. We now have 10 listener(s)
,09-22 03:01:24.665  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.665  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 03:01:24.665  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 03:01:24.665  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 03:01:24.665  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:24.665  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 03:01:24.668  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:24.669  5466  5512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-22 03:01:24.669  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 03:01:24.673  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 03:01:24.673  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 03:01:24.674  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 03:01:24.676  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-22 03:01:24.677  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 03:01:24.677  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-22 03:01:24.677  5466  5512 D BluetoothAdapter: STATE_ON
,09-22 03:01:24.680  5707  5747 D BtGatt.GattService: registerClient() - UUID=5d5791b8-e454-4aae-9364-e0c28c3ccc0d
,09-22 03:01:24.681  5707  5723 D BtGatt.GattService: onClientRegistered() - UUID=5d5791b8-e454-4aae-9364-e0c28c3ccc0d, clientIf=5
,09-22 03:01:24.682  5466  5477 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-22 03:01:24.683  5707  5717 D BtGatt.GattService: start scan with filters
,09-22 03:01:24.687  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-22 03:01:24.687  5707  5726 D BtGatt.ScanManager: handling starting scan
09-22 03:01:24.687  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 03:01:24.687  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 03:01:24.687  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 03:01:24.688  5707  5726 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6237c34
,09-22 03:01:24.690  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 03:01:24.690  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 03:01:24.690  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 03:01:24.692  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 03:01:24.694  5707  5723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-22 03:01:24.694  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.695  5707  5726 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 03:01:24.696  5466  5512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-22 03:01:24.696  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:24.696  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-22 03:01:24.696  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.696  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 03:01:24.696  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-22 03:01:24.696  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 03:01:24.696  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 03:01:24.696  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 03:01:24.696  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 03:01:24.696  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-22 03:01:24.697  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:24.697  5707  5747 D BtGatt.GattService: stopScan() - queue size =1
09-22 03:01:24.698  5707  5717 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 03:01:24.698  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-22 03:01:24.698  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-22 03:01:24.698  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 03:01:24.699  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 03:01:24.699  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-22 03:01:24.700  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:24.700  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 03:01:24.700  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 03:01:24.700  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 03:01:24.700  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-22 03:01:24.702  5707  5723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 03:01:24.702  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 03:01:24.702  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 03:01:24.702  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:24.702  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:24.702  5707  5726 D BtGatt.ScanManager: Starting BLE batch scan
09-22 03:01:24.702  5707  5726 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-22 03:01:24.705  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 03:01:24.705  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:24.705  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:24.705  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.705  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.705  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:24.705  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.705  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8de4990 removed from the list
09-22 03:01:24.705  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.705  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66f6289 removed from the list
09-22 03:01:24.705  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:24.705  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.706  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.706  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.707  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.707  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.707  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.707  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66f6289 not in the list
,09-22 03:01:24.707  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.707  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.708  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.708  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.708  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.708  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d066ebc removed from the list
09-22 03:01:24.708  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.708  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.708  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.708  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.708  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@583eaaf removed from the list
09-22 03:01:24.709  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.709  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@529baa8 added. We now have 2 listener(s)
09-22 03:01:24.710  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.710  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:24.710  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-22 03:01:24.710  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.711  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f93d9c1 added. We now have 9 listener(s)
09-22 03:01:24.711  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.712  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 03:01:24.712  5707  5723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 03:01:24.713  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.714  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:24.717  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:24.718  5707  5723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 03:01:24.718  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.718  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:24.718  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:24.718  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.718  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a080a7 added. We now have 3 listener(s)
,09-22 03:01:24.719  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.719  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.719  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:24.719  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.720  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.720  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3d954 added. We now have 10 listener(s)
09-22 03:01:24.720  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.720  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 03:01:24.721  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 03:01:24.721  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 03:01:24.721  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.721  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 03:01:24.721  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:24.721  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-22 03:01:24.724  5707  5723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 03:01:24.724  5466  5512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 03:01:24.725  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-22 03:01:24.725  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.725  5707  5726 D BtGatt.ScanManager: stopping BLe Batch
,09-22 03:01:24.728  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-22 03:01:24.729  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-22 03:01:24.729  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-22 03:01:24.730  5707  5723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 03:01:24.730  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.730  5707  5726 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 03:01:24.732  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 03:01:24.732  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 03:01:24.732  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 03:01:24.733  5466  5512 D BluetoothAdapter: STATE_ON
,09-22 03:01:24.735  5707  5747 D BtGatt.GattService: registerClient() - UUID=a8cc2693-4863-4212-a48b-9ce40d70b980
09-22 03:01:24.735  5707  5723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-22 03:01:24.735  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 03:01:24.735  5707  5723 D BtGatt.GattService: onClientRegistered() - UUID=a8cc2693-4863-4212-a48b-9ce40d70b980, clientIf=5
09-22 03:01:24.736  5466  5563 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 03:01:24.736  5707  5745 D BtGatt.GattService: start scan with filters
,09-22 03:01:24.738  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-22 03:01:24.738  5707  5726 D BtGatt.ScanManager: handling starting scan
09-22 03:01:24.738  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 03:01:24.738  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 03:01:24.738  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 03:01:24.740  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:24.740  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 03:01:24.740  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 03:01:24.741  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-22 03:01:24.744  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-22 03:01:24.744  5466  5512 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-22 03:01:24.744  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:24.744  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:24.744  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:24.744  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-22 03:01:24.744  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.744  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 03:01:24.745  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.745  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@529baa8 removed from the list
09-22 03:01:24.745  5707  5723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 03:01:24.745  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.745  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 03:01:24.745  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f93d9c1 removed from the list
09-22 03:01:24.745  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:24.745  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:24.745  5707  5726 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-22 03:01:24.745  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.745  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 03:01:24.745  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-22 03:01:24.745  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:24.747  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.747  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.747  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.747  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f93d9c1 not in the list
09-22 03:01:24.747  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 03:01:24.748  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-22 03:01:24.748  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 03:01:24.748  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 03:01:24.748  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 03:01:24.748  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:24.749  5707  5745 D BtGatt.GattService: stopScan() - queue size =1
09-22 03:01:24.749  5707  5746 D BtGatt.GattService: unregisterClient() - clientIf=5
09-22 03:01:24.749  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 03:01:24.749  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 03:01:24.750  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 03:01:24.750  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-22 03:01:24.750  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 03:01:24.750  5707  5723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-22 03:01:24.750  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 03:01:24.751  5707  5726 D BtGatt.ScanManager: Starting BLE batch scan
,09-22 03:01:24.751  5707  5726 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 03:01:24.751  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:24.751  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 03:01:24.751  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 03:01:24.752  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 03:01:24.752  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.753  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.753  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.754  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.754  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-22 03:01:24.754  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:24.754  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3d954 removed from the list
09-22 03:01:24.754  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:24.754  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.754  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.754  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.754  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.754  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6a080a7 removed from the list
09-22 03:01:24.755  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.755  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1f36c0 added. We now have 2 listener(s)
09-22 03:01:24.756  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.757  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:24.757  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.757  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.757  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@478fff9 added. We now have 9 listener(s)
09-22 03:01:24.757  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-22 03:01:24.758  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 03:01:24.759  5707  5723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-22 03:01:24.759  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 03:01:24.760  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:24.763  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:24.764  5707  5723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 03:01:24.764  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.764  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:24.765  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:24.765  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.765  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10add9f added. We now have 3 listener(s)
09-22 03:01:24.766  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.766  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:24.766  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.766  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.766  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@920feec added. We now have 10 listener(s)
,09-22 03:01:24.766  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.766  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 03:01:24.766  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-22 03:01:24.766  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-22 03:01:24.766  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-22 03:01:24.766  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-22 03:01:24.767  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.768  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.769  5707  5723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-22 03:01:24.769  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.769  5707  5726 D BtGatt.ScanManager: stopping BLe Batch
09-22 03:01:24.770  5466  5512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-22 03:01:24.770  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-22 03:01:24.774  5707  5723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-22 03:01:24.774  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-22 03:01:24.774  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.774  5707  5726 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-22 03:01:24.774  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-22 03:01:24.774  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-22 03:01:24.777  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-22 03:01:24.777  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-22 03:01:24.777  5466  5512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-22 03:01:24.778  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:24.778  5707  5723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-22 03:01:24.778  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 03:01:24.779  5707  5746 D BtGatt.GattService: registerClient() - UUID=b2f0b294-a0c4-495b-80fd-0f398c1b728c
09-22 03:01:24.779  5707  5723 D BtGatt.GattService: onClientRegistered() - UUID=b2f0b294-a0c4-495b-80fd-0f398c1b728c, clientIf=5
,09-22 03:01:24.780  5466  5563 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-22 03:01:24.780  5707  5717 D BtGatt.GattService: start scan with filters
,09-22 03:01:24.782  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-22 03:01:24.782  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-22 03:01:24.782  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-22 03:01:24.782  5707  5726 D BtGatt.ScanManager: handling starting scan
09-22 03:01:24.782  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-22 03:01:24.784  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-22 03:01:24.784  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-22 03:01:24.784  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-22 03:01:24.785  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-22 03:01:24.787  5707  5723 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-22 03:01:24.787  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.787  5707  5726 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-22 03:01:24.790  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-22 03:01:24.790  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:24.790  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:24.790  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.790  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.790  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-22 03:01:24.791  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.791  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c1f36c0 removed from the list
09-22 03:01:24.791  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.791  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@478fff9 removed from the list
09-22 03:01:24.791  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:24.791  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:24.791  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.791  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-22 03:01:24.791  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.791  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:24.791  5707  5723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-22 03:01:24.791  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.791  5707  5726 D BtGatt.ScanManager: Starting BLE batch scan
09-22 03:01:24.791  5707  5726 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-22 03:01:24.792  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.792  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.792  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.792  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@478fff9 not in the list
09-22 03:01:24.792  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-22 03:01:24.792  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-22 03:01:24.792  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-22 03:01:24.792  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-22 03:01:24.792  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-22 03:01:24.793  5466  5512 D BluetoothAdapter: STATE_ON
09-22 03:01:24.794  5707  5718 D BtGatt.GattService: stopScan() - queue size =1
09-22 03:01:24.794  5707  5747 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-22 03:01:24.795  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-22 03:01:24.795  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-22 03:01:24.795  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-22 03:01:24.795  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-22 03:01:24.795  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-22 03:01:24.796  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:24.796  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-22 03:01:24.796  5466  5512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-22 03:01:24.796  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-22 03:01:24.797  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 03:01:24.800  5707  5723 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-22 03:01:24.800  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-22 03:01:24.800  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.800  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.800  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.800  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@920feec removed from the list
,09-22 03:01:24.800  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.800  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:24.800  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.801  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.801  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.801  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10add9f removed from the list
09-22 03:01:24.801  5466  5466 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-22 03:01:24.801  5466  5466 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-22 03:01:24.801  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.801  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1951dd8 added. We now have 2 listener(s)
,09-22 03:01:24.802  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.802  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:24.802  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.802  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.802  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a5b531 added. We now have 9 listener(s)
09-22 03:01:24.802  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.803  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-22 03:01:24.805  5707  5723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-22 03:01:24.805  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.805  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-22 03:01:24.809  5466  5512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-22 03:01:24.811  5707  5723 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-22 03:01:24.811  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.811  5707  5726 D BtGatt.ScanManager: stopping BLe Batch
09-22 03:01:24.811  5466  5512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-22 03:01:24.811  5466  5512 D io.jxcore.node.ConnectivityMonitor: start: OK
09-22 03:01:24.812  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-22 03:01:24.812  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d4e197 added. We now have 3 listener(s)
09-22 03:01:24.812  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-22 03:01:24.813  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-22 03:01:24.813  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-22 03:01:24.813  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-22 03:01:24.814  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-22 03:01:24.814  5466  5466 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-22 03:01:24.814  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2a3f84 added. We now have 10 listener(s)
09-22 03:01:24.814  5466  5512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-22 03:01:24.814  5466  5512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-22 03:01:24.814  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-22 03:01:24.814  5466  5512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-22 03:01:24.814  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.814  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.814  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-22 03:01:24.815  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.815  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1951dd8 removed from the list
09-22 03:01:24.815  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.815  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a5b531 removed from the list
09-22 03:01:24.815  5466  5512 D io.jxcore.node.ConnectivityMonitor: stop
09-22 03:01:24.815  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 03:01:24.815  5707  5723 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-22 03:01:24.815  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.815  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.816  5707  5726 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-22 03:01:24.816  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-22 03:01:24.817  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.817  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.817  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.817  5466  5512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a5b531 not in the list
09-22 03:01:24.817  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.817  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.818  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-22 03:01:24.818  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-22 03:01:24.818  5466  5512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-22 03:01:24.819  5466  5512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2a3f84 removed from the list
,09-22 03:01:24.819  5466  5512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-22 03:01:24.819  5466  5512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-22 03:01:24.819  5466  5512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-22 03:01:24.819  5466  5512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-22 03:01:24.819  5466  5512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d4e197 removed from the list
,09-22 03:01:24.820  5707  5723 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-22 03:01:24.820  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-22 03:01:24.820  5707  5723 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-22 03:01:24.820  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-22 03:01:24.820  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-22 03:01:24.820  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-22 03:01:24.820  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-22 03:01:24.821  5466  5512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-22 03:01:24.826  5466  5765 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name)
,09-22 03:01:24.826  5466  5765 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: My test thread name)
09-22 03:01:24.826  5466  5765 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-22 03:01:24.827  5466  5766 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name)
09-22 03:01:24.827  5466  5766 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name)
09-22 03:01:24.828  5466  5766 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-22 03:01:24.829  5466  5512 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-22 03:01:24.829  5466  5512 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-22 03:01:24.829  5466  5512 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-22 03:01:24.829  5466  5512 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-22 03:01:24.829  5466  5512 D com.test.thalitest.ThaliTestRunner: Total duration: 22570 ms
,09-22 03:01:24.831  5466  5512 I jxcore-log: *Native tests were executed*
09-22 03:01:24.831  5466  5512 I jxcore-log: 
,09-22 03:01:24.831  5466  5512 I jxcore-log: Total number of executed tests:  80
09-22 03:01:24.831  5466  5512 I jxcore-log: 
09-22 03:01:24.831  5466  5512 I jxcore-log: Number of passed tests:  80
09-22 03:01:24.831  5466  5512 I jxcore-log: 
09-22 03:01:24.831  5466  5512 I jxcore-log: Number of failed tests:  0
09-22 03:01:24.831  5466  5512 I jxcore-log: 
09-22 03:01:24.831  5466  5512 I jxcore-log: Number of ignored tests:  0
09-22 03:01:24.831  5466  5512 I jxcore-log: 
09-22 03:01:24.832  5466  5512 I jxcore-log: Total duration:  22570
09-22 03:01:24.832  5466  5512 I jxcore-log: 
09-22 03:01:24.832  5466  5512 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-22 03:01:24.832  5466  5512 I jxcore-log: 
,09-22 03:01:24.835  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 03:01:24.835  5466  5512 I jxcore-log: 
09-22 03:01:24.837  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 03:01:24.837  5466  5512 I jxcore-log: 
09-22 03:01:24.838  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 03:01:24.838  5466  5512 I jxcore-log: 
09-22 03:01:24.839  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 03:01:24.839  5466  5512 I jxcore-log: 
09-22 03:01:24.841  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 03:01:24.841  5466  5512 I jxcore-log: 
09-22 03:01:24.842  5466  5466 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-22 03:01:24.842  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 03:01:24.842  5466  5512 I jxcore-log: 
09-22 03:01:24.845  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.845  5466  5512 I jxcore-log: 
09-22 03:01:24.846  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-22 03:01:24.846  5466  5512 I jxcore-log: 
09-22 03:01:24.847  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.847  5466  5512 I jxcore-log: 
09-22 03:01:24.848  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.848  5466  5512 I jxcore-log: 
09-22 03:01:24.849  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.849  5466  5512 I jxcore-log: 
09-22 03:01:24.850  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 03:01:24.850  5466  5512 I jxcore-log: 
09-22 03:01:24.851  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.851  5466  5512 I jxcore-log: 
09-22 03:01:24.852  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.852  5466  5512 I jxcore-log: 
09-22 03:01:24.852  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.852  5466  5512 I jxcore-log: 
09-22 03:01:24.853  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.853  5466  5512 I jxcore-log: 
09-22 03:01:24.854  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.854  5466  5512 I jxcore-log: 
09-22 03:01:24.854  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.854  5466  5512 I jxcore-log: 
09-22 03:01:24.855  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.855  5466  5512 I jxcore-log: 
09-22 03:01:24.856  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.856  5466  5512 I jxcore-log: 
,09-22 03:01:24.856  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.856  5466  5512 I jxcore-log: 
09-22 03:01:24.857  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-22 03:01:24.857  5466  5512 I jxcore-log: 
,09-22 03:01:24.857  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.857  5466  5512 I jxcore-log: 
,09-22 03:01:24.858  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.858  5466  5512 I jxcore-log: 
09-22 03:01:24.859  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.859  5466  5512 I jxcore-log: 
,09-22 03:01:24.859  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.859  5466  5512 I jxcore-log: 
,09-22 03:01:24.860  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.860  5466  5512 I jxcore-log: 
,09-22 03:01:24.861  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.861  5466  5512 I jxcore-log: 
09-22 03:01:24.861  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-22 03:01:24.861  5466  5512 I jxcore-log: 
,09-22 03:01:25.203  5466  5466 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 03:01:25.206  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 03:01:25.206  5466  5512 I jxcore-log: 
,09-22 03:01:25.254  5466  5466 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 03:01:25.259  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 03:01:25.259  5466  5512 I jxcore-log: 
,09-22 03:01:25.269  5767  5767 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-22 03:01:25.275  5767  5767 D AndroidRuntime: CheckJNI is OFF
,09-22 03:01:25.301  5466  5466 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-22 03:01:25.304  5466  5512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-22 03:01:25.304  5466  5512 I jxcore-log: 
,09-22 03:01:25.305  5767  5767 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-22 03:01:25.337  5767  5767 I Radio-JNI: register_android_hardware_Radio DONE
,09-22 03:01:25.352  5767  5767 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-22 03:01:25.360   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-22 03:01:25.361   931   944 I ActivityManager: Killing 5466:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-22 03:01:25.437   931  2937 D WifiService: Client connection lost with reason: 4
09-22 03:01:25.437   931  3145 I WindowState: WIN DEATH: Window{3567fb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-22 03:01:25.437   931  3392 D GraphicsStats: Buffer count: 2
,09-22 03:01:25.498   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-22 03:01:25.498   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-22 03:01:25.498   931   954 I art     : Starting a blocking GC Explicit
,09-22 03:01:25.499   931   944 E ActivityManager: Failure starting process com.test.thalitest
09-22 03:01:25.499   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-22 03:01:25.499   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:25.499   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:25.499   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 03:01:25.499   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 03:01:25.500   931   944 I ActivityManager:   Force finishing activity ActivityRecord{5f1d34d u0 com.test.thalitest/.MainActivity t2}
,09-22 03:01:25.507   931  3565 W ActivityManager: Spurious death for ProcessRecord{a6fddac 0:com.test.thalitest/u0a77}, curProc for 5466: null
,09-22 03:01:25.511   931   949 W WindowManager: Attempted to add application window with unknown token Token{e69e02 ActivityRecord{5f1d34d u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-22 03:01:25.511   931   949 W WindowManager: Token{e69e02 ActivityRecord{5f1d34d u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{e69e02 ActivityRecord{5f1d34d u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-22 03:01:25.511   931   949 W WindowManager: view not successfully added to wm, removing view
09-22 03:01:25.512   931   949 W WindowManager: Exception when adding starting window
09-22 03:01:25.512   931   949 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{577b57 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-22 03:01:25.512   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-22 03:01:25.512   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-22 03:01:25.512   931   949 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-22 03:01:25.512   931   949 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-22 03:01:25.512   931   949 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-22 03:01:25.512   931   949 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:25.512   931   949 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:25.512   931   949 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-22 03:01:25.512   931   949 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-22 03:01:25.575   931   954 I art     : Explicit concurrent mark sweep GC freed 24623(1559KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.444ms total 76.251ms
,09-22 03:01:25.596   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-22 03:01:25.599  5767  5767 I art     : System.exit called, status: 0
,09-22 03:01:25.599  5767  5767 I AndroidRuntime: VM exiting with result code 0.
,09-22 03:01:25.614   931   954 I ActivityManager: Start proc 5777:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-22 03:01:25.614   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-22 03:01:25.619   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-22 03:01:25.624  5707  5707 D BluetoothMapAppObserver: onReceive
,09-22 03:01:25.625  5707  5707 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-22 03:01:25.626   931  2928 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-22 03:01:25.627  3410  3410 I Keyboard.Facilitator: resetDictionaries() : en_US
09-22 03:01:25.629  3450  3954 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-22 03:01:25.653  3516  3516 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-22 03:01:25.657  3396  5790 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-22 03:01:25.659  3410  5789 I Keyboard.Facilitator.DecoderInitializer: run()
,09-22 03:01:25.672  3410  5789 I Decoder : createOrResetDecoder
,09-22 03:01:25.700   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-22 03:01:25.710    27    27 W kworker/1:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 03:01:25.713    27    27 W kworker/1:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 03:01:25.725  3594  3594 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-22 03:01:25.726  3594  3594 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-22 03:01:25.727  3546  3687 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-22 03:01:25.733    27    27 W kworker/1:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-22 03:01:25.742   931  3592 I ActivityManager: Start proc 5796:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-22 03:01:25.742  3546  3687 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-22 03:01:25.742  3546  3687 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3546
09-22 03:01:25.742  3546  3687 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:25.742  3546  3687 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 03:01:25.748   931  3560 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 03:01:25.749   931  5804 E DropBoxManagerService: Can't write: system_app_crash
09-22 03:01:25.749   931  5804 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 03:01:25.749   931  5804 E DropBoxManagerService: 	... 5 more
,09-22 03:01:25.752  3546  3687 I Process : Sending signal. PID: 3546 SIG: 9
,09-22 03:01:25.757  3396  5790 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-22 03:01:25.759  3594  3594 I ConfigService: onCreate
,09-22 03:01:25.761  3915  5808 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-22 03:01:25.761  3915  5808 D AccountUtils: Clearing selected account for com.test.thalitest
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-22 03:01:25.763  3594  5810 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.content.ContextWrapper.,openOrCreateDatabase(ContextWrapper.java:269)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-22 03:01:25.763  3594  5810 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-22 03:01:25.766  3594  5810 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-22 03:01:25.778  3410  5789 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-22 03:01:25.790  3396  5790 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-22 03:01:25.790  3396  5790 E AndroidRuntime: Process: android.process.acore, PID: 3396
09-22 03:01:25.790  3396  5790 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:25.790  3396  5790 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-22 03:01:25.794   931  5814 E DropBoxManagerService: Can't write: system_app_crash
09-22 03:01:25.794   931  5814 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 03:01:25.794   931  5814 E DropBoxManagerService: 	... 5 more
,09-22 03:01:25.794  3396  5790 I Process : Sending signal. PID: 3396 SIG: 9
,09-22 03:01:25.846   931  3526 I WindowState: WIN DEATH: Window{94f377b u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-22 03:01:25.847   931  3537 D GraphicsStats: Buffer count: 1
,09-22 03:01:25.852   931  3592 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3546) has died
09-22 03:01:25.853   931  3592 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-22 03:01:25.854   931  3592 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 03:01:25.857   931   941 I ActivityManager: Process android.process.acore (pid 3396) has died
09-22 03:01:25.858   931   941 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-22 03:01:25.871   931   944 I ActivityManager: Start proc 5816:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 03:01:25.917  5816  5816 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:25.917  5816  5816 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 03:01:25.917  5816  5816 D AndroidRuntime: Shutting down VM
,09-22 03:01:25.925  5816  5816 E AndroidRuntime: FATAL EXCEPTION: main
09-22 03:01:25.925  5816  5816 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5816
09-22 03:01:25.925  5816  5816 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 03:01:25.925  5816  5816 E AndroidRuntime: 	... 10 more
,09-22 03:01:25.928   931   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 03:01:25.928   931  5829 E DropBoxManagerService: Can't write: system_app_crash
09-22 03:01:25.928   931  5829 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 03:01:25.928   931  5829 E DropBoxManagerService: 	... 5 more
09-22 03:01:25.928  5816  5816 I Process : Sending signal. PID: 5816 SIG: 9
,09-22 03:01:25.943   931   942 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5816) has died
,09-22 03:01:25.945   931   942 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 03:01:25.960   931   944 I ActivityManager: Start proc 5830:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 03:01:26.011  5830  5830 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:26.011  5830  5830 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-22 03:01:26.011  5830  5830 D AndroidRuntime: Shutting down VM
,09-22 03:01:26.018  5830  5830 E AndroidRuntime: FATAL EXCEPTION: main
09-22 03:01:26.018  5830  5830 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5830
09-22 03:01:26.018  5830  5830 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-22 03:01:26.018  5830  5830 E AndroidRuntime: 	... 10 more
,09-22 03:01:26.021   931  3392 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 03:01:26.021   931  5842 E DropBoxManagerService: Can't write: system_app_crash
09-22 03:01:26.021   931  5842 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-22 03:01:26.021   931  5842 E DropBoxManagerService: 	... 5 more
09-22 03:01:26.022  5830  5830 I Process : Sending signal. PID: 5830 SIG: 9
,09-22 03:01:26.038   931  3592 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5830) has died
09-22 03:01:26.039   931  3592 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-22 03:01:26.055   931   944 I ActivityManager: Start proc 5843:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-22 03:01:26.100   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
